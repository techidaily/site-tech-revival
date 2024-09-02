---
title: Instant Guide to Severing GPT Ties
date: 2024-09-01T19:13:55.706Z
updated: 2024-09-02T19:13:55.706Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: This Article Describes Instant Guide to Severing GPT Ties
excerpt: This Article Describes Instant Guide to Severing GPT Ties
thumbnail: https://thmb.techidaily.com/da30e1ebb9eb5ab25a7effb66e03594a33963d6af1f63bbe87601ee182a33306.jpg
---

## Llama ˈLocal-Ization' Guide: How to Install and Use It Yourself

 Meta released Llama 2 in the summer of 2023\. The new version of Llama is fine-tuned with 40% more tokens than the original Llama model, doubling its context length and significantly outperforming other open-sourced models available. The fastest and easiest way to access Llama 2 is via an API through an online platform. However, if you want the best experience, installing and loading Llama 2 directly on your computer is best.

 With that in mind, we've created a step-by-step guide on how to use Text-Generation-WebUI to load a quantized Llama 2 LLM locally on your computer.

## Why Install Llama 2 Locally

 There are many reasons why people choose to run Llama 2 directly. Some do it for privacy concerns, some for customization, and others for offline capabilities. If you're researching, fine-tuning, or integrating Llama 2 for your projects, then accessing Llama 2 via API might not be for you. The point of running an LLM locally on your PC is to reduce reliance on[third-party AI tools](https://www.makeuseof.com/best-ai-web-apps/) and use AI anytime, anywhere, without worrying about leaking potentially sensitive data to companies and other organizations.

 With that said, let's begin with the step-by-step guide to installing Llama 2 locally.

## Step 1: Install Visual Studio 2019 Build Tool

 To simplify things, we will use a one-click installer for Text-Generation-WebUI (the program used to load Llama 2 with GUI). However, for this installer to work, you need to download the Visual Studio 2019 Build Tool and install the necessary resources.

