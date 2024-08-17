---
title: "ChatGPT Mastery: How It Can Transform Employment and Why You Should Learn Now – Top Six Insights Revealed"
date: 2024-08-16T14:53:08.663Z
updated: 2024-08-17T14:53:08.663Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes ChatGPT Mastery: How It Can Transform Employment and Why You Should Learn Now – Top Six Insights Revealed"
excerpt: "This Article Describes ChatGPT Mastery: How It Can Transform Employment and Why You Should Learn Now – Top Six Insights Revealed"
thumbnail: https://thmb.techidaily.com/6d2d53e2342f21d415006db38fe4601b286d92e55c94874be07e2903db77be9c.jpg
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

## Why Provide ChatGPT with Custom Data?

 Feeding ChatGPT with custom data and providing updated information beyond its knowledge cutoff date provides several benefits over just using ChatGPT as usual. Here are a few of them:

* **Personalized Interactions:** By providing ChatGPT with custom data, users can create a more customized experience. The model can be trained on specific datasets relevant to individual users or organizations, resulting in responses tailored to their unique needs and preferences.
* **Domain-Specific Expertise:** Custom data integration allows ChatGPT to specialize in particular domains or industries. It can be trained on industry-specific knowledge, terminology, and trends, enabling more accurate and insightful responses within those specific areas.
* **Current and Accurate Information:** Access to updated information ensures that ChatGPT stays current with the latest developments and knowledge. It can provide accurate responses based on recent events, news, or research, making it a more reliable source of information.

 Now that you understand the importance of providing custom data to ChatGPT, here's a step-by-step on how to do so on your local computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

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
<li><a href="https://youtube-sure.techidaily.com/5-best-game-recording-software-for-youtuber/"><u>[New] 15 Best Game Recording Software for YouTuber</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-how-to-effortlessly-share-vimeo-video-on-instagram/"><u>[New] 2024 Approved  How to Effortlessly Share Vimeo Video on Instagram</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-simple-steps-for-incorporating-videos-into-articles/"><u>[New] 2024 Approved  Simple Steps for Incorporating Videos Into Articles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-diy-unleashing-creative-power-in-animation-effects-for-2024/"><u>[New] DIY  Unleashing Creative Power in Animation Effects for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-save-the-day-linkinscapes-6-best-apps-for-video-downloading/"><u>[New] In 2024, Save the Day  Linkinscape's 6 Best Apps for Video Downloading</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-swiftswirl-momentmirror-recording-for-2024/"><u>[New] SwiftSwirl MomentMirror Recording for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-converging-music-and-imagery-online/"><u>[Updated] Converging Music and Imagery Online</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-iphoneandroid-users-add-soundtracks-to-their-profile-for-2024/"><u>[Updated] How iPhone/Android Users Add Soundtracks to Their Profile for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-the-creme-de-la-fluid-simulation-games/"><u>[Updated] In 2024, The Crème De La Fluid Simulation Games</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-8plus-free-easy-to-use-downloader-apps-for-instagrams-creative-videos/"><u>2024 Approved  8+ Free, Easy-to-Use Downloader Apps for Instagram's Creative Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-score-the-biggest-bargains-on-mystery-boxes-websites/"><u>2024 Approved  Score the Biggest Bargains on Mystery Boxes Websites</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-visual-storytelling-of-pc-playtime-top-6-screenshot-secrets/"><u>2024 Approved  Visual Storytelling of PC Playtime - Top 6 Screenshot Secrets</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-productivity-6-outstanding-ai-chatgpt-extensions-for-developers-in-vs-code/"><u>Boosting Productivity: 6 Outstanding AI ChatGPT Extensions for Developers in VS Code</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-truthgpts-capabilities-coinciding-with-authorities-sting-against-privacy-focused-mullvad-vpn-premier-selection-of-free-gaming-titles-for-computers39/"><u>Exploring TruthGPT's Capabilities: Coinciding with Authorities' Sting Against Privacy-Focused Mullvad VPN, Premier Selection of Free Gaming Titles for Computers & Detailed Overview of Switching to Mechanical Keyboards</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gemini-pro-vs-gptplusplus-best-ai-showdown/"><u>Gemini Pro Vs. GPT++: Best AI Showdown</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-utilizing-artificial-intelligence-with-bing-app-for-android-users/"><u>Guide: Utilizing Artificial Intelligence with Bing App for Android Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-initiate-a-collaborative-skype-group-discussion-for-2024/"><u>How to Initiate a Collaborative Skype Group Discussion for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ideal-integrations-boosting-vs-codes-chatgpt-capabilities/"><u>Ideal Integrations: Boosting VS Code's ChatGPT Capabilities</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chromatic-coherence-helper/"><u>In 2024, Chromatic Coherence Helper</u></a></li>
<li><a href="https://tech-revival.techidaily.com/inside-googles-new-breakthrough-an-in-depth-look-at-the-palm-2-system/"><u>Inside Google's New Breakthrough: An In-Depth Look at the PaLM 2 System</u></a></li>
<li><a href="https://tech-revival.techidaily.com/introducing-newcomers-bard-against-bing-chatbot/"><u>Introducing Newcomers: Bard Against Bing Chatbot</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-forefront-ai-the-future-comparing-it-against-chatgpt-in-detail/"><u>Is Forefront AI the Future? Comparing It Against ChatGPT in Detail</u></a></li>
<li><a href="https://tech-revival.techidaily.com/language-labyrinth-luminaries-the-battle-of-brains-and-syntax/"><u>Language Labyrinth Luminaries: The Battle of Brains and Syntax</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leverage-artificnial-intelligence-in-bing-essential-guide-for-android-users/"><u>Leverage Artificnial Intelligence in Bing - Essential Guide for Android Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leveraging-chatgpt-in-freelance-writing-key-dos-and-donts/"><u>Leveraging ChatGPT in Freelance Writing: Key Dos and Don'ts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/linearized-installation-of-bavarder-in-linux/"><u>Linearized Installation of Bavarder in Linux</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-apple-iphone-6s-5-ways-to-get-into-a-locked-apple-iphone-6s-by-drfone-ios/"><u>Locked Out of Apple iPhone 6s? 5 Ways to get into a Locked Apple iPhone 6s</u></a></li>
<li><a href="https://tech-revival.techidaily.com/maximize-efficiency-with-these-6-strategies-leveraging-chatgpts-code-interpreter-functionality/"><u>Maximize Efficiency with These 6 Strategies Leveraging ChatGPT’s Code Interpreter Functionality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/neural-network-progression-the-anticipated-debut-of-gpt-5/"><u>Neural Network Progression: The Anticipated Debut of GPT-5?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-videopad-video-editing-software-review-pros-cons-and-buying-advice/"><u>New 2024 Approved Videopad Video Editing Software Review Pros, Cons, and Buying Advice</u></a></li>
<li><a href="https://tech-revival.techidaily.com/precision-in-ai-reactions-the-power-of-6-strategic-prompts/"><u>Precision in AI Reactions: The Power of 6 Strategic Prompts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/prompt-engineering-jobs-unveiling-the-legitimacy-and-important-points-to-think-about/"><u>Prompt Engineering Jobs: Unveiling the Legitimacy and Important Points to Think About</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-workflow-with-these-8-smart-auto-gpt-techniques/"><u>Revolutionize Your Workflow with These 8 Smart Auto-GPT Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguarding-confidentiality-in-an-era-of-customizable-gpt-models-like-chatgpt/"><u>Safeguarding Confidentiality in an Era of Customizable GPT Models Like ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-dawn-of-bard-googles-revolutionary-response-to-chatgpt/"><u>The Dawn of 'Bard' - Google's Revolutionary Response to ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-efficient-approach-to-persona-creation-with-chatgpt/"><u>The Efficient Approach to Persona Creation with ChatGPT</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essentials-of-selecting-an-elite-monitor-for-games/"><u>The Essentials of Selecting an Elite Monitor for Games</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-potential-of-emotion-recognition-technology-by-ai-fact-or-fiction/"><u>The Potential of Emotion Recognition Technology by AI: Fact or Fiction?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-to-using-chatgpt-for-building-unique-characters-learn-the-best-prompts/"><u>The Ultimate Guide to Using ChatGPT for Building Unique Characters: Learn the Best Prompts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-preserving-and-revisiting-your-chatgpt-conversations/"><u>The Ultimate Guide: Preserving and Revisiting Your ChatGPT Conversations</u></a></li>
<li><a href="https://some-tips.techidaily.com/unforgettable-visions-the-top-15-stop-motion-film-classics-for-2024/"><u>Unforgettable Visions  The Top 15 Stop-Motion Film Classics for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-7-driver-set-lenovo-y470-laptop/"><u>Windows 7 Driver Set - Lenovo Y470 Laptop</u></a></li>
</ul></div>
