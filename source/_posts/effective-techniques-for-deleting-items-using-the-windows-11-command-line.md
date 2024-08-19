---
title: Effective Techniques for Deleting Items Using the Windows 11 Command Line
date: 2024-08-18T10:59:23.415Z
updated: 2024-08-19T10:59:23.415Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Effective Techniques for Deleting Items Using the Windows 11 Command Line
excerpt: This Article Describes Effective Techniques for Deleting Items Using the Windows 11 Command Line
thumbnail: https://thmb.techidaily.com/1b366750108562524d82d4ae59a489c50fa84a81f8bcbe092ec793162bb9610d.jpg
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
![TPM required](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide1-overview.jpg)

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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
   ![enable tpm chip](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/enable-tpm-20-chip-for-windows-11-step-3.jpg)  
   4. Step 4 – Hit the F10 key and press Enter to exit the BIOS.Restart your PC and get the Windows 11 update successfully.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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

2. #### Check if your PC supports UEFI mode  

   1. Restart your PC and press the F2/F10/Del key to enter your BIOS  
   2. Navigate to the Boot Menu. Locate the Boot Mode section and click to see if your computer supports UEFI mode.If you see a UEFI mode, that means that your PC supports this boot mode. If it is currently disabled follow the next steps to enable both UEFI and Secure Mode.Note that, if your computer doesn’t support UEFI mode, you can’t enable Secure Boot and upgrade to Windows 11.

3. #### Enable UEFI Mode and Secure Boot  

##### Enable UEFI Mode  

   1. 1. Restart your PC and press the F2/F10/Del key to enter your BIOS  
         2. Navigate to the Boot Menu. Locate the Boot Mode section and click to see if your computer supports UEFI mode.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
         ![uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide22-check-if-your-pc-supports-uefi-mode-step-2.jpg)  
         3. Select UEFI boot mode and press F10 to Save and Exit your BIOS.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
         ![select uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide23-enable-uefi-step-3.jpg)  

##### Enable Secure Boot  

   1. 1. Restart your PC and re-enter your BIOS settings.  
         2. Navigate to the Boot Menu, select Secure Boot settings and set it to “Enabled”  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
         ![enable uefi mode](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide24-enable-secure-boot-step-2.jpg) Once you enable the UEFI mode and Secure Boot you can continue installing the Windows 100 update on your computer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Guide 3 – How to fix “This PC can’t run Windows 11\. The processor isn’t supported for Windows 11.” error

