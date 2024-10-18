---
title: "Command Line Mastery: How to Delete Directories and Files on Windows 11 with PowerShell or CMD"
date: 2024-10-11T16:06:26.101Z
updated: 2024-10-18T16:37:52.271Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: "This Article Describes Command Line Mastery: How to Delete Directories and Files on Windows 11 with PowerShell or CMD"
excerpt: "This Article Describes Command Line Mastery: How to Delete Directories and Files on Windows 11 with PowerShell or CMD"
thumbnail: https://thmb.techidaily.com/b1dca77248729ae79ab1361747a38e85586597f7f453dbe6b343c97f8212615b.jpg
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
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
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
2. Enable TPM 2.0 chip for Windows 11  
   1. Step 1 – Restart your PC and press the F2/F10/Del key to enter your BIOS  
   2. Step 2 – Navigate with your keyboard to the Security section.  
   3. Step 3 – Enable the TMP State  
   ![enable tpm chip](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/enable-tpm-20-chip-for-windows-11-step-3.jpg)  
   4. Step 4 – Hit the F10 key and press Enter to exit the BIOS.Restart your PC and get the Windows 11 update successfully.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

         ![select uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide23-enable-uefi-step-3.jpg)  

##### Enable Secure Boot  

   1. 1. Restart your PC and re-enter your BIOS settings.  
         2. Navigate to the Boot Menu, select Secure Boot settings and set it to “Enabled”  
         ![enable uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide24-enable-secure-boot-step-2.jpg) Once you enable the UEFI mode and Secure Boot you can continue installing the Windows 100 update on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Guide 3 – How to fix “This PC can’t run Windows 11\. The processor isn’t supported for Windows 11.” error

![processor not supported](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide3-overview.jpg)

 This error message means that your computer processor is not included in the supported processor list.

 We’ve cover this error in a separate article that you can find[here](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111967/7443" target="_top" id="2111967">
  <img src="//a.impactradius-go.com/display-ad/7443-2111967" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111967/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-the-art-of-virtual-environments-in-cinema/"><u>[Updated] 2024 Approved The Art of Virtual Environments in Cinema</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-guide-to-troubleshoot-idt-high-quality-sound-drivers-in-windows-11/"><u>Comprehensive Guide to Troubleshoot IDT High-Quality Sound Drivers in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/delete-kernel-or-full-memory-dumps-from-windows-11-systematically/"><u>Delete Kernel or Full Memory Dumps From Windows 11 Systematically</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-influencers-at-play-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Digital Influencers at Play: Navigating Through Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-for-resolving-task-unsuccessful-errors-in-microsofts-latest-operating-system/"><u>Expert Tips for Resolving 'Task Unsuccessful' Errors in Microsoft's Latest Operating System</u></a></li>
<li><a href="https://some-techniques.techidaily.com/first-frame-wins-fundamental-cinematography-for-newcomers-for-2024/"><u>First Frame Wins Fundamental Cinematography for Newcomers for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-erase-iphone-15-pro-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Erase iPhone 15 Pro When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-the-enhancements-in-windows-11-unveiled/"><u>In 2024, The Enhancements in Windows 11 Unveiled</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximize-connections-streamlined-menu-for-linkedin-facebook-and-youtube-instant-page-navigation-to-top/"><u>Maximize Connections: Streamlined Menu for LinkedIn, Facebook, and YouTube | Instant Page Navigation to Top</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/the-ultimate-guide-safest-and-most-efficient-way-to-link-your-iphone-with-pc-for-seamless-file-sharing-free-software/"><u>The Ultimate Guide: Safest & Most Efficient Way to Link Your iPhone with PC for Seamless File Sharing (Free Software)</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809008145-top-tips-for-optimizing-menu-functionality-on-leading-networks-learn-to-efficiently-scroll-and-manage-content-on-facebook-linkedin-and-youtube/"><u>Top Tips for Optimizing Menu Functionality on Leading Networks – Learn to Efficiently Scroll & Manage Content on Facebook, LinkedIn, and YouTube</u></a></li>
</ul></div>

