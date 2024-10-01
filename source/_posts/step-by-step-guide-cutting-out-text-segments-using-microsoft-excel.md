---
title: "Step-by-Step Guide: Cutting Out Text Segments Using Microsoft Excel"
date: 2024-09-25T17:01:38.787Z
updated: 2024-10-01T17:02:07.853Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5cbb31b0aa89284f511ea895d4dc406591717af976dec90561d5751a6efa2298.jpg
---

## Step-by-Step Guide: Cutting Out Text Segments Using Microsoft Excel

### Quick Links

* [Which Method to Use for Substring Extraction?](https://youtube-clips.techidaily.com/new-crafting-a-pro-sports-youtube-feed-on-macos/)
* [Get the String To the Left of Your Text](https://facebook-video-share.techidaily.com/in-2024-youtube-ad-free-watching-chromefirefoxandroidios-tutorial/)
* [Extract the String to the Right of Your Text](https://ai-live-streaming.techidaily.com/meet-geekoms-game-changer-the-mini-pc-ax8-equipped-with-next-gen-intel-and-cutting-edge-ryzen-processors/)
* [Obtain a String From the Middle of Your Text](https://driver-download.techidaily.com/easy-installation-brother-mfc-9340cdw-drivers-for-windows-10-8-and-7-free-downloads-and-updates/)

 If you want to extract a substring from the left, right, or middle of your text, you can use Microsoft Excel's

        `LEFT`
    
 , `RIGHT`, `MID`, `LEN`, and `FIND` functions to do that. We'll show you how.

##  Which Method to Use for Substring Extraction?

 What [method to use](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) to extract a substring depends on where your substring is located.

 To extract a string from the left of your specified character, use the [first method](https://network-issues.techidaily.com/1719974331029-eradicate-lagging-vids-instantly/) below. To extract everything that's to the right of your specified character, use the [second method](https://extra-skills.techidaily.com/updated-leading-meaningful-conversations-an-interviewers-journey/) below. To extract a string from the middle of your text, use the [third method](https://technical-tips.techidaily.com/navigating-through-facebooks-visual-library-a-comprehensive-guide-to-image-searches/) below.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

##  Get the String To the Left of Your Text

 If you'd like to get all the text that's to the left of the specified character in your cell, use Excel's

        `LEFT`
    
 and `FIND` functions to do that.

 First, open your spreadsheet and click the cell in which you want to see the result.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/1-left-select-cell.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In your selected cell, type the following function. In this function, replace `B2` with the cell where your full text is and `@` with the search character. The function will retrieve the entire string to the left of this character.

 Then press Enter.

=LEFT(B2,FIND("@",B2)-1)

![Use the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/2-enter-left-function.png) 

 Your selected cell will display the result of the function, which is the full text before your specified character in your cell.

![The result of the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/3-left-function-result.png) 

 You're all set.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Extract the String to the Right of Your Text

 To get all the text that's to the right of the specified character in your cell, use Excel's `RIGHT` , `LEN` , and `FIND` functions.

 Start by launching your spreadsheet and clicking the cell in which you want to see the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/4-right-select-cell.png) 

 In the selected cell, enter the [following function](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/). In this function, replace `B2` with the cell where your full text is and `@` with the search character. Excel will extract the entire string to the right of this character.

 Then press Enter.

=RIGHT(B2,LEN(B2)-FIND("@",B2))

![Type the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/5-type-right-function.png) 

 You'll see the result of the function in your chosen cell.

![The result of the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/6-right-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You're done.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

##  Obtain a String From the Middle of Your Text

 If you'd like to extract a string containing a specific number of characters located at a certain position in your cell, use Excel's `MID` function.

 In your spreadsheet, select the cell where you want to display the resulting string.

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/7-mid-select-cell.png) 

 In the selected cell, enter the following function. In this function, replace `B2` with the cell where you have the full text, `1` with the position of the character where you want to start the string selection, and `3` with the number of characters you want to extract.

 Then press Enter.

=MID(B2,1,3)

![Enter the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/8-enter-mid-function.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Excel will extract the specified number of characters from the given position in your cell.

![The result of the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/9-mid-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that's all there is to it.

---

 Like this, you can also [count the number of cells with text](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/) in your Excel spreadsheets. Check out our guide to learn how.

Related: [How to Count Cells With Text in Microsoft Excel](https://buynow-tips.techidaily.com/family-fun-on-wheels-holy-stone-rc-cartoon-race-car-evaluation/)

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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-instant-file-accessibility-syncing-from-pc-to-iphone/"><u>[New] 2024 Approved Instant File Accessibility Syncing From PC to iPhone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-nine-crucial-strategies-to-elevate-your-youtube-presence/"><u>[Updated] 2024 Approved Nine Crucial Strategies to Elevate Your Youtube Presence</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-apples-m1-battle-is-the-air-or-pro-more-efficient-in-2024/"><u>[Updated] Apple's M1 Battle Is the Air or Pro More Efficient, In 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-evaluating-cloud-options-price-and-performance/"><u>[Updated] In 2024, Evaluating Cloud Options Price & Performance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/essential-10-no-cost-video-conference-platforms-worklearn-edition-for-2024/"><u>Essential 10 No-Cost Video Conference Platforms Work/Learn Edition for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-advice-how-to-erase-tracker-footprints-on-your-windows-and-android-devices/"><u>Expert Advice: How to Erase Tracker Footprints on Your Windows and Android Devices</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-fix-this-app-cant-run-on-your-pc-error/"><u>How to Fix This App Can't Run on Your PC Error</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-disk-maintenance-the-ultimate-guide-to-defragging-on-windows-11-with-revo-uninstaller/"><u>Mastering Disk Maintenance: The Ultimate Guide to Defragging on Windows 11 with Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-system-diagnostics-a-users-manual-for-windows-11-bios-tools/"><u>Mastering System Diagnostics: A User's Manual for Windows 11 BIOS Tools</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-major-networks-understanding-facebook-twitter-instagram-and-youtube/"><u>Navigating the Major Networks: Understanding Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-world-of-social-networking-with-facebook-twitter-instagram-and-youtube/"><u>Navigating the World of Social Networking with Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcome-error-getting-netflix-up-and-running-again-on-xbox-gaming-system/"><u>Overcome Error: Getting Netflix Up and Running Again on Xbox Gaming System</u></a></li>
<li><a href="https://win-forum.techidaily.com/overcoming-hardware-barriers-how-to-run-windows-11-on-unsupported-chipsets/"><u>Overcoming Hardware Barriers: How to Run Windows 11 on Unsupported Chipsets</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/personal-growth-reflections-for-digital-platforms/"><u>Personal Growth Reflections for Digital Platforms</u></a></li>
<li><a href="https://win-forum.techidaily.com/race-away-from-restarts-7-surefire-fixes-for-forza-horizon-5-freeze/"><u>Race Away From Restarts: 7 Surefire Fixes for Forza Horizon 5 Freeze</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-open-source-video-tools-for-every-desktop-environment-for-2024/"><u>Top Open Source Video Tools for Every Desktop Environment for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/est-immersion-top-ten-titles-for-2024/"><u>VR's Best Immersion Top Ten Titles for 2024</u></a></li>
</ul></div>

