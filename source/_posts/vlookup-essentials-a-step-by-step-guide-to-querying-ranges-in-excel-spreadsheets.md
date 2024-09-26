---
title: "VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets"
date: 2024-09-15T17:40:36.031Z
updated: 2024-09-21T17:06:48.197Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068408/7443" target="_top" id="2068408">
  <img src="//a.impactradius-go.com/display-ad/7443-2068408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068408/7443" style="position:absolute;visibility:hidden;" border="0" />
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



