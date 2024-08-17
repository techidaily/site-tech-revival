---
title: "ChatGPT Excellence: Top 10 Prompts Transforming Your Crypto Knowledge"
date: 2024-08-16T14:51:05.237Z
updated: 2024-08-17T14:51:05.237Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes ChatGPT Excellence: Top 10 Prompts Transforming Your Crypto Knowledge"
excerpt: "This Article Describes ChatGPT Excellence: Top 10 Prompts Transforming Your Crypto Knowledge"
thumbnail: https://thmb.techidaily.com/7b4c05e427ef93175f84d0a703341dbe0517d72f4c6891c8d31a4e5e36657912.jpg
---

## Transform Personal Datasets Into an Intelligent, Customized ChatBot – Learn How

 Providing GPT technology in a powerful and easy-to-use chatbot, ChatGPT has become the world's most popular AI tool. Many people use ChatGPT to provide engaging conversations, answer queries, offer creative suggestions, and aid in coding and writing. However, ChatGPT is limited as you cannot store your data for long-term personal use, and its September 2021 knowledge data cutoff point.

 As a workaround, we can use OpenAI's API and LangChain to provide ChatGPT with custom data and updated info past 2021 to create a custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
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

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
![Testing ChatGPT with custom data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/visit.jpg)

 It worked! This means ChatGPT was able to read the Personal Sched.txt provided earlier. Now let's see if we have successfully fed ChatGPT with information it does not know due to its knowledge cutoff date.

![Asking custom ChatGPT about topic outside knowledge cut off data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/m250x.jpg)

 As you can see, it correctly described the AMD Instinct MI250x, which was released after ChatGPT -3's knowledge cutoff date.

## Limitations of Custom ChatGPT

 Although feeding GPT-3.5 with custom data opens more ways to apply and use the LLM, there are a few drawbacks and limitations.

 Firstly, you need to provide all the data yourself. You can still access all the knowledge of GPT-3.5 until its knowledge cutoff date; however, you must provide all the extra data. This means if you want your local model to be knowledgeable of a certain subject on the internet that GPT-3.5 don't already know, you'll have to go to the internet and scrape the data yourself and save it as a text on the data folder of chatgpt-retrieval-main.

 Another issue is that querying ChatGPT like this takes more time to load when compared to asking ChatGPT directly.

 Lastly, the only model currently available is GPT-3.5 Turbo. So even if you have access to GPT-4, you won't be able to use it to power your custom ChatGPT instance.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-channeling-twitter-vids-seamlessly-to-snapchat/"><u>[New] 2024 Approved  Channeling Twitter Vids Seamlessly to Snapchat</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-easy-methods-for-downloading-vimeo-clips/"><u>[New] 2024 Approved  Easy Methods for Downloading Vimeo Clips</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-guard-your-images-with-top-photo-watermarks/"><u>[New] 2024 Approved  Guard Your Images with Top Photo Watermarks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-behind-the-scenes-with-top-influencers-insights-into-their-fb-stories/"><u>[New] Behind the Scenes with Top Influencers – Insights Into Their FB Stories</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-diy-digital-storytelling-making-moving-pictures-on-your-smartphone/"><u>[New] In 2024, DIY Digital Storytelling  Making Moving Pictures on Your Smartphone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-elevating-selfies-and-pics-on-snapchat-edit-like-a-pro/"><u>[New] In 2024, Elevating Selfies and Pics on Snapchat – Edit Like a Pro</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-essential-offline-android-games-for-uninterrupted-fun/"><u>[Updated] 2024 Approved  Essential Offline Android Games for Uninterrupted Fun</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-spin-tiktok-magic-into-viral-instagram-reel-success/"><u>[Updated] In 2024, Spin TikTok Magic Into Viral Instagram Reel Success</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-no-pay-no-problem-get-your-free-passport-photo-creator-now-online-and-on-desktop/"><u>[Updated] No Pay, No Problem  Get Your Free Passport Photo Creator Now Online & On Desktop</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-10-uplifting-films-for-momentum-and-motivation/"><u>[Updated] Top 10 Uplifting Films for Momentum & Motivation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-fixing-audio-gaps-in-social-network-videos/"><u>2024 Approved  Fixing Audio Gaps in Social Network Videos</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-ultimate-10-royale-showdowns/"><u>2024 Approved  Ultimate 10 Royale Showdowns</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ahead-of-the-curve-5-critical-ai-innovations-for-entrepreneurs/"><u>Ahead of the Curve: 5 Critical AI Innovations for Entrepreneurs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beat-cyber-threats-affordable-mobile-solutions-and-the-power-of-ai-in-our-latest-episode/"><u>Beat Cyber Threats: Affordable Mobile Solutions and the Power of AI in Our Latest Episode</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722114674826-best-ai-companion-exploring-features-of-google-bard-vs-bing-chat-for-a-winners-edge/"><u>Best AI Companion? Exploring Features of Google Bard vs Bing Chat for a Winner's Edge.</u></a></li>
