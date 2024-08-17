---
title: How Does CodeGPT Work, And Its Potential to Transform Coding?
date: 2024-08-16T14:51:21.093Z
updated: 2024-08-17T14:51:21.093Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes How Does CodeGPT Work, And Its Potential to Transform Coding?
excerpt: This Article Describes How Does CodeGPT Work, And Its Potential to Transform Coding?
thumbnail: https://thmb.techidaily.com/7572b835422df4a46e1dde0ebf1594c94500d035cdbdf693fb3fdb8a7d6301cc.jpg
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
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 1: Install and Download Software and Pre-Made Script

 Please note the following instructions are for a Windows 10 or Windows 11 machine.

 To provide custom data to ChatGPT, you'll need to install and download the latest Python3, Git, Microsoft C++, and the ChatGPT-retrieval script from GitHub. If you already have some of the software installed on your PC, make sure they are updated with the latest version to avoid any hiccups during the process.

Start by installing:

* **Download:** [Python3](https://www.python.org/downloads/) (Free)
* **Download:** [Git](https://git-scm.com/downloads) (Free)
* **Download:** [Microsoft Visual Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/) (Free)

### Python3 and Microsoft C++ Installation Notes

 When installing Python3, make sure that you tick the**Add python.exe to PATH** option before clicking**Install Now** . This is important as it allows you to access Python in any directory on your computer.

![Adding Python to PATH](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/1-download-python.jpg)

 When Installing Microsoft C++, you'll want to install**Microsoft Visual Studio Build Tools** first. Once installed, you can tick the**Desktop development with C++** option and click**Install** with all the optional tools automatically ticked on the right sidebar.

![Installing Microsoft C++ through Build Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/2-install-c.jpg)

 Now that you have installed the latest versions of Python3, Git, and Microsoft C++, you can download the Python script to easily query custom local data.

**Download:** [ChatGPT-retrieval script](https://github.com/techleadhd/chatgpt-retrieval) (Free)

 To download the script, click on**Code,** then select**Download ZIP** . This should download the Python script into your default or selected directory.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Downloading Python script on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/3-download-script.jpg)

Once downloaded, we can now set up a local environment.

## Step 2: Set Up the Local Environment

 To set up the environment, you'll need to open a terminal in the chatgpt-retrieval-main folder you downloaded. To do that, open**chatgpt-retrieval-main** folder, right-click, and select**Open in Terminal** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![Opening terminal on directory folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/4-open-terminal.jpg)

Once the terminal is open, copy and paste this command:

pip install langchain openai chromadb tiktoken unstructured

 This command uses Python's package manager to[create and manage the Python virtual environment](https://www.makeuseof.com/create-manage-python-virtual-environments/) needed.

 After creating the virtual environment, we need to supply an OpenAI API key to access their services. We'll first need to generate an API key from the[OpenAI API keys site](https://platform.openai.com/account/api-keys) by clicking on**Create new secret key** , adding a name for the key, then hitting the**Create secret key button** .

![Creating secret API key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/generate-api-key.jpg)

 You will be provided with a string of characters. This is your OpenAI API key. Copy it by clicking on the copy icon on the side of the API key. Keep note that this API key should be kept secret. Do not share it with others unless you really intend for them to use it with you.

 Once copied, return to the chatgpt-retrieval-main folder and open constants with**Notepad** . Now replace the placeholder with your API key. Remember to save the file!

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding API key as environment variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-api-key.jpg)

 Now that you have successfully set up your virtual environment and added your OpenAI API key as an environment variable. You can now provide your custom data to ChatGPT.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Step 3: Adding Custom Data

 To add custom data, place all your custom text data in the**data** folder within chatgpt-retrieval-main. The format of the text data may be in the form of a PDF, TXT, or DOC.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding custom data for ChatGPT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-data.jpg)

 As you can see from the screenshot above, I've added a text file containing a made-up personal schedule, an article I wrote on[AMD's Instinct Accelerators](https://www.makeuseof.com/what-are-amd-instinct-ai-accelerators/) , and a PDF document.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 4: Querying ChatGPT Through Terminal

 The Python script allows us to query data from the custom data we've added to the data folder and the internet. In other words, you will have access to the usual ChatGPT backend and all the data stored locally in the data folder.

 To use the script, run the python[chatgpt.py](http://chatgpt.py) script and then add your question or query as the argument.

python [chatgpt.py](http://chatgpt.py) "YOUR QUESTION"

Make sure to put your questions in quotation marks.

 To test if we have successfully fed ChatGPT our data, I'll ask a personal question regarding the**Personal Sched.txt** file.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-simplified-guide-effortless-ipad-screen-recording-techniques/"><u>[New] 2024 Approved  Simplified Guide  Effortless iPad Screen Recording Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-mastering-macos-sierra-installation-procedures-for-2024/"><u>[New] Mastering macOS Sierra Installation Procedures for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-swiftly-restore-working-airdrop-between-apple-gadgets-and-macs/"><u>[New] Swiftly Restore Working AirDrop Between Apple Gadgets & Macs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unveil-the-power-of-vrecorder-installs-demystified/"><u>[New] Unveil the Power of VRecorder  Installs Demystified</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dissecting-tseries-profit-generation-through-youtube-videos-for-2024/"><u>[Updated] Dissecting TSeries' Profit Generation Through YouTube Videos for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-8-compelling-no-cost-video-calls-applications-for-pc-and-mac-users/"><u>[Updated] In 2024, 8 Compelling No-Cost Video Calls Applications for PC and MAC Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-tallying-up-mr-beasts-billions/"><u>[Updated] Tallying Up Mr. Beast's Billions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-instagram-live-maintaining-privacy-while-streaming/"><u>2024 Approved  Instagram Live  Maintaining Privacy While Streaming</u></a></li>
<li><a href="https://extra-tips.techidaily.com/asus-proart-pa-329q-in-focus-the-comprehensive-4k-professional-display-analysis-for-2024/"><u>Asus ProArt PA 329Q in Focus – The Comprehensive 4K Professional Display Analysis for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevate-your-career-with-chatgpt-discover-the-6-essential-reasons-to-learn-it-now/"><u>Elevate Your Career with ChatGPT: Discover the 6 Essential Reasons to Learn It Now</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevate-your-search-experience-with-perplex-the-best-the-top-choice-in-ai-powered-google-tools-youre-missing-out-on/"><u>Elevate Your Search Experience with Perplex the Best: The Top Choice in AI-Powered Google Tools You're Missing Out On</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevating-conversational-ai-tips-for-chatgpt-extension-use/"><u>Elevating Conversational AI: Tips for ChatGPT Extension Use</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enterprise-focused-insights-on-gpt-systems/"><u>Enterprise-Focused Insights on GPT Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-anthropics-innovative-ai-prompt-store-with-claude-3-technology/"><u>Exploring Anthropic’s Innovative AI Prompt Store with Claude 3 Technology</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-paperclip-maximizer-understanding-its-connection-with-artificial-intelligence/"><u>Exploring the Paperclip Maximizer: Understanding Its Connection with Artificial Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/first-steps-in-langchain-language-models/"><u>First Steps in LangChain Language Models</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-bert-to-palm-2-understanding-the-evolution-of-googles-large-scale-language-models/"><u>From BERT to PaLM 2: Understanding the Evolution of Google’s Large-Scale Language Models</u></a></li>
<li><a href="https://tech-revival.techidaily.com/game-on-chatgpts-my-bot-techniques-in-strategy-and-visual-creation/"><u>Game On: ChatGPT's My Bot Techniques in Strategy & Visual Creation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-boost-your-productivity-combining-chatgpt-with-visual-studio-code/"><u>How to Boost Your Productivity: Combining ChatGPT with Visual Studio Code</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-xiaomi-redmi-note-12-proplus-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Xiaomi Redmi Note 12 Pro+ 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-hiring-methods-discovering-6-chatgpt-approaches/"><u>Innovative Hiring Methods: Discovering 6 ChatGPT Approaches</u></a></li>
<li><a href="https://tech-revival.techidaily.com/inside-look-the-operating-principles-of-seven-apps-utilizing-gpt-4-technology/"><u>Inside Look: The Operating Principles of Seven Apps Utilizing GPT-4 Technology</u></a></li>
<li><a href="https://tech-revival.techidaily.com/intelligent-machines-at-the-workforce-crossroads/"><u>Intelligent Machines at the Workforce Crossroads</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-claude-ai-the-next-big-thing-or-does-chatgpt-still-rule/"><u>Is Claude AI the Next Big Thing or Does ChatGPT Still Rule?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-it-possible-for-chatgpt-to-craft-personalized-safe-and-effective-exercise-regimens-tailored-just-for-you/"><u>Is It Possible For ChatGPT To Craft Personalized, Safe And Effective Exercise Regimens Tailored Just For You?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/justifying-the-investment-in-advanced-ai-writing-tools-is-it-worth-it/"><u>Justifying the Investment in Advanced AI Writing Tools – Is It Worth It?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/master-chatgpt-easily-by-exploring-its-top-5-untapped-features/"><u>Master ChatGPT Easily by Exploring Its Top 5 Untapped Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-chatgpt-organizing-conversations-with-custom-folders/"><u>Mastering ChatGPT: Organizing Conversations with Custom Folders</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mercedes-benz-innovates-ai-assistant-with-voice-command-integration-for-drivers/"><u>Mercedes-Benz Innovates: AI Assistant with Voice Command Integration for Drivers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-auto-gpt-without-gpt-4-pros-and-cons-for-users/"><u>Navigating Auto-GPT Without GPT-4: Pros and Cons for Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-beyond-chatgpts-boundaries-what-are-your-options-for-extra-tokens/"><u>Navigating Beyond ChatGPT's Boundaries: What Are Your Options for Extra Tokens?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-future-of-work-6-key-tips-to-excel-in-an-ai-integrated-office/"><u>Navigating the Future of Work: 6 Key Tips to Excel in an AI-Integrated Office</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-web-easier-with-microsofts-bing-and-its-cutting-edge-ai-features/"><u>Navigating the Web Easier with Microsoft’s Bing and Its Cutting-Edge AI Features</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/plotting-your-way-through-successful-instagram-video-marketing/"><u>Plotting Your Way Through Successful Instagram Video Marketing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/premium-extensions-for-enhanced-gpt-in-vs-code/"><u>Premium Extensions for Enhanced GPT in VS Code</u></a></li>
</ul></div>
