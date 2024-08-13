---
title: Winning Against High CPU Usage by svchost.exe in Windows 11 - Step-by-Step Solution
date: 2024-08-12T05:01:40.659Z
updated: 2024-08-13T05:01:40.659Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning Against High CPU Usage by svchost.exe in Windows 11 - Step-by-Step Solution
excerpt: This Article Describes Winning Against High CPU Usage by svchost.exe in Windows 11 - Step-by-Step Solution
thumbnail: https://thmb.techidaily.com/91890d8faaa4ea50693cf087efaa142eb641e1cff9ced9796756021407f6ea21.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-apowersoft-screen-recordings-critical-insights-and-alternatives/"><u>[New] 2024 Approved  Apowersoft Screen Recordings - Critical Insights and Alternatives</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-fine-tune-your-virtual-interaction-with-close-up-google-meet-tips/"><u>[New] Fine-Tune Your Virtual Interaction with Close-Up Google Meet Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-your-google-podcast-submission-process/"><u>[New] Perfecting Your Google Podcast Submission Process</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-social-strategists-guide-to-capturing-feedback-via-instagram-story-polls-for-2024/"><u>[New] The Social Strategist's Guide to Capturing Feedback via Instagram Story Polls for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-telegram-web-setup-for-novices/"><u>[Updated] Step-by-Step Telegram Web Setup for Novices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transforming-footage-a-step-by-step-guide-to-gopros-timelapse/"><u>[Updated] Transforming Footage  A Step-by-Step Guide to GoPro's Timelapse</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/vating-your-audience-youtube-intro-excellence-with-imovie-for-2024/"><u>Captivating Your Audience  YouTube Intro Excellence with iMovie for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-guide-to-engaging-audiences-on-major-platforms-ftiy/"><u>Comprehensive Guide to Engaging Audiences on Major Platforms FTIY</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-communication-leaders-strategies-for-success-on-facebook-twitter-instagram-youtube/"><u>Digital Communication Leaders: Strategies for Success on Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-adjustment-save-and-fix-completed/"><u>Display Adjustment: Save & Fix Completed</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-instructions-for-revo-uninstaller-app-management-setup/"><u>Easy Instructions for Revo Uninstaller App Management Setup</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-methods-for-installing-latest-windows-10-drivers-with-revouninstaller/"><u>Easy Methods for Installing Latest Windows 10 Drivers with RevoUninstaller</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-setup-for-your-epson-wf-2750-download-the-latest-driver-version/"><u>Easy Setup for Your Epson WF-2750: Download the Latest Driver Version</u></a></li>
<li><a href="https://win-forum.techidaily.com/enhance-windows-1astoff-speed-strategies-and-tools/"><u>Enhance Windows 1Astoff Speed - Strategies & Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/experience-ultimate-control-with-revo-uninstaller-professional-5/"><u>Experience Ultimate Control with Revo Uninstaller Professional 5</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-abruptly-discontinuing-hanging-software-in-your-windows-11-system/"><u>Expert Tips: Abruptly Discontinuing Hanging Software in Your Windows 11 System</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/explore-diverse-love-phrases-this-valentines-season/"><u>Explore Diverse Love Phrases This Valentine's Season</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-interactive-media-channels-the-power-of-facebook-twitter-instagram-and-youtube/"><u>Exploring Interactive Media Channels: The Power of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-oppo-a1x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-honor-x9b-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Honor X9b Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-ballot-box-battles-prime-voting-challenge-platforms/"><u>In 2024, Ballot Box Battles  Prime Voting Challenge Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-elevating-sims-4-chronicles-advanced-techniques-for-precise-game-recording/"><u>In 2024, Elevating Sims 4 Chronicles  Advanced Techniques for Precise Game Recording</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-f04-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy F04</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unravel-time-on-your-mobile-screen-with-videos/"><u>In 2024, Unravel Time on Your Mobile Screen with Videos</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-fast-boots-how-to-optimize-windows-11-starting-performance/"><u>Mastering Fast Boots: How to Optimize Windows 11 Starting Performance</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-networked-boot-controls-activating-wake-on-lan-for-windows-10-and-11-users/"><u>Mastering Networked Boot Controls: Activating Wake-on-LAN for Windows 10 & 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-engagement-on-major-sites-like-facebook-twitter-instagram-and-youtube/"><u>Mastering Social Media Engagement on Major Sites Like Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-media-facebook-twitter-and-instagram/"><u>Navigating the Giants of Social Media: Facebook, Twitter & Instagram</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-edit-mp4-videos-like-a-pro-top-10-free-tools/"><u>New 2024 Approved Edit MP4 Videos Like a Pro Top 10 Free Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-internet-issues-by-flushing-your-dns-cache-on-windows-10-and-11-a-how-to/"><u>Resolving Internet Issues by Flushing Your DNS Cache on Windows 10 & 11 – A How-To</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-eradicating-tracking-cookies-from-your-windows-11-and-android-device/"><u>Step-by-Step Guide: Eradicating Tracking Cookies From Your Windows 11 & Android Device</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-memory-dump-files-in-windows-10/"><u>Step-by-Step Guide: Removing Memory Dump Files in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-to-activate-wake-on-lan-in-windows-11/"><u>Step-by-Step Instructions to Activate Wake-on-LAN in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/tackling-windows-10-audio-issues-reinstalling-drivers/"><u>Tackling Windows 10 Audio Issues: Reinstalling Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/text-file-safeguarding-techniques-how-to-add-password-protection-effectively/"><u>Text File Safeguarding Techniques: How to Add Password Protection Effectively</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915306474-the-digital-mosaic-a-guide-to-successful-branding-on-facebook-twitter-instagram-and-youtube/"><u>The Digital Mosaic: A Guide to Successful Branding on Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-four-navigating-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Four - Navigating Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-social-networks-tactics-for-success-on-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Social Networks: Tactics for Success on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlisted-application-removal-steps-beyond-the-control-panel/"><u>Unlisted Application Removal: Steps Beyond the Control Panel</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-remote-power-management-activating-wake-on-lan-on-windows-devices/"><u>Unlocking Remote Power Management: Activating Wake-on-LAN on Windows Devices</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-does-my-iphones-screen-stay-on-too-long-and-what-can-i-do/"><u>Why Does My iPhone's Screen Stay On Too Long & What Can I Do?</u></a></li>
</ul></div>
