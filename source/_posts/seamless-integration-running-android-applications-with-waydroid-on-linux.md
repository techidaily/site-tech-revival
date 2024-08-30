---
title: "Seamless Integration: Running Android Applications with WayDroid on Linux"
date: 2024-08-29T01:36:51.783Z
updated: 2024-08-30T01:36:51.783Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/450ec1b84e72a24dc748a4aee1ff3d014e9229d42ab5bd65b8cf7e7b256ed53c.jpg
---

## Seamless Integration: Running Android Applications with WayDroid on Linux

### Key Takeaways

* WayDroid lets you launch a complete Android system on Linux with Google Play Services so you can install your favorite apps.
* You can install it on most major Linux distros, but be sure to choose the "GAPPS" Android type during WayDroid's setup. You'll also need to get your device certified by visiting Google's website.
* Once you're certified, launch WayDroid and open the Play Store to start installing apps.

 Looking to run Android apps on your Linux desktop? Learn how to use WayDroid to turn your Linux desktop or laptop into an Android app powerhouse.

##  What Is WayDroid?

 WayDroid is a container-based tool that allows for launching a complete Android system within the Linux desktop. It does this with Linux namespaces, effectively utilizing the Linux kernel. In simple terms, namespaces are a feature that helps isolate and separate parts of a computer so that it is possible to run each part independently as if it is the only one on the computer.

 If you're trying to run Android apps on Linux, WayDroid is the way to do it, and former "Android on Linux" tools [like Anbox](https://iphone-location.techidaily.com/a-full-review-for-itools-virtual-location-and-top-5-alternatives-for-apple-iphone-8ipad-drfone-by-drfone-virtual-ios/) recommend it. WayDroid is compatible with a wide variety of Linux distributions and CPU architectures. Additionally, it harnesses Android's Mesa technology to enable efficient GPU pass-through from the container to the host system, which enhances the performance of graphical applications, ensuring a smooth user experience.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
##  Setting Up WayDroid in No Time

 To get started with WayDroid on your Linux desktop or laptop, open a terminal window. You can do this by pressing Ctrl+Alt+T on your keyboard or searching for "Terminal" in your Linux app menu. Follow the steps below to install WayDroid:

###  Ubuntu or Debian Installation

 For users on Ubuntu, Debian, or derivatives, begin by installing the "curl" tool, which is necessary for running WayDroid's official installation script. First, Install curl:

sudo apt install curl

 After setting up curl, run the official WayDroid installation script with curl:

curl -s https://repo.waydro.id/ | sudo bash

 After the script is completed, install the WayDroid package:

sudo apt install waydroid

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  WayDroid on Other Linux Distributions

 WayDroid enjoys broad support across various Linux platforms. While the installation script primarily targets Ubuntu and Debian-based systems, other distributions can run WayDroid. If you're looking to install WayDroid on your Linux device, search for WayDroid packages on [Pkgs.org](https://pkgs.org/search/?q=waydroid) to find compatible installation options.

 If you're unable to find a package to install WayDroid on your system at Pkgs.org, consider checking out the [official WayDroid documentation](https://docs.waydro.id/) for information on how you can get it working on your Linux workstation.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The WayDroid Experience

 WayDroid stands out as a great tool for Linux, especially as it helps get the best out of your device by enabling the integration of Android applications into the Linux environment. Unlike many alternatives that offer Android compatibility, WayDroid excels in ease of use and system integration.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
