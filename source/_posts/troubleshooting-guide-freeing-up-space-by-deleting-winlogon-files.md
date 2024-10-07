---
title: "Troubleshooting Guide: Freeing Up Space by Deleting Winlogon Files"
date: 2024-10-02T18:31:43.378Z
updated: 2024-10-06T21:21:43.342Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Winlogon Files"
excerpt: "This Article Describes Troubleshooting Guide: Freeing Up Space by Deleting Winlogon Files"
thumbnail: https://thmb.techidaily.com/42a3217d9873863c48091846f5f8a9e9b9b6456440b499628df593e7d229a025.jpg
---

## The Ultimate Troubleshooting Steps to Get Windows 11 Up and Running Again

## [How to fix Windows 11 Wont Run on my PC error](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-fix-windows-11-wont-run-on-my-pc-error/&title=How+to+fix+Windows+11+Wont+Run+on+my+PC+error)
* [](https://twitter.com/intent/tweet?text=How+to+fix+Windows+11+Wont+Run+on+my+PC+error&url=https://www.revouninstaller.com/blog/how-to-fix-windows-11-wont-run-on-my-pc-error/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[fix Windows 11 Wont Run on my PC error](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/fix-windows-11-wont-run-on-my-pc.jpg) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 June 24th was the date that Windows 11 was announced. To ease the Windows 10 user’s life, Microsoft provided a tool called PC Health Check. With this tool, the users can check if their computer is compatible with the new operating system. A lot of people were surprised once they ran the software that they received the message “This PC Can’t Run Windows 11”.

 If you were one of those users, that means that your current PC is not compatible with Windows 11 and you won’t be able to directly install it.

 There are several workarounds and if you follow this guide, we will show you how to fix the “This PC Can’t Run Windows 11” error.

## So why are you getting the “This PC Can’t Run Windows 11” error?

 When you run PC Health Check and you get the error it is probably because your PC does not meet the minimum system requirements. Check the table below to see if you cover the requirements:

| Processor                                 | 1 gigahertz (GHz) or faster with 2 or more cores on a compatible 64-bit processor or System on a Chip (SoC).                             |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| RAM                                       | 4 gigabyte (GB).                                                                                                                         |
| Storage                                   | 64 GB or larger storage device Note: See below under “More information on storage space to keep Windows 11 up-to-date” for more details. |
| System firmware                           | UEFI, Secure Boot capable. Check here for information on how your PC might be able to meet this requirement.                             |
| TPM                                       | Trusted Platform Module (TPM) version 2.0\. Check here for instructions on how your PC might be enabled to meet this requirement.        |
| Graphics card                             | Compatible with DirectX 12 or later with WDDM 2.0 driver.                                                                                |
| Display                                   | High definition (720p) display that is greater than 9″ diagonally, 8 bits per colour channel.                                            |
| Internet connection and Microsoft account | Windows 11 Home edition requires internet connectivity and a Microsoft account.                                                          |

 The majority of requirements are not so different from the Windows 10 ones and most computers can meet them. The problems with the upgrade come from the requirements for UEFI, Secure Boot, and TPM 2.0.

 Here is a list of all error messages that you can see when you run PC Health Check. If you encounter one of them, follow the solutions below to fix them:

* [This PC can’t run Windows 11. TPM 2.0 is a requirement for running Windows 11,+](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)
* [This PC can’t run Windows 11. The PC must support Secure Boot.](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)
* [This PC can’t run Windows 11. The processor isn’t supported for Windows 11.](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

## Guide 1: How to fix “This PC can’t run Windows 11\. TPM 2.0 is a requirement for running Windows 11” error

![TPM required](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide1-overview.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In this case there are 2 issues:

1. Your PC contains a TPM chip, but it is not enabled.
2. Your PC does not have a TPM chip and you won’t be able to update to Windows 11.

### How to fix the issue

1. Check if your PC supports TPM:  
   1. Step1 – Press Win Key + R. Type tpm.msc in the dialog window, and hit Enter.  
   2. Step 2 – When the TPM utility pops up, check if the chip is in use.  
    If yes, you’ll see it under the Status section, marked as The TPM is ready to use.  
   3. Step 3 – The TPM Manufacturer Information section will provide you with information about the TPM version.  
   ![TPM ready to use](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide1-step3.jpg) If it is TPM 2.0, you will be able to install and run Windows 11.If the version of TPM is not 2.0 or if it is lower, that means that you won’t be able to update to Windows 11.  
    When your computer warns “Compatible TPM cannot be found” or the TPM module version is lower than 2.0, staying with your current computer operating system will be a wise decision.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. Enable TPM 2.0 chip for Windows 11  
   1. Step 1 – Restart your PC and press the F2/F10/Del key to enter your BIOS  
   2. Step 2 – Navigate with your keyboard to the Security section.  
   3. Step 3 – Enable the TMP State  
   ![enable tpm chip](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/enable-tpm-20-chip-for-windows-11-step-3.jpg)  
   4. Step 4 – Hit the F10 key and press Enter to exit the BIOS.Restart your PC and get the Windows 11 update successfully.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Guide 2 – How to fix “This PC can’t run Windows 11\. The PC must support Secure Boot” error

![secure boot not supported](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide2-overview.png)

 Secure Boot mode is usually enabled for most modern computers. Its’ role is to keep your computer safe. In order to update to Windows 11 the Secure Boot mode needs to be enabled.

### How to enable Secure Boot

1. #### Check if your system supports Secure Boot  

   1. Press Win Key + R. Type msinfo32.exe, and hit Enter.  
   2. Select System Summary  
   3. On the right-side pane scroll down and try to find a section named Secure Boot State (as shown in the screenshot)  
   ![secure boot info](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide21-how-to-enable-secure-boot-step-3.png) If the Secure Boot State shows as “Off”, that means that your PC support Secure Boot and just follow this guide in order to enable it.If the Secure Boot State shows as “Unsupported”, that means that your computer hardware does not support Secure Boot. To fix this issue you need to check if your PC supports UEFI mode first.

<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2. #### Check if your PC supports UEFI mode  

   1. Restart your PC and press the F2/F10/Del key to enter your BIOS  
   2. Navigate to the Boot Menu. Locate the Boot Mode section and click to see if your computer supports UEFI mode.If you see a UEFI mode, that means that your PC supports this boot mode. If it is currently disabled follow the next steps to enable both UEFI and Secure Mode.Note that, if your computer doesn’t support UEFI mode, you can’t enable Secure Boot and upgrade to Windows 11.

3. #### Enable UEFI Mode and Secure Boot  

##### Enable UEFI Mode  

   1. 1. Restart your PC and press the F2/F10/Del key to enter your BIOS  
         2. Navigate to the Boot Menu. Locate the Boot Mode section and click to see if your computer supports UEFI mode.  
         ![uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide22-check-if-your-pc-supports-uefi-mode-step-2.jpg)  
         3. Select UEFI boot mode and press F10 to Save and Exit your BIOS.  
         ![select uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide23-enable-uefi-step-3.jpg)  

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##### Enable Secure Boot  

   1. 1. Restart your PC and re-enter your BIOS settings.  
         2. Navigate to the Boot Menu, select Secure Boot settings and set it to “Enabled”  
         ![enable uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide24-enable-secure-boot-step-2.jpg) Once you enable the UEFI mode and Secure Boot you can continue installing the Windows 100 update on your computer.

## Guide 3 – How to fix “This PC can’t run Windows 11\. The processor isn’t supported for Windows 11.” error

![processor not supported](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide3-overview.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This error message means that your computer processor is not included in the supported processor list.

 We’ve cover this error in a separate article that you can find[here](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

## Conclusion

 As a new operating system, every user wants to try out its’ new features. However, because there are minimum system requirements, many users receive the “This PC can’t run Windows” error. The most common reason for the message is the lack of secure boot or TPM 2.0.

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
<li><a href="https://facebook-videos.techidaily.com/updated-exploring-options-when-facebook-takes-down-my-content-for-2024/"><u>[Updated] Exploring Options When Facebook Takes Down My Content for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-transform-meetings-with-easy-to-follow-zoom-sharing-tips/"><u>[Updated] In 2024, Transform Meetings with Easy-to-Follow Zoom Sharing Tips</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-initial-glimpse-at-vectors-classifying-and-choosing-right-tech/"><u>[Updated] Initial Glimpse at Vectors Classifying and Choosing Right Tech</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/accessing-shared-media-in-facebook-messenger-how/"><u>Accessing Shared Media in Facebook Messenger How?</u></a></li>
<li><a href="https://win-forum.techidaily.com/bypassing-file-restrictions-a-how-to-for-forcing-deletes-with-revouninstaller-in-windows-1011/"><u>Bypassing File Restrictions: A How-To for Forcing Deletes with RevoUninstaller in Windows 10/11</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-implementing-revo-permission-manager-through-revouninstaller-software/"><u>Comprehensive Tutorial on Implementing Revo Permission Manager Through RevoUninstaller Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-inside-the-popularity-of-facebook-twitter-instagram-and-youtube/"><u>Connecting the World: Inside The Popularity of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/determining-your-windows-11-powershell-release-a-comprehensive-guide/"><u>Determining Your Windows 11 PowerShell Release – A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-popular-online-networks-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Exploring Popular Online Networks: A Guide to Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/guide-to-stop-receiving-amber-alerts-on-android-smartphones/"><u>Guide to Stop Receiving Amber Alerts on Android Smartphones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-add-music-to-any-snapchat-video-in-2024/"><u>How to Add Music to Any Snapchat Video, In 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-converting-vimeo-videos-to-mp3-format/"><u>In 2024, Converting Vimeo Videos to MP3 Format</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-inside-magixs-acid-pro-and-its-competitors/"><u>In 2024, Inside Magix's ACID Pro and Its Competitors</u></a></li>
<li><a href="https://win-forum.techidaily.com/locating-your-current-windows-10-powershell-edition-a-step-by-step-guide/"><u>Locating Your Current Windows 10 PowerShell Edition: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-role-of-the-windows-registry-in-system-management/"><u>Understanding the Role of the Windows Registry in System Management</u></a></li>
</ul></div>

