---
title: "Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
date: 2024-10-17T03:52:22.058Z
updated: 2024-10-23T17:17:46.041Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
excerpt: "This Article Describes Windows 11 Troubleshooting: Eliminating System Memory Dump Files Efficiently"
thumbnail: https://thmb.techidaily.com/ad7d05b0030775951042fde08b0fbde9a0ebb4cf05f0435bf5618af5d7b42ae3.jpg
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettieu.pxf.io/c/5597632/2141676/17091" target="_top" id="2141676">
  <img src="//a.impactradius-go.com/display-ad/17091-2141676" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141676/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-hovers.techidaily.com/new-mastering-podcast-writing-tips-and-free-template-samples/"><u>[New] Mastering Podcast Writing Tips & Free Template Samples</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-how-to-upload-shorts-video-on-youtube/"><u>[Updated] 2024 Approved How to Upload Shorts Video on YouTube?</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-photographic-precision-the-ultimate-list-of-photo-framing-software/"><u>[Updated] 2024 Approved Photographic Precision The Ultimate List of Photo Framing Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instas-power-players-a-guide-to-your-niches-movers-and-shakers/"><u>[Updated] In 2024, Insta’s Power Players A Guide to Your Niche's Movers & Shakers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-iphones-mirror-images-in-photos-for-2024/"><u>[Updated] Mastering iPhone's Mirror Images in Photos for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-seamless-temporal-annotation-perfecting-photo-date-insertion/"><u>[Updated] Seamless Temporal Annotation Perfecting Photo Date Insertion</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/complete-guide-setting-up-the-likuoo-plugin-for-unlimited-fun-with-likuoovideo-on-kodi-lea-and-krypton/"><u>Complete Guide: Setting Up the Likuoo Plugin for Unlimited Fun with likuoo.video on Kodi (Lea & Krypton)</u></a></li>
<li><a href="https://win-forum.techidaily.com/defy-the-restrictions-a-step-by-step-to-run-windows-11-on-prohibited-cpus/"><u>Defy the Restrictions: A Step-by-Step to Run Windows 11 on Prohibited CPUs</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-connection-leaders-delving-into-facebook-twitter-instagram-youtube/"><u>Digital Connection Leaders - Delving Into Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-popular-sites-connect-and-share-on-facebook-twitter-instagram-youtube/"><u>Discover Popular Sites: Connect and Share on Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-your-pc-specs-in-windows-11-a-detailed-walkthrough-of-the-system-summary-panel/"><u>Discover Your PC Specs in Windows 11 - A Detailed Walkthrough of the System Summary Panel</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-solutions-for-tackling-full-hard-drive-use-in-windows-10-systems/"><u>Effective Solutions for Tackling Full Hard Drive Use in Windows 10 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficiently-deleting-windows-10-memory-dumps-for-optimal-performance/"><u>Efficiently Deleting Windows 10 Memory Dumps for Optimal Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficiently-roll-back-windows-1011-patches-using-the-ultimate-tutorial-for-revouninstaller/"><u>Efficiently Roll Back Windows 10/11 Patches Using the Ultimate Tutorial for RevoUninstaller</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-tutorial-for-effective-morphvox-audio-changes/"><u>In 2024, Step-by-Step Tutorial for Effective MorphVOX Audio Changes</u></a></li>
</ul></div>

