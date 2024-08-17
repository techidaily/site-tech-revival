---
title: "Ultimate Guide: Setting Up CodeGPT on Visual Studio Code"
date: 2024-08-16T14:02:48.823Z
updated: 2024-08-17T14:02:48.823Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Ultimate Guide: Setting Up CodeGPT on Visual Studio Code"
excerpt: "This Article Describes Ultimate Guide: Setting Up CodeGPT on Visual Studio Code"
thumbnail: https://thmb.techidaily.com/d8d6563b1e83446e0eb6eee844ba3f9b3df6929eaff9c17a0488818cf8023092.jpg
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
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install-Desktop-Development-With-C++](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/2-install-desktop-development-with-c.jpg)

 Now that you have Desktop development with C++ installed, it's time to download the Text-Generation-WebUI one-click installer.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
4. A terminal will open and start the setup. Early on, the setup will pause and ask you what GPU you are using. Select the appropriate type of GPU installed on your computer and hit enter. For those without a dedicated graphics card, select**None (I want to run models in CPU mode)** . Keep in mind that running on CPU mode is much slower when compared to running the model with a dedicated GPU.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Selecting GPU hardware installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/5-select-gpu-settings.jpg)
5. Once the setup is complete, you can now launch Text-Generation-WebUI locally. You can do so by opening your preferred web browser and entering the provided IP address on the URL.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![How to launch-Text-Generation-WebUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/6-launch-text-generation-webui.jpg)
6. The WebUI is now ready for use.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![Text-Generation-WebUI ](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/7-text-generation-webui-view.jpg)

 However, the program is only a model loader. Let's download Llama 2 for the model loader to launch.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
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

 Now that you have your model downloaded and placed in the model folder, it's time to configure the model loader.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-new-age-monetization-cost-effective-channel-options/"><u>[New] 2024 Approved  New Age Monetization  Cost-Effective Channel Options</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-diving-into-the-depths-with-gopro-hero5/"><u>[New] Diving Into the Depths with GoPro Hero5</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-control-center-creator-studio-essentials-for-2024/"><u>[Updated] Channel Control Center  Creator Studio Essentials for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-from-clicks-to-coins-mastering-the-art-of-earnings-through-fb-videos/"><u>[Updated] From Clicks to Coins  Mastering the Art of Earnings Through FB Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-eliminate-hurdle-video-playback-issue-in-chrome/"><u>[Updated] In 2024, Eliminate Hurdle  Video Playback Issue in Chrome</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-quick-methods-for-saving-videos-on-youtube-for-2024/"><u>[Updated] Quick Methods for Saving Videos on YouTube for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gamings-new-leaders-1-ranked-4k-laptops/"><u>2024 Approved  Gaming's New Leaders  #1 Ranked 4K Laptops</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-visual-impact-mastering-thumbnail-dimensions/"><u>2024 Approved  YouTube Visual Impact  Mastering Thumbnail Dimensions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/choosing-an-ai-sidekick-on-snapchat-myai-or-chatgpt/"><u>Choosing an AI Sidekick on Snapchat: MyAI or ChatGPT?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/claude-vs-chatgpt-face-off-the-ultimate-guide-to-picking-the-best-ai-for-your-daily-needs/"><u>Claude Vs. ChatGPT Face-Off: The Ultimate Guide to Picking the Best AI for Your Daily Needs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1723262386964-conquer-fathers-day-with-an-elite-ibuypower-gaming-computer-present/"><u>Conquer Father's Day with an Elite iBUYPOWER Gaming Computer Present</u></a></li>
