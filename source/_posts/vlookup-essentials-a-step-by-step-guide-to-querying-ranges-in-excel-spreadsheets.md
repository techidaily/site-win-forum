---
title: "VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets"
date: 2024-09-24T17:34:46.586Z
updated: 2024-10-01T17:27:01.298Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 It is important to be clear that the order is only essential with range lookups. When you put False on the end of a VLOOKUP function, the order is not so important.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Example Two: Providing a Discount Based on How Much a Customer Spends

 In this example, we have some sales data. We would like to provide a discount on the sales amount, and the percentage of that discount is dependent upon the amount spent.

 A lookup table (columns D and E) contains the discounts at each spending bracket.

![Second VLOOKUP example data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/VLOOKUP-second-example.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The VLOOKUP formula below can be used to return the correct discount from the table.

=VLOOKUP(A2,$D$2:$E$7,2,TRUE)

 This example is interesting because we can use it in a formula to subtract the discount.

 You will often see Excel users writing complicated formulas for this type of conditional logic, but this VLOOKUP provides a concise way of achieving it.

 Below, the VLOOKUP is added to a formula to subtract the discount returned from the sales amount in column A.

=A2-A2*VLOOKUP(A2,$D$2:$E$7,2,TRUE)

![VLOOKUP returning conditional discounts](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-discounted-price.png) 

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
<li><a href="https://some-knowledge.techidaily.com/new-explore-new-horizons-mobile-videography-beyond-periscope/"><u>[New] Explore New Horizons Mobile Videography Beyond Periscope</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-instagrams-edge-infusing-artistry-with-slow-motion/"><u>[New] In 2024, Instagram's Edge Infusing Artistry with Slow Motion</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unlock-clearer-depths-with-instas-bokeh-effects/"><u>[Updated] Unlock Clearer Depths with Insta's Bokeh Effects</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-video-marketing-excellence-on-instagram-crafting-a-winning-strategy/"><u>2024 Approved Video Marketing Excellence on Instagram Crafting a Winning Strategy</u></a></li>
<li><a href="https://win-forum.techidaily.com/comprehensive-tutorial-on-entering-the-bios-configuration-of-a-windows-11-device/"><u>Comprehensive Tutorial on Entering the BIOS Configuration of a Windows 11 Device</u></a></li>
<li><a href="https://win-forum.techidaily.com/evaluating-protection-levels-the-fintie-case-for-apples-laptop-series-a-detailed-macbook-pro-13-assessment-on-worth-and-endurance/"><u>Evaluating Protection Levels: The Fintie Case for Apple's Laptop Series - A Detailed MacBook Pro 13 Assessment on Worth & Endurance</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-upgrade-samsung-bdplus-k850-review-update-2023/"><u>In 2024, The Ultimate Upgrade Samsung BD+ K850 Review Update 2023</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-big-four-of-social-networking-exploring-facebook-twitter-instagram-and-youtube/"><u>The Big Four of Social Networking: Exploring Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-modern-connectivity-the-impact-of-facebook-twitter-instagram-and-youtube-on-our-lives/"><u>Understanding Modern Connectivity: The Impact of Facebook, Twitter, Instagram and YouTube on Our Lives</u></a></li>
</ul></div>

