---
title: How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
date: 2024-10-17T17:02:58.439Z
updated: 2024-10-18T17:08:30.139Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
excerpt: This Article Describes How to Add Unrecognized Devices to BIOS Settings on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/4aac991e64509d68ac8489b0b42db25368d487df0c50d4cd60fbe09c3938eb3d.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027190/19272" target="_top" id="2027190">
  <img src="//a.impactradius-go.com/display-ad/19272-2027190" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027190/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014857/22899" target="_top" id="2014857">
  <img src="//a.impactradius-go.com/display-ad/22899-2014857" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014857/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-drone-species-and-their-traits/"><u>[Updated] 2024 Approved Drone Species & Their Traits</u></a></li>
<li><a href="https://facebook.techidaily.com/analyzing-the-shift-in-tech-monopoly-controls/"><u>Analyzing the Shift in Tech Monopoly Controls</u></a></li>
<li><a href="https://win-forum.techidaily.com/boost-performance-by-flushing-dns-on-windows-operating-systems/"><u>Boost Performance by Flushing DNS on Windows Operating Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-setting-up-and-enabling-the-revo-app-manager/"><u>Complete Guide: Setting Up & Enabling the Revo App Manager</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-instructions-to-automatically-launch-apps-with-admin-authority-in-windows-11/"><u>Complete Instructions to Automatically Launch Apps with Admin Authority in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-digital-landscape-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Exploring the Digital Landscape: A Deep Dive Into Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-vivo-t2x-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Vivo T2x 5G Pattern Lock Screen</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-a-poco-m6-pro-5g-easily-by-drfone-android/"><u>How To Unlock a Poco M6 Pro 5G Easily?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-harness-the-power-of-analytics-to-rise-in-fan-counts/"><u>In 2024, Harness the Power of Analytics to Rise in Fan Counts</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-depth-assessment-comprehensive-camstudio-review/"><u>In-Depth Assessment Comprehensive CamStudio Review</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-networking-on-giants-of-digital-age-facebook-twitter-instagram-and-youtub/"><u>Mastering Networking on Giants of Digital Age: Facebook, Twitter, Instagram & YouTub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-stuck-gifs-in-discord-windows-edition/"><u>Mastering the Art of Fixing Stuck GIFs in Discord Windows Edition</u></a></li>
<li><a href="https://win-forum.techidaily.com/removing-undetected-installed-software-on-windows-computers/"><u>Removing Undetected Installed Software on Windows Computers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-error-code-0x80071ac3-methods-to-fix-a-corrupted-disk/"><u>Solving Error Code 0X80071AC3: Methods to Fix a Corrupted Disk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-resolving-steam-login-errors/"><u>Strategies for Resolving Steam Login Errors</u></a></li>
<li><a href="https://win-forum.techidaily.com/streamline-tech-support-updating-device-drivers-on-windows-11-made-simple/"><u>Streamline Tech Support: Updating Device Drivers on Windows 11 Made Simple</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-fix-for-frequent-windows-1011-stalling-insider-advice/"><u>The Ultimate Fix for Frequent Windows 10/11 Stalling: Insider Advice</u></a></li>
</ul></div>

