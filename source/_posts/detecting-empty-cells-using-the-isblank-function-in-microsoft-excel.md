---
title: Detecting Empty Cells Using the ISBLANK Function in Microsoft Excel
date: 2024-09-17T16:02:48.686Z
updated: 2024-09-21T16:25:55.157Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/05/MS-excel-logo-675.png
---

## Detecting Empty Cells Using the ISBLANK Function in Microsoft Excel

### Quick Links

* [What Is the ISBLANK Function in Excel?](https://some-skills.techidaily.com/in-2024-understanding-telegram-advertising-for-new-marketing-entrants/)
* [Check If a Cell Is Blank With Excel's ISBLANK Function](https://facebook-clips.techidaily.com/new-enhancing-fb-video-content-with-streamlined-captioning-tactics/)
* [Perform an Action When a Cell Is Blank or Non-Blank](https://youtube-web.techidaily.com/n-2024-how-to-get-free-views-on-youtube-2-easy-ways/)

### Key Takeaways

 You can use Excel's ISBLANK function with a cell reference as the argument, for example "=ISBLANK(A1)", to check if that cell is blank or non-blank. Combine it with other functions to perform actions depending on the result.

 Microsoft Excel's 

        `ISBLANK`
    
 function enables you to check whether a cell is blank or not. You can use this function in conjunction with the `IF` function to determine what happens to your cells when they're blank or non-blank. Here's how to do it.

Related: [How to Count Blank or Empty Cells in Microsoft Excel](https://fox-blue.techidaily.com/2024-approved-revel-in-richness-your-pcs-pathway-to-exceptional-video-quality/) 

##  What Is the ISBLANK Function in Excel?

 Excel's 

        `ISBLANK`
    
 function lets you check if the specified cell is blank or not. If the cell is blank, the function retrieves a 

        `TRUE`
    
 value. If the cell is not blank, you get a 

        `FALSE`
    
 value. You can use these values with other Excel functions, like `IF` , to perform actions on or in response to your blank and non-blank cells.

 The syntax of the 

        `ISBLANK`
    
 function is:

=ISBLANK(value)

 Here, `value` refers to the reference of the cell that you want to check. So if you want to check whether or not cell A1 is blank, you would insert `A1` in place of `value`.

 Excel also offers other functions for working with blank cells, like `COUNTBLANK` that gives you the [total count of blank cells](https://fox-blue.techidaily.com/2024-approved-revel-in-richness-your-pcs-pathway-to-exceptional-video-quality/) in the specified range. If you already know whether a cell is blank or not but want to know what type of value it contains, you can use functions like `ISNUMBER` to check if a specified cell contains any numbers, or `ISTEXT` to check if a cell has a text value.

Related: [How to Use the IS Functions in Microsoft Excel](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) 

##  Check If a Cell Is Blank With Excel's ISBLANK Function

 To use the function, first, open your spreadsheet with the Excel app and click the cell where you want to display the function's result.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/1-select-cell-excel.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the selected cell, type the following function and press Enter. In this function, replace `C2` with the cell that you want to check.

=ISBLANK(C2)

![Enter the ISBLANK function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/2-use-isblank-function-excel.png) 

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To [use the function for all your records](https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-magic-6-drfone-by-drfone-virtual-android/) in the spreadsheet, from the bottom-right corner of the cell where you entered the function, drag downwards covering all your rows.

![The result of the ISBLANK function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/3-excel-isblank-function-result.png) 

 Now you know what cell is and isn't blank in your spreadsheet.

Related: [How to Fill Excel Cells Automatically with Flash Fill and Auto Fill](https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-magic-6-drfone-by-drfone-virtual-android/) 

##  Perform an Action When a Cell Is Blank or Non-Blank

 Often, you may want to [perform an action depending on your cell's status](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/). You may want to display a message that says something when your cell is blank and says something else when your cell isn't blank.

 To do that, combine the `ISLBLANK` function with Excel's `IF` function.

 First, open your spreadsheet with Excel. Then, click the cell where you want to display your function's result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/4-choose-cell-excel.png) 

 In your selected cell, type the following function and press Enter. Here, replace `C2` with the cell that you want to check (if it's blank or not), `Sale Not Made` with the text you want to use if the cell is blank, and `Sale Made` with the text if the cell is not blank.

=IF(ISBLANK(C2),"Sale Not Made","Sale Made")

 To use the function for all your records in the spreadsheet, from the bottom-right corner of the cell where you've entered the function, drag downwards covering all your records.

![The result of the IF and ISBLANK functions.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/5-excel-isblank-if-function-result.png) 

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And you now have your chosen text displayed for your blank and non-blank cells.

Related: [How to Skip Pasting Blank Cells When Copying in Microsoft Excel](https://extra-information.techidaily.com/new-brand-alliances-elevating-youtube-content/)

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
<li><a href="https://win-forum.techidaily.com/apeaac-movavi/"><u>免費線上APE到AAC轉換解決方案 - 為動態影片提供全天候服務的Movavi編輯器</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/conversion-gratuite-de-fichiers-m4a-a-mp3-en-ligne-avec-movavi/"><u>Conversion Gratuite De Fichiers M4A À MP3 en Ligne Avec Movavi</u></a></li>
<li><a href="https://win-forum.techidaily.com/convert-images-for-free-with-movavis-jpg-to-jpeg-tool-easy-and-reliable-image-format-change/"><u>Convert Images for Free with Movavi's JPG to JPEG Tool - Easy and Reliable Image Format Change</u></a></li>
<li><a href="https://win-forum.techidaily.com/devenir-un-maitre-de-la-caricature-guide-simple-pour-convertir-votre-photo-en-un-bel-dessin/"><u>Devenir Un Maître De La Caricature: Guide Simple Pour Convertir Votre Photo en Un Bel Dessin</u></a></li>
<li><a href="https://fox-that.techidaily.com/fix-the-mysterious-vanishing-of-app-icons-from-your-iphone-quick-solutions-inside/"><u>Fix the Mysterious Vanishing of App Icons From Your iPhone – Quick Solutions Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-the-widgets-toolbar-in-windows-11/"><u>How to Enable the Widgets Toolbar in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-yuva-2-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Yuva 2</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-lava-agni-2-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Lava Agni 2 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-honor-magic5-ultimate-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Honor Magic5 Ultimate Location Settings | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-mastering-podcast-name-selection-step-by-step-guide-plus-50plus-top-ideas-list/"><u>In 2024, Mastering Podcast Name Selection Step-by-Step Guide + 50+ Top Ideas List</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/masterful-video-starts-get-them-for-free-for-2024/"><u>Masterful Video Starts, Get Them for Free for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/stop-life-is-strange-true-colors-from-crashing-effective-fix-and-tips/"><u>Stop Life Is Strange: True Colors From Crashing: Effective Fix & Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/subissione-rapida-di-wmv-a-jpg-online-gratuita-con-convertitore-web-movavi/"><u>Subissione Rapida Di WMV a JPG Online Gratuita Con Convertitore Web - Movavi</u></a></li>
<li><a href="https://win-forum.techidaily.com/transforma-sus-archivos-ogv-en-wmv-de-manera-gratuita-utilizando-el-servicio-en-linea-de-movavi/"><u>Transforma Sus Archivos OGV en WMV De Manera Gratuita Utilizando El Servicio en Línea De Movavi</u></a></li>
</ul></div>

