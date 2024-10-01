---
title: "Mastering File Management: Setting Up Directories & Documents via Windows Command Line"
date: 2024-09-29T16:08:53.380Z
updated: 2024-10-01T16:56:34.062Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/cb670c879e89656e881160d22473efee38dda114df0401fe96c31b4cf2882857.jpg
---

## Mastering File Management: Setting Up Directories & Documents via Windows Command Line

### Quick Links

* [Before You Begin: Copy the Folder Path and Launch Command Prompt](https://desktop-recording.techidaily.com/updated-iphone-filmmaking-101-capturing-time-in-pixels/)
* [Create a Single Folder](https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-x7b-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Create a Folder Inside Another Folder (Subfolder)](https://www.howtogeek.com/how-to-create-folders-and-files-from-windows-command-prompt/#create-a-folder-inside-another-folder-subfolder)
* [Create Multiple Folders at Once](https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-xr-without-password-by-drfone-ios/)
* [Create a File with Command Prompt](https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-infinix-hot-40i-drfone-by-drfone-virtual-android/)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

 Make sure to enclose the folder name with double quotes if its name has spaces.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

 To create a text file and add some actual text to it, use the following command. Replace "Welcome to How-To Geek" with the text you want to add and "howtogeek" with the name you want to use for the file.

echo Welcome to How-To Geek > howtogeek.txt

 When you open howtogeek.txt in a text editor you'll find it has "Welcome to How-To Geek" written in it. 

---

 And that’s how you make folders and files without using graphical tools on your Windows machine.

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
<li><a href="https://fox-links.techidaily.com/new-cutting-edge-graphic-amendments-for-2024/"><u>[New] Cutting-Edge Graphic Amendments for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/productname-the-ultimate-autonomous-analytics-solution-for-superior-seo-results/"><u>[Product_Name]: The Ultimate Autonomous Analytics Solution for Superior SEO Results</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-exploring-instagrams-max-video-length-for-2024/"><u>[Updated] Exploring Instagram's Max Video Length for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-streamlining-your-photo-editing-the-crop-essentials/"><u>[Updated] Streamlining Your Photo Editing The Crop Essentials</u></a></li>
<li><a href="https://change-location.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/delete-kernel-or-full-memory-dumps-from-windows-11-systematically/"><u>Delete Kernel or Full Memory Dumps From Windows 11 Systematically</u></a></li>
<li><a href="https://win-forum.techidaily.com/digital-influencers-at-play-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Digital Influencers at Play: Navigating Through Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/elites-take-the-future-of-global-ai-technology/"><u>Elite's Take: The Future of Global AI Technology</u></a></li>
<li><a href="https://win-forum.techidaily.com/expert-tips-for-resolving-task-unsuccessful-errors-in-microsofts-latest-operating-system/"><u>Expert Tips for Resolving 'Task Unsuccessful' Errors in Microsoft's Latest Operating System</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-from-your-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID From Your iPhone 15 Pro Max</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-zte-axon-40-lite-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On ZTE Axon 40 Lite? Fixed | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/leveraging-social-giants-tactics-for-facebook-twitter-instagram-and-youtube-success/"><u>Leveraging Social Giants: Tactics for Facebook, Twitter, Instagram & YouTube Success</u></a></li>
<li><a href="https://win-forum.techidaily.com/maximize-connections-streamlined-menu-for-linkedin-facebook-and-youtube-instant-page-navigation-to-top/"><u>Maximize Connections: Streamlined Menu for LinkedIn, Facebook, and YouTube | Instant Page Navigation to Top</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809009086-maximize-your-sites-accessibility-swiftly-navigate-to-the-top-and-seamlessly-connect-with-facebook-linkedin-and-youtube-through-our-expanding-toggle-menu/"><u>Maximize Your Site's Accessibility - Swiftly Navigate to the Top and Seamlessly Connect with Facebook, LinkedIn, and YouTube Through Our Expanding Toggle Menu</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-top-four-digital-connectors-facebook-twitter-instagram-and-you-tube/"><u>The Top Four Digital Connectors: Facebook, Twitter, Instagram and You-Tube</u></a></li>
<li><a href="https://win-forum.techidaily.com/1723809008145-top-tips-for-optimizing-menu-functionality-on-leading-networks-learn-to-efficiently-scroll-and-manage-content-on-facebook-linkedin-and-youtube/"><u>Top Tips for Optimizing Menu Functionality on Leading Networks – Learn to Efficiently Scroll & Manage Content on Facebook, LinkedIn, and YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unveiling-igtv-insights-key-measures-for-effective-content/"><u>Unveiling IGTV Insights Key Measures for Effective Content</u></a></li>
</ul></div>