<li><a href="https://tech-revival.techidaily.com/critical-insights-into-8-issues-faced-with-openais-chatgpt/"><u>Critical Insights Into 8 Issues Faced With OpenAI's ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/deciphering-the-facts-critical-analysis-in-ai-health-advice/"><u>Deciphering the Facts: Critical Analysis in AI Health Advice</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-ai-opinions-of-10-international-technology-authorities-shaping-the-industry/"><u>Decoding AI: Opinions of 10 International Technology Authorities Shaping the Industry</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-mystery-of-ai-black-boxes-and-their-working-dynamics/"><u>Decoding the Mystery of AI Black Boxes and Their Working Dynamics</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-9-basic-ai-tools-perfect-for-starters/"><u>Discover 9 Basic AI Tools Perfect for Starters</u></a></li>
<li><a href="https://tech-revival.techidaily.com/dive-into-ai-9-essential-forums-for-newbies-to-master-tools-and-techniques/"><u>Dive Into AI: 9 Essential Forums for Newbies to Master Tools and Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/easy-instructions-for-integrating-chatgpt-into-windows-applications/"><u>Easy Instructions for Integrating ChatGPT Into Windows Applications</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevate-your-search-experience-why-perplexity-reigns-as-the-supreme-ai-powered-tool-for-google-queries/"><u>Elevate Your Search Experience: Why Perplexity Reigns as the Supreme AI-Powered Tool for Google Queries</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elevating-image-quality-with-expert-usage-of-ps-3d-color-grading/"><u>Elevating Image Quality with Expert Usage of PS 3D Color Grading</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-bard-top-7-improvements-from-googles-palm-2/"><u>Enhancing Bard: Top 7 Improvements From Google's PaLM 2</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-privacy-chatgpt-and-vpn-synergy/"><u>Enhancing Privacy: ChatGPT and VPN Synergy?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-the-benefits-of-auto-gpt-as-an-alternative-to-waiting-for-gpt-4/"><u>Evaluating the Benefits of Auto-GPT as an Alternative to Waiting for GPT-4</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-your-creative-genius-utilizing-free-dall-e-3-via-microsoft-bing/"><u>Harness Your Creative Genius: Utilizing Free DALL-E 3 via Microsoft Bing</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-do-vector-databases-contribute-to-advancements-in-ai/"><u>How Do Vector Databases Contribute to Advancements in AI?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-predictive-ai-anticipate-the-future-exploring-its-inner-workings/"><u>How Does Predictive AI Anticipate the Future? Exploring Its Inner Workings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-vivo-y36i-devices-by-drfone-android/"><u>How to Reset Gmail Password on Vivo Y36i Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-craft-precise-notes-using-mematic-software/"><u>In 2024, Craft Precise Notes Using Mematic Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-creativity-with-the-best-online-screen-changers/"><u>In 2024, Unleash Creativity with the Best Online Screen Changers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-zooming-into-success-the-essential-blueprint-for-producing-high-quality-audio-on-video-platforms/"><u>In 2024, Zooming Into Success  The Essential Blueprint for Producing High-Quality Audio on Video Platforms</u></a></li>
<li><a href="https://extra-tips.techidaily.com/inexpensive-chinese-virtual-reality-helmets/"><u>Inexpensive Chinese Virtual Reality Helmets</u></a></li>
<li><a href="https://tech-revival.techidaily.com/interactive-evolution-6-ways-ai-transforms-video-game-scriptwriting/"><u>Interactive Evolution: 6 Ways AI Transforms Video Game Scriptwriting</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-gemini-by-google-a-worthy-contender-against-microsofts-popular-chatgpt-platform/"><u>Is Gemini by Google a Worthy Contender Against Microsoft's Popular ChatGPT Platform?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-ai-synergy-delving-into-the-complexities-of-aligning-machine-goals/"><u>Mastering AI Synergy: Delving Into the Complexities of Aligning Machine Goals</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/maximizing-conversions-with-targeted-snapad-strategies-for-2024/"><u>Maximizing Conversions with Targeted SnapAd Strategies for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigate-through-idea-stagnation-with-these-5-ai-assistants/"><u>Navigate Through Idea Stagnation With These 5 AI Assistants</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/navigating-googles-augmented-reality-adornments/"><u>Navigating Google's Augmented Reality Adornments</u></a></li>
<li><a href="https://tech-revival.techidaily.com/nonewsubs-when-will-chatgpt-welcome-again/"><u>NoNewSubs: When Will ChatGPT Welcome Again?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/perfect-your-palate-with-ai-enhanced-gourmet-guidance/"><u>Perfect Your Palate with AI-Enhanced Gourmet Guidance</u></a></li>
<li><a href="https://tech-revival.techidaily.com/prompt-engineering-job-outlook-nine-parameters-that-determine-its-validity-and-opportunities/"><u>Prompt Engineering Job Outlook: Nine Parameters That Determine Its Validity and Opportunities</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-productivity-at-no-cost-experience-gpt-4-turbo-enhanced-by-copilot/"><u>Revolutionize Productivity at No Cost - Experience GPT-4 Turbo Enhanced by Copilot</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-self-care-top-9-chatgpt-tips-for-improved-health/"><u>Revolutionize Self-Care: Top 9 ChatGPT Tips for Improved Health</u></a></li>
<li><a href="https://tech-revival.techidaily.com/seamless-communication-via-chatgpts-api/"><u>Seamless Communication via ChatGPT's API</u></a></li>
<li><a href="https://tech-revival.techidaily.com/six-perspectives-on-snapchats-my-ai-demonstrating-its-capabilities-beyond-just-entertainment-gadgetry/"><u>Six Perspectives on Snapchat's My AI: Demonstrating Its Capabilities Beyond Just Entertainment Gadgetry</u></a></li>
<li><a href="https://tech-revival.techidaily.com/streamlining-content-creation-with-advanced-ai-tools/"><u>Streamlining Content Creation with Advanced AI Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/talking-with-precision-exclusive-chatgpt-plus-plan-for-us-at-20mth/"><u>Talking with Precision: Exclusive ChatGPT Plus Plan for US at $20/Mth</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-7-critical-issues-with-adopting-generative-ai-for-text-based-communications/"><u>The 7 Critical Issues with Adopting Generative AI for Text-Based Communications</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-departure-of-ceo-sam-altman-from-openai-future-directions-for-chatgpt/"><u>The Departure of CEO Sam Altman From OpenAI - Future Directions for ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-overcome-directdraw-challenges-in-11-series-windows/"><u>Unveiling the Secrets to Overcome DirectDraw Challenges in 11-Series Windows</u></a></li>
</ul></div>
