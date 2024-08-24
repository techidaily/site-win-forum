---
title: Troubleshooting Unexpected Issues in Windows 11 Operating System
date: 2024-08-23T11:00:43.953Z
updated: 2024-08-24T11:00:43.953Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Troubleshooting Unexpected Issues in Windows 11 Operating System
excerpt: This Article Describes Troubleshooting Unexpected Issues in Windows 11 Operating System
thumbnail: https://thmb.techidaily.com/5eac549bf0074d54dd4b3414ac1cd5ccda2e57524c605d3807bb2415d6b1435a.jpg
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

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastering-the-art-of-uploading-youtube-videos-on-fb/"><u>[New] 2024 Approved  Mastering the Art of Uploading YouTube Videos on FB</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/fficiently-convert-youtube-to-desktop-format-for-2024/"><u>[New] Efficiently Convert YouTube to Desktop Format for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-comprehensive-guide-to-viewing-facebook-videos-on-apple-tv-devices/"><u>[New] In 2024, Comprehensive Guide to Viewing Facebook Videos on Apple TV Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-expertly-navigate-the-cloud-of-content-with-best-screen-recording-tools/"><u>[New] In 2024, Expertly Navigate the Cloud of Content with Best Screen Recording Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-twist-and-tell-the-art-of-angling-your-videos-for-instagram-audiences/"><u>[New] Twist & Tell  The Art of Angling Your Videos for Instagram Audiences</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-androids-video-recording-techniques-explored/"><u>[Updated] 2024 Approved  Android's Video Recording Techniques Explored</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhance-editing-unlimited-free-audio-samples/"><u>[Updated] 2024 Approved  Enhance Editing  Unlimited Free Audio Samples</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-unleashing-your-cellphones-potential-in-videography/"><u>[Updated] 2024 Approved  Unleashing Your Cellphone's Potential in Videography</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-convert-avi-videos-into-high-impact-gifs-using-filmora-for-windowsmacos/"><u>[Updated] Convert AVI Videos Into High Impact GIFs Using Filmora for Windows/MacOS</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-how-to-mergecombinejoin-youtube-flv-videos/"><u>[Updated] How to Merge/Combine/Join YouTube (FLV) Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-aerial-footage-a-guide-to-drone-video-editing/"><u>[Updated] Mastering Aerial Footage  A Guide to Drone Video Editing</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-best-way-to-use-obs-live-stream-to-facebook/"><u>[Updated] The Best Way to Use OBS Live Stream to Facebook</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-chuckle-creator-app/"><u>2024 Approved  Chuckle Creator App</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-beginners-guide-to-basic-inputoutput-systems-unlocking-your-pcs-core-operations/"><u>A Beginner's Guide to Basic Input/Output Systems: Unlocking Your PC's Core Operations</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-samsung-galaxy-a24-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Samsung Galaxy A24</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-to-forcibly-removing-directories-on-windows-11-a-step-by-step-process/"><u>Complete Guide to Forcibly Removing Directories on Windows 11: A Step-by-Step Process</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-instructions-how-to-undo-the-most-recent-windows-11-installation-changes/"><u>Comprehensive Instructions: How to Undo the Most Recent Windows 11 Installation Changes</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-with-the-world-dive-into-facebook-twitter-instagram-and-youtube/"><u>Connect with the World: Dive Into Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-with-billions-a-guide-to-using-facebook-twitter-instagram-and-youtube/"><u>Connecting with Billions: A Guide to Using Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/core-concepts-of-story-making/"><u>Core Concepts of Story Making</u></a></li>
<li><a href="https://win-forum.techidaily.com/defeat-the-dying-light-lag-demon-expert-tips-and-techniques/"><u>Defeat the Dying Light Lag Demon – Expert Tips and Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/determining-your-current-powershell-verison-in-windows-10-a-step-by-step-guide/"><u>Determining Your Current PowerShell Verison in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/engaging-audiences-through-prominent-social-media-facey-tweets-gram-and-tube/"><u>Engaging Audiences Through Prominent Social Media - Facey, Tweets, Gram & Tube</u></a></li>
<li><a href="https://win-forum.techidaily.com/enhance-your-computers-compatibility-with-updated-windows-11-drivers/"><u>Enhance Your Computer's Compatibility with Updated Windows 11 Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-social-media-sites-for-engagement-exploring-facebook-twitter-instagram-and-youtube/"><u>Essential Social Media Sites for Engagement: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/fix-and-optimize-your-pc-a-comprehensive-guide-to-update-windows-11-drivers/"><u>Fix and Optimize Your PC: A Comprehensive Guide to Update Windows 11 Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-issues-when-an-application-fails-to-launch-on-windows-systems/"><u>Fixing Issues When an Application Fails to Launch on Windows Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/framegauge-evaluator-suite/"><u>FrameGauge Evaluator Suite</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-delete-user-profile-in-windows-10-revouninstaller/"><u>How to Delete User Profile in Windows 10 - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-free-up-space-by-deleting-bloatware-on-windows-10-and-11-systems/"><u>How to Free Up Space by Deleting Bloatware on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-remove-tracking-cookies-on-windows-11-and-android-phone/"><u>How to Remove Tracking Cookies on Windows 11 and Android Phone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-successfully-remove-non-listed-programs-from-your-computers-system/"><u>How to Successfully Remove Non-Listed Programs From Your Computer's System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oneplus-nord-ce-3-lite-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from OnePlus Nord CE 3 Lite 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-beginning-profits-periscope-income-strategies-for-novices/"><u>In 2024, Beginning Profits  Periscope Income Strategies for Novices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-on-iphone-6s-by-drfone-ios/"><u>In 2024, How to Fix when Apple Account Locked On iPhone 6s?</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-unveiling-the-secrets-perfecting-motion-blur-in-photoshop/"><u>In 2024, Unveiling the Secrets  Perfecting Motion Blur in Photoshop</u></a></li>
<li><a href="https://hardware-help.techidaily.com/keep-your-pc-connected-download-updated-msi-bluetooth-drivers-for-windows-1110-today/"><u>Keep Your PC Connected: Download Updated MSI Bluetooth Drivers for Windows 11/10 Today</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mac-users-guide-to-retrieving-lost-iphone-memories-photo-and-video-restoration-app-with-contact-support/"><u>Mac Users' Guide to Retrieving Lost iPhone Memories: Photo and Video Restoration App with Contact Support</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-windows-11-cmd-a-comprehensive-tutorial-for-file-deletion/"><u>Navigating Windows 11 CMD: A Comprehensive Tutorial for File Deletion</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-your-idevice-how-to-download-episodes-with-swiftness/"><u>Navigating Your iDevice - How to Download Episodes with Swiftness</u></a></li>
<li><a href="https://win-forum.techidaily.com/preventing-and-resolving-persistent-freeze-issues-on-your-laptop-or-desktop/"><u>Preventing and Resolving Persistent Freeze Issues on Your Laptop or Desktop</u></a></li>
<li><a href="https://win-forum.techidaily.com/reset-your-internet-connection-dns-flushing-for-windows-users/"><u>Reset Your Internet Connection: DNS Flushing for Windows Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/revamp-your-computers-performance-by-learning-to-update-windows-10-device-drivers/"><u>Revamp Your Computer's Performance by Learning to Update Windows 10 Device Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstallers-techniques-to-forcibly-delete-stubborn-folders-on-your-windows-11-system/"><u>RevoUninstaller's Techniques to Forcibly Delete Stubborn Folders on Your Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-unveiled-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Social Media Giants Unveiled: A Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-networking-powerhouses-delving-into-facebook-twitter-instagram-and-youtube-features/"><u>Social Networking Powerhouses: Delving Into Facebook, Twitter, Instagram & YouTube Features</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-correcting-class-registration-errors-on-windows-systems/"><u>Step-by-Step Guide: Correcting Class Registration Errors on Windows Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-to-revitalize-the-audio-quality-of-your-home-speakers-with-proper-cleaning-techniques/"><u>Step-by-Step Instructions to Revitalize the Audio Quality of Your Home Speakers with Proper Cleaning Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-terminating-applications-that-wont-close-on-windows-11/"><u>Step-by-Step Tutorial: Terminating Applications That Won't Close on Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-leading-yoga-focused-fitness-youtube-channels-for-2024/"><u>The Leading Yoga-Focused Fitness YouTube Channels for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-for-undoing-windows-11s-latest-update/"><u>The Ultimate Walkthrough for Undoing Windows 11'S Latest Update</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-windows-registry-explained-how-it-affects-software-management/"><u>The Windows Registry Explained: How It Affects Software Management</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-social-networking-giants-facebook-twitter-instagram-and-youtube/"><u>Top Four Social Networking Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-full-disk-utilization-in-windows-10-a-step-by-step-tutorial/"><u>Troubleshooting Full Disk Utilization in Windows 10 - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-fixes-for-overcoming-your-pcs-app-compatibility-snags/"><u>Ultimate Fixes for Overcoming Your PC's App Compatibility Snags</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-system-restore-a-guide-for-windows-11-users/"><u>Understanding System Restore: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/what-is-windows-10-system-restore/"><u>What Is Windows 10 System Restore</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-users-learn-the-simple-way-to-enter-your-computers-bios/"><u>Windows 11 Users, Learn the Simple Way to Enter Your Computer's BIOS</u></a></li>
</ul></div>
