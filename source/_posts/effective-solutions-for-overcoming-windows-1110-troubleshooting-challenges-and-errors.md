---
title: Effective Solutions for Overcoming Windows 11/10 Troubleshooting Challenges and Errors
date: 2024-08-29T01:37:22.949Z
updated: 2024-08-30T01:37:22.949Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/52781763425_7caa012745_o.jpg
---

## Effective Solutions for Overcoming Windows 11/10 Troubleshooting Challenges and Errors

### Key Takeaways

* Try launching the troubleshooter from the Settings app on your Windows 11 or 10 PC.
* Restart the "Background Intelligent Transfer Service" and "Cryptographic Services" services.
* If the issue persists, fix Windows' damaged system files with DSM and SFC, try to use the troubleshooter in safe mode, or reset your Windows PC.

 If you’ve encountered an “An error occurred while troubleshooting” error while launching a troubleshooter, worry not, as fixing this issue is easy in most cases. Here’s how to do that on your Windows 11 or Windows 10 PC.

 After applying each fix, launch your troubleshooter to check if it’s working.

##  Run the Troubleshooter From Settings

 While Windows allows you to [launch the built-in troubleshooters](https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-play-40c-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) from the Run dialog box, we recommend opening those tools from Settings, as this is where the tools are hosted.

 To do that, [open the Settings app](https://facebook-video-footage.techidaily.com/updated-2024-approved-5-easy-ways-to-multiply-your-youtube-follower-base/) by pressing Windows+i. On Windows 11, head into System > Troubleshoot > Other Troubleshooters. On Windows 10, go to Update & Security > Troubleshoot > Additional Troubleshooters.

 Find the troubleshooting tool to launch. On Windows 11, next to the troubleshooter, select "Run."

!['Run' highlighted for multiple troubleshooters in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-troubleshooter-windows-11-settings-1.jpg) 

 On Windows 10, click the troubleshooter and choose "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for a troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-troubleshooter-windows-10-settings.jpg) 

 The tool will launch.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
##  Restart the Required Windows Services

 The built-in troubleshooters rely on various Windows services to function. These services might not be working correctly, causing an error. Give these services a reboot to fix the problem.

 Open the Run dialog box by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Background Intelligent Transfer Service." Right-click it and select "Restart."

!['Restart' highlighted for the 'Background Intelligent Transfer Service' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-restart-bits-service.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Similarly, right-click the "Cryptographic Services" service and select "Restart."

!['Restart' highlighted for the 'Cryptographic Services' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-restart-cryptographic-services-service.jpg) 

 Close the Services window.

##  Fix Broken Troubleshooters

 It’s possible Windows’ system files are corrupted, causing the troubleshooters to malfunction. In this case, you must [repair the damaged core files](https://some-guidance.techidaily.com/twirl-forge-instruments-for-2024/) using the built-in System File Checker (SFC) tool.

 To do that, open the Start Menu, search for **Command Prompt**, and select "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-cmd-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the User Account Control"(UAC) prompt, select "Yes."

 In Command Prompt, type the following command and press Enter. This command will download the files required to fix the broken system files.

DISM.exe /Online /Cleanup-image /Restorehealth

![The DISM command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-run-dism-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 Next up, run the following command to begin finding and repairing the damaged system files:

sfc /scannow

[Restart your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC once it finishes.

##  Launch the Troubleshooter in Safe Mode

[Safe mode on Windows](https://video-capture.techidaily.com/new-essential-scripting-instant-stopwatch-integration-in-obs-for-2024/) lets you check if third-party apps are preventing you from performing your tasks. In safe mode, Windows only loads the essential files to boot the system, letting you check for interference from any third-party programs or drivers.

 To [start your Windows 11 PC in safe mode](https://buynow-marvelous.techidaily.com/unveiling-the-strong-battery-feature-in-moto-g-power-a-tech-review-insight/), go to Settings > System > Recovery. Next to "Advanced Startup," click "Restart Now."

!['Restart Now' highlighted for 'Advanced Startup' in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-advanced-restart-windows-11.jpg) 

 To [boot your Windows 10 PC in safe mode](https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock/), head into Settings > Update & Security > Recovery. In the "Advanced Startup" section, click "Get Started."

!['Get Started' highlighted for 'Advanced Startup' in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-advanced-restart-windows-10.jpg) 

 When your PC reboots, navigate to Troubleshoot > Advanced Options > Startup Settings and select "Restart." Then, choose the number for safe mode to boot into that mode. When your PC enters safe mode, launch the troubleshooter you wanted to use.

 If the tool works, a third-party app is likely the culprit. Review the list of your installed apps and remove any suspicious ones. It’s quick and easy to [uninstall apps on Windows 11](https://youtube-docs.techidaily.com/ed-in-2024-strategies-for-using-youtube-to-boost-classroom-engagement/) and [Windows 10](https://tech-recovery.techidaily.com/top-savings-on-apple-watches-in-april/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
##  Reset Windows

 If nothing else works, you can reset your Windows 11 or Windows 10 PC to the factory defaults. Resetting the system will fix any issues related to settings or corrupted files, but it should only be used as an last resort.

 You’ll lose your installed apps when you reset your PC. You’ll have the option to keep your personal files, though.

 To [reset a Windows 11 PC](https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/), navigate to Settings > System > Recovery. Next to "Reset This PC," click "Reset PC."

!['Reset PC' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-reset-windows-11-pc.jpg) 

 To [reset a Windows 10 PC](https://instagram-videos.techidaily.com/fast-and-free-strategies-for-authenticity-in-insta-circles-for-2024/), go to Settings > Update & Security > Recovery. In the "Reset This PC" section, click "Get Started."

!['Get Started' highlighted in the 'Reset This PC' section of Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-restart-windows-10-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 On the open window, select "Keep My Files" so Windows doesn’t delete your personal files. Then, follow the on-screen instructions to finish resetting your computer.

 Your troubleshooting tool should work once your machine is back to the default settings.

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
<li><a href="https://screen-recording.techidaily.com/new-from-surviving-to-conquering-top-zombie-games-decoded-for-2024/"><u>[New] From Surviving to Conquering  Top Zombie Games Decoded for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-the-5-must-try-samsung-gear-vr-games/"><u>[Updated] 2024 Approved  The 5 Must-Try Samsung Gear VR Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-10-best-apps-for-editing-igtv-vertical-videos/"><u>[Updated] In 2024, 10 Best Apps for Editing IGTV Vertical Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-expertly-selected-top-7-internet-voice-recorders-2023/"><u>[Updated] In 2024, Expertly Selected Top 7 Internet Voice Recorders 2023</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-streamlining-your-tweets-with-video-upload-rules/"><u>[Updated] In 2024, Streamlining Your Tweets with Video Upload Rules</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-sync-video-elements-to-captivate-instagram-audiences/"><u>[Updated] In 2024, Sync Video Elements to Captivate Instagram Audiences</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-strategies-to-streamline-your-google-meet-calendar/"><u>2024 Approved  Strategies to Streamline Your Google Meet Calendar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-v29-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo V29 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-se-2020-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone SE (2020) for Free</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-poco-x6-pro-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Poco X6 Pro</u></a></li>
<li><a href="https://win-forum.techidaily.com/an-overview-of-what-the-windows-registry-is-and-how-it-works/"><u>An Overview of What The Windows Registry Is & How It Works</u></a></li>
<li><a href="https://data-wizards.techidaily.com/celestial-recovery-stellar-services-for-data-hubs/"><u>Celestial Recovery: Stellar Services for Data Hubs</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-xiaomi-redmi-12-5g-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/creating-seamless-meeting-transitions-with-slackplusfilmora/"><u>Creating Seamless Meeting Transitions with Slack+Filmora</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cure-asus-lcd-squirm-for-clear-vision/"><u>Cure ASUS LCD Squirm for Clear Vision</u></a></li>
<li><a href="https://tech-revival.techidaily.com/easy-solutions-for-resolving-a-non-functioning-windows-tcalculator-on-your-pc/"><u>Easy Solutions for Resolving a Non-Functioning Windows tCalculator on Your PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/efficiently-using-microsoft-edge-for-webnote-creation-tutorials/"><u>Efficiently Using Microsoft Edge for Webnote Creation Tutorials</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effortless-conversion-turn-dall-es-webp-art-into-jpeg-png/"><u>Effortless Conversion: Turn DALL-E's WebP Art Into JPEG, PNG</u></a></li>
<li><a href="https://tech-revival.techidaily.com/essential-tips-on-enabling-protective-measures-in-windows-11/"><u>Essential Tips on Enabling Protective Measures in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-credibility-of-chatgpt-in-providing-health-information/"><u>Exploring the Credibility of ChatGPT in Providing Health Information</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-reality-of-prompt-engineering-as-a-career-key-points/"><u>Exploring the Reality of Prompt Engineering as a Career: Key Points</u></a></li>
<li><a href="https://tech-revival.techidaily.com/face-off-between-giants-determining-superiority-between-chatgpt-and-google-bard/"><u>Face-Off Between Giants: Determining Superiority Between ChatGPT and Google Bard</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/flagship-firefox-screenshot-tools-for-2024/"><u>Flagship Firefox Screenshot Tools for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-one-generation-to-the-next-analyzing-the-five-key-differences-between-gpt-4-and-gpt-35/"><u>From One Generation to the Next: Analyzing the Five Key Differences Between GPT-^4 and GPT-3.5</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-far-can-you-push-the-chatgpt-token-threshold/"><u>How Far Can You Push the ChatGPT Token Threshold?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-check-windows-10-build-number/"><u>How to Check Windows 10 Build Number</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-create-restore-point-in-windows-11/"><u>How to Create Restore Point in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-delete-cookies-in-chrome/"><u>How to Delete Cookies in Chrome</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-open-command-prompt-as-administrator-in-windows-10-8-and-81/"><u>How to Open Command Prompt as Administrator in Windows 10, 8 & 8.1</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-perform-a-clean-boot-in-windows-11/"><u>How to Perform a Clean Boot in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-resolve-windows-10-developer-release-installer-hanging-during-installation-solutions-revealed/"><u>How to Resolve Windows 10 Developer Release Installer Hanging During Installation: Solutions Revealed</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-set-up-your-brother-all-in-one-printer-on-modern-windows-platforms-vista-and-beyond/"><u>How to Set Up Your Brother All-in-One Printer on Modern Windows Platforms (Vista & Beyond)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-use-nightshade-to-protect-your-artwork-from-generative-ai/"><u>How to Use Nightshade to Protect Your Artwork From Generative AI</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-use-ping-command-to-check-internet-connection/"><u>How to Use Ping Command to Check Internet Connection</u></a></li>
<li><a href="https://tech-revival.techidaily.com/identifying-your-pcs-os-a-step-by-step-guide-to-finding-the-windows-11-build-version/"><u>Identifying Your PC's OS: A Step-by-Step Guide to Finding the Windows 11 Build Version</u></a></li>
<li><a href="https://tech-revival.techidaily.com/innovative-techniques-to-design-stellar-slides-with-chatgpt-assistance/"><u>Innovative Techniques to Design Stellar Slides with ChatGPT Assistance</u></a></li>
<li><a href="https://tech-revival.techidaily.com/iphone-windows-11-compatibility-fixing-the-itunes-error-54-for-seamless-device-syncs-after-upgrade/"><u>IPhone-Windows 11 Compatibility: Fixing the iTunes Error -54 for Seamless Device Syncs After Upgrade</u></a></li>
<li><a href="https://article-helps.techidaily.com/navigate-the-best-free-photography-enhancers-worldwide-for-2024/"><u>Navigate the Best Free Photography Enhancers Worldwide for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/openai-alternatives-revealed-discover-5-techniques-to-leverage-chatgpts-capabilities-without-an-account/"><u>OpenAI Alternatives Revealed: Discover 5 Techniques to Leverage ChatGPT's Capabilities without an Account</u></a></li>
<li><a href="https://tech-revival.techidaily.com/overcome-platform-unsupported-message-when-setting-up-intel-serial-io-drivers/"><u>Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/quickly-entering-safe-mode-on-windows-8-and-81-a-step-by-step-guide/"><u>Quickly Entering Safe Mode on Windows 8 and 8.1: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/seven-predictions-for-job-markets-transformed-by-generative-artificial-intelligence/"><u>Seven Predictions for Job Markets Transformed by Generative Artificial Intelligence</u></a></li>
<li><a href="https://tech-revival.techidaily.com/solve-your-windows-11-creators-update-woes-overcoming-download-stalls-and-silent-screens/"><u>Solve Your Windows 11 Creators Update Woes: Overcoming Download Stalls & Silent Screens</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-disabling-quick-access-feature-on-windows-11/"><u>Step-by-Step Guide: Disabling Quick Access Feature on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-updating-and-downloading-drivers-for-your-hp-envy-20-laptop/"><u>Step-by-Step Guide: Updating and Downloading Drivers for Your HP ENVY 20 Laptop</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-tutorial-running-command-prompt-with-administrator-rights-in-win10881/"><u>Step-by-Step Tutorial: Running Command Prompt with Administrator Rights in Win10/8/8.1</u></a></li>
<li><a href="https://extra-information.techidaily.com/swift-image-adaptation-techniques-for-iphone-users/"><u>Swift Image Adaptation Techniques for iPhone Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ins-and-outs-of-chatgpt-bypass-methods-a-comprehensive-guide/"><u>The Ins and Outs of ChatGPT Bypass Methods - A Comprehensive Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-8-innovative-dall-e-3-ai-art-creation-cues/"><u>Top 8 Innovative DALL-E 3 AI Art Creation Cues</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-conversations-with-new-chatgpt-capabilities-a-closer-look-at-essential-updates/"><u>Transforming Conversations with New ChatGPT Capabilities: A Closer Look at Essential Updates</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-forefront-ai-how-does-it-stack-up-against-chatgpt-for-natural-language-processing/"><u>Unveiling Forefront AI: How Does It Stack Up Against ChatGPT for Natural Language Processing?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-four-compelling-reasons-to-embrace-claude-3-instead-of-chatgpt/"><u>Unveiling Four Compelling Reasons to Embrace Claude 3 Instead of ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-relying-solely-on-zerogpt-and-similar-ais-might-be-risky-4-real-cases/"><u>Why Relying Solely on ZeroGPT & Similar AIs Might Be Risky: 4 Real Cases</u></a></li>
</ul></div>