###  Installing Android Apps with WayDroid on Linux

 To enjoy Android apps on Linux through WayDroid, first open WayDroid from the Linux application menu. The "Initialize Waydroid" window will appear on the first launch. When the "Initialize WayDroid" window is open, navigate to the "Android Type" option and choose "GAPPS" to integrate [Google Play Services](https://tech-recovery.techidaily.com/top-11-free-movie-downloading-websites-you-should-know-about/). Hit the "Download" button to begin downloading and installing your Android container. This might take a while, so patience is key.

![The WayDroid initialization wizard on Ubuntu, showing the download options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-init.png) 

 After installation, click "Done" in the "Initialize WayDroid" window to start WayDroid Android. Upon the first startup, a notification may indicate that the device isn’t certified to run Google Play apps. You now need to certify your Android device. Certification is required, as without it, you cannot install Android applications on WayDroid via the Google Play Store.

 Open a terminal and enter **sudo waydroid shell**. Execute the command to display your device's Android ID:

ANDROID_RUNTIME_ROOT=/apex/com.android.runtime ANDROID_DATA=/data ANDROID_TZDATA_ROOT=/apex/com.android.tzdata ANDROID_I18N_ROOT=/apex/com.android.i18n sqlite3 /data/data/com.google.android.gsf/databases/gservices.db "select * from main where name = 'android_id';"

 After you've found your ID, you need to submit it to Google for device verification purposes. To do this, visit the [Google "Uncertified" page](https://www.google.com/android/uncertified) and enter the code shown in your terminal. With your Android device registered with Google, restart WayDroid using the terminal commands **waydroid session stop** and then **waydroid session start** following that.

 You can now install Android apps. To start, open the Play Store app within WayDroid, sign in with your Google account.

![The WayDroid Android launcher showing the Google Play Store icon, with an arrow pointing to the user instructing them to open it.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-select-play-store.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
 Once you've logged in, you can search the Google Play Store for your favorite apps.

![The Google Play Store search box in WayDroid. The user is searching for the Audible app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-search-for-audible.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
 Just select "Install," to download it directly to your Linux system.

![The Google Play Store in WayDroid. The user is searching for Audible, and Google Play is showing it as the top search result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/waydroid-google-play-store-2.jpg) 

---

 WayDroid is an excellent tool to run Android apps on Linux, and most apps run quite well on the platform. Give WayDroid a try and install your favorite apps with it. Once you do, you'll find that WayDroid is a worthy addition to the Linux desktop.

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
<li><a href="https://vp-tips.techidaily.com/new-ultimate-mix-seamless-free-and-paid-blu-ray-playback-windows-macos/"><u>[New] Ultimate Mix  Seamless Free & Paid Blu-Ray Playback (Windows, macOS)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-divergence-in-dungeons-classic-and-hybrid-games/"><u>[Updated] 2024 Approved  Divergence in Dungeons  Classic and Hybrid Games</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-secrets-to-splendid-windows-11-backdrops/"><u>[Updated] Secrets to Splendid Windows 11 Backdrops</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-tier-image-manipulations/"><u>[Updated] Top-Tier Image Manipulations</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-expert-tips-implement-borders-on-instagram-media/"><u>2024 Approved  Expert Tips  Implement Borders on Instagram Media</u></a></li>
<li><a href="https://tech-revival.techidaily.com/addressing-car-gpt-issues-6-common-hurdles-and-their-remedies/"><u>Addressing Car GPT Issues: 6 Common Hurdles and Their Remedies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-showdown-determining-the-superior-coding-companion-between-chatgpt-and-gemini/"><u>AI Showdown: Determining the Superior Coding Companion Between ChatGPT and Gemini</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-oppo-a2-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/beware-of-ineffective-plugins-top-6-that-fall-short-compared-to-gpt/"><u>Beware of Ineffective Plugins: Top 6 That Fall Short Compared to GPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/bridging-minds-and-devices-chatgpt-on-android/"><u>Bridging Minds & Devices: ChatGPT on Android</u></a></li>
<li><a href="https://tech-revival.techidaily.com/customizing-conversational-agents-creating-an-adapted-chatgpt-for-specific-needs/"><u>Customizing Conversational Agents: Creating an Adapted ChatGPT for Specific Needs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/cut-the-clutter-organizing-chatgpt-exchanges-through-folders/"><u>Cut the Clutter: Organizing ChatGPT Exchanges Through Folders</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063153514-elevate-your-connections-effortlessly-with-our-driver-tools/"><u>Elevate Your Connections Effortlessly with Our Driver Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhanced-with-editing-capabilities-new-features-of-dall-e-3-demand-more-work-on-user-interface-and-functionality/"><u>Enhanced with Editing Capabilities: New Features of DALL-E 3 Demand More Work on User Interface and Functionality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-productivity-incorporating-chatgpt-into-google-sheets-via-gpt-for-office-suites/"><u>Enhancing Productivity: Incorporating ChatGPT Into Google Sheets via GPT for Office Suites</u></a></li>
<li><a href="https://tech-revival.techidaily.com/essential-elements-in-selecting-chatgpt-for-psychological-support/"><u>Essential Elements in Selecting ChatGPT for Psychological Support</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebook-live-the-world-in-minutes-for-2024/"><u>Facebook Live  The World in Minutes for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-basics-to-expertise-a-developers-roadmap-for-combining-gpt-3-with-python-technology/"><u>From Basics to Expertise: A Developer's Roadmap for Combining GPT-3 with Python Technology</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gauging-ai-trustworthiness-for-financial-guidance/"><u>Gauging AI Trustworthiness for Financial Guidance?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/imposter-extension-snatches-fb-login-data/"><u>Imposter Extension: Snatches FB Login Data</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-comprehensive-guide-for-high-quality-presentation-capture/"><u>In 2024, Comprehensive Guide for High-Quality Presentation Capture</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-easy-guide-to-crafting-fun-snapchat-lenses/"><u>In 2024, Easy Guide to Crafting Fun Snapchat Lenses</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-profit-from-reddit-easy-style-top-13-beginner-strategies/"><u>In 2024, Profit From Reddit Easy Style  Top 13 Beginner Strategies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sky-high-quality-unveiling-the-best-4k-video-converters/"><u>In 2024, Sky-High Quality  Unveiling the Best 4K Video Converters</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-the-asus-proart-pa32ucxr-unmatched-color-precision-in-a-compact-form/"><u>In-Depth Analysis of the Asus ProArt PA32UCXR - Unmatched Color Precision in a Compact Form</u></a></li>
<li><a href="https://tech-revival.techidaily.com/installing-bavarder-linuxs-chatgpt-routine/"><u>Installing Bavarder: Linux's ChatGPT Routine</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-working-in-prompt-engineering-feasible-understand-key-considerations/"><u>Is Working in Prompt Engineering Feasible? Understand Key Considerations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/macs-finest-the-leading-free-art-programs/"><u>Mac's Finest - The Leading Free Art Programs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/master-the-art-of-gamesharing-on-xbox-one-to-enjoy-multiplayer-fun-with-buddies/"><u>Master the Art of Gamesharing on Xbox One to Enjoy Multiplayer Fun with Buddies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-through-chatgpts-service-integration-troubles/"><u>Navigating Through ChatGPT's Service Integration Troubles</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-drawing-to-animating-the-best-software-tools-for-bringing-your-art-to-life-for-2024/"><u>New Drawing to Animating The Best Software Tools for Bringing Your Art to Life for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/new-iphone-7-plus-restore-from-icloud-stuck-on-time-remaining-estimating-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>New iPhone 7 Plus Restore from iCloud Stuck on Time Remaining Estimating | Stellar</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protecting-authenticity-in-creative-works-using-the-power-of-nightshade/"><u>Protecting Authenticity in Creative Works Using the Power of Nightshade</u></a></li>
<li><a href="https://tech-revival.techidaily.com/reviving-your-broken-pc-expert-tips-and-tricks-from-chatgpts-assistance/"><u>Reviving Your Broken PC: Expert Tips and Tricks From ChatGPT's Assistance</u></a></li>
<li><a href="https://tech-revival.techidaily.com/skip-the-sign-up-process-joining-apps-without-numbers/"><u>Skip the Sign-Up Process: Joining Apps without Numbers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/snapshot-vs-search-assistant-showdown-uncovering-8-major-contrasts-of-snapchat-and-bing-chat-on-skype/"><u>Snapshot Vs. Search Assistant Showdown: Uncovering 8 Major Contrasts of Snapchat and Bing Chat on Skype</u></a></li>
<li><a href="https://tech-revival.techidaily.com/speak-the-language-of-ai-5-voice-controlled-chatgpt-tips/"><u>Speak the Language of AI: 5 Voice-Controlled ChatGPT Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/stay-ahead-of-tech-trends-understanding-new-threats-on-twitter-the-launch-of-metas-verification-status-and-comprehensive-insights-into-chatgpt-4-technology.12/"><u>Stay Ahead of Tech Trends: Understanding New Threats on Twitter, The Launch of Meta's Verification Status, and Comprehensive Insights Into ChatGPT- 4 Technology</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-generative-ai-and-its-revolutionary-impact/"><u>Understanding Generative AI and Its Revolutionary Impact</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-insights-how-to-utilize-chatgpt-as-a-data-analyst-6-key-approaches/"><u>Unlocking Insights: How to Utilize ChatGPT as a Data Analyst (6 Key Approaches)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-potential-with-chatgpt-a-guide-to-its-native-addons/"><u>Unlocking Potential with ChatGPT: A Guide to Its Native Addons</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-cloud-based-vertical-video-editing-software-top-picks-2023/"><u>Updated In 2024, Cloud-Based Vertical Video Editing Software Top Picks 2023</u></a></li>
</ul></div>
