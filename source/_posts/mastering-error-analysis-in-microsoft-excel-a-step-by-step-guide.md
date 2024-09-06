---
title: "Mastering Error Analysis in Microsoft Excel: A Step-by-Step Guide"
date: 2024-09-05T07:55:57.401Z
updated: 2024-09-06T07:55:57.401Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2cb259c465a86a9d87c2ab8ed232a243225880491ec4b7484688140a5b3e77f5.jpg
---

## Mastering Error Analysis in Microsoft Excel: A Step-by-Step Guide

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Quick Links

* [Arithmetic Mean of Values](https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-y27s-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Standard Deviation of the Values](https://extra-skills.techidaily.com/navigating-sales-for-inexpensive-gopros-for-2024/)
* [Calculate the Standard Error](https://games-able.techidaily.com/harmonizing-fun-and-safety-in-childs-steam-world/)
* [Using Error Bars to Present Uncertainty in Charts](https://facebook-record-videos.techidaily.com/updated-in-2024-elevating-your-music-crafting-stunning-lyric-videos-using-lyric-video-maker/)

 There is doubt surrounding the accuracy of most statistical data---even when following procedures and using efficient equipment to test. Excel lets you calculate uncertainty based on your sample's standard deviation.

 There are statistical formulas in Excel we can use to calculate uncertainty. And in this article, we will calculate the arithmetic mean, standard deviation and the standard error. We will also look at how we can plot this uncertainty on a chart in Excel.

 We will use the following sample data with these formulas.

![Sample data to calculate uncertainty](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/sample-data-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This data shows five people that have taken a measurement or reading of some kind. With five different readings, we have uncertainty over what the real value is.

##  Arithmetic Mean of Values

 When you have uncertainty over a range of different values, taking the average (arithmetic mean) can serve as a reasonable estimate.

 This is easy to do in Excel with the AVERAGE function.

 We can use the following formula on the sample data above.

=AVERAGE(B2:B6)

![Mean average of a set of measurements](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/mean-average-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030370/7443" target="_top" id="2030370">
  <img src="//a.impactradius-go.com/display-ad/7443-2030370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Standard Deviation of the Values

 The standard deviation functions show how widely spread your data is from a central point (the mean average value we calculated in the last section).

 Excel has a few different standard deviation functions for various purposes. The two main ones are STDEV.P and STDEV.S.

 Each of these will calculate the standard deviation. The difference between the two is that STDEV.P is based on you supplying it with the entire population of values. STDEV.S works on a smaller sample of that population of data.

 In this example, we're using all five of our values in the data set, so we will work with STDEV.P.

 This function works in the same way as AVERAGE. You can use the formula below on this sample of data.

=STDEV.P(B2:B6)

![Standard deviation of a set of values using STDEV.P](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-deviation-1.png) 

 The result of these five different values is 0.16\. This number tells us how different each measurement typically is from the average value.

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Calculate the Standard Error

 With the standard deviation calculated, we can now find the standard error.

 The standard error is the standard deviation divided by the square root of the number of measurements.

 The formula below will calculate the standard error on our sample data.

=D5/SQRT(COUNT(B2:B6))

![Calculate the standard error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-error-1.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Using Error Bars to Present Uncertainty in Charts

 Excel makes it wonderfully simple to plot the standard deviations or margins of uncertainty on charts. We can do this by adding error bars.

 Below we have a column chart from a sample data set showing a population measured over five years.

![Column chart showing population data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/column-chart-2.png) 

 With the chart selected, click Design > Add Chart Element.

 Then choose from the different error types available.

![Select an error bar type for your chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/error-bars-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can show a standard error or standard deviation amount for all values as we calculated earlier in this article. You can also display a percentage error change. The default is 5%.

 For this example, we chose to show the percentage.

![Error bars showing percentage margin](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/percentage-error.png) 

 There are some further options to explore to customize your error bars.

 Double-click an error bar in the chart to open the Format Error Bars pane. Select the "Error Bars Options" category if it is not already selected.

 You can then adjust the percentage, standard deviation value, or even select a custom value from a cell that may have been produced by a statistical formula.

![Format error bars to customise them further](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/format-error-bars.png) 

 Excel is an ideal tool for statistical analysis and reporting. It provides many ways to calculate uncertainty so that you get what you need.

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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-enhancing-authenticity-techniques-to-apply-on-insta-photos/"><u>[New] In 2024, Enhancing Authenticity  Techniques to Apply on Insta Photos</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-luts-transforming-images-magic/"><u>[New] Understanding LUTs  Transforming Images Magic</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-getting-started-with-photography-the-leading-cams/"><u>[Updated] Getting Started with Photography  The Leading Cams</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-navigating-the-realm-of-sponsorships-on-instagram-influencer-edition/"><u>[Updated] In 2024, Navigating the Realm of Sponsorships on Instagram  Influencer Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pewdiepie-financial-overview-monetary-metrics/"><u>[Updated] PewDiePie Financial Overview – Monetary Metrics</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-warping-letters-in-photographyvideo/"><u>[Updated] Warping Letters in Photography/Video</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/best-practices-for-resolving-high-disk-usage-at-100-on-your-windows-10-system/"><u>Best Practices for Resolving High Disk Usage at 100%% on Your Windows 10 System</u></a></li>
<li><a href="https://win-forum.techidaily.com/clear-out-pc-clutter-on-windows-11-a-detailed-walkthrough-using-revo-uninstaller/"><u>Clear Out PC Clutter on Windows 11 – A Detailed Walkthrough Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-removing-user-accounts-on-windows-11-with-revo-uninstaller/"><u>Complete Guide: Removing User Accounts on Windows 11 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-tutorial-how-to-erase-user-profiles-using-revo-uninstaller-on-windows-11/"><u>Complete Tutorial: How to Erase User Profiles Using Revo Uninstaller on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-share-on-major-social-media-facebook-twitter-instagram-youtube-overview/"><u>Connect and Share on Major Social Media: Facebook, Twitter, Instagram, YouTube Overview</u></a></li>
<li><a href="https://win-forum.techidaily.com/defeating-the-persistent-problem-of-unrecognized-usb-devices/"><u>Defeating the Persistent Problem of Unrecognized USB Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/do-you-really-need-a-third-party-app-to-remove-programs-exploring-the-alternatives/"><u>Do You Really Need a Third-Party App to Remove Programs: Exploring the Alternatives</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-solutions-to-overcome-apps-not-running-error-in-pc/"><u>Effective Solutions to Overcome Apps Not Running Error in PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/efficient-techniques-for-killing-hanging-programs-in-the-latest-windows-operating-system/"><u>Efficient Techniques for Killing Hanging Programs in the Latest Windows Operating System</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-on-the-web-with-leading-networks-facebook-twitter-instagram-and-youtube/"><u>Engage on the Web with Leading Networks: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/explore-social-networks-facebook-twitter-and-instagram-youtube/"><u>Explore Social Networks: Facebook, Twitter & Instagram, YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-digital-connections-through-leading-platforms-facebook-twitter-instagram-and-youtube/"><u>Exploring Digital Connections Through Leading Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-core-of-windows-os-a-guide-to-the-windows-registry-system/"><u>Exploring The Core of Windows OS: A Guide to the Windows Registry System</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-top-social-platforms-facebook-twitter-instagram-and-youtube-unveiled/"><u>Exploring Top Social Platforms: Facebook, Twitter, Instagram & YouTube Unveiled</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-blue-yeti-drivers-not-detected-recognized-or-installed/"><u>Fix: Blue Yeti Drivers Not Detected, Recognized or Installed</u></a></li>
<li><a href="https://win-forum.techidaily.com/harnessing-engagement-on-popular-networks-facebook-twitter-instagram-and-youtube-insights/"><u>Harnessing Engagement on Popular Networks: Facebook, Twitter, Instagram, and YouTube Insights</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-enter-the-bios-in-windows-11-revouninstaller/"><u>How to Enter the Bios in Windows 11 - RevoUninstaller</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-perform-a-clean-installation-on-windows-11-essential-steps-and-tips/"><u>How to Perform a Clean Installation on Windows 11 - Essential Steps and Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-reclaim-disk-capacity-in-windows-11-the-ultimate-troubleshooting-and-cleanup-tutorial/"><u>How to Reclaim Disk Capacity in Windows 11: The Ultimate Troubleshooting and Cleanup Tutorial</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elevate-your-video-game-with-these-5-youtube-thumbnail-builders/"><u>In 2024, Elevate Your Video Game with These 5 YouTube Thumbnail Builders</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-thriving-livestreams-strategies-for-beginners-with-low-followers/"><u>In 2024, Thriving Livestreams  Strategies for Beginners with Low Followers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/inside-scoop-on-the-new-pixel-buds-pro-2-by-google-pricing-insights-and-anticipated-release-date-shared/"><u>Inside Scoop on the New Pixel Buds Pro 2 by Google - Pricing Insights & Anticipated Release Date Shared</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/keep-it-hot-ideas-for-uninterrupted-snapchat-connections/"><u>Keep It Hot - Ideas for Uninterrupted Snapchat Connections</u></a></li>
<li><a href="https://win-forum.techidaily.com/launch-of-revo-uninstaller-pro-version-5-enhanced-system-cleanup/"><u>Launch of Revo Uninstaller Pro Version 5: Enhanced System Cleanup</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-forcing-quit-uncooperative-software-on-windows-11-computers/"><u>Mastering the Art of Forcing Quit Uncooperative Software on Windows 11 Computers</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-media-powerhouses-insight-into-facebook-twitter-instagram-and-youtube/"><u>Navigating the Social Media Powerhouses: Insight Into Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-and-simple-guide-elgato-driver-software-download/"><u>Quick and Simple Guide: Elgato Driver Software Download</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-insights-5-easy-techniques-for-effective-audio-capture-on-windows-11/"><u>Quick Insights  5 Easy Techniques for Effective Audio Capture on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstallers-powerful-method-to-force-delete-non-responding-folders-on-windows-os/"><u>Revo Uninstaller's Powerful Method to Force Delete Non-Responding Folders on Windows OS</u></a></li>
<li><a href="https://win-forum.techidaily.com/solution-found-troubleshooting-far-cry-6-pc-game-wont-start/"><u>Solution Found: Troubleshooting Far Cry 6 PC Game Won't Start</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-tutorial-for-setting-up-wake-on-lan-on-microsofts-latest-operating-systems/"><u>Step-by-Step Tutorial for Setting Up Wake-on-LAN on Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-infinix-zero-5g-2023-turbo-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Infinix Zero 5G 2023 Turbo ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-online-social-interaction-facebook-twitter-instagram-and-youtube-explained/"><u>The Big Four of Online Social Interaction: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-definitive-technique-to-grant-administrator-rights-automatically-to-all-your-apps-on-windows-11/"><u>The Definitive Technique to Grant Administrator Rights Automatically to All Your Apps on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-players-in-social-media-exploring-facebook-twitter-instagram-and-youtubes-dominance/"><u>The Power Players in Social Media: Exploring Facebook, Twitter, Instagram & Youtube's Dominance</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouses-of-social-media-a-closer-look-at-facebook-twitter-instagram-and-youtube/"><u>The Powerhouses of Social Media: A Closer Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-quad-of-digital-sphere-exploring-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Quad of Digital Sphere: Exploring Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-media-platforms-for-engagement-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Social Media Platforms for Engagement: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-networks-explained-facebook-twitter-instagram-and-youtube/"><u>The Quintessential Social Networks Explained: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-top-social-media-sites-facebook-twitter-instagram-and-youtube/"><u>The Ultimate Guide to Top Social Media Sites - Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-5-methods-for-securing-your-pc-protecting-windows-devices/"><u>Top 5 Methods for Securing Your PC: Protecting Windows Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-windows-11-solutions-for-wont-run-issues/"><u>Troubleshooting Windows 11: Solutions for Wont Run Issues</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveil-your-windows-11-powershell-version-with-simple-steps-a-comprehensive-guide/"><u>Unveil Your Windows 11 PowerShell Version with Simple Steps – A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/unveiling-the-giants-of-digital-communication-facebook-twitter-instagram-and-youtube/"><u>Unveiling the Giants of Digital Communication: Facebook, Twitter, Instagram & YouTube</u></a></li>
</ul></div>
