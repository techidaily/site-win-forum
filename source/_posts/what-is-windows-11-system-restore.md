---
title: What Is Windows 11 System Restore
date: 2024-08-12T05:01:36.407Z
updated: 2024-08-13T05:01:36.407Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes What Is Windows 11 System Restore
excerpt: This Article Describes What Is Windows 11 System Restore
thumbnail: https://thmb.techidaily.com/005e6344e4c73e50ccb232f7e6d3806cb38585b8b60bbb71db163db20304611c.jpg
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://some-approaches.techidaily.com/new-symphony-in-softness-playback-reduction-guide/"><u>[New] Symphony in Softness  Playback Reduction Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-10-common-vlogging-fears-and-how-to-beat-them/"><u>[Updated] 2024 Approved  10 Common Vlogging Fears and How To Beat Them</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-essential-tips-for-gameplay-screen-shotting-on-playstation-4/"><u>[Updated] 2024 Approved  Essential Tips for Gameplay Screen Shotting on PlayStation 4</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-video-expertise-elevated-streamline-your-edits-with-these-vimeo-shortening-techniques/"><u>[Updated] 2024 Approved  Video Expertise Elevated  Streamline Your Edits with These Vimeo Shortening Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-farm-family-fun-pack-the-ultimate-agritainment-guide-for-2024/"><u>[Updated] Farm Family Fun-Pack  The Ultimate Agritainment Guide for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-precision-techniques-for-messenger-content-extraction/"><u>[Updated] In 2024, Precision Techniques for Messenger Content Extraction</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-guide-to-maximizing-reach-on-major-social-networks-facebook-twitter-instagram-and-youtube-insights/"><u>A Guide to Maximizing Reach on Major Social Networks - Facebook, Twitter, Instagram & YouTube Insights</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/ai-powered-youtube-monetization-strategies-2024-guidebook/"><u>AI-Powered Youtube Monetization Strategies - 2024 Guidebook</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/budget-conscious-consumers-guide-to-caixun-75-inch-4k-android-smart-tv-a-comprehensive-review/"><u>Budget-Conscious Consumer's Guide to Caixun 75 Inch 4K Android Smart TV - A Comprehensive Review!</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-tutorial-on-removing-windows-11-patches/"><u>Complete Tutorial on Removing Windows 11 Patches</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-guide-to-popular-media-outlets-facebook-twitter-instagram-and-youtube/"><u>Comprehensive Guide to Popular Media Outlets: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-solutions-for-addressing-full-disk-capacity-in-windows-10-systems/"><u>Comprehensive Solutions for Addressing Full-Disk Capacity in Windows 10 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-major-social-sites-twitter-instagram-facebook-and-youtube-insights/"><u>Connect and Share on Major Social Sites: Twitter, Instagram, Facebook & YouTube Insights</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1715701216752-employing-in-device-recording-for-screen-capture-across-huaweis-mate-and-p-series/"><u>Employing In-Device Recording for Screen Capture Across Huawei’s Mate and P Series.</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-platforms-in-digital-communication-facebook-twitter-instagram-and-youtube/"><u>Essential Platforms in Digital Communication: Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-factory-reinitialize-your-windows-11-system-effortlessly/"><u>Expert Advice: Factory Reinitialize Your Windows 11 System Effortlessly</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-methods-for-uninstalling-non-control-panel-applications/"><u>Expert Methods for Uninstalling Non-Control Panel Applications</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-passive-viewers-to-earnings-youtubes-monetization-mastery-for-2024/"><u>From Passive Viewers to Earnings  YouTube's Monetization Mastery for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-enabling-wake-on-lan-feature-on-windows-11-systems/"><u>Guide: Enabling Wake-on-LAN Feature on Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-correctly-address-not-as-expected-messages-on-windows-11/"><u>How to Correctly Address 'Not As Expected' Messages on Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-easily-fix-a-non-responsive-imessage-app-on-ios-and-macos/"><u>How to Easily Fix a Non-Responsive iMessage App on iOS and macOS</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-fix-100-disk-usage-in-windows-10/"><u>How to Fix 100%% Disk Usage in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-immediately-force-quit-stalled-window-software-a-step-by-step-walkthrough/"><u>How To Immediately Force Quit Stalled Window Software – A Step-by-Step Walkthrough</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/immediate-recovery-of-lost-snapshots/"><u>Immediate Recovery of Lost Snapshots</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-iphone-x-could-not-be-activatedreached-issue-by-drfone-ios/"><u>In 2024, How To Fix iPhone X Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-kinemaster-app-for-android-complete-review-2023/"><u>In 2024, KineMaster App for Android - Complete Review 2023</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snapchat-story-crafting-harness-over-a-hundred-ideas-for-your-unique-narrative/"><u>In 2024, Snapchat Story Crafting  Harness over a Hundred Ideas for Your Unique Narrative</u></a></li>
<li><a href="https://win-forum.techidaily.com/in-depth-guide-installing-initializing-and-using-the-revo-uninstaller-application-efficiently/"><u>In-Depth Guide: Installing, Initializing, and Using The Revo Uninstaller Application Efficiently</u></a></li>
<li><a href="https://win-forum.techidaily.com/professional-grade-program-elimination-with-revo-uninstaller-pro-latest-update/"><u>Professional-Grade Program Elimination with Revo Uninstaller Pro - Latest Update!</u></a></li>
<li><a href="https://win-forum.techidaily.com/protect-your-device-from-malware-spotting-dangerous-apps-on-android-via-revouninstaller/"><u>Protect Your Device From Malware: Spotting Dangerous Apps on Android via RevoUninstaller</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-installation-guide-obtain-latest-hp-drivers-today/"><u>Quick Installation Guide: Obtain Latest HP Drivers Today</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/secrets-to-selecting-the-best-online-game-coverage-for-2024/"><u>Secrets to Selecting the Best Online Game Coverage for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-your-documents-a-step-by-step-guide-on-text-file-encryption-and-password-security/"><u>Secure Your Documents: A Step-by-Step Guide on Text File Encryption & Password Security</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-staples-decoded-exploring-facebook-twitter-instagram-and-youtube/"><u>Social Media Staples Decoded: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-windows-11s-full-hard-drive-conundrum-essential-fixes-for-stable-operation/"><u>Solving Windows 11'S Full Hard Drive Conundrum: Essential Fixes for Stable Operation</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-leading-social-media-sites-facebook-twitter-instagram-and-youtube-explained/"><u>The Leading Social Media Sites: Facebook, Twitter, Instagram & Youtube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-social-networking-sites-facebook-twitter-instagram-youtube/"><u>Top Four Social Networking Sites: Facebook | Twitter | Instagram | YouTube</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-vivo-y36i-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the Vivo Y36i password or pattern lock</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-the-secrets-of-the-windows-registry-tips-for-efficient-management/"><u>Unveiling the Secrets of The Windows Registry: Tips for Efficient Management</u></a></li>
</ul></div>
