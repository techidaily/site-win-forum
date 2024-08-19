---
title: Understanding and Accessing PC Specifications in Windows 11 without Third-Party Software
date: 2024-08-18T11:08:34.108Z
updated: 2024-08-19T11:08:34.108Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Understanding and Accessing PC Specifications in Windows 11 without Third-Party Software
excerpt: This Article Describes Understanding and Accessing PC Specifications in Windows 11 without Third-Party Software
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-expert-insights-mastering-your-game-recording-on-windows-10/"><u>[New] 2024 Approved  Expert Insights  Mastering Your Game Recording on Windows 10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-8-most-viewed-videos-on-facebook/"><u>[Updated] 8 Most Viewed Videos on Facebook</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-boost-your-instagram-with-easily-shareable-gifs-step-by-step-for-2024/"><u>[Updated] Boost Your Instagram with Easily Shareable GIFs (Step-by-Step) for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-examining-the-best-of-screen-capturing-tools-in-action/"><u>[Updated] Examining the Best of Screen Capturing Tools in Action</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-maximize-your-youtube-reach-key-tips-for-enhancing-video-seo/"><u>[Updated] Maximize Your YouTube Reach  Key Tips for Enhancing Video SEO</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-pinnacle-mac-screen-plus-audio-transcription-system-for-2024/"><u>[Updated] Pinnacle Mac Screen + Audio Transcription System for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-tecno-spark-10-4g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Tecno Spark 10 4G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win-forum.techidaily.com/hidden-removal-techniques-a-comprehensive-guide-to-eradicating-offscreen-apps-on-windows-systems/"><u>Hidden Removal Techniques: A Comprehensive Guide to Eradicating Offscreen Apps on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-firewall-options-for-blocking-software-to-windows-11s-context-menu/"><u>How to Add Firewall Options for Blocking Software to Windows 11’S Context Menu</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-free-up-space-by-eliminating-memory-dump-archives-on-windows-10-devices/"><u>How to Free Up Space by Eliminating Memory Dump Archives on Windows 10 Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-refresh-your-computer-factory-resetting-windows-11-using-the-powerful-revouninstaller/"><u>How to Refresh Your Computer: Factory Resetting Windows 11 Using the Powerful RevoUninstaller</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y36-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo Y36 Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-ace-your-videos-essential-editors-for-youtube/"><u>In 2024, Ace Your Videos  Essential Editors for YouTube</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/72511160-in-2024-unlock-creative-potential-access-free-sfx/"><u>In 2024, Unlock Creative Potential, Access Free SFX</u></a></li>
<li><a href="https://win-forum.techidaily.com/in-depth-walkthrough-eliminating-system-memory-dumps-on-windows-11-devices/"><u>In-Depth Walkthrough: Eliminating System Memory Dumps on Windows 11 Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-digital-connections-with-facebook-twitter-instagram-and-youtube/"><u>Mastering Digital Connections with Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-online-presence-leveraging-powerhouses-facebook-twitter-instagram-and-youtube/"><u>Mastering Online Presence: Leveraging Powerhouses Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-power-management-setting-up-wake-on-lan-for-windows-11-devices/"><u>Mastering Power Management: Setting Up Wake-on-LAN for Windows 11 Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-major-online-communities-facebook-twitter-instagram-youtube-insights/"><u>Navigating Major Online Communities: Facebook, Twitter, Instagram, Youtube Insights</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-major-online-communities-the-impact-of-facebook-twitter-instagram-and-youtube/"><u>Navigating Major Online Communities: The Impact of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-digital-communication-fb-twtr-igtv-and-yt/"><u>Navigating the Giants of Digital Communication: FB, TWTR, IGTV and YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-platforms-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Platforms: A Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-top-social-media-sites-faceook-tweetbook-instagram-yootube/"><u>Navigating the Top Social Media Sites: Faceook | TweetBook | InstaGram | YooTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/popular-networking-sites-navigating-through-facebook-twitter-instagram-youtube/"><u>Popular Networking Sites: Navigating Through Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/secretive-startup-strategies-conceal-the-shutdown-command/"><u>Secretive Startup Strategies: Conceal the Shutdown Command</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-giants-overview-understanding-facebook-twitter-instagram-and-youtube-impact/"><u>Social Giants Overview: Understanding Facebook, Twitter, Instagram & YouTube Impact</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-explained-how-to-excel-on-facebook-twitter-instagram-and-youtube/"><u>Social Media Giants Explained: How to Excel on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-titans-unleashing-potential-on-facebook-twitter-instagram-and-youtube/"><u>Social Media Titans: Unleashing Potential on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-unveiled-inside-stories-of-facebook-twitter-instagram-and-youtube-users/"><u>Social Media Unveiled: Inside Stories of Facebook, Twitter, Instagram and YouTube Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-network-showdown-insights-into-facebook-twitter-instagram-and-youtube-usage/"><u>Social Network Showdown: Insights Into Facebook, Twitter, Instagram, and YouTube Usage</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-excessive-hard-drive-load-on-windows-11-a-step-by-step-guide/"><u>Solving Excessive Hard Drive Load on Windows 11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-a-user-account-from-windows-11/"><u>Step-by-Step Guide: Removing a User Account From Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-a-windows-11-operating-system-update/"><u>Step-by-Step Guide: Removing a Windows 11 Operating System Update</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-to-find-the-powershell-version-on-windows-11/"><u>Step-by-Step Process to Find the PowerShell Version on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-social-scene-understanding-facebook-twitter-instagram-and-youtube-dynamics/"><u>The Digital Social Scene: Understanding Facebook, Twitter, Instagram & YouTube Dynamics</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essential-role-of-bios-in-computer-boot-process-insights-from-using-revo-uninstaller/"><u>The Essential Role of BIOS in Computer Boot Process: Insights From Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-social-networking-a-guide-to-using-facebook-twitter-instagram-and-youtube-effectively/"><u>The Power of Social Networking - A Guide to Using Facebook, Twitter, Instagram & YouTube Effectively</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-samsung-galaxy-a14-5g-by-drfone-android/"><u>Three Ways to Sim Unlock Samsung Galaxy A14 5G</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networking-sites-exploring-facebook-twitter-instagram-and-youtube/"><u>Top Social Networking Sites: Exploring Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://extra-tips.techidaily.com/transform-videos-with-tiktok-effects/"><u>Transform Videos with TikTok Effects</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-complete-storage-usage-issues-on-windows-11-computers/"><u>Troubleshooting Complete Storage Usage Issues on Windows 11 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-securely-erase-data-on-your-windows-10-pc/"><u>Ultimate Guide: Securely Erase Data on Your Windows 10 PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-guide-troubleshooting-and-resolving-lack-of-sound-in-zoom-for-desktop-users/"><u>Ultimate Guide: Troubleshooting and Resolving Lack of Sound in Zoom for Desktop Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-secrets-eradicating-full-hard-drive-congestion-in-windows-11-setups/"><u>Unlock the Secrets: Eradicating Full Hard Drive Congestion in Windows 11 Setups</u></a></li>
<li><a href="https://win-forum.techidaily.com/unpacking-the-influential-four-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Unpacking the Influential Four: A Deep Dive Into Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/unstuck-from-stubborn-folders-power-deletion-techniques-on-win-1011-via-revo-uninstaller/"><u>Unstuck From Stubborn Folders: Power Deletion Techniques on Win 10/11 via Revo Uninstaller</u></a></li>
</ul></div>
