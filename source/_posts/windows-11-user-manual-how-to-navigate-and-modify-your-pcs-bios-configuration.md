---
title: "Windows 11 User Manual: How To Navigate and Modify Your PC's BIOS Configuration"
date: 2024-10-12T16:41:12.589Z
updated: 2024-10-18T16:07:15.495Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Windows 11 User Manual: How To Navigate and Modify Your PC's BIOS Configuration"
excerpt: "This Article Describes Windows 11 User Manual: How To Navigate and Modify Your PC's BIOS Configuration"
thumbnail: https://thmb.techidaily.com/b891766f2e74dbdf20c5f444f013e0eb25d6a2a5da6255104df4cb09d08d4f81.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).
5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/n-2024-the-in-depth-technique-for-formulating-youtube-playlists/"><u>[New] In 2024, The In-Depth Technique for Formulating YouTube Playlists</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-quick-fixes-addressing-top-youtube-short-challenges/"><u>[New] Quick Fixes Addressing Top YouTube Short Challenges</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-quickcapture-plus-voice-guided-session-maker/"><u>2024 Approved QuickCapture + Voice-Guided Session Maker</u></a></li>
<li><a href="https://win-forum.techidaily.com/breaking-the-rules-unsupported-cpu-compatibility-with-windows-11-installation-explained/"><u>Breaking the Rules: Unsupported CPU Compatibility with Windows 11 Installation Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-determine-your-windows-10s-powershell-compatibility-and-version/"><u>Easy Steps to Determine Your Windows 10'S PowerShell Compatibility and Version</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-with-influential-networking-hubs-instagram-youtube-facebook-twitter/"><u>Engage with Influential Networking Hubs: Instagram, YouTube, Facebook, Twitter</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-giants-of-social-networking-instagram-twitter-facebook-and-youtube/"><u>Exploring the Giants of Social Networking: Instagram, Twitter, Facebook & YouTube</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-many-attempts-to-unlock-apple-iphone-14-plus-by-drfone-ios/"><u>How Many Attempts To Unlock Apple iPhone 14 Plus</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/powerful-language-in-marketing-the-20-must-know-phrases-for-2024/"><u>Powerful Language in Marketing - The 20 Must-Know Phrases for 2024</u></a></li>
<li><a href="https://fox-metric.techidaily.com/quick-access-choices-mastering-the-shortcuts-dialog-box/"><u>Quick Access Choices: Mastering the Shortcuts Dialog Box</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-file-deletion-using-command-prompt-on-windows-11/"><u>Step-by-Step Guide: File Deletion Using Command Prompt on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-mastering-the-art-of-forcible-application-termination-in-windows-11/"><u>Ultimate Guide: Mastering the Art of Forcible Application Termination in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-starting-your-sound-journey-right-2023s-top-6-affordable-daw-tools-for-beginners/"><u>Updated 2024 Approved Starting Your Sound Journey Right 2023S Top 6 Affordable DAW Tools for Beginners</u></a></li>
</ul></div>

