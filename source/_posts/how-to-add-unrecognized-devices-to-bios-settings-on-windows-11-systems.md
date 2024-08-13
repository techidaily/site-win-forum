---
title: How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
date: 2024-08-12T04:56:23.328Z
updated: 2024-08-13T04:56:23.328Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
excerpt: This Article Describes How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/4aac991e64509d68ac8489b0b42db25368d487df0c50d4cd60fbe09c3938eb3d.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![windows 11 setup](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/windows-11-setup.jpg)

 Luckily, if your PC does not have the TPM2.0 chip there is still a way to take advantage of Windows 11 and its features.

 Note: If you use this method, Microsoft reserves the right to deny updates on your OS.

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-flavor-leaders-must-watch-culinary-youtube-stars/"><u>[New] 2024 Approved  Flavor Leaders  Must-Watch Culinary YouTube Stars</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-apples-podcast-submission-requirements-clearly/"><u>[New] Navigating Apple's Podcast Submission Requirements Clearly</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/treamline-your-impact-the-most-effective-video-formats-for-youtube/"><u>[New] Streamline Your Impact  The Most Effective Video Formats for YouTube</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-from-novice-to-pro-your-discord-broadcast-journey/"><u>[Updated] 2024 Approved  From Novice to Pro  Your Discord Broadcast Journey</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-live-stream-showdown-xsplit-vs-obs/"><u>[Updated] 2024 Approved  Live Stream Showdown  XSplit Vs. OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-10-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 10 Blue Screen Error</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-hue-adjustments-making-your-gopro-footage-pop/"><u>2024 Approved  Hue Adjustments  Making Your GoPro Footage Pop</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-zenithbgfreeze-top-background-elimination-solution/"><u>2024 Approved  ZenithBgFreeze  Top Background Elimination Solution</u></a></li>
<li><a href="https://win-forum.techidaily.com/defeating-the-dreaded-error-getting-applications-to-launch-successfully-again/"><u>Defeating the Dreaded Error: Getting Applications to Launch Successfully Again</u></a></li>
<li><a href="https://win-forum.techidaily.com/diagnose-and-solve-the-class-not-registered-issue-on-your-windows-pc/"><u>Diagnose and Solve the 'Class Not Registered' Issue on Your Windows PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/diagnosing-and-fixing-total-disk-utilization-problems-in-windows-11/"><u>Diagnosing and Fixing Total Disk Utilization Problems in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-giants-of-online-networking-facebook-twitter-instagram-youtube-journey/"><u>Discover the Giants of Online Networking: Facebook-Twitter-Instagram-YouTube Journey</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-powerhouses-of-digital-networking-facebook-twitter-instagram-and-youtube/"><u>Discover the Powerhouses of Digital Networking: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/enable-wake-on-lan-for-your-network-devices-using-windows-11/"><u>Enable Wake-on-LAN for Your Network Devices Using Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-and-tricks-for-resolving-windows-10-taskbar-freeze-issues/"><u>Expert Tips and Tricks for Resolving Windows 10 Taskbar Freeze Issues</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-major-social-channels-facebook-twitter-instagram-and-youtube-unveiled/"><u>Exploring Major Social Channels: Facebook, Twitter, Instagram & YouTube Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-popular-online-hubs-connect-on-facebook-twitter-instagram-and-youtube/"><u>Exploring Popular Online Hubs: Connect on Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-essentials-of-bios-and-how-revouninstaller-helps/"><u>Exploring the Essentials of BIOS & How RevoUninstaller Helps</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-functionality-of-system-restore-on-your-windows-11-pc/"><u>Exploring the Functionality of System Restore on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/fast-track-your-pc-enhancing-windows-11-boot-speed-using-simple-strategies/"><u>Fast Track Your PC: Enhancing Windows 11 Boot Speed Using Simple Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/faster-launching-for-windows-11-users-expert-boot-time-optimization-techniques/"><u>Faster Launching for Windows 11 Users: Expert Boot Time Optimization Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-configuring-wake-on-lan-feature-on-your-pc-running-windows-10-or-11/"><u>Guide to Configuring Wake-on-LAN Feature on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-clean-up-eliminating-unwanted-additions-in-microsofts-latest-os/"><u>How to Clean Up: Eliminating Unwanted Additions in Microsoft's Latest OS</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-correctly-resolve-class-not-registered-mistake-on-pcs/"><u>How to Correctly Resolve ‘Class Not Registered’ Mistake on PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-fix-a-non-stop-crashing-windows-explorer-a-guide-of-seven-methods/"><u>How to Fix a Non-Stop Crashing Windows Explorer: A Guide of Seven Methods</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-safeguard-your-text-documents-implement-password-security-features/"><u>How To Safeguard Your Text Documents: Implement Password Security Features</u></a></li>
<li><a href="https://win-forum.techidaily.com/identifying-and-removing-harmful-android-applications-with-revouninstaller/"><u>Identifying and Removing Harmful Android Applications with RevoUninstaller</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-learn-to-navigate-large-tiktok-files-editing-made-simple-and-swift/"><u>In 2024, Learn to Navigate Large TikTok Files  Editing Made Simple and Swift</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-photo-editing-unveiling-background-eraser-in-adobe-photoshop/"><u>In 2024, Mastering Photo Editing  Unveiling Background Eraser in Adobe Photoshop</u></a></li>
<li><a href="https://win-forum.techidaily.com/maintain-your-system-update-device-drivers-on-windows-11-efficiently/"><u>Maintain Your System: Update Device Drivers on Windows 11 Efficiently</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-tips-ensuring-successful-boot-of-rainbow-six-siege/"><u>Master Tips: Ensuring Successful Boot of Rainbow Six Siege</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-file-deletion-in-windows-10-using-the-command-prompt-technique/"><u>Mastering File Deletion in Windows 10 Using the Command Prompt Technique</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-force-quitting-software-issues-in-windows-11-systems/"><u>Mastering the Art of Force Quitting Software Issues in Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-online-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Four of Online Networking: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimize-chromes-voice-the-best-web-based-vocal-modification-apps-for-2024/"><u>Optimize Chrome's Voice  The Best Web-Based Vocal Modification Apps for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/stop-receiving-amber-alerts-on-your-android-device-today/"><u>Stop Receiving AMBER Alerts on Your Android Device Today!</u></a></li>
<li><a href="https://network-issues.techidaily.com/swiftly-solving-youtubes-green-mishaps/"><u>Swiftly Solving YouTube's Green Mishaps</u></a></li>
</ul></div>
