---
title: "Effortless Currency Transformation: Learn How to Use Microsoft Excel for Effective Money Conversion"
date: 2024-09-28T16:01:34.109Z
updated: 2024-10-01T17:04:08.699Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7240c2e9a6abc552c14c05c0954b803ce022aaf37095d266ecb3ccb4c8e95c38.jpg
---

## Effortless Currency Transformation: Learn How to Use Microsoft Excel for Effective Money Conversion

### Quick Links

* [Adding an External Data Source to Excel](https://pokemon-go-android.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-poco-m6-5g-drfone-by-drfone-virtual-android/)
* [Converting Currency in Microsoft Excel](https://youtube-sure.techidaily.com/for-effective-tripod-usage-in-video-blogging-for-2024/)

 Microsoft Excel doesn't include built-in tools to convert currency. However, you can use an external data source to provide up-to-date rates. A basic multiplication formula will then convert from one currency to another. Here's how you do it!

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Adding an External Data Source to Excel

 An external data source is the best way to get up-to-date currency exchange rates. You can use this data to convert from one currency to another in Excel. The process is similar to [converting currency in Google Sheets](https://fox-blue.techidaily.com/2024-approved-close-up-clarity-mastering-the-art-of-intense-focus/).

Related: [How to Convert Currency in Google Sheets](https://fox-blue.techidaily.com/2024-approved-close-up-clarity-mastering-the-art-of-intense-focus/) 

 First, you need a suitable online data source (in the XML format) that you can import into your spreadsheet. [FloatRates](http://www.floatrates.com/feeds.html) has various XML feeds based around different currencies that you can use.

 After you find the one you want to use, open your Excel spreadsheet. In Excel 2019 or Office 365, click Data > Get Data > From File > From XML. In older versions of Excel, click Data > Get External Data > From Other Sources > From XML Data Import instead.

![Click &quot;Data,&quot; click &quot;Get Data,&quot; click &quot;From File,&quot; and then select &quot;From XML.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Add-XML-Data-Source.png) 

 For our example, we're using the [FloatRates USD data feed,](http://www.floatrates.com/daily/usd.xml) so we import that into Excel.

 In the "Import Data" window, paste the URL to your XML data feed in the "File Name" box, and then click "Import."

![Paste your XML data feed into the Import Data window, then press Import to import it into Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Import-Data-Window.png) 

 If you have Office 2019 or 365, you see a preview of how the data will be imported. If you're using FloatRates data, you have to convert it in the Excel Power Query Editor to use it.

 To do so, click "Transform Data."

![Click Transform Data to convert an XML data feed during the XML import wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-XML-Transform-Data.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Excel Power Query Editor appears. Scroll to the "Item" column, and then double-click "Table" to load the up-to-date currency rates.

![In the Excel Power Query Editor, scroll to the Item column, then double-click the Table item](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-XML-Data-Select-Table.png) 

 The Power Query Editor preview updates and shows the FloatRates currency data. Click "Close and Load" in the top-left corner to add the data to your spreadsheet.

![Press Close and Load to add your XML data to your Excel spreadsheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Power-Query-Load-Data.png) 

 The data you import appears in a new worksheet, to which you can now refer when you need to convert currency.

 Most external data sources update hourly, but FloatRates only updates every 12 hours. If you want to update your data manually, click Data > Refresh All.

![Press Data > Refresh All to refresh your data sources manually](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Refresh-Data.png) 

##  Converting Currency in Microsoft Excel

 You can use the up-to-date data you imported to convert currency figures with a simple multiplication formula.

 Click the worksheet with your imported currency rates. If you're using FloatRates data, look at the exchange rates under the "exchangeRate" column. Note the cell that contains the rate of the currency to which you want to convert.

 Using our FloatRates U.S. dollar data, we see that to convert from U.S. dollars to British pounds, we need to use the GBP exchange rate in cell I3.

![Currency exchange rates, imported from an external data source in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-GBP-Currency-Rate.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Return to your existing worksheet, and type the USD price from which you want to convert into a cell. In a second cell, use the formula 

        `=A2*Sheet2!$I$3`
    
 , and replace "A2" with the cell that contains your USD price.

 Replace the second part of the formula with an [absolute reference](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/) to the cell in the "exchangeRate" column on your imported data worksheet that contains the exchange rate to which you want to convert.

![Various currency conversion prices in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Currency-Conversion.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the example above, Column A lists U.S. dollars. Column B lists the converted currency rates from U.S. dollars to British pounds (1 USD to GBP is in cell B2).

 When you change the absolute cell reference and use alternative data sources (like the FloatRates GBP data source to convert from GBP to other currencies), you can convert from any currency to another.

 You can also use a manual rate instead of an external data source to convert currency rates. Just set the exchange rate manually in a cell (in our example, cell B2), and the price in another (cell A3).

![Manual currency conversion in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Manual-Currency-Conversion.png) 

 The same multiplication formula converts your currency. However, if you're not using an external data source, you'll have to update the rate manually to see the correct price.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-top-5-ios-platforms-for-experiencing-classic-psp-games/"><u>[New] 2024 Approved Top 5 iOS Platforms for Experiencing Classic PSP Games</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-instant-facebook-beat-loader-for-2024/"><u>[New] Instant Facebook Beat Loader for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-convenient-methods-for-video-recording-on-youtube-for-2024/"><u>[Updated] Convenient Methods for Video Recording on YouTube for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722874435427-all-you-need-to-know-about-the-new-google-pixel-tablet-launch-info-and-hardware-details-revealed/"><u>All You Need to Know About The New Google Pixel Tablet - Launch Info and Hardware Details Revealed!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bridging-the-gap-between-zoom-and-social-media-streams/"><u>Bridging the Gap Between ZOOM and Social Media Streams</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/freeing-up-space-on-your-windows-11-system-a-comprehensive-guide/"><u>Freeing Up Space on Your Windows 11 System: A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-fix-pc-issues-preventing-windows-11-installation-successfully/"><u>How to Fix PC Issues Preventing Windows 11 Installation Successfully</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-implement-power-on-by-lan-functionality-on-windows-11/"><u>How to Implement Power On By LAN Functionality on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-landscapes-with-facebook-twitter-instagram-and-youtube/"><u>Mastering Social Media Landscapes with Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://techidaily.com/solutions-to-repair-corrupt-pdf-v17-file-by-stellar-guide/"><u>Solutions to Repair Corrupt PDF v1.7 File</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-players-of-online-networking-navigating-through-facebook-twitter-instagram-and-youtube/"><u>The Big Players of Online Networking: Navigating Through Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-apple-iphone-13-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from Apple iPhone 13 iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-social-media-impact-with-facebook-twitter-instagram-and-youtube-analysis/"><u>Understanding Social Media Impact with Facebook, Twitter, Instagram, and YouTube Analysis</u></a></li>
<li><a href="https://win-forum.techidaily.com/unpacking-the-powerhouses-of-digital-communication-facebook-twitter-instagram-and-youtube/"><u>Unpacking the Powerhouses of Digital Communication: Facebook, Twitter, Instagram & YouTube</u></a></li>
</ul></div>

