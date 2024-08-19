---
title: Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
date: 2024-08-18T10:51:03.330Z
updated: 2024-08-19T10:51:03.330Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
excerpt: This Article Describes Guide to Configuring Wake-on-LAN on Your Windows PC (Windows 10/11)
thumbnail: https://thmb.techidaily.com/a7fa63ce234167f10d2e30f61413bb6b349d751281a956fa095e6d4da5fc3673.jpg
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-frontier-visionaries-merging-media-triad/"><u>[New] In 2024, Frontier Visionaries Merging Media Triad</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-future-of-techno-gaming-revenue/"><u>[Updated] 2024 Approved  Future of Techno-Gaming Revenue</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-virtual-visions-versus-tangible-tools-in-streaming/"><u>[Updated] In 2024, Virtual Visions Versus Tangible Tools in Streaming</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-exploring-the-boundaries-64128gb-for-vids/"><u>2024 Approved  Exploring the Boundaries  64/128GB for Vids</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-total-command-mastery-powerdirector-review-and-guide/"><u>2024 Approved  Total Command Mastery  PowerDirector Review & Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-user-friendly-approach-to-install-latest-drivers-on-your-windows-10-setup/"><u>A User-Friendly Approach to Install Latest Drivers on Your Windows 10 Setup</u></a></li>
<li><a href="https://change-location.techidaily.com/additional-tips-about-sinnoh-stone-for-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-step-by-step-process-of-deleting-windows-11-memory-dump-files/"><u>Complete Guide: Step-by-Step Process of Deleting Windows 11 Memory Dump Files</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-tutorial-edit-bios-settings-in-windows-11-made-simple/"><u>Complete Tutorial: Edit BIOS Settings in Windows 11 Made Simple</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-deleting-profiles-for-windows-10-users-using-advanced-tools/"><u>Comprehensive Tutorial on Deleting Profiles for Windows 10 Users Using Advanced Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-with-billions-on-popular-platforms-like-facebook-twitter-instagram-youtube/"><u>Connect with Billions on Popular Platforms Like Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-dots-among-top-platforms-facebook-twitter-instagram-and-youtube/"><u>Connecting the Dots Among Top Platforms: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-online-through-key-platforms-facebook-twitter-instagram-youtube/"><u>Connecting the World Online Through Key Platforms: Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-latest-methods-verifying-your-powershell-version-on-windows-11/"><u>Discover the Latest Methods: Verifying Your PowerShell Version on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/diy-solutions-for-windows-11-cant-be-installed-problem-on-your-pc-using-revouninstaller/"><u>DIY Solutions for 'Windows 11 Can't Be Installed' Problem on Your PC Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortless-software-removal-with-revo-uninstallers-hunter-mode-feature/"><u>Effortless Software Removal with Revo Uninstaller's Hunter Mode Feature</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-big-four-of-social-networking-facebook-tweetdeck-gramflex-and-vidplay/"><u>Exploring the Big Four of Social Networking: FaceBook, TweetDeck, GramFlex & VidPlay</u></a></li>
<li><a href="https://extra-tips.techidaily.com/extensive-analysis-best-cloud-storage-recommendations/"><u>Extensive Analysis  Best Cloud Storage Recommendations</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-overcome-total-drive-occupancy-problems-in-windows-10-computers/"><u>Guide to Overcome Total Drive Occupancy Problems in Windows 10 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/harnessing-the-power-of-major-social-channels-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Harnessing the Power of Major Social Channels: A Guide to Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-fix-access-denied-error-in-windows-revouninstaller/"><u>How to Fix Access Denied Error in Windows - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-safeguard-text-files-with-strong-passwords-expert-advice-and-solutions/"><u>How To Safeguard Text Files With Strong Passwords - Expert Advice & Solutions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-jokejumper-generate-meme-graphics-instantly/"><u>In 2024, JokeJumper  Generate Meme Graphics Instantly</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-turn-onoff-youtube-feedback-settings-with-this-guide/"><u>In 2024, Turn On/Off YouTube Feedback Settings With This Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/lock-down-windows-a-step-by-step-guide-to-enhanced-computer-safety/"><u>Lock Down Windows: A Step-by-Step Guide to Enhanced Computer Safety</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-major-online-communities-insights-on-facebook-twitter-instagram-and-youtube-usage/"><u>Navigating Major Online Communities: Insights on Facebook, Twitter, Instagram & YouTube Usage</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-the-powerhouses-of-social-media-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape: The Powerhouses of Social Media - Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-networking-fb-twitter-ig-and-yt/"><u>Navigating the Giants of Social Networking: FB, TWITTER, IG, and YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-networking-giants-facebook-twitter-instagram-and-youtube/"><u>Navigating the Social Networking Giants: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-installation-woes-effective-strategies-for-forced-uninstalls/"><u>Overcoming Installation Woes: Effective Strategies for Forced Uninstalls</u></a></li>
<li><a href="https://win-forum.techidaily.com/permanent-file-deletion-techniques-on-windows-11-a-step-by-step-guide/"><u>Permanent File Deletion Techniques on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/popular-platforms-for-sharing-and-engagement-facebook-twitter-instagram-youtube/"><u>Popular Platforms for Sharing & Engagement: Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolve-your-fortnite-login-failed-issue-in-minutes-step-by-step-guide/"><u>Resolve Your 'Fortnite Login Failed' Issue in Minutes - Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-the-class-not-registered-issue-in-windows-environments/"><u>Resolving the 'Class Not Registered' Issue in Windows Environments</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstaller-technique-to-delete-users-in-windows-11-efficiently/"><u>Revo Uninstaller Technique to Delete Users in Windows 11 Efficiently</u></a></li>
<li><a href="https://win-forum.techidaily.com/revos-role-in-user-profile-removal-on-windows-11-an-in-depth-guide/"><u>Revo's Role in User Profile Removal on Windows 11 - An In-Depth Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-essentials-mastering-facebook-twitter-instagram-and-youtube/"><u>Social Media Essentials: Mastering Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-titans-facebook-twitter-instagram-and-youtube-unveiled/"><u>Social Media Titans: Facebook, Twitter, Instagram & YouTube Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-class-not-found-issues-in-windows-a-step-by-step-guide/"><u>Solving 'Class Not Found' Issues in Windows - A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-your-pcs-cache-in-windows-11-using-revo-uninstaller/"><u>Step-by-Step Guide: Clearing Your PC's Cache in Windows 11 Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-windows-1n-10-memory-dump-files/"><u>Step-by-Step Guide: Removing Windows 1N 10 Memory Dump Files</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-7-plus-drfone-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essentials-of-bios-explained-insights-for-revouninstaller-users/"><u>The Essentials of BIOS Explained: Insights for RevoUninstaller Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-navigating-leading-social-media-sites-facebook-twitter-instagram-youtube/"><u>The Ultimate Guide to Navigating Leading Social Media Sites: Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-ensuring-peak-system-functionality-by-updating-drivers-on-windows-11-with-revouninstallers-help/"><u>The Ultimate Walkthrough: Ensuring Peak System Functionality by Updating Drivers on Windows 11 with RevoUninstaller's Help</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networking-platforms-facebook-twitter-and-instagram-vs-youtube/"><u>Top Social Networking Platforms: Facebook, Twitter & Instagram vs YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networking-sites-facebook-twitter-instagram-youtube/"><u>Top Social Networking Sites: Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-digital-sphere-with-leading-platforms-fbtwitterinstayoutube/"><u>Understanding the Digital Sphere with Leading Platforms - FbTwitterInstaYouTube</u></a></li>
</ul></div>
