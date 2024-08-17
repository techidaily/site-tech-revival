---
title: Vital Upgrades to Transform ChatGPT Plugins Store Dynamics
date: 2024-08-16T13:44:33.455Z
updated: 2024-08-17T13:44:33.455Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Vital Upgrades to Transform ChatGPT Plugins Store Dynamics
excerpt: This Article Describes Vital Upgrades to Transform ChatGPT Plugins Store Dynamics
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## Why Provide ChatGPT with Custom Data?

 Feeding ChatGPT with custom data and providing updated information beyond its knowledge cutoff date provides several benefits over just using ChatGPT as usual. Here are a few of them:

* **Personalized Interactions:** By providing ChatGPT with custom data, users can create a more customized experience. The model can be trained on specific datasets relevant to individual users or organizations, resulting in responses tailored to their unique needs and preferences.
* **Domain-Specific Expertise:** Custom data integration allows ChatGPT to specialize in particular domains or industries. It can be trained on industry-specific knowledge, terminology, and trends, enabling more accurate and insightful responses within those specific areas.
* **Current and Accurate Information:** Access to updated information ensures that ChatGPT stays current with the latest developments and knowledge. It can provide accurate responses based on recent events, news, or research, making it a more reliable source of information.

 Now that you understand the importance of providing custom data to ChatGPT, here's a step-by-step on how to do so on your local computer.

## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

