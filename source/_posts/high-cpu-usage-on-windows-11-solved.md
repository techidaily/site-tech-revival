---
title: High CPU Usage on Windows 11 [Solved]
date: 2024-08-16T13:06:22.820Z
updated: 2024-08-17T13:06:22.820Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes High CPU Usage on Windows 11 [Solved]
excerpt: This Article Describes High CPU Usage on Windows 11 [Solved]
thumbnail: https://thmb.techidaily.com/965654acbd64cd762e18be6423e980e53d1c3fa7dd1512b5cfdc18b0e2b93a57.jpg
---

## WinSxS Folder: Clean Up and Save Space on Windows 11 Easily

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_59759c33baabd.png)

 This is among the usually asked questions: can I delete WinSxS folder to free up some disk space?

The answer is, no.

 Nor can you delete everything in the WinSxS folder, because some of the files are important for Windows to run and update. Basically, WinSxS folder is where the files needed for your Windows are, as well as backups and/or updates of those files.

 But there are many ways you can use to reduce the size for your WinSxS folder on Windows 10\. In this post, we will be introducing two of them. So you will at least have one option that works.

[**1. Use Disk Cleanup**](https://tools.techidaily.com/drivereasy/download/)

[**2. Use DISM Tool**](https://tools.techidaily.com/drivereasy/download/)

**WARNING** : It is never suggested that you use a third-party tool to cleanup your WinSxS file, since faulty deleting the whole folder or some files in the folder might end up breaking your computer, making it impossible to boot or update.

## **1\. Use Disk Cleanup**

 Disk cleanup is a built-in tool that helps you delete temporary files. To run it, just follow:

 1) On your keyboard, press**Windows logo** button, then type in**disk cleanup** . Then choose**Disk Cleanup** from the list.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b754c83e3.png)

 2) If you haven’t changed the location where you placed your system file, choose**(C:)** and click**OK** . If you have changed the file location before, choose the correct file directory accordingly.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975b948ea778.png)

 3) Under**Files to delete** sector, tick the boxes before the files you don’t need anymore and then hit**OK** to delete them. Select to highlight the file name to see more detailed information if you want.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bc59c244b.png)

 4) If you need to free more space, you can also choose**Clean up system files** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf02990e3.png)

 Then you will be prompted to choose which system drive you want to clean up. Choose accordingly and the clean process will start right away.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975bf68b4ff6.png)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->

 If you need more assistance, feel free to leave us comment and we will see what else we can do to help.

Hope your problem solved!

