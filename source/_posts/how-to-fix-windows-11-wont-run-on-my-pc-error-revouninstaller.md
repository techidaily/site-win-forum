---
title: How to Fix Windows 11 Wont Run on My PC Error - RevoUninstaller
date: 2024-12-03T02:20:16.433Z
updated: 2024-12-10T01:10:59.793Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes How to Fix Windows 11 Wont Run on My PC Error - RevoUninstaller
excerpt: This Article Describes How to Fix Windows 11 Wont Run on My PC Error - RevoUninstaller
thumbnail: https://thmb.techidaily.com/8581bfa31a5d038a1f8f5ee676586f0437981f1b9f6527b07717a27989fe2446.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-information.techidaily.com/new-a-tale-of-two-faces-iphone-x-and-samsung-compared/"><u>[New] A Tale of Two Faces IPhone X & Samsung Compared</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-sci-ed-hacks-top-youtube-experts-to-elevate-learning/"><u>[New] In 2024, Sci-Ed Hacks Top YouTube Experts to Elevate Learning</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-harmonyhub-pro-downloads-and-reviews-for-2024/"><u>[Updated] HarmonyHub Pro Downloads & Reviews for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-maximizing-youtube-clicks-with-imagery/"><u>2024 Approved Maximizing YouTube Clicks with Imagery</u></a></li>
<li><a href="https://win-forum.techidaily.com/enhancing-the-handheld-experience-microsoft-upgrades-windows-for-mobile-devices/"><u>Enhancing the Handheld Experience: Microsoft Upgrades Windows for Mobile Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/exciting-developments-await-as-windows-ns-widget-panel-gets-major-updates/"><u>Exciting Developments Await as Windows N's Widget Panel Gets Major Updates</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-diagnosing-and-repairing-lack-of-light-in-your-razer-keyboard/"><u>Expert Advice: Diagnosing and Repairing Lack of Light in Your Razer Keyboard</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/free-avi-video-rotator-software-and-apps-for-all-devices/"><u>Free AVI Video Rotator Software and Apps for All Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/goodnotes-on-windows-arrives-my-long-awaited-journey-to-an-enhanced-note-taking-adventure/"><u>GoodNotes on Windows Arrives - My Long-Awaited Journey to an Enhanced Note-Taking Adventure</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-xiaomi-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Xiaomi</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-oppo-find-x6-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Oppo Find X6 Device</u></a></li>
<li><a href="https://win-forum.techidaily.com/introducing-enhanced-windows-11-security-patch-kb5040442/"><u>Introducing Enhanced Windows 11 Security Patch KB5040442</u></a></li>
<li><a href="https://win-forum.techidaily.com/nvidias-new-approach-organizing-a-chaotic-array-of-pc-software-solutions/"><u>NVIDIA's New Approach: Organizing a Chaotic Array of PC Software Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resolving-ios-photo-import-issues-on-windows-os/"><u>Quick Guide: Resolving iOS Photo Import Issues on Windows OS</u></a></li>
<li><a href="https://win-forum.techidaily.com/refreshed-windows-11-experience-with-advanced-ai-copilot-support-redesigned-photo-gallery-and-dynamic-widget-features/"><u>Refreshed Windows 11 Experience with Advanced AI Copilot Support, Redesigned Photo Gallery, and Dynamic Widget Features</u></a></li>
<li><a href="https://win-forum.techidaily.com/revamped-microsoft-paint-advanced-editing-capabilities-unveiled/"><u>Revamped Microsoft Paint: Advanced Editing Capabilities Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/revolutionizing-portable-computing-microsofts-improvements-to-windows-for-pocket-sized-pcs/"><u>Revolutionizing Portable Computing: Microsoft's Improvements to Windows for Pocket-Sized PCs</u></a></li>
</ul></div>

