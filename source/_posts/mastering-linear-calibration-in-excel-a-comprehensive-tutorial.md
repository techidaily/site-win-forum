---
title: "Mastering Linear Calibration in Excel: A Comprehensive Tutorial"
date: 2024-08-28T04:29:20.094Z
updated: 2024-08-29T04:29:20.094Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e24af9d0b47d7bf3dcde61ab73ef441dcda155d4ef5a243e1a2546d643282d46.jpg
---

## Mastering Linear Calibration in Excel: A Comprehensive Tutorial

### Quick Links

* [What is a Calibration Curve and How is Excel Useful When Creating One?](https://ai-video-tools.techidaily.com/speed-up-your-storytelling-time-lapse-video-creation-in-final-cut-pro-for-2024/)
* [Let's Look at an Example](https://location-social.techidaily.com/in-2024-how-to-change-your-oppo-f25-pro-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/)

 Excel has built-in features that you can use to display your calibration data and calculate a line-of-best-fit. This can be helpful when you are writing a chemistry lab report or programming a correction factor into a piece of equipment.

 In this article, we'll look at how to use Excel to create a chart, plot a linear calibration curve, display the calibration curve's formula, and then set up simple formulas with the SLOPE and INTERCEPT functions to use the calibration equation in Excel.

##  What is a Calibration Curve and How is Excel Useful When Creating One?

 To perform a calibration, you compare the readings of a device (like the temperature that a thermometer displays) to known values called standards (like the freezing and boiling points of water). This lets you create a series of data pairs that you'll then use to develop a calibration curve.

 A two-point calibration of a thermometer using the freezing and boiling points of water would have two data pairs: one from when the thermometer is placed in ice water (32**°**F or 0**°**C) and one in boiling water (212**°**F or 100**°**C). When you plot those two data pairs as points and draw a line between them (the calibration curve), then assuming the response of the thermometer is linear, you could pick any point on the line that corresponds to the value the thermometer displays, and you could find the corresponding "true" temperature.

 So, the line is essentially filling in the information between the two known points for you so that you can be reasonably certain when estimating the actual temperature when the thermometer is reading 57.2 degrees, but when you have never measured a "standard" that corresponds to that reading.

 Excel has features that allow you to plot the data pairs graphically in a chart, add a trendline (calibration curve), and display the calibration curve's equation on the chart. This is useful for a visual display, but you can also calculate the formula of the line using Excel's SLOPE and INTERCEPT functions. When you enter these values into simple formulas, you will be able to automatically calculate the "true" value based on any measurement.

##  Let's Look at an Example

 For this example, we will develop a calibration curve from a series of ten data pairs, each consisting of an X-value and a Y-value. The X-values will be our "standards," and they could represent anything from the concentration of a chemical solution we are measuring using a scientific instrument to the input variable of a program that controls a marble launching machine.

 The Y-values will be the "responses," and they would represent the reading the instrument provided when measuring each chemical solution or the measured distance of how far away from the launcher the marble landed using each input value.

 After we graphically depict the calibration curve, we will use the SLOPE and INTERCEPT functions to calculate the calibration line's formula and determine the concentration of an "unknown" chemical solution based on the instrument's reading or decide what input we should give the program so that the marble lands a certain distance away from the launcher.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
###  Step One: Create Your Chart

 Our simple example spreadsheet consists of two columns: X-Value and Y-Value.

![creating an x-value and y-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-01.png) 

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Let's start by selecting the data to plot in the chart.

 First, select the 'X-Value' column cells.

![select the x-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-02.png) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now press the Ctrl key and then click the Y-Value column cells.

![hold Ctrl while clicking the Y-value column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-03.png) 

 Go to the "Insert" tab.

![insert tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-04.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Navigate to the "Charts" menu and select the first option in the "Scatter" drop-down.

![choose charts &gt; scatter](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-05.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 A chart will appear containing the data points from the two columns.

![the chart appears](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-06.png) 

 Select the series by clicking on one of the blue points. Once selected, Excel outlines the points will be outlined.

![select the data points](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-07.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Right-click one of the points and then select the "Add Trendline" option.

![choose the add trendline option](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-08.png) 

 A straight line will appear on the chart.

![the trendline now displays on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-09.png) 

 On the right side of the screen, the "Format Trendline" menu will appear. Check the boxes next to "Display Equation on chart" and "Display R-squared value on chart." The R-squared value is a statistic that tells you how closely the line fits the data. The best R-squared value is 1.000, which means every data point touches the line. As the differences between the data points and the line grow, the r-squared value drops, with 0.000 being the lowest possible value.

![the format trendline pane](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-10.png) 

 The equation and R-squared statistic of the trendline will appear on the chart. Note that the correlation of the data is very good in our example, with an R-squared value of 0.988.

 The equation is in the form "Y = Mx + B," where M is the slope and B is the y-axis intercept of the straight line.

![the equations now show on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-11.png) 

 Now that the calibration is complete, let's work on customizing the chart by editing the title and adding axis titles.

 To change the chart title, click on it to select the text.

![changing the chart title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-12.png) 

 Now type in a new title that describes the chart.

![the new titles appears on the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-13.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 To add titles to the x-axis and y-axis, first, navigate to Chart Tools > Design.

![head to chart tools &gt; design](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-14.png) 

 Click the "Add a Chart Element" drop-down.

![click the add chart element button](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-15.png) 

 Now, navigate to Axis Titles > Primary Horizontal.

![head to axis tools &gt; primary horizontal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-16.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 An axis title will appear.

![the axis title appears](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-17.png) 

 To rename the axis title, first, select the text, and then type in a new title.

![changing the axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-18.png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now, head to Axis Titles > Primary Vertical.

![adding a primary vertical axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-19.png) 

 An axis title will appear.

![showing the new axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-20.png) 

 Rename this title by selecting the text and typing in a new title.

![renaming the axis title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-21.png) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Your chart is now complete.

![viewing the complete chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-22.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
###  Step Two: Calculate the Line Equation and R-Squared Statistic

 Now let's calculate the line equation and R-squared statistic using Excel's built-in SLOPE, INTERCEPT, and CORREL functions.

 To our sheet (in row 14) we've added titles for those three functions. We'll perform the actual calculations in the cells beneath those titles.

 First, we will calculate the SLOPE. Select cell A15.

![select the cell for the slope data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-23.png) 

 Navigate to Formulas > More Functions > Statistical > SLOPE.

![Navigate to Formulas &gt; More Functions &gt; Statistical &gt; SLOPE](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-24.png) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
 The Function Arguments window pops up. In the "Known\_ys" field, select or type in the Y-Value column cells.

![select or type in the Y-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-25.png) 

 In the "Known\_xs" field, select or type in the X-Value column cells. The order of the 'Known\_ys' and 'Known\_xs' fields matters in the SLOPE function.

![select or type in the X-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-26.png) 

 Click "OK." The final formula in the formula bar should look like this:

        `=SLOPE(C3:C12,B3:B12)`
    
 Note that the value returned by the SLOPE function in cell A15 matches the value displayed on the chart.

![slope value displayed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-27.png) 

 Next, select cell B15 and then navigate to Formulas > More Functions > Statistical > INTERCEPT.

![navigate to Formulas &gt; More Functions &gt; Statistical &gt; INTERCEPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-28.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The Function Arguments window pops up. Select or type in the Y-Value column cells for the "Known\_ys" field.

![Select or type in the Y-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-29.png) 

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
 Select or type in the X-Value column cells for the "Known\_xs" field. The order of the 'Known\_ys' and 'Known\_xs' fields also matters in the INTERCEPT function.

![Select or type in the X-Value column cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-30.png) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 Click "OK." The final formula in the formula bar should look like this:

        `=INTERCEPT(C3:C12,B3:B12)`
    
 Note that the value returned by the INTERCEPT function matches the y-intercept displayed in the chart.

![showing the intercept function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-31.png) 

 Next, select cell C15 and navigate to Formulas > More Functions > Statistical > CORREL.

![navigate to Formulas &gt; More Functions &gt; Statistical &gt; CORREL](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-32.png) 

 The Function Arguments window pops up. Select or type in either of the two cell ranges for the "Array1" field. Unlike SLOPE and INTERCEPT, the order does not affect the result of the CORREL function.

![enter the first cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-33.png) 

 Select or type in the other of the two cell ranges for the "Array2" field.

![enter the second cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-34.png) 

 Click "OK." The formula should look like this in the formula bar:

        `=CORREL(B3:B12,C3:C12)`
    
 Note that the value returned by the CORREL function does not match the "r-squared" value on the chart. The CORREL function returns "R," so we must square it to calculate "R-squared."

![showing the correl function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-35.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 Click inside the Function Bar and add "^2" to the end of the formula to square the value returned by the CORREL function. The completed formula should now look like this:

        `=CORREL(B3:B12,C3:C12)^2`
    
 Press Enter.

![viewing the completed formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-36.png) 

 After changing the formula, the "R-squared" value now matches the one displayed in the chart.

![the r-squared value now matches](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-37.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step Three: Set Up Formulas For Quickly Calculating Values

 Now we can use these values in simple formulas to determine the concentration of that "unknown" solution or what input we should enter into the code so that the marble flies a certain distance.

 These steps will set up the formulas required for you to be able to enter an X-value or a Y-value and get the corresponding value based on the calibration curve.

![enter an X-value or a Y-value and get the corresponding value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-38.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 The equation of the line-of-best-fit is in the form "Y-value = SLOPE \* X-value + INTERCEPT," so solving for the "Y-value" is done by multiplying the X-value and SLOPE and then adding the INTERCEPT.

![values displayed based on input](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-39.png) 

 As an example, we put zero in as the X-value. The Y-value returned should be equal to the INTERCEPT of the line of best fit. It matches, so we know the formula is working correctly.

![showing the zero as the X-value being equal to the INTERCEPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-40.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 Solving for the X-value based on a Y-value is done by subtracting the INTERCEPT from the Y-value and dividing the result by the SLOPE:

X-value=(Y-value-INTERCEPT)/SLOPE

![solving for an x value based on a y value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-41.png) 

 As an example, we used the INTERCEPT as a Y-value. The X-value returned should be equal to zero, but the value returned is 3.14934E-06\. The value returned is not zero because we inadvertently truncated the INTERCEPT result when typing the value. The formula is working correctly, though, because the result of the formula is 0.00000314934, which is essentially zero.

![showing a truncated result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-42.png) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can enter in any X-value you'd like into the first thick-bordered cell and Excel will calculate the corresponding Y-value automatically.

![solving Y for an x value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-43.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Entering any Y-value into the second thick-bordered cell will give the corresponding X-value. This formula is what you would use to calculate the concentration of that solution or what input is needed to launch the marble a certain distance.

![solving x for a y value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Calibration-Curve-44.png) 

 In this case, the instrument reads "5" so the calibration would suggest a concentration of 4.94 or we want the marble to travel five units of distance so the calibration suggests we enter 4.94 as the input variable for the program controlling the marble launcher. We can be reasonably confident in these results because of the high R-squared value in this example.

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-ultimate-handbook-for-watching-facebook-livestreams/"><u>[New] 2024 Approved  The Ultimate Handbook for Watching Facebook Livestreams</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-evaluating-tseries-business-model-with-youtube-viewership-metrics/"><u>[New] Evaluating TSeries' Business Model with YouTube Viewership Metrics</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-expert-guide-screen-capture-on-windows-8-devices-for-2024/"><u>[New] Expert Guide  Screen Capture on Windows 8 Devices for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-maximizing-video-longevity-saving-snaps-on-android-and-mac/"><u>[New] In 2024, Maximizing Video Longevity  Saving Snaps on Android & Mac</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-visual-treasures-a-pexels-search-guide/"><u>[New] Unleashing Visual Treasures  A Pexels Search Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-easy-to-follow-strategies-recording-hulu-across-windowsmacandroidios/"><u>[Updated] 2024 Approved  Easy-to-Follow Strategies  Recording Hulu Across Windows/Mac/Android/iOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-make-profitable-youtube-ads-for-free-for-2024/"><u>[Updated] How To Make Profitable YouTube Ads for Free for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-navigating-legalities-in-skype-call-audio-preservation/"><u>[Updated] In 2024, Navigating Legalities in Skype Call Audio Preservation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-parody-pointers-from-script-to-screenplay/"><u>[Updated] Parody Pointers  From Script to Screenplay</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-the-ultimate-screen-recorders-guide-trusted-recommendations-for-2024/"><u>[Updated] The Ultimate Screen Recorders Guide - Trusted Recommendations for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-elevate-your-stream-game-mastering-onestream-platforms/"><u>2024 Approved  Elevate Your Stream Game  Mastering OneStream Platforms</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-tailoring-humor-with-9gag-your-personal-meme-making-manual/"><u>2024 Approved  Tailoring Humor with 9GAG  Your Personal Meme Making Manual</u></a></li>
<li><a href="https://win-forum.techidaily.com/a-comprehensive-guide-to-leading-social-platforms-facebook-twitter-instagram-and-youtube/"><u>A Comprehensive Guide to Leading Social Platforms: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/advanced-strategies-for-capturing-fb-chats-for-2024/"><u>Advanced Strategies for Capturing FB Chats for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-on-leading-sites-facebook-twitter-instagram-and-youtube/"><u>Connect and Engage on Leading Sites: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-with-audience-through-major-platforms-facebook-twitter-instagram-and-youtube-explained/"><u>Connect and Engage with Audience Through Major Platforms: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-billions-an-in-depth-look-at-facebook-twitter-instagram-and-youtube/"><u>Connecting Billions: An In-Depth Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-giants-unveiled-mastering-interactions-on-facebook-twitter-instagram-and-youtube/"><u>Digital Giants Unveiled: Mastering Interactions on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/easily-undo-recent-windows-11-changes-with-this-simple-method/"><u>Easily Undo Recent Windows 11 Changes with This Simple Method</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-guide-updating-your-pcs-hardware-drivers-on-windows-10-with-revo-uninstaller/"><u>Easy Guide: Updating Your PC's Hardware Drivers on Windows 10 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-determine-the-powershell-build-in-your-windows-1-confirming-microsoft-edges-current-release-browser-defense-pro/"><u>Easy Steps to Determine the PowerShell Build in Your Windows 1# Confirming Microsoft Edge's Current Release - Browser Defense Pro</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-refresh-your-pc-updating-windows-10-driver-software/"><u>Easy Steps to Refresh Your PC: Updating Windows 10 Driver Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-ways-to-delete-user-settings-in-windows-11-via-revouninstaller-software/"><u>Effective Ways to Delete User Settings in Windows 11 via RevoUninstaller Software</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-efficiently-flush-dns-caches-across-both-windows-10-and-windows-11-platforms/"><u>Expert Advice: Efficiently Flush DNS Caches Across Both Windows 10 and Windows 11 Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-fixes-for-clearing-up-dark-screen-troubles-on-your-star-wars-battlefront-2-consolepc-setup/"><u>Expert Fixes for Clearing Up Dark Screen Troubles on Your Star Wars Battlefront 2 Console/PC Setup</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-giants-of-digital-communication-facebook-twitter-instagram-and-youtube-explained/"><u>Exploring Giants of Digital Communication: Facebook, Twitter, Instagram & YouTube Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-social-media-giants-a-guide-to-facebook-twitter-instagram-and-youtube/"><u>Exploring Social Media Giants: A Guide to Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-updating-graphics-and-sound-cards-in-windows-11-made-simple/"><u>Guide: Updating Graphics and Sound Cards in Windows 11 Made Simple</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-xiaomi-14-ultra-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Xiaomi 14 Ultra</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-15-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 15 Pro Max without iTunes? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-xr-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-optimize-and-reduce-high-disk-resource-consumption-in-windows/"><u>How to Optimize and Reduce High Disk Resource Consumption in Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/leading-social-networks-for-engagement-facebook-twitter-instagram-youtube-uncovered/"><u>Leading Social Networks for Engagement: Facebook, Twitter, Instagram, YouTube Uncovered</u></a></li>
<li><a href="https://win-forum.techidaily.com/learn-how-to-check-and-update-your-windows-npowershell-version/"><u>Learn How to Check and Update Your Windows nPowerShell Version</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-fix-for-peak-disk-usage-spike-on-your-windows-10-device-top-tips-and-tricks/"><u>Mastering the Fix for Peak Disk Usage Spike on Your Windows 10 Device: Top Tips & Tricks</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-windows-registry-edit-add-or-remove-key-steps/"><u>Mastering the Windows Registry: Edit, Add, or Remove Key Steps</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-big-four-of-online-networking-facebook-twitter-instagram-youtube/"><u>Navigating The Big Four of Online Networking: Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-online-networking-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Online Networking: Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://driver-install.techidaily.com/new-drivers-for-geforce-gtx-1060-available/"><u>New Drivers for GeForce GTX 1060 Available</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-guide-terminating-unresponsive-programs-in-windows-11/"><u>Quick Guide: Terminating Unresponsive Programs in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-superuser-access-for-applications-a-step-by-step-tutorial-for-windows-11-users/"><u>Secure Superuser Access for Applications: A Step-by-Step Tutorial for Windows 11 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915274991-social-media-success-strategies-for-facebook-twitter-instagram-and-you/"><u>Social Media Success Strategies for Facebook, Twitter, Instagram & You.</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915317189-social-media-titans-delving-into-facebook-twitter-instagram-and-youtubes-success/"><u>Social Media Titans: Delving Into Facebook, Twitter, Instagram and YouTube's Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-cookie-trails-from-your-windows-10-and-android-devices/"><u>Step-by-Step Guide: Clearing Cookie Trails From Your Windows 10 & Android Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-windows-10-system-cache-with-ease/"><u>Step-by-Step Guide: Clearing Windows 10 System Cache with Ease</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-clearing-your-domain-name-system-cache-on-windows-1011/"><u>Step-by-Step Guide: Clearing Your Domain Name System Cache on Windows 10/11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-enabling-wake-on-lan-feature-on-windows-11/"><u>Step-by-Step Guide: Enabling Wake-on-LAN Feature on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-flushing-your-windows-10-pcs-memory/"><u>Step-by-Step Guide: Flushing Your Windows 10 PC's Memory</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-updating-your-windows-10-hardware-drivers-easily/"><u>Step-by-Step Guide: Updating Your Windows 10 Hardware Drivers Easily</u></a></li>
<li><a href="https://extra-resources.techidaily.com/swiftly-restoring-eliminated-reddit-content/"><u>Swiftly Restoring Eliminated Reddit Content</u></a></li>
<li><a href="https://ai-voice.techidaily.com/the-best-text-voice-generators-for-all-platforms-for-2024/"><u>The Best Text Voice Generators for All Platforms for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-digital-giants-mastering-content-on-facebook-twitter-instagram-and-youtube/"><u>The Digital Giants: Mastering Content on Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouses-of-digital-connection-facebook-twitter-instagram-and-youtube/"><u>The Powerhouses of Digital Connection: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-giants-for-digital-engagement-fb-twitter-ig-and-yt/"><u>The Quintessential Social Giants for Digital Engagement: FB, TWITTER, IG and YT</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-four-online-networking-sites-facebook-twitter-instagram-youtube/"><u>Top Four Online Networking Sites: Facebook | Twitter | Instagram | YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-platforms-unite-navigating-facebook-twitter-instagram-and-youtube/"><u>Top Social Platforms Unite: Navigating Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlocking-new-possibilities-configuring-windows-11-on-cpus-not-officially-supported/"><u>Unlocking New Possibilities: Configuring Windows 11 on CPUs Not Officially Supported</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/bes-mini-millionaire-how-a-kid-earned-big-bucks-daily/"><u>YouTube's Mini Millionaire  How a Kid Earned Big Bucks Daily</u></a></li>
</ul></div>
