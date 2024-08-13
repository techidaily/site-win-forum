---
title: "Breaking the Rules: Unsupported CPU Compatibility with Windows 11 Installation Explained"
date: 2024-08-12T04:57:08.696Z
updated: 2024-08-13T04:57:08.696Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Breaking the Rules: Unsupported CPU Compatibility with Windows 11 Installation Explained"
excerpt: "This Article Describes Breaking the Rules: Unsupported CPU Compatibility with Windows 11 Installation Explained"
thumbnail: https://thmb.techidaily.com/102c7cf0ada16d45d73aab06a0df3c1b4bd516c1e4675a811bb1bd88b724571c.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![windows 11 setup](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/windows-11-setup.jpg)

 Luckily, if your PC does not have the TPM2.0 chip there is still a way to take advantage of Windows 11 and its features.

 Note: If you use this method, Microsoft reserves the right to deny updates on your OS.

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guide-to-consolidating-your-youtube-video-collection/"><u>[New] 2024 Approved  Guide to Consolidating Your YouTube Video Collection</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fix-webview-issues-for-fb-videos-in-chrome-for-2024/"><u>[New] Fix WebView Issues for FB Videos in Chrome for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-tips-for-creating-a-viral-buzz-on-facebook-that-you-should-know/"><u>[New] In 2024, Tips for Creating a Viral Buzz on Facebook that You Should Know</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-snap-into-fb-shorts-saga/"><u>[New] Snap Into FB Shorts Saga</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-easy-screenshot-methods-for-mac-users/"><u>[Updated] 2024 Approved  Easy Screenshot Methods for Mac Users</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-follower-drones-reviewed-best-of-the-best/"><u>[Updated] 2024 Approved  Follower Drones Reviewed  Best of the Best</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-catchy-tracks-the-20-top-rapping-beats-you-cant-miss-on-tiktok/"><u>[Updated] In 2024, Catchy Tracks  The 20 Top Rapping Beats You Can't Miss on TikTok</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-simplifying-tiktok-video-sharing-for-twitter-for-2024/"><u>[Updated] Simplifying TikTok Video Sharing for Twitter for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-at-the-helm-of-augmented-perception-tools/"><u>2024 Approved  At the Helm of Augmented Perception Tools</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-discover-the-5-best-android-photo-editors-for-enhanced-images/"><u>2024 Approved  Discover the 5 Best Android Photo Editors for Enhanced Images</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-how-to-create-and-edit-videos-on-windows-11/"><u>2024 Approved  How to Create and Edit Videos on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-essential-guide-from-twitter-videos-to-high-quality-mp3-soundtracks/"><u>2024 Approved  The Essential Guide  From Twitter Videos to High-Quality MP3 Soundtracks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transforming-video-quality-from-sdr-to-stunning-hdr-a-practical-handbook/"><u>2024 Approved  Transforming Video Quality From SDR to Stunning HDR - A Practical Handbook</u></a></li>
<li><a href="https://win-forum.techidaily.com/banish-windows-explorer-malfunctions-for-good-discover-our-7-fixes-using-revouninstaller/"><u>Banish Windows Explorer Malfunctions for Good - Discover Our 7 Fixes Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/clear-clutter-effective-ways-to-expand-your-storage-on-windows-11/"><u>Clear Clutter: Effective Ways to Expand Your Storage on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-deleting-unwanted-folders-in-windows-1011-with-revo-uninstaller/"><u>Complete Guide: Deleting Unwanted Folders in Windows 10/11 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-through-giants-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Connecting Through Giants: A Guide to Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-worldwide-the-powerhouses-of-social-media-facebook-twitter-instagram-and-youtube/"><u>Connecting Worldwide: The Powerhouses of Social Media - Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/delete-filesfolders-efficiently-using-windows-11s-command-line-tools/"><u>Delete Files/Folders Efficiently Using Windows 11'S Command Line Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915376131-digital-connectivity-essentials-mastering-facebook-twitter-instagram-and-youtube/"><u>Digital Connectivity Essentials: Mastering Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/enhance-your-pcs-startup-speed-effective-solutions-for-windows-11-efficiency/"><u>Enhance Your PC's Startup Speed: Effective Solutions for Windows 11 Efficiency</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-tactics-for-effective-handc-facebook-promos/"><u>Essential Tactics for Effective H&C Facebook Promos</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-popular-online-communities-facebook-instagram-and-more/"><u>Explore Popular Online Communities: Facebook, Instagram, and More</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-the-world-of-connectivity-with-facebook-twitter-instagram-and-youtube/"><u>Explore the World of Connectivity with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-popular-networking-sites-a-comparison-of-facebook-twitter-instagram-and-youtube/"><u>Exploring Popular Networking Sites: A Comparison of Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-popular-online-communities-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Exploring Popular Online Communities: A Deep Dive Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-social-networks-strategies-for-success-on-facebook-twitter-instagram-and-youtube/"><u>Exploring Social Networks: Strategies for Success on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/finding-the-right-powershell-version-for-windows-10-using-command-prompt-or-powershell/"><u>Finding the Right PowerShell Version for Windows 10 Using Command Prompt or Powershell</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-windows-11-wont-run-problems-expert-strategies-and-solutions/"><u>Fixing 'Windows 11 Wont Run' Problems: Expert Strategies and Solutions</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-enhanced-privacy-5-techniques-for-locking-down-your-windows-system/"><u>Guide to Enhanced Privacy: 5 Techniques for Locking Down Your Windows System</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-successfully-setting-up-windows-11-on-non-compatible-processors/"><u>Guide: Successfully Setting Up Windows 11 on Non-Compatible Processors</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-manually-delete-blue-screen-error-dumps-from-your-windows-10-pc/"><u>How to Manually Delete Blue Screen Error Dumps From Your Windows 10 PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-iphone-13-mini-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even On iPhone 13 mini If Youve Tried Everything</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-how-to-make-your-facebook-profile-cover-video-more-attractive/"><u>In 2024, How to Make Your Facebook Profile Cover Video More Attractive</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-13t-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi 13T Phone FRP Lock</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-potential-top-tactics-for-medical-ads-on-social-networks/"><u>In 2024, Unlocking Potential  Top Tactics for Medical Ads on Social Networks</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-power-management-configuring-wake-on-lan-on-windows-11-systems/"><u>Mastering Power Management: Configuring Wake-on-LAN on Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-engagement-across-facebook-twitter-instagram-and-youtube-channels/"><u>Mastering Social Media Engagement Across Facebook, Twitter, Instagram & YouTube Channels</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-force-quitting-essential-techniques-for-windows-software-using-revouninstaller/"><u>Mastering the Art of Force Quitting: Essential Techniques for Windows Software Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-social-media-giants-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Mastering the Social Media Giants: A Deep Dive Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-uninstallation-getting-rid-of-non-controlled-system-apps/"><u>Mastering Uninstallation: Getting Rid of Non-Controlled System Apps</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/most-reliable-free-online-tools-for-tiktok-video-to-mp3-downloads-for-2024/"><u>Most Reliable Free Online Tools for TikTok Video to MP3 Downloads for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-social-networking-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Four of Social Networking: Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-media-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Media: Insights on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcome-deletion-hurdles-forcing-out-stubborn-folders-from-windows-10-and-11/"><u>Overcome Deletion Hurdles: Forcing Out Stubborn Folders From Windows 10 & 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/podcast-perfection-elite-webcam-selection-guide-for-2024/"><u>Podcast Perfection  Elite Webcam Selection Guide for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/remedying-stuck-print-head/"><u>Remedying Stuck Print Head</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-fixes-for-starcraft-ii-game-crashes-on-windows-computers/"><u>Resolved: Fixes for StarCraft II Game Crashes on Windows Computers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-color-correction-top-15-luts-for-gopro-cams/"><u>Ultimate Color Correction  Top 15 LUTs for GoPro Cams</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-power-of-chatgpts-api-capabilities/"><u>Unveiling the Power of ChatGPT's API Capabilities</u></a></li>
</ul></div>
