---
title: "Solving the 'Windows 11 Can't Install Error': Expert Guide"
date: 2024-11-01T20:51:58.672Z
updated: 2024-11-04T19:47:35.300Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Solving the 'Windows 11 Can't Install Error': Expert Guide"
excerpt: "This Article Describes Solving the 'Windows 11 Can't Install Error': Expert Guide"
thumbnail: https://thmb.techidaily.com/8979e8080587e2a8dc2c43407031e5a8747618e7ac4eca2f3b40cffb1bdf15c9.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-mastering-the-dynamics-of-ppt-sessions-across-devices-and-platforms/"><u>[New] 2024 Approved Mastering the Dynamics of PPT Sessions Across Devices and Platforms</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-cutting-edge-imaging-top-8k-cameras-unveiled-for-2024/"><u>[New] Cutting-Edge Imaging Top 8K Cameras Unveiled for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-broadcast-power-playout-analyzing-obs-versus-twitch-studios-strengths/"><u>[Updated] In 2024, Broadcast Power Playout Analyzing OBS Versus Twitch Studio's Strengths</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-insta-stories-enhancing-background-blur-technique/"><u>[Updated] Insta Stories Enhancing Background Blur Technique</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-websites-for-rhythmic-alerts-unique-sounds/"><u>2024 Approved Top Websites for Rhythmic Alerts Unique Sounds</u></a></li>
<li><a href="https://fox-access.techidaily.com/amplify-your-iphone-films-with-free-audio-additions-discover-three-ways/"><u>Amplify Your iPhone Films with Free Audio Additions – Discover Three Ways</u></a></li>
<li><a href="https://vp-tips.techidaily.com/complete-collection-every-movavi-software-offered-by-movavi-unlimited/"><u>Complete Collection: Every Movavi Software Offered by Movavi Unlimited</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/discover-excellent-open-source-video-players-the-ultimate-guide-for-windows-11-users/"><u>Discover Excellent Open-Source Video Players: The Ultimate Guide for Windows 11 Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-install-soundmax-drivers-for-windows-step-by-step-guide/"><u>Download & Install SoundMax Drivers for Windows - Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/hack-your-pc-enable-windows-11-installation-on-unsupported-chips/"><u>Hack Your PC: Enable Windows 11 Installation on Unsupported Chips</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-install-windows-11-on-unsupported-cpus-revouninstaller/"><u>How to Install Windows 11 on Unsupported CPUs - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-navigate-the-bios-setup-utility-with-ease-on-your-windows-11-pc/"><u>How to Navigate the BIOS Setup Utility with Ease on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-rollback-new-enhancements-in-windows-11-system/"><u>How to Rollback New Enhancements in Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/introducing-revo-uninstaller-pro-5-revouninstaller/"><u>Introducing Revo Uninstaller Pro 5 - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-content-sharing-across-major-networks-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Mastering Content Sharing Across Major Networks - A Deep Dive Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-digital-connections-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Mastering Digital Connections: A Guide to Facebook, Twitter, Instagram & YouTube</u></a></li>
</ul></div>

