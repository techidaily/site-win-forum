---
title: "Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
date: 2024-10-01T18:54:37.831Z
updated: 2024-10-07T00:02:40.024Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
excerpt: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Win 11 Memory Dumps"
thumbnail: https://thmb.techidaily.com/58d1c82f33ff87a2a49ef482dc26ca840416cdee7dcea0bf9addd82da02902e0.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The next step is to edit the Windows Registry to skip the CPU Check during Windows 11 installation

1. Open the Start Menu and in the Search Bar type “regedit”  
![regedit](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/regedit-exe.png)
2. In the Registry Editor navigate to**Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\Setup\\MoSetup**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043661/7443" target="_top" id="2043661">
  <img src="//a.impactradius-go.com/display-ad/7443-2043661" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043661/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. In the right pane, right-click and select**New -> DWORD (32-bit) Value** .  
![dword](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/dword.png)
4. Name the value “**AllowUpgradesWithUnsupportedTPMOrCPU** ” (don’t include the quotes).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click on the newly created value and enter 1 in the**Value data** filed.  
![dword value](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/edit-dword-value.jpg)
6. Click**OK** and close the registry editor.

### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-safe-no-cost-methods-for-youtube-tracks-extraction/"><u>[New] 2024 Approved Safe, No-Cost Methods for YouTube Tracks Extraction</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-elite-alternatives-to-microsofts-official-gaming-recorder/"><u>[New] Elite Alternatives to Microsoft's Official Gaming Recorder</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-cutting-edge-fb-video-ads-mastery-with-free-toolset/"><u>[Updated] 2024 Approved Cutting-Edge FB Video Ads Mastery with FREE Toolset</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-continuous-connection-avoiding-streak-breakers-on-snapchat/"><u>[Updated] In 2024, Continuous Connection Avoiding Streak Breakers on Snapchat</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-leap-into-a-bigger-view-the-new-full-screen-fb-video-trend/"><u>2024 Approved Leap Into a Bigger View The New Full-Screen FB Video Trend</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-eradicating-data-with-the-windows-10-command-line-interface/"><u>Comprehensive Tutorial: Eradicating Data with the Windows 10 Command Line Interface</u></a></li>
<li><a href="https://win-forum.techidaily.com/defend-your-data-protecting-text-file-with-simple-password-techniques-explored/"><u>Defend Your Data: Protecting Text File with Simple Password Techniques Explored</u></a></li>
<li><a href="https://win-forum.techidaily.com/determining-the-latest-powershell-version-in-windows-11-made-easy/"><u>Determining the Latest PowerShell Version in Windows 11 Made Easy</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-how-to-determine-powershell-version-on-a-windows-10-machine-easily/"><u>Discover How to Determine PowerShell Version on a Windows 10 Machine Easily</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-for-clearing-up-entire-disk-capacity-problems-on-windows-11-computers/"><u>Expert Advice for Clearing Up Entire Disk Capacity Problems on Windows 11 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-the-giants-of-online-communication-facebook-twitter-instagram-and-youtube/"><u>Explore the Giants of Online Communication: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-open-source-options-is-vlc-bound-to-beat-mpc-in-2024/"><u>Exploring Open-Source Options Is VLC Bound to Beat MPC, In 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-explore-tiktoks-1-game-bloggers-list/"><u>In 2024, Explore TikTok's #1 Game Bloggers List</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-shadowy-troubles-how-to-repair-black-screens-in-resident-evil-village-gameplay-pc/"><u>Overcoming Shadowy Troubles: How to Repair Black Screens in Resident Evil Village Gameplay (PC)</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915162683-professional-grade-program-elimination-with-revo-uninstaller-pro-latest-update/"><u>Professional-Grade Program Elimination with Revo Uninstaller Pro - Latest Update</u></a></li>
<li><a href="https://fox-that.techidaily.com/simplify-photo-management-combining-identical-person-albums-using-iphoneipad-or-mac-tools/"><u>Simplify Photo Management: Combining Identical Person Albums Using iPhone/iPad or Mac Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-social-media-giants-facebook-twitter-and-instagram-youtube/"><u>Understanding Social Media Giants: Facebook, Twitter & Instagram, YouTube</u></a></li>
</ul></div>

