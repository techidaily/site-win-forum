---
title: "Troubleshooting Windows 11: Solutions for Wont Run Issues"
date: 2024-09-05T07:55:59.285Z
updated: 2024-09-06T07:55:59.285Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Troubleshooting Windows 11: Solutions for Wont Run Issues"
excerpt: "This Article Describes Troubleshooting Windows 11: Solutions for Wont Run Issues"
thumbnail: https://thmb.techidaily.com/61c513946ca67c4ebe171c06eca13adeadd0c93b5bf89d5e42f26ac56570469b.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

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
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## So how can you install Windows 11 if your processor is not supported?

### Download the Windows 11 ISO

 This is a very important step. If you use the Windows 11 Install Assistant, this method won’t work.

1. Go to the[Microsoft page](https://www.microsoft.com/en-us/software-download/windows11?ranMID=24542&ranEAID=nOD/rLJHOac&ranSiteID=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&epi=nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&tduid=%28ir%5F%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00%29%287593%29%281243925%29%28nOD%5FrLJHOac-42vlJMwQgDDSJ5XfoWPeBA%29%28%29&irclickid=%5Fzpv3mpuozckfqijnkk0sohz3we2xobwf0ymxujdc00) and scroll down to**Download Windows 11 Disk Image (ISO)** .
2. Open the**Select Download** dropdown. Click on**Windows 11** and hit the**Download** button.
3. Select your desired product language and click**Confirm** .
4. Finally, click**64-bit Download** .

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
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-sparking-inspiration-outstanding-youtube-content-themes/"><u>[New] 2024 Approved  Sparking Inspiration  Outstanding YouTube Content Themes</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-unleashing-video-magic-on-tiktok-with-pre-made-designs/"><u>[New] 2024 Approved  Unleashing Video Magic on TikTok with Pre-Made Designs</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-a-comprehensive-list-of-top-virtual-classrooms-not-inspired-by-udemy-for-2024/"><u>[New] A Comprehensive List of Top Virtual Classrooms Not Inspired by Udemy for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-6-youtuber-quizzes-to-know-which-youtuber-you-are/"><u>[New] In 2024, 6 YouTuber Quizzes to Know Which YouTuber You Are</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagrams-audio-alteration-the-ultimate-guide/"><u>[Updated] 2024 Approved  Instagram's Audio Alteration  The Ultimate Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-direct-engagement-broadcast-from-twitch-to-facebook-friends-for-2024/"><u>[Updated] Direct Engagement  Broadcast From Twitch to Facebook Friends for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-sketches-to-screens-animation-via-windows-movie-maker/"><u>[Updated] From Sketches to Screens  Animation via Windows Movie Maker</u></a></li>
<li><a href="https://win-forum.techidaily.com/addressing-windows-11-booting-problem-comprehensive-fixes-and-tips/"><u>Addressing 'Windows 11 Booting Problem': Comprehensive Fixes and Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/avoiding-trouble-undoing-the-latest-windows-11-software-changes/"><u>Avoiding Trouble: Undoing the Latest Windows 11 Software Changes</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-online-with-leading-sites-facebook-twitter-instagram-and-youtube-journey/"><u>Connect Online with Leading Sites: Facebook, Twitter, Instagram and YouTube Journey</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-methods-to-lockdown-your-text-files-using-passwords/"><u>Easy Methods to Lockdown Your Text Files Using Passwords</u></a></li>
<li><a href="https://win-forum.techidaily.com/elevate-your-pc-maintenance-using-revouninstaller-pro-latest-edition-insights/"><u>Elevate Your PC Maintenance Using RevoUninstaller Pro - Latest Edition Insights</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-writing-workflow-using-advanced-ai-techniques/"><u>Elevate Your Writing Workflow Using Advanced AI Techniques</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-for-effective-use-of-command-prompt-to-remove-files-on-windows-11/"><u>Expert Tips for Effective Use of Command Prompt to Remove Files on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-social-media-giants-delve-into-facebook-twitter-instagram-and-youtubes-universe/"><u>Explore Social Media Giants: Delve Into Facebook, Twitter, Instagram & YouTube's Universe</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-what-the-windows-registry-is-and-how-revo-uninstaller-helps-manage-it/"><u>Exploring What the Windows Registry Is and How Revo Uninstaller Helps Manage It</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-altering-erasing-and-building-registry-keys-via-the-revouninstaller-tool/"><u>Guide to Altering, Erasing, and Building Registry Keys via the RevoUninstaller Tool</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-disable-unwanted-updates-in-windows-11-for-a-smooth-experience/"><u>How To Disable Unwanted Updates in Windows 11 for a Smooth Experience</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-safeguard-your-windows-system-with-these-5-tips/"><u>How to Safeguard Your Windows System with These 5 Tips</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-mastering-the-art-of-screen-sharing-in-zoom/"><u>In 2024, Mastering the Art of Screen Sharing in Zoom</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-oppo-k11x-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Oppo K11x FRP Bypass</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigate-major-social-platforms-engage-with-facebook-twitter-post-to-instagram-and-create-content-for-youtube/"><u>Navigate Major Social Platforms: Engage with Facebook, Twitter, Post to Instagram & Create Content for Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-biggest-networking-sites-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the Biggest Networking Sites: A Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-with-leading-sites-socialnet-facebook-microblog-twitter-photospace-instagram-and-videohub-youtube/"><u>Navigating the Digital Landscape with Leading Sites: SocialNet Facebook, MicroBlog Twitter, PhotoSpace Instagram & VideoHub YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-digital-conversations-across-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Digital Conversations Across Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915399478-navigating-the-world-of-social-media-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Social Media with Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/reset-your-windows-11-device-a-comprehensive-walkthrough/"><u>Reset Your Windows 11 Device - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-print-hang-up-swiftly/"><u>Resolve Print Hang-Up Swiftly</u></a></li>
<li><a href="https://win-forum.techidaily.com/revamp-your-pcs-performance-with-windows-11-driver-updates/"><u>Revamp Your PC's Performance with Windows 11 Driver Updates</u></a></li>
<li><a href="https://win-forum.techidaily.com/revouninstaller-tutorial-for-efficient-computer-maintenance-defragmenting-your-drive-in-windows-10/"><u>RevoUninstaller Tutorial for Efficient Computer Maintenance: Defragmenting Your Drive in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-powerhouses-unveiling-the-secrets-of-facebook-twitter-instagram-and-youtube/"><u>Social Media Powerhouses: Unveiling the Secrets of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915368124-social-networking-giants-exploring-facebook-twitter-instagram-and-youtube/"><u>Social Networking Giants: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-mix-fold-3-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Mix Fold 3</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-setting-up-and-enabling-the-revo-uninstaller-app-on-your-smartphone/"><u>Step-by-Step Guide: Setting Up & Enabling the Revo Uninstaller App on Your Smartphone</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-social-networking-facebook-twitter-instagram-and-youtube-explained/"><u>The Big Four of Social Networking - Facebook, Twitter, Instagram, and YouTube Explained!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-next-generation-apple-watch-ultra-unveiled-anticipated-costs-launch-timeline-and-latest-leaks/"><u>The Next Generation Apple Watch Ultra Unveiled? Anticipated Costs, Launch Timeline & Latest Leaks</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-social-media-engage-on-facebook-tweet-on-twitter-post-on-instagram-stream-on-youtube/"><u>The Power of Social Media: Engage on Facebook, Tweet on Twitter, Post on Instagram, Stream on Youtube</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-itel-a60-frp-by-drfone-android/"><u>The Updated Method to Bypass Itel A60 FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-cloud-glitch-on-windows/"><u>Troubleshooting Steam Cloud Glitch on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-troubleshooting-your-lenovo-laptops-malfunctioning-webcam/"><u>Ultimate Guide: Troubleshooting Your Lenovo Laptop's Malfunctioning Webcam</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-full-control-ensuring-your-applications-run-with-admin-access-every-time-on-windows-nul-11/"><u>Unlock Full Control: Ensuring Your Applications Run with Admin Access Every Time on Windows Nul 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-system-secrets-a-beginners-guide-to-bios-entry-on-windows-11-computers/"><u>Unlocking System Secrets: A Beginner's Guide to BIOS Entry on Windows 11 Computers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-everyday-moments-epic-movies-the-power-of-video-editing/"><u>Updated Everyday Moments, Epic Movies The Power of Video Editing</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-10-file-management-delete-multiple-items-using-cmd-instructions/"><u>Windows 10 File Management: Delete Multiple Items Using CMD Instructions</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-space-saver-a-guide-to-boosting-performance-by-freeing-disk-space/"><u>Windows 11 Space Saver: A Guide to Boosting Performance by Freeing Disk Space</u></a></li>
</ul></div>
