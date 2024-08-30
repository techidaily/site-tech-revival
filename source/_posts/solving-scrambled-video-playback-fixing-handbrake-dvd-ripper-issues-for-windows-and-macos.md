---
title: "Solving Scrambled Video Playback: Fixing Handbrake DVD Ripper Issues for Windows and macOS"
date: 2024-08-24 15:12:49
updated: 2024-08-27 11:38:45
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/7e92efb572f341d595fdf51653eb900bed0a3b4c499d6d0e966107ddb98f908c.jpg
---

## Solving Scrambled Video Playback: Fixing Handbrake DVD Ripper Issues for Windows and macOS

[![macx dvd ripper pro icon](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/icon12.png)](https://tools.techidaily.com/macxdvd/products/)

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [Guide](https://tools.techidaily.com/macxdvd/products/)
* [Support](https://tools.techidaily.com/macxdvd/products/)
* [Free Download](https://tools.techidaily.com/macxdvd/products/)



![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/icon7.png) [Home](https://tools.techidaily.com/macxdvd/products/) \> [DVD](https://tools.techidaily.com/macxdvd/products/) \> [Rip DVDs](https://tools.techidaily.com/macxdvd/products/) \>HandBrake DVD Rip Scrambled 

## \[Fixed\] HandBrake DVD Ripped Videos Get Scrambled 



_Users are getting badly pixelated and garbled video when using Handbrake to rip a DVD. Why and how to fix? This post summerizes all the possible reasons and corresponding fixes that will solve Handbrake distoreted video problems in 99% cases._ 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/icon6.png) By [Bella Brown](https://tools.techidaily.com/macxdvd/products/) ｜Last updated on Feb.23, 2023 

* [![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/share-fa.jpg)](https://www.facebook.com/sharer/sharer.php?u=https://www.macxdvd.com//mac-dvd-ripper-pro/handbrake-scrambled-video-mac-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/share-tw.jpg)](https://twitter.com/intent/tweet?url=https://www.macxdvd.com//mac-dvd-ripper-pro/handbrake-scrambled-video-mac-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/share-go.jpg)](https://pinterest.com/pin/create/button/?url=https://www.macxdvd.com//mac-dvd-ripper-pro/handbrake-scrambled-video-mac-fixed.htm)
* [![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com//mac-dvd-ripper-pro/handbrake-scrambled-video-mac-fixed.htm&title=&summary=https://www.macxdvd.com//mac-dvd-ripper-pro/handbrake-scrambled-video-mac-fixed.htm&source=)

_"I've been using the same presets in Handbrake for a long time to encode many videos in the past. But now all I get is an unwatchable scrambled video. The libdvdcss has been installed so I guess it's not an encryption issue. Handbrake 1.0.7\. macOS 10.13 High Sierra."_

This is a frustrated user from Handbrake forum and similar Handbrake scrambled video problems with macOS are ubiquitous on VideoHelp Forum, MacRumors, etc. When using Handbrake to rip DVD or encode videos, the output videos are sometimes pixelated and distorted with annoying RGB blocks. In this post, we're going to discuss what causes the Handbrake DVD rip scrambled problems on Mac (and also PC) and how to fix them. 

![Handbrake distorted DVD rip on macOS](https://www.macxdvd.com/mac-dvd-ripper-pro/article-image/scrambled-video.jpg) 

Handbrake distorted DVD rip on macOS

## \[100% Fixed\] Handbrake Scrambled Video Errors in DVD Ripping 

### [**MacX DVD Ripper Pro**](https://tools.techidaily.com/macxdvd/products/)\- Rip any protected DVD without Handbrake scrambed/distorted video errors. 

* Rip new DVDs, multiple titles, Disney movies, workout discs, etc. with any protections.
* Convert DVDs to 1:1 ISO image, mp4, mkv, hevc, avi, mov, flv, 3gp, mp3, aac, etc.
* GPU hardware acceleration based on Intel, Nvidia, AMD to offer super-fast DVD ripping speed.
* Advanced Safe Mode, Deinterlacing Accelerator and High Quality Engine ensure best output quality.

[Download for Mac](https://tools.techidaily.com/macxdvd/products/) [Download for PC](https://tools.techidaily.com/macxdvd/products/) 

## Table of Contents

* [Part 1: Reasons & Fixes to Handbrake DVD Rip Scrambled on Mac](https://tools.techidaily.com/macxdvd/products/)
* [Part 2: Ultimate Fix to Handbrake Pixelated and Scrambled DVD Rip](https://tools.techidaily.com/macxdvd/products/)

## Reasons & Fixes to Handbrake DVD Rip Scrambled on Mac

### 1\. Incorrect libdvdcss 

CSS (Content Scrambling System) is the major cause for distorted and garbled Handbrake DVD rip. DVD with CSS protection has multiple fake titles with the same length. Unless Handbrake finds the correct title, the output video will be broken or distorted. Handbrake out of the box can't deal with CSS, but the libdvdcss lets Handbrake decrypt and unscramble DVDs. However, [Handbrake libdvdcss errors](https://tools.techidaily.com/macxdvd/products/) will lead to scrambled video effects. 

Make sure you have stored the libdvdcss library in the correct directory, namely the "/usr/local/lib" folder. To get the library, open a Terminal and run the following commands:

_cd /usr/local/lib_ 
_sudo curl -O https://download.videolan.org/libdvdcss/1.2.11/macosx/libdvdcss.2.dylib_

If you don't have _/usr/local/lib_ folder and save the libdvdcss somewhere like _"/usr/lib"_, you may still see Handbrake ripped video with green blocks or pixelated effects on Mac. /usr/lib is probably write protected with SIP. You should then run the following command to create it:

_sudo mkdir -p /usr/local/lib_

Note that you shoud sudo cp into the /usr/local/lib directory. Or use the Finder with shift-**⌘-**g and type in /usr/local/lib to open a window to copy the files. You should get prompted for a admin account, follow the prompts, and completely restart Handbrake. Then you should be able to rip DVD on Mac using Handbrake without scrambled/distorted video error. 

### 2\. Other DVD protections

Like the user complaints at the beginning of this article, why Handbrake still gives scrambled video on Mac even with libdvdcss installed. Here are two reasons:

* Since HandBrake 1.3 and higher uses the Apple's Hardened Runtime, they can load only dynamic libraries that are signed with a valid Apple Developer ID certificate. HomeBrew libdvdcss is not signed.
* Even installed, libdvdcss won't rip DVD with tough discs. Discs like Disney movies, workout discs, UDF, non-UDF or ISO 9660 and others are still a challenge that leads the pixelated and scrambled DVD rip with Handbrake. In this case, try other DVD rippers like MakeMKV. FYI, MacX DVD Ripper Pro supports a wide range of DVD encryptions that frustrate Handbrake.

### 3\. Check if the libdvdcss is blocked on Mac

Still have Handbrake pixelated/scrambed video after DVD ripping on Mac? Don't forget to check your Gatekeeper. Gatekeeper in macOS is used to open trusted apps on Mac. When you download and install apps from the internet or directly from a developer, just like Handbrake and libdvdcss, you need to right click the .app and choose Open to get rid of the Gatekeeper. In some cases, the .dylib files are being blocked by Gatekeeper without warning the user. That results in green blocks and scrambed pictures after Handbrake DVD rip. You need to right click all of the .dylib files and chose open.

### 4\. Wrong HW encoding

Handbrake has added AMD VCE, Nvidia NVENC (Windows), and Apple VideoToolbox (macOS) hardware-accelerated video encoding for a faster speed. But they are the culprit to part of Handbrake scrambled video problems. There are users reporting that the H.264 videos encoded with VideoToolbox GPU acceleration are completely scrambled, full of colored blocks, skipping, lagging and 100% unwatchable. The badly pixelated problems happen more often with Intel QSV on Windows. Currently, we're not sure if it's a bug or anything, but there are fixes.([Check Handbrake GPU acceleration guide](https://tools.techidaily.com/macxdvd/products/))

* Disable GPU encoding by clicking Video > select H.264 instead of H.264 (VideoToolbox).
* H.264 is famous for good quality and relatively small size mainly for its Psycho-Visual optimization. Even when there is no scrambled result with GPU encoding, it will suffer quality loss compared to CPU encoding. If you want both speed and quality, MacX DVD Ripper Pro is worth a shot. It supports Intel QSV, AMD and Nivida for H.264/H.265 and has a High Quality Engine to ensure the output quality.

### 5\. Bad DVD sectors

Another possible reason to Handbrake DVD rip scrambled on macOS is that the disc is damaged. Rather than the bad sector DVD protection, the disc may be damaged or scratched sometimes. In this case, Handbrake may get stuck, fail to rip or give scrambled videos. Hold down the option key while click the Open button and then you can tell Handbrake the individual title you want to rip instead of the entire source. But if the bad sector is in the title you want, you can't select the specific length. Handbrake can't do that. Now you will need a third-party ripper that comes along the ability to [copy damaged DVD](https://tools.techidaily.com/macxdvd/products/).

### 6\. Interlaced VC1 format

DVD and Blu-ray owners usually use Handbrake and MakeMKV together. As Handbrake won't support Blu-ray discs, they often rip Blu-ray into MKV and transcode AC-1 to H.264 using Handbrake. Then problems occur. The VC-1 interlaced videos ripped from MakeMKV end up with annoying pixels and blocks through Handbrake. Why? The VC-1 decoding bug may plague libavcodec. 

* Try xmedia recode that uses ffmpeg DXVA decoder to transcode VC-1\.
* The latest nightly builds or update to the latest version should transcode VC-1 to x264 without Handbrake scrambled video artifacts.

### 7\. Graphics Card's Upscaling 

The pixelated DVD rip may not be caused by Handbrake, but rather with your graphics card's upscaling. In VLC, try switching Video -> Output to Windows GDI Video Output, and disable hardware decoding (Input/Codecs -> Hardware-accelrated Decoding -> Disable). Does that look better?

## Ultimate Fix to Handbrake Pixelated and Scrambled DVD Rip 

Handbrake is a video transcoder instead of a ripper. If you still get pixelated video with Handbrake after trying all the above fixes, try another DVD ripper. Here [**MacX DVD Ripper Pro**](https://tools.techidaily.com/macxdvd/products/) is able to rip any copy-protected/damaged DVDs without giving green blocks or pixels like Handbrake. 

[Download for Mac](https://tools.techidaily.com/macxdvd/products/) [Download for PC](https://tools.techidaily.com/macxdvd/products/) 

**Step 1: Load DVD Movie** 

 Free download the Handbrake alternative DVD ripper and click Disc to load the DVD. 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../mobile/article-image/down-icon.png) [Free download MacX DVD Ripper Pro on Mac](https://tools.techidaily.com/macxdvd/products/)![](https://www.macxdvd.com/mac-dvd-ripper-pro/../mobile/article-image/down-icon.png) [Free download MacX DVD Ripper Pro on Windows](https://tools.techidaily.com/macxdvd/products/)

**Step 2: Select the Output Video Format** 

The DVD ripper will automatically identify the correct title and ask you to select the output format. You can convert a DVD to H.264, H.265, MOV, MP4, AVI, MKV, VOB, iPhone, Samsung and more as shown in the figure below.

![fix Handbrake distorted video](https://www.macxdvd.com/mac-dvd-ripper-pro/../mac-dvd-video-converter-how-to/article-image/drp-review-rip-dvd.jpg)

**Step 3: Edit the DVD**

It's also a [DVD editing program](https://tools.techidaily.com/macxdvd/products/). For example, when the Handbrake scrambled video errors on Mac are cuased by a bad sector, you can cut out the damaged portion with the Edit feature. Click the Edit button from the selected title and set the exact starting and ending time of the length that you need.

![Handbrake pixelated video fix](https://www.macxdvd.com/mac-dvd-ripper-pro/article-image/import-itunes3.png)

**Step 4: Adjust DVD Rippping Settings**

On the right lower part of the interface, there are several important buttons you need to check. 

* Hardware Encoder - apply Intel/AMD/Nvidia when applicable when converting a DVD into H.264/H.265 for about 5x faster speed.
* Safe Mode - a unique feature that will deal with most tough protections and avoid any pixelated or scrambled outputs like Handbrake.
* High Quality Engine and Deinterlacing - two technologies from the company that can ensure the maximum output quality.

![rip DVD without Handbrake pixelated and garbled video](https://www.macxdvd.com/mac-dvd-ripper-pro/article-image/hw-settings.jpg)

**Step 5: Click Run and Start Ripping**. The Hardware Encoder will speed up the ripping process and finish the task within minutes.

Note: We only advocates using the best DVD ripper for Mac to rip protected DVDs for Mac under the concept of Fair Use and does not encourage any illegal reproduction or distribution of copyrighted content. Please abide by the local DVD copyright law before doing it. Still have any problem on converting the entire movie with Handbrake, just [email us >>](https://tools.techidaily.com/macxdvd/products/)

ABOUT THE AUTHOR

![author- bella](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/bella.png) 

[Bella Brown ![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/bella-brown-920145104/) 

Bella has been working with DVD digitization for over 12 years. She writes articles about everything related to DVD, from disc drive, DVD copyright protection, physical structure, burning and backup tips. The unceasing passion of DVD movies helps her build a rich DVD library and ensure a practical solution to address almost all possible DVD issues. Bella is also a crazy fan for Apple products.



Related Articles

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic7.jpg)

[Handbrake Tutorial: Freely & Easily Convert DVD to MP4 with Handbrake](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic6.jpg)

[How to Make Handbrake Decrypt DVD Copy Protection](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic5.jpg)

[Handbrake Error in Reading from DVD? Problem Gets Solved!](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic4.jpg)

[Handbrake Failed to Rip Disney DVD? How to Rip Disney DVD in Handbrake?](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic3.jpg)

[HandBrake Won't Scan and Show All Titles](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-ripper-pro/../image-style/new-seo/pic2.jpg)

[Rip DVD with Handbrake Alternative Freeware to Unlock Copy Protection](https://tools.techidaily.com/macxdvd/products/) 



![Digiarty Software](https://www.macxdvd.com/mac-dvd-ripper-pro/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

### Company

* [About Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Tech & Sales FAQ >>](https://tools.techidaily.com/macxdvd/products/)
* [User Guides >>](https://tools.techidaily.com/macxdvd/products/)
* [Contact Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Partner >>](https://tools.techidaily.com/macxdvd/products/)



[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

Copyright © 2024 Digiarty Software, Inc (MacXDVD). All rights reserved

Apple, the Apple logo, Mac, iPhone, iPad, iPod and iTunes are trademarks of Apple Inc, registered in the U.S. and other countries.  
Digiarty Software is not developed by or affiliated with Apple Inc.

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