![processor not supported](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/fix-windows-11-wont-run/guide3-overview.jpg)

 This error message means that your computer processor is not included in the supported processor list.

 We’ve cover this error in a separate article that you can find[here](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Conclusion

 As a new operating system, every user wants to try out its’ new features. However, because there are minimum system requirements, many users receive the “This PC can’t run Windows” error. The most common reason for the message is the lack of secure boot or TPM 2.0.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-unseen-snappers-guide-the-art-of-stealthy-picture-recording/"><u>[New] 2024 Approved  Unseen Snapper's Guide  The Art of Stealthy Picture Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-a-beginners-guide-to-customizing-your-instagram-snapshonscape/"><u>[New] A Beginner's Guide to Customizing Your Instagram Snapshonscape</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-effortlessly-download-your-favorite-youtube-playlists-for-2024/"><u>[New] Effortlessly Download Your Favorite YouTube Playlists for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-top-tier-designers-making-magic-in-discord-emojis/"><u>[Updated] In 2024, Top-Tier Designers  Making Magic in Discord Emojis</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-real-time-streaming-excellence-instagram-and-obs-unite-for-2024/"><u>[Updated] Real-Time Streaming Excellence  Instagram and OBS Unite for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-inverse-photo-journey-through-facebooks-vast-web-for-2024/"><u>[Updated] The Inverse Photo Journey Through Facebook’s Vast Web for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-elevate-your-wit-crafting-memes-with-kapwing/"><u>2024 Approved  Elevate Your Wit  Crafting Memes with Kapwing</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-oppo-a1-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/camera-kings-collide-sj6-powerhouse-vs-yi-4k-masterpiece/"><u>Camera Kings Collide  SJ6 Powerhouse Vs. Yi 4K Masterpiece</u></a></li>
<li><a href="https://techtrends.techidaily.com/effortless-instructions-for-transmitting-oral-notes-with-iphones-built-in-tools-and-apps/"><u>Effortless Instructions for Transmitting Oral Notes with iPhone's Built-In Tools and Apps</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-itel-p40plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Itel P40+ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-apple-iphone-15-pro-max-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-discover-the-powershell-version-in-windows-11-essential-steps/"><u>How to Discover the PowerShell Version in Windows 11 - Essential Steps</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-find-out-which-version-of-microsoft-edge-you-are-using-a-user-friendly-guide/"><u>How to Find Out Which Version of Microsoft Edge You Are Using: A User-Friendly Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-pop-7-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Pop 7 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-update-windows-11-device-drivers-revouninstaller/"><u>How to Update Windows 11 Device Drivers - RevoUninstaller</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-directly-stream-google-meet-youtube-edition-steps/"><u>In 2024, Directly Stream Google Meet - YouTube Edition Steps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-honor-100-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Honor 100 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-registry-management-in-windows-a-complete-tutorial-on-revouninstaller-tools/"><u>Master Registry Management in Windows: A Complete Tutorial on RevoUninstaller Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-online-engagement-on-facebook-twitter-instagram-and-youtube/"><u>Mastering the Art of Online Engagement on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-windows-registry-a-deep-dive-into-its-integration-with-revo-uninstaller-tools/"><u>Mastering the Windows Registry - A Deep Dive Into Its Integration with Revo Uninstaller Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-era-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Era with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-with-leading-sites-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape with Leading Sites: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-landscape-of-digital-media-giants-facebook-twitter-instagram-and-youtube/"><u>Navigating the Landscape of Digital Media Giants: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-powerhouses-of-online-interaction-insights-on-facebook-twitter-instagram-and-youtube-strategies/"><u>Navigating the Powerhouses of Online Interaction: Insights on Facebook, Twitter, Instagram, and YouTube Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-top-platforms-in-social-networking-fb-tw-in-yt/"><u>Navigating the Top Platforms in Social Networking: FB, TW, IN, YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-worlds-largest-social-channels-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the World's Largest Social Channels: Insights on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-through-windows-11-errors-what-to-do-when-things-dont-go-as-planned/"><u>Navigating Through Windows 11 Errors: What to Do When Things Don't Go as Planned</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-unforeseen-glitches-on-your-windows-11-machine-a-step-by-step-fix-guide/"><u>Navigating Unforeseen Glitches on Your Windows 11 Machine: A Step-by-Step Fix Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-hardware-restrictions-installing-windows-11-with-revouninstaller-on-non-compatible-cpus/"><u>Overcoming Hardware Restrictions: Installing Windows 11 with RevoUninstaller on Non-Compatible CPUs</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-tricks-for-determining-the-powershell-version-on-your-windows-11-system/"><u>Quick Tricks for Determining the PowerShell Version on Your Windows 11 System</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/secrets-of-high-quality-steam-gameplay-footage-for-2024/"><u>Secrets of High-Quality Steam Gameplay Footage for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/securing-your-system-5-key-methods-to-protect-your-windows-machine/"><u>Securing Your System: 5 Key Methods to Protect Your Windows Machine</u></a></li>
<li><a href="https://win-forum.techidaily.com/simple-guide-to-clearing-out-user-profiles-on-your-windows-10-device-successfully/"><u>Simple Guide to Clearing Out User Profiles on Your Windows 10 Device Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-butterflies-go-online-mastering-interaction-on-facebook-twitter-instagram-and-youtube/"><u>Social Butterflies Go Online: Mastering Interaction on Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://fox-glue.techidaily.com/unlock-the-world-of-vr-with-your-phone-in-minutes-for-2024/"><u>Unlock the World of VR with Your Phone in Minutes for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-your-youtube-potential-expert-tips-on-writing-video-outlines-for-2024/"><u>Unlock Your YouTube Potential  Expert Tips on Writing Video Outlines for 2024</u></a></li>
</ul></div>
