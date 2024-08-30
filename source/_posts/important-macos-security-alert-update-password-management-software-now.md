---
title: "Important macOS Security Alert: Update Password Management Software Now!"
date: 2024-08-26 18:22:15
updated: 2024-08-29 10:40:58
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3b2bc9a3a892785318d5d0f2114220ad982ea100320932632e38a5b677339306.jpg
---

## Important macOS Security Alert: Update Password Management Software Now!

A flaw in 1Password 8 for macOS may leave vault items exposed to hackers or malware. The issue, which was discovered by Robinhood's Red Team, is resolved in 1Password 8 version 8.10.36 and later.

 This issue, identified as [CVE-2024-42219](https://nvd.nist.gov/vuln/detail/CVE-2024-42219), is due to an incomplete XPC inter-process communication implementation. In plain English, the thing that's supposed to prevent untrusted apps from talking to 1Password is broken. An attacker who gains access to a victim's Mac could impersonate a trusted app (such as the 1Password browser extension), collect security keys from the victim, and swipe the victim's vaults.

 Robinhood's Red Team, along with 1Password itself, say that CVE-2024-42219 has not been exploited in the wild. It was also patched in the July's8.10.36 update, meaning that very few 1Password users are currently vulnerable to the threat.

 The company hasn't specified whether CVE-2024-42219 affects 1Password 7, which a small fraction of users still cling to. That said, 1Password 7 is discontinued and no longer receives regular security updates. We do not recommend using 1Password 7.

![A screenshot of the 1Password 'About' page with the current version number highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/12.jpg) 

Andrew Heinzman / How-To Geek

 The 1Password desktop app is very good at updating itself. Still, you should check 1Password's current version number from the "About" panel in the app's settings (open 1Password, press Command+Comma on your keyboard, and select "About"). If you're running version 8.10.36 or 8.10.38, you're all good.

 Auto-updates may fail if 1Password isn't regularly used or if the app's background processes are disabled. If you find that you're running an outdated version of 1Password, press the "Check for Updates" button on the "About" page. Or, click "Restart Now" if the app has already detected a new update.

 Note that 1Password 8.10.38 may automatically "reset some of your settings to default" as a "safety precaution." This is due to new [security improvements](https://1password.community/discussion/comment/715748/#Comment%5F715748) that were previously tested in the beta channel (and are unrelated to CVE-2024-42219). The 1Password team did not anticipate this error message, and it hasn't specified which settings may be automatically set to default.

 Source: [1Password](https://support.1password.com/kb/202408a/) via [The Register](https://www.theregister.com/2024/08/08/using%5F1password%5Fon%5Fmac%5Fpatch/)

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
