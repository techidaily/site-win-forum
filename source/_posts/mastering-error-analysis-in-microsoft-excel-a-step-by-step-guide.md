---
title: "Mastering Error Analysis in Microsoft Excel: A Step-by-Step Guide"
date: 2024-09-25T16:53:42.448Z
updated: 2024-10-01T16:36:07.378Z
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The result of these five different values is 0.16\. This number tells us how different each measurement typically is from the average value.

##  Calculate the Standard Error

 With the standard deviation calculated, we can now find the standard error.

 The standard error is the standard deviation divided by the square root of the number of measurements.

 The formula below will calculate the standard error on our sample data.

=D5/SQRT(COUNT(B2:B6))

![Calculate the standard error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-error-1.png) 

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
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 There are some further options to explore to customize your error bars.

 Double-click an error bar in the chart to open the Format Error Bars pane. Select the "Error Bars Options" category if it is not already selected.

 You can then adjust the percentage, standard deviation value, or even select a custom value from a cell that may have been produced by a statistical formula.

![Format error bars to customise them further](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/format-error-bars.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-recording.techidaily.com/new-streamline-and-save-prime-tools-to-plug-into-fb-videos-for-2024/"><u>[New] Streamline & Save Prime Tools to Plug Into Fb Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-navigating-the-social-sphere-of-tiktok-lives/"><u>[Updated] Navigating the Social Sphere of TikTok Lives</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pushing-boundaries-in-media-text-curve-concepts/"><u>2024 Approved Pushing Boundaries in Media Text Curve Concepts</u></a></li>
<li><a href="https://win-forum.techidaily.com/android-11-features-one-time-permission-revouninstaller/"><u>Android 11 Features: One-Time Permission - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-dots-in-digital-networking-through-facebook-twitter-instagram-and-youtube/"><u>Connecting the Dots in Digital Networking Through Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Realme Narzo 60x 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-file-explorer-on-windows-11-quick-tips-and-tricks/"><u>Mastering File Explorer on Windows 11: Quick Tips & Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-engagement-across-major-platforms-facebook-twitter-instagram-and-youtube/"><u>Mastering Social Media Engagement Across Major Platforms: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-social-sphere-with-facebook-twitter-instagram-and-youtube/"><u>Mastering the Social Sphere with Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-the-witcher-3-on-pc-fixing-and-avoiding-frustrating-game-crashes/"><u>Mastering The Witcher 3 on PC: Fixing and Avoiding Frustrating Game Crashes</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-media-giants-facebook-twitter-instagram-and-youtube/"><u>Navigating the Social Media Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://data-wizards.techidaily.com/remedies-for-dim-or-flickering-surveillance-video/"><u>Remedies for Dim or Flickering Surveillance Video</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/"><u>Seamless Multi-Screen Browsing in Chrome Using PIP for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-print-service-non-responsive/"><u>Solved: Print Service Non-Responsive</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-hidden-applications-from-your-pc-without-using-control-panel/"><u>Step-by-Step Guide: Removing Hidden Applications From Your PC Without Using Control Panel</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-to-immediately-end-frozen-windows-programs-using-revouninstaller/"><u>Step-by-Step Process to Immediately End Frozen Windows Programs Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-platforms-compared-facebook-vs-twitter-vs-instagram-vs-youtube/"><u>Top Social Platforms Compared: Facebook Vs. Twitter Vs. Instagram Vs. YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-protection-safeguarding-your-text-files-with-password-encryption-techniques/"><u>Ultimate Protection: Safeguarding Your Text Files with Password Encryption Techniques</u></a></li>
</ul></div>

