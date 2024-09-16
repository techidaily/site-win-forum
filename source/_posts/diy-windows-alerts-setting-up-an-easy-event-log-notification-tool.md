---
title: "DIY Windows Alerts: Setting Up an Easy Event Log Notification Tool"
date: 2024-09-13T16:46:59.785Z
updated: 2024-09-16T16:50:09.785Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fa51da89f91ea3306806b0c92d6d119cfa0eae393a63e41c230a883a3e7c64cd.jpg
---

## DIY Windows Alerts: Setting Up an Easy Event Log Notification Tool

### Quick Links

* [How It Works](https://common-error.techidaily.com/the-laptop-headset-harmony-breakthrough-solution/)
* [Configuration](https://some-guidance.techidaily.com/enhance-your-website-with-cookiebot-technology-smart-data-driven-solutions/)
* [Examples](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-30-pro-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/)

 The Windows Event Logs are a tremendous resource as they can not only help you troubleshoot current system issues, but can also provide you with warning signs of potential future problems. So keeping on top of the events your system records can be key to keeping your system running as it should. Unfortunately, sifting through the Event Logs or creating custom views can be a cumbersome manual process.

 Thankfully, we have a solution which will easily allow you to export and filter Windows Event Log entries and then have them emailed and/or saved to a text file. When this process is configured as part of a scheduled task you can have, for example, warning and error messages emailed to you automatically.

##  How It Works

 Our solution works by using a freeware utility, MyEventViewer, by Nirsoft which allows you to easily export Windows Event Logs to a comma separated file. Based on this output, we have developed an easy to configure batch script which filters these results and then can email and/or save the filtered results file. Because the results are a comma separated file, it can be opened in Excel (or your favorite CSV program) and further sorted and filtered.

##  Configuration

 The configuration settings and options are documented as inline comments in the script, however we will cover a few of them in a bit of detail here.

**Event Log Name** 

 When specifying the Event Logs you want to capture the events from, you must use the system full name of the log. This is not necessarily what you see in the Event Viewer list of logs.

 For example, if you wanted to capture events from the "Microsoft Office Alerts" log, go to the Properties dialog of the log.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image1.png) 

 Note the value in the Full Name value, in this case "OAlerts". This would be the value you would need to enter into the script's configuration.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image2.png) 

**Event Types** 

 The values for the Event Types is simply the text you see in the "Level" column when you are viewing Event Logs. Typically these are either Information, Warning or Error but various logs may have different values.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image3.png) 

**Scheduled Task Setup** 

 The typical usage of this script is most likely in an automated process. So to make sure there is no overlap between your capture interval and when the process runs, you should set up a Windows Scheduled Task to complement the capture time.

 Quite simply, if your configuration is set to capture events for the last day, you should have a scheduled task that runs once per day. If your configuration is set to capture for the last hour, your scheduled task should be set to run once every hour. Etc.

 As an additional note, in order to make sure the MyEventViewer application can get to the information it needs, the respective scheduled task should be run with administrator rights on the machine.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image4.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-creations-summary-studio-25-detailed-assessment-2023/"><u>[New] Pinnacle Creations Summary Studio 25 Detailed Assessment, 2023</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-luminosity-boost-for-low-light-mobile-video/"><u>[Updated] Luminosity Boost for Low-Light Mobile Video</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unzip-excitement-funimate-pros-apk-unwrapped/"><u>2024 Approved Unzip Excitement - Funimate Pro's APK Unwrapped</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/androids-low-cost-video-call-app-selection/"><u>Android's Low Cost Video Call App Selection</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721477462829-cant-upload-photos-to-icloud-from-iphone-try-these-9-fixes/"><u>Can't Upload Photos to iCloud From iPhone? Try These 9 Fixes!</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-locking-text-files-behind-strong-passwords/"><u>Comprehensive Tutorial on Locking Text Files Behind Strong Passwords</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-solving-teardown-application-crashes-a-complete-step-by-step-guide/"><u>Comprehensive Tutorial: Solving Teardown Application Crashes - A Complete Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-with-the-world-mastering-facebook-twitter-instagram-and-youtube-strategies/"><u>Connect with the World: Mastering Facebook, Twitter, Instagram, and YouTube Strategies</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/explore-these-15-fantastic-gratis-software-uninstallers-for-your-pc/"><u>Explore These 15 Fantastic Gratis Software Uninstallers for Your PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-ensure-optimal-performance-by-keeping-device-drivers-current-in-windows-10/"><u>How to Ensure Optimal Performance by Keeping Device Drivers Current in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-seamlessly-install-the-latest-driver-updates-for-your-devices-in-windows-11-with-revo-uninstaller/"><u>How to Seamlessly Install the Latest Driver Updates for Your Devices in Windows 11 With Revo Uninstaller</u></a></li>
<li><a href="https://video-capture.techidaily.com/screenflow-for-mac-a-full-featured-deep-dive-for-2024/"><u>ScreenFlow for Mac - A Full Featured Deep Dive for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/struggling-with-slow-iphone-screen-shutdowns-discover-proven-fixes-for-immediate-action/"><u>Struggling with Slow iPhone Screen Shutdowns? Discover Proven Fixes for Immediate Action</u></a></li>
<li><a href="https://win-forum.techidaily.com/workaround-for-windows-11-installation-tips-for-non-qualifying-cpus/"><u>Workaround for Windows 11: Installation Tips for Non-Qualifying CPUs</u></a></li>
</ul></div>

