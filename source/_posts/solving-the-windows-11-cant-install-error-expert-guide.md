---
title: "Solving the 'Windows 11 Can't Install Error': Expert Guide"
date: 2024-08-18T10:25:46.828Z
updated: 2024-08-19T10:25:46.828Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Solving the 'Windows 11 Can't Install Error': Expert Guide"
excerpt: "This Article Describes Solving the 'Windows 11 Can't Install Error': Expert Guide"
thumbnail: https://thmb.techidaily.com/8979e8080587e2a8dc2c43407031e5a8747618e7ac4eca2f3b40cffb1bdf15c9.jpg
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
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://article-posts.techidaily.com/new-in-2024-ultimate-virtual-reality-controller-guide/"><u>[New] In 2024, Ultimate Virtual Reality Controller Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-essential-choice-10-free-youtube-subtitle-extractors/"><u>[Updated] 2024 Approved  Essential Choice  10 FREE YouTube Subtitle Extractors</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-strategies-that-accelerate-youtube-followers-acquisition/"><u>[Updated] 2024 Approved  Strategies That Accelerate YouTube Followers Acquisition</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-chromes-multi-screen-magic-pip-tutorial-for-2024/"><u>[Updated] Chrome's Multi-Screen Magic  PIP Tutorial for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevate-your-biz-game-youtube-channels-that-succeeded-for-2024/"><u>[Updated] Elevate Your Biz Game  YouTube Channels That Succeeded for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-how-to-change-voice-on-tiktok-for-2024/"><u>[Updated] How to Change Voice on TikTok for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-mastering-instagram-videos-direct-and-alternative-saves/"><u>[Updated] In 2024, Mastering Instagram Videos  Direct & Alternative Saves</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-picart-hack-keep-identities-unseen-for-2024/"><u>[Updated] PicArt Hack  Keep Identities Unseen for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-cutting-ties-with-instagram-users/"><u>2024 Approved  Cutting Ties with Instagram Users</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-top-10-mac-exclusive-free-drawing-platforms/"><u>2024 Approved  Top 10 Mac-Exclusive Free Drawing Platforms</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-want-to-explore-every-shared-piece-by-friends-through-messaging/"><u>2024 Approved  Want to Explore Every Shared Piece By Friends Through Messaging</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-guide-to-the-big-4-of-social-networks-mastering-interaction-on-facebook-twitter-instagram-and-youtube/"><u>A Guide to the Big 4 of Social Networks: Mastering Interaction on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/an-introduction-to-basic-inputoutput-systems-bios-explained/"><u>An Introduction to Basic Input/Output Systems (BIOS) Explained</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avi-video-editing-essentials-top-t-for-2024/"><u>AVI Video Editing Essentials Top T for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/best-soundstage-networking-for-2024/"><u>Best Soundstage Networking for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-walkthrough-for-installing-and-using-revo-uninstaller-pro-on-mobile-devices/"><u>Complete Walkthrough for Installing and Using Revo Uninstaller Pro on Mobile Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-methods-for-eliminating-user-accounts-in-windows-10/"><u>Comprehensive Methods for Eliminating User Accounts in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-with-a-click-exploring-facebook-twitter-instagram-and-youtube/"><u>Connect with a Click: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-across-networks-mastering-facebook-twitter-instagram-and-youtube-use/"><u>Connecting Across Networks: Mastering Facebook, Twitter, Instagram, and YouTube Use</u></a></li>
<li><a href="https://win-forum.techidaily.com/detecting-suspicious-android-apps-a-guide-using-revouninstaller/"><u>Detecting Suspicious Android Apps: A Guide Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-techniques-for-eliminating-windows-10-user-settings-and-data-permanently/"><u>Easy Techniques for Eliminating Windows 10 User Settings and Data Permanently</u></a></li>
<li><a href="https://techtrends.techidaily.com/effective-solutions-for-when-you-encounter-shell32dll-not-found-issues-on-your-pc/"><u>Effective Solutions for When You Encounter 'Shell32.dll Not Found' Issues on Your PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevating-visual-content-the-best-5-tools-for-online-videos/"><u>Elevating Visual Content  The Best 5 Tools for Online Videos</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/essential-fixes-for-6-common-gpt-flaws/"><u>Essential Fixes for 6 Common GPT Flaws</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-online-networking-sites-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Essential Online Networking Sites: A Guide to Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-on-immediately-ending-non-responsive-programs-in-windows-11-pcs/"><u>Expert Advice on Immediately Ending Non-Responsive Programs in Windows 11 PCs</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-advice-on-preventing-your-game-of-frostpunk-from-crashing/"><u>Expert Advice on Preventing Your Game of Frostpunk From Crashing</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-to-efficiently-erase-data-with-windows-11-command-prompt-tools/"><u>Expert Tips to Efficiently Erase Data with Windows 11 Command Prompt Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915261372-explore-the-giants-of-social-networking-facebook-twitter-instagram-and-youtube/"><u>Explore the Giants of Social Networking - Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-landscape-of-modern-connectivity-with-facebook-twitter-instagram-youtube/"><u>Exploring the Landscape of Modern Connectivity with Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-can-not-run-error-on-your-pc-with-windows-11-comprehensive-strategies/"><u>Fixing Can Not Run Error on Your PC with Windows 11 - Comprehensive Strategies</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-to-fact-check-health-information-from-chatgpt-and-ai-sources/"><u>How to Fact-Check Health Information From ChatGPT and AI Sources</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-download-custom-mcb-banner-packs/"><u>In 2024, Download Custom MCB Banner Packs</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-fostering-creativity-for-impressive-mac-produced-tiktok-beginnings/"><u>In 2024, Fostering Creativity for Impressive Mac-Produced TikTok Beginnings</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-the-undead-battlefield-solving-za4-issues-with-steam-and-pc-optimization/"><u>Mastering the Undead Battlefield: Solving ZA4 Issues with Steam and PC Optimization</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/smooth-printing-techniques-to-stop-your-3d-filament-from-tangling/"><u>Smooth Printing: Techniques to Stop Your 3D Filament From Tangling</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-guide-removing-liquid-from-inside-your-phone-speakers/"><u>Step-by-Step Guide: Removing Liquid From Inside Your Phone Speakers</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-complete-tutorial-on-refreshing-driver-software-in-windows-10/"><u>The Complete Tutorial on Refreshing Driver Software in Windows 10</u></a></li>
<li><a href="https://fox-info.techidaily.com/the-hidden-history-in-your-browser-how-to-tackle-for-2024/"><u>The Hidden History in Your Browser  How to Tackle for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-social-media-giants-insights-on-facebook-twitter-instagram-and-youtube/"><u>The Power of Social Media Giants: Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-guide-to-facebook-twitter-instagram-and-youtube-for-branding-success/"><u>The Quintessential Guide to Facebook, Twitter, Instagram and YouTube for Branding Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-titans-of-social-networking-connect-and-engage-on-facebook-twitter-instagram-youtube/"><u>The Titans of Social Networking: Connect and Engage on Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-optimizing-your-presence-on-fb-tw-ig-and-yt-platforms/"><u>The Ultimate Guide to Optimizing Your Presence on FB, TW, IG & YT Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-for-reverting-windows-11-patches/"><u>The Ultimate Walkthrough for Reverting Windows 11 Patches</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-5-strategies-for-securing-your-pc-protecting-with-windows/"><u>Top 5 Strategies for Securing Your PC: Protecting with Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-online-platforms-navigating-facebook-twitter-instagram-and-youtube/"><u>Top Online Platforms: Navigating Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-dull-to-dynamic-top-5-ai-writing-catalysts/"><u>Transforming Dull to Dynamic: Top 5 AI Writing Catalysts</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-the-error-plan-gone-awry-on-your-windows-11-system/"><u>Troubleshooting the Error: Plan Gone Awry on Your Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-managing-windows-registry-with-revo-uninstaller-key-creation-and-deletion/"><u>Ultimate Guide: Managing Windows Registry with Revo Uninstaller – Key Creation & Deletion</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915231907-ultimate-trick-for-protecting-text-documents-with-strong-passwords-learn-today/"><u>Ultimate Trick for Protecting Text Documents with Strong Passwords - Learn Today!</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-tutorial-on-removing-undocumented-programs-in-windows/"><u>Ultimate Tutorial on Removing Undocumented Programs in Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/uncovering-the-current-powershell-version-on-a-windows-10-system/"><u>Uncovering the Current PowerShell Version on a Windows 10 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-digital-interaction-the-powerhouses-facebook-twitter-instagram-and-youtube/"><u>Understanding Digital Interaction: The Powerhouses - Facebook, Twitter, Instagram & Youtube.</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-the-potential-of-wake-on-lan-for-your-windows-11-system/"><u>Unlocking the Potential of Wake-on-LAN for Your Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-the-power-of-social-media-expert-insights-into-facebook-twitter-instagram-and-youtube-usage/"><u>Unlocking the Power of Social Media: Expert Insights Into Facebook, Twitter, Instagram & Youtube Usage</u></a></li>
<li><a href="https://win-forum.techidaily.com/unofficial-guide-installing-windows-11-on-non-compatible-processors/"><u>Unofficial Guide: Installing Windows 11 on Non-Compatible Processors</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-best-online-locations-to-find-and-download-open-source-closing-music/"><u>Updated 2024 Approved Best Online Locations to Find and Download Open-Source Closing Music</u></a></li>
<li><a href="https://win-forum.techidaily.com/wake-on-lan-made-easy-how-to-turn-it-on-for-your-windows-desktops-and-laptops/"><u>Wake-on-Lan Made Easy: How to Turn It On for Your Windows Desktops and Laptops</u></a></li>
<li><a href="https://win-forum.techidaily.com/wireless-wakeup-secrets-how-to-implement-wake-on-lan-on-windows-10-and-11/"><u>Wireless Wakeup Secrets: How to Implement Wake-on-LAN on Windows 10 and 11</u></a></li>
</ul></div>
