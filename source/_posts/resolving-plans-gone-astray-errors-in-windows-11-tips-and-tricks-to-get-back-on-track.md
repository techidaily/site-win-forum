---
title: Resolving 'Plans Gone Astray' Errors in Windows 11 - Tips and Tricks to Get Back on Track
date: 2024-08-18T10:59:50.073Z
updated: 2024-08-19T10:59:50.073Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Resolving 'Plans Gone Astray' Errors in Windows 11 - Tips and Tricks to Get Back on Track
excerpt: This Article Describes Resolving 'Plans Gone Astray' Errors in Windows 11 - Tips and Tricks to Get Back on Track
thumbnail: https://thmb.techidaily.com/7e377b50c4e513bd18b3a4caf17d4fa401f54e28db3371c8a6654c909a09f9e7.png
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://article-helps.techidaily.com/new-essential-manual-for-crafting-perfect-podcast-titles-and-50plus-inspirations/"><u>[New] Essential Manual for Crafting Perfect Podcast Titles & 50+ Inspirations</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-top-pick-screen-capture-tools-for-apple-devices/"><u>[New] In 2024, Top Pick  Screen Capture Tools for Apple Devices</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-mastering-reddit-posts-a-stepwise-strategy-for-engagement/"><u>[New] Mastering Reddit Posts  A Stepwise Strategy for Engagement</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-premier-playwrighting-for-public-broadcast/"><u>[New] Premier Playwrighting for Public Broadcast</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-best-way-to-use-obs-live-stream-to-facebook/"><u>[New] The Best Way to Use OBS Live Stream to Facebook</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fundamentals-of-crafting-engaging-stories/"><u>[Updated] Fundamentals of Crafting Engaging Stories</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-5-must-do-things-before-tiktok-usage-on-macos/"><u>[Updated] In 2024, 5 Must-Do Things Before TikTok Usage on macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-from-basic-to-breakthrough-elevating-your-zoom-livestream-game/"><u>[Updated] In 2024, From Basic to Breakthrough  Elevating Your Zoom Livestream Game</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-must-get-external-hard-drives-for-xbox-enthusiasts/"><u>[Updated] Must-Get External Hard Drives for Xbox Enthusiasts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-screen-streaming-showdown-go-obs-vs-shadowtoolkit/"><u>[Updated] Screen Streaming Showdown  Go OBS! Vs ShadowToolkit</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/best-free-resources-to-master-a-new-language/"><u>Best Free Resources to Master a New Language</u></a></li>
<li><a href="https://win-forum.techidaily.com/boosting-your-windows-11-startup-top-tips-for-faster-booting/"><u>Boosting Your Windows 11 Startup: Top Tips for Faster Booting</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparing-giants-in-the-digital-world-twitter-instagram-facebook-and-youtube/"><u>Comparing Giants in the Digital World: Twitter, Instagram, Facebook and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-walkthrough-on-installing-and-running-revos-application-manager/"><u>Complete Walkthrough on Installing and Running Revo's Application Manager</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-troubleshooting-tactics-for-high-disk-usage-on-windows-11/"><u>Comprehensive Troubleshooting Tactics for High Disk Usage on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-activating-revos-permission-manager-feature-via-revouninstaller/"><u>Comprehensive Tutorial on Activating Revo's Permission Manager Feature via RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-with-the-world-via-major-platforms-discover-facebook-twitter-instagram-and-youtube/"><u>Connect with the World via Major Platforms - Discover Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915317930-discover-the-giants-of-social-networking-exploring-facebook-twitter-instagram-and-youtube/"><u>Discover the Giants of Social Networking: Exploring Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/enabling-wake-on-lan-feature-on-windows-11-a-step-by-step-guide/"><u>Enabling Wake-on-LAN Feature on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/examining-the-lenovo-130s-a-user-friendly-laptop-despite-its-constrained-power-capacity/"><u>Examining the Lenovo 130S: A User-Friendly Laptop Despite Its Constrained Power Capacity</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-key-online-communities-insights-into-facebook-twitter-instagram-and-youtube-usage/"><u>Exploring Key Online Communities: Insights Into Facebook, Twitter, Instagram & YouTube Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-misses-out-on-sd-card-heres-fixing-it/"><u>File Explorer Misses Out on SD Card - Here's Fixing It</u></a></li>
<li><a href="https://win-forum.techidaily.com/five-essential-steps-to-protect-your-microsoft-windows-machine/"><u>Five Essential Steps to Protect Your Microsoft Windows Machine</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723006145462-fix-your-fortnite-login-issues-fast-expert-solutions/"><u>Fix Your Fortnite Login Issues Fast: Expert Solutions!</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-reboot-your-network-connection-by-flushing-dns-in-windows-10-and-11/"><u>How to Reboot Your Network Connection by Flushing DNS in Windows 10 and 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-system-of-iphone-15-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair System of iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-gmail-password-on-nokia-c02-devices-by-drfone-android/"><u>How to Reset Gmail Password on Nokia C02 Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-securely-shutdown-your-pc-mastering-windows-protection-techniques/"><u>How to Securely Shutdown Your PC - Mastering Window's Protection Techniques</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-wipe-out-tracking-data-on-your-pc-windows-10-and-smartphone-android/"><u>How to Wipe Out Tracking Data on Your PC (Windows 10) and Smartphone (Android)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-vivo-v30-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Vivo V30 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Use Special Features - Virtual Location On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlocking-the-top-5-virtual-title-designers/"><u>In 2024, Unlocking the Top 5 Virtual Title Designers</u></a></li>
<li><a href="https://win-forum.techidaily.com/in-depth-strategies-for-managing-system-registry-editing-deletion-and-key-creation-in-revo-uninstaller/"><u>In-Depth Strategies for Managing System Registry: Editing, Deletion & Key Creation in Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-technique-eliminating-unregistered-class-error-on-windows-with-proven-strategies/"><u>Master the Technique: Eliminating 'Unregistered Class' Error on Windows with Proven Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximize-your-storage-on-windows-11-with-easy-deletion-tips-and-tricks/"><u>Maximize Your Storage on Windows 11 with Easy Deletion Tips and Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915403847-navigating-the-giants-of-social-networking-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Networking: Insights on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-titans-of-online-engagement-facebook-twitter-instagram-and-youtube/"><u>Navigating the Titans of Online Engagement: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-popular-networks-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating Through Popular Networks: A Look at Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://facebook.techidaily.com/new-era-begins-fbs-ad-chief-quits/"><u>New Era Begins: FB's Ad Chief Quits</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-s-top-avchd-video-editing-tools-a-comprehensive-review-for-2024/"><u>New S Top AVCHD Video Editing Tools A Comprehensive Review for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-tutorial-deleting-files-and-directories-via-command-line-in-windows-10/"><u>Quick Tutorial: Deleting Files and Directories via Command Line in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-the-windows-11-cant-start-issue-a-step-by-step-guide/"><u>Resolving the 'Windows 11 Can't Start' Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-samsung-galaxy-z-flip-5-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Samsung Galaxy Z Flip 5 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-the-access-denied-issue-on-windows-pcs-with-ease/"><u>Solving the 'Access Denied' Issue on Windows PCs with Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/steps-to-successfully-get-windows-11-running-after-wont-run-errors/"><u>Steps to Successfully Get Windows 11 Running After 'Wont Run' Errors</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-titans-a-comprehensive-guide-to-facebook-twitter-instagram-and-youtube/"><u>The Digital Titans: A Comprehensive Guide to Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-gamers-tools-premium-gear-lists-on-youtube-for-2024/"><u>Top Gamers' Tools  Premium Gear Lists on YouTube for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-tips-for-overcoming-windows-11-installation-hiccups-on-personal-computers/"><u>Troubleshooting Tips for Overcoming Windows 11 Installation Hiccups on Personal Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915311245-ultimate-fix-guide-for-recurrently-failing-windows-explorer-discover-our-top-7-hacks/"><u>Ultimate Fix Guide for Recurrently Failing Windows Explorer - Discover Our Top 7 Hacks!</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-managing-registry-keys-with-ease-deleting-and-creating-using-revo-uninstaller/"><u>Ultimate Guide: Managing Registry Keys with Ease – Deleting & Creating Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-the-powerhouses-of-digital-interaction-insights-into-facebook-twitter-instagram-youtube/"><u>Unveiling the Powerhouses of Digital Interaction: Insights Into Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-top-8-android-audio-workstations-elevating-your-music-creation/"><u>Updated Top 8 Android Audio Workstations Elevating Your Music Creation</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-hacks-overcoming-processor-incompatibilities-for-a-smooth-setup-and-use/"><u>Windows 11 Hacks: Overcoming Processor Incompatibilities for a Smooth Setup and Use</u></a></li>
</ul></div>
