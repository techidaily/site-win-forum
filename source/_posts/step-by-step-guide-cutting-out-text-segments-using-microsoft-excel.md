---
title: "Step-by-Step Guide: Cutting Out Text Segments Using Microsoft Excel"
date: 2024-09-17T17:39:33.562Z
updated: 2024-09-21T16:43:51.009Z
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

 In your selected cell, type the following function. In this function, replace `B2` with the cell where your full text is and `@` with the search character. The function will retrieve the entire string to the left of this character.

 Then press Enter.

=LEFT(B2,FIND("@",B2)-1)

![Use the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/2-enter-left-function.png) 

 Your selected cell will display the result of the function, which is the full text before your specified character in your cell.

![The result of the LEFT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/3-left-function-result.png) 

 You're all set.

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Extract the String to the Right of Your Text

 To get all the text that's to the right of the specified character in your cell, use Excel's `RIGHT` , `LEN` , and `FIND` functions.

 Start by launching your spreadsheet and clicking the cell in which you want to see the result.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/4-right-select-cell.png) 

 In the selected cell, enter the [following function](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/). In this function, replace `B2` with the cell where your full text is and `@` with the search character. Excel will extract the entire string to the right of this character.

 Then press Enter.

=RIGHT(B2,LEN(B2)-FIND("@",B2))

![Type the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/5-type-right-function.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll see the result of the function in your chosen cell.

![The result of the RIGHT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/6-right-function-result.png) 

 You're done.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

##  Obtain a String From the Middle of Your Text

 If you'd like to extract a string containing a specific number of characters located at a certain position in your cell, use Excel's `MID` function.

 In your spreadsheet, select the cell where you want to display the resulting string.

![Click a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/7-mid-select-cell.png) 

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the selected cell, enter the following function. In this function, replace `B2` with the cell where you have the full text, `1` with the position of the character where you want to start the string selection, and `3` with the number of characters you want to extract.

 Then press Enter.

=MID(B2,1,3)

![Enter the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/8-enter-mid-function.png) 

 Excel will extract the specified number of characters from the given position in your cell.

![The result of the MID function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/9-mid-function-result.png) 

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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-10-mock-musicals-that-bring-smiles/"><u>[New] In 2024, 10 Mock Musicals That Bring Smiles</u></a></li>
<li><a href="https://win-forum.techidaily.com/1-8/"><u>1. 제공되는 모든 기능에 꼈짐이 들어 있는 가장 최고의 맥북 비디오 편집 소프트웨어: 8개 선보기</u></a></li>
<li><a href="https://vp-tips.techidaily.com/15-simple-steps-to-convert-youtube-to-mpeg-effortlessly/"><u>15 Simple Steps to Convert YouTube to MPEG Effortlessly</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-harmony-of-collaboration-brands-and-youtube-unite/"><u>2024 Approved The Harmony of Collaboration Brands & YouTube Unite</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/decoding-the-purpose-of-windows-11s-update-helper-a-guide-to-easily-disable-or-remove-it/"><u>Decoding the Purpose of Windows 11'S Update Helper: A Guide to Easily Disable or Remove It</u></a></li>
<li><a href="https://article-posts.techidaily.com/full-analysis-of-t5-eyes-exceptional-action-recording-for-2024/"><u>Full Analysis of T5 Eye's Exceptional Action Recording for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/grayscale-conversion-black-and-white-effect-monochrome-and-simple-editing-tools/"><u>Grayscale Conversion, Black & White Effect, Monochrome, and Simple Editing Tools.</u></a></li>
<li><a href="https://data-wizards.techidaily.com/restoring-deformed-mp4-media-on-mobile-devices/"><u>Restoring Deformed MP4 Media on Mobile Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-xiaomi-13t-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Xiaomi 13T for Parents | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-3-estrategias-para-converter-filmes-em-dvd-do-formato-mkv-compativel-com-windows-e-mac/"><u>Top 3 Estratégias Para Converter Filmes Em DVD Do Formato MKV (Compatível Com Windows E Mac)</u></a></li>
<li><a href="https://win-forum.techidaily.com/trasforma-i-tuoi-file-ogv-in-animazioni-gif-senza-costi-con-movavi/"><u>Trasforma I Tuoi File OGV in Animazioni GIF Senza Costi Con Movavi</u></a></li>
</ul></div>

