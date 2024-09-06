---
title: "DIY Windows Alerts: Setting Up an Easy Event Log Notification Tool"
date: 2024-09-05T07:55:56.231Z
updated: 2024-09-06T07:55:56.231Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fa51da89f91ea3306806b0c92d6d119cfa0eae393a63e41c230a883a3e7c64cd.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049383/7443" target="_top" id="2049383">
  <img src="//a.impactradius-go.com/display-ad/7443-2049383" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049383/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## DIY Windows Alerts: Setting Up an Easy Event Log Notification Tool

### Quick Links

* [How It Works](https://common-error.techidaily.com/the-laptop-headset-harmony-breakthrough-solution/)
* [Configuration](https://some-guidance.techidaily.com/enhance-your-website-with-cookiebot-technology-smart-data-driven-solutions/)
* [Examples](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-30-pro-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/)

 The Windows Event Logs are a tremendous resource as they can not only help you troubleshoot current system issues, but can also provide you with warning signs of potential future problems. So keeping on top of the events your system records can be key to keeping your system running as it should. Unfortunately, sifting through the Event Logs or creating custom views can be a cumbersome manual process.

 Thankfully, we have a solution which will easily allow you to export and filter Windows Event Log entries and then have them emailed and/or saved to a text file. When this process is configured as part of a scheduled task you can have, for example, warning and error messages emailed to you automatically.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How It Works

 Our solution works by using a freeware utility, MyEventViewer, by Nirsoft which allows you to easily export Windows Event Logs to a comma separated file. Based on this output, we have developed an easy to configure batch script which filters these results and then can email and/or save the filtered results file. Because the results are a comma separated file, it can be opened in Excel (or your favorite CSV program) and further sorted and filtered.

##  Configuration

 The configuration settings and options are documented as inline comments in the script, however we will cover a few of them in a bit of detail here.

**Event Log Name** 

 When specifying the Event Logs you want to capture the events from, you must use the system full name of the log. This is not necessarily what you see in the Event Viewer list of logs.

 For example, if you wanted to capture events from the "Microsoft Office Alerts" log, go to the Properties dialog of the log.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image1.png) 

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Note the value in the Full Name value, in this case "OAlerts". This would be the value you would need to enter into the script's configuration.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image2.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Event Types** 

 The values for the Event Types is simply the text you see in the "Level" column when you are viewing Event Logs. Typically these are either Information, Warning or Error but various logs may have different values.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image3.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087409/7443" target="_top" id="2087409">
  <img src="//a.impactradius-go.com/display-ad/7443-2087409" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087409/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Scheduled Task Setup** 

 The typical usage of this script is most likely in an automated process. So to make sure there is no overlap between your capture interval and when the process runs, you should set up a Windows Scheduled Task to complement the capture time.

 Quite simply, if your configuration is set to capture events for the last day, you should have a scheduled task that runs once per day. If your configuration is set to capture for the last hour, your scheduled task should be set to run once every hour. Etc.

 As an additional note, in order to make sure the MyEventViewer application can get to the information it needs, the respective scheduled task should be run with administrator rights on the machine.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image4.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024329/7443" target="_top" id="2024329">
  <img src="//a.impactradius-go.com/display-ad/7443-2024329" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024329/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Examples

 This configuration would email Errors and Warnings from the System and Application Event Logs recorded in the past day (24 hours) to my@email.com as well as save the output to the C:\\EventNotices folder:

* EmailResults=1
* EmailTo=my@email.com
* SaveResults=1
* SaveTo=C:\\EventNotices
* TimeInterval=3
* TimeValue=1
* Logs=System,Application
* Types=Error,Warning
* Scheduled Task should run every day.

 This configuration would only email Errors from the System Event Log recorded in the past hour to my@email.com:

* EmailResults=1
* EmailTo=my@email.com
* SaveResults=0
* TimeInterval=2
* TimeValue=1
* Logs=System
* Types=Error
* Scheduled Task should run every hour.

 This configuration would only save Errors and Warnings from the Application Event Log in the past week to the desktop of user JFaulkner (Windows 7) C:\\Users\\jfaulkner\\Desktop:

   * EmailResults=0
   * SaveResults=1
   * SaveTo=C:\\Users\\jfaulkner\\Desktop
   * TimeInterval=3
   * TimeValue=7
   * Logs=Application
   * Types=Error,Warning
   * Scheduled Task should run every week.

[Download Event Log Notifier Script from How-To Geek](https://printer-issues.techidaily.com/revived-post-windows-update-printer-workflow/) 

[Download MyEventViewer from Nirsoft](http://www.nirsoft.net/utils/my%5Fevent%5Fviewer.html) 

[Download Blat from Sourceforge](http://sourceforge.net/projects/blat/files/)

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
<li><a href="https://instagram-video-files.techidaily.com/new-influence-unleashed-5-crucial-steps-to-thriving-on-instagram-marketing/"><u>[New] Influence Unleashed  5 Crucial Steps to Thriving on Instagram Marketing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-basic-recorder-your-windows-10-companion/"><u>[Updated] In 2024, Basic Recorder - Your Windows 10 Companion</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-mastering-image-quality-a-guide-without-watermarks-for-2024/"><u>[Updated] Mastering Image Quality  A Guide Without Watermarks for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-shopping-spree-simplified-the-compreenas-guide-to-creating-and-crafting-haul-vids/"><u>2024 Approved  Shopping Spree Simplified  The Compreenas Guide to Creating & Crafting Haul Vids</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-comprehensive-guide-to-leading-social-platforms-facebook-twitter-instagram-and-youtube/"><u>A Comprehensive Guide to Leading Social Platforms: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-sony-xperia-5-v-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Sony Xperia 5 V</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-with-audience-through-major-platforms-facebook-twitter-instagram-and-youtube-explained/"><u>Connect and Engage with Audience Through Major Platforms: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-billions-an-in-depth-look-at-facebook-twitter-instagram-and-youtube/"><u>Connecting Billions: An In-Depth Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-giants-unveiled-mastering-interactions-on-facebook-twitter-instagram-and-youtube/"><u>Digital Giants Unveiled: Mastering Interactions on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-setup-intel-chipset-serial-io-drivers/"><u>Download & Setup: Intel Chipset Serial I/O Drivers</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-ways-to-delete-user-settings-in-windows-11-via-revouninstaller-software/"><u>Effective Ways to Delete User Settings in Windows 11 via RevoUninstaller Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-efficiently-flush-dns-caches-across-both-windows-10-and-windows-11-platforms/"><u>Expert Advice: Efficiently Flush DNS Caches Across Both Windows 10 and Windows 11 Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-social-media-giants-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Exploring Social Media Giants: A Guide to Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-social-media-giants-insights-into-facebook-twitter-instagram-and-youtube-usage/"><u>Exploring Social Media Giants: Insights Into Facebook, Twitter, Instagram and YouTube Usage</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-updating-graphics-and-sound-cards-in-windows-11-made-simple/"><u>Guide: Updating Graphics and Sound Cards in Windows 11 Made Simple</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-redmi-note-12-proplus-5g-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Redmi Note 12 Pro+ 5G.</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-honor-play-40c-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Honor Play 40C Phone? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-realme-c67-4g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Realme C67 4G Pattern Lock Screen</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Watch Hulu Outside US On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/journey-from-photographic-moments-to-sequential-videos/"><u>Journey From Photographic Moments to Sequential Videos</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-fix-for-peak-disk-usage-spike-on-your-windows-10-device-top-tips-and-tricks/"><u>Mastering the Fix for Peak Disk Usage Spike on Your Windows 10 Device: Top Tips & Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-windows-registry-edit-add-or-remove-key-steps/"><u>Mastering the Windows Registry: Edit, Add, or Remove Key Steps</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-online-networking-facebook-twitter-instagram-youtube/"><u>Navigating The Big Four of Online Networking: Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-online-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Online Networking: Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/premium-memory-device-for-sony-a7s-cameras/"><u>Premium Memory Device for Sony A7S Cameras</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-superuser-access-for-applications-a-step-by-step-tutorial-for-windows-11-users/"><u>Secure Superuser Access for Applications: A Step-by-Step Tutorial for Windows 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915274991-social-media-success-strategies-for-facebook-twitter-instagram-and-you/"><u>Social Media Success Strategies for Facebook, Twitter, Instagram & You.</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-the-domain-name-system-cache-on-windows-10-and-11/"><u>Step-by-Step Guide: Clearing the Domain Name System Cache on Windows 10 & 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-windows-10-system-cache-with-ease/"><u>Step-by-Step Guide: Clearing Windows 10 System Cache with Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-your-domain-name-system-cache-on-windows-1011/"><u>Step-by-Step Guide: Clearing Your Domain Name System Cache on Windows 10/11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-updating-your-windows-10-hardware-drivers-easily/"><u>Step-by-Step Guide: Updating Your Windows 10 Hardware Drivers Easily</u></a></li>
<li><a href="https://win-forum.techidaily.com/stop-file-explorer-disruptions-with-these-7-proven-fixes/"><u>Stop File Explorer Disruptions with These 7 Proven Fixes</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-mosaic-a-guide-to-successful-branding-on-facebook-twitter-instagram-and-youtube/"><u>The Digital Mosaic: A Guide to Successful Branding on Facebook, Twitter, Instagram & Youtube.</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-trio-of-social-networks-unpacking-facebook-twitter-instagram-and-youtube-influence/"><u>The Power Trio of Social Networks: Unpacking Facebook, Twitter, Instagram & YouTube Influence</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouses-of-digital-connection-facebook-twitter-instagram-and-youtube/"><u>The Powerhouses of Digital Connection: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-giants-for-digital-engagement-fb-twitter-ig-and-yt/"><u>The Quintessential Social Giants for Digital Engagement: FB, TWITTER, IG and YT</u></a></li>
<li><a href="https://common-error.techidaily.com/top-8-solutions-to-resolve-windows-10-error-message-0x800f0922/"><u>Top 8 Solutions to Resolve Windows 10 Error Message: 0X800F0922</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-guide-to-video-dimensions-and-proportion-harmony-on-youtube-for-2024/"><u>Total Guide to Video Dimensions & Proportion Harmony on YouTube for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-new-possibilities-configuring-windows-11-on-cpus-not-officially-supported/"><u>Unlocking New Possibilities: Configuring Windows 11 on CPUs Not Officially Supported</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-and-fix-enhance-performance-on-windows-11-v2004-with-new-conexant-driver/"><u>Update and Fix: Enhance Performance on Windows 11 (v2004) With New Conexant Driver</u></a></li>
</ul></div>
