---
title: "Troubleshooting: Steps to Discard a Windows 11 Software Upgrade"
date: 2024-08-18T10:22:29.661Z
updated: 2024-08-19T10:22:29.661Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Troubleshooting: Steps to Discard a Windows 11 Software Upgrade"
excerpt: "This Article Describes Troubleshooting: Steps to Discard a Windows 11 Software Upgrade"
thumbnail: https://thmb.techidaily.com/202879ef7f02a179959dd0c2fa2c18e23fdc8822666d6240110addaa046f6e87.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![windows 11 setup](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/windows-11-setup.jpg)

 Luckily, if your PC does not have the TPM2.0 chip there is still a way to take advantage of Windows 11 and its features.

 Note: If you use this method, Microsoft reserves the right to deny updates on your OS.

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-ultimate-guide-top-10-cameras-in-the-new-os/"><u>[New] 2024 Approved  Ultimate Guide  Top 10 Cameras in the New OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-exclusive-online-cam-dance-duels/"><u>[New] Exclusive Online Cam Dance Duels</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flash-forward-quick-youtube-playlists-distribution/"><u>[New] In 2024, Flash Forward  Quick Youtube Playlists Distribution</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-picsart-background-removal-tool-a-step-by-step-guide/"><u>[New] Picsart Background Removal Tool  A Step-By-Step Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-sound-seekers-sanctuary-download-and-listen-to-songs-for-2024/"><u>[New] Sound Seeker's Sanctuary  Download & Listen To Songs for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-step-by-step-process-for-free-youtube-educational-events/"><u>[Updated] 2024 Approved  Step-by-Step Process for Free Youtube Educational Events</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-effortless-twitpic-integration-a-video-guide-for-2024/"><u>[Updated] Effortless Twitpic Integration  A Video Guide for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-the-ultimate-guide-to-non-xbox-screen-recording-software/"><u>[Updated] The Ultimate Guide to Non-Xbox Screen Recording Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-oppo-k11x-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Oppo K11x Activity | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/boost-your-systems-speed-on-windows-11-a-guide-to-free-up-disk-space/"><u>Boost Your System's Speed on Windows 11: A Guide to Free Up Disk Space</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-in-the-modern-age-a-deep-dive-into-facebook-twitter-instagram-and-youtube-strategies/"><u>Connecting in the Modern Age: A Deep Dive Into Facebook, Twitter, Instagram, and YouTube Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-platforms-in-digital-age-facebook-twitter-instagram-and-youtube/"><u>Essential Platforms in Digital Age - Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-social-networking-sites-facebook-twitter-instagram-and-youtube/"><u>Essential Social Networking Sites - Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/fix-the-windows-1n-wont-run-problem-top-tricks-for-seamless-boot-up/"><u>Fix the Windows 1N Wont Run Problem: Top Tricks for Seamless Boot-Up</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-permanently-running-any-application-with-administrator-privileges-in-windows-11/"><u>Guide: Permanently Running Any Application with Administrator Privileges in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-discover-the-powershell-release-running-under-windows-a-detailed-guide/"><u>How to Discover the PowerShell Release Running Under Windows #: A Detailed Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-perform-factory-reset-windows-11-revo-uninstaller-pro-4/"><u>How to Perform Factory Reset Windows 11 - Revo Uninstaller Pro 4</u></a></li>
<li><a href="https://extra-support.techidaily.com/iphones-best-5-podcast-audio-platforms-for-2024/"><u>IPhone's Best 5 Podcast Audio Platforms for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/keep-your-pc-running-smoothly-on-windows-11-with-fresh-drivers/"><u>Keep Your PC Running Smoothly on Windows 11 with Fresh Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-interaction-across-major-platforms-tips-for-facebook-twitter-instagram-and-youtube-success/"><u>Mastering Interaction Across Major Platforms: Tips for Facebook, Twitter, Instagram, and YouTube Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-pc-energy-saving-enabling-wake-on-wireless-lan-in-win10-and-win11-platforms/"><u>Mastering PC Energy Saving: Enabling Wake on Wireless LAN in Win10 & Win11 Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/meet-the-enhanced-revo-uninstaller-pro-5-the-ultimate-cleanup-tool/"><u>Meet the Enhanced Revo Uninstaller Pro 5: The Ultimate Cleanup Tool</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915215998-navigating-the-digital-landscape-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape: A Guide to Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-media-facebook-twitter-instagram-youtube/"><u>Navigating the Giants of Social Media: Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-social-media-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Social Media: A Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-what-to-use-instead-of-virtualdub-best-video-editing-tools/"><u>New In 2024, What to Use Instead of VirtualDub Best Video Editing Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstaller-guide-mastering-android-11s-one-time-app-permissions/"><u>RevoUninstaller Guide: Mastering Android 11'S One-Time App Permissions</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstaller-masterclass-fresh-driver-update-tutorials-for-windows-11-devices/"><u>RevoUninstaller Masterclass: Fresh Driver Update Tutorials for Windows 11 Devices</u></a></li>
<li><a href="https://video-capture.techidaily.com/screenshot-expert-evaluator/"><u>ScreenShot Expert Evaluator</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-the-mystery-of-invisible-program-removal-on-windows-systems/"><u>Solving the Mystery of Invisible Program Removal on Windows Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-permanently-deleting-tough-folders-in-win-1011-using-third-party-tools/"><u>Step-by-Step Instructions: Permanently Deleting Tough Folders in Win 10/11 Using Third-Party Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essential-guide-to-major-social-media-giants-fbtwitterigyt/"><u>The Essential Guide to Major Social Media Giants: Fb/Twitter/IG/Yt</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essentials-of-system-startup-bios-explained-and-role-of-revouninstaller/"><u>The Essentials of System Startup: BIOS Explained & Role of RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouse-titans-of-digital-communication-facebook-twitter-instagram-and-youtube/"><u>The Powerhouse Titans of Digital Communication: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-guide-to-popular-networking-sites-fb-tw-ig-yt/"><u>The Quintessential Guide to Popular Networking Sites: FB, TW, IG, YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-social-media-overview-understanding-facebook-twitter-instagram-and-youtube-trends/"><u>The Ultimate Social Media Overview: Understanding Facebook, Twitter, Instagram & YouTube Trends</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-to-update-device-drivers-on-windows-10-with-revo-uninstaller/"><u>The Ultimate Walkthrough to Update Device Drivers on Windows 10 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-platforms-in-social-networking-exploring-facebook-twitter-instagram-and-youtube/"><u>Top Platforms in Social Networking - Exploring Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-media-platforms-facebook-twitter-and-instagram-youtube-guide/"><u>Top Social Media Platforms: Facebook, Twitter & Instagram | YouTube Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-methods-for-when-an-app-wont-start-on-windows/"><u>Troubleshooting Methods for When an App Won't Start on Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-tutorial-to-delete-items-using-windows-10s-command-prompt/"><u>Ultimate Tutorial to Delete Items Using Windows 10'S Command Prompt</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-walkthrough-mastering-the-art-of-windows-11-system-refresh-using-advanced-tools/"><u>Ultimate Walkthrough: Mastering the Art of Windows 11 System Refresh Using Advanced Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-bios-a-comprehensive-guide-with-revo-uninstaller/"><u>Understanding BIOS: A Comprehensive Guide with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-system-restore-in-windows-10-a-complete-guide/"><u>Understanding System Restore in Windows 10: A Complete Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-potential-of-remote-booting-activating-wake-on-lan-in-windows-11/"><u>Unlock the Potential of Remote Booting: Activating Wake-on-LAN in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-tips-quick-ways-to-gain-more-free-drive-space/"><u>Windows 11 Tips: Quick Ways to Gain More Free Drive Space</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-defense-tactics-discover-5-proven-ways-to-lock-down-your-pc/"><u>Windows Defense Tactics: Discover 5 Proven Ways to Lock Down Your PC</u></a></li>
</ul></div>
