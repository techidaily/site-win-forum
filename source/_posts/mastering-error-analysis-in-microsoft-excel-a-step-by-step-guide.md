---
title: "Mastering Error Analysis in Microsoft Excel: A Step-by-Step Guide"
date: 2024-09-11T16:46:09.544Z
updated: 2024-09-16T16:26:28.641Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2cb259c465a86a9d87c2ab8ed232a243225880491ec4b7484688140a5b3e77f5.jpg
---

## Mastering Error Analysis in Microsoft Excel: A Step-by-Step Guide

### Quick Links

* [Arithmetic Mean of Values](https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-y27s-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Standard Deviation of the Values](https://extra-skills.techidaily.com/navigating-sales-for-inexpensive-gopros-for-2024/)
* [Calculate the Standard Error](https://games-able.techidaily.com/harmonizing-fun-and-safety-in-childs-steam-world/)
* [Using Error Bars to Present Uncertainty in Charts](https://facebook-record-videos.techidaily.com/updated-in-2024-elevating-your-music-crafting-stunning-lyric-videos-using-lyric-video-maker/)

 There is doubt surrounding the accuracy of most statistical data---even when following procedures and using efficient equipment to test. Excel lets you calculate uncertainty based on your sample's standard deviation.

 There are statistical formulas in Excel we can use to calculate uncertainty. And in this article, we will calculate the arithmetic mean, standard deviation and the standard error. We will also look at how we can plot this uncertainty on a chart in Excel.

 We will use the following sample data with these formulas.

![Sample data to calculate uncertainty](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/sample-data-1.png) 

 This data shows five people that have taken a measurement or reading of some kind. With five different readings, we have uncertainty over what the real value is.

##  Arithmetic Mean of Values

 When you have uncertainty over a range of different values, taking the average (arithmetic mean) can serve as a reasonable estimate.

 This is easy to do in Excel with the AVERAGE function.

 We can use the following formula on the sample data above.

=AVERAGE(B2:B6)

![Mean average of a set of measurements](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/mean-average-1.png) 

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
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Calculate the Standard Error

 With the standard deviation calculated, we can now find the standard error.

 The standard error is the standard deviation divided by the square root of the number of measurements.

 The formula below will calculate the standard error on our sample data.

=D5/SQRT(COUNT(B2:B6))

![Calculate the standard error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-error-1.png) 

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Using Error Bars to Present Uncertainty in Charts

 Excel makes it wonderfully simple to plot the standard deviations or margins of uncertainty on charts. We can do this by adding error bars.

 Below we have a column chart from a sample data set showing a population measured over five years.

![Column chart showing population data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/column-chart-2.png) 

 With the chart selected, click Design > Add Chart Element.

 Then choose from the different error types available.

![Select an error bar type for your chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/error-bars-1.png) 

 You can show a standard error or standard deviation amount for all values as we calculated earlier in this article. You can also display a percentage error change. The default is 5%.

 For this example, we chose to show the percentage.

![Error bars showing percentage margin](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/percentage-error.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-audio-treasures-to-amplify-youtube/"><u>[New] 2024 Approved Free Audio Treasures to Amplify YouTube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-tailoring-your-videos-for-impact-on-instagram-feed/"><u>[Updated] 2024 Approved Tailoring Your Videos for Impact on Instagram Feed</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-for-deleting-windows-11-memory-dump-data/"><u>Expert Advice for Deleting Windows 11 Memory Dump Data</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/expert-advice-on-handling-and-repairing-bios-level-faults-whea-error/"><u>Expert Advice on Handling and Repairing BIOS-Level Faults (WHEA Error)</u></a></li>
<li><a href="https://driver-install.techidaily.com/fix-dell-touchpad-not-working-issue-for-windows-10/"><u>Fix Dell Touchpad Not Working Issue for Windows 10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/harness-the-potential-of-ai-conversations-on-quora-through-its-api-poe/"><u>Harness the Potential of AI Conversations on Quora Through Its API (Poe)</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-prevent-and-solve-frequent-haltings-during-steam-downloads/"><u>How to Prevent and Solve Frequent Haltings During Steam Downloads</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-samsung-galaxy-s23-ultra-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Samsung Galaxy S23 Ultra</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-speed-up-windows-11-boot-time-revouninstaller/"><u>How to Speed up Windows 11 Boot Time - RevoUninstaller</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-tecno-spark-go-2023-and-browser-drfone-by-drfone-virtual-android/"><u>In 2024, Prevent Cross-Site Tracking on Tecno Spark Go (2023) and Browser | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-search-how-to-check-and-confirm-powershell-version-on-windows-11/"><u>Mastering the Search: How to Check and Confirm PowerShell Version on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-web-of-connections-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the Web of Connections with Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-windows-11-updates-efficiently/"><u>Step-by-Step Guide: Removing Windows 11 Updates Efficiently</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-complete-hard-drive-occupancy-on-windows-10-machines/"><u>Troubleshooting Complete Hard Drive Occupancy on Windows 10 Machines</u></a></li>
<li><a href="https://win-forum.techidaily.com/troubleshooting-guide-how-to-roll-back-recent-updates-on-windows-11/"><u>Troubleshooting Guide: How to Roll Back Recent Updates on Windows 11</u></a></li>
</ul></div>

