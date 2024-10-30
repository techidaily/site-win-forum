---
title: "Troubleshooting: Steps to Discard a Windows 11 Software Upgrade"
date: 2024-10-28T22:21:23.290Z
updated: 2024-10-30T03:44:00.017Z
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
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-whimsical-videoland-assessment/"><u>[New] Whimsical Videoland Assessment</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-brush-up-your-skills-and-inspire-creativity-top-10-freeware-for-mac/"><u>[Updated] Brush Up Your Skills & Inspire Creativity - Top 10 Freeware for Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-ultimate-guide-the-hottest-meme-accounts-for-emotional-rollerscoasters/"><u>[Updated] The Ultimate Guide The Hottest Meme Accounts for Emotional Rollerscoasters</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-ultimate-selection-10-budget-friendly-youtube-caption-tools-for-2024/"><u>[Updated] Ultimate Selection 10 Budget-Friendly YouTube Caption Tools for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-essential-mac-tips-unlocking-your-srt-files/"><u>2024 Approved Essential Mac Tips Unlocking Your SRT Files</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-evaluating-the-storage-power-of-64128gb-units-for-vids/"><u>2024 Approved Evaluating the Storage Power of 64/128GB Units for Vids</u></a></li>
<li><a href="https://win-solutions.techidaily.com/avoid-frustration-in-star-wars-battlefront-ii-a-step-by-step-guide-to-fix-error-327/"><u>Avoid Frustration in Star Wars Battlefront II: A Step-by-Step Guide to Fix Error #327</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparing-giants-of-the-digital-world-facebook-twitter-instagram-and-youtube/"><u>Comparing Giants of the Digital World: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-social-hubs-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Essential Social Hubs: Navigating Through Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915337417-exploring-key-social-networks-unpacking-the-influence-of-facebook-twitter-instagram-and-youtube/"><u>Exploring Key Social Networks: Unpacking the Influence of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-the-class-not-registered-error-on-your-pc-easy-solutions-for-windows-users/"><u>Fixing the Class Not Registered Error on Your PC – Easy Solutions for Windows Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-s23-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy S23 to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-the-error-that-stops-windows-11-from-running-on-your-computer/"><u>Overcoming the Error That Stops Windows 11 From Running on Your Computer</u></a></li>
<li><a href="https://video-capture.techidaily.com/proven-6-best-video-grabbers-for-your-mac-for-2024/"><u>Proven 6 Best Video Grabbers for Your Mac for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-tutorial-to-clearing-dns-in-microsofts-latest-windows-versions/"><u>The Ultimate Tutorial to Clearing DNS in Microsoft's Latest Windows Versions</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-fix-guide-for-recurrently-failing-windows-explorer-discover-our-top-7-hacks/"><u>Ultimate Fix Guide for Recurrently Failing Windows Explorer - Discover Our Top 7 Hacks</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915308901-windows-11-launches-swiftly-techniques-for-a-quicker-boot-experience/"><u>Windows 11 Launches Swiftly: Techniques for a Quicker Boot Experience.</u></a></li>
</ul></div>

