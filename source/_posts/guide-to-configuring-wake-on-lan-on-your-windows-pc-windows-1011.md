---
title: Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
date: 2024-11-25T19:13:03.858Z
updated: 2024-12-02T19:24:03.673Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
excerpt: This Article Describes Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
thumbnail: https://thmb.techidaily.com/a7fa63ce234167f10d2e30f61413bb6b349d751281a956fa095e6d4da5fc3673.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-discover-the-best-12-pc-games-for-click-mastery/"><u>[New] 2024 Approved Discover the Best 12 PC Games for Click Mastery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-cutting-edge-recording-win-11s-superior-camcorders-for-2024/"><u>[New] Cutting-Edge Recording Win 11'S Superior Camcorders for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-elevate-your-iphone-x-experience-with-pro-animoji-use/"><u>[Updated] Elevate Your iPhone X Experience with Pro Animoji Use</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-trending-pictures-life-stories-uncovered/"><u>[Updated] Trending Pictures Life Stories Uncovered</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/bypassing-cpu-limitations-for-a-successful-windows-11-setup/"><u>Bypassing CPU Limitations for a Successful Windows 11 Setup</u></a></li>
<li><a href="https://win-forum.techidaily.com/command-prompt-techniques-for-permanent-deletion-of-files-and-directories-on-windows-11-computers/"><u>Command Prompt Techniques for Permanent Deletion of Files and Directories on Windows 11 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-removing-applications-from-your-windows-11-pc/"><u>Complete Guide: Removing Applications From Your Windows 11 PC</u></a></li>
<li><a href="https://tech-haven.techidaily.com/connecting-your-printer-to-wireless-network-a-comprehensive-tutorial/"><u>Connecting Your Printer to Wireless Network - A Comprehensive Tutorial</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elevate-your-gaming-experience-with-unique-sound-alteration-techniques-for-a-competitive-edge-no-cost/"><u>Elevate Your Gaming Experience with Unique Sound Alteration Techniques for a Competitive Edge (No Cost!)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-image-caption-manipulation-for-2024/"><u>Innovative Image Caption Manipulation for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/leading-mesh-wireless-solutions-reviewed-your-2024-roundup/"><u>Leading Mesh Wireless Solutions Reviewed - Your 2024 Roundup</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915231008-social-media-synergy-maximizing-impact-on-facebook-twitter-instagram-and-youtube-channels/"><u>Social Media Synergy: Maximizing Impact on Facebook, Twitter, Instagram and YouTube Channels</u></a></li>
<li><a href="https://solve-luxury.techidaily.com/superior-ebook-tool-transform-and-decode-your-digital-books-to-access-them-anytime-anywhere/"><u>Superior eBook Tool: Transform & Decode Your Digital Books to Access Them Anytime, Anywhere!</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-for-erasing-user-information-from-windows-11-systems-using-revo-uninstaller/"><u>Ultimate Guide for Erasing User Information From Windows 11 Systems Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-solving-the-issue-of-continuous-windows-explorer-crashes/"><u>Ultimate Guide: Solving the Issue of Continuous Windows Explorer Crashes</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-digital-landscape-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Understanding the Digital Landscape: A Deep Dive Into Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-your-pcs-nucleus-an-in-depth-look-at-the-windows-registry/"><u>Understanding Your PC's Nucleus: An In-Depth Look at the Windows Registry</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-easy-steps-implementing-and-running-revo-permission-manager-through-revouninstaller/"><u>Unveiling Easy Steps: Implementing & Running Revo Permission Manager Through RevoUninstaller</u></a></li>
</ul></div>

