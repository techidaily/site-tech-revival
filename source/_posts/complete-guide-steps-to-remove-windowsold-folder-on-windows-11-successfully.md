---
title: "Complete Guide: Steps to Remove 'Windows.old' Folder on Windows 11 Successfully"
date: 2024-08-16T13:06:09.845Z
updated: 2024-08-17T13:06:09.845Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Complete Guide: Steps to Remove 'Windows.old' Folder on Windows 11 Successfully"
excerpt: "This Article Describes Complete Guide: Steps to Remove 'Windows.old' Folder on Windows 11 Successfully"
thumbnail: https://thmb.techidaily.com/1b6d7be592f2912a27c2919b7274dc65400897b1c72eb15814464402850a760a.jpg
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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## **2\. Use DISM Tool**

**DISM**  stands for Deployment Image & Servicing Management. It is a tool that allows you to make changes to Windows features, packages, drivers, and international settings. In this case, we will use it to help us clean up our WinSxS folder.

 The process may take a long time. It some cases, it could take up to 30 minutes. Please don’t worry when it’s not finished after a long time. Please be patient until the process finishes.

 1) On your keyboard, press **Windows logo key**   and **X**   at the same time, then choose **Command Prompt (Admin)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1bb42138.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 When prompted with the UAC, hit **Yes** to continue.

 2) In DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup

 This command helps you clean up files when your system is not in use.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c1fc428ac.png)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Check for possible typo. Then hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c4b394177.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->

 4) In the same DISM window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /StartComponentCleanup /ResetBase

 This command helps you remove all superseded versions of every component in the component store.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c546794f7.png)

 5) Make sure you have made no typo and hit**Enter** . Wait for it to finish.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c55d520c4.png)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 6) Still in the same window, type in or copy and paste in the following command:

Dism.exe /online /Cleanup-Image /SPSuperseded

 This command helps you reduce the amount of space used by a Service Pack.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5c8b3c70.png)

