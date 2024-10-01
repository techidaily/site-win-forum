---
title: "Step-by-Step Guide: Naming Cell Ranges Efficiently in Microsoft Excel"
date: 2024-09-25T16:38:14.711Z
updated: 2024-10-01T16:09:10.515Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/184d7cf1dfbfc8948b40afe261697d83b7fb70b650978462e7e0c6bc450abb26.png
---

## Step-by-Step Guide: Naming Cell Ranges Efficiently in Microsoft Excel

### Quick Links

* [How to Create a Name for a Cell or a Range of Cells Using the Name Box](https://hardware-tips.techidaily.com/cooler-masters-revolutionary-ai-thermal-paste-enhanced-performance-with-diamond-nanotechnology-in-cryofuse-5/)
* [How to Edit Names Using the Name Manager](https://some-guidance.techidaily.com/new-the-ultimate-list-of-livestream-streaming-strategies/)
* [How to Delete a Name Using the Name Manager](https://data-safeguard.techidaily.com/seamless-data-gathering-advanced-techniques-with-the-power-of-cookiebot/)
* [How to Create a Name Using the "New Name" Dialog Box](https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/)
* [How to Use a Name to Represent a Constant Value](https://extra-guidance.techidaily.com/updated-inside-out-of-t5-ultimate-sports-and-adventures-recorder/)

 When creating formulas in Excel, you can reference cells from another part of the worksheet in your formulas. But if you have a lot of formulas, all those cell references can get confusing. There's an easy way to remove the confusion.

 Excel includes a feature, called "Names", that can make your formulas more readable and less confusing. Instead of referencing a cell or range of cells, you can assign a name to that cell or range and use that name in formulas. This will make your formulas much easier to understand and maintain.

Related: [How to Use VLOOKUP in Excel](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) 

 In the formula below, we reference a range of cells (in bold) from another worksheet, called "Product Database", in the same workbook. In this case, the name of the worksheet gives us a good idea as to what's contained in the range of cells, "A2:D7". However, we could use a name for this range of cells to make the formula shorter and easier to read.

=IF(ISBLANK(A11),"",VLOOKUP(ALL,'**Product Database'!A2:D7**,2,FALSE))

 NOTE: For more information about the VLOOKUP function used in the formula above, see our article about [using VLOOKUP in Excel](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/). You can also learn how to use the ["IF" function and other useful functions](https://some-techniques.techidaily.com/new-exploring-whatsapp-voice-chat-features/).

![01_using_cell_range_in_formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/01_using_cell_range_in_formula.png) 

##  How to Create a Name for a Cell or a Range of Cells Using the Name Box

 To assign a name to a range of cells, select the cells you want to name. The cells don't have to be contiguous. To select non-contiguous cells, use the "Ctrl" key when selecting them.

![02_selecting_cell_range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/02_selecting_cell_range.png) 

 Click the mouse in the "Name Box" above the cell grid.

![03_name_box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/03_name_box.png) 

 Type a name for the range of cells in the box and press "Enter". For example, we called the selected cells on our "Product Database" worksheet "Products". There are syntax rules you must abide by when choosing a name. You can only begin a name with a letter, an underscore (\_), or a backslash (\\). The rest of the name can consist of letters, numbers, periods, and underscores. There are [additional syntax rules](https://support.office.com/en-US/article/Define-and-use-names-in-formulas-4D0F13AC-53B7-422E-AFD2-ABD7FF379C64#bmsyntax%5Frules%5Ffor%5Fnames) about what's valid and not when defining names.

![04_entering_name_in_name_box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/04_entering_name_in_name_box.png) 

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Remember the formula from the beginning of this article? It contained a reference to the "Products Database" worksheet in the workbook and a range of cells on the that worksheet. Now, that we created the "Products" name to represent the range of cells on our "Products Database" worksheet, we can use that name in the formula, shown in bold below.

=IF(ISBLANK(A11),"",VLOOKUP(ALL,**Products**,2,FALSE))

 NOTE: When creating a name using the "Name Box", the [scope of the name](https://support.office.com/en-US/article/Define-and-use-names-in-formulas-4D0F13AC-53B7-422E-AFD2-ABD7FF379C64#bmlearn%5Fmore%5Fabout%5Fusing%5Fnames) defaults to the workbook. That means that the name is available to be used on any worksheet in the current workbook without referencing a specific worksheet. You can choose to limit the scope to a specific worksheet so the worksheet name has to be used when referring to the name, such as in the example at the beginning of this article.

![16_using_name_in_formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/16_using_name_in_formula.png) 

##  How to Edit Names Using the Name Manager

 Excel provides a tool, called "Name Manager", that makes it easy to find, edit, and delete the names in your workbook. You can also use the Name Manager to create names, if you want to specify more details about the name. To access the Name Manager, click the "Formulas" tab.

![05_clicking_formulas_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/05_clicking_formulas_tab.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the "Defined Names" section of the "Formulas" tab, click "Name Manager".

![06_clicking_name_manager](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/06_clicking_name_manager.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Name Manager dialog box displays. To edit an existing name, select the name in the list and click "Edit". For example, we're going to edit the "Products" name.

![07_clicking_edit_on_name_manager](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/07_clicking_edit_on_name_manager.png) 

 The "Edit Name" dialog box displays. You can change the "Name" itself as well as add a "Comment" to the name, providing more details about what the name represents. You can also change the range of cells to which this name is assigned by clicking the "Expand Dialog" button on the right side of the "Refers to" edit box.

 NOTE: You'll see that the "Scope" drop-down list is grayed out. When you edit an existing name, you cannot change the "Scope" of that name. You must choose the scope when you first create the name. If you want the scope to be a specific worksheet, rather than the entire workbook, you can create a name in a way that allows you to specify the scope initially. We'll show you how to do that in a later section.

![08_edit_name_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/08_edit_name_dialog.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As an example, say we added another product to our "Product Database" and we want to include it in the cell range named "Products". When we click on the "Expand Dialog" button, the "Edit Name" dialog box shrinks down to contain only the "Refers to" edit box. We select the range of cells directly on the "Product Database" worksheet, including the row containing the newly added product. The worksheet name and cell range are automatically entered into the "Refers to" edit box. To accept your selection and return to the full "Edit Name" dialog box, click the "Collapse Dialog" button. Click "OK" on the "Edit Name dialog box to accept the changes to the name.

![08a_selecting_new_cell_range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/08a_selecting_new_cell_range.png) 

##  How to Delete a Name Using the Name Manager

 If you decide you don't need a name anymore, it's easy to delete it. Simply, access the "Name Manager" dialog box as we discussed in the previous section. Then, select the name you want to delete in the list of names and click "Delete".

![09_deleting_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/09_deleting_name.png) 

 On the confirmation dialog box that displays, click "OK" if you're sure you want to delete the selected name. You are returned to the "Name Manager" dialog box. Click "Close" to close it.

![10_delete_confirmation](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/10_delete_confirmation.png) 

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Create a Name Using the "New Name" Dialog Box

 When you create a new name by selecting one or more cells and then entering a name in the "Name Box", the default scope of the name is the entire workbook. So, what do you do if you want to limit the scope of a name to just a specific worksheet?

 Select the cells to which you want to assign the name. Click the "Formulas" tab and then click "Define Name" in the "Defined Names" section.

 NOTE: You don't have to select the cells first. You can also select them using the "Expand Dialog" button later on, if you want.

![12_clicking_define_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/12_clicking_define_name.png) 

 The "New Name" dialog box displays. Notice that it's very similar to the "Edit Name" dialog box mentioned earlier. The main difference is that now you can change the scope of the name. Say we want to limit the scope of the name to just the "Invoice" worksheet. We would do this if we wanted to be able to use the same name for a range of cells on another worksheet.

 First, we'll enter the name we want to use, which in our case is "Products". Remember the [syntax rules](https://support.office.com/en-US/article/Define-and-use-names-in-formulas-4D0F13AC-53B7-422E-AFD2-ABD7FF379C64#bmsyntax%5Frules%5Ffor%5Fnames) when creating your name. Then, to limit the [scope](https://support.office.com/en-US/article/Define-and-use-names-in-formulas-4D0F13AC-53B7-422E-AFD2-ABD7FF379C64#bmlearn%5Fmore%5Fabout%5Fusing%5Fnames) of the "Products" name to only the "Invoice" worksheet, we select that from the "Scope" drop-down list.

 NOTE: The "New Name" dialog box can also be accessed by clicking "New" on the "Name Manager" dialog box.

![13_selecting_scope](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/13_selecting_scope.png) 

<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Enter more details about the name, if desired, in the "Comment" box. If you didn't select the cells to which you're assigning the name, click the "Expand Dialog" button to the right of the "Refers to" edit box to select the cells the same way we did when we edited the name earlier. Click "OK" to finish creating the new name.

![14_clicking_ok_on_new_name_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/14_clicking_ok_on_new_name_dialog.png) 

 The name is automatically inserted into the same "Name Box" we used to assign a name to a range of cells at the beginning of this article. Now, we can replace the cell range reference ('Product Database'!$A$2:$D:7) with the name (Products) in the formulas on the "Invoice" worksheet, like we did earlier in this article.

![15_name_inserted_into_name_box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/15_name_inserted_into_name_box.png) 

##  How to Use a Name to Represent a Constant Value

 You don't have to refer to cells when creating a name. You can use a name to represent a constant, or even a formula. For example, the worksheet below shows the exchange rate used to calculate the price in Euros for the various sizes of widgets. Because the exchange rate changes often, it would be useful if it was located in a place that's easy to find and update. Since names are easy to edit, as discussed earlier, we can create a name to represent the exchange rate and assign a value to the name.

![17_exchange_rate_on_worksheet](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/17_exchange_rate_on_worksheet.png) 

 Notice the formula contains an [absolute cell reference](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/) to a cell containing the current exchange rate. We'd rather use a name that will refer to the current exchange rate so it's easier to change and formulas using the exchange rate are easier to understand.

![18_formula_with_cell_reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/18_formula_with_cell_reference.png) 

 To create a name that will be assigned to a constant value, open the "New Name" dialog box by clicking the "Formulas" tab and then clicking "Define Name" in the "Defined Names" section. Enter a name to represent the constant value, such as "ExchangeRate". To assign a value to this name, enter an equal sign (=) in the "Refers to" edit box followed by the value. There should not be a space between the equal sign and the value. Click "OK" to finish creating the name.

 NOTE: If there's a formula you use in many places in your workbook, you can enter that formula into the "Refers to" edit box so you can simply enter the name in every cell where you need to use the formula.

![19_new_name_dialog_for_constant](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/19_new_name_dialog_for_constant.png) 

 Now, we can use the new name in formulas where we want to use the exchange rate. When we click on a cell with a formula that contains an [absolute cell reference](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/), notice the result is "0.00". That's because we removed the exchange rate from the cell being referenced. We'll replace that cell reference with the new name we created.

![20_cell_reference_results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/20_cell_reference_results.png) 

 Highlight the cell reference (or other part of the formula you want to replace with a name) and start typing the name you created. As you type, any matching names display in a popup box. Select the name you want to insert into the formula by clicking on it in the popup box.

![21_selecting_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/21_selecting_name.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The name is inserted into the formula. Press "Enter" to accept the change and update the cell.

![22_name_inserted](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/22_name_inserted.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note that the result is updated using the exchange rate referred to by the name.

![23_formula_using_constant_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/02/23_formula_using_constant_name.png) 

 Names are very useful if you create complex Excel workbooks with a lot of formulas. When you need to distribute your workbooks to others, using names makes it easier for others, as well as yourself, to understand your formulas.

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
<li><a href="https://win-forum.techidaily.com/bypass-limits-how-to-get-windows-11-working-on-unsupported-chips-via-revouninstaller/"><u>Bypass Limits: How to Get Windows 11 Working on Unsupported Chips via RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-one-post-at-a-time-insights-on-facebook-twitter-instagram-and-youtube/"><u>Connecting the World One Post at a Time: Insights on Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-techniques-to-delete-foldersfiles-with-powershell-or-command-prompt-on-windows-11/"><u>Expert Techniques to Delete Folders/Files with PowerShell or Command Prompt on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915271217-facebook-to-youtube-a-comprehhemic-view-on-the-leading-social-networks-of-our-time/"><u>Facebook to Youtube: A Comprehhemic View on the Leading Social Networks of Our Time.</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fix-silent-system-following-latest-windows-11-patch-simple-tips/"><u>Fix Silent System Following Latest Windows 11 Patch: Simple Tips</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-oppo-reno-8t-5g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Oppo Reno 8T 5G FRP Locks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y100a-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo Y100A Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oneplus-nord-n30-semirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can OnePlus Nord N30 SEMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-iphone-15-plus-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From iPhone 15 Plus without Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-poco-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Poco Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/innovative-approaches-to-keeping-your-snaps-connected-for-2024/"><u>Innovative Approaches to Keeping Your Snaps Connected for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/lenovo-thinkpad-x1-titanium-yoga-the-ultimate-2-in-one-laptop-for-fans-of-the-iconic-thinkpad-line/"><u>Lenovo ThinkPad X1 Titanium Yoga - The Ultimate 2-In-One Laptop for Fans of the Iconic ThinkPad Line</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-digital-engagement-with-top-platforms-facebook-twitter-instagram-and-youtube/"><u>Mastering Digital Engagement with Top Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-quartet-understanding-facebook-twitter-instagram-and-youtubes-impact/"><u>The Quintessential Quartet: Understanding Facebook, Twitter, Instagram & YouTube's Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/top-tools-that-makes-your-laptops-os-change-more-manageable/"><u>Top Tools that Makes Your Laptop's OS Change More Manageable</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unavailable-domain-services-printer-malfunction/"><u>Unavailable Domain Services, Printer Malfunction</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-giants-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Understanding the Giants: A Look at Facebook, Twitter, Instagram, and YouTube</u></a></li>
</ul></div>

