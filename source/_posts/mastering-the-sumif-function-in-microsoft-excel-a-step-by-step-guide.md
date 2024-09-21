---
title: Mastering the SUMIF Function in Microsoft Excel - A Step-by-Step Guide
date: 2024-09-16T16:56:52.724Z
updated: 2024-09-21T16:49:09.014Z
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

 Using the following formula, you can add the expenses in cells B2 through B7 only if the revenue in cells C2 through C7 is greater than 25,000.

=SUMIF(C2:C7,">25000",B2:B7)

![SUMIF using greater than for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleGreaterThan-ExcelSUMIF.jpg) 

 You can also replace the actual value in the formula with one contained in a cell. For instance, this formula adds the numbers in B2 through B7 if the value in C2 through C7 is greater than the value in cell D2.

=SUMIF(C2:C7,">"&D2,B2:B7)

 This formula uses the greater than symbol (">") and cell D2 (&D2).

![SUMIF using greater than a cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleGreaterThanCell-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Use SUMIF With Text Criteria for Multiple Ranges

 Maybe the values you want to add correlate to [text rather than numbers](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/). Here we have types, products, and sales. Using SUMIF, you can add values in the Sales column for products that meet certain conditions in the other columns.

Related: [How to Count Cells With Text in Microsoft Excel](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/) 

 In this example, you can add the sales in cells C2 through C7 only if the text in cells A2 through B7 equals the word Apparel.

=SUMIF(A2:B7,"Apparel",C2:C7)

![SUMIF equals a word for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextWord-ExcelSUMIF.jpg) 

 For another example, you can add the sales in cells C2 through C7 for products in cells B2 through B7 that end in "ts."

=SUMIF(B2:B7,"*ts",C2:C7)

 In this formula, the asterisk (\*) is a wildcard representing any letters before "ts".

![SUMIF ends with letters in multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextWildcard-ExcelSUMIF.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 One more example uses our Shoes product whose Type is blank.

=SUMIF(A2:B7,"",C2:C7)

 In this formula the quotation marks are side-by-side with no space between them. This gives us the sales for Shoes as seen below.

![SUMIF using a blank for multiple cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/MultipleTextBlank-ExcelSUMIF.jpg) 

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
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapchat-cameos-catch-up-with-the-trendiest-trick/"><u>[Updated] 2024 Approved Snapchat Cameos Catch Up with the Trendiest Trick</u></a></li>
<li><a href="https://win-forum.techidaily.com/aifoggmovavi/"><u>簡単な方法！無料で高品質のAIF形式ファイルをOGGに変換：Movaviでご提案</u></a></li>
<li><a href="https://win-forum.techidaily.com/free-online-nef-to-jpeg-converter-by-movavi-no-download-required/"><u>Free Online NEF to JPEG Converter by Movavi - No Download Required</u></a></li>
<li><a href="https://win-forum.techidaily.com/gratis-online-mp4-konvertere-fra-videofilen-raskt-og-enkel-handtering/"><u>Gratis Online-MP4 Konvertere Fra Videofilen - Raskt Og Enkel Håndtering</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-a-lost-apple-iphone-6-for-free-drfone-by-drfone-virtual-ios/"><u>How to Track a Lost Apple iPhone 6 for Free? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-rectifying-identity-mix-up-in-fb-text-exchange/"><u>In 2024, Rectifying Identity Mix-Up in FB Text Exchange</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/pixel-fold-2-unveiled-anticipated-features-pricing-and-release-timeline-stay-updated-with-latest-buzz/"><u>Pixel Fold 2 Unveiled: Anticipated Features, Pricing & Release Timeline - Stay Updated with Latest Buzz!</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/refurbished-apple-iphone-x-everything-you-need-to-know-drfone-by-drfone-transfer-from-ios/"><u>Refurbished Apple iPhone X Everything You Need to Know | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/reviven-tu-memoria-7-sencillas-tecnicas-para-recuperar-fotos-antiguas-con-eficacia-usando-movavi/"><u>Reviven Tu Memoria: 7 Sencillas Técnicas Para Recuperar Fotos Antiguas Con Eficacia Usando Movavi</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-frames-per-second-for-slow-clips/"><u>Ultimate Frames Per Second for Slow Clips</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-to-understanding-screen-recording-everything-you-need-to-know-comprehensive-breakdown/"><u>Ultimate Guide to Understanding Screen Recording: Everything You Need To Know - Comprehensive Breakdown</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/unlock-the-secrets-of-restoring-your-iphone-expert-tips-and-tricks/"><u>Unlock the Secrets of Restoring Your iPhone - Expert Tips and Tricks</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Motorola Razr 40 Ultra? | Dr.fone</u></a></li>
</ul></div>

