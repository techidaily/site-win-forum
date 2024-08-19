---
title: "Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
date: 2024-08-18T10:48:51.449Z
updated: 2024-08-19T10:48:51.449Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
excerpt: "This Article Describes Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
thumbnail: https://thmb.techidaily.com/d021ea19d35ef3673abfe0bc9bdff457eb34791e55514d7bc0ce5bafaca00aee.jpg
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
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-effective-storytelling-through-youtube-and-facebook/"><u>[New] In 2024, Effective Storytelling Through YouTube and Facebook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-secure-your-contents-identity-adding-logo-and-watermark-to-videos/"><u>[Updated] Secure Your Content's Identity  Adding Logo and Watermark to Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-enhance-branding-the-ultimate-guide-to-custom-urls-for-youtube/"><u>2024 Approved  Enhance Branding  The Ultimate Guide to Custom URLs for YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-unlocking-creative-potential-with-new-iphone-x-camera/"><u>2024 Approved  Unlocking Creative Potential with New iPhone X Camera</u></a></li>
<li><a href="https://win-forum.techidaily.com/clearing-out-windows-11-user-profiles-with-the-help-of-revos-powerful-tools/"><u>Clearing Out Windows 11 User Profiles with the Help of Revo's Powerful Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-on-major-online-channels-facebook-twitter-instagram-and-youtube-unveiled/"><u>Connect on Major Online Channels - Facebook, Twitter, Instagram and YouTube Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-through-social-media-an-insight-into-facebook-twitter-instagram-and-youtube/"><u>Connecting the World Through Social Media: An Insight Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/daily-diary-downloader-for-2024/"><u>Daily Diary Downloader for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/decoding-the-leaders-of-online-networking-an-insightful-study-on-facebook-twitter-instagram-and-youtube/"><u>Decoding the Leaders of Online Networking: An Insightful Study on Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discovering-your-windows-10-powershell-verison-a-step-by-step-guide/"><u>Discovering Your Windows 10 PowerShell Verison: A Step-by-Step Guide</u></a></li>
<li><a href="https://video-capture.techidaily.com/easy-screen-capture-in-vlc-player/"><u>Easy Screen Capture in VLC Player</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-techniques-to-reset-dns-settings-for-windows-10-and-11-users/"><u>Effective Techniques to Reset DNS Settings for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficient-methods-for-keeping-your-windows-10-hardware-compatible-with-updated-drivers/"><u>Efficient Methods for Keeping Your Windows 10 Hardware Compatible with Updated Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-in-digital-conversations-across-facebook-twitter-instagram-and-youtube-platforms/"><u>Engage in Digital Conversations Across Facebook, Twitter, Instagram & Youtube Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-with-giants-of-social-media-explore-fb-twitternest-and-youtube-galaxy-ig-surfing/"><u>Engage with Giants of Social Media – Explore FB, Twitternest & YouTube Galaxy | IG Surfing</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915261007-exploring-leading-platforms-connect-on-facebook-tweet-on-twitter-share-with-instagram-and-stream-with-youtube/"><u>Exploring Leading Platforms: Connect on Facebook, Tweet on Twitter, Share with Instagram and Stream with Youtube!</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-giants-of-social-media-facebook-twitter-and-instagram/"><u>Exploring the Giants of Social Media: Facebook, Twitter & Instagram</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-problems-with-the-ar-capabilities-on-newer-iphones/"><u>Fixing Problems with the AR Capabilities on Newer iPhones</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-keep-your-windows-11-devices-running-smoothly-by-updating-drivers-with-revouninstaller/"><u>How to Keep Your Windows 11 Devices Running Smoothly by Updating Drivers with RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-permanently-and-unrecoverably-delete-files-windows-11/"><u>How to Permanently and Unrecoverably Delete Files - Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-13-pro-max-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 13 Pro Max iOS System? | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-double-location-dongle-all-to-know-about-apple-iphone-se-2020ipad-gps-spoofing-drfone-by-drfone-virtual-ios/"><u>In 2024, Double Location Dongle All to Know About Apple iPhone SE (2020)/iPad GPS Spoofing | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-poco-c55-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Poco C55 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/masterclass-in-choosing-your-best-live-streamer/"><u>Masterclass in Choosing Your Best Live Streamer</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-factory-restoration-in-windows-11-with-revo-uninstaller-pro-tips/"><u>Mastering the Art of Factory Restoration in Windows 11 with Revo Uninstaller Pro Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-user-privileges-permanent-admin-launch-of-programs-in-windows-11/"><u>Mastering User Privileges: Permanent Admin Launch of Programs in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915368052-navigating-the-giants-of-online-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Online Networking: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/premium-podcasters-at-universities-for-2024/"><u>Premium Podcasters at Universities for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstaller-explained-a-deep-dive-into-computer-boot-settings/"><u>RevoUninstaller Explained: A Deep Dive Into Computer Boot Settings</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-showdown-how-facebook-twitter-instagram-stack-up-against-youtube/"><u>Social Media Showdown: How Facebook, Twitter, Instagram Stack Up Against YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-out-memory-dump-files-on-windows-10/"><u>Step-by-Step Guide: Clearing Out Memory Dump Files on Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-your-dns-cache-on-windows-10-and-11/"><u>Step-by-Step Guide: Clearing Your DNS Cache on Windows 10 & 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-your-account-from-windows-10-using-revo-uninstaller/"><u>Step-by-Step Guide: Removing Your Account From Windows 10 Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-solving-the-failed-to-execute-plan-message-in-windows-11/"><u>Step-by-Step Guide: Solving the 'Failed To Execute Plan' Message in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-on-activating-wake-on-lan-for-latest-windows-versions/"><u>Step-by-Step Tutorial on Activating Wake-on-LAN for Latest Windows Versions</u></a></li>
<li><a href="https://win-forum.techidaily.com/tackling-disk-overflow-a-comprehensive-fix-for-windows-10-storage-glitches/"><u>Tackling Disk Overflow: A Comprehensive Fix for Windows 10 Storage Glitches</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-giants-how-facebook-twitter-instagram-and-youtube-shape-our-lives/"><u>The Digital Giants: How Facebook, Twitter, Instagram and YouTube Shape Our Lives</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-giants-navigating-through-facebook-twitter-instaconnect-and-videohub/"><u>The Digital Giants: Navigating Through Facebook, Twitter, InstaConnect, and VideoHub</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-ultimate-guide-to-choosing-a-budget-friendly-sturdy-tablet-support-unpacking-the-omoton-t-1-review/"><u>The Ultimate Guide to Choosing a Budget-Friendly, Sturdy Tablet Support: Unpacking the Omoton T 1 Review</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-erasing-kernel-memory-leaks-in-windows-11/"><u>The Ultimate Guide to Erasing Kernel Memory Leaks in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-how-to-manual-rolling-back-updates-on-your-pc-with-windows-10-or-11-using-revosofts-tool/"><u>The Ultimate How-To Manual: Rolling Back Updates on Your PC with Windows 10 or 11 Using RevoSoft's Tool</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-solution-for-stubborn-folder-removal-on-windows-10-and-11-revouninstaller-methods/"><u>The Ultimate Solution for Stubborn Folder Removal on Windows 10 and 11 - RevoUninstaller Methods</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-for-wiping-data-with-windows-11s-command-line-utility/"><u>The Ultimate Walkthrough for Wiping Data with Windows 11'S Command Line Utility</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-platforms-dominating-digital-conversations-fb-tw-inst-yt/"><u>Top Four Platforms Dominating Digital Conversations: FB, TW, INST, YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-full-potential-always-launch-apps-with-admin-rights-on-windows-11-explained/"><u>Unlocking Full Potential: Always Launch Apps with Admin Rights on Windows 11 Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-driver-update-solutions-how-to-ensure-peak-performance-for-your-hardware/"><u>Windows 11 Driver Update Solutions: How to Ensure Peak Performance for Your Hardware</u></a></li>
</ul></div>
