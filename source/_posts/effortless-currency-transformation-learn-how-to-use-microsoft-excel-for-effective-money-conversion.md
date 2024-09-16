---
title: "Effortless Currency Transformation: Learn How to Use Microsoft Excel for Effective Money Conversion"
date: 2024-09-11T16:56:32.749Z
updated: 2024-09-16T16:41:19.565Z
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

 Return to your existing worksheet, and type the USD price from which you want to convert into a cell. In a second cell, use the formula 

        `=A2*Sheet2!$I$3`
    
 , and replace "A2" with the cell that contains your USD price.

 Replace the second part of the formula with an [absolute reference](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/) to the cell in the "exchangeRate" column on your imported data worksheet that contains the exchange rate to which you want to convert.

![Various currency conversion prices in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/Excel-Currency-Conversion.png) 

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-broadcast-elegance-gamers-guide-to-using-obs/"><u>[New] 2024 Approved Broadcast Elegance Gamers' Guide to Using OBS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-art-of-disregarding-harmful-youtube-comments/"><u>[New] The Art of Disregarding Harmful YouTube Comments</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-top-ranked-instagram-tunes-and-secrets-for-exceptional-call-alerts-for-2024/"><u>[Updated] Top-Ranked Instagram Tunes & Secrets for Exceptional Call Alerts for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/dominant-giants-in-digital-interaction-facebook-twitter-instagram-and-youtube/"><u>Dominant Giants in Digital Interaction: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-with-social-giants-facebook-twitter-instagram-and-youtube/"><u>Engage with Social Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://some-skills.techidaily.com/get-your-personalized-internet-access-with-spacexs-new-portable-starlink-mini-device/"><u>Get Your Personalized Internet Access with SpaceX’s New Portable Starlink Mini Device</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-open-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock OnePlus Open Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-iphone-11-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your iPhone 11 on MetroPCS</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-online-communication-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Online Communication: Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-challenges-repairing-steam-errors-related-to-disk-operations/"><u>Overcoming Challenges: Repairing Steam Errors Related to Disk Operations</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915430381-troubleshooting-the-plan-not-executed-issue-on-windows-11/"><u>Troubleshooting the Plan Not Executed Issue on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-techniques-for-bypassing-default-deletion-protocols-on-windows-revo-uninstaller-tips/"><u>Ultimate Techniques for Bypassing Default Deletion Protocols on Windows: Revo Uninstaller Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/why-cant-i-open-my-application-diagnosing-and-repairing-launch-errors-on-a-pc/"><u>Why Can't I Open My Application? Diagnosing and Repairing Launch Errors on a PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

