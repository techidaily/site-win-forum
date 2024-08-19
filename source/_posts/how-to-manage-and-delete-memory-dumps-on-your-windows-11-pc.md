---
title: "How To: Manage and Delete Memory Dumps on Your Windows 11 PC"
date: 2024-08-18T10:44:25.901Z
updated: 2024-08-19T10:44:25.901Z
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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
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

## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-mastering-instagram-the-ultimate-video-editing-handbook/"><u>[New] 2024 Approved  Mastering Instagram  The Ultimate Video Editing Handbook</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-modern-marketers-guide-to-video-sharing-exploring-igtv-and-youtube/"><u>[New] 2024 Approved  The Modern Marketer's Guide to Video Sharing  Exploring IGTV & YouTube</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-5-strategies-for-enhancing-iphone-hdr-footage-in-premiere-pro/"><u>[Updated] 2024 Approved  5 Strategies for Enhancing iPhone HDR Footage in Premiere Pro</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-charting-success-understanding-youtube-insights/"><u>[Updated] In 2024, Charting Success  Understanding YouTube Insights</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sony-a6400-the-unseen-movie-problem/"><u>2024 Approved  Sony A6400  The Unseen Movie Problem</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparing-popular-sites-facebook-twitter-instagram-and-youtube-showdown/"><u>Comparing Popular Sites: Facebook, Twitter, Instagram and YouTube Showdown</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-removing-directories-and-files-using-cmd-on-windows-11/"><u>Complete Guide: Removing Directories & Files Using CMD on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-walkthrough-to-enable-your-revo-app-manager-seamlessly/"><u>Complete Walkthrough to Enable Your Revo App Manager Seamlessly</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-guide-to-popular-social-channels-facebook-twitter-instagram-and-youtube/"><u>Comprehensive Guide to Popular Social Channels - Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-major-platforms-twitter-instagram-facebook-and-youtube/"><u>Connect and Share on Major Platforms: Twitter, Instagram, Facebook & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-giants-showdown-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Digital Giants Showdown: Navigating Through Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/enhancing-system-efficiency-accessing-bios-in-windows-11-using-revouninstallers-features/"><u>Enhancing System Efficiency: Accessing BIOS in Windows 11 Using RevoUninstaller's Features</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>How Can I Use a Fake GPS Without Mock Location On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-force-quit-windows-apps-revouninstaller/"><u>How to Force Quit Windows Apps - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-locate-your-installed-powershell-version-on-a-windows-11-machine/"><u>How To Locate Your Installed PowerShell Version on a Windows 11 Machine</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-enhance-your-gopros-battery-health/"><u>In 2024, How to Enhance Your GoPro's Battery Health</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-vanguard-video-workshop-titlewright/"><u>In 2024, Vanguard Video Workshop Titlewright</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-major-online-hubs-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Mastering the Major Online Hubs: A Guide to Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-with-leading-sites-facebook-twitter-instagram-and-youtube-explained/"><u>Navigating the Digital Landscape with Leading Sites: Facebook, Twitter, Instagram, and YouTube Explained</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-through-openais-features-the-complete-user-manual-for-innovative-solutions/"><u>Navigating Through OpenAI's Features: The Complete User Manual for Innovative Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-samsung-galaxy-a14-4g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Samsung Galaxy A14 4G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/quickstart-activating-your-revo-app-manager-for-peak-performance/"><u>Quickstart: Activating Your Revo App Manager for Peak Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-windows-11-wont-run-issues-a-step-by-step-guide/"><u>Resolving 'Windows 11 Won't Run' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-sphere-titans-a-deep-dive-into-facebook-twitter-instagram-and-youtube/"><u>Social Sphere Titans: A Deep Dive Into Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/speed-up-windows-11-boot-process-in-minutes-a-comprehensive-walkthrough/"><u>Speed Up Windows 11 Boot Process in Minutes – A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-a-list-of-social-media-titans-connecting-through-facebook-twitter-instagram-youtube/"><u>The A-List of Social Media Titans: Connecting Through Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essentials-of-social-media-mastery-from-instagram-and-twitter-to-youtube/"><u>The Essentials of Social Media Mastery: From Instagram and Twitter to YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouse-of-online-networking-understanding-facebook-twitter-instagram-and-youtube/"><u>The Powerhouse of Online Networking: Understanding Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-7-solutions-to-stop-windows-explorer-from-continuously-failing/"><u>Top 7 Solutions to Stop Windows Explorer From Continuously Failing</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-methods-for-fixing-application-failure-on-pc-messages/"><u>Troubleshooting Methods for Fixing 'Application Failure on PC' Messages</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-cleanup-guide-freeing-up-space-with-ease/"><u>Windows 11 Cleanup Guide: Freeing Up Space with Ease</u></a></li>
</ul></div>
