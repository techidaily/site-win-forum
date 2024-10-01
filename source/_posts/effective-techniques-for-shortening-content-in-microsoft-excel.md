---
title: Effective Techniques for Shortening Content in Microsoft Excel
date: 2024-09-27T16:33:26.523Z
updated: 2024-10-01T16:28:23.857Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Truncate Text in Excel with MID or MIDB

 If the [text that you want to keep](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) is in the middle of a text string, you'll use the MID or MIDB functions. These functions are like the other two in that you enter a number or characters for MID and number of bytes for MIDB.

Related: [How to Shrink or Expand Cells to Fit Text in Microsoft Excel](https://youtube-web.techidaily.com/024-approved-ultimate-routine-personalize-your-youtube-shorts-image-credits/) 

 The syntaxes are `MID(text, start, number_characters)` and `MIDB(text, start, number_bytes)` with all arguments for each formula required. You can use a cell reference for the first argument, the number of the starting character or byte for the second, and the number to keep for the third.

 Here, we'll remove everything from the string except for a middle portion. With this formula, the text is in cell A2, we want to start with the 35th character, and keep only 24 characters.

=MID(A2,35,24)

![Keep 24 characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID35-ExcelTruncateText.png) 

 As another example, using the following formula you can shorten the text in cell A2 and keep only the second word. We use 6 for the `start` argument and 3 for the `number_characters` argument.

=MID(A2,6,3)

![Keep three characters in the middle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/MID6-ExcelTruncateText.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/new-unlocking-11-pros-window-secrets-for-2024/"><u>[New] Unlocking 11 Pro's Window Secrets for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-jumpstart-your-channelstopwatch-seeking-viewers-with-these-youtube-seo-essentials/"><u>[Updated] 2024 Approved Jumpstart Your Channel’stopwatch-Seeking Viewers with These YouTube SEO Essentials</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unveiling-effective-strategies-for-fb-in-stream-ad-setup/"><u>[Updated] Unveiling Effective Strategies for FB In-Stream Ad Setup</u></a></li>
<li><a href="https://technical-tips.techidaily.com/free-snd-movavi/"><u>線上全面FREE SND改版轉移功能 – Movavi解決方案</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-list-mobile-applications-for-enhanced-gopro-videos/"><u>A-List Mobile Applications for Enhanced GoPro Videos</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-community-giants-your-guide-to-facebook-twitter-instagram-and-youtube-success/"><u>Digital Community Giants - Your Guide to Facebook, Twitter, Instagram & YouTube Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-tutorial-on-how-to-erase-profiles-from-windows-10-systems/"><u>Easy Tutorial on How to Erase Profiles From Windows 10 Systems</u></a></li>
<li><a href="https://article-files.techidaily.com/expert-recommended-steadicams-for-drone-videography/"><u>Expert-Recommended Steadicams for Drone Videography</u></a></li>
<li><a href="https://win-forum.techidaily.com/free-up-space-on-your-windows-11-pc-a-step-by-step-revouninstaller-tutorial/"><u>Free Up Space on Your Windows 11 PC - A Step-by-Step RevoUninstaller Tutorial</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-big-four-strategies-for-facebook-twitter-instagram-and-youtube-engagement/"><u>Mastering the Big Four: Strategies for Facebook, Twitter, Instagram & YouTube Engagement</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-unveiled-understanding-the-dynamics-of-facebook-twitter-instagram-and-youtube/"><u>Social Media Unveiled: Understanding The Dynamics of Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/timeless-treasures-accessing-fbs-historic-stories/"><u>Timeless Treasures Accessing FB's Historic Stories</u></a></li>
<li><a href="https://win-online.techidaily.com/top-10-gratisk-avi-redigeringstekniker-for-windows-11-8-och-7-samt-macos/"><u>Top 10 Gratisk Avi-Redigeringstekniker För Windows 11, 8 Och 7 Samt macOS</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915269358-top-platforms-in-social-networking-explore-facebook-twitter-instagram-and-youtube/"><u>Top Platforms in Social Networking - Explore Facebook, Twitter, Instagram and YouTube</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-the-windows-registry-an-insight-with-revo-uninstaller/"><u>Understanding the Windows Registry: An Insight with Revo Uninstaller</u></a></li>
<li><a href="https://discover-blog.techidaily.com/windows-10webtop13/"><u>おすすめ！Windows 10に対応した高性能Webカメラソフトの選択肢TOP13(無料)</u></a></li>
</ul></div>

