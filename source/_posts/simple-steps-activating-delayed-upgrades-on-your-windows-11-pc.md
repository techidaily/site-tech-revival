---
title: "Simple Steps: Activating Delayed Upgrades on Your Windows 11 PC"
date: 2024-08-16T13:09:12.366Z
updated: 2024-08-17T13:09:12.366Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Simple Steps: Activating Delayed Upgrades on Your Windows 11 PC"
excerpt: "This Article Describes Simple Steps: Activating Delayed Upgrades on Your Windows 11 PC"
thumbnail: https://thmb.techidaily.com/26c79816e74e12a8f414621a79d8575a6f7513edd59ad13bbdba2af26e7005b7.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-from-viral-beats-to-ringtones-transforming-tiktok-sounds/"><u>[Updated] 2024 Approved  From Viral Beats to Ringtones  Transforming TikTok Sounds</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-what-lies-beneath-the-true-meanings-in-emoji/"><u>[Updated] 2024 Approved  What Lies Beneath  The True Meanings in Emoji</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-leading-popular-instagram-after-effects-designs/"><u>[Updated] Leading Popular Instagram After Effects Designs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-ultimate-guide-to-instas-trendy-filters-for-2024/"><u>[Updated] The Ultimate Guide to Insta's Trendy Filters for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/an-insiders-look-into-the-art-of-repairing-faulty-videos-a-comprehensive-guide-to-mending-video-irregularities-including-tips-on-subtitles/"><u>An Insider's Look Into the Art of Repairing Faulty Videos - A Comprehensive Guide to Mending Video Irregularities (Including Tips on Subtitles)</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-windows-n10-unknown-usb-device-and-port-reset-errors/"><u>Effective Fixes for Windows N10: Unknown USB Device and Port Reset Errors</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-alternatives-gpt-4-vs-gpt-4-turbo-vs-gpt-4o-explained/"><u>Exploring Alternatives: GPT-4 Vs. GPT-4 Turbo Vs. GPT-4o Explained</u></a></li>
<li><a href="https://tech-revival.techidaily.com/generate-stunning-visuals-using-dall-e-3-for-free-on-microsoft-bing-platform/"><u>Generate Stunning Visuals Using DALL-E 3 for Free on Microsoft Bing Platform</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-to-resolving-plugin-service-interruptions-in-chatgpt/"><u>Guide to Resolving Plugin Service Interruptions in ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-mastering-the-art-of-inserting-gpt-references-into-chatgpt-interactions/"><u>Guide: Mastering the Art of Inserting GPT References Into ChatGPT Interactions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on OnePlus Ace 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-lava-blaze-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Lava Blaze Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-storytelling-mastering-characters-with-precise-gpt-prompts/"><u>Innovative Storytelling: Mastering Characters with Precise GPT Prompts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-best-practices-for-video-editing-and-cropping-for-2024/"><u>Instagram's Best Practices for Video Editing & Cropping for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/latest-information-accessibility-for-everyone/"><u>Latest Information Accessibility for Everyone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leveraging-ai-how-chatgpt-can-revolutionize-your-poetry-book-writing-process/"><u>Leveraging AI: How ChatGPT Can Revolutionize Your Poetry Book Writing Process</u></a></li>
<li><a href="https://tech-revival.techidaily.com/leveraging-vector-database-technology-to-supercharge-artificial-intelligence/"><u>Leveraging Vector Database Technology to Supercharge Artificial Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-chatgpt-guide-to-activating-its-newly-released-beta-browsing-capabilities-and-add-ons/"><u>Mastering ChatGPT: Guide to Activating Its Newly Released Beta Browsing Capabilities and Add-Ons</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-convincing-proposal-writing-using-chatgpt/"><u>Mastering Convincing Proposal Writing Using ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastermind-techniques-using-cognitive-mapping-and-gpt-powered-bots-to-spark-innovation/"><u>Mastermind Techniques: Using Cognitive Mapping & GPT-Powered Bots to Spark Innovation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastery-over-ai-solving-the-alignment-control-conundrum/"><u>Mastery Over AI: Solving the Alignment Control Conundrum</u></a></li>
<li><a href="https://tech-revival.techidaily.com/questioning-the-reliability-of-zerogpt-and-similar-tech-tools/"><u>Questioning the Reliability of ZeroGPT & Similar Tech Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/redefine-your-document-creation-10-must-have-ai-apps/"><u>Redefine Your Document Creation: 10 Must-Have AI Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/resolving-chatgpt-access-issues-quickly/"><u>Resolving ChatGPT Access Issues Quickly</u></a></li>
<li><a href="https://tech-revival.techidaily.com/sharpen-your-writing-skills-eliminate-errors-with-chatgpt-insights/"><u>Sharpen Your Writing Skills – Eliminate Errors with ChatGPT Insights</u></a></li>
<li><a href="https://tech-revival.techidaily.com/stop-mingling-siri-and-chatgpt-differentiate-them-now/"><u>Stop Mingling Siri & ChatGPT: Differentiate Them Now</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-downside-of-generative-ai-in-text-messaging-services-7-key-points-to-consider/"><u>The Downside of Generative AI in Text Messaging Services - 7 Key Points to Consider</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-of-freelancing-can-these-8-ai-tools-outshine-chatgpt-in-making-extra-cash/"><u>The Future of Freelancing: Can These 8 AI Tools Outshine ChatGPT in Making Extra Cash?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-potential-influence-of-artificial-intelligence-on-game-development/"><u>The Potential Influence of Artificial Intelligence on Game Development</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-8-side-hustles-with-chatgpt-can-these-be-the-key-to-your-financial-freedom/"><u>Top 8 Side Hustles with ChatGPT: Can These Be the Key to Your Financial Freedom?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-reasons-why-zerogpt-and-similar-ai-detectors-may-not-be-reliable-case-studies/"><u>Top Reasons Why ZeroGPT & Similar AI Detectors May Not Be Reliable: Case Studies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tutorial-activate-gpts-beta-browser-and-plugin-functionality/"><u>Tutorial: Activate GPT's Beta Browser & Plugin Functionality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-ai-hallucinations-identification-and-detection-strategies/"><u>Understanding AI Hallucinations: Identification & Detection Strategies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->