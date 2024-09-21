---
title: "DIY Windows Alerts: Setting Up an Easy Event Log Notification Tool"
date: 2024-09-16T16:45:48.143Z
updated: 2024-09-21T16:08:27.570Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-fbs-viral-hits-decoded-crafting-your-number-one-song-video/"><u>[Updated] 2024 Approved FB's Viral Hits Decoded Crafting Your Number One Song Video</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-your-guide-to-facebook-video-angle-selection/"><u>[Updated] 2024 Approved Your Guide to Facebook Video Angle Selection</u></a></li>
<li><a href="https://extra-resources.techidaily.com/10plus-top-tips-for-accessing-the-best-of-international-cricket-online-for-2024/"><u>10+ Top Tips for Accessing the Best of International Cricket Online for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/achieve-creative-excellence-discover-movavis-premium-media-solutions-today/"><u>Achieve Creative Excellence - Discover Movavi's Premium Media Solutions Today!</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-powerpoint-outputs-9-steps-for-windows-users/"><u>Achieving Flawless PowerPoint Outputs: 9 Steps for Windows Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/convert-avi-files-to-swf-format-at-no-cost-with-movavis-tool/"><u>Convert AVI Files to SWF Format at No Cost with Movavi's Tool</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortless-simpel-high-quality-video-editing-with-movavi-tool/"><u>Effortless Simpel: High-Quality Video Editing with Movavi Tool</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/master-social-media-youtube-to-facebook-links-for-2024/"><u>Master Social Media YouTube to Facebook Links for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/revive-your-iphone-essential-dfu-troubleshooting-for-common-problems-5/"><u>Revive Your iPhone: Essential DFU Troubleshooting for Common Problems (#5)</u></a></li>
</ul></div>

