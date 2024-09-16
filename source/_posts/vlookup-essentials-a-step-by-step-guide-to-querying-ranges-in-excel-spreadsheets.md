---
title: "VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets"
date: 2024-09-10T16:28:05.297Z
updated: 2024-09-16T16:45:13.130Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/23f13f96d936d78089a7e8a3b93e560ac0ab8587601498f32a131493f3f787f8.jpg
---

## VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets

### Quick Links

* [Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores](https://hardware-updates.techidaily.com/1722963330919-newly-released-geforce-nvidia-210-drivers-compatible-with-windows-11-get-them-now/)
* [Example Two: Providing a Discount Based on How Much a Customer Spends](https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-g310-drfone-by-drfone-virtual-android/)

 VLOOKUP is one of Excel's most well-known functions. You'll typically use it to look up exact matches, such as the ID of products or customers, but in this article, we'll explore how to use VLOOKUP with a range of values.

##  Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores

 As an example, say we have a list of exam scores, and we want to assign a grade to each score. In our table, column A shows the actual exam scores and column B will be used to show the letter grades we calculate. We've also created a table off to the right (the D and E columns) that show the score necessary to achieve each letter grade.

![Grade score sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/grades-lookup-1.png) 

 With VLOOKUP, we can use the range values in column D to assign the letter grades in column E to all the actual exam scores.

###  The VLOOKUP Formula

 Before we get into applying the formula to our example, let's have a quick reminder of the VLOOKUP syntax:

=VLOOKUP(lookup_value, table_array, col_index_num, range_lookup)

 In that formula, the variables work like this:

* lookup\_value: This is the value for which you are looking. For us, this is the score in column A, starting with cell A2.
* table\_array: This is often referred to unofficially as the lookup table. For us, this is the table containing the scores and associated grades (range D2:E7).
* col\_index\_num: This is the column number where the results will be placed. In our example, this is column B, but since the VLOOKUP command requires a number, it's column 2.
* range\_lookup> This is a logical value question, so the answer is either true or false. Are you performing a range lookup? For us, the answer is yes (or "TRUE" in VLOOKUP terms).

 The completed formula for our example is shown below:

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![Results of our VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-results.png) 

 The table array has been fixed to stop it changing when the formula is copied down the cells of column B.

###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 It is important to be clear that the order is only essential with range lookups. When you put False on the end of a VLOOKUP function, the order is not so important.

##  Example Two: Providing a Discount Based on How Much a Customer Spends

 In this example, we have some sales data. We would like to provide a discount on the sales amount, and the percentage of that discount is dependent upon the amount spent.

 A lookup table (columns D and E) contains the discounts at each spending bracket.

![Second VLOOKUP example data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/VLOOKUP-second-example.png) 

 The VLOOKUP formula below can be used to return the correct discount from the table.

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

 This example is interesting because we can use it in a formula to subtract the discount.

 You will often see Excel users writing complicated formulas for this type of conditional logic, but this VLOOKUP provides a concise way of achieving it.

 Below, the VLOOKUP is added to a formula to subtract the discount returned from the sales amount in column A.

=A2-A2*VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![VLOOKUP returning conditional discounts](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-discounted-price.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

 VLOOKUP is not just useful for when looking for specific records such as employees and products. It's more versatile than many people know, and having it return from a range of values is an example of that. You can also use it as an alternative to otherwise complicated formulas.

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-full-screen-mastery-for-premier-pro-users/"><u>[New] 2024 Approved Full Screen Mastery for Premier Pro Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-premium-windows-10-screen-recording-software-for-2024/"><u>[New] Premium Windows 10 Screen Recording Software for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-eliminating-noise-in-photos-using-photopeas-tools/"><u>[Updated] 2024 Approved Eliminating Noise in Photos Using Photopea's Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-on-major-online-channels-facebook-twitter-instagram-and-youtube/"><u>Connect and Engage on Major Online Channels: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decoding-poap-exploring-the-evolution-of-memory-storage-within-the-web3-revolution/"><u>Decoding POAP: Exploring the Evolution of Memory Storage Within the Web3 Revolution</u></a></li>
<li><a href="https://extra-tips.techidaily.com/delicate-film-opening/"><u>Delicate Film Opening</u></a></li>
<li><a href="https://media-tips.techidaily.com/master-the-art-of-music-blending-a-step-by-step-guide-with-visuals-simplified/"><u>Master the Art of Music Blending: A Step-by-Step Guide with Visuals, Simplified</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-installation-of-revo-permission-manager-using-revouninstaller-a-detailed-guide/"><u>Master the Installation of Revo Permission Manager Using RevoUninstaller - A Detailed Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigate-through-social-giants-strategies-for-facebook-twitter-instagram-and-youtube-success/"><u>Navigate Through Social Giants: Strategies for Facebook, Twitter, Instagram, and Youtube Success</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sci-fis-new-dimensions-top-10-films-taking-viewers-beyond-our-reality-for-2024/"><u>Sci-Fi's New Dimensions Top 10 Films Taking Viewers Beyond Our Reality for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/solving-connectivity-issues-a-guide-to-reviving-your-logitech-k780-keyboard/"><u>Solving Connectivity Issues: A Guide to Reviving Your Logitech K780 Keyboard</u></a></li>
<li><a href="https://win-forum.techidaily.com/synergy-of-popular-platforms-strategies-for-facebook-twitter-instagram-and-youtubers/"><u>Synergy of Popular Platforms: Strategies for Facebook, Twitter, Instagram and YouTubers</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-guide-to-major-social-media-sites-twitter-instagram-and-more/"><u>The Ultimate Guide to Major Social Media Sites: Twitter, Instagram & More!</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-how-to-fix-fifa-21-failure-on-startup/"><u>Troubleshooting: How to Fix FIFA 21 Failure on Startup</u></a></li>
</ul></div>

