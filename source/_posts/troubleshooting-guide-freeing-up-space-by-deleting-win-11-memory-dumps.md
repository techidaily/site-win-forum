---
title: "Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
date: 2024-08-23T10:59:28.136Z
updated: 2024-08-24T10:59:28.136Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
excerpt: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
thumbnail: https://thmb.techidaily.com/58d1c82f33ff87a2a49ef482dc26ca840416cdee7dcea0bf9addd82da02902e0.jpg
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

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/ear-up-for-greatness-choosing-webcams-for-youtube-excellence-for-2024/"><u>[New] Gear Up for Greatness  Choosing Webcams for YouTube Excellence for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-best-captures-of-macs-visual-display-under-156-characters/"><u>2024 Approved  Best Captures of Mac's Visual Display (Under 156 Characters)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-bypassing-identification-to-explore-instagram-stories-desktop-android-ios/"><u>2024 Approved  Bypassing Identification to Explore Instagram Stories [Desktop, Android, iOS]</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-eradicating-data-with-the-windows-10-command-line-interface/"><u>Comprehensive Tutorial: Eradicating Data with the Windows 10 Command Line Interface</u></a></li>
<li><a href="https://win-forum.techidaily.com/delete-kernel-or-full-memory-dumps-from-windows-11-systematically/"><u>Delete Kernel or Full Memory Dumps From Windows 11 Systematically</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-influencers-at-play-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Digital Influencers at Play: Navigating Through Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/emerging-trends-in-enterprise-search-tech-a-glimpse-into-the-future-beyond-copernic/"><u>Emerging Trends in Enterprise Search Tech: A Glimpse Into the Future Beyond Copernic</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-social-networking-sites-navigating-facebook-twitter-instagram-youtube/"><u>Essential Social Networking Sites: Navigating Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-for-resolving-task-unsuccessful-errors-in-microsofts-latest-operating-system/"><u>Expert Tips for Resolving 'Task Unsuccessful' Errors in Microsoft's Latest Operating System</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-the-giants-of-online-communication-facebook-twitter-instagram-and-youtube/"><u>Explore the Giants of Online Communication: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-major-online-interaction-channels-facebook-twitter-instagram-and-youtube/"><u>Exploring Major Online Interaction Channels: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://extra-tips.techidaily.com/extensive-analysis-best-cloud-storage-recommendations/"><u>Extensive Analysis  Best Cloud Storage Recommendations</u></a></li>
<li><a href="https://common-error.techidaily.com/google-chrome-black-screen-error-step-by-step-solutions-for-a-clear-display/"><u>Google Chrome Black Screen Error - Step-by-Step Solutions for a Clear Display</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-xiaomi-redmi-note-12-proplus-5g-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Xiaomi Redmi Note 12 Pro+ 5G Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>How to Watch Hulu Outside US On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-raw-footage-to-high-quality-mpeg-youtube-conversion-techniques/"><u>In 2024, From Raw Footage to High-Quality MPEG  YouTube Conversion Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-no-more-running-out-of-room-top-20-zero-cost-cloud-services-up-to-1tb/"><u>In 2024, No More Running Out of Room - Top 20 Zero-Cost Cloud Services (Up To 1TB)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfect-habits-to-embrace-with-podcasts-playing/"><u>In 2024, Perfect Habits to Embrace with Podcasts Playing</u></a></li>
<li><a href="https://win-forum.techidaily.com/leveraging-social-giants-tactics-for-facebook-twitter-instagram-and-youtube-success/"><u>Leveraging Social Giants: Tactics for Facebook, Twitter, Instagram & YouTube Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximize-connections-streamlined-menu-for-linkedin-facebook-and-youtube-instant-page-navigation-to-top/"><u>Maximize Connections: Streamlined Menu for LinkedIn, Facebook, and YouTube | Instant Page Navigation to Top</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809009086-maximize-your-sites-accessibility-swiftly-navigate-to-the-top-and-seamlessly-connect-with-facebook-linkedin-and-youtube-through-our-expanding-toggle-menu/"><u>Maximize Your Site's Accessibility - Swiftly Navigate to the Top and Seamlessly Connect with Facebook, LinkedIn, and YouTube Through Our Expanding Toggle Menu</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/maximizing-movie-file-saving-6-methods-for-win-11-for-2024/"><u>Maximizing Movie File Saving  6 Methods for Win 11 for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-major-networking-sites-insights-into-facebook-twitter-instagram-and-youtube/"><u>Navigating Major Networking Sites: Insights Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/new-beginnings-in-windows-11-heres-your-guide-to-a-full-system-restore/"><u>New Beginnings in Windows 11? Here's Your Guide to a Full System Restore</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/personalized-dialogue-engines-creating-your-own-ai/"><u>Personalized Dialogue Engines: Creating Your Own AI</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolve-wireless-issues-in-windows-instantly/"><u>Resolve Wireless Issues in Windows Instantly</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809006988-santa-skims-but-you-need-depth-discover-how-copernic-transforms-your-data-check-with-precision-and-ease/"><u>Santa Skims, But You Need Depth - Discover How Copernic Transforms Your Data Check with Precision and Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/securely-grant-administrative-access-to-your-favorite-programs-on-windows-11/"><u>Securely Grant Administrative Access to Your Favorite Programs on Windows 11</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-itel-p55t-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Itel P55T</u></a></li>
<li><a href="https://win-forum.techidaily.com/solve-internet-issues-with-ease-flushing-the-dns-on-your-windows-pcs/"><u>Solve Internet Issues with Ease: Flushing the DNS on Your Windows PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/solving-app-cannot-run-errors-essential-steps-for-pc-users/"><u>Solving 'App Cannot Run' Errors: Essential Steps for PC Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809007894-struggling-to-track-down-files-on-your-machine-discover-proven-techniques-with-our-guide/"><u>Struggling to Track Down Files on Your Machine? Discover Proven Techniques with Our Guide!</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-top-four-digital-connectors-facebook-twitter-instagram-and-you-tube/"><u>The Top Four Digital Connectors: Facebook, Twitter, Instagram and You-Tube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-for-cleaning-files-and-folders-through-windows-10-command-line/"><u>The Ultimate Walkthrough for Cleaning Files and Folders Through Windows 10 Command Line</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/tilling-through-time-top-farmer-games-evolutions-for-2024/"><u>Tilling Through Time  Top Farmer Games Evolutions for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-engaging-social-networks-discover-the-power-of-facebook-twitter-instagram-and-youtube/"><u>Top Four Engaging Social Networks - Discover the Power of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809008145-top-tips-for-optimizing-menu-functionality-on-leading-networks-learn-to-efficiently-scroll-and-manage-content-on-facebook-linkedin-and-youtube/"><u>Top Tips for Optimizing Menu Functionality on Leading Networks – Learn to Efficiently Scroll & Manage Content on Facebook, LinkedIn, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-managing-registry-keys-with-ease-tips-from-revo-uninstaller/"><u>Ultimate Guide: Managing Registry Keys with Ease – Tips From Revo Uninstaller</u></a></li>
</ul></div>
