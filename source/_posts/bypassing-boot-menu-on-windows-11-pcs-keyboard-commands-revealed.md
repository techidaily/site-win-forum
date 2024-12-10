---
title: "Bypassing Boot Menu on Windows 11 PCs: Keyboard Commands Revealed"
date: 2024-12-01T17:23:34.547Z
updated: 2024-12-02T16:21:38.783Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Bypassing Boot Menu on Windows 11 PCs: Keyboard Commands Revealed"
excerpt: "This Article Describes Bypassing Boot Menu on Windows 11 PCs: Keyboard Commands Revealed"
thumbnail: https://thmb.techidaily.com/908abdf5786977a17c0b2ecf2fc693bdf5a10c0549e2851740329dd839b1ac68.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-daily-blog-key-practices-and-avoidance-tactics/"><u>[New] 2024 Approved Elevate Your Daily Blog Key Practices and Avoidance Tactics</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-joke-makers-haven-get-it-today/"><u>[New] Joke Makers' Haven - Get It Today</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-legalities-sharing-vids-on-social-media-platforms/"><u>[New] Legalities Sharing Vids on Social Media Platforms</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/o-more-youtube-shorts-a-detailed-breakdown/"><u>[New] No More YouTube Shorts A Detailed Breakdown</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-crafting-professional-livestreams-on-youtube-and-twitch-using-obs/"><u>[Updated] 2024 Approved Crafting Professional Livestreams on YouTube and Twitch Using OBS</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-streamlining-your-digital-liftoffs-using-vlc-for-mp4-and-more/"><u>2024 Approved Streamlining Your Digital Liftoffs Using VLC for MP4 and More</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-comprehvew-on-file-encryption-implementing-password-protections-for-text-files/"><u>A Comprehvew on File Encryption: Implementing Password Protections for Text Files</u></a></li>
<li><a href="https://win-forum.techidaily.com/banish-recurrent-crashes-in-windows-explorer-with-these-easy-fix-steps/"><u>Banish Recurrent Crashes in Windows Explorer with These Easy Fix Steps</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-leading-social-media-facebook-twitter-instagram-youtube/"><u>Connect and Share on Leading Social Media: Facebook | Twitter | Instagram | YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-in-cyberspace-exploring-facebook-twitter-instagram-and-you-tubes-impact/"><u>Connecting in Cyberspace: Exploring Facebook, Twitter, Instagram & You-Tube's Impact</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915175275-exploring-the-giants-of-social-networking-facebook-twitter-instagram-and-youtube/"><u>Exploring the Giants of Social Networking - Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-peak-interactive-webcam-fun-fests/"><u>In 2024, Peak Interactive Webcam Fun Fests</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-issues-with-compiling-shaders-in-call-of-duty-black-ops-cold-war/"><u>Resolved: Issues with Compiling Shaders in Call of Duty Black Ops Cold War</u></a></li>
<li><a href="https://driver-install.techidaily.com/swift-driver-refresh-for-logitech-sound-equipment/"><u>Swift Driver Refresh for Logitech Sound Equipment</u></a></li>
<li><a href="https://win-forum.techidaily.com/win11-wont-boot-heres-what-you-need-to-do/"><u>Win11 Wont Boot? Here's What You Need to Do!</u></a></li>
</ul></div>

