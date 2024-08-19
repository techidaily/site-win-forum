---
title: "Resolving the 'Windows 11 Can't Start' Issue: A Step-by-Step Guide"
date: 2024-08-18T10:18:43.356Z
updated: 2024-08-19T10:18:43.356Z
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
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**
3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-exclusive-insights-elevating-your-mobizen-screencast-game/"><u>[New] Exclusive Insights  Elevating Your Mobizen Screencast Game</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/rowth-hackers-guide-the-ultimate-list-of-top-strategies-to-retain-youtube-viewers/"><u>[New] Growth Hackers Guide  The Ultimate List of Top Strategies to Retain YouTube Viewers</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-a-practical-approach-to-streaming-fb-content-on-your-apple-setup/"><u>[New] In 2024, A Practical Approach to Streaming FB Content on Your Apple Setup</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-charting-out-youtubes-financial-strategy-for-nurturing-short-videos/"><u>[New] In 2024, Charting Out YouTube's Financial Strategy for Nurturing Short Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-prime-video-communication-experience-the-top-10-mobile-apps/"><u>[New] In 2024, Prime Video Communication Experience  The Top 10 Mobile Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-influential-impact-celebrating-instagrams-most-dynamic-stars/"><u>[Updated] 2024 Approved  Influential Impact  Celebrating Instagram's Most Dynamic Stars</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-advanced-tips-for-recording-google-voice-dialogues/"><u>[Updated] Advanced Tips for Recording Google Voice Dialogues</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-enhancing-youtube-beauty-mastering-video-color-dynamics-for-2024/"><u>[Updated] Enhancing YouTube Beauty  Mastering Video Color Dynamics for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-tunetruthseeker-reaction-to-songs-and-speech-for-2024/"><u>[Updated] TuneTruthseeker  Reaction to Songs and Speech for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-engaging-oratory-insights-part-8/"><u>2024 Approved  Engaging Oratory Insights Part 8</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-leading-macos-sierra-choices-for-file-conversion/"><u>2024 Approved  Leading MacOS Sierra Choices for File Conversion</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-poco-c50-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Poco C50 | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/advanced-techniques-to-modify-delete-and-add-new-entries-into-the-windows-registry/"><u>Advanced Techniques to Modify, Delete and Add New Entries Into the Windows Registry</u></a></li>
<li><a href="https://win-forum.techidaily.com/an-overview-of-what-the-windows-registry-is-and-how-it-works/"><u>An Overview of What The Windows Registry Is & How It Works</u></a></li>
<li><a href="https://win-forum.techidaily.com/clearing-storage-on-your-pc-a-step-by-step-guide-for-windows-11/"><u>Clearing Storage on Your PC: A Step-by-Step Guide for Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/comparing-major-networks-facebook-twitter-instagram-and-youtube/"><u>Comparing Major Networks: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-the-perfect-strategy-exclusive-youtube-to-gmail-connection/"><u>Crafting the Perfect Strategy  Exclusive YouTube to Gmail Connection</u></a></li>
<li><a href="https://extra-tips.techidaily.com/eliminating-watermarks-from-your-stock-collections/"><u>Eliminating Watermarks From Your Stock Collections</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-the-top-online-tech-training-courses-available/"><u>Explore the Top Online Tech Training Courses Available</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-major-social-hubs-online-from-twitter-to-instagram/"><u>Exploring Major Social Hubs Online: From Twitter to Instagram</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-online-connectivity-a-comparison-of-facebook-twitter-instagram-and-youtube/"><u>Exploring Online Connectivity: A Comparison of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-biggest-networks-online-from-tweets-to-likes-facebook-twitter-instagram-and-youtube/"><u>Exploring the Biggest Networks Online: From Tweets to Likes - Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/eye-appeal-the-top-3-ways-to-increase-instagram-visibility-for-2024/"><u>Eye Appeal  The Top 3 Ways to Increase Instagram Visibility for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nubia-red-magic-8s-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-tecno-spark-10-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/guarantee-computer-security-master-the-5-key-steps-for-windows-protection/"><u>Guarantee Computer Security: Master the 5 Key Steps for Windows Protection</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-permanently-setting-up-administrator-access-for-apps-in-windows-11/"><u>Guide: Permanently Setting Up Administrator Access for Apps in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Realme C53 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-vivo-y78plus-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Vivo Y78+ FRP Bypass</u></a></li>
<li><a href="https://win-forum.techidaily.com/maintain-optimal-performance-updating-hardware-drivers-in-windows-10-using-revouninstaller/"><u>Maintain Optimal Performance: Updating Hardware Drivers in Windows 10 Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-flushing-dns-tips-and-tricks-for-windows-1011-users/"><u>Master the Art of Flushing DNS: Tips and Tricks for Windows 10/11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-trick-to-always-launch-windows-11-programs-as-an-administrator/"><u>Master the Trick to Always Launch Windows 11 Programs as an Administrator</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-online-interaction-on-major-platforms-facebook-twitter-instagram-and-youtube-tips/"><u>Mastering Online Interaction on Major Platforms: Facebook, Twitter, Instagram & Youtube Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-windows-11-a-step-by-step-guide-to-running-any-app-with-admin-rights/"><u>Mastering Windows 11: A Step-by-Step Guide to Running Any App with Admin Rights</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-listening-windows-episode-releases-for-2024/"><u>Prime Listening Windows  Episode Releases for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-frozen-downloads-restart-tracker-resume-progress/"><u>Quick-Fix for Frozen Downloads: Restart Tracker, Resume Progress</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-0x80t70541-update-issue-successfully/"><u>Resolving the Windows 11 0X80t70541 Update Issue Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-a-look-into-facebook-twitter-instagram-and-youtubes-influence/"><u>Social Media Giants: A Look Into Facebook, Twitter, Instagram & Youtube's Influence</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-networking-titans-exploring-facebook-twitter-instagram-and-youtubes-impact/"><u>Social Networking Titans: Exploring Facebook, Twitter, Instagram & YouTube's Impact</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-major-social-media-sites-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Major Social Media Sites: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-social-media-giants-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Social Media Giants: Facebook, Twitter, Instagram, & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/tips-and-tricks-for-handling-unexpected-windows-11-errors-successfully/"><u>Tips and Tricks for Handling Unexpected Windows 11 Errors Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-failed-startup-for-apps-effective-solutions-for-your-pc-woes/"><u>Troubleshooting Failed Startup for Apps: Effective Solutions for Your PC Woes</u></a></li>
<li><a href="https://win-forum.techidaily.com/unleash-your-online-presence-with-leading-platforms-facebook-twitter-instagram-and-youtube/"><u>Unleash Your Online Presence with Leading Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-free-video-editing-made-easy-a-jaycut-tutorial-for-beginners/"><u>Updated 2024 Approved Free Video Editing Made Easy A Jaycut Tutorial for Beginners</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-10-power-users-tutorial-file-and-folder-removal-via-cmd/"><u>Windows 10 Power User's Tutorial: File & Folder Removal via CMD</u></a></li>
</ul></div>
