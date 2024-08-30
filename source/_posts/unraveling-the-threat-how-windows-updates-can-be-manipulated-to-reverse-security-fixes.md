---
title: "Unraveling the Threat: How Windows Updates Can Be Manipulated to Reverse Security Fixes"
date: 2024-08-29T01:36:13.766Z
updated: 2024-08-30T01:36:13.766Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d998ed1ce4fa21b446a75f0e6c9a8cf84aeb11cbd732d7f1223ebbfd05a07e14.jpg
---

## Unraveling the Threat: How Windows Updates Can Be Manipulated to Reverse Security Fixes

Security researcher Alon Leviev has discovered a vulnerability in Windows Update that allows attackers to disable security patches without detection. This downgrade attack can potentially compromise fully updated Windows systems, and expose them to old threats which Microsoft has already patched.

 According to Leviev, he wanted to test the protection Windows offers against downgrade attacks. To his surprise, Windows barely has any fail safes to prevent unauthorized OS rollbacks. The researcher found serious security flaws in Windows Update that he exploited to gain elevated system privileges and breeze past Windows security. Using a custom tool called Windows Downdate, he managed to downgrade system files, [drivers](https://hardware-tips.techidaily.com/increase-your-savings-with-a-huge-80-off-the-elegoo-neptune-plus-ideal-for-big-prints/), and the Windows kernel (the core program which has full control over the operating system) on Windows 10 and 11.

 The downgrades he made remained undetectable and persistent, meaning they were invisible to Windows Update and [system recovery](https://tech-hub.techidaily.com/innovative-training-crafting-custom-exercise-routines-using-chatgpt-for-trainers/) tools. They're also irreversible. The attack would trick the victim into thinking their machine is up-to-date (as Windows Update would confirm). But the core components would have been quietly replaced with older versions, exposing them to thousands of already-fixed vulnerabilities.

 Leviev also discovered critical flaws in the Windows virtualization security, including [Hyper V](https://fox-glue.techidaily.com/the-ultimate-guide-to-using-telegram-web-effectively-for-2024/). Exploiting those flaws, he managed to downgrade and bypass virtualization security features. The researcher warns that Windows might not be the only operating system vulnerable to downgrade attacks.

 There have been no attacks in the wild using this attack vector, which is good news. But Leviev demoed it at Black Hat USA 2024 and DEF CON 32 2024\. He also reached out to Microsoft in February, when he first identified these threats.

 Microsoft has since been working on an update to patch them, but six months later, it’s still not available. “We are actively developing mitigations to protect against these risks while following an extensive process involving a thorough investigation, update development across all affected versions, and compatibility testing, to ensure maximized customer protection with minimized operational disruption,” Microsoft stated in an official response.

 Source: Alon Leviev via [Safebreach](https://www.safebreach.com/blog/downgrade-attacks-using-windows-updates/)

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-apowersoft-screen-recorder-testimony/"><u>[New] 2024 Approved  Apowersoft Screen Recorder Testimony</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-dominate-instagram-with-superior-reel-content/"><u>[New] 2024 Approved  Dominate Instagram with Superior Reel Content</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-videorecording-mastery-with-screencapture-x/"><u>[New] 2024 Approved  VideoRecording Mastery with ScreenCapture X</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-quality-sky-images-leading-sites-listed/"><u>[New] High-Quality Sky Images  Leading Sites Listed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-end-scene-excellence-your-guide-to-yt-outro-mastery/"><u>[New] In 2024, End Scene Excellence  Your Guide to YT Outro Mastery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-sierras-icloud-drive-accessibility/"><u>[New] Mastering Sierra’s iCloud Drive Accessibility</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-revolutionize-video-crafting-mastering-the-integration-of-windows-11-and-storyremix/"><u>[New] Revolutionize Video Crafting  Mastering the Integration of Windows 11 & StoryRemix</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-engage-audiences-effortlessly-social-medias-screen-share-guide/"><u>[Updated] In 2024, Engage Audiences Effortlessly  Social Media's Screen Share Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-guide-to-delivering-engaging-ppt-in-google-meet-mobiledesktop/"><u>[Updated] In 2024, Guide to Delivering Engaging PPT in Google Meet (Mobile/Desktop)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-crafting-the-perfect-first-touch-redefining-unboxing/"><u>2024 Approved  Crafting the Perfect First Touch  Redefining Unboxing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-premium-recommendations-for-ultra-hd-monitoring-tools/"><u>2024 Approved  Premium Recommendations for Ultra-HD Monitoring Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-integration-boosts-bing-mobile-search-for-android-and-ios-devices/"><u>AI Integration Boosts Bing Mobile Search for Android & iOS Devices.</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-pros-and-cons-of-using-chatgpt-plus-in-digital-communication/"><u>Decoding the Pros and Cons of Using ChatGPT Plus in Digital Communication</u></a></li>
<li><a href="https://tech-revival.techidaily.com/easy-steps-disabling-the-quicksheet-feature-on-your-windows-10-system/"><u>Easy Steps: Disabling the Quicksheet Feature on Your Windows 10 System</u></a></li>
<li><a href="https://program-issues.techidaily.com/elevate-your-elden-ring-experience-by-resolving-fps-issues-quickly/"><u>Elevate Your Elden Ring Experience by Resolving FPS Issues Quickly</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-inner-workings-of-artificial-intelligence-what-are-ai-black-boxes-and-why-do-they-matter/"><u>Exploring the Inner Workings of Artificial Intelligence: What Are 'AI Black Boxes' And Why Do They Matter?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gamify-your-experience-with-chatgpt-check-out-these-6-engaging-titles/"><u>Gamify Your Experience with ChatGPT - Check Out These 6 Engaging Titles!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guide-to-accessing-troubleshooting-mode-in-windows-8-and-81-without-hesitation/"><u>Guide to Accessing Troubleshooting Mode in Windows 8 & 8.1 Without Hesitation!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-chatgpt-adapt-based-on-customer-dialogues/"><u>How Does ChatGPT Adapt Based On Customer Dialogues?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-capture-an-image-of-your-screen-on-windows-11/"><u>How to Capture an Image of Your Screen on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-delete-cookies-in-chrome/"><u>How to Delete Cookies in Chrome</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-perform-a-clean-boot-in-windows-11/"><u>How to Perform a Clean Boot in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-set-up-your-brother-all-in-one-printer-on-modern-windows-platforms-vista-and-beyond/"><u>How to Set Up Your Brother All-in-One Printer on Modern Windows Platforms (Vista & Beyond)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-will-artificial-intelligence-impact-our-mental-wellness-enhancement-or-deterioration/"><u>How Will Artificial Intelligence Impact Our Mental Wellness: Enhancement or Deterioration?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/identifying-your-pcs-os-a-step-by-step-guide-to-finding-the-windows-11-build-version/"><u>Identifying Your PC's OS: A Step-by-Step Guide to Finding the Windows 11 Build Version</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-monetizing-your-social-media-presence-snapchat-edition/"><u>In 2024, Monetizing Your Social Media Presence  Snapchat Edition</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-unlocking-the-potential-of-aiseesoft-for-video-documentation/"><u>In 2024, Unlocking the Potential of Aiseesoft for Video Documentation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/introducing-googles-newest-innovation-bard-the-revolutionary-ai-set-to-challenge-chatgpt/"><u>Introducing Google's Newest Innovation: Bard, the Revolutionary AI Set to Challenge ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/next-viewing-choice-leveraging-chatgpts-power/"><u>Next Viewing Choice: Leveraging ChatGPT's Power</u></a></li>
<li><a href="https://extra-support.techidaily.com/optimal-gpus-for-high-res-media-production-for-2024/"><u>Optimal GPUs for High Res Media Production for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/overcome-platform-unsupported-message-when-setting-up-intel-serial-io-drivers/"><u>Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-launch-errors-in-persona-3-fresh-royal-a-comprehensive-guide/"><u>Overcoming Launch Errors in Persona 3 Fresh Royal: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-tecno-phantom-v-flip-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Tecno Phantom V Flip to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/recipe-renovation-with-a-digital-master-chef-chatgpt/"><u>Recipe Renovation with a Digital Master Chef (ChatGPT)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revamping-chatgpts-extensions-hub-four-key-improvements-awaited/"><u>Revamping ChatGPT's Extensions Hub: Four Key Improvements Awaited</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionizing-internet-queries-the-rise-of-microsofts-smart-bing-feature/"><u>Revolutionizing Internet Queries: The Rise of Microsoft's Smart Bing Feature</u></a></li>
<li><a href="https://tech-revival.techidaily.com/solve-your-windows-11-creators-update-woes-overcoming-download-stalls-and-silent-screens/"><u>Solve Your Windows 11 Creators Update Woes: Overcoming Download Stalls & Silent Screens</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-itel-a05s-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Itel A05s FRP</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-dawn-of-truthgpt-and-the-scrutiny-over-mullvad-vpn-by-law-enforcement-your-comprehensive-list-to-top-free-pc-games-and-understanding-mechanical-keyboard20/"><u>The Dawn of TruthGPT and the Scrutiny over Mullvad VPN by Law Enforcement, Your Comprehensive List to Top FREE PC Games & Understanding Mechanical Keyboards Better</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-9-benefits-of-switching-to-chatgpt-plus-now/"><u>Top 9 Benefits of Switching to ChatGPT Plus Now</u></a></li>
<li><a href="https://article-files.techidaily.com/unveiling-360-vs-vr-film-explained-for-2024/"><u>Unveiling  360° Vs. VR Film Explained for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-exploring-8-signature-free-game-sounds-that-are-a-must-have/"><u>Updated In 2024, Exploring 8 Signature Free Game Sounds That Are a Must-Have</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/yahoo-messenger-the-complete-story-of-its-creation-and-closure/"><u>Yahoo! Messenger: The Complete Story of Its Creation and Closure</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->