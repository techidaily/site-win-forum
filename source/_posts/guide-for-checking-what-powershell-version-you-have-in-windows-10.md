---
title: Guide for Checking What PowerShell Version You Have in Windows ‪‬10
date: 2024-08-18T10:35:53.836Z
updated: 2024-08-19T10:35:53.836Z
tags:
  - win11
  - win10
  - win7
categories:
  - tips
description: This Article Describes Guide for Checking What PowerShell Version You Have in Windows ‪‬10
excerpt: This Article Describes Guide for Checking What PowerShell Version You Have in Windows ‪‬10
thumbnail: https://thmb.techidaily.com/05054cfe506491b99a35f8cf834debaebdbdb9bad3863dd1f8be14d01cc17569.jpg
---

## Windows 11 Upgrade Troubles? Here's How You Can Install It on Non-Compatible Processors

## [How to install Windows 11 on unsupported CPUs](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

* Share
* [](http://www.facebook.com/share.php?u=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/&title=How+to+install+Windows+11+on+unsupported+CPUs)
* [](https://twitter.com/intent/tweet?text=How+to+install+Windows+11+on+unsupported+CPUs&url=https://www.revouninstaller.com/blog/how-to-install-windows-11-on-unsupported-cpus/ "Click to share on Twitter")
* [](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

[install Windows 11 on unsupported CPUs](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/blog/install-windows-unsupported-cpu/how-to-install-windows-11-on-unsupported-cpu.png) ](https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1)

 Windows 11 finally arrived this October. Unfortunately, not everyone is happy with the arrival of the latest update. The problem is that not every processor supports Windows 11\. The issue comes to life because not every device has a Trusted Platform Module (TPM) 2.0 crypto processor.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The final step is the following

 Remember the Windows 11 ISO that you started downloading at the beginning of this article?

1. Right-click on it and select**Open with -> Windows Explorer** to mount the virtual disc.
2. Double-click the setup file to begin the Windows 11 installation.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## Summary

 If you’ve followed all the steps, you should see a warning message that your CPU is not “the perfect match” for Windows 11, but you will be allowed to install it on your PC. **Just keep in mind that Microsoft reserves the right to stop your security updates if you decide to use this method** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![icon of revo uninstaller pro](https://f057a20f961f56a72089-b74530d2d26278124f446233f95622ef.ssl.cf1.rackcdn.com/site/icons/rup5-64.png)

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
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
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-turbocharging-your-instagram-footage/"><u>2024 Approved  Turbocharging Your Instagram Footage</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-beginners-tutorial-making-the-most-out-of-revoapp-manager/"><u>A Beginner's Tutorial: Making the Most Out of RevoApp Manager</u></a></li>
<li><a href="https://win-forum.techidaily.com/command-line-mastery-how-to-delete-directories-and-files-on-windows-11-with-powershell-or-cmd/"><u>Command Line Mastery: How to Delete Directories and Files on Windows 11 with PowerShell or CMD</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-walkthrough-installing-and-using-the-revo-application-manager/"><u>Comprehensive Walkthrough: Installing and Using the Revo Application Manager</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-facebook-twitter-instagram-and-youtube/"><u>Connect and Share on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-globally-understanding-the-impact-of-facebook-twitter-instagram-and-youtube/"><u>Connecting Globally: Understanding the Impact of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-dots-in-social-media-understanding-facebook-twitter-instagram-and-youtubes-impact/"><u>Connecting the Dots in Social Media: Understanding Facebook, Twitter, Instagram and YouTube's Impact</u></a></li>
<li><a href="https://win-forum.techidaily.com/demystifying-bios-functionality-enhanced-by-revo-uninstaller-tools/"><u>Demystifying BIOS Functionality Enhanced by Revo Uninstaller Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/demystifying-digital-giants-essential-insights-on-facebook-twitter-instagram-and-youtube/"><u>Demystifying Digital Giants: Essential Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-the-world-of-social-networking-with-facebook-twitter-instagram-and-youtube/"><u>Discover the World of Social Networking with Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-and-effective-ways-to-update-drivers-on-a-windows-11-system/"><u>Easy and Effective Ways to Update Drivers on a Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-methods-to-refresh-your-dns-resolver-cache-on-windows-systems/"><u>Effective Methods to Refresh Your DNS Resolver Cache on Windows Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficiently-delete-data-with-windows-10s-command-prompt-a-comprehensive-guide/"><u>Efficiently Delete Data with Windows 10'S Command Prompt - A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficiently-upgrade-device-drivers-on-windows-10-with-ease/"><u>Efficiently Upgrade Device Drivers on Windows 10 with Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/essential-steps-to-fortify-your-windows-machine-against-unauthorized-access/"><u>Essential Steps to Fortify Your Windows Machine Against Unauthorized Access</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-basics-of-bios-and-its-relation-to-uninstallers-like-revo/"><u>Exploring the Basics of BIOS and Its Relation to Uninstallers Like Revo</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915316027-exploring-the-giants-of-online-networking-facebook-twitter-instagram-and-youtube/"><u>Exploring the Giants of Online Networking - Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-top-social-media-sites-the-powerhouses-facebook-twitter-insta-youtube/"><u>Exploring Top Social Media Sites: The Powerhouses - Facebook, Twitter, Insta, Youtube</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-canon-mf8500c-printer-drivers-compatible-with-multiple-windows-versions/"><u>Find and Install Canon MF8500C Printer Drivers: Compatible with Multiple Windows Versions</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-honor-90-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Honor 90 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-force-delete-a-folder-windows-11-and-11-revouninstaller/"><u>How to Force Delete a Folder - Windows 11 & 11 - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-force-uninstall-a-program-that-wont-uninstall/"><u>How to Force Uninstall a Program that Won’t Uninstall</u></a></li>
<li><a href="https://win-forum.techidaily.com/identifying-your-installed-powershell-version-in-windows-10-made-easy/"><u>Identifying Your Installed PowerShell Version in Windows 10 Made Easy</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-choreographing-vids-with-a-musical-twist-in-snapchat/"><u>In 2024, Choreographing Vids with a Musical Twist in Snapchat</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-iphone-13-mini-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 13 mini When You Forget the Passcode?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-meizu-21-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Meizu 21 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-s24-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy S24 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-igtv-a-comprehensive-guide-for-beginners-for-2024/"><u>Mastering IGTV  A Comprehensive Guide for Beginners for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-pc-security-a-comprehensive-list-of-5-key-practices-for-windows-users/"><u>Mastering PC Security: A Comprehensive List of 5 Key Practices for Windows Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-major-players-in-digital-media-facebook-twitter-instagram-and-youtube-strategies/"><u>Mastering the Major Players in Digital Media: Facebook, Twitter, Instagram, and YouTube Strategies</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastery-of-windows-access-issues-a-user-friendly-guide-to-rectifying-blockages-with-revo-uninstaller/"><u>Mastery of Windows Access Issues: A User-Friendly Guide to Rectifying Blockages with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-social-networking-insights-on-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Social Networking: Insights on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-compatibility-problems-fixing-your-pc-app-launch-failures/"><u>Overcoming Compatibility Problems - Fixing Your PC App Launch Failures</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-the-windows-11-installation-hurdle-expert-tips-and-tricks/"><u>Overcoming the Windows 11 Installation Hurdle: Expert Tips and Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-this-application-cannot-be-launched-issues-steps-for-a-smooth-windows-experience/"><u>Resolving 'This Application Cannot Be Launched' Issues: Steps for a Smooth Windows Experience</u></a></li>
<li><a href="https://win-forum.techidaily.com/revitalize-your-computer-mastering-the-windows-11-factory-reset-process/"><u>Revitalize Your Computer: Mastering the Windows 11 Factory Reset Process</u></a></li>
<li><a href="https://win-forum.techidaily.com/securely-wipe-out-your-data-for-good-in-windows-11-with-these-tips/"><u>Securely Wipe Out Your Data for Good in Windows 11 with These Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/simplified-windows-registry-modification-edit-delete-and-create-with-revo-uninstaller/"><u>Simplified Windows Registry Modification: Edit, Delete & Create with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-mastery-leveraging-power-of-facebook-twitter-instagram-and-youtube-for-success/"><u>Social Media Mastery: Leveraging Power of Facebook, Twitter, Instagram & YouTube for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-evolution-continues-understanding-the-cutting-edge-features-of-apples-latest-ipad-generation/"><u>The Evolution Continues: Understanding the Cutting-Edge Features of Apple's Latest iPad Generation</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouses-of-online-engagement-facebook-twitter-instagram-and-youtube-explained/"><u>The Powerhouses of Online Engagement: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-dominant-social-channels-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Dominant Social Channels: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-major-social-media-channels-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Major Social Media Channels: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-tutorial-for-file-deletion-via-command-line-in-windows-11/"><u>The Ultimate Tutorial for File Deletion via Command Line in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-social-media-giants-facebook-twitter-instagram-and-youtube/"><u>Top Four Social Media Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-troubleshooting-how-to-perform-a-hard-close-on-stuck-programs-on-windows-11/"><u>Ultimate Troubleshooting: How to Perform a Hard Close on Stuck Programs on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-role-of-windows-registry-in-system-management/"><u>Understanding the Role of Windows Registry in System Management</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-xiaomi-redmi-k70-pros-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Xiaomi Redmi K70 Pros Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-vivo-y78plus-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Vivo Y78+ Phone Network-Ready</u></a></li>
</ul></div>
