---
title: "Locating Your Windows 11 PowerShell Edition: A Step-by-Step Guide"
date: 2024-11-12T02:21:06.890Z
updated: 2024-11-14T22:11:12.555Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Locating Your Windows 11 PowerShell Edition: A Step-by-Step Guide"
excerpt: "This Article Describes Locating Your Windows 11 PowerShell Edition: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/ae6df8d795ccb00d61125315956262434c01d350a9cd0692f6268b3c3a74de3f.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2043596/7443" target="_top" id="2043596">
  <img src="//a.impactradius-go.com/display-ad/7443-2043596" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043596/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-2024-approved-essential-knowledge-base-using-googles-ai-for-speech-recognition/"><u>[New] 2024 Approved Essential Knowledge Base Using Google's AI for Speech Recognition</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-journey-just-beginning-how-to-unlock-ifunny-memes/"><u>[New] 2024 Approved Journey Just Beginning How to Unlock iFunny Memes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-thrill-seekers-guide-games-like-grand-theft-auto-v/"><u>[Updated] 2024 Approved Thrill Seekers' Guide Games Like Grand Theft Auto V</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-oculus-odyssey-a-journey-through-best-vr-headsets/"><u>2024 Approved Oculus Odyssey A Journey Through Best VR Headsets</u></a></li>
<li><a href="https://win-forum.techidaily.com/battle-with-a-crashy-windows-explorer-try-these-7-tactics/"><u>Battle with a Crashy Windows Explorer? Try These 7 Tactics</u></a></li>
<li><a href="https://win-forum.techidaily.com/beyond-default-options-evaluating-the-need-for-a-third-party-app-to-remove-programs/"><u>Beyond Default Options: Evaluating the Need for a Third-Party App to Remove Programs</u></a></li>
<li><a href="https://win-forum.techidaily.com/clearing-storage-on-your-pc-efficient-ways-to-reclaim-disk-space-with-windows-11/"><u>Clearing Storage on Your PC: Efficient Ways to Reclaim Disk Space with Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/comprehensive-guide-to-overcoming-top-11-social-media-snags-on-fb/"><u>Comprehensive Guide to Overcoming Top 11 Social Media Snags on FB</u></a></li>
<li><a href="https://facebook.techidaily.com/how-linkedins-tracking-makes-networking-effortless-and-free/"><u>How LinkedIn’s Tracking Makes Networking Effortless and Free</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Infinix Note 30 VIP Racing Edition | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915400483-mastering-digital-interaction-on-popular-platforms-like-facebook-twitter-instagram-youtube/"><u>Mastering Digital Interaction on Popular Platforms Like Facebook, Twitter, Instagram, Youtube.</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915258477-navigating-the-giants-of-social-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Networking: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-tech-maze-with-tomns-hardware-experts/"><u>Navigating the Tech Maze with Tom'n's Hardware Experts</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915395345-troubleshooting-pc-problems-resolve-app-not-working-errors-easily/"><u>Troubleshooting PC Problems - Resolve 'App Not Working' Errors Easily</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-edition-easily-navigate-and-edit-your-pcs-bios-settings/"><u>Windows 11 Edition: Easily Navigate and Edit Your PC's BIOS Settings</u></a></li>
</ul></div>

