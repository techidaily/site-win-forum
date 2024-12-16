---
title: Resolving 'Plans Gone Astray' Errors in Windows 11 - Tips and Tricks to Get Back on Track
date: 2024-12-14T12:27:56.031Z
updated: 2024-12-15T22:51:14.550Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-innovative-ways-to-capture-online-discussions/"><u>[New] In 2024, Innovative Ways to Capture Online Discussions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-privacy-protection-in-videos-a-guide-to-obscuring/"><u>[New] In 2024, Privacy Protection in Videos A Guide to Obscuring</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-itel-p55-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Itel P55 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y78-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y78 5G</u></a></li>
<li><a href="https://fox-helps.techidaily.com/engaging-book-video-snippets/"><u>Engaging Book Video Snippets</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-stop-buffer-tweet-vids-in-chromium-browser/"><u>In 2024, Stop Buffer Tweet Vids in Chromium Browser</u></a></li>
<li><a href="https://extra-resources.techidaily.com/innovate-personalized-digital-chuckle-comedy/"><u>Innovate Personalized Digital Chuckle Comedy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revamping-your-clicks-a-comprehensive-tutorial-on-logitech-m310-mouse-drivers-update/"><u>Revamping Your Clicks: A Comprehensive Tutorial on Logitech M310 Mouse Drivers Update</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/speeding-up-your-pc-made-easy-a-step-by-step-guide-by-yl-software-experts/"><u>Speeding Up Your PC Made Easy: A Step-by-Step Guide by YL Software Experts</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-for-installing-revo-application-suite/"><u>Step-by-Step Instructions for Installing Revo Application Suite</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-for-removing-user-profiles-on-windows-11/"><u>Step-by-Step Process for Removing User Profiles on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-for-running-windows-11-with-ineligible-cpu-models/"><u>Step-by-Step Tutorial for Running Windows 11 with Ineligible CPU Models</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-clearing-up-100-storage-on-your-windows-11-pc/"><u>Step-by-Step Tutorial: Clearing Up 100% Storage on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-walkthrough-eliminating-secure-folders-using-revo-uninstaller-on-windows-operating-systems/"><u>Step-by-Step Walkthrough: Eliminating Secure Folders Using Revo Uninstaller on Windows Operating Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-social-media-and-video-sharing-unveiling-facebook-twitter-instagram-and-youtube/"><u>The Big Four of Social Media and Video Sharing: Unveiling Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-complete-tutorial-on-refreshing-driver-software-in-windows-10/"><u>The Complete Tutorial on Refreshing Driver Software in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-social-media-giants-insights-on-facebook-twitter-instagram-and-youtube/"><u>The Power of Social Media Giants: Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
</ul></div>