7) Make sure that you have made no typo and hit Enter.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_5975c5eb65aaf.png)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-boost-views-via-strategic-tagging-tactics/"><u>[New] 2024 Approved  Boost Views via Strategic Tagging Tactics</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-from-live-streams-to-recorded-content-navigating-aiseesofts-features/"><u>[New] 2024 Approved  From Live Streams to Recorded Content  Navigating Aiseesoft's Features</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-make-big-bucks-fast-with-a-focus-on-youtube-short-video-creation/"><u>[New] 2024 Approved  Make Big Bucks Fast with a Focus on YouTube Short Video Creation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-cheap-not-bad-chromebooks-top-recording-tools/"><u>[New] Cheap Not Bad – Chromebook's Top Recording Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-ranking-the-best-ios-devices-tools-to-download-fb-movies-and-tunes/"><u>[New] Ranking the Best iOS Devices' Tools to Download FB Movies & Tunes</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-blockade-8-steps-to-resolving-windows-10s-error-code-0x800f0922-during-updates/"><u>Bypassing the Blockade: 8 Steps to Resolving Windows 10'S Error Code 0X800F0922 During Updates</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comparative-costs-yt-vs-other-platforms/"><u>Comparative Costs  YT vs Other Platforms</u></a></li>
<li><a href="https://screen-recording.techidaily.com/comprehensive-iptv-accessibility-for-2024/"><u>Comprehensive IPTV Accessibility for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172637216-discover-the-ultimate-gba-experience-for-iphoneipad-users/"><u>Discover the Ultimate GBA Experience for iPhone/iPad Users!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ensuring-data-security-when-utilizing-tailored-gpt-models-like-chatgpt/"><u>Ensuring Data Security When Utilizing Tailored GPT Models Like ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-the-reliability-of-chatgpt-and-bard-in-providing-solid-financial-recommendations/"><u>Evaluating the Reliability of ChatGPT and Bard in Providing Solid Financial Recommendations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/expand-your-ai-interaction-horizons-duckduckgos-discreet-chat-alternatives-to-chatgpt/"><u>Expand Your AI Interaction Horizons: DuckDuckGo's Discreet Chat Alternatives to ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-ai-boundaries-the-challenge-for-chatgpt-in-identifying-its-generated-content/"><u>Exploring AI Boundaries: The Challenge for ChatGPT in Identifying Its Generated Content</u></a></li>
<li><a href="https://tech-revival.techidaily.com/fight-feelings-of-loneliness-through-ai-powered-dialogue-discover-how/"><u>Fight Feelings of Loneliness Through AI-Powered Dialogue - Discover How!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-concept-to-creation-mastering-ai-image-generation-with-copilot/"><u>From Concept to Creation: Mastering AI Image Generation with Copilot</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-creative-webps-to-standard-pngjpg-with-dall-e-3-techniques/"><u>From Creative WebPs to Standard PNG/JPG with DALL-E 3 Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/get-unlimited-global-reach-with-chatgpt-and-its-everywhere-feature/"><u>Get Unlimited Global Reach with ChatGPT and Its 'Everywhere' Feature</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-openais-shap-enhance-model-insight/"><u>How Does OpenAI's SHAP Enhance Model Insight?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-ensure-your-private-data-stays-confidential-with-adapted-gpt-models/"><u>How to Ensure Your Private Data Stays Confidential with Adapted GPT Models</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-restore-and-access-previous-chatgpt-interactions-efficiently/"><u>How to Restore and Access Previous ChatGPT Interactions Efficiently</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-vivo-y36-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Vivo Y36 without App | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-6-ways-to-record-mov-files-on-windows-10/"><u>In 2024, 6 Ways to Record .mov Files on Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-infinix-hot-30-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Infinix Hot 30 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-synchronized-device-tutorial-for-efficient-movie-logging/"><u>In 2024, Synchronized Device Tutorial for Efficient Movie Logging</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-techniques-for-smoothing-meetings-backgrounds-in-teams/"><u>In 2024, Techniques for Smoothing Meetings' Backgrounds in Teams</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-techniques-to-generate-professional-photos-with-dall-e-and-gpt-4-combined/"><u>Innovative Techniques to Generate Professional Photos with DALL-E and GPT-4 Combined</u></a></li>
<li><a href="https://tech-revival.techidaily.com/insight-into-how-businesses-are-restricting-ai-engagement-tools/"><u>Insight Into How Businesses Are Restricting AI Engagement Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/insights-on-why-companies-are-wary-of-conversational-ai-tools/"><u>Insights on Why Companies Are Wary of Conversational AI Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-chatgpt-a-potential-tool-for-developing-malicious-software/"><u>Is ChatGPT a Potential Tool for Developing Malicious Software?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-chatgpt-identifying-and-fixing-the-six-most-common-errors/"><u>Mastering ChatGPT: Identifying & Fixing the Six Most Common Errors</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-14-essential-vlog-video-editors-for-youtube-tiktok-and-more-free-and-paid/"><u>New 2024 Approved 14 Essential Vlog Video Editors for YouTube, TikTok, and More Free & Paid</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-online-video-creation-made-easy-with-wevideo/"><u>New Online Video Creation Made Easy with WeVideo</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/peak-business-sky-storage-for-firms-for-2024/"><u>Peak Business Sky-Storage for Firms for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/prioritize-value-discard-the-unnecessary-gpt-enhancements/"><u>Prioritize Value: Discard the Unnecessary GPT Enhancements</u></a></li>
<li><a href="https://tech-revival.techidaily.com/projections-in-machine-learning-when-will-gpt-5-emerge/"><u>Projections in Machine Learning: When Will GPT-5 Emerge?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/resolve-iphone-issues-with-chatgpt-discover-these-9-effective-fixes/"><u>Resolve iPhone Issues with ChatGPT: Discover These 9 Effective Fixes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionizing-image-design-combining-dall-e-with-chatgpt-4/"><u>Revolutionizing Image Design: Combining DALL-E with ChatGPT-4</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/saving-smiles-techniques-for-capturing-twitters-gifs/"><u>Saving Smiles  Techniques for Capturing Twitter's GIFs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/side-hustle-mastery-chatgpt-like-earning-avenues-pc-building-best-practices-and-tips-for-a-thriving-vintage-handheld-game-collection/"><u>Side Hustle Mastery: ChatGPT-Like Earning Avenues, PC Building Best Practices & Tips for a Thriving Vintage Handheld Game Collection</u></a></li>
<li><a href="https://tech-revival.techidaily.com/simple-steps-transforming-your-dall-e-3-creations-from-webp-format-into-jpeg-and-png/"><u>Simple Steps: Transforming Your DALL-E 3 Creations From WebP Format Into JPEG and PNG</u></a></li>
<li><a href="https://tech-revival.techidaily.com/standard-copybot-or-copybot-plus-decoding-the-benefits-to-guide-your-choice/"><u>Standard Copybot or Copybot Plus? Decoding the Benefits to Guide Your Choice</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-into-the-custom-gpt-experience-with-openai-access-and-tips-for-instant-use/"><u>Step Into the Custom GPT Experience with OpenAI – Access and Tips for Instant Use</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-apple-iphone-6-here-is-the-answer-drfone-by-drfone-virtual-ios/"><u>Wondering the Best Alternative to Hola On Apple iPhone 6? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
