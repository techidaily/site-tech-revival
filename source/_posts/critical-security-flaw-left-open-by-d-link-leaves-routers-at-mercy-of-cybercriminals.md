---
title: Critical Security Flaw Left Open by D-Link Leaves Routers at Mercy of Cybercriminals
date: 2024-08-27 21:33:31
updated: 2024-08-29 12:52:29
tags:
  - web
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/52577999789_6417edb804_o.jpg
---

## Critical Security Flaw Left Open by D-Link Leaves Routers at Mercy of Cybercriminals

Security researchers have discovered a critical vulnerability that affects D-Link DIR-859 Wi-Fi routers. This vulnerability, which is currently being exploited by hackers, can expose user credentials and provide remote access to a user's local network. D-Link won't patch the problem and suggests that customers buy a new router.

 The vulnerability, tracked as [CVE-2024-0769](https://nvd.nist.gov/vuln/detail/CVE-2024-0769), carries a severity score of 9.8 and affects all D-Link DIR-859 routers (regardless of their current firmware version).

 Hackers can exploit the CVE to target the 'DEVICE.ACCOUNT.xml' file and obtain sensitive information, such as the device's password. Configuration files associated with access control lists (ACLs) and device firewall settings may also be targeted.

![The D-Link DIR-856 router on a white background.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/74.jpg) 

D-Link

> "The exploit's variations, including one observed in the wild by GreyNoise, enable the extraction of account details from the device. The product is End-of-Life, so it won't be patched, posing long-term exploitation risks. Multiple XML files can be invoked using the vulnerability." - GreyNoise

 Researchers first identified CVE-2024-0769 in January of 2024\. Security monitoring group [GreyNoise](https://www.greynoise.io/blog/perma-vuln-d-link-dir-859-cve-2024-0769) has since observed an attempt to exploit the vulnerability in the wild. While "an" attack isn't too scary, this CVE has been disclosed for a while, so previous attacks may have simply gone undetected. (And, in any case, future attacks are certain.)

 The D-Link DIR-859 launched in 2015 and reached end of service on December 10th, 2020\. It's an extremely outdated router, so poor security doesn't come as much of a surprise. D-Link has published a security advisory to raise awareness of the issue, but it refuses to provide a patch, which is also unsurprising.

 For those wondering, D-Link doesn't appear to be offering discounts or coupons to affected customers.

 Those who currently use the D-Link DIR-859 Wi-Fi router should replace it with [a new router](https://facebook-video-share.techidaily.com/updated-discovering-the-ultimate-10-free-youtube-artist-collaborators-for-2024/). Thankfully, the DIR-859 was an entry-level router with limited speeds and specs—any cheap replacement will be an upgrade in terms of speed, reliability, and security. If you're on a budget, I suggest the [ASUS RT-AX1800S](https://www.amazon.com/ASUS-AX1800-Router-RT-AX1800S-Subscription-Free/dp/B09M9477NS/?tag=hotoge-20&ascsubtag=UUhtgUeUpU2003922&asc%5Frefurl=https%3A%2F%2Fwww.howtogeek.com%2Fd-link-dir-856-router-exposed-to-hackers%2F&asc%5Fcampaign=Short-Term). It offers Wi-Fi 6 connectivity, five Gigabit LAN ports, and dual-band MU-MIMO functionality (which was a notable omission from the D-Link DIR-859 at the time of its release).

 Whatever router you choose, be sure to set it up with a brand new username and password. The username and password associated with your D-Link DIR-859 router may have been compromised.

 Source: [GreyNoise](https://www.greynoise.io/blog/perma-vuln-d-link-dir-859-cve-2024-0769) via [TechRadar](https://www.techradar.com/pro/security/d-link-routers-are-being-hacked-to-steal-customer-passwords-but-it-says-there-is-no-patch)

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
