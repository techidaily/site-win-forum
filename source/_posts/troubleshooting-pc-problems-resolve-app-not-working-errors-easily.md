---
title: Troubleshooting PC Problems - Resolve 'App Not Working' Errors Easily!
date: 2024-08-12T04:48:44.733Z
updated: 2024-08-13T04:48:44.733Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Troubleshooting PC Problems - Resolve 'App Not Working' Errors Easily!
excerpt: This Article Describes Troubleshooting PC Problems - Resolve 'App Not Working' Errors Easily!
thumbnail: https://thmb.techidaily.com/e61ec8b8b6fcdc5ae49f80ff7f35fd26c15f5f9f26e0670f639723e26a96ce2a.jpeg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/updated-in-2024-enhancing-video-conferencing-skills-on-chromebooks/"><u>[Updated] In 2024, Enhancing Video Conferencing Skills on ChromeBooks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-free-to-paid-subscriber-count-surpasses-500/"><u>2024 Approved  From Free to Paid  Subscriber Count Surpasses 500</u></a></li>
<li><a href="https://win-forum.techidaily.com/command-prompt-mastery-how-to-delete-filesfolders-efficiently-on-windows-11/"><u>Command Prompt Mastery: How to Delete Files/Folders Efficiently on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparing-major-networks-exploring-content-on-facebook-twitter-instagram-and-youtube/"><u>Comparing Major Networks: Exploring Content on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-how-to-erase-profiles-in-windows-10-using-revouninstaller/"><u>Comprehensive Tutorial on How to Erase Profiles in Windows 10 Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-powerhouses-of-digital-interaction-facebook-twitter-instagram-and-youtube-explained/"><u>Discover the Powerhouses of Digital Interaction: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-steps-to-identify-your-windows-11-powershell-version-with-ease/"><u>Discover the Steps to Identify Your Windows 11 PowerShell Version with Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-eliminate-windows-11-memory-dump-files-for-better-performance/"><u>Easy Steps to Eliminate Windows 11 Memory Dump Files for Better Performance</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-xiaomi-redmi-a2-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Xiaomi Redmi A2 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficient-techniques-for-expanding-drive-availability-in-windows-11/"><u>Efficient Techniques for Expanding Drive Availability in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-guide-selecting-high-quality-ringtone-downloads/"><u>Elite Guide  Selecting High-Quality Ringtone Downloads</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-security-tips-how-to-safely-shut-down-a-windows-machine/"><u>Essential Security Tips: How To Safely Shut Down A Windows Machine</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-strengthen-windows-defenses-with-these-5-techniques/"><u>Expert Advice: Strengthen Window's Defenses with These 5 Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-big-four-in-social-media-understanding-facebook-twitter-instagram-and-youtube/"><u>Exploring the Big Four in Social Media: Understanding Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-giants-of-online-interaction-facebook-twitter-instagram-youtube-explained/"><u>Exploring the Giants of Online Interaction: Facebook, Twitter, Instagram, YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-powerhouses-of-online-engagement-facebook-twitter-instagram-and-youtube/"><u>Exploring the Powerhouses of Online Engagement: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/faster-pc-launches-with-windows-11-essential-speeding-strategies/"><u>Faster PC Launches with Windows 11: Essential Speeding Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-find-out-what-version-of-powershell-youre-using-on-windows-11/"><u>How To Find Out What Version of PowerShell You're Using on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-blades-visual-journey-from-standard-to-stunning-4k/"><u>In 2024, Blade's Visual Journey  From Standard to Stunning 4K</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-poco-x6-pro-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-on-iphone-14-plus-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes On iPhone 14 Plus?</u></a></li>
<li><a href="https://win-forum.techidaily.com/insights-into-windows-registry-functionality-and-importance/"><u>Insights Into Windows Registry Functionality and Importance</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/learning-to-utilize-burst-mode-for-high-speed-photography-for-2024/"><u>Learning to Utilize Burst Mode for High-Speed Photography for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-communication-in-the-digital-age-with-facebook-twitter-instagram-and-youtube/"><u>Mastering Communication in the Digital Age with Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-engagement-on-leading-sites-facebook-twitter-instagram-youtube/"><u>Mastering the Art of Engagement on Leading Sites: Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-windows-registry-management-edit-remove-and-add-keys/"><u>Mastering Windows Registry Management: Edit, Remove & Add Keys</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-your-systems-firmware-a-deep-dive-into-bios-with-revouninstaller-assistance/"><u>Mastering Your System's Firmware: A Deep Dive Into BIOS with RevoUninstaller Assistance</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-social-giants-the-world-of-facebook-twitter-instagram-and-youtube/"><u>Navigating Social Giants: The World of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-digital-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Digital Networking: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-fixing-windows-configuration-stuck-glitch/"><u>Solution Guide for Fixing Windows Configuration Stuck Glitch</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-windows-11s-didnt-work-as-intended-error-step-by-step-guide/"><u>Solving Windows 11'S Didn't Work As Intended Error: Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-a-user-account-from-windows-10-with-ease/"><u>Step-by-Step Guide: Removing a User Account From Windows 10 with Ease</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-evolution-of-auto-hdr-and-its-role-in-todays-photography/"><u>The Evolution of Auto HDR and Its Role in Today's Photography</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-digital-communities-on-facebook-twitter-instagram-and-youtube/"><u>The Power of Digital Communities on Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-amazing.techidaily.com/troubleshooting-and-fixing-xbox-gamepad-drivers-for-windows-7-8-and-10/"><u>Troubleshooting and Fixing Xbox Gamepad Drivers for Windows 7, 8 & 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-updating-device-drivers-on-windows-11-using-revo-uninstaller/"><u>Ultimate Guide: Updating Device Drivers on Windows 11 Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-the-tricks-to-verify-powershell-versions-in-windows-10-systems/"><u>Unveiling the Tricks to Verify PowerShell Versions in Windows 10 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/upgrade-your-system-with-revo-uninstaller-pro-5-next-generation-app-cleanup-solution/"><u>Upgrade Your System with Revo Uninstaller Pro #5: Next-Generation App Cleanup Solution</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-10-user-profile-erasure-techniques-for-efficient-system-management/"><u>Windows 10 User Profile Erasure Techniques for Efficient System Management</u></a></li>
</ul></div>
