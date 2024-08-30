---
title: "Securing Image Data in Linux: Removing EXIF Information Using Exiftool"
date: 2024-08-29T01:36:08.698Z
updated: 2024-08-30T01:36:08.698Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/bbcc4a007f0a07614972fe24eb730165421ff81b1eea5d7fad50043a76fd78c0.jpg
---

## Securing Image Data in Linux: Removing EXIF Information Using Exiftool

### Key Takeaways

* Did you know smartphone pictures can contain sensitive data? Remove metadata to protect your privacy.
* EXIF tags store a lot of information about your photos, including device details and GPS coordinates.
* Use exiftool on Linux to easily strip all metadata from your images before sharing them online.

 Did you know that pictures you snap with your smartphone may include sensitive information? Posting them as-is on social media or elsewhere can be risky to your privacy unless you take steps to remove extra data from them. In this article you'll learn how to do just that on Linux with exiftool.

##  Why Should I Remove Metadata?

 Back in the days of analog cameras, the only "extra" information you needed to worry about being disclosed alongside them was what you physically wrote on the back of each photo. Fast-forward to modern times, and we've got the ability to capture moments instantly in digital form (and even keep thousands of them at a time on a single device). This shift made a lot of folks think about what could augment this new technology to make our lives even easier.

 In the mid-1990's, borrowing from the TIFF standard, research and standards bodies developed a way to embed extra information inside image files themselves. They called this new standard [Exchangable Image File Format (EXIF)](https://some-knowledge.techidaily.com/new-ignite-motivation-the-hottest-playlists-for-workouts/). Now you will see your picture libraries, for instance, using EXIF tags to help search, sort and categorize every image you take.

 The amount of data that gets stored in your images depends on manufacturer defaults, features enabled on your device and other factors. Along with basic information like the date/time taken and image resolution, just a small sample of other tags stored with your picture may include:

* The model name of the phone/camera used to take it
* Exposure time
* Whether the camera's flash was used or not
* A thumbnail, in binary format
* [GPS](https://win-forum.techidaily.com/how-to-access-and-understand-bios-on-windows-11-a-comprehensive-guide/) coordinates

 That last one is a particular privacy concern as it can be used to locate precisely where you or the subject of the picture were at the time the picture was taken.

 The other items are also interesting in that they can be used to enumerate, for example, exactly what type of device you used, right down to the model. This can, for instance, be used to plan a targeted [attack on your phone](https://desktop-recording.techidaily.com/1715859817771-updated-seeking-authentic-ps2-play-check-out-the-5-best-android-simulators/).

 If you take a look at [all the possible EXIF tags that could be embedded in your images](https://exiftool.org/TagNames/EXIF.html), you'll start to understand the importance of keeping some (most?) of them away from those who may want to use them for less-than-honest reaasons.

 So, with this knowledge, we'll move forward to protect ourselves with Linux and exiftool!

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
##  Installing Required Packages

 Exiftool is a platform-independent library and command line application, written in Perl, by Phil Harvey. It's available from [the official exiftool website](https://exiftool.org/), which also has a wealth of information, a FAQ and message forum for user questions.

 Exiftool is also available via your distribution's package repositories, which is how we'll install it in this tutorial.

 For Debian based distributions, install the libimage-exiftool-perl package using apt:

sudo apt install libimage-exiftool-perl

![Terminal window showing command to install exiftool on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-18.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 For Redhat distros, use dnf to install the perl-Image-ExifTool package:

sudo dnf install perl-Image-ExifTool

![Terminal window showing command to install exiftool on Fedora](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-19.png) 

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For Arch distros like Manjaro, you'll install the perl-image-exiftool package with pacman:

sudo pacman -S perl-image-exiftool

![Terminal window showing command to install exiftool on Arch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1.png) 

##  Viewing Metadata on an Existing Image

![An old, red telephone booth](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/donor-1.jpg) 

Jordan Erickson / How-To Geek

 Here's a nice picture I took last year of a phone booth. Innocent enough, right? Well, now that we've got exiftool in our arsenal, let's take a look what metadata it's stowing:

exiftool donor.jpg

![Terminal window showing exiftool output with a donor image on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-all.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 Compared to what could be recorded by other smartphones, this is pretty tame. You'll notice that I didn't have GPS enabled on my phone when snapping this photo since it was not recorded in the EXIF metadata. Even so, there's still other info I'd rather not share with just anyone. So let's just strip it _all_ from the image.

##  Stripping It All Out

 Removing all EXIF metadata is pretty simple:

exiftool -all= donor.jpg

![Terminal window showing command to remove EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-4-1.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The command above will create a backup of the original, appending "\_original" to the end of the filename. If you don't want this behavior, you can use:

exiftool -all= -overwrite_original donor.jpg

![Terminal window showing the command to remove all metadata and overwrite original file, not creating a backup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-5.png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Verifying It's Removed Before Sharing

 Let's ensure we've gotten rid of everything before posting it online, shall we? We'll use the same command we used above to re-examine the file:

exiftool donor.jpg

![Terminal window showing command to view the nonexistent EXIF metadata on Debian](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/exiftool-6.png) 

 Much better! There's not much here now, besides what's mandatory as per the EXIF spec.

 Posting pictures online has become ubiquitous. Of course, that doesn't mean you have to share more than you intended to. With exiftool in your arsenal, you can protect yourself and others a bit better. Additionally, along with the power of [scripting](https://common-error.techidaily.com/rebooting-woes-windows-10-troubleshooting/), you can do much more to manipulate the existing metadata in your image library than what's described in this tutorial.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-expert-tips-for-efficient-instagram-to-mp4-transformation/"><u>[New] 2024 Approved  Expert Tips for Efficient Instagram to MP4 Transformation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leading-edge-slow-motion-capture-software-phones-iosandroid/"><u>[New] Leading Edge Slow Motion Capture Software, Phones iOS/Android</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-navigating-the-landscape-intricacies-of-using-the-background-eraser-feature/"><u>[Updated] Navigating the Landscape  Intricacies of Using the Background Eraser Feature</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-twister-timber-titmice-for-2024/"><u>[Updated] Twister Timber Titmice for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-affordable-high-resolution-monitors-for-pc-and-laptop-games/"><u>2024 Approved  Affordable, High-Resolution Monitors for PC & Laptop Games</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-xiaomi-redmi-a2plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/battling-anxiety-with-ai-tips-and-tricks-for-utilizing-chatgpt/"><u>Battling Anxiety with AI: Tips and Tricks for Utilizing ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-your-chatgpt-interactions-five-proven-methods-for-writing-high-quality-prompts/"><u>Boost Your ChatGPT Interactions: Five Proven Methods for Writing High-Quality Prompts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boost-your-prompt-writing-talent-with-these-7-digital-tools/"><u>Boost Your Prompt Writing Talent with These 7 Digital Tools</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boosting-bonds-how-ai-powered-chat-assistants-can-transform-your-search-for-compannionship/"><u>Boosting Bonds: How AI-Powered Chat Assistants Can Transform Your Search for Compannionship</u></a></li>
<li><a href="https://tech-revival.techidaily.com/create-professional-correspondence-with-these-free-ai-services-leverage-chatgpt-to-enhance-email-quality/"><u>Create Professional Correspondence with These Free AI Services: Leverage ChatGPT to Enhance Email Quality</u></a></li>
<li><a href="https://tech-revival.techidaily.com/eager-for-a-gpt-powered-desktop-experience-discover-this-top-open-source-alternative/"><u>Eager for a GPT-Powered Desktop Experience? Discover This Top Open Source Alternative!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/edgeplus-2023-messages-recovery-recover-deleted-messages-from-edgeplus-2023-by-fonelab-android-recover-messages/"><u>Edge+ (2023) Messages Recovery - Recover Deleted Messages from Edge+ (2023)</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/effortless-extraction-of-twitter-jokes-3-ways/"><u>Effortless Extraction of Twitter Jokes  3 Ways</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhance-conversations-10-superior-personal-gpt-variants-that-outshine-chatgpt/"><u>Enhance Conversations: 10 Superior Personal GPT Variants That Outshine ChatGPT</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ethical-engagement-chatgpt-for-emotional-support/"><u>Ethical Engagement: ChatGPT for Emotional Support</u></a></li>
<li><a href="https://tech-revival.techidaily.com/five-ai-driven-tactics-amplifying-malicious-digital-ventures/"><u>Five AI-Driven Tactics: Amplifying Malicious Digital Ventures</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-iphone-15-activation-lock-by-drfone-ios-unlock-ios-unlock/"><u>How to bypass iPhone 15 activation lock</u></a></li>
<li><a href="https://techidaily.com/how-to-free-up-apple-iphone-14-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Free Up Apple iPhone 14 Space | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-lava-yuva-2-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Lava Yuva 2</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-see-someones-location-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>How to See Someones Location on Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/improving-professional-collaboration-with-strategic-office-planning-for-2024/"><u>Improving Professional Collaboration with Strategic Office Planning for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-6-best-apps-to-remove-objects-from-photo-on-iphone/"><u>In 2024, 6 Best Apps to Remove Objects From Photo on iPhone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-ignite-your-channels-engagement-with-targeted-youtube-links/"><u>In 2024, Ignite Your Channel's Engagement with Targeted YouTube Links</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-vivo-y27-4g-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Vivo Y27 4G to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-honor-magic-5-lite-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Honor Magic 5 Lite Phone Network-Ready</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-investing-in-high-quality-ai-prompts-a-smart-choice/"><u>Is Investing in High-Quality AI Prompts a Smart Choice?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-movie-choices-the-chatgpt-guide/"><u>Mastering Movie Choices: The ChatGPT Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-ai-control-mechanisms/"><u>Navigating AI Control Mechanisms</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-numbers-essential-online-stock-market-guides-for-2024/"><u>Navigating Numbers  Essential Online Stock Market Guides for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/optimizing-productivity-should-you-turn-to-bing-chat-or-gpt-3-7-factors/"><u>Optimizing Productivity: Should You Turn to Bing Chat or GPT-3? 7 Factors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/picture-puns-memify-pro-for-2024/"><u>Picture Puns  Memify Pro for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protect-personal-data-preventing-chatgpt-from-archiving-communication/"><u>Protect Personal Data: Preventing ChatGPT From Archiving Communication</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protect-yourself-from-these-5-notorious-chatgpt-scams/"><u>Protect Yourself From These 5 Notorious ChatGPT Scams</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-connection-issues-with-blizzard-games-a-step-by-step-guide/"><u>Resolving Connection Issues with Blizzard Games: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/safeguard-your-pc-why-manual-entry-is-safer-than-relying-on-ai-for-windows-11-license-codes/"><u>Safeguard Your PC: Why Manual Entry Is Safer Than Relying on AI for Windows 11 License Codes</u></a></li>
<li><a href="https://tech-revival.techidaily.com/surpassing-chatgpt-discover-the-top-4-advantages-of-claude-3/"><u>Surpassing ChatGPT? Discover the Top 4 Advantages of Claude 3!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-impact-of-artificial-intelligence-on-interactive-entertainment-industry/"><u>The Impact of Artificial Intelligence on Interactive Entertainment Industry</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-new-era-of-ai-artistry-with-dall-e-3s-editable-tools-still-evolving/"><u>The New Era of AI Artistry with DALL-E 3'S Editable Tools - Still Evolving</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-twittersphere-treasure-trove/"><u>The Twittersphere Treasure Trove</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transformative-techniques-employing-chatgpt-to-boost-your-data-analyst-abilities/"><u>Transformative Techniques: Employing ChatGPT to Boost Your Data Analyst Abilities</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-excel-workflows-using-ai-tips-for-implementing-chatgpt-support/"><u>Transforming Excel Workflows Using AI: Tips for Implementing ChatGPT Support</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-limitations-7-key-downsides-to-using-ai-in-communication-apps/"><u>Understanding the Limitations: 7 Key Downsides to Using AI in Communication Apps</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-the-potential-of-chatgpt-for-generating-stunning-ai-artwork/"><u>Unlocking the Potential of ChatGPT for Generating Stunning AI Artwork</u></a></li>
</ul></div>
