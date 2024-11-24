---
title: "How To: Manage and Delete Memory Dumps on Your Windows 11 PC"
date: 2024-11-19T16:01:44.166Z
updated: 2024-11-24T16:02:53.924Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes How To: Manage and Delete Memory Dumps on Your Windows 11 PC"
excerpt: "This Article Describes How To: Manage and Delete Memory Dumps on Your Windows 11 PC"
thumbnail: https://thmb.techidaily.com/be34f09b3263dabe58e7e8e9b611840eed5d78451bd041646a395d4031103684.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-joking-jokebooks-top-10-hilarious-social-media-posts/"><u>[New] Joking Jokebooks Top 10 Hilarious Social Media Posts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-mirth-manual-best-free-meme-kits-alive/"><u>2024 Approved Mirth Manual Best Free Meme Kits Alive</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unlock-laughter-traps-20-quirky-fb-detention-anecdotes-for-amusement/"><u>2024 Approved Unlock Laughter Traps 20 Quirky FB Detention Anecdotes for Amusement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-cdw-air-glide-instructions-quickly/"><u>Brother CDW Air-Glide Instructions Quickly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enjoy-family-classics-with-amazon-prime-videos-curated-selection-for-july-2e-e4/"><u>Enjoy Family Classics with Amazon Prime Video's Curated Selection for July 2E-E4</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-tecno-camon-20-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Tecno Camon 20 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-system-protection-in-windows-10-with-system-restore-functionality/"><u>Mastering System Protection in Windows 10 with System Restore Functionality</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-troubled-setups-fixing-did-not-work-as-intended-mishaps-on-windows-11/"><u>Mastering Troubled Setups: Fixing 'Did Not Work As Intended' Mishaps on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-modern-communication-a-comparison-of-facebook-twitter-instagram-and-youtube/"><u>Navigating Modern Communication: A Comparison of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-social-networks-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Four Social Networks: Insights on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-major-social-platforms-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Major Social Platforms: Insights on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-windows-10-cli-mastering-file-and-folder-deletion-commands/"><u>Navigating the Windows 10 CLI: Mastering File and Folder Deletion Commands</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-social-media-giants-understanding-facebook-twitter-instagram-and-youtube/"><u>Navigating Through Social Media Giants: Understanding Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-top-platforms-an-insight-into-facebook-twitter-instagram-and-youtube/"><u>Navigating Through Top Platforms: An Insight Into Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-guide-to-fix-and-update-your-ralink-rt329n-wireless-card-on-windows-11-8-and-7/"><u>The Ultimate Guide to Fix and Update Your Ralink RT329n Wireless Card on Windows 11, 8 & 7</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/1722902312664-top-verizon-phone-promotions-exclusive-offers-available-this-month/"><u>Top Verizon Phone Promotions: Exclusive Offers Available This Month!</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
</ul></div>

