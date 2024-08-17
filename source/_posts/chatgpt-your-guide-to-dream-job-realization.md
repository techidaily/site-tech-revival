---
title: "ChatGPT: Your Guide to Dream Job Realization"
date: 2024-08-16T14:22:26.362Z
updated: 2024-08-17T14:22:26.362Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes ChatGPT: Your Guide to Dream Job Realization"
excerpt: "This Article Describes ChatGPT: Your Guide to Dream Job Realization"
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
---

## Llama ˈLocal-Ization' Guide: How to Install and Use It Yourself

 Meta released Llama 2 in the summer of 2023\. The new version of Llama is fine-tuned with 40% more tokens than the original Llama model, doubling its context length and significantly outperforming other open-sourced models available. The fastest and easiest way to access Llama 2 is via an API through an online platform. However, if you want the best experience, installing and loading Llama 2 directly on your computer is best.

 With that in mind, we've created a step-by-step guide on how to use Text-Generation-WebUI to load a quantized Llama 2 LLM locally on your computer.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![Select operating system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/4-select-operating-system.jpg)
3. Your anti-virus might create an alert; this is fine. The prompt is just an[antivirus false positive](https://www.makeuseof.com/what-is-antivirus-false-result/) for running a batch file or script. Click on**Run anyway** .
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Step 3: Download the Llama 2 Model

 There are quite a few things to consider when deciding which iteration of Llama 2 you need. These include parameters, quantization, hardware optimization, size, and usage. All of this information will be found denoted in the model's name.

* **Parameters:** The number of parameters used to train the model. Bigger parameters make more capable models but at the cost of performance.
* **Usage:** Can either be standard or chat. A chat model is optimized to be used as a chatbot like ChatGPT, while the standard is the default model.
* **Hardware Optimization:** Refers to what hardware best runs the model. GPTQ means the model is optimized to run on a dedicated GPU, while GGML is optimized to run on a CPU.
* **Quantization:** Denotes the precision of weights and activations in a model. For inferencing, a precision of q4 is optimal.
* **Size:** Refers to the size of the specific model.

 Note that some models may be arranged differently and may not even have the same types of information displayed. However, this type of naming convention is fairly common in the[HuggingFace](https://www.makeuseof.com/what-is-hugging-face-and-what-is-it-used-for/) Model library, so it's still worth understanding.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![HuggingFace model naming convention](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/huggingface-model-naming-convention-1.jpg)

 In this example, the model can be identified as a medium-sized Llama 2 model trained on 13 billion parameters optimized for chat inferencing using a dedicated CPU.

 For those running on a dedicated GPU, choose a**GPTQ** model, while for those using a CPU, choose**GGML** . If you want to chat with the model like you would with ChatGPT, choose**chat** , but if you want to experiment with the model with its full capabilities, use the**standard** model. As for parameters, know that using bigger models will provide better results at the expense of performance. I would personally recommend you start with a 7B model. As for quantization, use q4, as it's only for inferencing.

**Download:** [GGML](https://huggingface.co/localmodels/Llama-2-7B-ggml/tree/main) (Free)

**Download:** [GPTQ](https://huggingface.co/localmodels/Llama-2-7B-Chat-GPTQ/tree/main) (Free)

 Now that you know what iteration of Llama 2 you need, go ahead and download the model you want.

 In my case, since I'm running this on an ultrabook, I'll be using a GGML model fine-tuned for chat,**llama-2-7b-chat-ggmlv3.q4\_K\_S.bin.**

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Downloading Llama 2 model of your preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/8-download-llama-2-model.jpg)

 After the download is finished, place the model in**text-generation-webui-main** \>**models** .

![Placing Llama 2 model to model folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/9-place-model-to-model-folder.jpg)

 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

## Step 4: Configure Text-Generation-WebUI

Now, let's begin the configuration phase.

1. Once again, open Text-Generation-WebUI by running the**start\_(your OS)** file (see the previous steps above).
2. On the tabs located above the GUI, click**Model.** Click the refresh button at the model dropdown menu and select your model.
3. Now click on the dropdown menu of the**Model loader** and select**AutoGPTQ** for those using a GTPQ model and**ctransformers** for those using a GGML model. Finally, click on**Load** to load your model.  
![Setting model loader](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/10-select-model-loader.jpg)
4. To use the model, open the Chat tab and start testing the model.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Testing Llama 2 locally](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/12-testing-llama-2-locally.jpg)

 Congratulations, you've successfully loaded Llama2 on your local computer!

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-engineering-captivating-video-teasers-for-online-presence/"><u>[New] 2024 Approved  Engineering Captivating Video Teasers for Online Presence</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twittrek-toolkit-a-comprehensive-approach-to-saving-tweets-visuals/"><u>[New] 2024 Approved  TwitTrek Toolkit  A Comprehensive Approach to Saving Tweets' Visuals</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exploring-the-best-practices-for-online-cricket-watch/"><u>[Updated] Exploring the Best Practices for Online Cricket Watch</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ideal-illustration-tools-for-windows-no-cost-high-prices/"><u>[Updated] Ideal Illustration Tools for Windows  No Cost, High Prices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-birth-of-an-internet-persona-the-vtuber-blueprint/"><u>[Updated] In 2024, Birth of an Internet Persona – The VTuber Blueprint?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-top-7-enhancements-for-an-optimal-stardew-farming-experience/"><u>[Updated] Top 7 Enhancements for an Optimal Stardew Farming Experience</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-zootopias-freshest-startup-ideas/"><u>2024 Approved  Zootopia’s Freshest Startup Ideas</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-10-must-have-sound-recording-devices-for-broadcast-enthusiasts/"><u>2024 Approved 10 Must-Have Sound Recording Devices for Broadcast Enthusiasts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/7-effective-strategies-to-address-the-chatgpt-body-stream-error-a-comprehensive-guide/"><u>7 Effective Strategies to Address the ChatGPT Body Stream Error – A Comprehensive Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-enhanced-resume-craftsmayer-with-chatgpt-innovations/"><u>AI-Enhanced Résume Craftsmayer with ChatGPT Innovations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/archiving-made-simple-saving-chatgpt-talks/"><u>Archiving Made Simple: Saving ChatGPT Talks</u></a></li>
<li><a href="https://tech-revival.techidaily.com/artificial-intelligence-6-rise-of-creative-tools/"><u>Artificial Intelligence: 6 Rise of Creative Tools</u></a></li>
<li><a href="https://vp-tips.techidaily.com/best-jpg-to-gif-tools-online-free-and-easy-for-2024/"><u>Best JPG to GIF Tools Online, Free and Easy for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beyond-turing-exploring-modern-approaches-to-ai-evaluation/"><u>Beyond Turing: Exploring Modern Approaches to AI Evaluation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/build-your-web-presence-faster-how-chatgpt-can-assist-in-4-stages/"><u>Build Your Web Presence Faster: How ChatGPT Can Assist in 4 Stages</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-the-future-of-higher-education-have-traditional-papers-lost-their-relevance/"><u>ChatGPT and the Future of Higher Education: Have Traditional Papers Lost Their Relevance?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-on-your-pc-discover-why-it-trumps-the-web-interface-in-performance-and-convenience/"><u>ChatGPT on Your PC: Discover Why It Trumps the Web Interface in Performance and Convenience</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-strategies-for-climbing-the-corporate-ladder-and-achieving-employment-success/"><u>ChatGPT Strategies for Climbing the Corporate Ladder and Achieving Employment Success</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-creativity-in-3-bot-systems/"><u>Comparing Creativity in 3 Bot Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/crafting-secure-customized-workout-routines-by-chatgpt/"><u>Crafting Secure, Customized Workout Routines by ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevate-your-skills-with-openais-bug-bounty-program-eligibility-criteria-and-steps-to-participation-explained/"><u>Elevate Your Skills with OpenAI’s Bug Bounty Program – Eligibility Criteria and Steps to Participation Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/envisioned-epics-interactive-tales-using-chatgpt/"><u>Envisioned Epics: Interactive Tales Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/expert-advice-on-lifting-your-chatgpt-ban/"><u>Expert Advice on Lifting Your ChatGPT Ban</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-these-7-superior-options-beyond-openais-chatgpt-on-your-phone/"><u>Explore These 7 Superior Options: Beyond OpenAI's ChatGPT on Your Phone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-evolution-in-ai-language-models-comparing-gpt-4-to-gpt-(span-stylecolor-0000ff)35(span)/"><u>Exploring Evolution in AI Language Models: Comparing GPT-4 to GPT- <Span Style=color: #0000Ff>3.5</Span></u></a></li>
<li><a href="https://tech-revival.techidaily.com/fixing-high-traffic-errors-on-chatgpt-for-windows-users/"><u>Fixing High-Traffic Errors on ChatGPT for Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-the-power-of-ai-code-suggestions-using-microsoft-copilot-on-mac-computers/"><u>Harness the Power of AI Code Suggestions – Using Microsoft Copilot on Mac Computers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-realme-11-proplus-to-mac-drfone-by-drfone-android/"><u>How to Mirror Realme 11 Pro+ to Mac? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-nubia-red-magic-8s-proplus-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Nubia Red Magic 8S Pro+ Phone? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-a54-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy A54 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transforming-moments-samsungs-time-lapse-tutorial/"><u>In 2024, Transforming Moments  Samsung's Time-Lapse Tutorial</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-understanding-av1-your-initial-compre-point/"><u>In 2024, Understanding AV1  Your Initial Compre Point</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-pexels-a-photographers-toolkit/"><u>Mastering Pexels  A Photographer's Toolkit</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/maximizing-your-macbook-camera-a-recording-handbook/"><u>Maximizing Your MacBook Camera  A Recording Handbook</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-a-detailed-guide-to-making-your-pictures-speak/"><u>New A Detailed Guide to Making Your Pictures Speak</u></a></li>
<li><a href="https://review-topics.techidaily.com/new-iphone-14-pro-restore-from-icloud-stuck-on-time-remaining-estimating-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>New iPhone 14 Pro Restore from iCloud Stuck on Time Remaining Estimating | Stellar</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-ai-uprising-between-gemini-max-and-gptplusplus/"><u>The Ultimate AI Uprising: Between Gemini Max & GPT++</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-10-international-tech-visionaries-share-their-insights-on-artificeial-intelligence/"><u>Top 10 International Tech Visionaries Share Their Insights on Artificeial Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-5-no-cost-innovative-image-design-tools/"><u>Top 5 No-Cost, Innovative Image Design Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-thrilling-new-capabilities-of-bard-unveiled-at-google-io-2023-event/"><u>Top 7 Thrilling New Capabilities of BARD Unveiled at Google I/O 2023 Event</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-connection-errors-in-android-devices/"><u>Troubleshooting Connection Errors in Android Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-strong-artificial-intelligence-vs-weak-artificnient-intelligence/"><u>Understanding Strong Artificial Intelligence Vs. Weak Artificnient Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-7-ultimate-tools-with-artificial-intelligence-for-smart-presenting/"><u>Unveiling The 7 Ultimate Tools with Artificial Intelligence for Smart Presenting</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-mechanics-behind-ai-chatbots/"><u>Unveiling the Mechanics Behind AI Chatbots</u></a></li>
<li><a href="https://tech-revival.techidaily.com/using-conversational-ai-chatgpt-as-a-solution-for-alleviating-lonely-feelings/"><u>Using Conversational AI (ChatGPT) as a Solution for Alleviating Lonely Feelings</u></a></li>
<li><a href="https://tech-revival.techidaily.com/voicecommand-power-integrating-gpt-into-android-life/"><u>VoiceCommand Power – Integrating GPT Into Android Life</u></a></li>
<li><a href="https://tech-revival.techidaily.com/what-is-a-vector-database-and-how-do-they-boost-ai/"><u>What Is a Vector Database, and How Do They Boost AI?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-you-should-tap-into-chatgpts-expertise-for-medical-guidance-a-seven-point-guide/"><u>Why You Should Tap Into ChatGPT's Expertise for Medical Guidance: A Seven-Point Guide</u></a></li>
</ul></div>
