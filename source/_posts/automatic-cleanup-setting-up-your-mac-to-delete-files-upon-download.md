---
title: "Automatic Cleanup: Setting Up Your Mac to Delete Files Upon Download"
date: 2024-08-26 14:48:57
updated: 2024-08-29 10:52:50
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/38deee1fec1c0bec7cba4dcb61a1033e4c5fd684f75205d6b2dd2ff58f0ec205.jpg
---

## Automatic Cleanup: Setting Up Your Mac to Delete Files Upon Download

### Key Takeaways

* Use Automator to create a Folder Action that automatically deletes old files in your Downloads folder.
* Customize when your files are deleted based on their age, such as those more than a week or month old.
* The action runs automatically whenever you download new files. It keeps the Downloads folder free from clutter without you needing to do anything.

 If you download a lot of files on your Mac, you'll need to delete the ones you no longer need regularly to avoid congesting your Downloads folder. Doing this manually can be a tedious task. Thankfully, there's a way to automate it. Let's show you how.

##  How to Create a Folder Action in Automator to Delete Downloads Automatically

 Apple ships the Automator app with macOS on all its Macs. With Automator, you can [automate repetitive tasks on your Mac](https://win-dash.techidaily.com/amd-ryzen-5-2600-driver-download-fast-simple-steps/), so you don't have to perform them manually.

 Automator supports multiple types of tasks. However, what we need for this guide is the Folder Action automation, which triggers an action every time there's a change to a specified folder. In our case, the Folder Action will automatically delete from the Downloads folder all files and folders that are more than seven days old whenever new ones get added.

###  Set Up a Folder Action

 To create the Folder Action, start by launching the Automator app on your Mac. When it asks you to choose a document type, click on "Folder Action" and hit "Choose."

![Choosing document type in Automator app on a Mac.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-1.jpg) 

 Look for a dropdown box in the rightmost pane at the top of the screen. It'll appear next to the text "Folder Action receives files and folders added to." Click on it and select "Other." Then, select the "Downloads" folder in the Finder and hit "Choose."

![Choosing a folder to perform action on in Automator app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-2.jpg) 

###  Find the Files to Delete

 There are two ways to find your files and folders in the Downloads folder. The first method uses the "Filter Finder Items" action, whereas the second takes advantage of the "Run Shell Script" action. We'll be using the latter, as the former doesn't work as expected and fails to return the right files and folders.

 Click the search box in the middle pane and look for "Run Shell Script." Drag this action to the right-hand pane to add it to the workflow.

![Adding the Run Shell Script action to the workflow in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-4.jpg) 

 On this action, click the dropdown button next to "Shell" and select the "/bin/bash" option.

![Setting the default shell to bash in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-5.jpg) 

 In the text box below that, enter the following command:

find "[path to Downloads directory]/Downloads" -ctime +7d -o -mtime +7d -iname '*.*'

 The command looks for files created ("-ctime") or modified ("-mtime") more than seven days ago ("+7d"). You can change it to whatever time frame you like. For example, changing the "-ctime" figure to "+30d" would only delete files downloaded more than a month ago.

 You also need to replace \[path to Downloads directory\] with the path to the Downloads folder on your Mac. To find the path, open Finder, right-click on "Downloads" in the left sidebar, and select "Get Info."

 On the Downloads Info window that opens, expand the "General" section by clicking the arrow button before it.

![Expanding the General tab to view the path of Downloads folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-10-1.jpg) 

 Right-click on the address next to "Where," and select "Copy as Pathname."

![Copying the path of Downloads folder on Mac.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-11.jpg) 

 Finally, paste it into the command in Automator. Remember to ensure that /Downloads is on the end of the path. Now, click the "Run" button in the Automator window to run the workflow.

![Running the Folder Action workflow to verify if the Run Shell Script action returns right files and folders.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-8.jpg) 

 If you did everything correctly, it'll return all the files and folders in the Downloads folder that meet your criteria. You can look at the results by clicking the "Results" tab on the Run Shell Script action.

![Run Shell Scription action results.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-7.jpg) 

###  Auto-Delete the Files

 If you're happy that it's working, proceed to add the final action to the workflow. Search for "Move Finder Items to Trash" or "Move Finder Items to Bin" in the search box on the middle pane and drag it to the workflow area below the Run Shell Script action such that the two are linked.

 Finally, click on File > Save or press Command+S. Then, name the Folder Action and click "Save." macOS saves all your Automator Folder Actions under the "\~/Library/Workflows/Applications/Folder Actions/" path.

![Saving a Folder Action workflow in Automator.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/automatically-delete-downloads-on-a-mac-9.jpg) 

 Now, any time you add new files to your Downloads folder, the existing files that are more than a week old will be automatically moved to the trash.

##  Keep Your Trash Decluttered as Well

 As the above Folder Action workflow moves files and folders from your Mac's Downloads folder into the Trash, your Trash will likely end up with a lot of unused files and folders, and will still eat up your Mac's storage space. However, you can avoid this by automatically emptying your Trash every 30 days.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
