---
title: Detecting Empty Cells Using the ISBLANK Function in Microsoft Excel
date: 2024-09-09T16:24:56.460Z
updated: 2024-09-16T16:47:19.981Z
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
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the selected cell, type the following function and press Enter. In this function, replace `C2` with the cell that you want to check.

=ISBLANK(C2)

![Enter the ISBLANK function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/2-use-isblank-function-excel.png) 

 To [use the function for all your records](https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-magic-6-drfone-by-drfone-virtual-android/) in the spreadsheet, from the bottom-right corner of the cell where you entered the function, drag downwards covering all your rows.

![The result of the ISBLANK function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/3-excel-isblank-function-result.png) 

 Now you know what cell is and isn't blank in your spreadsheet.

Related: [How to Fill Excel Cells Automatically with Flash Fill and Auto Fill](https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-magic-6-drfone-by-drfone-virtual-android/) 

##  Perform an Action When a Cell Is Blank or Non-Blank

 Often, you may want to [perform an action depending on your cell's status](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/). You may want to display a message that says something when your cell is blank and says something else when your cell isn't blank.

 To do that, combine the `ISLBLANK` function with Excel's `IF` function.

 First, open your spreadsheet with Excel. Then, click the cell where you want to display your function's result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/4-choose-cell-excel.png) 

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In your selected cell, type the following function and press Enter. Here, replace `C2` with the cell that you want to check (if it's blank or not), `Sale Not Made` with the text you want to use if the cell is blank, and `Sale Made` with the text if the cell is not blank.

=IF(ISBLANK(C2),"Sale Not Made","Sale Made")

 To use the function for all your records in the spreadsheet, from the bottom-right corner of the cell where you've entered the function, drag downwards covering all your records.

![The result of the IF and ISBLANK functions.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/12/5-excel-isblank-if-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-unveiling-social-media-puzzles-how-to-use-facebook-insights/"><u>[New] In 2024, Unveiling Social Media Puzzles How to Use Facebook Insights</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-starlight-moment-capture-analysis/"><u>[New] Starlight Moment Capture Analysis</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-snapperview-4-review-synopsis/"><u>2024 Approved SnapperView 4 Review Synopsis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitters-visual-treats-free-video-to-gif-transformation/"><u>2024 Approved Twitter's Visual Treats Free Video to Gif Transformation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-oppo-a1-5g-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Oppo A1 5G Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-game-plan-for-getting-your-product-in-front-of-a-youtubers-audience-for-2024/"><u>The Game Plan for Getting Your Product in Front of a Youtuber's Audience for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-how-to-stop-elex-ii-from-continuously-failing-on-pc/"><u>Troubleshooting Guide: How To Stop Elex II From Continuously Failing On PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-power-of-your-pc-discover-13-methods-to-access-windows-11-settings/"><u>Unlock the Power of Your PC: Discover 13 Methods to Access Windows 11 Settings</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-your-browser-freedom-a-comprehensive-tutorial-to-deactivate-microsoft-smartscreen-filter-in-windows-11-and-8/"><u>Unlock Your Browser Freedom: A Comprehensive Tutorial to Deactivate Microsoft SmartScreen Filter in Windows 11 and 8</u></a></li>
<li><a href="https://win-forum.techidaily.com/unseen-transformation-how-the-true-artificial-intelligence-shift-is-happening/"><u>Unseen Transformation: How the True Artificial Intelligence Shift Is Happening</u></a></li>
</ul></div>

