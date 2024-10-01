---
title: "Guide: Updating Graphics and Sound Cards in Windows 11 Made Simple"
date: 2024-09-30T16:17:25.031Z
updated: 2024-10-01T17:40:00.687Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Guide: Updating Graphics and Sound Cards in Windows 11 Made Simple"
excerpt: "This Article Describes Guide: Updating Graphics and Sound Cards in Windows 11 Made Simple"
thumbnail: https://thmb.techidaily.com/4d82cc5d4830160f77be1be23b3b0d5c8cbc630ac82437e197dd592c77a4c46e.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-enhance-creativity-with-these-top-6-instagram-reel-tools/"><u>[New] 2024 Approved Enhance Creativity with These Top 6 Instagram Reel Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-optimal-budget-free-fb-picturemotion-designer/"><u>[New] 2024 Approved Optimal Budget-Free FB Picture/Motion Designer</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-step-into-the-world-of-vrecorder-downloading-and-using/"><u>[New] In 2024, Step Into the World of VRecorder Downloading and Using</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-strategic-insights-into-making-emotional-connection-with-customer-success-videos/"><u>[Updated] 2024 Approved Strategic Insights Into Making Emotional Connection with Customer Success Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-commanding-attention-top-20-creative-tiktok-captions-for-2024/"><u>[Updated] Commanding Attention Top 20 Creative TikTok Captions for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-from-standard-to-spectacular-the-journey-with-vce-22/"><u>2024 Approved From Standard to Spectacular The Journey with VCE 2.2</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explaining-the-freeze-photo-booth-film-flow-for-2024/"><u>Explaining the Freeze Photo Booth Film Flow for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-not-running-problems-in-windows-11-a-comprehensive-guide/"><u>Overcoming 'Not Running' Problems in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-full-disk-utilization-on-windows-11-a-comprehensive-guide/"><u>Resolving Full Disk Utilization on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-unveiled-the-impact-of-facebook-twitter-instagram-and-youtube-on-society/"><u>Social Media Giants Unveiled: The Impact of Facebook, Twitter, Instagram and YouTube on Society</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-unveiled-the-essence-of-facebook-twitter-instagram-and-youtube/"><u>Social Media Unveiled: The Essence of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-to-disable-quick-launch-applications-with-revo-uninstaller/"><u>Step-by-Step Guide to Disable Quick Launch Applications with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-forcefully-erase-directories-in-windows-1011-using-professional-software/"><u>Step-by-Step Instructions: Forcefully Erase Directories in Windows 10/11 Using Professional Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-to-forcefully-eliminate-files-in-windows-11-with-the-help-of-revo-uninstaller/"><u>Step-by-Step Process to Forcefully Eliminate Files in Windows 11 with the Help of Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-how-to-remove-windows-10-dump-file-history/"><u>Step-by-Step Process: How To Remove Windows 10 Dump File History</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-clearing-data-with-cmd-tools-in-windows-10-system/"><u>Step-by-Step Tutorial: Clearing Data with CMD Tools in Windows 10 System</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-guide-to-3d-text-design-in-ps-for-2024/"><u>The Ultimate Guide to 3D Text Design in PS for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-xiaomi-redmi-note-12-pro-4g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Xiaomi Redmi Note 12 Pro 4G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/ultimate-audio-guide-to-the-top-5-4k-recording-microphones/"><u>Ultimate Audio Guide to the Top 5 4K Recording Microphones</u></a></li>
</ul></div>

