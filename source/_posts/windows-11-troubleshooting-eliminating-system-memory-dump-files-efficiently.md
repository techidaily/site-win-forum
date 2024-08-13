---
title: "Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
date: 2024-08-12T04:48:11.595Z
updated: 2024-08-13T04:48:11.595Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
excerpt: "This Article Describes Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
thumbnail: https://thmb.techidaily.com/ad7d05b0030775951042fde08b0fbde9a0ebb4cf05f0435bf5618af5d7b42ae3.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

![windows 11 setup](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/windows-11-setup.jpg)

 Luckily, if your PC does not have the TPM2.0 chip there is still a way to take advantage of Windows 11 and its features.

 Note: If you use this method, Microsoft reserves the right to deny updates on your OS.

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
## We can help you every time when…

* you cannot find the program in the Apps & Features list
* the program's built-in uninstaller is non-functional
* you have a lot of leftovers slowing down your computer's performance
* you want to batch uninstall
* many more things
[Download now](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-cinematic-capture-top-picks-from-video-experts-for-2024/"><u>[New] Cinematic Capture  Top Picks From Video Experts for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/avigating-the-best-dates-and-hours-for-youtube-impact-for-2024/"><u>[New] Navigating the Best Dates and Hours for YouTube Impact for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/1715860544444-updated-inbuilt-screen-capture-huaweis-mate-series-and-p-lineup-phones/"><u>[Updated] Inbuilt Screen Capture  Huawei's Mate Series & P Lineup Phones.</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-next-gen-players-guide-rift-vive-vs-ps-vr-games/"><u>[Updated] Next-Gen Players Guide  Rift, Vive, vs PS VR Games</u></a></li>
<li><a href="https://win-forum.techidaily.com/activating-remote-access-the-ultimate-walkthrough-for-windows-11s-wake-on-lan/"><u>Activating Remote Access: The Ultimate Walkthrough for Windows 11'S Wake-on-LAN</u></a></li>
<li><a href="https://win-forum.techidaily.com/activating-wol-technology-in-windows-10-and-windows-11-a-comprehensive-guide/"><u>Activating WOL Technology in Windows 10 and Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-download.techidaily.com/after-every-quote-integration-include-a-parenthetical-citation-with-the-year-when-the-quote-was-said-eg-preparedness-is-key-the-best-way-to-predict-your-fut215/"><u>After Every Quote Integration, Include a Parenthetical Citation with the Year when the Quote Was Said (E.g., Preparedness Is Key: 'The Best Way to Predict Your Future...' (Warren Buffett, 2014)).</u></a></li>
<li><a href="https://win-forum.techidaily.com/bypassing-control-panel-for-uninstalling-non-displayed-programs-a-how-to/"><u>Bypassing Control Panel for Uninstalling Non-Displayed Programs: A How-To</u></a></li>
<li><a href="https://win-forum.techidaily.com/clear-your-windows-11-storage-essential-tips-for-freeing-up-disk-space/"><u>Clear Your Windows 11 Storage: Essential Tips for Freeing Up Disk Space</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparative-guide-to-popular-social-sites-facebook-twitter-instagram-alongside-youtube/"><u>Comparative Guide to Popular Social Sites: Facebook, Twitter, Instagram Alongside YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-solving-high-disk-utilization-on-windows-10-pcs/"><u>Complete Guide: Solving High Disk Utilization on Windows 10 PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-fixes-overcoming-pc-compatibility-issues-with-windows-11/"><u>Comprehensive Fixes: Overcoming PC Compatibility Issues with Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-resetting-windows-11-to-its-original-state-for-optimal-performance/"><u>Comprehensive Tutorial on Resetting Windows 11 to Its Original State for Optimal Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-leading-platforms-facebook-twitter-instagram-and-youtube/"><u>Connect and Share on Leading Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-with-audiennce-on-major-platforms-unpacking-facebook-twitter-instagram-and-youtube/"><u>Connecting with Audiennce on Major Platforms: Unpacking Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/defend-sensitive-information-in-plain-text-files-with-robust-password-encryption-tips/"><u>Defend Sensitive Information in Plain Text Files with Robust Password Encryption Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-with-social-giants-exploring-facebook-twitter-instagram-and-youtube/"><u>Engage with Social Giants - Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-how-to-get-rid-of-crash-dump-files-on-your-windows-10-machine/"><u>Expert Advice: How to Get Rid of Crash Dump Files on Your Windows 10 Machine</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-popular-online-networking-sites-facebook-twitter-instagram-youtube/"><u>Exploring Popular Online Networking Sites: Facebook | Twitter | Instagram | YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/facetime-for-android-the-ten-best-free-alternatives-to-facetime-on-android-for-2024/"><u>FaceTime for Android  The Ten Best Free Alternatives to FaceTime on Android for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-samsung-galaxy-f14-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Samsung Galaxy F14 5G FRP Bypass</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915403078-masterclass-how-to-successfully-update-and-maintain-device-drivers-in-windows-cuhmmm/"><u>Masterclass: How to Successfully Update and Maintain Device Drivers in Windows Cuhmmm</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915390302-navigating-the-digital-sphere-with-leading-platforms-facebook-twitter-instagram-and-youtube-guides/"><u>Navigating the Digital Sphere with Leading Platforms: Facebook, Twitter, Instagram & Youtube Guides.</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-unforeseen-glitches-on-your-windows-11-machine-a-step-by-step-fix-guide/"><u>Navigating Unforeseen Glitches on Your Windows 11 Machine: A Step-by-Step Fix Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-hardware-restrictions-installing-windows-11-with-revouninstaller-on-non-compatible-cpus/"><u>Overcoming Hardware Restrictions: Installing Windows 11 with RevoUninstaller on Non-Compatible CPUs</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-fix-get-your-samsung-c460-printers-latest-drivers-instantly/"><u>Quick Fix: Get Your Samsung C460 Printer's Latest Drivers Instantly</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-tricks-for-determining-the-powershell-version-on-your-windows-11-system/"><u>Quick Tricks for Determining the PowerShell Version on Your Windows 11 System</u></a></li>
<li><a href="https://games-able.techidaily.com/reconnecting-windows-11-steam-with-online-friends/"><u>Reconnecting Windows 11 Steam with Online Friends</u></a></li>
<li><a href="https://win-forum.techidaily.com/securing-your-system-5-key-methods-to-protect-your-windows-machine/"><u>Securing Your System: 5 Key Methods to Protect Your Windows Machine</u></a></li>
<li><a href="https://win-forum.techidaily.com/simple-guide-to-clearing-out-user-profiles-on-your-windows-10-device-successfully/"><u>Simple Guide to Clearing Out User Profiles on Your Windows 10 Device Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-butterflies-go-online-mastering-interaction-on-facebook-twitter-instagram-and-youtube/"><u>Social Butterflies Go Online: Mastering Interaction on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-excellence-building-a-robust-online-footprint-across-facebook-twitter-instagram-and-youtube/"><u>Social Media Excellence: Building a Robust Online Footprint Across Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-explained-maximizing-presence-on-facebook-twitter-instagram-and-youtube/"><u>Social Media Giants Explained: Maximizing Presence on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-titans-the-power-of-facebook-twitter-instagram-and-youtube-in-modern-communication/"><u>Social Media Titans: The Power of Facebook, Twitter, Instagram & YouTube in Modern Communication</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-complete-factory-reset-on-windows-11-using-revo-uninstaller-pro/"><u>Step-by-Step Guide: Complete Factory Reset on Windows 11 Using Revo Uninstaller Pro</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-forcibly-terminating-unresponsive-programs-in-windows-11/"><u>Step-by-Step Guide: Forcibly Terminating Unresponsive Programs in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-social-media-a-deep-dive-into-facebook-twitter-instagram-and-youtubes-influence/"><u>The Big Four in Social Media: A Deep Dive Into Facebook, Twitter, Instagram & YouTube's Influence</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-social-networking-fb-tw-insta-yt/"><u>The Big Four of Social Networking: FB, TW, INSTA, YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-definitive-guide-eliminate-user-accounts-from-your-pc-using-revo-uninstaller-on-windows/"><u>The Definitive Guide: Eliminate User Accounts From Your PC Using Revo Uninstaller on Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-giants-mastering-engagement-across-facebook-twitter-instagram-and-youtube/"><u>The Digital Giants: Mastering Engagement Across Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-leading-social-media-sites-for-sharing-content-fb-twt-ig-yt-channels/"><u>The Leading Social Media Sites for Sharing Content: FB, TWT, IG, YT Channels</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-quartet-of-online-engagement-uncovering-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Quartet of Online Engagement: Uncovering Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-trick-to-clean-up-persistent-folders-using-revo-uninstaller-on-windows-1nk-and-11/"><u>The Ultimate Trick to Clean Up Persistent Folders Using Revo Uninstaller on Windows 1Nk & 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-5-strategies-to-secure-your-windows-pc-essential-techniques/"><u>Top 5 Strategies to Secure Your Windows PC: Essential Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-7-solutions-when-windows-explorer-continually-fails-explore-with-revouninstaller/"><u>Top 7 Solutions When Windows Explorer Continually Fails – Explore With RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-class-not-found-errors-for-windows-users/"><u>Troubleshooting 'Class Not Found' Errors for Windows Users</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-microsoft-flight-simulator-2020-a-step-by-step-guide-to-bypass-persistent-updates-screen/"><u>Troubleshooting Microsoft Flight Simulator 2020 – A Step-by-Step Guide to Bypass Persistent Updates Screen</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-giants-of-social-networking-facebook-twitter-instagram-youtube-guide/"><u>Understanding the Giants of Social Networking: Facebook-Twitter-Instagram-YouTube Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-profile-erasure-made-simple-a-revo-uninstaller-walkthrough/"><u>Windows 11 Profile Erasure Made Simple - A Revo Uninstaller Walkthrough</u></a></li>
</ul></div>