<li><a href="https://tech-revival.techidaily.com/building-fantasy-worlds-easily-a-comprehensive-guide-to-using-chatgpt/"><u>Building Fantasy Worlds Easily: A Comprehensive Guide to Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-machine-learning-decode-our-feelings-through-emotion-ai/"><u>Can Machine Learning Decode Our Feelings Through Emotion AI?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/challenging-gpt-constraints-implications-for-use/"><u>Challenging GPT Constraints: Implications for Use</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpts-role-in-behavioral-change-for-better-health/"><u>ChatGPT's Role in Behavioral Change for Better Health</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpts-role-in-cultivating-emotional-intelligence-insights-and-techniques/"><u>ChatGPT's Role in Cultivating Emotional Intelligence: Insights and Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chrome-extension-revolutionizing-easy-chatgpt-prompting-now-available/"><u>Chrome Extension Revolutionizing Easy ChatGPT Prompting Now Available!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-horoscope-claims-with-ai-powered-foresight-chatgpts-edge-explained/"><u>Comparing Horoscope Claims with AI-Powered Foresight: ChatGPT's Edge Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/complete-guide-downloading-and-installing-auto-gpt-step-by-step/"><u>Complete Guide: Downloading & Installing Auto-GPT - Step by Step</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/designing-short-trailers-that-tell-a-story/"><u>Designing Short Trailers That Tell a Story</u></a></li>
<li><a href="https://tech-revival.techidaily.com/detecting-synthetic-writing-an-in-depth-guide-to-using-gptzero/"><u>Detecting Synthetic Writing: An In-Depth Guide to Using GPTZero</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-power-of-personalized-ai-with-openais-latest-gpt-store-begin-your-journey-here/"><u>Discover the Power of Personalized AI with OpenAI's Latest GPT Store - Begin Your Journey Here</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dissecting-twitters-verification-process-the-significance-of-blue-checkmarks/"><u>Dissecting Twitter's Verification Process: The Significance of Blue Checkmarks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-s17-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Vivo S17 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-clearsightcapture-straightforward-desktop-to-video-conversion/"><u>In 2024, ClearSightCapture  Straightforward Desktop to Video Conversion</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-poco-x6-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Poco X6 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/next-level-playing-field-embrace-the-philips-evnias-49-oled-curved-monitor/"><u>Next-Level Playing Field: Embrace the Philips Evnia's 49 OLED Curved Monitor</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pro-tips-to-amplify-your-canva-designs-for-2024/"><u>Pro Tips to Amplify Your Canva Designs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-disk-management-virtual-disk-hiccups/"><u>Rectifying Disk Management Virtual Disk Hiccups</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722159590411-reinvigorate-your-iphones-mindfulness-with-these-fixes-to-try/"><u>Reinvigorate Your iPhone's Mindfulness with These Fixes to Try!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722084026785-the-ultimate-guide-to-communicating-with-chatgpt-begin-your-journey-today/"><u>The Ultimate Guide to Communicating with ChatGPT – Begin Your Journey Today!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-apps-and-online-tools-to-track-xiaomi-redmi-note-13-proplus-5g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Xiaomi Redmi Note 13 Pro+ 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-how-you-interact-get-chatgpt-for-android-and-start-conversing-today/"><u>Transform How You Interact: Get ChatGPT for Android and Start Conversing Today!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-loneliness-interactive-ai-as-social-catalyst/"><u>Transform Loneliness: Interactive AI as Social Catalyst</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-job-hunting-with-smart-ai/"><u>Transforming Job Hunting with Smart AI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/translating-languages-in-real-time-how-chatgpt-works-its-magic/"><u>Translating Languages in Real-Time: How ChatGPT Works Its Magic</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-oppo-find-x6-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Oppo Find X6 Screen | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-and-overcoming-chatgpts-conversation-recall-challenge/"><u>Understanding & Overcoming ChatGPT’s Conversation Recall Challenge</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleash-creativity-and-efficiency-10-chatgpt-enhancements-for-vs-code/"><u>Unleash Creativity and Efficiency: 10 ChatGPT Enhancements for VS Code</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleash-your-inner-storyteller-using-chatgpt-the-ultimate-strategy/"><u>Unleash Your Inner Storyteller Using ChatGPT: The Ultimate Strategy</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-crypto-success-leverage-these-5-chatgpt-hacks-for-trading-triumphs/"><u>Unlocking Crypto Success: Leverage These 5 ChatGPT Hacks for Trading Triumphs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-potential-with-default-plugins-in-chatgpt-uses-and-applications/"><u>Unlocking Potential with Default Plugins in ChatGPT: Uses and Applications</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/unpacking-tunefab-written-review-on-latest-tech-for-screen-recording-for-2024/"><u>Unpacking Tunefab' Written Review on Latest Tech for Screen Recording for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unraveling-ai-rules-who-holds-responsibility-for-guiding-ai-development-safely/"><u>Unraveling AI Rules: Who Holds Responsibility for Guiding AI Development Safely?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/what-is-fraudgpt-how-to-protect-yourself-from-this-dangerous-chatbot/"><u>What Is FraudGPT? How to Protect Yourself From This Dangerous Chatbot</u></a></li>
<li><a href="https://tech-revival.techidaily.com/whats-hugging-face-an-in-depth-look-at-this-cutting-edge-ai-tool/"><u>What's Hugging Face? An In-Depth Look at This Cutting-Edge AI Tool</u></a></li>
</ul></div>
