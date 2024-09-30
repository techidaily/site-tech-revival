---
title: Resolving the Issue of Your External Hard Drive Not Appearing on Windows 11
date: 2024-08-16T13:09:53.295Z
updated: 2024-08-17T13:09:53.295Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Resolving the Issue of Your External Hard Drive Not Appearing on Windows 11
excerpt: This Article Describes Resolving the Issue of Your External Hard Drive Not Appearing on Windows 11
thumbnail: https://thmb.techidaily.com/d91a8e4d3e328994798cbf4d4f5c1573225bbff13640403fc40b5c32e2b3cd22.jpg
---

## Windows 11 Hack: Bypassing Driver Signature Checks with Ease

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52a003bb57.jpg)

 On Windows 8 and Windows 10 (64-bit), Microsoft has included a feature,**driver signature enforcement** . It is a feature that is designed to ensure that users of Microsoft can only load drivers that have been signed by Microsoft.

 As much security driver signature enforcement brings us, it does also bring with it some inconveniences. For instance, when you want to use some less official drivers, old unsigned drivers or drivers developed by yourself, this feature needs to be disabled first before you can move on.

 In this post, we will show you two different methods to disable this feature by yourself.

**NOTE** : Please be aware that disabling this feature and using or installing driver that were not officially signed could cause damage to your PC. Please only do so when you fully understand what you are about to do.

[**Method One: Enable Test Signing Mode**](https://tools.techidaily.com/drivereasy/download/)
[**Method Two: Advanced Boot Option**](https://tools.techidaily.com/drivereasy/download/)

 **Method One: Enable Test Signing Mode**

 This method allows you to disable driver signature enforcement**completely** if you don’t enable it again manually.

 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt(Admin)** from the list of choice.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52400287b2.png)
  
 When prompted with administrator permission, just click**Yes** to move on.

 2) In the command prompt window, type in the following command:

bcdedit /set testsigning on

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5256f2d41d.jpg)

 3) Restart your computer to enter test mode. You will be able to see the watermark saying**Test Mode** on the bottom right corner of your desktop.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b526cd6a758.jpg)

 Now you can install or use the driver you want.

 4) If you want to leave Test Mode, repeat step 1) to enter Command Prompt with administrative permission. Then in the command prompt window, type in the following command:

bcedit /set testsigning off

 Make sure you have made no typo and hit**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5277821eea.jpg)

 Then restart your computer into normal mode.

**Method Two: Advanced Boot Option**

 This method allows you to shut off driver signature enforcement feature for once. It is not a permanent change. Restart your computer and this feature is back on again.

 1) Press**Start** button, and then click the icon for Restart and Shut down. Now, press and hold**Shift** key when you choose**Restart** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b5290902f87.png)
  
 2) Choose**Troubleshoot** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52950e64a6.jpg)

 3) Choose**Advanced options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52981a7af8.jpg)

 4) Now choose**Startup Settings** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b529a600eb2.jpg)

 5) Click the**Restart** button here.

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b529d3d6368.jpg)

 6) Press**F7** key on your keyboard to go**Disable driver signature enforcement** .

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b52a003bb57.jpg)

 7) Your PC will restart now and the driver signature enforcement feature will be disabled. You are free to install unsigned drivers as you want. As mentioned above, this is not a permanent fix and it will be gone the next time you restart your computer.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->