**Download:** [Visual Studio 2019](https://learn.microsoft.com/en-us/visualstudio/releases/2019/release-notes) (Free)

1. Go ahead and download the community edition of the software.
2. Now install Visual Studio 2019, then open the software. Once opened, tick the box on**Desktop development with C++** and hit install.  
![Install-Desktop-Development-With-C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/2-install-desktop-development-with-c.jpg)

 Now that you have Desktop development with C++ installed, it's time to download the Text-Generation-WebUI one-click installer.

## Step 2: Install Text-Generation-WebUI

 The Text-Generation-WebUI one-click installer is a script that automatically creates the required folders and sets up the Conda environment and all necessary requirements to run an AI model.

 To install the script, download the one-click installer by clicking on**Code** \>**Download ZIP.**

**Download:** [Text-Generation-WebUI Installer](https://github.com/oobabooga/text-generation-webui/tree/main) (Free)

1. Once downloaded, extract the ZIP file to your preferred location, then open the extracted folder.
2. Within the folder, scroll down and look for the appropriate start program for your operating system. Run the programs by double-clicking the appropriate script.  
   * If you are on Windows, select**start\_windows** batch file  
   * for MacOS, select**start\_macos** shell scrip  
   * for Linux,**start\_linux** shell script.  
   ![Select operating system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/4-select-operating-system.jpg)
3. Your anti-virus might create an alert; this is fine. The prompt is just an[antivirus false positive](https://www.makeuseof.com/what-is-antivirus-false-result/) for running a batch file or script. Click on**Run anyway** .
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

 Congratulations, you've successfully loaded Llama2 on your local computer!

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Try Out Other LLMs

 Now that you know how to run Llama 2 directly on your computer using Text-Generation-WebUI, you should also be able to run other LLMs besides Llama. Just remember the naming conventions of models and that only quantized versions of models (usually q4 precision) can be loaded on regular PCs. Many quantized LLMs are available on HuggingFace. If you want to explore other models, search for TheBloke in HuggingFace's model library, and you should find many models available.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-precision-playback-aligning-video-views-in-real-time/"><u>[New] 2024 Approved  Precision Playback  Aligning Video Views in Real-Time</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-iphone-ios-vr-games-you-should-try/"><u>[New] 2024 Approved  Top Iphone IOS VR Games You Should Try</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-audio-identity-the-art-of-adding-your-own-tones-to-android/"><u>[New] Crafting Audio Identity  The Art of Adding Your Own Tones to Android</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-10-comprehensible-and-cost-free-subtitle-downloader-sites/"><u>[Updated] 10 Comprehensible & Cost-Free Subtitle Downloader Sites</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-blueprint-producing-purposeful-life-exploration-broadcasts/"><u>[Updated] 2024 Approved  Blueprint  Producing Purposeful Life Exploration Broadcasts</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/achieve-mastery-in-tracking-fbs-recently-seen-videos-for-2024/"><u>Achieve Mastery in Tracking Fb’s Recently Seen Videos for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-missteps-an-ongoing-cybersecurity-scare/"><u>AI Missteps: An Ongoing Cybersecurity Scare</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-showdown-features-benefits-and-uses-of-snapchats-my-ai-compared-to-chatgpt/"><u>AI Showdown: Features, Benefits, and Uses of Snapchat's My AI Compared to ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/an-overview-what-is-openai/"><u>An Overview: What Is OpenAI?</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-realme-gt-neo-5-se-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Realme GT Neo 5 SE? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-an-artificial-intelligence-companion-ensure-safety-in-natures-playgrounds/"><u>Can an Artificial Intelligence Companion Ensure Safety in Nature's Playgrounds?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/cook-smart-live-well-chatgpts-kitchen-companion/"><u>Cook Smart, Live Well: ChatGPT's Kitchen Companion</u></a></li>
<li><a href="https://tech-revival.techidaily.com/crafting-side-income-from-ai-and-reviving-classic-games/"><u>Crafting Side Income From AI & Reviving Classic Games</u></a></li>
<li><a href="https://tech-revival.techidaily.com/deploying-artifice-intelligence-via-web-browsers-using-agentgpt/"><u>Deploying Artifice Intelligence via Web Browsers Using AgentGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effective-strategies-for-organizing-chatgpt-interactions-with-dedicated-folders/"><u>Effective Strategies for Organizing ChatGPT Interactions with Dedicated Folders</u></a></li>
<li><a href="https://tech-revival.techidaily.com/empowering-conversations-mastering-chatgpt-on-iphone-via-siri/"><u>Empowering Conversations: Mastering ChatGPT on iPhone via Siri</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exceeding-chatgpts-maximum-characters-how/"><u>Exceeding ChatGPT's Maximum Characters: How?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/exclusive-hub-free-images-galore-across-the-web/"><u>Exclusive Hub  Free Images Galore Across the Web</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-oppo-f23-5g-lock-screen-password-by-drfone-android/"><u>How To Change Oppo F23 5G Lock Screen Password?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Realme Narzo 60 Pro 5G Phone that is Locked?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-se-without-face-id-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock iPhone SE without Face ID</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-the-iphone-se-2022-sim-lock-4-easy-methods-by-drfone-ios/"><u>How To Unlock The iPhone SE (2022) SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-hidden-paths-techniques-to-skip-without-watching-edgenuity-videos/"><u>In 2024, The Hidden Paths  Techniques to Skip Without Watching Edgenuity Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-depth-look-at-xvideo-hub-a-full-studio-guide-for-2024/"><u>In-Depth Look at XVideo Hub  A Full Studio Guide for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/is-your-apple-iphone-se-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>Is Your Apple iPhone SE in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/leveraging-luminaries-for-greater-exposure/"><u>Leveraging Luminaries for Greater Exposure</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/manycam-review-is-there-a-better-alternative-for-2024/"><u>ManyCam Review  Is There A Better Alternative for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-art-of-verse-with-chatgpt-support/"><u>Navigating the Art of Verse with ChatGPT Support</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-virtual-connections-a-comprehensive-guide-to-identifying-who-you-interact-with-in-cyberspace-and-demystifying-the-dead-internet-hypothesis/"><u>Navigating Virtual Connections: A Comprehensive Guide to Identifying Who You Interact With in Cyberspace and Demystifying The Dead Internet Hypothesis</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protecting-your-digital-self-insights-into-why-hackers-prey-on-chatgpt-accounts/"><u>Protecting Your Digital Self: Insights Into Why Hackers Prey on ChatGPT Accounts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/reset-rendezvous-solving-stubborn-ios-chatgpt-problems/"><u>Reset Rendezvous: Solving Stubborn iOS ChatGPT Problems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-3d-creations-using-chatgpts-intelligent-assistance/"><u>Revolutionize Your 3D Creations Using ChatGPT's Intelligent Assistance</u></a></li>
<li><a href="https://extra-information.techidaily.com/simplifying-cinematography-best-film-cameras-for-newbies/"><u>Simplifying Cinematography  Best Film Cameras for Newbies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/strategic-nutrition-planning-using-the-power-of-chatgpt/"><u>Strategic Nutrition Planning Using the Power of ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-of-diagnostics-and-treatment-can-chatgpt-lead-the-way/"><u>The Future of Diagnostics and Treatment: Can ChatGPT Lead the Way?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-gpt-4-for-you-and-all/"><u>Understanding GPT-4, For You and All</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleashing-potential-seamlessly-connect-chatgpt-and-google-sheets-for-enhanced-productivity/"><u>Unleashing Potential: Seamlessly Connect ChatGPT and Google Sheets for Enhanced Productivity</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-5-primary-companies-grievances-with-gpt/"><u>Unveiling the 5 Primary Companies' Grievances with GPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-mystery-of-gpt-4-all-a-deep-dive-into-its-functionality/"><u>Unveiling the Mystery of GPT-4 All: A Deep Dive Into Its Functionality</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-lenovo-ideapad-100-device-drivers-step-by-step-guide-for-windows-10-users/"><u>Update Lenovo IdeaPad 100 Device Drivers: Step-by-Step Guide for Windows 10 Users</u></a></li>
</ul></div>
