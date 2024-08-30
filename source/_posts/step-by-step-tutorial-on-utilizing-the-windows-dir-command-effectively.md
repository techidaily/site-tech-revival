---
title: Step-by-Step Tutorial on Utilizing the Windows DIR Command Effectively
date: 2024-08-28 13:22:43
updated: 2024-08-29 10:47:28
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/52880885757_aff84061b0_o-2.jpg
---

## Step-by-Step Tutorial on Utilizing the Windows DIR Command Effectively

### Quick Links

* [What is DIR?](https://extra-lessons.techidaily.com/in-2024-audible-illusion-how-does-this-voice-change-application-work-alternatives-awaits/)
* [DIR Command Switches](https://some-techniques.techidaily.com/updated-gently-unveiled-scene/)
* [Display Files Based on File Attributes with DIR](https://screen-mirroring-recording.techidaily.com/in-2024-navigating-the-nuances-of-streaming-and-saving-on-facebook/)
* [Display Stripped Results](https://extra-resources.techidaily.com/dji-inspire-2-complete-evaluation/)
* [Display Using Thousands Separator](https://extra-skills.techidaily.com/updated-scheduling-virtual-gatherings-with-zoom-an-android-users-handbook/)
* [Display Results in Columns](https://tech-revival.techidaily.com/can-algorithms-craft-humor-understanding-ais-comedy-abilities-plus-unveiling-the-developmental-story-of-laptops-and-the-role-of-vpn-in-cybersecurity/)
* [Display DIR Results in Lowercase](https://extra-approaches.techidaily.com/new-legal-chants-for-clarity-top-10-downloads-guide/)
* [Display Filename Results on the Far Right](https://win-answers.techidaily.com/mastering-mw-warzone-effective-strategies-to-fix-the-persistent-error-6068/)
* [Display Results in Sorted Order](https://facebook-video-recording.techidaily.com/how-to-play-facebook-videos-on-tv-in-2024/)
* [Display Results One Page at a Time](https://tech-haven.techidaily.com/explore-these-free-options-the-best-alternatives-to-openais-sora/)
* [Display File Metadata with DIR](https://facebook-videos.techidaily.com/2024-approved-engaging-viewers-with-unique-square-videography-techniques/)
* [Display Alternate Data Streams (ADS)](https://www.howtogeek.com/363639/how-to-use-the-dir-command-in-windows/#display-alternate-data-streams-ads)
* [Display All Files and Folders and Everything Inside](https://solve-latest.techidaily.com/boost-your-site-with-cookiebots-advanced-tracking-technology/)
* [Display Results from DIR Sorted by Time](https://easy-unlock-android.techidaily.com/the-ultimate-guide-to-nokia-c22-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/)
* [Display DIR's Results in Wide Format](https://digital-screen-recording.techidaily.com/updated-relaxation-reigns-top-pc-titles/)
* [Display Short Name Filenames](https://on-screen-recording.techidaily.com/1716069583771-updated-in-2024-xbox-game-memories-save-them-with-screenshots/)
* [Display Help Pages For DIR](https://buynow-tips.techidaily.com/top-5-exterior-blu-ray-dvd-burners-a-comprehensive-guide/)
* [DIR Command Examples](https://youtube-zero.techidaily.com/024-approved-navigating-youtube-skip-the-top-8-novice-missteps/)

### Key Takeaways

* The dir command can be used in Command Prompt or PowerShell. It lists files and subdirectories in a specific directory.
* dir can take dozens of different switches to customize the output to display more concise or relevant information.
* Use switch /A followed by a letter code to display files with specific attributes, such as directories, hidden files, or read-only files.

 Run “dir” in Command Prompt to list all of the files and folders in the current directory. Dir also take special arguments to sort and select what kinds of files and folders are displayed. For example, “dir /h” will display hidden files.

##  What is DIR?

 The DIR command is a powerful Windows Command Prompt function that lists all files and subdirectories contained in a specific directory. The DIR command also offers some switches that unlock some powerful functionality.

##  DIR Command Switches

 You can use the `DIR` command by itself (just type "dir" at the Command Prompt) to list the files and folders in the current directory. To extend that functionality, you need to use the various switches, or options, associated with the command. We've compiled a list of some of the most useful dir switches, with examples.

##  Display Files Based on File Attributes with DIR

 You can add "/A" followed by a letter code after the DIR command to display files with a specific attribute. These letter codes include:

* **D:** Displays all directories in the current path
* **R:** Displays read-only files
* **H:** Displays hidden files
* **A:** Files that are ready for archiving
* **S:** System files
* **I:** Not content indexed files
* **L:** Reparse points

 So, for example, to display just the directories in the current path, you'd type the following command and then hit Enter:

dir /ad

 You can combine those codes, too. For example, if you wanted to show only system files that are also hidden, you could use the following command:

dir /ash

 You also can add a "-" (minus) in front of any of those letter codes to specify that the DIR command does not show that kind of file. So, for example, if you don't want to see any directories in the results, you could use this command:

dir /a-d

 One more tip: Instead of cramming the main switch and the letter code together the way we did in our examples, you can use a colon to separate the switch from its optional codes. Like this:

dir /a:d

 It can make things a little easier to parse, but it's entirely optional.

##  Display Stripped Results

![Command Prompt with dir /b output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-09-10.png) 

 Using the `/b` switch with the DIR command strips away all excess information, displaying only the name of the folders and files in the current directory and not attributes like file size and time stamps. Type the following command to make it work:

dir /b

##  Display Using Thousands Separator

 In modern versions of Windows, the Command Prompt shows large numbers separated by commas (so: 25,000 instead of 25000). This wasn't always the case. In older versions, you had to use the `/c` switch to show those commas.

 Why bother including it here if it's already the default? Because if for whatever reason you don't want to show those commas, you can use this switch along with the "-" minus sign:

dir /-c

##  Display Results in Columns

![Command Prompt with dir /b output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-09-10.png) 

 You can use the `/D` switch to display results in two columns instead of one. When you display results this way, the Command Prompt does not show extra file information (file size and so on)---just the names of the files and directories.

dir /D

##  Display DIR Results in Lowercase

 The `/L` switch displays all names of files and folders as lowercase.

dir /L

##  Display Filename Results on the Far Right

![Command Prompt with dir /b output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-09-10.png) 

 By default, the Command Prompt displays the names of files to the far right. The `/N` switch used to be used to achieve this effect. Now, you can use it along with a "-" (minus) to have filenames displayed on the far left instead.

dir /-N

##  Display Results in Sorted Order

 You can use the `/O` switch followed by a letter code to display directory results sorted in various ways. Those letter codes include:

* **D:** Sorts by date/time. Older entries appear first.
* **E:** Sorts by file extension in alphabetical order.
* **G:** Sorts by listing folders first, then files.
* **N:** Sorts by the name of file/folder in alphabetical order.
* **S:** Sorts by file size, smallest to largest.

 So, for example, you could use the following command to sort results by time and date, with older entries appearing first:

dir /OD

 You can also add "-" (minus) before any of the above options to reverse the order. So, for example, if you want to sort files by time and date with newer entries appearing first, you could use this command:

dir /O-D

##  Display Results One Page at a Time

![Command Prompt with dir /b output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-09-10.png) 

 Some directories have hundreds or thousands of files. You can use the `/P` switch to have the Command Prompt pause the results after it displays each screen. You have to press a key to continue viewing the next page of results.

dir /P

##  Display File Metadata with DIR

![Command Prompt with dir /b output.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-09-10.png) 

 Using the `/Q` switch on the DIR command displays metadata tied to files and directories, along with ownership details.

dir /Q

##  Display Alternate Data Streams (ADS)

 The `/R` switch displays any alternate data streams (ADS) that files might contain. ADS are a feature of the NTFS file system that let files contain additional metadata for locating files by author and title.

dir /R

##  Display All Files and Folders and Everything Inside

 You can use the `/S` switch to recursively show all files and folders inside the current directory. This means all files and folders in every subdirectory, all files and folders in those subdirectories, and so on. Be prepared for a lot of results.

dir /S

##  Display Results from DIR Sorted by Time

 Using the `/T` switch along with a letter code lets you sort results by the different time stamps associated with files and folders. These letter codes include:

* **A:** The time the item was last accessed.
* **C:** The time the item was created.
* **W:** The time the item was last written to. This is the default option used.

 So, for example, to sort results by the time items were created, you could use the following command:

dir /TC

##  Display DIR's Results in Wide Format

 The `/W` switch is similar to `/D` (which shows columns), but instead, it sorts the results in wide format horizontally.

dir /W

##  Display Short Name Filenames

 The `/X` switch shows a file's short name when the long name doesn't comply with 8.3 naming rules.

dir /X

##  Display Help Pages For DIR

 Using the `/?` switch displays helpful information regarding the DIR command, including a brief description of all the switches we've talked about.

![The help page for the dir command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-23_15h28_08.png) 

##  DIR Command Examples

 All right, now you know about the switches and options associated with the DIR command. Let's take a look at a few real-world examples to gain a better understanding as to how you can start putting them to use.

 A simple `dir` command returns a list of all files and folders in the current directory you're in.

![Command Prompt with dir run in the C:\ directory.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-24_11h26_03.png) 

 Running the following command shows all system files inside your current path by utilizing the "s" attribute:

dir /a:s

![Command prompt with dir /a:s run in C:\ displaying the system files.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-24_12h54_12.png) 

 But what if you want to view all files of a certain type within all subsequent folders of your current path. That's easy, just run this extremely fast and useful command:

dir \*.mp3 /s

 You can replace the ".mp3" part with whatever file format you're looking for.

![Command Prompt with dir \*.mp3 /s run to display only MP3 files.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-24_12h01_41.png) 

[The asterisk acts as a wildcard](https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s24plus-phone-password-without-factory-reset-by-drfone-android/), saying "find anything with .mp3 file format at the end" while the "/s" recursively looks through all folders within your current path.

 Now, you may have noticed that returned a LOT of results. Almost too many to be able to read before they scrolled off the screen. This is where we can use the pause switch to give you a chance to read them. To do that, modify the command like this:

dir \*.mp3 /s /p

![Command Prompt with dir \*.mp3 /s /p run to pause the list of MP3 files.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-24_12h08_30.png) 

 Another trick the Command Prompt offers is called piping. You can use the ">" character to send the results of one command to another place or service. A good example of this is [sending all your results to a text file](https://extra-resources.techidaily.com/affordable-gopros-where-to-buy-with-best-price-for-2024/). You can then scroll through them later or import them into other types of documents. To do that, you could use the command:

dir \*.mp3 /s /b > filename.txt

![Add &quot;&gt; audio.txt&quot; to output the results to a text file named &quot;Audio.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/08/2018-08-24_12h29_46.png) 

 We added the `/b` switch in there to only output the filenames themselves, without any of the other details. The greater than symbol reroutes everything normally displayed in your results directly to the file.

 There are many more combinations and uses for the DIR command, but this should be a good starting point to help you understand the basics.

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
