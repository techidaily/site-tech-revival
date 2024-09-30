---
title: "Complete Walkthrough: Securing Your iPhone Information by Syncing with an Outer Hard Drive on PCs and Apple Computers"
date: 2024-08-29T01:40:38.451Z
updated: 2024-08-30T01:40:38.451Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/bf2709550851c34ad73e4e10402b84c4b2a66d4794566cc36dae676c4f05bd25.jpg
---

## Complete Walkthrough: Securing Your iPhone Information by Syncing with an Outer Hard Drive on PCs and Apple Computers

[![](https://www.macxdvd.com/mobile/../image-style/article-seo/icon4.png)](https://tools.techidaily.com/macxdvd/products/)

[MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/) [Mobile Transfer](https://tools.techidaily.com/macxdvd/products/) [Guide](https://tools.techidaily.com/macxdvd/products/) [Support](https://tools.techidaily.com/macxdvd/products/) 

}[Home](https://tools.techidaily.com/macxdvd/products/) \> [Data Backup](https://tools.techidaily.com/macxdvd/products/) \> Back Up iPhone to an External Hard Drive }

## How to Backup iPhone to an External Hard Drive Directly

_Whether you want to free up space on the computer or keep another safe backup of your iPhone data, if you don't know how to save an iPhone backup on an external hard drive, this post will help. It will show you how to backup iPhone to USB drive directly or using iTunes._

![](https://www.macxdvd.com/mobile/../image-style/article-seo/icon1.png) By [Rico Rodriguez](https://www.linkedin.com/in/rico-rodriguez-06815a104/) to iPhone Tips, iTunes | Last Updated on Sep 13, 2023



While iPhone storage goes up to 512GB, the iOS backups users create become larger. This leads to a heavier burden on the disk space of computers, especially Macs, most of which have very limited storage like 250GB or so. For example, users may have seen the message saying "iPhone restore cannot be saved because of not enough space on the computer". Besides, a full storage will result in slow performance on the computer. To protect iPhone data and avoid any lags on the computer at the same time, we will need to backup iPhone to a USB drive. Today this post will show you how to backup iPhone to an external hard drive on Windows & Mac.

This guide works for macOS Big Sur and ealier and Windows 10/8/7/XP. 

CONTENTS

* [Transfer iTunes backup to external drive](https://tools.techidaily.com/macxdvd/products/)
* [Backup iPhone to USB drive without iTunes](https://tools.techidaily.com/macxdvd/products/)

## Method 1: Copy iTunes Backup to External Hard Drive 

First of all, connect your external hard drive to the computer and create a new folder to save the backup. Now let's go.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
### Step 1: Locate the iTunes backup

Find the iTunes backup folder on your computer:

\* On a Mac, it's saved in /Users/\[username\]/Library/Application Support/MobileSync/Backup.  
 Or you can open a new Finder window and tap Command+Shift+G and enter \~/Library/Application Support/MobileSync/Backup to find the Backup folder quickly.  
 \* On Windows, it's saved in C:\\Users\\\[Username\]\\AppData\\Roaming\\Apple Computer\\MobileSync\\Backup  
 Or you can open Run (Windows 7 and earlier) or Search (Windows 8/10) > type %appdata% (with the percents) and press return. From Application Data, navigate to Apple Computer > MobileSync > Backup to find the folder quickly.

![locate iTunes backup](https://www.macxdvd.com/mobile/article-image/find-itunes.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
### Step 2: Copy iPhone backup to external hard drive

After you find the Backup folder, copy it to the new folder you just created on the USB drive and wait for the transfer to complete. After the Backup folder is moved to the external drive, now back to the original location of the Backup folder on the computer and rename the Backup to Backup-Old or delete it (we suggest you delete it after Step 3).

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Step 3: Change iTunes backup location to the USB drive 

In this step, we'll create a symlink or symbolic link to make a new location for iTunes to backup iPhone, namely, set the external hard drive as the new location for iTunes backup. 

\* On Mac, Launch the Terminal in /Applications/Utilities/ and type in the following command:  
 ln -s /Volumes/\[your hard drive name\]/\[backup folder name\]/Backup/ \~/Library/Application\\ Support/MobileSync/Backup  
 \* On Windows, run Command Prompt as administrator and type the following command and press Enter:  
 mklink /J "C:\\Users\\\[Username\]\\AppData\\Roaming\\Apple Computer\\MobileSync\\Backup" "\[your hard drive name\]:\\ \[backup folder name\]"

![transfer iTunes backup to external drive](https://www.macxdvd.com/mobile/article-image/symlink.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
Hit return and quit Terminal. Go back to \~/Library/Application Support/MobileSync/ folder in Finder (or the path on Windows) and you can see the Backup folder is now a blank icon with an arrow on it. It means you have changed the iTunes backup location and further iPhone will be backed up to the external drive via iTunes. 

![change iTunes backup location](https://www.macxdvd.com/mobile/article-image/back-external1.jpg)

### Step 4 (Optional): Backup iPhone to External USB Drive

 Now you can start to back up iPhone via iTunes as usual to check if it will save iPhone backup to external drive. If you don't know how, we also share you a simple guide: (Then you can delete the Backup-Old folder from the computer)

Keep the USB drive connected > connect iPhone to the computer > open iTunes > click device icon next to the left drop-down menu and then Summary > click Back Up Now under Manually Back Up and Restore section > click Done. 

Check detailed guide on[how to backup iPhone to iTunes](https://tools.techidaily.com/macxdvd/products/)

![backup iPhone to USB drive](https://www.macxdvd.com/mobile/article-image/itunes-backup2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 2: Backup iPhone to External Drive on Windows/Mac Directly

 The above command lines may seem too complicated, especially for a newbie. So we will also share you a way to directly backup iPhone to external hard drive without iTunes. The tool we will use named [**MacX MediaTrans**](https://tools.techidaily.com/macxdvd/products/), an iPhone backup tool that is able to backup videos, music, photos, other data from iPhone to external hard drive on Mac/Windows with a super fast speed. This method is faster, easier and more flexible than iTunes as it allows you to transfer or back up large-size iPhone data to USB drive (like 4K photos or HD videos) separately. 

[![](https://www.macxdvd.com/mobile/../mobile/article-image/down-icon.png) Free download Mac version](https://tools.techidaily.com/macxdvd/products/)  
[![](https://www.macxdvd.com/mobile/../mobile/article-image/down-icon.png) Free download Windows version](https://tools.techidaily.com/winxdvd/products/)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
### Step 1: Set iPhone backup location

Before we start, you also need to connect your iPhone and external hard drive to the computer, then run the software. On Mac, click MediaTrans on the top toolbar of the desktop and click Preferences to bring the Settings page. On windows, simply find the settings button with a gear icon ne the right top corner of the main interface. In the Settings window, select the Export default path and navigate to the connected external drive.

![save iPhone backups to external drive](https://www.macxdvd.com/mobile/article-image/settings-path-1.png)

### Step 2: Save iPhone backup to external hard drive

Click the data category you want to back up, like Photo Transfer, Music Manager, Video from the main interface. Below we will show you how to backup iPhone photos to external hard drive as an example. 

After you click Photo Transfer, you will see all your photos listed here with each album displayed on the left bar > click Select All checkbox below the top toolbar to save all the photos at once or press Ctrl and select the photos you'd like to backup > click Export on the top toolbar and the iPhone photos will be saved to the external drive. You can backup other iPhone data in the same way. 

Check detailed guide on [how to backup iPhone without iTunes](https://tools.techidaily.com/macxdvd/products/)

![backup iPhone photos to external hard drive](https://www.macxdvd.com/mobile/article-image/photo-month-1.png)

Still have any problem to save iPhone backup to external hard drive, just [email us >>](https://tools.techidaily.com/macxdvd/products/) 

 Tags: [iPhone](https://tools.techidaily.com/macxdvd/products/) [Apple Related Tips](https://tools.techidaily.com/macxdvd/products/) [iTunes](https://tools.techidaily.com/macxdvd/products/) 

Related Articles

![](https://www.macxdvd.com/mobile/../image-style/article-seo/img1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
[How to Transfer Pictures from iPhone to a USB Flash Drive](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mobile/../image-style/article-seo/img2.jpg)

[How to Backup iPhone Camera Roll Photos in a Faster Way](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/mobile/../image-style/article-seo/img3.jpg)

[Simple Methods to Backup Old Phone Files Without iCloud](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mobile/../image-style/article-seo/mt.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
### [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

One-click to backup videos, photos, music, iTunes items, books, other data from iPhone to an external hard drive. 

[![](https://www.macxdvd.com/mobile/../image-style/article-seo/fd.png)](https://tools.techidaily.com/macxdvd/products/) 

Trusted by Macworld,CNET

MOST READ

1 [How to Backup iPhone to Mac in A Way Easier than iTunes](https://tools.techidaily.com/macxdvd/products/) 

2 [iPhone Backup Software for Mac - Copy iPhone Data without iTunes](https://tools.techidaily.com/macxdvd/products/) 

3 [How to Backup iPhone to iCloud on Mac/Windows PCs](https://tools.techidaily.com/macxdvd/products/) 

4 [Real Fixes to Photos Not Uploading to iCloud Photo Library](https://tools.techidaily.com/macxdvd/products/) 



![Digiarty Software](https://www.macxdvd.com/mobile/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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



[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Site Map](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

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


