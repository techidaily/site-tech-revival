---
title: "Step-by-Step Tutorial: Integrating WSL Into Your Windows ˈlɪnksi, Microsoft’s Latest Operating System Innovation"
date: 2024-08-29T01:37:44.253Z
updated: 2024-08-30T01:37:44.253Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/288c4a8a533b0f1094aca3a28c5db0188ea8b5a3c3aca95005c1c84fe62729c2.jpg
---

## Step-by-Step Tutorial: Integrating WSL Into Your Windows ˈlɪnksi, Microsoft’s Latest Operating System Innovation

### Quick Links

* [How WSL Works on Windows 11](https://screen-sharing-recording.techidaily.com/easy-ways-to-record-steam-gameplay-2023-for-2024/)
* [Install WSL through Windows Terminal](https://ios-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-8-plus-with-7-methods-by-drfone-ios/)
* [The Slow Way: Enable WSL and Install a Distro](https://smart-video-creator.techidaily.com/new-blur-unwanted-parts-of-your-videos-with-these-mobile-apps/)

### Key Takeaways

 To install the Windows Subsystem for Linux (WSL) on Windows 11, run Terminal as administrator, then enter "wsl --install" into the window. Run "wsl --install -d Distro", replacing "Distro" with the name of a Linux distro, to install a specific distribution instead of Ubuntu. You can install additional Linux distros from the Terminal or the Microsoft Store.

 The Windows Subsystem for Linux (WSL) lets you run Linux software on your Windows 11 PC. When you enable WSL, Windows will install a custom-built Linux kernel. You can then install Ubuntu or another Linux distribution of your choice.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##  How WSL Works on Windows 11

 You can enable the Windows Subsystem for Linux (WSL) on all editions of [Windows 11](https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/)—even Windows 11 Home. (You can also [install WSL on Windows 10](https://tech-haven.techidaily.com/ais-role-in-todays-misinformation-landscape/).)

 Like more recent versions of Windows 10, Windows 11 uses WSL 2\. This second version is redesigned and runs a full Linux kernel in a [Hyper-V](https://facebook-record-videos.techidaily.com/updated-the-infographic-index-youtubes-surprising-stat-treasury-2017/) hypervisor for improved compatibility. When you enable the feature, Windows 11 downloads a [Microsoft-built Linux kernel](https://win-answers.techidaily.com/god-of-war-not-working-overcome-inadequate-memory-error-here/) that it runs in the background. Windows Update keeps the kernel updated. (You can use your own custom Linux kernel if you prefer, too.)

 To use WSL, you'll need to install a Linux distribution. By default, WSL installs Ubuntu. This will give you access to a full Ubuntu command-line environment using the Bash shell or any other command-line shell of your choice.

 You can access your Linux shell environments in the Windows Terminal app included with Windows 11, too.

 You can also run graphical Linux apps out of the box (Just install them in the Linux command-line environment and run the command). Windows 11 also includes support for running Linux apps with GPU access, making GPU-accelerated Linux computing workloads run well on Windows.

 It is also worth noting that most new, interesting developments for WSL are shifting to Windows 11—Windows 10 users won't be able to use them. 

##  Install WSL through Windows Terminal

 Microsoft has made this process extremely simple on Windows 11\. You can enable the Windows Subsystem for Linux and install a Linux distribution like Ubuntu with a single command.

 To do this, you will need to use a command-line window with Administrator permissions. We'll do this with the Windows Terminal, although you can also just launch Command Prompt.

 To launch a Windows Terminal with Administrator permissions, right-click the Start button on the taskbar or press Windows+X and click "Terminal (Admin)." (You can also find the Windows Terminal shortcut in your Start menu—right-click it and select "Run as Administrator.") Agree to the User Account Control prompt that appears.

![Right-click the Start button, then select "Terminal (Admin)."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-9.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 To enable the Windows Subsystem for Linux and install Ubuntu, which is the default distribution, just run the following command:

wsl --install

 When the process is complete, Windows will ask you to reboot your PC. Restart your computer by entering **shutdown /r /t 0** into the Terminal. You'll be able to use your Linux system after you do. (You can right-click the Start menu and click Shut Down or Sign Out > Restart to quickly reboot.)

![Run the &quot;wsl --install&quot; command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/a2-install-wsl-and-ubuntu.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To list other available Linux distributions, run the following command instead. This lists (-l) distributions that are available online (-o).

wsl -l -o

 You can install a Linux distribution of your choice by running the following command, replacing "Name" with the name of the Linux distro, as displayed in the "Name" column:

wsl --install -d Name

 For example, to install Debian instead of Ubuntu, you'd run:

wsl --install -d Debian

 You can also run this command multiple times to install several Linux distributions on your system.

![List available Linux distributions and install one.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/a3-list-distros.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Once your computer has rebooted, you can launch the Linux distro that you installed from your Start menu.

![Launch the &quot;Ubuntu&quot; shortcut.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/ubuntu-start-menu.png) 

 You'll also find it as an option in the Windows Terminal app. Click the down arrow to the right of the new tab "+" button on the tab bar and select the Linux distribution that you installed.

 If you don't see the Linux distribution that you installed in the Windows Terminal, launch it from your Start menu first. After it completes its first-run setup process, it will appear here.

![Click the down arrow and select your Linux distribution.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/powershell-ubuntu-terminal.png) 

 Now, you can use the Linux shell just as if you were sitting in front of a PC Linux—or as if you were remotely connected to a server running Linux. You'll just need to [know Linux commands](https://buynow-help.techidaily.com/misinterpretation-of-gram-staining-results-can-lead-to-incorrect-identification-affecting-treatment-decisions-in-clinical-settings/).

##  The Slow Way: Enable WSL and Install a Distro

 You can also enable the Windows Subsystem for Linux (WSL) the older way. This takes more clicking, and we recommend just running the command above.

 If you install a Linux distro before installing and enabling WSL you may experience problems. If this happens, run wsl -l to list your current Linux distros, then use enter the command **wsl --unregister** followed by the name of the distro. Try launching the Linux distro again. 

 To do this, open your Start menu and search for "Windows features." (You can press the Windows key to open the Start menu and just start typing.) Launch the "Turn Windows Features On or Off" shortcut.

 Enable the "Windows Subsystem for Linux" checkbox here and click "OK." You will be prompted to reboot your computer.

![Enable the &quot;Windows Subsystem for Linux&quot; option and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/07/b1-install-wsl.png) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After you do, open the Microsoft Store app and search for the Linux distribution that you want to use. For example, you might search for "Ubuntu."

 Install the Linux distribution that you want to use (like Ubuntu) as you would any other application. Just click the "Get" button on its Store page.

![Search for "Ubuntu," then click "Get."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/ubuntu.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can now launch it from your Start menu just as if it were installed from the command above. 

 New Linux distros are occasionally added to the Microsoft Store, and you can find the currently available distros by searching for "Linux" rather than a specific distro. If your preferred Linux flavor isn't available, you can always import your preferred distro into WSL manually.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-mastering-snapchat-sharing-with-twitter-videos/"><u>[New] 2024 Approved  Mastering Snapchat Sharing with Twitter Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-crafting-your-signature-voice-for-instagram-success/"><u>[New] Crafting Your Signature Voice for Instagram Success</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-changes-in-instagrams-algorithm-user-perspectives/"><u>[New] In 2024, Changes in Instagram's Algorithm  User Perspectives</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-how-to-climb-the-social-ladder-a-guide-to-higher-facebook-page-ranks/"><u>[New] In 2024, How to Climb the Social Ladder  A Guide to Higher Facebook Page Ranks</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-sharpen-your-visual-storytelling-advanced-kinemaster-zoom-techniques/"><u>[Updated] 2024 Approved  Sharpen Your Visual Storytelling  Advanced Kinemaster Zoom Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/anonymity-at-risk-neural-network-inversion/"><u>Anonymity at Risk: Neural Network Inversion</u></a></li>
<li><a href="https://tech-revival.techidaily.com/breaking-free-setting-up-gpt-on-windows/"><u>Breaking Free: Setting Up GPT on Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/can-a-digital-mentor-help-you-navigate-the-perils-of-wild-environments/"><u>Can a Digital Mentor Help You Navigate the Perils of Wild Environments?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-as-your-co-pilot-expert-tips-on-car-modification-support/"><u>ChatGPT as Your Co-Pilot: Expert Tips on Car Modification Support</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpts-scriptwriting-magic-in-my-podcast-realm/"><u>ChatGPT's Scriptwriting Magic in My Podcast Realm</u></a></li>
<li><a href="https://tech-revival.techidaily.com/diagnosing-and-resolving-interface-issues-chatgpts-trouble-with-plugin-connectivity/"><u>Diagnosing & Resolving Interface Issues: ChatGPT's Trouble with Plugin Connectivity</u></a></li>
<li><a href="https://tech-revival.techidaily.com/empowering-your-smartphone-with-chatgpt-techniques/"><u>Empowering Your Smartphone with ChatGPT Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gpus-in-artificial-intelligence-surges-to-alarming-levels-with-one-card-using-up-to-37m-wh-annually-dwarfing-home-electricity-use-13mplus-units/"><u>GPUs in Artificial Intelligence Surges to Alarming Levels with One Card Using Up to 3.7M Wh Annually – Dwarfing Home Electricity Use (1.3M+ Units)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-do-they-harness-gpt-4-insights-on-7-innovative-app-integrations/"><u>How Do They Harness GPT-4? Insights on 7 Innovative App Integrations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-chatgpt-decode-programming-languages-its-crucial-role-explained/"><u>How Does ChatGPT Decode Programming Languages? Its Crucial Role Explained</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-delete-icloud-account-with-or-without-password-from-your-apple-iphone-15-pro-maxwindowsmac-by-drfone-ios/"><u>How to Delete iCloud Account with or without Password from your Apple iPhone 15 Pro Max/Windows/Mac</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-maintain-uninterrupted-chatsessions-with-chatgpt-by-enabling-save-features-effectively/"><u>How to Maintain Uninterrupted ChatSessions with ChatGPT by Enabling Save Features Effectively</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-infinix-note-30-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Infinix Note 30</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-nubia-red-magic-8s-pro-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Nubia Red Magic 8S Pro to New Phone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/integrating-chatgpt-in-cognitive-therapy-methods/"><u>Integrating ChatGPT in Cognitive Therapy Methods</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-it-possible-to-use-chatgpt-through-a-virtual-private-network-vpn/"><u>Is It Possible To Use ChatGPT Through A Virtual Private Network (VPN)?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ating-youtube-shorts-thumbnail-losses-for-2024/"><u>Navigating YouTube Shorts Thumbnail Losses for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/perfecting-image-editing-on-your-iphone-with-the-new-cutout-effect-tips-and-tricks-for-ios-16-users/"><u>Perfecting Image Editing on Your iPhone with the New Cutout Effect – Tips and Tricks for iOS 16 Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/quit-juxtaposing-ai-pros-and-cons-insightful-observations/"><u>Quit Juxtaposing AI Pros & Cons: Insightful Observations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/rise-above-the-crowd-how-to-amass-over-a-million-video-views/"><u>Rise Above the Crowd  How to Amass Over a Million Video Views</u></a></li>
<li><a href="https://extra-information.techidaily.com/scrutinizing-the-performance-of-dji-solo-vision-goggles/"><u>Scrutinizing the Performance of DJi Solo Vision Goggles</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tailoring-text-based-assistance-how-to-shape-chatgpts-language-to-mirror-yours/"><u>Tailoring Text-Based Assistance: How to Shape ChatGPT's Language to Mirror Yours</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-dark-side-of-ai-how-to-stay-secure-from-the-threats-posed-by-fraudgpt-and-similar-bots/"><u>The Dark Side of AI: How to Stay Secure From the Threats Posed by FraudGPT and Similar Bots</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-inner-workings-of-gpt-4all-explained-a-detailed-overview/"><u>The Inner Workings of GPT-4All Explained: A Detailed Overview</u></a></li>
<li><a href="https://video-capture.techidaily.com/translate-speech-to-text-with-ultimate-accuracy-thanks-to-google/"><u>Translate Speech to Text with Ultimate Accuracy, Thanks to Google</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlock-advanced-prompt-skills-discover-7-must-use-software-solutions-online/"><u>Unlock Advanced Prompt Skills: Discover 7 Must-Use Software Solutions Online</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-huggingchat-how-this-open-source-platform-positions-itself-against-chatgpt/"><u>Unveiling HuggingChat: How This Open-Source Platform Positions Itself Against ChatGPT</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-to-enhanced-performance-free-download-of-geforce-rtx-2060-drivers-for-windows-11-devices/"><u>Update to Enhanced Performance: Free Download of GeForce RTX 2060 Drivers for Windows 11 Devices</u></a></li>
</ul></div>
