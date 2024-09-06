---
title: "VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets"
date: 2024-09-05T07:55:56.888Z
updated: 2024-09-06T07:55:56.888Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/23f13f96d936d78089a7e8a3b93e560ac0ab8587601498f32a131493f3f787f8.jpg
---

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## VLOOKUP Essentials: A Step-by-Step Guide to Querying Ranges in Excel Spreadsheets

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Quick Links

* [Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores](https://hardware-updates.techidaily.com/1722963330919-newly-released-geforce-nvidia-210-drivers-compatible-with-windows-11-get-them-now/)
* [Example Two: Providing a Discount Based on How Much a Customer Spends](https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-g310-drfone-by-drfone-virtual-android/)

 VLOOKUP is one of Excel's most well-known functions. You'll typically use it to look up exact matches, such as the ID of products or customers, but in this article, we'll explore how to use VLOOKUP with a range of values.

##  Example One: Using VLOOKUP to Assign Letter Grades to Exam Scores

 As an example, say we have a list of exam scores, and we want to assign a grade to each score. In our table, column A shows the actual exam scores and column B will be used to show the letter grades we calculate. We've also created a table off to the right (the D and E columns) that show the score necessary to achieve each letter grade.

![Grade score sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/grades-lookup-1.png) 

 With VLOOKUP, we can use the range values in column D to assign the letter grades in column E to all the actual exam scores.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The table array has been fixed to stop it changing when the formula is copied down the cells of column B.

###  Something to Be Careful About

 When looking in ranges with VLOOKUP, it is essential that the first column of the table array (column D in this scenario) is sorted in ascending order. The formula relies on this order to place the lookup value in the correct range.

 Below is an image of the results we'd get if we sorted the table array by the grade letter rather than the score.

![Wrong results due to table not being in order](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/vlookup-gone-wrong.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It is important to be clear that the order is only essential with range lookups. When you put False on the end of a VLOOKUP function, the order is not so important.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052060/7443" target="_top" id="2052060">
  <img src="//a.impactradius-go.com/display-ad/7443-2052060" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052060/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/updated-iconic-stop-motion-animations-15-best-ever/"><u>[Updated] Iconic Stop-Motion Animations - #15 Best Ever</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-digital-fortune-makers-top-earning-youtubers/"><u>[Updated] In 2024, Digital Fortune Makers  Top Earning YouTubers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-prime-time-action-film-transcription-for-2024/"><u>[Updated] Prime Time Action Film Transcription for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-start-filming-right-the-newbies-guide-to-video-gear/"><u>[Updated] Start Filming Right  The Newbie's Guide to Video Gear</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-discerning-podcasters-average-incomes/"><u>2024 Approved  Discerning Podcasters' Average Incomes</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-exploring-asmr-uncover-its-pros-today/"><u>2024 Approved  Exploring ASMR  Uncover Its Pros Today</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-final-cuts-vertical-voyage-editing-for-the-modern-instagram-reader/"><u>2024 Approved  Final Cut's Vertical Voyage  Editing for the Modern Instagram Reader</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-secrets-to-great-gopro-time-lapses/"><u>2024 Approved  Unveiling Secrets to Great GoPro Time-Lapses</u></a></li>
<li><a href="https://win-forum.techidaily.com/advanced-file-deletion-techniques-with-command-prompt-for-windows-10-users/"><u>Advanced File Deletion Techniques with Command Prompt for Windows 10 Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/android-11-features-one-time-permission-revouninstaller/"><u>Android 11 Features: One-Time Permission - RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-guide-forcibly-deleting-files-and-folders-in-windows-11-using-revo-uninstaller/"><u>Complete Guide: Forcibly Deleting Files and Folders in Windows 11 Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-on-the-webs-most-popular-sites-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Connect and Engage on the Web's Most Popular Sites: A Look at Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-dots-in-digital-networking-through-facebook-twitter-instagram-and-youtube/"><u>Connecting the Dots in Digital Networking Through Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/connecting-the-world-online-through-major-platforms-facebook-twitter-instagram-and-youtube/"><u>Connecting the World Online Through Major Platforms - Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://fox-access.techidaily.com/creating-captivating-hdr-portraits-in-10-steps-for-2024/"><u>Creating Captivating HDR Portraits in 10 Steps for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/determining-your-current-windows-11-powershell-version-a-comprehensive-guide/"><u>Determining Your Current Windows 11 PowerShell Version: A Comprehensive Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-ways-to-resolve-class-not-registered-errors-on-your-pc/"><u>Easy Ways to Resolve ‘Class Not Registered’ Errors on Your PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-eliminating-unwanted-memory-dump-files-on-your-pc/"><u>Expert Advice: Eliminating Unwanted Memory Dump Files on Your PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915310660-exploring-popular-digital-hubs-connect-with-facebook-twitter-instagram-and-youtube/"><u>Exploring Popular Digital Hubs: Connect with Facebook, Twitter, Instagram and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-the-giants-of-online-engagement-facebook-twitter-instagram-and-youtube/"><u>Exploring the Giants of Online Engagement: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915371234-exploring-the-giants-of-social-networking-facebook-twitter-instagram-and-youtube/"><u>Exploring the Giants of Social Networking: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-top-platforms-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Exploring Top Platforms: Navigating Through Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-vivo-y78t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/identifying-your-windows-10-powershell-version-a-comprehensive-guide/"><u>Identifying Your Windows 10 PowerShell Version: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-xiaomi-redmi-k70e-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Xiaomi Redmi K70E? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-social-media-with-four-titans-facebook-twitter-instagram-and-youtube/"><u>Master the Art of Social Media with Four Titans: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-windows-11-driver-updates-with-revouninstaller/"><u>Master the Art of Windows 11 Driver Updates with RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-social-media-engagement-across-major-platforms-facebook-twitter-instagram-and-youtube/"><u>Mastering Social Media Engagement Across Major Platforms: Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-driver-updates-for-windows-10-devices-with-revouninstaller/"><u>Mastering the Art of Driver Updates for Windows 10 Devices with RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-social-sphere-with-facebook-twitter-instagram-and-youtube/"><u>Mastering the Social Sphere with Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-digital-landscape-of-facebook-twitter-instagram-and-youtube/"><u>Navigating the Digital Landscape of Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-social-media-giants-facebook-twitter-instagram-and-youtube/"><u>Navigating the Social Media Giants: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-webs-giants-a-look-at-facebook-twitter-instagram-and-youtube/"><u>Navigating the Web's Giants: A Look at Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-the-issue-of-apps-not-launching-on-your-computer-expert-tips-and-solutions/"><u>Overcoming the Issue of Apps Not Launching on Your Computer: Expert Tips & Solutions</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ctivity-in-duality-employment-and-video-creation/"><u>Productivity in Duality  Employment & Video Creation</u></a></li>
<li><a href="https://win-forum.techidaily.com/remove-unwanted-online-trackers-a-complete-walkthrough-for-windows-11android-users/"><u>Remove Unwanted Online Trackers: A Complete Walkthrough for Windows 11/Android Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/say-goodbye-to-clutter-with-revo-uninstaller-pros-version-5-enhanced-features/"><u>Say Goodbye to Clutter with Revo Uninstaller Pro's Version 5 Enhanced Features</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-giants-of-the-internet-era-exploring-facebook-twitter-instagram-and-youtube/"><u>Social Giants of the Internet Era - Exploring Facebook, Twitter, Instagram, and Youtube</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-titans-harnessing-the-power-of-facebook-twitter-instagram-and-youtube-for-your-brand/"><u>Social Media Titans: Harnessing the Power of Facebook, Twitter, Instagram & YouTube for Your Brand</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-on-removing-or-disabling-the-latest-windows-11-update/"><u>Step-by-Step Guide on Removing or Disabling the Latest Windows 11 Update</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-hidden-applications-from-your-pc-without-using-control-panel/"><u>Step-by-Step Guide: Removing Hidden Applications From Your PC Without Using Control Panel</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-instructions-on-how-to-refresh-device-drivers-in-windows-10/"><u>Step-by-Step Instructions on How to Refresh Device Drivers in Windows 10</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-process-to-immediately-end-frozen-windows-programs-using-revouninstaller/"><u>Step-by-Step Process to Immediately End Frozen Windows Programs Using RevoUninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/tackling-complete-disk-use-in-windows-11-expert-solutions-and-tips/"><u>Tackling Complete Disk Use in Windows 11: Expert Solutions and Tips</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/the-art-of-slow-motion-tips-and-tricks-for-windows-live-movie-maker-users/"><u>The Art of Slow Motion Tips and Tricks for Windows Live Movie Maker Users</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-power-of-online-influence-understanding-facebook-twitter-instagram-and-youtube/"><u>The Power of Online Influence: Understanding Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-powerhouse-quartet-of-online-interaction-facebook-twitter-insta-grams-and-youtubes-explained/"><u>The Powerhouse Quartet of Online Interaction: Facebook, Twitter, Insta-Grams & Youtubes Explained</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-quintessential-social-hubs-unveiling-facebook-twitter-instagram-and-youtubes-powerful-influence/"><u>The Quintessential Social Hubs: Unveiling Facebook, Twitter, Instagram & Youtube's Powerful Influence</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-on-how-to-rollback-a-windows-11-patch/"><u>The Ultimate Walkthrough on How to Rollback a Windows 11 Patch</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-social-platforms-compared-facebook-vs-twitter-vs-instagram-vs-youtube/"><u>Top Social Platforms Compared: Facebook Vs. Twitter Vs. Instagram Vs. YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-guide-secure-file-deletion-on-windows-11/"><u>Ultimate Guide: Secure File Deletion on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/ultimate-protection-safeguarding-your-text-files-with-password-encryption-techniques/"><u>Ultimate Protection: Safeguarding Your Text Files with Password Encryption Techniques</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/write-magic-utilizing-chatgpt-for-original-tales/"><u>Write Magic: Utilizing ChatGPT for Original Tales</u></a></li>
</ul></div>
