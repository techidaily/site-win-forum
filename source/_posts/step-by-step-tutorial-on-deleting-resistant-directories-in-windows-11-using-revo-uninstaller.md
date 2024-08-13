---
title: Step-by-Step Tutorial on Deleting Resistant Directories in Windows 11 Using Revo Uninstaller
date: 2024-08-12T04:53:24.749Z
updated: 2024-08-13T04:53:24.749Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Step-by-Step Tutorial on Deleting Resistant Directories in Windows 11 Using Revo Uninstaller
excerpt: This Article Describes Step-by-Step Tutorial on Deleting Resistant Directories in Windows 11 Using Revo Uninstaller
thumbnail: https://thmb.techidaily.com/b025fc7ab394893f7e8a7b25d81a217b766fc055b9d4d40cb760c793a3b4d35f.jpg
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://youtube-webster.techidaily.com/57308572-new-in-2024-channel-milestone-hurdle-cross-the-10k-view-threshold-fast/"><u>[New] In 2024, Channel Milestone Hurdle – Cross the 10K View Threshold Fast!</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-plan-ahead-on-instagram-rankings-of-the-top-8-scheduling-apps/"><u>[Updated] 2024 Approved  Plan Ahead on Instagram  Rankings of The Top 8 Scheduling Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-accelerated-conversion-of-yt-content-for-mac-screens/"><u>[Updated] Accelerated Conversion of YT Content for MAC Screens</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-creating-a-tranquil-auditory-space-with-tech-for-2024/"><u>[Updated] Creating a Tranquil Auditory Space with Tech for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-new-light-on-the-sony-s3700-blu-ray-reader-review/"><u>2024 Approved  New Light on the Sony S3700 Blu-Ray Reader Review</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/bypass-the-restrictions-install-windows-11-on-unsupported-cpu-systems-via-revouninstaller-tips/"><u>Bypass the Restrictions: Install Windows 11 on Unsupported CPU Systems via RevoUninstaller Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-to-permanently-remove-a-login-account-from-your-pc-windows-11-and-revo-uninstaller-techniques/"><u>Complete Guide to Permanently Remove a Login Account From Your PC: Windows 11 and Revo Uninstaller Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-with-leading-networks-explore-facebook-to-youtube/"><u>Connect and Share with Leading Networks: Explore Facebook to YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-power-of-social-networking-with-fb-tw-ig-and-yt/"><u>Discover the Power of Social Networking with FB, TW, IG and YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-methods-for-deletion-of-windows-11-memory-dumps/"><u>Effective Methods for Deletion of Windows 11 Memory Dumps</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-techniques-to-quickly-unfreeze-and-shut-down-hanging-windows-programs/"><u>Effective Techniques to Quickly Unfreeze and Shut Down Hanging Windows Programs</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortless-system-maintenanci-with-hunter-mode-in-revo-uninstaller/"><u>Effortless System Maintenanci with Hunter Mode in Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-your-audience-on-major-sites-like-facebook-twitter-instagram-and-youtube/"><u>Engage Your Audience on Major Sites Like Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-strategies-to-reset-your-pcs-dns-settings-in-windows-10-and-11/"><u>Expert Strategies to Reset Your PC's DNS Settings in Windows 10 and 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-social-media-giants-facebook-twitter-instagram-and-youtube/"><u>Exploring the Social Media Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-encrypting-text-files-with-secure-passwords-using-revo-uninstaller/"><u>Guide to Encrypting Text Files with Secure Passwords Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-successfully-installing-windows-11-on-non-supported-processors/"><u>Guide: Successfully Installing Windows 11 on Non-Supported Processors</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Xiaomi Redmi Note 12R? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-creating-high-impact-yt-cover-images/"><u>In 2024, Creating High-Impact YT Cover Images</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-and-paid-drawing-tools-for-windows-enthusiasts/"><u>In 2024, Free and Paid Drawing Tools for Windows Enthusiasts</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-honor-x9b-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Honor X9b FRP?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-modern-communication-the-power-of-facebook-twitter-instagram-and-youtube/"><u>Mastering Modern Communication: The Power of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-most-popular-online-interaction-sites-facebook-twitter-instagram-youtube/"><u>Mastering the Most Popular Online Interaction Sites: Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-online-communities-with-leading-sites-like-facebook-twitter-instagram-and-youtube/"><u>Navigating Online Communities with Leading Sites Like Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-biggest-social-media-channels-facebook-twitter-insta-gram-youtube/"><u>Navigating the Biggest Social Media Channels: Facebook, Twitter, Insta-Gram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-system-restore-functionality-on-your-windows-11-pc/"><u>Navigating the System Restore Functionality on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-social-platforms-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Social Platforms: Insights on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcome-persistent-windows-explorer-crashes-with-these-7-essential-fixes-and-revouninstaller-tool/"><u>Overcome Persistent Windows Explorer Crashes with These 7 Essential Fixes and RevoUninstaller Tool</u></a></li>
<li><a href="https://win-forum.techidaily.com/rapid-startup-solutions-for-enhanced-windows-11-performance/"><u>Rapid Startup Solutions for Enhanced Windows 11 Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-100-disk-overload-on-your-windows-10-pc-a-step-by-step-guide/"><u>Resolving 100%% Disk Overload on Your Windows 10 PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-complete-disk-utilization-issues-on-windows-10-a-step-by-step-guide/"><u>Resolving Complete Disk Utilization Issues on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-speakers-not-detected-issue/"><u>Resolving Windows: Speakers Not Detected Issue</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstaller-strategies-expert-techniques-for-force-quitting-windows-software/"><u>RevoUninstaller Strategies: Expert Techniques for Force Quitting Windows Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-your-text-files-a-step-by-step-guide-to-applying-password-protection/"><u>Secure Your Text Files: A Step-by-Step Guide to Applying Password Protection</u></a></li>
<li><a href="https://win-forum.techidaily.com/speeding-up-the-launch-of-windows-11-a-comprehensive-guide-using-revouninstaller/"><u>Speeding Up the Launch of Windows 11: A Comprehensive Guide Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-complete-pc-refresh-with-windows-11-restore/"><u>Step-by-Step Guide: Complete PC Refresh with Windows 11 Restore</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-enabling-wake-on-lan-on-your-pc-running-windows-11/"><u>Step-by-Step Guide: Enabling Wake-on-LAN on Your PC Running Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-memory-dump-files-on-windows-10/"><u>Step-by-Step Guide: Removing Memory Dump Files on Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-overcoming-full-hard-drive-issues-on-windows-11-devices/"><u>Step-by-Step Instructions: Overcoming Full Hard Drive Issues on Windows 11 Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-top-four-mastering-the-art-of-engagement-on-facebook-twitter-instagram-and-youtube/"><u>The Top Four: Mastering the Art of Engagement on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-keeping-your-windows-10-drivers-current-and-compatible/"><u>The Ultimate Guide to Keeping Your Windows 10 Drivers Current and Compatible</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-navigating-the-bios-on-a-windows-11-machine-with-revo-uninstaller-assistance/"><u>The Ultimate Guide to Navigating the BIOS on a Windows 11 Machine with Revo Uninstaller Assistance</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-10-no-cost-gaming-recording-apps-for-gamers/"><u>Top 10 No-Cost Gaming Recording Apps for Gamers</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-platforms-engage-with-facebook-twitter-instagram-and-youtube/"><u>Top Social Platforms: Engage with Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://extra-information.techidaily.com/transformative-file-conversion-your-quick-srt-to-text-txt-guide/"><u>Transformative File Conversion  Your Quick SRT to Text (TXT) Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-managing-windows-registry-entries-with-revo-uninstaller/"><u>Ultimate Guide: Managing Windows Registry Entries with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-popular-online-communities-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Understanding Popular Online Communities: A Guide to Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-windows-registry-a-comprehensive-guide/"><u>Understanding the Windows Registry: A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-secrets-to-a-swift-windows-1n-boot-tactics-and-tools-for-efficiency/"><u>Unlock the Secrets to a Swift Windows 1N Boot: Tactics and Tools for Efficiency</u></a></li>
<li><a href="https://win-forum.techidaily.com/upgrade-your-system-the-ultimate-tutorial-on-refreshing-windows-11-driver-software/"><u>Upgrade Your System: The Ultimate Tutorial on Refreshing Windows 11 Driver Software</u></a></li>
</ul></div>
