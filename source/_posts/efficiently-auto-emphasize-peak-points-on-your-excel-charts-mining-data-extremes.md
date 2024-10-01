---
title: Efficiently Auto-Emphasize Peak Points on Your Excel Charts - Mining Data Extremes
date: 2024-09-30T16:39:24.814Z
updated: 2024-10-01T17:18:42.805Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/a-tablet-with-an-excel-spreadsheet-and-a-chart-highlighting-the-maximum-and-minimum-values.jpg
---

## Efficiently Auto-Emphasize Peak Points on Your Excel Charts - Mining Data Extremes

### Quick Links

* [Step 1: Prepare Your Data](https://some-approaches.techidaily.com/the-editors-secret-smooth-transitions-in-premiere-pro-for-2024/)
* [Step 2: Create Your Chart](https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-samsung-galaxy-f54-5g-by-stellar-photo-recovery-android-mobile-photo-recover/)
* [Step 3: Add an Additional Column for Your Parameters](https://buynow-marvelous.techidaily.com/beginners-ultra-durable-aquatic-photography-gear/)
* [Step 4: Extract Your Parameters](https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-y100t-drfone-by-drfone-virtual-android/)
* [Step 5: Add this Data to the Chart](https://ai-vdieo-software.techidaily.com/new-design-beautiful-memories-online-photo-and-video-collage-editors/)
* [Step 6: Overlap the LARGE Series](https://extra-lessons.techidaily.com/new-comprehensive-understanding-leveraging-adobe-cloud-and-finding-alternatives/)
* [Step 7: Hide the Extra Table Column (Optional)](https://www.howtogeek.com/how-to-automatically-highlight-the-min-and-max-values-in-excel-charts/#step-7-hide-the-extra-table-column-optional)

 If you have a chart in Excel and want to emphasize the highest or lowest values in a way that changes with your data, changing them to a different color is the most effective method. Here's everything you need to know about how to do it.

 Here's what our chart will look like after running through the steps in this article.

![A completed sales chart with the three highest-value bars colored orange, and the remaining data bars colored blue.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/sales-chart-complete.png) 

##  Step 1: Prepare Your Data

 Start by creating your Excel table. As we run through the steps, we'll use a simple sales table with the day of the week in column A and total sales in column B.

![An unformatted Excel table with the day of the week in column A and number of sales in column B.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/unformatted-table.png) 

 Next, select all the data, and click "Format As Table" in the Styles group on the Home tab. Then, choose a design that works for you. As you can see, we've chosen a simple green design.

![An Excel table with the Format As Table drop-down opened.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/format-table.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080312/19272" target="_top" id="2080312">
  <img src="//a.impactradius-go.com/display-ad/19272-2080312" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080312/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Formatting your table is a crucial step, as it means that your chart will pick up any additional data you might add later on.

##  Step 2: Create Your Chart

 Now, you can create the chart for your table. Select all the data in your table (including the header row). Then, in the Insert tab on the ribbon, head to the Charts group, and open the chart drop-down selector.

![An Excel worksheet with data in a table selected, and the chart drop-down selector opened.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/create-chart-from-data.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938693/19272" target="_top" id="1938693">
  <img src="//a.impactradius-go.com/display-ad/19272-1938693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For our data, we've chosen a 2D clustered bar chart.

![An Excel worksheet with a table on the left and a corresponding chart on the right.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/table-and-chart.png) 

##  Step 3: Add an Additional Column for Your Parameters

 You could stop there, as you have a nicely-presented chart showing your data. However, we want the chart to automatically highlight certain values, which is especially useful if you have lots of data, and you want certain numbers to stand out.

 So, the next step is to add an additional column to your table to create the values that you want to be highlighted in your chart. To do this, move your cursor over the handle in the bottom-right corner of your table (your cursor will change to a two-way arrow), and click and drag it to the right.

![An Excel table with the table handle highlighted and an arrow showing the direction to click and drag the handle.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/add-column-to-table.png) 

 You will see a new column appear, which you will need to name according to what data you want to highlight in your chart. In our example, we want to highlight the three largest values.

![An Excel table with three columns and an arrow pointing to the header name (Largest 3) in the third column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/extra-column.png) 

##  Step 4: Extract Your Parameters

 We're now ready to use a formula to tell Excel what data we want to extract from our table.

 In the first cell under the new column's header, you'll need to use a combination of the IF function and the LARGE function. Here's the syntax:

=IF(_a_>=LARGE([_b_],_c_),_a,_"")

 where

* _a_ is the cell reference you want to compare to the rest of the data,
* _b_ is the column containing all the data you are comparing (the square brackets tell Excel that we're referencing the name of a column in a formatted table), and
* _c_ is the total number of high or low values you want to extract.

 Bear with us—this might seem confusing, but let's break the formula down to see how it works.

 In cell C2, we start by using the IF function to tell Excel that we are looking to make a comparison between values in our table.

=IF(

 We first want to tell Excel that we're looking to compare the value in cell B2 with the rest of the data.

=IF(**B2**

 In our case, we want to see if cell B2 is a larger value within the series, so we add the > (larger than) symbol.

=IF(B2**>**

 We now need to tell Excel that we're going to evaluate whether the value in cell B2 is one of the largest values in the Sales column. Take care when typing your brackets, and remember to embed the header name of the column containing your data in square brackets.

=IF(B2>**=LARGE([Sales],**

    
 If you want to extract the **lowest** values from the data, change the > symbol to <, and use SMALL instead of LARGE.

 Now, specify how many values you want to extract. In our case, we want to see if B2 is one of the three largest values in our data.

=IF(B2>=LARGE([Sales],**3),**

 Next, we want to tell Excel to extract the value into our third column if it is, indeed, one of the three largest within the array.

=IF(B2>=LARGE([Sales],3),**B2**

 Finally, if the value we're evaluating is not one of the highest three values, we want Excel to return a blank cell.

=IF(B2>=LARGE([Sales],3),B2,**"")**

 After you have typed your formula, press Enter. If the cell remains blank, it means that it's not one of the three highest values. If it is, indeed, one of the three highest values, it will duplicate the total where you have just typed your formula.

 Excel will assume you want to apply this to all cells in this column and automatically fill the rest in for you. If this doesn't happen, select the cell containing your formula, and [use the handle to AutoFill the rest of the column](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/).

![An Excel sheet containing a table with the largest three values extracted into an additional column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/largest-3-values-in-data.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Step 5: Add this Data to the Chart

 Now that you've applied your new parameters to your table, you're ready to add this to your chart.

 Select the chart, open "Chart Design" on the ribbon, and click "Select Data."

![An Excel sheet with a chart selected and 'Select Data' highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/select-data.png) 

 In the dialog box that opens, click "Add" under Legend Entries to add new data to your chart.

![An Excel sheet with the Select Data Source dialog box open, and 'Add' highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/add-data-source-1.png) 

 In the Edit Series window, you will see two fields to complete. First, clear both fields of any information they already contain. Now, click the empty Series Values field box and select the new data range you created in step 4.

 In our case, we would highlight cells C2 to C8\. Then, click the Series Name field box and select the table header for the new data range. In our case, we would select cell C1 (Largest 3). It might seem strange completing the bottom box before the top box, but this is important, because Excel won't let you give your data range a name until you've told it where the data is.

![The Edit Series dialog box in Excel with Series Values labelled as '1' and Series Name labelled as '2'.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/edit-series.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135395/19272" target="_top" id="2135395">
  <img src="//a.impactradius-go.com/display-ad/19272-2135395" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135395/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will then see the outcome in your graph, with an extra bar appearing next to each of the three largest values.

![An Excel chart next to a table. There are three arrows, each pointing from the new series of data in the table to its corresponding bar in the chart.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/series-added.png) 

 The final step is to make the new series overlap the existing series (that is to say, replace the largest three blue bars with the three orange bars).

##  Step 6: Overlap the LARGE Series

 To do this, double-click any of the newly added bars on your chart to open the Format Series Data pane to the right of your window.

 Then, click the drop-down arrow shown in the screenshot below, and click the name of the series you added—in our example, that's "Series Largest 3."

![An Excel chart with the Format Chart Area pane open and a drop-down arrow highlighted. The series name is also highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/format-data-series.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click the "Series Options" icon, and change "Series Overlap" to 100% by clicking and dragging the slider to the right.

![An Excel chart with the Series Options highlighted and opened, and the Series Overlap set to 100%.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/series-overlap.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will now see the final outcome—your chart highlights the max three values in your Excel chart!

 You can format the chart to suit your needs, including giving it a title or changing the colors. Right-click anywhere on the chart and choose "Format Chart Area" or "Format Plot Area," or left-click the very edge of the chart outline and click "+."

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Step 7: Hide the Extra Table Column (Optional)

 This final step is optional, depending on how you want your spreadsheet to look.

 If you want to hide the additional column in your table that shows the minimum or maximum parameters you have set, resulting in a tidier table, continue reading. If, however, you think you might change the minimum and maximum conditions down the line, skip this step, and head to the bottom of the article.

 First, you need to make sure your chart includes data that is contained within hidden cells. To do this, click the very edge of the chart outline, and click "Select Data" in the "Chart Design" Tab.

![An Excel spreadsheet with a chart selected, and 'Select Data' being clicked.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/select-data-2.png) 

 Then, click "Hidden And Empty Cells" in the Select Data Source window, and check the "Show Data In Hidden Rows And Columns" box.

!['Show Data In Hidden Rows And Columns' in the Hidden And Empty Cells Settings dialog box is checked.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/show-data-in-hidden-1.png) 

 Finally, right-click the column you want to hide (in our case, we'll right-click the column C header), and click "Hide."

![Column C selected with a right-click, and 'Hide" highlighted in the drop-down options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/hide-extra-column.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will then see your table appear as it did when you first formatted it, and the chart maintains the additional color feature you added.

 Right-click the column again and click "Unhide" if you want to bring your hidden column back into view.

 Here's our finished product!

![An Excel sheet with a chart whose top three values are a different color, and a table with the extra column hidden](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/data-added-to-chart-and-extra-column-hidden-from-the-table-1.png) 

 What's more, if you add additional rows to your table by clicking and dragging downwards from the bottom-right corner, your chart will automatically adjust to incorporate any new data you insert.

---

 Now that you've added an impressive, dynamic feature to your chart, check out some [more ways to make your chart stand out](https://vp-tips.techidaily.com/2024-approved-capture-breathtaking-scenes-on-iphone-with-ease/).

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
<li><a href="https://vp-tips.techidaily.com/new-memories-in-motion-a-step-by-step-guide-for-digital-conversion-for-2024/"><u>[New] Memories in Motion A Step-by-Step Guide for Digital Conversion for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/loggers-money-saving-camera-recommendations/"><u>[New] Vloggers' Money-Saving Camera Recommendations</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-zero-cost-image-booster-online-plus-mobile-app/"><u>[Updated] Best Zero-Cost Image Booster Online + Mobile App</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-a-step-by-step-approach-to-typography-addition-in-ae/"><u>[Updated] In 2024, A Step-by-Step Approach to Typography Addition in AE</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-transform-your-devices-tone-swiftly-with-these-leading-chrome-apps/"><u>[Updated] Transform Your Device's Tone Swiftly With These Leading Chrome Apps</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-to-forcibly-deleting-files-in-windows-11-with-revo-uninstaller/"><u>Complete Guide to Forcibly Deleting Files in Windows 11 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/fix-your-crashing-file-explorer-7-essential-troubleshooting-steps/"><u>Fix Your Crashing File Explorer: 7 Essential Troubleshooting Steps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unravel-the-mystery-of-scouring-exceptional-photos-on-pexels/"><u>In 2024, Unravel the Mystery of Scouring Exceptional Photos on Pexels</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-social-media-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Social Media with Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/revo-uninstaller-pro-5-the-ultimate-software-removal-solution/"><u>Revo Uninstaller Pro 5: The Ultimate Software Removal Solution</u></a></li>
<li><a href="https://techtrends.techidaily.com/revolutionize-your-designs-top-er-reviewed-by-experts-in-their-fields/"><u>Revolutionize Your Designs: Top Er Reviewed by Experts in Their Fields.</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-disabling-and-uninstalling-browser-add-ons-in-windows-11/"><u>Step-by-Step Guide: Disabling & Uninstalling Browser Add-Ons in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-digital-sphere-exploring-facebook-twitter-instagram-and-youtube/"><u>The Big Four in Digital Sphere: Exploring Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-in-social-sphere-connecting-with-facebook-twitter-instagram-and-youtube/"><u>The Big Four in Social Sphere: Connecting with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://fox-web3.techidaily.com/unlocking-hidden-gems-discover-special-content-with-flipbuilder/"><u>Unlocking Hidden Gems: Discover Special Content with FlipBuilder</u></a></li>
</ul></div>

