---
title: "Mastering MS Excel's IF Statements: A Comprehensive Guide"
date: 2024-09-19T16:15:08.468Z
updated: 2024-09-21T17:26:04.799Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d1114cdd62049ffd7653e7094748e36a17e96d6070583d2a1a451841876e1401.jpg
---

## Mastering MS Excel's IF Statements: A Comprehensive Guide

### Quick Links

* [The IS Functions in Excel](https://facebook-clips.techidaily.com/in-2024-reclaim-inaccessible-watch-icon/)
* [IS Function Examples](https://extra-resources.techidaily.com/2024-approved-benchmark-analysis-djis-drone-phantom-3/)

### Key Takeaways

 Excel's IS functions return "True" or "False" depending on the contents of a cell. For example, =ISBLANK(A1) will return "TRUE" if cell A1 is blank and "FALSE" if it is not. Excel provides the following IS functions: ISBLANK, ISERR, ISERROR, ISLOGICAL, ISNA, ISNONTEXT, ISNUMBER, ISREF, and ISTEXT.

 When you want to test your data and receive a simple True or False result, the IS [functions in Excel](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) are just what you need. You can check for blank cells, errors, text, numbers, references, and more quickly and easily.

 There are currently nine IS functions, also known as information functions, in Excel. This includes ISBLANK, ISERROR, ISTEXT, and more.

 When you use these functions in conjunction with others, like [the IF function](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/), you can put parameters around your true/false statements. But, you can also use the IS functions on their own if it's beneficial. Let's take a look at how they work.

##  The IS Functions in Excel

 The syntax for each function's formula is the same with just one argument: 

        `ISLBLANK(value)`
    
 , 

        `ISERR(value)`
    
 , 

        `ISERROR(value)`
    
 , and so on. The 

        `value`
    
 can be a cell reference, text, or number, and the result is either True or False.

 Here are the nine IS functions and brief explanations of each one.

* **ISBLANK:** Returns True for a blank cell or False for a cell with content.
* **ISERR:** Returns True for any error value except #N/A or False for the #N/A error.
* **ISERROR:** Returns True for any error value or False for no error.
* **ISLOGICAL:** Returns True for a logical value or False if not a logical value.
* **ISNA:** Returns True for the #N/A error or False if not an #N/A error.
* **ISNONTEXT:** Returns True for a value that's not text (or a blank cell) or False for a value that's text.
* **ISNUMBER:** Returns True for a value that's a number or False if it's not a number.
* **ISREF:** Returns True if the value is a reference or False if it's not a reference.
* **ISTEXT:** Returns True if the value is text or False if it's not text.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  IS Function Examples

 As you review the above list, you can see where some of the IS functions can come in handy. At the same time, you may see a couple that you'll probably rarely use. So, let's look at common uses for a few of the functions.

###  ISBLANK

[The ISBLANK function](https://tech-savvy.techidaily.com/1723808302722-effortless-guide-setting-up-your-ps4-remote-play-on-android-devices-in-just-three-simple-steps/) is one you can use to [locate empty cells](https://fox-blue.techidaily.com/2024-approved-revel-in-richness-your-pcs-pathway-to-exceptional-video-quality/) where you expect data. You can use this with the IF function to display a particular value for blank and non-blank cells.

 Here, we have ISBLANK to determine if cell A1 is blank.

=ISBLANK(A1)

 The result is True for a blank cell. You can [copy the same formula](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) down to check additional cells using the fill handle. As you see below, we have True for blanks and False for non-blanks.

![ISBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISBLANK-ExcelISFunctions.png) 

 Now we'll include the IF function to display a question mark (?) for a blank cell and a hyphen (-) for a cell containing data.

=IF(ISBLANK(A1),"?","-")

 As you can see, we now have the result of a question mark instead of True for blank cells.

![ISBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISBLANK-ExcelISFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  ISERROR

 The ISERROR function is ideal if you want to locate [errors in your sheet](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) for constantly changing data. It works well with the IF function in the same way that IFERROR works on its own.

 As an example, we'll use ISERROR to determine if a calculation results in an error. We'll divide the value in cell A1 by that in cell B1.

=ISERROR(A1/B1)

 As you can see, we have an error because the result displays True. The error would be #DIV/0! because you cannot divide by zero.

![ISERROR function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISERROR-ExcelISFunctions.png) 

 Now we can add the IF function to display something other than True or False. If the calculation results in an error, we'll display 1, otherwise, we'll display 2.

=IF(ISERROR(A1/B1),A,B)

 As you can see, our result is 1 because the calculation returns an error.

![ISERROR function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISERROR-ExcelISFunctions.png) 

 Again, you can use the newer IFERROR function instead of the IF and ISERROR combination in most cases. But you can also use IF and ISERROR with other functions like VLOOKUP to display certain results for both errors and non-errors, whereas IFERROR displays only the value for the error.

 For more on this specific topic, take a look at our guide on [using the IFERROR function to hide errors](https://instagram-videos.techidaily.com/updated-cut-and-paste-success-enhancing-videos-for-instagram-shares/) in your sheet.

Related: [How to Hide Error Values and Indicators in Microsoft Excel](https://instagram-videos.techidaily.com/updated-cut-and-paste-success-enhancing-videos-for-instagram-shares/) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144297/7443" target="_top" id="2144297">
  <img src="//a.impactradius-go.com/display-ad/7443-2144297" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144297/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  ISNUMBER and ISTEXT

 Next, we'll look at examples using the ISNUMBER and ISTEXT functions. These similarly display True if the value is a number or text, respectively.

 Here, we want to ensure we [have a number in our cell](https://facebook-videos.techidaily.com/2024-approved-unlock-laughter-traps-20-quirky-fb-detention-anecdotes-for-amusement/).

=ISNUMBER(A1)

 Our result is False because the value in cell A1 is text, not a number.

![ISNUMBER function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISNUMBER-ExcelISFunctions.png) 

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, we'll add the IF function to display nothing if the cell contains a number but "Please enter a number" if the cell doesn't contain a number.

=IF(ISNUMBER(A1)," ","Please enter a number")

 By using the above formula, we can let the user know they must enter a number.

![ISNUMBER function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISNUMBER-ExcelISFunctions.png) 

 We can do the same thing with the ISTEXT function. Here we have our ISTEXT function to see if [the value is text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) or not.

=ISTEXT(A1)

![ISTEXT function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISTEXT-ExcelISFunctions.png) 

 And with the IF function, we can display "Please enter text" if the value is something other than text.

=IF(ISTEXT(A1)," ","Please enter text")

![ISTEXT function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/ISTEXT-ExcelISFunctions.png) 

 These are basic examples of how to use the IS functions in Excel. They are available for simple checks of data on their own or more complex tests when combined with other functions.

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·**[MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  |

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
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-ensuring-every-detail-is-visible-during-google-meets/"><u>[Updated] 2024 Approved Ensuring Every Detail Is Visible During Google Meets</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-horizontal-vs-vertical-deciding-the-right-face-for-vids-for-2024/"><u>[Updated] Horizontal Vs. Vertical - Deciding the Right Face for Vids for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-strategies-for-writing-persuasive-vlog-show-narratives/"><u>[Updated] Strategies for Writing Persuasive Vlog Show Narratives</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-the-power-of-your-lost-iphone-x/"><u>[Updated] Unleash the Power of Your Lost iPhone X</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-your-easy-guide-to-youtube-downloads-on-idevices/"><u>[Updated] Your Easy Guide to YouTube Downloads on iDevices</u></a></li>
<li><a href="https://win-forum.techidaily.com/como-transformar-archivos-wmv-a-formato-webm-sin-costo-con-online-tools/"><u>Cómo Transformar Archivos WMV a Formato WebM Sin Costo Con Online Tools</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/passos-simples-para-fotografia-em-esquema-de-cor-preta-e-branca-tecnicas-facilmente-utilizaveis/"><u>Passos Simples Para Fotografia Em Esquema De Cor Preta E Branca - Técnicas Facilmente Utilizáveis</u></a></li>
<li><a href="https://fox-that.techidaily.com/prevalent-iphone-visual-glitches-fixes-you-cant-miss/"><u>Prevalent iPhone Visual Glitches: Fixes You Can't Miss</u></a></li>
<li><a href="https://win-forum.techidaily.com/transforme-sus-archivos-flv-en-canciones-mp3-sin-costo-adicional-guia-de-movavi/"><u>Transforme Sus Archivos FLV en Canciones MP3 Sin Costo Adicional: Guía De Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/winx-dvd-funktionen-verbessern-zusammenarbeit-fur-fortschritte-in-der-dvd-technologie/"><u>WinX DVD Funktionen Verbessern: Zusammenarbeit Für Fortschritte in Der DVD-Technologie</u></a></li>
<li><a href="https://win-forum.techidaily.com/webmflv-movavi/"><u>우리에서는 원급 WEBM/FLV 변환을 가장 안심하여 제공하세요! - Movavi 기회</u></a></li>
</ul></div>

