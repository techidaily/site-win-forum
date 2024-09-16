---
title: "Step-by-Step Guide: Resolving 'Error Occurred During Troubleshooting' In Windows 11/10"
date: 2024-09-13T16:00:58.982Z
updated: 2024-09-16T16:32:52.322Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0a1a7225cf59c67660e5517795e22301d6d92dc2445c6377515e5503eb99dcd0.jpg
---

## Step-by-Step Guide: Resolving 'Error Occurred During Troubleshooting' In Windows 11/10

### Key Takeaways

* Try launching the troubleshooter from the Settings app on your Windows 11 or 10 PC.
* Restart the "Background Intelligent Transfer Service" and "Cryptographic Services" services.
* If the issue persists, fix Windows' damaged system files with DSM and SFC, try to use the troubleshooter in safe mode, or reset your Windows PC.

 If you’ve encountered an “An error occurred while troubleshooting” error while launching a troubleshooter, worry not, as fixing this issue is easy in most cases. Here’s how to do that on your Windows 11 or Windows 10 PC.

 After applying each fix, launch your troubleshooter to check if it’s working.

##  Run the Troubleshooter From Settings

 While Windows allows you to [launch the built-in troubleshooters](https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-play-40c-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) from the Run dialog box, we recommend opening those tools from Settings, as this is where the tools are hosted.

 To do that, [open the Settings app](https://facebook-video-footage.techidaily.com/updated-2024-approved-5-easy-ways-to-multiply-your-youtube-follower-base/) by pressing Windows+i. On Windows 11, head into System > Troubleshoot > Other Troubleshooters. On Windows 10, go to Update & Security > Troubleshoot > Additional Troubleshooters.

 Find the troubleshooting tool to launch. On Windows 11, next to the troubleshooter, select "Run."

!['Run' highlighted for multiple troubleshooters in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-troubleshooter-windows-11-settings-1.jpg) 

 On Windows 10, click the troubleshooter and choose "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for a troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-troubleshooter-windows-10-settings.jpg) 

 The tool will launch.

##  Restart the Required Windows Services

 The built-in troubleshooters rely on various Windows services to function. These services might not be working correctly, causing an error. Give these services a reboot to fix the problem.

 Open the Run dialog box by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Background Intelligent Transfer Service." Right-click it and select "Restart."

!['Restart' highlighted for the 'Background Intelligent Transfer Service' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-restart-bits-service.jpg) 

 Similarly, right-click the "Cryptographic Services" service and select "Restart."

!['Restart' highlighted for the 'Cryptographic Services' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-restart-cryptographic-services-service.jpg) 

 Close the Services window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Fix Broken Troubleshooters

 It’s possible Windows’ system files are corrupted, causing the troubleshooters to malfunction. In this case, you must [repair the damaged core files](https://some-guidance.techidaily.com/twirl-forge-instruments-for-2024/) using the built-in System File Checker (SFC) tool.

 To do that, open the Start Menu, search for **Command Prompt**, and select "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-cmd-as-admin.jpg) 

 In the User Account Control"(UAC) prompt, select "Yes."

 In Command Prompt, type the following command and press Enter. This command will download the files required to fix the broken system files.

DISM.exe /Online /Cleanup-image /Restorehealth

![The DISM command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-run-dism-command-in-cmd.jpg) 

 Next up, run the following command to begin finding and repairing the damaged system files:

sfc /scannow

[Restart your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC once it finishes.

##  Launch the Troubleshooter in Safe Mode

[Safe mode on Windows](https://video-capture.techidaily.com/new-essential-scripting-instant-stopwatch-integration-in-obs-for-2024/) lets you check if third-party apps are preventing you from performing your tasks. In safe mode, Windows only loads the essential files to boot the system, letting you check for interference from any third-party programs or drivers.

 To [start your Windows 11 PC in safe mode](https://buynow-marvelous.techidaily.com/unveiling-the-strong-battery-feature-in-moto-g-power-a-tech-review-insight/), go to Settings > System > Recovery. Next to "Advanced Startup," click "Restart Now."

!['Restart Now' highlighted for 'Advanced Startup' in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-advanced-restart-windows-11.jpg) 

 To [boot your Windows 10 PC in safe mode](https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock/), head into Settings > Update & Security > Recovery. In the "Advanced Startup" section, click "Get Started."

!['Get Started' highlighted for 'Advanced Startup' in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-advanced-restart-windows-10.jpg) 

 When your PC reboots, navigate to Troubleshoot > Advanced Options > Startup Settings and select "Restart." Then, choose the number for safe mode to boot into that mode. When your PC enters safe mode, launch the troubleshooter you wanted to use.

 If the tool works, a third-party app is likely the culprit. Review the list of your installed apps and remove any suspicious ones. It’s quick and easy to [uninstall apps on Windows 11](https://youtube-docs.techidaily.com/ed-in-2024-strategies-for-using-youtube-to-boost-classroom-engagement/) and [Windows 10](https://tech-recovery.techidaily.com/top-savings-on-apple-watches-in-april/).

##  Reset Windows

 If nothing else works, you can reset your Windows 11 or Windows 10 PC to the factory defaults. Resetting the system will fix any issues related to settings or corrupted files, but it should only be used as an last resort.

 You’ll lose your installed apps when you reset your PC. You’ll have the option to keep your personal files, though.

 To [reset a Windows 11 PC](https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/), navigate to Settings > System > Recovery. Next to "Reset This PC," click "Reset PC."

!['Reset PC' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-reset-windows-11-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To [reset a Windows 10 PC](https://instagram-videos.techidaily.com/fast-and-free-strategies-for-authenticity-in-insta-circles-for-2024/), go to Settings > Update & Security > Recovery. In the "Reset This PC" section, click "Get Started."

!['Get Started' highlighted in the 'Reset This PC' section of Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-restart-windows-10-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134242/18498" target="_top" id="2134242">
  <img src="//a.impactradius-go.com/display-ad/18498-2134242" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134242/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the open window, select "Keep My Files" so Windows doesn’t delete your personal files. Then, follow the on-screen instructions to finish resetting your computer.

 Your troubleshooting tool should work once your machine is back to the default settings.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-digital-dilemma-unexpectedly-barred-content/"><u>[New] 2024 Approved Digital Dilemma Unexpectedly Barred Content</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-bringing-back-windows-photo-viewer-a-quick-guide-for-win-11-users/"><u>[New] Bringing Back Windows Photo Viewer A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-iphone-12-pro-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase iPhone 12 Pro When Its Locked Within Seconds</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-honor-magic-5-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Honor Magic 5</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-vivo-s18e-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Vivo S18e Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-improve-lost-arks-fps-and-enhance-smooth-gameplay-experience/"><u>How To Improve Lost Ark's FPS & Enhance Smooth Gameplay Experience</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Motorola Razr 40 Ultra? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leveraging-audacity-for-unparalleled-professional-recording/"><u>In 2024, Leveraging Audacity for Unparalleled Professional Recording</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-methods-for-discovering-and-deleting-aged-data-on-your-windows-11-pc/"><u>Quick Methods for Discovering and Deleting Aged Data on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/retro-tech-goes-open-source-microsofts-dos-40-from-the-late-80s-ready-to-download/"><u>Retro Tech Goes Open Source: Microsoft's DOS 4.0 From the Late '80S Ready to Download!</u></a></li>
<li><a href="https://win-forum.techidaily.com/save-big-secure-microsoft-windows-11-pro-with-an-impressive-88-price-cut/"><u>Save Big: Secure Microsoft Windows 11 Pro with an Impressive 88% Price Cut!</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-your-childs-digital-space-a-step-by-step-tutorial-for-enabling-parental-controls-in-windows-11/"><u>Secure Your Child's Digital Space: A Step-by-Step Tutorial for Enabling Parental Controls in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-items-from-clipboard-memory-in-windows-11/"><u>Step-by-Step Guide: Removing Items From Clipboard Memory in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-turning-off-microsofts-smartscreen-in-windows-10-and-8/"><u>Step-by-Step Guide: Turning Off Microsoft's SmartScreen in Windows 10 and 8</u></a></li>
</ul></div>

