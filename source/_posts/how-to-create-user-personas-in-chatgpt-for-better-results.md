---
title: How to Create User Personas in ChatGPT for Better Results
date: 2024-08-16T15:07:26.102Z
updated: 2024-08-17T15:07:26.102Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes How to Create User Personas in ChatGPT for Better Results
excerpt: This Article Describes How to Create User Personas in ChatGPT for Better Results
thumbnail: https://thmb.techidaily.com/66532283e392299f83b40e1057e43cc22a016c0905229694154e720c235ea49f.jpg
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

## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
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
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-leading-firefox-recording-software/"><u>[Updated] 2024 Approved  Leading Firefox Recording Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-sophisticated-screenshot-options-for-gamers/"><u>[Updated] 2024 Approved  Sophisticated Screenshot Options for Gamers</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-step-by-step-for-gaining-access-to-the-best-clip-art/"><u>[Updated] 2024 Approved  Step by Step for Gaining Access to the Best Clip Art</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-video-transcriber-chrome-os-companion/"><u>[Updated] Best Video Transcriber  Chrome OS Companion</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-infuse-your-films-with-text-magic-top-10-techniques-unveiled/"><u>[Updated] Infuse Your Films with Text Magic  Top 10 Techniques Unveiled</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unveiling-mr-beasts-economic-status-for-2024/"><u>[Updated] Unveiling Mr. Beast's Economic Status for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-free-after-effects-title-templates/"><u>2024 Approved  Best Free After Effects Title Templates</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-from-graphics-to-emojis-turning-gifs-into-stickers-on-telegram-and-more/"><u>2024 Approved  From Graphics to Emojis  Turning GIFs Into Stickers on Telegram & More</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-magix-vpx-review-transforming-media-with-ease/"><u>2024 Approved  Magix VPX Review  Transforming Media with Ease</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-tecno-pop-7-pro-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Tecno Pop 7 Pro to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-giants-in-ai-the-critical-variances-between-gpt-4-and-gpt-35/"><u>Comparing Giants in AI: The Critical Variances Between GPT-4 and GPT-3.5.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/customizing-the-twitter-interface-an-experts-tutorial-for-video-images-for-2024/"><u>Customizing the Twitter Interface  An Expert's Tutorial for Video Images for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dangers-dont-get-a-chatgpt-androidios-app/"><u>Dangers: Don't Get a ChatGPT Android/iOS App</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-cause-of-display-driver-non-startups/"><u>Deciphering the Cause of Display Driver Non-Startups</u></a></li>
<li><a href="https://tech-revival.techidaily.com/detailed-insight-into-the-operation-of-shared-chatgpt-links/"><u>Detailed Insight Into the Operation of Shared ChatGPT Links</u></a></li>
<li><a href="https://extra-tips.techidaily.com/effortless-techniques-to-turn-off-youtube-video-previews/"><u>Effortless Techniques to Turn Off YouTube Video Previews</u></a></li>
<li><a href="https://tech-revival.techidaily.com/get-started-with-discreet-communication-experience-duckduckgos-ai-and-alternatives/"><u>Get Started with Discreet Communication: Experience DuckDuckGo's AI & Alternatives</u></a></li>
<li><a href="https://tech-revival.techidaily.com/get-started-with-gpt-ngpt-free-access-tactics-you-need/"><u>Get Started with GPT-nGPT - FREE Access Tactics You Need</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guarding-against-glossed-over-nuances-by-ai-summarization-tools/"><u>Guarding Against Glossed Over Nuances by AI Summarization Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-the-power-of-ai-top-10-chatgpt-and-vs-code-tactics/"><u>Harness the Power of AI: Top 10 ChatGPT & VS Code Tactics</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harnessing-chatgpt-for-individualized-exercise-plans/"><u>Harnessing ChatGPT for Individualized Exercise Plans</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-learning-chatgpt-can-advance-your-career-a-guide-for-job-hunters-and-employees/"><u>How Learning ChatGPT Can Advance Your Career: A Guide for Job Hunters & Employees</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-apple-iphone-6-plus-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and Apple iPhone 6 Plus The Right Way</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-z-fold-5-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-ensure-chatgpt-remembers-our-dialogue-a-step-by-step-guide/"><u>How To Ensure ChatGPT Remembers Our Dialogue: A Step-by-Step Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-cutting-edge-zoom-techniques-for-peak-call-quality/"><u>In 2024, Cutting Edge Zoom Techniques for Peak Call Quality</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-tecno-camon-20-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Tecno Camon 20 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-seamlessly-post-pictures-your-youtube-visual-guide/"><u>In 2024, Seamlessly Post Pictures  Your YouTube Visual Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/intuitive-explanations-of-ai/"><u>Intuitive Explanations of AI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/key-factors-for-effective-and-reliable-bot-assisted-platforms/"><u>Key Factors for Effective and Reliable Bot-Assisted Platforms</u></a></li>
<li><a href="https://tech-revival.techidaily.com/learn-to-navigate-microsoft-copilot-for-developers-using-a-mac/"><u>Learn to Navigate Microsoft Copilot for Developers Using a Mac</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leveraging-chatgpt-effective-strategies-and-tips-for-macos-enthusiasts/"><u>Leveraging ChatGPT: Effective Strategies and Tips for macOS Enthusiasts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/maximizing-client-results-with-ai-driven-planning/"><u>Maximizing Client Results with AI-Driven Planning</u></a></li>
<li><a href="https://tech-revival.techidaily.com/maximizing-your-output-with-chatgpt-essential-tips-for-writers/"><u>Maximizing Your Output with ChatGPT: Essential Tips for Writers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/most-effective-8-chatgpt-queries-for-reducing-digital-noise/"><u>Most Effective 8 ChatGPT Queries for Reducing Digital Noise</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-crypto-exchanges-why-geminis-one-million-token-capability-is-a-milestone/"><u>Navigating Crypto Exchanges : Why Gemini's One Million Token Capability Is a Milestone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-differences-between-standard-and-premium-copilots-is-it-worth-the-upgrade/"><u>Navigating the Differences Between Standard and Premium Copilots - Is It Worth The Upgrade?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/openais-gpt-unpacking-cybersecurity-issues/"><u>OpenAI's GPT: Unpacking Cybersecurity Issues</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protect-yourself-from-these-5-dangerous-chatgpt-deceptions/"><u>Protect Yourself From These 5 Dangerous ChatGPT Deceptions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/real-time-hardware-for-vr/"><u>Real-Time Hardware for VR</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-homelife-6-chatgpt-productivity-hacks/"><u>Revolutionize Your Homelife: 6 ChatGPT Productivity Hacks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/scaling-up-innovative-design-methods-with-canva-and-ai-assistance/"><u>Scaling Up: Innovative Design Methods with Canva & AI Assistance</u></a></li>
<li><a href="https://extra-information.techidaily.com/shine-up-advanced-setups-to-make-your-clips-pop/"><u>Shine Up  Advanced Setups to Make Your Clips Pop</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-msvcr100dll-missing-error-a-comprehensive-guide/"><u>Solving the MSVCR100.DLL Missing Error: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/strategic-insights-dos-and-donts-of-incorcuating-chatgpt-in-writing-projects/"><u>Strategic Insights: Do’s and Don’ts of Incorcuating ChatGPT in Writing Projects</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-art-of-life-balancing-using-chatgpt-as-your-secret-weapon/"><u>The Art of Life Balancing: Using ChatGPT as Your Secret Weapon</u></a></li>
</ul></div>