## Custom ChatGPT Is Awesome But Limited

 Providing custom data to ChatGPT is a powerful way to get more out of the model. Through this method, you can feed the model with any text data you want and prompt it just like regular ChatGPT, albeit with some limitations. However, this will change in the future as it becomes easier to integrate our data with the LLM, along with access to the latest GPT-4 model.


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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-automate-calendar-events-to-zoom-on-mobile-devices-for-2024/"><u>[New] Automate Calendar Events to Zoom on Mobile Devices for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-guide-to-cutting-edge-online-streaming-via-vlc-media-player/"><u>[New] Expert Guide to Cutting-Edge Online Streaming via VLC Media Player</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-high-end-cameras-for-stunning-4k-content-top-18/"><u>[New] High-End Cameras for Stunning 4K Content (Top 18)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-navigating-the-best-freefire-tips-online/"><u>[New] Navigating the Best FreeFire Tips Online</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-screen-savers-review-cutting-edge-video-gadgets-for-2024/"><u>[New] Screen Savers Review  Cutting-Edge Video Gadgets for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-a-comprehensive-guide-to-softening-images-with-iphone-software-for-2024/"><u>[Updated] A Comprehensive Guide to Softening Images with iPhone Software for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-from-basic-to-advanced-usage-maximize-your-experience-with-macs-preview/"><u>[Updated] From Basic to Advanced Usage  Maximize Your Experience with Mac's Preview</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-pro-video-enhancements-grasping-green-screen-artistry-through-4-youtube-demos/"><u>[Updated] Pro Video Enhancements  Grasping Green Screen Artistry Through 4 YouTube Demos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2022-ice-dancing-showcase-review/"><u>2022 Ice Dancing Showcase Review</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-screencasting-simplified-compreehd-step-by-step-guide/"><u>2024 Approved  Screencasting Simplified  Compreehd, Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-ethics-and-legal-responsibility/"><u>AI Ethics & Legal Responsibility</u></a></li>
<li><a href="https://tech-revival.techidaily.com/artificial-muse-reimagined-the-best-ai-writers-of-today/"><u>Artificial Muse Reimagined: The Best AI Writers of Today</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-visual-impact-learning-to-edit-videos-using-storyremix-and-windows-photos/"><u>Boost Visual Impact  Learning to Edit Videos Using StoryRemix and Windows Photos</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bring-your-mobile-experience-upgrade-with-bings-new-ai-search-feature-for-iosandroid-devices/"><u>Bring Your Mobile Experience Upgrade with Bing's New AI Search Feature for iOS/Android Devices!</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722188636644-chatgpt-takes-the-ios-stage/"><u>ChatGPT Takes the iOS Stage</u></a></li>
<li><a href="https://tech-revival.techidaily.com/could-ai-powered-chatgpt-become-a-tool-for-online-criminals-to-access-your-savings-or-devices/"><u>Could AI-Powered ChatGPT Become a Tool for Online Criminals to Access Your Savings or Devices?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-turing-test-can-machines-truly-mimic-human-intelligence/"><u>Decoding the Turing Test: Can Machines Truly Mimic Human Intelligence?</u></a></li>
<li><a href="https://win-blog.techidaily.com/defeating-path-of-exiles-crash-glitch-effective-strategies-for-smooth-gaming/"><u>Defeating Path of Exile's Crash Glitch: Effective Strategies for Smooth Gaming</u></a></li>
<li><a href="https://tech-revival.techidaily.com/desired-upgrades-for-chatgpt-plugin-marketplace-a-user-centric-perspective/"><u>Desired Upgrades for ChatGPT Plugin Marketplace: A User-Centric Perspective</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-leading-7-spaceships-selling-ai-generated-content/"><u>Discover the Leading 7 Spaceships Selling AI Generated Content</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effortless-installation-of-auto-gpt-for-ubuntu-enthusiasts-a-complete-guide/"><u>Effortless Installation of Auto-GPT for Ubuntu Enthusiasts - A Complete Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-one-language-to-another-utilizing-chatgpt-effectively/"><u>From One Language to Another: Utilizing ChatGPT Effectively</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722197368173-gpt-4-welcomes-everyone-despite-freedom-to-use-plus-continues-offering-6-superior-services/"><u>GPT-4 Welcomes Everyone: Despite Freedom to Use, Plus Continues Offering 6 Superior Services</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gptbot-explained-an-overview-of-the-cutting-edge-technology-and-its-online-barriers/"><u>GPTBot Explained - An Overview of the Cutting-Edge Technology and Its Online Barriers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guarding-against-imitations-of-chatgpt-apps/"><u>Guarding Against Imitations of ChatGPT Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-do-shared-links-in-chatgpt-enhance-user-interaction-unveiling-the-process/"><u>How Do Shared Links in ChatGPT Enhance User Interaction? Unveiling The Process</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-fact-check-health-information-from-chatgpt-and-ai-sources/"><u>How to Fact-Check Health Information From ChatGPT and AI Sources</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-7-plus-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 7 Plus Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-c33-2023-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Realme C33 2023 Phone Without Password?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-track-to-superior-srt-upgrades/"><u>In 2024, Inside Track to Superior SRT Upgrades</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-proven-tactics-increasing-your-instagram-video-traffic/"><u>In 2024, Proven Tactics  Increasing Your Instagram Video Traffic</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-asus-rog-phone-8-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Asus ROG Phone 8 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://tech-revival.techidaily.com/inside-chatgpts-world-generating-tomorrows-ideas-today/"><u>Inside ChatGPT's World: Generating Tomorrow’s Ideas Today</u></a></li>
<li><a href="https://tech-revival.techidaily.com/keeping-your-conversations-private-how-not-to-let-chatgpt-remember-them/"><u>Keeping Your Conversations Private: How Not to Let ChatGPT Remember Them</u></a></li>
<li><a href="https://tech-revival.techidaily.com/painting-with-purpose-mastering-ai-art-through-chatgpt/"><u>Painting with Purpose: Mastering AI Art Through ChatGPT</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/screen-saving-android-titles-a-curated-list-of-indoor-games-for-2024/"><u>Screen-Saving Android Titles  A Curated List of Indoor Games for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-contrast-between-auto-gpt-and-chatgpt-a-comprehensive-look-at-their-differences/"><u>The Contrast Between Auto-GPT & ChatGPT: A Comprehensive Look at Their Differences</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-game-changing-million-token-context-of-gemini-15/"><u>The Game-Changing Million Token Context of Gemini 1.5</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-walkthrough-of-bings-intelligent-assistant-on-android-phones/"><u>The Ultimate Walkthrough of Bing's Intelligent Assistant on Android Phones</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-infinix-zero-5g-2023-turbo-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Infinix Zero 5G 2023 Turbo Reset Code | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-ai-driven-counseling-bots-for-emotional-wellness/"><u>Top 5 AI-Driven Counseling Bots for Emotional Wellness</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-revolutionary-chatgpt-browser-add-ons-enhance-your-ai-conversations/"><u>Top 7 Revolutionary ChatGPT Browser Add-Ons: Enhance Your AI Conversations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-document-crafting-with-ai-using-chatgpt-to-enhance-your-microsoft-word-experience/"><u>Transform Document Crafting with AI: Using ChatGPT to Enhance Your Microsoft Word Experience</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/troubleshooting-tips-fixing-the-persistent-blue-screen-of-death-with-netwtw1-10sys/"><u>Troubleshooting Tips: Fixing the Persistent Blue Screen of Death with Netwtw1 10.sys</u></a></li>
<li><a href="https://tech-revival.techidaily.com/truthgpt-coin-explained-is-it-safe-to-invest-in-this-cryptocurrency/"><u>TruthGPT Coin Explained: Is It Safe to Invest in This Cryptocurrency?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleashing-the-power-of-ai-explore-these-8-methods-for-using-chatgpts-visual-skills/"><u>Unleashing the Power of AI: Explore These 8 Methods for Using ChatGPT's Visual Skills</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unveiling-past-images-3-approaches-for-fb-reverse-search-for-2024/"><u>Unveiling Past Images  3 Approaches for FB Reverse Search for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-why-hackers-go-after-chatgpt-users/"><u>Unveiling Why Hackers Go After ChatGPT Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/virtual-emotional-support-guidelines-for-chatgpt-use/"><u>Virtual Emotional Support: Guidelines for ChatGPT Use</u></a></li>
</ul></div>
