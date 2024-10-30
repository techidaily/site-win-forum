---
title: "Resolving the 'Windows 11 Can't Start' Issue: A Step-by-Step Guide"
date: 2024-10-27T00:34:37.467Z
updated: 2024-10-29T23:30:20.206Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Resolving the 'Windows 11 Can't Start' Issue: A Step-by-Step Guide"
excerpt: "This Article Describes Resolving the 'Windows 11 Can't Start' Issue: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/7a686a1b526676a12878d5e404ff256d91c8737d5163c7ab05139a28f15cb6cd.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-capture-discord-talks-best-ways-to-record-live-streaming-sessions-for-2024/"><u>[New] Capture Discord Talks Best Ways to Record Live Streaming Sessions for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-amateurs-to-pros-transformative-steps-in-gopro-timelapses/"><u>[New] From Amateurs to Pros Transformative Steps in GoPro Timelapses</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-unlock-earnings-the-guide-to-successful-vimeo-monetization/"><u>[Updated] Unlock Earnings The Guide to Successful Vimeo Monetization</u></a></li>
<li><a href="https://buynow-info.techidaily.com/garmin-forerunner-45-review/"><u>Garmin Forerunner 45 Review</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/glitch-spotted-and-rectified-nvidia-drivers-to-the-rescue/"><u>Glitch Spotted & Rectified - Nvidia Drivers to the Rescue</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-free-minecraft-branding-tools-download/"><u>In 2024, Free Minecraft Branding Tools Download</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/iphone-15-pro-vs-iphone-14-pro-examining-the-enhancements-and-advantages-of-apples-latest-smartphone-in-depth-review-on-zdnet/"><u>IPhone 15 Pro Vs. IPhone 14 Pro: Examining the Enhancements and Advantages of Apple’s Latest Smartphone | In-Depth Review on ZDNET</u></a></li>
<li><a href="https://vp-tips.techidaily.com/les-top-5-sites-secrets-pour-decouvrir-et-downloader-de-jeu-free-sur-pc-sans-risque/"><u>Les Top 5 Sites Secrets Pour Découvrir Et Downloader De Jeu Free Sur PC Sans Risque</u></a></li>
<li><a href="https://some-approaches.techidaily.com/next-level-graphic-cards-for-4k-titles-for-2024/"><u>Next-Level Graphic Cards for 4K Titles for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-a-windows-11-update/"><u>Step-by-Step Guide: Removing a Windows 11 Update</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-windows-11-updates/"><u>Step-by-Step Guide: Removing Windows 11 Updates</u></a></li>
<li><a href="https://win-forum.techidaily.com/strategies-to-correct-overflowing-disk-space-on-windows-10-machines/"><u>Strategies to Correct Overflowing Disk Space on Windows 10 Machines</u></a></li>
<li><a href="https://win-forum.techidaily.com/streamline-software-removal-the-essentials-of-hunter-mode-on-revo-uninstaller/"><u>Streamline Software Removal: The Essentials of Hunter Mode on Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/tackle-constant-windows-explorer-errors-using-our-proven-7-tricks/"><u>Tackle Constant Windows Explorer Errors Using Our Proven 7 Tricks!</u></a></li>
<li><a href="https://win-forum.techidaily.com/text-file-encryption-tutorial-how-to-apply-password-security-using-revouninstaller/"><u>Text File Encryption Tutorial: How To Apply Password Security Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-sphere-navigating-popular-channels-facebook-twitter-instagram-youtube/"><u>The Digital Sphere: Navigating Popular Channels - Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essential-guide-to-navigating-the-windows-registry-with-helpful-revouninstaller-strategies/"><u>The Essential Guide to Navigating the Windows Registry with Helpful RevoUninstaller Strategies</u></a></li>
</ul></div>

