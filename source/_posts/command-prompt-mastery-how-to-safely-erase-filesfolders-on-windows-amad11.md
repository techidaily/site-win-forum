---
title: "Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
date: 2024-11-28T02:56:04.877Z
updated: 2024-12-02T21:57:29.039Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
excerpt: "This Article Describes Command Prompt Mastery: How to Safely Erase Files/Folders on Windows Amad_11"
thumbnail: https://thmb.techidaily.com/d021ea19d35ef3673abfe0bc9bdff457eb34791e55514d7bc0ce5bafaca00aee.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Luckily, if your PC does not have the TPM2.0 chip there is still a way to take advantage of Windows 11 and its features.

 Note: If you use this method, Microsoft reserves the right to deny updates on your OS.

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-essential-tech-5-must-have-streaming-webcams-for-gamers/"><u>[New] In 2024, Essential Tech 5 Must-Have Streaming Webcams for Gamers</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-guide-to-the-top-10-historical-education-channels/"><u>[Updated] In 2024, Guide to the Top 10 Historical Education Channels</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-samsung-galaxy-a15-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Samsung Galaxy A15 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-honor-90-by-fonelab-android-recover-call-logs/"><u>How To Restore Missing Call Logs from Honor 90</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-5-premier-cloud-platforms-revolutionizing-storage/"><u>In 2024, 5 Premier Cloud Platforms Revolutionizing Storage</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-chucklecraft-constructor/"><u>In 2024, ChuckleCraft Constructor</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/peak-posts-on-reddit-honoring-10-highly-engaging-threads-for-2024/"><u>Peak Posts on Reddit Honoring 10 Highly Engaging Threads for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rejuvenating-exchdb-unveiling-stellarrepair-strategies/"><u>Rejuvenating Exchdb: Unveiling StellarRepair Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-up-your-game-with-advanced-copilot-plus-personal-computing-systems/"><u>Step Up Your Game with Advanced Copilot Plus Personal Computing Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-troubleshooting-and-solving-secure-internet-connectivity-problems-on-windows-pcs/"><u>Step-by-Step Tutorial: Troubleshooting & Solving Secure Internet Connectivity Problems on Windows PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/steps-to-turn-off-microsoft-defender-forever-in-windows-11/"><u>Steps to Turn Off Microsoft Defender Forever in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-inconspicuous-upheaval-of-ai-witnessing-change-beyond-sight/"><u>The Inconspicuous Upheaval of AI: Witnessing Change Beyond Sight</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-3-essential-gameplay-analytics-software-for-serious-pc-gamers/"><u>Top 3 Essential Gameplay Analytics Software for Serious PC Gamers</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-7-essential-window-configurations-to-maintain-active-benefits-explained/"><u>Top 7 Essential Window Configurations to Maintain Active: Benefits Explained</u></a></li>
<li><a href="https://fox-links.techidaily.com/unlock-the-art-of-iphone-photography-skill-building-tips-for-2024/"><u>Unlock the Art of iPhone Photography Skill-Building Tips for 2024</u></a></li>
</ul></div>