* [system](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-art-of-connecting-a-deep-dive-into-instagram-live/"><u>[New] 2024 Approved  The Art of Connecting  A Deep Dive Into Instagram Live</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-perfect-pics-how-to-capture-your-chromebook-screen-in-four-easy-steps/"><u>[New] In 2024, Perfect Pics  How to Capture Your Chromebook Screen in Four Easy Steps</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-zero-price-screen-recording-easy-on-pc-and-mac/"><u>[New] Zero Price Screen Recording - Easy on PC & Mac</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-discovering-the-secret-to-engaging-content-with-aspect-ratios-in-youtube/"><u>[Updated] 2024 Approved  Discovering the Secret to Engaging Content with ASPECT RATIOS in YOUTUBE</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-mobile-communication-redefined-best-10-secured-free-video-call-apps-to-keep-you-covered-on-devices/"><u>[Updated] 2024 Approved  Mobile Communication Redefined  Best 10 Secured, Free Video Call Apps to Keep You Covered on Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-awaitingnewagecameratechnologies/"><u>[Updated] In 2024, AwaitingNewAgeCameraTechnologies</u></a></li>
<li><a href="https://article-tips.techidaily.com/20-best-video-editors-compatible-with-dji-videos-for-2024/"><u>20 Best Video Editors Compatible with DJi Videos for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-top-10-strategies-for-crafting-engaging-podcast-graphics/"><u>2024 Approved  Top 10 Strategies for Crafting Engaging Podcast Graphics</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-ultimate-top-quality-hd-screen-capture-tools/"><u>2024 Approved  Ultimate Top-Quality HD Screen Capture Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/22-streamline-communication-leading-free-ai-email-services/"><u>22 Streamline Communication: Leading Free AI Email Services</u></a></li>
<li><a href="https://tech-revival.techidaily.com/6-human-techniques-for-mastering-creative-writing-against-ais/"><u>6 Human Techniques for Mastering Creative Writing Against AIs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-comprehensive-guide-to-generating-ai-masterpieces-with-the-help-of-chatgpt-technology/"><u>A Comprehensive Guide to Generating AI Masterpieces with the Help of ChatGPT Technology</u></a></li>
<li><a href="https://tech-revival.techidaily.com/assessing-if-top-tier-ai-prompts-merit-their-price/"><u>Assessing If Top-Tier AI Prompts Merit Their Price</u></a></li>
<li><a href="https://tech-revival.techidaily.com/avoid-installing-google-bard-potential-risks-of-harmful-software/"><u>Avoid Installing Google Bard: Potential Risks of Harmful Software</u></a></li>
<li><a href="https://tech-revival.techidaily.com/banks-vs-ai-are-your-assets-safe-from-gpt-inspired-cyberthreats/"><u>Banks vs AI: Are Your Assets Safe From GPT-Inspired Cyberthreats?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-your-brainpower-advanced-strategies-for-conceptualizing-with-mindmaps-and-chatgpt/"><u>Boost Your Brainpower: Advanced Strategies for Conceptualizing with Mindmaps and ChatGPT</u></a></li>
<li><a href="https://games-able.techidaily.com/bridging-wi-fi-gaps-for-switch-users/"><u>Bridging Wi-Fi Gaps for Switch Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-you-trust-chatgpt-to-keep-your-conversations-confidential/"><u>Can You Trust ChatGPT to Keep Your Conversations Confidential?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/challenge-the-chatgpt-token-count-norms/"><u>Challenge the ChatGPT Token Count Norms</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diagnosing-and-repairing-connection-woes-with-paramountplus-streaming-on-firestick/"><u>Diagnosing and Repairing Connection Woes with Paramount+ Streaming on Firestick</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-zte-nubia-flip-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does ZTE Nubia Flip 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dreamscapes-on-display-a-film-study/"><u>Dreamscapes on Display  A Film Study</u></a></li>
<li><a href="https://driver-error.techidaily.com/easy-steps-to-update-and-download-drivers-for-the-hp-envy-20/"><u>Easy Steps to Update and Download Drivers for the HP Envy 20</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/echo-of-tamil-syncing-songs-as-mobile-notifications/"><u>Echo of Tamil  Syncing Songs as Mobile Notifications</u></a></li>
<li><a href="https://printer-issues.techidaily.com/elevate-hp-officejet-4630-latest-software-releases/"><u>Elevate HP Officejet 4630: Latest Software Releases</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/essential-empowerment-packages-top-trending-products-for-todays-entrepreneur-for-2024/"><u>Essential Empowerment Packages  Top Trending Products for Today's Entrepreneur for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-analysis-and-reviews-for-the-cost-effective-dell-g5-5090-gaming-desktop-with-endless-customization-possibilities/"><u>Expert Analysis & Reviews for the Cost-Effective Dell G5 5090 Gaming Desktop with Endless Customization Possibilities</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-on-iphone-14-pro-max-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock On iPhone 14 Pro Max?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-preventing-shake-in-photographic-imagery/"><u>In 2024, Preventing Shake in Photographic Imagery</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-multimedia-how-to-teach-chatgpt-to-interpret-pdf-documents/"><u>Mastering Multimedia: How to Teach ChatGPT to Interpret PDF Documents</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/mastering-video-synchronization-with-obs/"><u>Mastering Video Synchronization with OBS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/microsoft-enhances-bing-with-advanced-ai-features-discover-the-future-of-search/"><u>Microsoft Enhances Bing with Advanced AI Features - Discover the Future of Search</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mistral-ais-le-chat-face-off-with-chatgpt-insights-from-a-real-user-test/"><u>Mistral AI’s Le Chat Face-Off with ChatGPT – Insights From a Real User Test</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-digital-landscape-a-guide-to-identifying-recent-twitter-scams-understanding-metas-new-verification-system-and-exploring-the-capabilities-of-c1/"><u>Navigating the Digital Landscape: A Guide to Identifying Recent Twitter Scams, Understanding Meta's New Verification System & Exploring the Capabilities of ChatGPT-4</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-pitfalls-why-you-might-want-to-skip-chatgpt-in-the-mac-app-store/"><u>Navigating the Pitfalls: Why You Might Want to Skip ChatGPT in the Mac App Store</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-through-the-ultimate-guide-to-top-9-free-logos-for-2024/"><u>Navigating Through The Ultimate Guide to Top 9 Free Logos for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-ultimate-pathway-to-uniform-audio-dynamics-in-three-steps/"><u>New The Ultimate Pathway to Uniform Audio Dynamics in Three Steps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/pilot-prowess-explained-from-basic-to-advanced-flight/"><u>Pilot Prowess Explained: From Basic to Advanced Flight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-google-chrome-windows-files-not-syncing-problem/"><u>Resolve Google Chrome: Windows Files Not Syncing Problem</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revealing-the-ratio-why-does-chatgpt-4-run-roughly/"><u>Revealing the Ratio: Why Does ChatGPT-4 Run Roughly?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionizing-team-sessions-with-chatgpt-integration/"><u>Revolutionizing Team Sessions with ChatGPT Integration</u></a></li>
<li><a href="https://tech-revival.techidaily.com/sensing-souls-in-silicon-is-ais-grasp-on-emotion-complete/"><u>Sensing Souls in Silicon: Is AI's Grasp on Emotion Complete?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/simplify-your-life-with-winchatgpt-app/"><u>Simplify Your Life with WinChatGPT App</u></a></li>
<li><a href="https://extra-support.techidaily.com/sj6-ultimate-face-off-with-xiaomis-yi-4k-genius-for-2024/"><u>SJ6 Ultimate Face-Off with Xiaomi's Yi 4K Genius for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/spearhead-your-proposals-with-intelligent-chatgpt-tech/"><u>Spearhead Your Proposals with Intelligent ChatGPT Tech</u></a></li>
<li><a href="https://tech-revival.techidaily.com/stay-connected-anywhere-the-ultimate-guide-to-activating-chatgpt-through-chatgpt-everywhere/"><u>Stay Connected Anywhere: The Ultimate Guide to Activating ChatGPT Through 'ChatGPT Everywhere'</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-to-utilizing-agentgpt-for-ai-agent-deployment-in-your-browser/"><u>Step-by-Step Guide to Utilizing AgentGPT for AI Agent Deployment in Your Browser</u></a></li>
<li><a href="https://tech-revival.techidaily.com/streamline-your-workflow-6-chatgpt-add-ons-you-should-reconsider-using/"><u>Streamline Your Workflow: 6 ChatGPT Add-Ons You Should Reconsider Using</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ten-tech-titans-insights-on-artificial-intelligence-an-in-depth-analysis/"><u>Ten Tech Titans' Insights on Artificial Intelligence: An In-Depth Analysis</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-essentials-of-using-llama-2-for-business-success/"><u>The Essentials of Using Llama 2 for Business Success</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-evolving-battleground-of-digital-defenses/"><u>The Evolving Battleground of Digital Defenses</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-4-benefits-of-using-chatgpt-for-your-custom-website-creation/"><u>Top 4 Benefits of Using ChatGPT for Your Custom Website Creation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-tips-leveraging-chatgpt-for-your-ideal-tv-show-selection/"><u>Top Tips: Leveraging ChatGPT for Your Ideal TV Show Selection</u></a></li>
<li><a href="https://fox-that.techidaily.com/turn-off-unwanted-rings-staying-silent-on-your-ipad-when-your-iphone-is-active/"><u>Turn Off Unwanted Rings: Staying Silent on Your iPad When Your iPhone Is Active</u></a></li>
<li><a href="https://tech-revival.techidaily.com/twitter-swindles-meet-the-new-meta-signature/"><u>Twitter Swindles: Meet the New Meta Signature</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-slowdown-an-analysis-of-chatgpt-4-vs-chatgpt-35-speeds/"><u>Understanding the Slowdown: An Analysis of ChatGPT-4 vs ChatGPT-3.5 Speeds</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-optimal-video-playback-by-tuning-speed-in-snapchat/"><u>Unlock Optimal Video Playback by Tuning Speed in Snapchat</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-global-access-how-to-use-chatgpt-with-the-portable-app-chatgpt-everywhere/"><u>Unlocking Global Access: How to Use ChatGPT with the Portable App 'ChatGPT Everywhere'</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-potential-in-ai-interaction-navigating-anthropics-claude-3-platform/"><u>Unlocking Potential in AI Interaction: Navigating Anthropic's Claude 3 Platform</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-7-high-quality-replacements-for-your-search-beyond-chatgpt/"><u>Unveiling 7 High-Quality Replacements for Your Search: Beyond ChatGPT</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-how-to-use-voice-recorder-on-samsung-s10s9-for-2024/"><u>Updated How to Use Voice Recorder on Samsung S10/S9 for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-modifying-gpt-is-a-complex-task/"><u>Why Modifying GPT Is a Complex Task</u></a></li>
<li><a href="https://tech-revival.techidaily.com/your-one-of-a-kind-text-experience-openais-gpt-marketplace/"><u>Your One-of-a-Kind Text Experience – OpenAI's GPT Marketplace</u></a></li>
</ul></div>
