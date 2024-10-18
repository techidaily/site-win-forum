---
title: "Step-by-Step Guide: Enabling Wake-on-LAN on Your PCs with Windows 10 & 11"
date: 2024-10-15T16:28:24.394Z
updated: 2024-10-18T16:53:52.263Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Step-by-Step Guide: Enabling Wake-on-LAN on Your PCs with Windows 10 & 11"
excerpt: "This Article Describes Step-by-Step Guide: Enabling Wake-on-LAN on Your PCs with Windows 10 & 11"
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
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

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flv-conversion-for-content-creators-top-10-youtubes-alternatives-unveiled/"><u>[New] In 2024, Flv Conversion for Content Creators Top 10 YouTubes Alternatives Unveiled</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-the-art-of-managing-discord-spoilers/"><u>[New] In 2024, The Art of Managing Discord Spoilers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722968353875-2-eastwood-also-directed/"><u>2) Eastwood Also Directed:</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/a-comprehensive-guide-to-using-your-blink-outdoor-multi-wireless-cameras-effectively/"><u>A Comprehensive Guide to Using Your Blink Outdoor Multi-Wireless Cameras Effectively</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-techniques-for-incor-written-by-sarah-johnson/"><u>Advanced Techniques for Incor Written By Sarah Johnson</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-guide-using-revo-uninstaller-pro-for-a-fresh-start-on-your-windows-11-pc/"><u>Comprehensive Guide: Using Revo Uninstaller Pro for a Fresh Start on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-an-overview-of-top-platforms-facebook-twitter-instagram-and-youtube/"><u>Connecting the World: An Overview of Top Platforms - Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-oneplus-nord-3-5g-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from OnePlus Nord 3 5G</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-major-social-media-platforms-facebook-twitter-instagram-and-youtube/"><u>Exploring Major Social Media Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-online-communities-across-facebook-twitter-instagram-and-youtube-platforms/"><u>Exploring Online Communities Across Facebook, Twitter, Instagram & YouTube Platforms</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-a-comprehenensive-guide-to-youtube-studios-editing-features/"><u>In 2024, A Comprehenensive Guide to YouTube Studio's Editing Features</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-worlds-most-influential-social-sites-a-closer-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the World's Most Influential Social Sites: A Closer Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-class-not-registration-problems-on-windows-systems/"><u>Troubleshooting 'Class Not Registration' Problems on Windows Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-tips-how-to-rollback-windows-11-updates/"><u>Troubleshooting Tips: How To Rollback Windows 11 Updates</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-voice-clarity-made-simple-top-10-no-cost-and-easy-to-use-audio-tools/"><u>Updated Voice Clarity Made Simple Top 10 No-Cost and Easy-to-Use Audio Tools</u></a></li>
</ul></div>

