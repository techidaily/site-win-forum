---
title: Mastering the SUMIF Function in Microsoft Excel - A Step-by-Step Guide
date: 2024-08-28T04:29:25.943Z
updated: 2024-08-29T04:29:25.943Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering the SUMIF Function in Microsoft Excel - A Step-by-Step Guide

### Quick Links

* [Use SUMIF For a Single Cell Range](https://driver-install.techidaily.com/efficient-gear-up-directly-recollecting-your-graphics-drivers/)
* [Use SUMIF With Number Criteria for Multiple Ranges](https://unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-vivo-v30-pro-by-drfone-android/)
* [Use SUMIF With Text Criteria for Multiple Ranges](https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oneplus-nord-3-5g-easily-and-safely-drfone-by-drfone-virtual-android/)

 Adding numbers together in Microsoft Excel is a [basic calculation](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) that can use the SUM function. What if you want to add those values but only if they meet certain conditions? This is when the SUMIF function comes in.

 With SUMIF, you can add the values in the cells you specify as long as they meet specific criteria. Maybe you want to [find the total](https://howto.techidaily.com/android-screen-stuck-general-samsung-galaxy-s23-ultra-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/) sales but only for certain products or the total revenue but only for particular locations.

 If your Excel sheet is set up in a way that your calculation isn't easily determined, the SUMIF [function and its formula](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) can help.

##  Use SUMIF For a Single Cell Range

 The syntax for the function is 

        `SUMIF(cell_range, criteria, sum_range)`
    
 where the first two arguments are required. Because `sum_range` is optional, you can add numbers in one range that correlate to criteria in another.

 To get the basic feel of the function and its arguments, let's start by using a single range of cells without the optional argument.

 You could [add values in a cell range](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) only if they are greater than a certain amount. Enter the following formula, replacing the cell references and criteria with your own.

=SUMIF(C2:C7,">25000")

 This formula adds the numbers in the cell range C2 through C7 only if they are greater than 25,000.

![SUMIF using greater than for a single cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SingleGreaterThan-ExcelSUMIF.jpg) 

 On the flip side, you can add numbers that are less than a certain amount using this formula:

=SUMIF(B2:B7,"<10000")

 This adds the numbers in cells B2 through B7 only if they are less than 10,000.

![SUMIF using less than for a single cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SingleLessThan-ExcelSUMIF.jpg) 

 For one more example, you can add numbers that are the same amount with this formula:

=SUMIF(A2:A7,"5000")

 This [adds the numbers](https://instagram-clips.techidaily.com/updated-2024-approved-unveiling-instagrams-policies-a-musicians-legal-primer/) in cells A2 through A7 only if they are exactly 5,000.

![SUMIF using equals for a single cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/SingleEquals-ExcelSUMIF.jpg) 

##  Use SUMIF With Number Criteria for Multiple Ranges

 Now let's put that conditional argument to work, `sum_range`. Here we're [calculating expenses](https://fox-blue.techidaily.com/updated-diving-into-the-depths-with-gopro-hero5-for-2024/) and revenue. With SUMIF, we can calculate the revenue for locations whose expenses meet our criteria and vice versa.

Related: [How to Create Expense and Income Spreadsheets in Microsoft Excel](https://fox-blue.techidaily.com/updated-diving-into-the-depths-with-gopro-hero5-for-2024/) 

 With this formula you can add the revenue in cells C2 through C7 only if the expenses in cells B2 through B7 are less than 10,000.

=SUMIF(B2:B7,"<10000",C2:C7)

![SUMIF using less than for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleLessThan-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
 Using the following formula, you can add the expenses in cells B2 through B7 only if the revenue in cells C2 through C7 is greater than 25,000.

=SUMIF(C2:C7,">25000",B2:B7)

![SUMIF using greater than for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleGreaterThan-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can also replace the actual value in the formula with one contained in a cell. For instance, this formula adds the numbers in B2 through B7 if the value in C2 through C7 is greater than the value in cell D2.

=SUMIF(C2:C7,">"&D2,B2:B7)

 This formula uses the greater than symbol (">") and cell D2 (&D2).

![SUMIF using greater than a cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleGreaterThanCell-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Use SUMIF With Text Criteria for Multiple Ranges

 Maybe the values you want to add correlate to [text rather than numbers](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/). Here we have types, products, and sales. Using SUMIF, you can add values in the Sales column for products that meet certain conditions in the other columns.

Related: [How to Count Cells With Text in Microsoft Excel](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/) 

 In this example, you can add the sales in cells C2 through C7 only if the text in cells A2 through B7 equals the word Apparel.

=SUMIF(A2:B7,"Apparel",C2:C7)

![SUMIF equals a word for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextWord-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 For another example, you can add the sales in cells C2 through C7 for products in cells B2 through B7 that end in "ts."

=SUMIF(B2:B7,"*ts",C2:C7)

 In this formula, the asterisk (\*) is a wildcard representing any letters before "ts".

![SUMIF ends with letters in multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextWildcard-ExcelSUMIF.jpg) 

 One more example uses our Shoes product whose Type is blank.

=SUMIF(A2:B7,"",C2:C7)

 In this formula the quotation marks are side-by-side with no space between them. This gives us the sales for Shoes as seen below.

![SUMIF using a blank for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextBlank-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The SUMIF function in Excel allows you to take a basic equation and spice it up to fit your needs. It's super handy when adding numbers isn't as simple as two plus two.

 For additional help, take a look at how to [find the function you need in Excel](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/).

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-ultimate-capture-assistant-az-audits-and-alternatives/"><u>[New] 2024 Approved  Ultimate Capture Assistant - AZ Audits & Alternatives</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-best-5-gopro-filters-for-underwater-video-shooting/"><u>[New] Best 5 GoPro Filters for Underwater Video Shooting</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-comprehensive-studio-study-xvideo-studio-insights/"><u>[New] Comprehensive Studio Study  XVideo Studio Insights</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-download-your-wish-unwatermarked-tiktok-files/"><u>[New] In 2024, Download-Your-Wish  Unwatermarked TikTok Files</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-exploring-and-harnessing-twitter-archive-insights/"><u>[New] In 2024, Exploring and Harnessing Twitter Archive Insights</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-quick-start-using-ez-grabber-effectively/"><u>[Updated] Quick Start  Using EZ Grabber Effectively</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-harnessing-ig-videos-effectively-blueprint-for-a-dynamic-marketing-plan/"><u>2024 Approved  Harnessing IG Videos Effectively  Blueprint for a Dynamic Marketing Plan</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ing-a-studio-quality-setup-at-home/"><u>Building a Studio-Quality Setup at Home</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-guide-to-popular-online-communities-facebook-twitter-instagram-and-youtubers/"><u>Comprehensive Guide to Popular Online Communities: Facebook, Twitter, Instagram & YouTubers</u></a></li>
<li><a href="https://win-forum.techidaily.com/discover-how-to-verify-your-powershell-version-on-a-windows-10-machine/"><u>Discover How to Verify Your PowerShell Version on a Windows 10 Machine</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-stability-improved-with-driver-correction/"><u>Display Stability Improved with Driver Correction</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diy-guide-building-a-win10-restore-flash-drive-from-scratch/"><u>DIY Guide: Building a Win10 Restore Flash Drive From Scratch</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficiently-manage-full-storage-space-problems-in-windows-11-computers/"><u>Efficiently Manage Full Storage Space Problems in Windows 11 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-and-grow-with-key-social-media-sites-facebook-twitter-instagram-and-youtube/"><u>Engage and Grow with Key Social Media Sites: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/fix-slow-network-issues-with-these-simple-dns-flush-steps-for-windows-users/"><u>Fix Slow Network Issues with These Simple DNS Flush Steps for Windows Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-identifying-the-active-powershell-version-in-windows-11-environments/"><u>Guide: Identifying The Active PowerShell Version In Windows 11 Environments</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-delete-user-profile-in-windows-11-revouninstaller/"><u>How to Delete User Profile in Windows 11 - RevoUninstaller</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-vivo-y100i-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Vivo Y100i Quickly? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-configuring-wake-on-lan-connectivity-for-windows-11-devices/"><u>How To: Configuring Wake-on-LAN Connectivity for Windows 11 Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-motorola-edge-40-neo-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Motorola Edge 40 Neo Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-sonic-pixels-turning-sound-into-visual-storytelling/"><u>In 2024, Sonic Pixels  Turning Sound Into Visual Storytelling</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-xbox-ones-zooming-edge-a-comprehensive-guide/"><u>In 2024, Xbox One's Zooming Edge  A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/is-the-iphone-15-pro-max-waterproof/"><u>Is the iPhone 15 Pro Max Waterproof?</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-fixing-recurring-windows-explorer-breakdowns-top-7-methods-revealed/"><u>Master the Art of Fixing Recurring Windows Explorer Breakdowns - Top 7 Methods Revealed</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-altitude-with-djis-new-gadget-for-2024/"><u>Mastering Altitude with DJI's New Gadget for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-dynamics-with-facebook-twitter-instagram-and-youtube/"><u>Mastering Social Media Dynamics with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-third-party-software-uninstallers-are-they-worth-it/"><u>Navigating the World of Third-Party Software Uninstallers - Are They Worth It?</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-the-modern-editors-handbook-cutting-and-mixing-in-avidemux/"><u>New In 2024, The Modern Editors Handbook Cutting and Mixing in Avidemux</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/obs-vs-wirecast-which-should-you-trust-for-live-in-2024/"><u>OBS Vs. Wirecast - Which Should You Trust for Live, In 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/quickstart-guide-accelerating-your-windows-11-booting-process/"><u>QuickStart Guide: Accelerating Your Windows 11 Booting Process</u></a></li>
<li><a href="https://win-forum.techidaily.com/seamless-elevation-tactics-for-enhanced-app-functionality-in-windows-nix/"><u>Seamless Elevation Tactics for Enhanced App Functionality in Windows Nix</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-to-clearing-memory-dump-files-on-windows-10/"><u>Step-by-Step Guide to Clearing Memory Dump Files on Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/streamlined-file-deletion-with-cmd-tools-a-window-10-users-handbook/"><u>Streamlined File Deletion with CMD Tools - A Window 10 User's Handbook</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-9-dangers-when-ai-takes-over-emotional-care/"><u>The 9 Dangers: When AI Takes Over Emotional Care</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-most-exciting-tiktok-content-to-date/"><u>The Most Exciting TikTok Content to Date</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-technique-for-clearing-out-ram-dump-records-on-windows-1011-systems/"><u>The Ultimate Technique for Clearing Out RAM Dump Records on Windows 10/11 Systems</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-networks-unveiled-exploring-facebook-twitter-instagram-and-youtube/"><u>Top Social Networks Unveiled: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-unforeseen-issues-the-windows-11-guide-to-unexpected-mishaps/"><u>Troubleshooting Unforeseen Issues: The Windows 11 Guide to Unexpected Mishaps</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-secrets-eliminating-stubborn-directories-on-your-windows-11-system/"><u>Unlock the Secrets: Eliminating Stubborn Directories on Your Windows 11 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/waking-up-remotely-enabling-wake-on-lan-on-your-latest-windows-pcs/"><u>Waking Up Remotely: Enabling Wake-on-LAN on Your Latest Windows PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/will-televising-facebook-vids-become-a-trend-in-2024/"><u>Will Televising Facebook Vids Become a Trend , In 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-10-powershell-verification-methods-what-you-need-to-know/"><u>Windows 10 PowerShell Verification Methods: What You Need to Know</u></a></li>
<li><a href="https://win-forum.techidaily.com/windows-11-users-learn-how-to-delete-system-memory-dumps-easily/"><u>Windows 11 Users! Learn How to Delete System Memory Dumps Easily</u></a></li>
</ul></div>
