---
title: Steps to Turn Off Microsoft Defender Forever in Windows 11
date: 2024-08-28T04:28:24.974Z
updated: 2024-08-29T04:28:24.974Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/windows-desktop.jpg
---

## Steps to Turn Off Microsoft Defender Forever in Windows 11

### Quick Links

* [When Should You Permanently Disable Microsoft Defender Antivirus](https://article-knowledge.techidaily.com/2024-approved-ultimate-guide-newest-lg-bp550-specs/)
* [Turn Off Real-Time Protection and Tamper Protection in the Windows Security App](https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-tecno-spark-20c-drfone-by-drfone-virtual-android/)
* [Disable Microsoft Defender Using the Registry Editor](https://screen-sharing-recording.techidaily.com/new-remote-recording-mastery-a-comprehensive-approach/)
* [Disable Microsoft Defender Using the Local Group Policy Editor](https://fox-access.techidaily.com/a-compreenas-guide-to-producing-slow-motion-content-with-photos-and-internet-for-2024/)
* [How to Check the State of Microsoft Defender on Windows 11](https://screen-mirroring-recording.techidaily.com/new-broadcast-software-beyond-standard-obs/)

### Key Takeaways

* If you want to permanently disable Microsoft Defender on Windows 11, you’ll first need to disable Real-time protection and Tamper protection in the Windows Security app.
* Windows Home users can use the Registry Editor to turn off Microsoft Defender. Windows Pro users have the option to do it through either the Registry Editor or the Local Group Policy Editor.
* You can determine whether Microsoft Defender is currently disabled by running the "Get-MpComputerStatus | select AMRunningMode" command in Windows PowerShell.

 Windows built-in security app, Microsoft Defender, protects your computer from malicious agents and viruses. However, there may be situations when you want to disable it, such as when testing a third-party security app. We'll show you how to permanently disable Microsoft Defender on Windows 11.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
##  When Should You Permanently Disable Microsoft Defender Antivirus 

 Microsoft Defender Antivirus provides various protection features, including real-time protection, cloud-delivered protection, network protection, and more. When you disable Microsoft Defender, you lose access to all these protections, leaving your computer at risk.

 Generally, you should avoid disabling Microsoft Defender Antivirus. However, if the need arises—for example, when you need to install an application that Defender is blocking—you can [temporarily turn it off](https://tech-renaissance.techidaily.com/what-is-the-difference-between-an-ipad-and-a-tablet/). To do so, [turn off Real-time protection](https://desktop-recording.techidaily.com/new-record-gameplay-in-samsung-galaxy-phones-for-2024/) in the Windows Security app, install the application, and then re-enable Real-time protection.

![Real-time Protection toggle disabled in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/real-time-protection-toggle-disabled-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Additionally, if you intend to permanently disable Defender Antivirus to install a third-party security application, you must reconsider your choice. This is because when you install a compatible [non-Microsoft antivirus program](https://video-capture.techidaily.com/2024-approved-nvidia-game-capturer-simple-gaming-sessions/), Microsoft Defender antivirus will automatically disable itself. Compatible non-Microsoft antivirus programs are those that do not cause any issues when installed alongside Windows Defender.

 Luckily, there are numerous [antivirus programs](https://facebook-video-recording.techidaily.com/in-2024-access-high-res-fb-media-files/) that are compatible with Microsoft. To verify compatibility, you should check the antivirus program’s user manual or inquire with the seller.

 However, if you wish to install a security program that is not compatible with Microsoft, you will need to disable Microsoft Defender Antivirus permanently.

 Now that you know when you should and should not permanently disable Microsoft Defender, let’s check out how you can permanently disable Microsoft Defender on Windows 11.

##  Turn Off Real-Time Protection and Tamper Protection in the Windows Security App

 Unlike temporarily disabling Microsoft Defender Antivirus, permanently disabling it isn’t straightforward. First, you’ll need to disable Real-time and Tamper Protection in the Windows Security app.

 Disabling Real-time protection ensures that Microsoft Defender won’t scan any files on your computer. And disabling [Tamper Protection](https://some-techniques.techidaily.com/in-2024-harnessing-funimates-downloading-prowess-quickly/) allows you to make changes to the Microsoft Defender antivirus settings on your computer, which otherwise wouldn’t be possible. To turn off these settings, open the Start menu, type **Windows Security** in the search bar, and hit Enter.

![Typing Windows Security in the Start Menu search bar.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/typing-windows-defender-in-the-start-menu-search-bar.jpg) 

 Choose "Virus & Threat Protection" from the left sidebar, then click "Manage Settings" on the right.

![Virus & Threat Protection option in the Windows Security App.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/virus-threat-protection-option-in-the-windows-security-app.jpg) 

 Turn off the “Real-Time Protection” toggle. If UAC pops up, click “Yes” to confirm your decision.

![Real-time Protection toggle in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/real-time-protection-toggle-in-the-windows-security-app.jpg) 

 Next, disable the “Tamper Protection” toggle. Click “Yes” when the UAC prompt appears.

![Tamper Protection toggle in the Windows Security app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/tamper-protection-toggle-in-the-windows-security-app.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
 Once you’ve adjusted these settings in the Windows Security app, you’re all set to disable Microsoft Defender Antivirus on Windows 11 permanently.

##  Disable Microsoft Defender Using the Registry Editor

 If you have Windows 11 Home installed on your computer, you can use the Registry Editor to disable Microsoft Defender permanently.

 Editing the registry is risky, as one wrong move can make your system unstable. As a precautionary measure, be sure to [back up the registry](https://screen-recording.techidaily.com/quick-start-guide-dells-simple-screen-recording-methods-for-2024/) and [create a restore point](https://instagram-video-files.techidaily.com/updated-in-2024-multiplying-joy-sharing-a-pile-of-photos-and-videos-with-instagram/). This way, you can [restore your computer](https://article-posts.techidaily.com/in-2024-proven-methods-to-infuse-engaging-dialogue-in-videos/) to a working state in case something goes wrong.

 Open the Start menu, type **Registry Editor** in the search bar, and hit Enter. Then, in the Registry Editor, navigate to the following path:

        `Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
    
 Right-click the “Windows Defender” key in the left sidebar, hover over “New,” and choose “DWORD (32-bit) Value”.

![Windows Defender Key in the Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/windows-defender-key-in-the-registry-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Name the value “DisableAntiSpyware.” Then, double-click the “DisableAntiSpyware” value, type **1** in the “Value Data” field, and click “OK.”

![Value Data field in the Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/value-data-field-in-the-registry-editor.jpg) 

 After that, [restart your computer](https://instagram-clips.techidaily.com/2024-approved-15-must-use-hashtags-for-popularity-on-instagram-feed/) for the changes to take effect. Upon restart, you’ll see that Microsoft Defender has been permanently disabled on your computer.

 To reenable Microsoft Defender Antivirus, type **0** in the “Value Data” field of the “DisableAntiSpyware” value and click “OK.” Afterward, you’ll need to enable “Real-time Protection” and “Tamper Protection” in the Windows Security app, too. 

![Enabling Windows Defender through Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/enabling-windows-defender-through-registry-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
##  Disable Microsoft Defender Using the Local Group Policy Editor

 If you are a Windows 11 Pro user, you have an additional option to permanently disable Microsoft Defender. While you can use the Registry Editor for this process, as a Pro user, you also have the option to use Local Group Policy Editor.

 Press Win+R to open the Run tool. Then, type **gpedit.msc** in the search field and click “OK.”

![Gpedit.msc command in the Run tool.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/gpedit-msc-command-in-the-run-tool.jpg) 

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
 In the Local Group Policy Editor window, navigate to the following location:

        `Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Antivirus`
    
 Double-click the “Turn Off Microsoft Defender Antivirus” policy.

![Turn Off Microsoft Defender Antivirus policy in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/turn-off-microsoft-defender-antivirus-policy-in-the-local-group-policy-editor.jpg) 

 In the Edit window, choose “Enabled.” Then, click “Apply” and “OK” to save the changes.

![Enabled option in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/enabled-option-in-the-local-group-policy-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 That’s it! Restart your computer, and you’ll see that Microsoft Defender is disabled.

 If you want to enable Microsoft Defender in the future, set the “Turn Off Microsoft Defender Antivirus” policy to “Disable.” After that, turn on the “Real-time Protection” and “Tamper Protection” toggles in the Windows Security app."

![Disabled option in the Local Group Policy Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/disabled-option-in-the-local-group-policy-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Check the State of Microsoft Defender on Windows 11

 Once you’ve disabled Microsoft Defender using the above method, you must check its state to confirm if it has actually been disabled. To do this, open the Start menu, type **PowerShell** in the search bar, and press Enter. Then, in the PowerShell window, type the following command and hit Enter:

        `Get-MpComputerStatus | select AMRunningMode`
    
 If you get “Not Running” as the result, then it confirms that you have disabled Microsoft Defender.

![PowerShell window showing Not Running in result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/powershell-window-showing-not-running-in-result.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 However, if you get “Normal” as the result, it means Microsoft Defender is still running on your computer. In this case, double-check that you followed the steps correctly.

![PowerShell window showing Normal in result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/powershell-window-showing-normal-in-result.jpg) 

---

 Microsoft opted for the longer process to permanently disable Microsoft Defender instead of providing a one-click button to ensure computer safety. Even though it might be tempting, you really should disable it unless you absolutely need to.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-your-guide-to-the-most-hilarious-tear-jerking-ig-memes/"><u>[New] 2024 Approved  Your Guide to The Most Hilarious, Tear-Jerking IG Memes</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-concealed-video-streaming-background-youtube-watch/"><u>[New] Concealed Video Streaming  Background YouTube Watch</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-6-choices-in-helmet-integrated-gopro-systems-explained/"><u>[Updated] Top 6 Choices in Helmet-Integrated GoPro Systems Explained</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-streamers-checklist-secure-video-ad-revenue/"><u>2024 Approved  Streamer's Checklist  Secure Video Ad Revenue</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/breaking-boundaries-with-eizos-spectaculous-cg318-4k/"><u>Breaking Boundaries with EIZO's Spectaculous CG318-4K</u></a></li>
<li><a href="https://win-forum.techidaily.com/bypass-limits-how-to-get-windows-11-working-on-unsupported-chips-via-revouninstaller/"><u>Bypass Limits: How to Get Windows 11 Working on Unsupported Chips via RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-one-post-at-a-time-insights-on-facebook-twitter-instagram-and-youtube/"><u>Connecting the World One Post at a Time: Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhancing-engagement-with-dynamic-text-on-instagram/"><u>Enhancing Engagement with Dynamic Text on Instagram</u></a></li>
<li><a href="https://win-forum.techidaily.com/ensuring-your-programs-run-as-an-admin-on-windows-11-a-complete-how-to/"><u>Ensuring Your Programs Run as an Admin on Windows 11 - A Complete How-To</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-digital-hubs-for-connectivity-unveiling-facebook-twitter-instagram-and-youtube/"><u>Essential Digital Hubs for Connectivity: Unveiling Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/experiencing-a-red-display-error-heres-how-you-can-successfully-fix-it/"><u>Experiencing a Red Display Error? Here's How You Can Successfully Fix It</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-techniques-to-delete-foldersfiles-with-powershell-or-command-prompt-on-windows-11/"><u>Expert Techniques to Delete Folders/Files with PowerShell or Command Prompt on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-to-resolve-continuous-windows-explorer-failures-7-fixes/"><u>Expert Tips to Resolve Continuous Windows Explorer Failures (7 Fixes)</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-big-4-in-social-media-an-insight-into-facebook-twitter-instagram-and-youtube/"><u>Exploring the Big 4 in Social Media - An Insight Into Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915271217-facebook-to-youtube-a-comprehhemic-view-on-the-leading-social-networks-of-our-time/"><u>Facebook to Youtube: A Comprehhemic View on the Leading Social Networks of Our Time.</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fluxvideoart-compile-and-display-on-macos-sierra/"><u>FluxVideoArt  Compile & Display on macOS Sierra</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-erase-crashdump-files-from-your-windows-11-pc-a-comprehensive-guide/"><u>How To Erase Crashdump Files From Your Windows 11 PC: A Comprehensive Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-7-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone 7 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-samsung-galaxy-f15-5g-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Samsung Galaxy F15 5G Phone Pattern Lock</u></a></li>
<li><a href="https://win-forum.techidaily.com/leading-platforms-of-digital-expression-facebook-twitter-instagram-and-youtube/"><u>Leading Platforms of Digital Expression - Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/lenovo-thinkpad-x1-titanium-yoga-the-ultimate-2-in-one-laptop-for-fans-of-the-iconic-thinkpad-line/"><u>Lenovo ThinkPad X1 Titanium Yoga - The Ultimate 2-In-One Laptop for Fans of the Iconic ThinkPad Line</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-technique-of-forced-folder-removal-on-windows-operating-systems/"><u>Master the Technique of Forced Folder Removal on Windows Operating Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-digital-engagement-with-top-platforms-facebook-twitter-instagram-and-youtube/"><u>Mastering Digital Engagement with Top Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-social-media-strategies-for-successful-presence-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Big Four of Social Media - Strategies for Successful Presence on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-a-dive-into-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape: A Dive Into Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915306397-navigating-the-giants-of-social-networking-fb-twtr-igtv-and-gotube/"><u>Navigating the Giants of Social Networking: FB, TWTR, IGTV, and GoTube!</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-sphere-insights-into-facebook-twittersphere-and-instagram-against-youtube/"><u>Navigating the Social Sphere: Insights Into Facebook, Twittersphere & Instagram Against YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-web-of-social-interaction-facebook-twitter-instagram-youtube-insights/"><u>Navigating the Web of Social Interaction: Facebook, Twitter, Instagram, Youtube Insights</u></a></li>
<li><a href="https://win-forum.techidaily.com/protect-your-privacy-removing-tracking-cookies-from-windows-11-and-android-devices-easily/"><u>Protect Your Privacy: Removing Tracking Cookies From Windows 11 & Android Devices Easily</u></a></li>
<li><a href="https://extra-information.techidaily.com/quantum-hdr-101-a-complete-breakdown/"><u>Quantum HDR 101  A Complete Breakdown</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-guide-mastering-forced-closure-of-windows-programs-with-revo-uninstaller/"><u>Quick Guide: Mastering Forced Closure of Windows Programs with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-my-pc-cannot-launch-windows-11-comprehensive-troubleshooting-tutorial/"><u>Resolving 'My PC Cannot Launch Windows 11': Comprehensive Troubleshooting Tutorial</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-quartet-understanding-facebook-twitter-instagram-and-youtubes-impact/"><u>The Quintessential Quartet: Understanding Facebook, Twitter, Instagram & YouTube's Impact</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-media-mix-harnessing-facebook-twitter-instagram-and-youtube-for-success/"><u>The Quintessential Social Media Mix: Harnessing Facebook, Twitter, Instagram & YouTube for Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-verdict-on-revo-uninstaller-and-alternatives-for-thorough-application-removal/"><u>The Verdict on Revo Uninstaller and Alternatives for Thorough Application Removal</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-the-class-registration-error-on-your-pc-expert-tips-and-tricks/"><u>Troubleshooting the 'Class Registration Error' On Your PC: Expert Tips & Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-giants-of-social-media-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Understanding the Giants of Social Media: A Look at Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-giants-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Understanding the Giants: A Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://driver-install.techidaily.com/victory-over-startech-drivers-on-windows-7-and-11-platforms/"><u>Victory Over StarTech Drivers on Windows 7 & 11 Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/your-ultimate-guide-to-popular-online-hubs-twitter-instagram-facebook-and-youtube/"><u>Your Ultimate Guide to Popular Online Hubs: Twitter, Instagram, Facebook & Youtube</u></a></li>
</ul></div>
