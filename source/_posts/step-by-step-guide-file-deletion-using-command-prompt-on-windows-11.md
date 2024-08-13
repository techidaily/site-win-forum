---
title: "Step-by-Step Guide: File Deletion Using Command Prompt on Windows 11"
date: 2024-08-12T04:57:07.687Z
updated: 2024-08-13T04:57:07.687Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Step-by-Step Guide: File Deletion Using Command Prompt on Windows 11"
excerpt: "This Article Describes Step-by-Step Guide: File Deletion Using Command Prompt on Windows 11"
thumbnail: https://thmb.techidaily.com/933460ab5e97c9ff94ee3e62c125239a5731074d09b9d43607b3861f48a7087e.jpg
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
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

<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-driving-sales-not-just-views-monetizing-your-social-media-videos/"><u>[New] 2024 Approved  Driving Sales, Not Just Views  Monetizing Your Social Media Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-ploughing-through-the-past-top-farming-games-follow/"><u>[New] 2024 Approved  Ploughing Through the Past  Top Farming Games Follow</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-a-creators-primer-to-understanding-major-content-providers/"><u>[Updated] A Creator's Primer to Understanding Major Content Providers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-crafting-an-impressive-executive-summary-for-stakeholder-engagement-for-2024/"><u>[Updated] Crafting an Impressive Executive Summary for Stakeholder Engagement for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-cutting-edge-tips-best-practices-in-digital-sound-recording/"><u>[Updated] Cutting-Edge Tips  Best Practices in Digital Sound Recording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-demystifying-how-tseries-capitalizes-on-youtube-audience-reach-for-2024/"><u>[Updated] Demystifying How TSeries Capitalizes on YouTube Audience Reach for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-for-effective-pip-use-on-edge-browser/"><u>[Updated] Expert Tips for Effective PIP Use on Edge Browser</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-top-10-non-native-screen-capture-applications/"><u>[Updated] In 2024, Top 10 Non-Native Screen Capture Applications</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-proactive-measures-for-validating-tiktok-copyright-status/"><u>[Updated] Proactive Measures for Validating TikTok Copyright Status</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-revolutionizing-task-management-the-power-of-ez-grabber-for-2024/"><u>[Updated] Revolutionizing Task Management  The Power of EZ Grabber for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-streamlinedprocess-for-youcamwebrecord/"><u>[Updated] StreamlinedProcess for YouCamWebRecord</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-ultimate-obs-playbook-for-twitch-and-youtube-streaming/"><u>[Updated] The Ultimate OBS Playbook for Twitch & YouTube Streaming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-9-expert-picked-smartphone-chat-apps-for-business-use-for-2024/"><u>[Updated] Top 9 Expert-Picked Smartphone Chat Apps for Business Use for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-decoding-the-dynamics-of-whatsapp-audio-communication/"><u>2024 Approved  Decoding the Dynamics of WhatsApp Audio Communication</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-lightning-fast-visualization-for-win11-users/"><u>2024 Approved  Lightning-Fast Visualization for Win11 Users</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-beat-of-branding-mixing-music-into-your-instareel/"><u>2024 Approved  The Beat of Branding  Mixing Music Into Your InstaReel</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-xiaomi-civi-3-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Xiaomi Civi 3.</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hero5-black-or-yi-comparing-top-actions-cameras-for-2024/"><u>Hero5 Black or YI  Comparing Top Actions Cameras for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Sony Xperia 10 V? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-apple-iphone-12-pro-by-drfone-ios/"><u>How Do You Remove Restricted Mode on Apple iPhone 12 Pro</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-navigating-the-world-of-fbx-for-gamers/"><u>In 2024, Navigating the World of FBX for Gamers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-streamline-your-media-experience-windows-films-to-vimeo/"><u>In 2024, Streamline Your Media Experience  Windows Films to Vimeo</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-mi-drone-4k-review-drones-vs-landscape-photography/"><u>In 2024, The Mi Drone 4K Review  Drones vs Landscape Photography</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-samsung-galaxy-f34-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Samsung Galaxy F34 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-content-creation-on-facebook-twitter-instagram-and-youtube/"><u>Mastering Content Creation on Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-online-presence-through-top-platforms-a-closer-look-at-facebook-twitter-instagram-and-youtube/"><u>Mastering Online Presence Through Top Platforms: A Closer Look at Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-big-four-in-social-media-facebook-twitter-instagram-youtube/"><u>Mastering the Big Four in Social Media: Facebook, Twitter, Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximizing-your-presence-online-through-social-media-titans-fb-twt-igyt-unveiled/"><u>Maximizing Your Presence Online Through Social Media Titans: Fb, Twt, IGYT Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-user-permissions-a-how-to-for-always-starting-apps-as-an-administrator-in-windows-11/"><u>Navigating User Permissions: A How-To for Always Starting Apps as an Administrator in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-10-secure-online-forums-dedicated-to-meeting-fellow-netizens/"><u>New In 2024, 10 Secure Online Forums Dedicated to Meeting Fellow Netizens</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-tiktok-velocity-dance-tutorial-filmora-for-2024/"><u>New TikTok Velocity Dance Tutorial| Filmora for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/optimize-your-computer-with-revo-uninstaller-pro-5-the-premier-cleanup-suite/"><u>Optimize Your Computer with Revo Uninstaller Pro #5 - The Premier Cleanup Suite</u></a></li>
<li><a href="https://win-forum.techidaily.com/protective-measures-secure-your-text-file-information-from-unauthorized-access-using-a-password/"><u>Protective Measures: Secure Your Text File Information From Unauthorized Access Using a Password</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-fixes-for-closing-frozen-applications-on-windows-11-systems/"><u>Quick Fixes for Closing Frozen Applications on Windows 11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-start-to-activating-revo-permission-manager-using-revo-uninstaller-applications/"><u>Quick Start to Activating Revo Permission Manager Using Revo Uninstaller Applications</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-xiaomi-mix-fold-3-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://win-forum.techidaily.com/revitalize-slow-computer-performance-master-the-art-of-revouninstaller/"><u>Revitalize Slow Computer Performance - Master the Art of RevoUninstaller</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionizing-your-phones-storage-space-with-these-47-effective-video-trimmers-for-2024/"><u>Revolutionizing Your Phone's Storage Space with These 47 Effective Video Trimmers for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915285190-say-hello-to-efficient-app-cleanup-with-revo-uninstaller-pro-5/"><u>Say Hello to Efficient App Cleanup with Revo Uninstaller Pro 5!</u></a></li>
<li><a href="https://win-forum.techidaily.com/seamless-hardware-functionality-in-windows-11-mastering-driver-updates/"><u>Seamless Hardware Functionality in Windows 11 - Mastering Driver Updates</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-your-system-5-tips-for-protecting-windows-computers/"><u>Secure Your System: 5 Tips for Protecting Windows Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/simplify-your-pc-cleanup-with-revo-uninstallers-hunter-mode/"><u>Simplify Your PC Cleanup with Revo Uninstaller's Hunter Mode</u></a></li>
<li><a href="https://win-forum.techidaily.com/simplifying-file-clean-up-deleting-with-the-command-prompt-in-your-new-windows-11-system/"><u>Simplifying File Clean-Up: Deleting with the Command Prompt in Your New Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-decoded-the-impact-of-facebook-twitter-instagram-and-youtube-on-society/"><u>Social Media Giants Decoded: The Impact of Facebook, Twitter, Instagram & YouTube on Society</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-tactics-for-dominance-in-the-digital-age-insights-into-facebook-twitter-instagram-and-youtube/"><u>Social Media Tactics for Dominance in the Digital Age: Insights Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-eliminating-tracking-cookies-in-windows-10-and-android-devices/"><u>Step-by-Step Guide: Eliminating Tracking Cookies in Windows 10 & Android Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-enabling-wake-on-lan-feature-on-your-windows-11-pc/"><u>Step-by-Step Guide: Enabling Wake-on-LAN Feature on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-uninstalling-browsers-add-ons-in-windows-11/"><u>Step-by-Step Guide: Uninstalling Browsers Add-Ons in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-how-to-effectively-safelist-contacts-in-gmail/"><u>Step-by-Step: How To Effectively Safelist Contacts in Gmail</u></a></li>
<li><a href="https://win-forum.techidaily.com/tackling-the-failure-to-execute-properly-problem-a-how-to-for-windows-11-users/"><u>Tackling the 'Failure to Execute Properly' Problem: A How-To for Windows 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-digital-communication-insights-on-facebook-twitter-instagram-and-youtube/"><u>The Big Four in Digital Communication: Insights on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-elite-compilation-of-superior-flash-memory-devices/"><u>The Elite Compilation of Superior Flash Memory Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-essential-guide-to-windows-registry-for-efficient-use-of-revo-uninstaller/"><u>The Essential Guide to Windows Registry for Efficient Use of Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-5-strategies-for-overcoming-recurring-windows-explorer-malfunctions/"><u>Top 5 Strategies for Overcoming Recurring Windows Explorer Malfunctions</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-social-networks-exploring-facebook-twitter-instagram-and-youtube/"><u>Top Four Social Networks: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networks-explore-facebook-twitter-instagram-and-youtube/"><u>Top Social Networks - Explore Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-resolve-class-registration-errors-on-your-pc/"><u>Ultimate Guide: Resolve Class Registration Errors on Your PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-powerhouses-of-digital-communication-facebook-twitter-instagram-and-youtube/"><u>Understanding the Powerhouses of Digital Communication: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/uninstall-windows-11-patches-easily-with-these-simple-steps/"><u>Uninstall Windows 11 Patches Easily with These Simple Steps</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-remote-access-configuring-wake-on-lan-in-the-latest-windows-versions/"><u>Unlocking Remote Access: Configuring Wake-on-LAN in the Latest Windows Versions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-power-of-the-clearstream-eclipse-antenna-exceptional-performance-housed-in-an-intuitively-simple-design/"><u>Unveiling the Power of the ClearStream Eclipse Antenna - Exceptional Performance Housed in an Intuitively Simple Design</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-the-titans-of-online-interaction-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Unveiling the Titans of Online Interaction: A Guide to Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/user-manual-disabling-and-eliminating-windows-11-profiles-with-revo-uninstaller-tools/"><u>User Manual: Disabling and Eliminating Windows 11 Profiles with Revo Uninstaller Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/zoom-chat-how-to-chat-in-zoom-meeting-tips-and-tricks-for-2024/"><u>Zoom Chat  How to Chat in Zoom Meeting? [Tips & Tricks] for 2024</u></a></li>
</ul></div>
