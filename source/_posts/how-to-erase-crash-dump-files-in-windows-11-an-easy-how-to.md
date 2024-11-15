---
title: "How to Erase Crash Dump Files in Windows 11: An Easy How-To"
date: 2024-11-12T04:49:17.199Z
updated: 2024-11-14T23:50:01.921Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes How to Erase Crash Dump Files in Windows 11: An Easy How-To"
excerpt: "This Article Describes How to Erase Crash Dump Files in Windows 11: An Easy How-To"
thumbnail: https://thmb.techidaily.com/9caf09d90581e3a94b158683bfe9026f493c02c1c7b54e4b375ff8955952a5c3.jpg
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
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
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
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-efficient-way-to-broadcast-tiktok-videos-via-facebook-for-2024/"><u>[New] Efficient Way to Broadcast TikTok Videos via Facebook for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-metadata-title-and-description-for-youtube-traction/"><u>[New] Mastering Metadata Title and Description for YouTube Traction</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-decoding-igtv-video-statistics-for-better-insights/"><u>2024 Approved Decoding IGTV Video Statistics for Better Insights</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-navigating-the-world-of-gopro-and-time-lapse-shooting/"><u>2024 Approved Navigating the World of GoPro and Time-Lapse Shooting</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/alternatives-to-xboxs-game-bar-for-gamers/"><u>Alternatives to Xbox’s Game Bar for Gamers</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-titans-of-social-networking-a-look-at-facebook-twitter-instagram-and-youtube-strategies/"><u>Exploring the Titans of Social Networking: A Look at Facebook, Twitter, Instagram, and YouTube Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-windows-11-not-running-errors-on-personal-computers-effective-strategies/"><u>Fixing Windows 11 Not Running Errors on Personal Computers - Effective Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-erase-kernel-and-user-mode-dumps-on-windows-11/"><u>How to Erase Kernel and User Mode Dumps on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/in-depth-guide-to-clearing-user-profiles-on-your-windows-10-machine-with-the-help-of-revo-uninstaller/"><u>In-Depth Guide to Clearing User Profiles on Your Windows 10 Machine with the Help of Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/keep-your-computer-safe-a-quick-look-at-locking-down-windows-systems/"><u>Keep Your Computer Safe: A Quick Look at Locking Down Windows Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/leading-channels-of-social-media-connection-facebook-twitter-instagram-and-youtube/"><u>Leading Channels of Social Media Connection: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/top-17-apple-mac-artists-the-ultimate-list-moveavista/"><u>Top 17 Apple Mac Artists : The Ultimate List - Moveavista</u></a></li>
<li><a href="https://fox-within.techidaily.com/ultimate-guide-removing-text-overlays-from-your-snaps-on-snapchat/"><u>Ultimate Guide: Removing Text Overlays From Your Snaps on Snapchat</u></a></li>
</ul></div>

