---
title: Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers
date: 2024-08-24T14:10:26.638Z
updated: 2024-08-25T14:10:26.638Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers
excerpt: This Article Describes Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers
thumbnail: https://thmb.techidaily.com/e35b3a5c1a462189bf0e7eb85d4007a41df15f6c2fae50b407ca5b13b61d24c2.jpg
---

## Overcome 'Platform Unsupported' Message When Setting Up Intel Serial IO Drivers

While installing Intel® Serial IO host controller driver, if you get error message **“The setup program ended prematurely because of the following error: This platform is not supported”** **,** don’t worry. The error can be easy to fix. The error would occur if I2C is not enabled in BIOS. To resolve the problem, just enable I2C in BIOS.

 [![1028](https://images.drivereasy.com/wp-content/uploads/2015/10/1028-300x244.png)](https://images.drivereasy.com/wp-content/uploads/2015/10/1028.png) 

  Please refer to the guide below how to enable I2C in BIOS.

  1\. Press **F2** during boot to enter BIOS Setup.

 2\. Go to the **Advanced** \> **Devices** \> **Onboard Devices** menu.

On the Legacy Device Configuration pane:

 3\. Set **Pins 13/14** to **I2C0\_SCL/I2C0\_SDA** .

 4\. Set **Pins 15/16** to **I2C1\_SCL/I2C1\_SDA** .

 5\. Press **F10** to save and exit BIOS Setup.

  After enabling I2C in BIOS, you can install the Intel® Serial IO host controller driver again.

 I2C is enabled for the Low Speed Custom Solutions Header. So if you don’t wish to use the Low Speed Custom Solutions Header, you don’t need to install this driver.

  If you use[Driver Easy](https://tools.techidaily.com/drivereasy/download/) to install this driver and meet this problem, follow the guide here and the problem will be resolved. Alternatively, you can skip to install this driver by clicking the arrow button and selecting**Hide this Update** .

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



<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->