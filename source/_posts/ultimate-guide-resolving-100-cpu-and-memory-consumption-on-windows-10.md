---
title: "Ultimate Guide: Resolving 100%% CPU and Memory Consumption on Windows 10"
date: 2024-10-17T16:47:16.504Z
updated: 2024-10-18T17:29:06.313Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Ultimate Guide: Resolving 100%% CPU and Memory Consumption on Windows 10"
excerpt: "This Article Describes Ultimate Guide: Resolving 100%% CPU and Memory Consumption on Windows 10"
thumbnail: https://thmb.techidaily.com/0f51979df117bbafdf1571070799e2143d64735bc1b6be8bfd5d8bcb718371f0.jpg
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-how-to-snappify-your-macs-viewport/"><u>[New] 2024 Approved How To Snappify Your Mac's Viewport</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-pcandroid-tutorial-successful-facebook-video-sharing-for-2024/"><u>[New] PC/Android Tutorial Successful Facebook Video Sharing for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-peeking-into-apeaksofts-2023-screen-recording-features/"><u>[New] Peeking Into Apeaksoft’s 2023 Screen Recording Features</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-divide-and-conquer-adding-chapters-to-vimeo/"><u>[Updated] 2024 Approved Divide and Conquer Adding Chapters to Vimeo</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-effective-youtube-customization-for-powerful-endings/"><u>[Updated] 2024 Approved Effective YouTube Customization for Powerful Endings</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-2023s-most-reliable-voice-capturers-reviewed/"><u>2024 Approved 2023'S Most Reliable Voice Capturers Reviewed</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/convert-images-faster-switch-your-jpeg-photos-to-bmp-format-no-cost/"><u>Convert Images Faster: Switch Your JPEG Photos to BMP Format - No Cost!</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortless-system-tweaking-the-complete-guide-on-building-and-deleting-registry-paths-via-revo-uninstaller/"><u>Effortless System Tweaking: The Complete Guide on Building & Deleting Registry Paths via Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-alleviating-total-storage-capacity-drain-under-windows-10-for-smoother-performance/"><u>Guide: Alleviating Total Storage Capacity Drain Under Windows 10 for Smoother Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-enabling-wake-on-lan-functionality-on-windows-11-systems/"><u>Guide: Enabling Wake-on-LAN Functionality on Windows 11 Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nubia-red-magic-8s-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nubia Red Magic 8S Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-biggest-platforms-facebook-twitter-instagram-youtube/"><u>Navigating the Biggest Platforms: Facebook | Twitter | Instagram | YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolve-connectivity-issues-with-a-comprehensive-guide-to-dns-flushing-on-windows-devices/"><u>Resolve Connectivity Issues with a Comprehensive Guide to DNS Flushing on Windows Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstaller-tutorial-how-to-add-remove-or-modify-registry-entries-effortlessly/"><u>Revo Uninstaller Tutorial: How To Add, Remove or Modify Registry Entries Effortlessly</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-social-networking-navigating-facebook-twitter-instagram-and-youtube/"><u>The Big Four in Social Networking: Navigating Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-user-manual-how-to-navigate-and-modify-your-pcs-bios-configuration/"><u>Windows 11 User Manual: How To Navigate and Modify Your PC's BIOS Configuration</u></a></li>
</ul></div>

