---
title: Effective Techniques for Shortening Content in Microsoft Excel
date: 2024-09-10T16:07:57.049Z
updated: 2024-09-16T16:54:40.414Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Effective Techniques for Shortening Content in Microsoft Excel

### Quick Links

* [Truncate Text in Excel with RIGHT or RIGHTB](https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/)
* [Truncate Text in Excel with LEFT or LEFTB](https://win-dash.techidaily.com/download-and-install-lenovo-ideapad-100-drivers-for-windows-10-step-by-step-guide/)
* [Truncate Text in Excel with MID or MIDB](https://youtube-web.techidaily.com/ehensive-guide-to-crafting-engaging-youtube-outros/)

 If text is a big part of the data in your spreadsheet, you may need to adjust it to fit properly. The [TRUNC function](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) in Microsoft Excel works only with numbers. So if you want to truncate text, here's how.

 There are many useful [functions for working with text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) in Excel. Three of those functions help you truncate text in a cell. These are RIGHT, LEFT, and MID, and each has a variation for using bytes instead of characters.

##  Truncate Text in Excel with RIGHT or RIGHTB

 The RIGHT function uses the [number of characters](https://fox-http.techidaily.com/new-dynamic-shade-adjuster-app-for-2024/) for a single-byte character set (SBCS) while RIGHTB uses a number of bytes for a [double-byte character set (DBCS)](https://en.wikipedia.org/wiki/DBCS). Both functions work the same way with only that difference. So, you can use whichever works best for you.

Related: [How to Count Characters in Microsoft Excel](https://fox-http.techidaily.com/new-dynamic-shade-adjuster-app-for-2024/) 

 The syntaxes are 

        `RIGHT(text, number_characters)`
    
 and 

        `RIGHTB(text, number_bytes)`
    
 with the first argument for each formula required. You can enter the cell reference and keep what's on the right.

 To keep 12 characters on the right from the text string in cell A2, you would use this formula:

=RIGHT(A2,12)

![Keep 12 characters on the right](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/RIGHT12-ExcelTruncateText.png) 

 As another example, we want to keep only the last word and punctuation. This formula retains the last eight characters on the right.

=RIGHT(A2,8)

![Keep eight characters on the right](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/RIGHT8-ExcelTruncateText.png) 

##  Truncate Text in Excel with LEFT or LEFTB

 The LEFT and LEFTB functions work like the RIGHT and RIGHTB functions where you use either the number of characters or bytes respectively. But with these [functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/), you're shortening your text string from the opposite side.

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

 The syntaxes are `LEFT(text, number_characters)` and `LEFTB(text, number_bytes)` with the first argument for each formula required. Again, insert the cell reference for the text and keep what's on the left side.

 To keep 32 characters on the left from the text string in cell A2, you would use this formula:

=LEFT(A2,32)

![Keep 32 characters on the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/LEFT32-ExcelTruncateText.png) 

 For another example, we want to keep only the first word in the string. This formula retains only the first four characters on the left.

=LEFT(A2,4)

![Keep four characters on the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/LEFT4-ExcelTruncateText.png) 

##  Truncate Text in Excel with MID or MIDB

 If the [text that you want to keep](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) is in the middle of a text string, you'll use the MID or MIDB functions. These functions are like the other two in that you enter a number or characters for MID and number of bytes for MIDB.

Related: [How to Shrink or Expand Cells to Fit Text in Microsoft Excel](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) 

 The syntaxes are `MID(text, start, number_characters)` and `MIDB(text, start, number_bytes)` with all arguments for each formula required. You can use a cell reference for the first argument, the number of the starting character or byte for the second, and the number to keep for the third.

 Here, we'll remove everything from the string except for a middle portion. With this formula, the text is in cell A2, we want to start with the 35th character, and keep only 24 characters.

=MID(A2,35,24)

![Keep 24 characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID35-ExcelTruncateText.png) 

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As another example, using the following formula you can shorten the text in cell A2 and keep only the second word. We use 6 for the `start` argument and 3 for the `number_characters` argument.

=MID(A2,6,3)

![Keep three characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID6-ExcelTruncateText.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Shortening text in your sheet may be necessary or simply something you prefer. These [functions and formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) help you truncate text in Excel from the right, left, or middle, as you need it.

Related: [How to Add Text to a Cell With a Formula in Excel](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/)

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
<li><a href="https://screen-recording.techidaily.com/new-revolutionary-6-sustainable-minecraft-homes-for-2024/"><u>[New] Revolutionary 6 Sustainable Minecraft Homes for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-converting-images-into-harmonious-videography/"><u>[Updated] 2024 Approved Converting Images Into Harmonious Videography</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-art-of-color-correction-best-practices-top-11/"><u>[Updated] The Art of Color Correction Best Practices (Top 11)</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-100-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-solutions-for-gionee-network-unlock-by-drfone-android/"><u>Best Solutions for Gionee Network Unlock</u></a></li>
<li><a href="https://win-forum.techidaily.com/determining-your-systems-powershell-version-on-windows-10-a-step-by-step-guide/"><u>Determining Your System's PowerShell Version on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-clean-user-data-from-windows-11-operating-system-using-revo-uninstaller/"><u>How to Clean User Data From Windows 11 Operating System Using Revo Uninstaller</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-eradicate-directories-and-files-using-powershell-or-command-prompt-in-windows-11/"><u>How to Eradicate Directories & Files Using PowerShell or Command Prompt in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-apple-iphone-6-plus-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your Apple iPhone 6 Plus Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-on-apple-iphone-7-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue On Apple iPhone 7</u></a></li>
<li><a href="https://media-tips.techidaily.com/master-the-art-of-music-blending-a-step-by-step-guide-with-visuals-simplified/"><u>Master the Art of Music Blending: A Step-by-Step Guide with Visuals, Simplified</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-web-of-friendship-a-guide-to-facebook-twitter-instagram-youtube/"><u>Navigating the Web of Friendship - A Guide to Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-mobile-experiences-ios-and-androids-vr-hits-for-2024/"><u>Top Mobile Experiences IOS & Android's VR Hits for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/unlock-the-secrets-of-your-windows-11-powershell-edition-and-version-info/"><u>Unlock the Secrets of Your Windows 11 PowerShell Edition and Version Info</u></a></li>
</ul></div>

