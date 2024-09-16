---
title: "Mastering File Management: Setting Up Directories & Documents via Windows Command Line"
date: 2024-09-13T16:22:42.800Z
updated: 2024-09-16T16:26:53.668Z
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

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

 Make sure to enclose the folder name with double quotes if its name has spaces.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-choreographed-vocal-harmony-on-tiktok/"><u>[Updated] 2024 Approved Choreographed Vocal Harmony on TikTok</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-discover-the-perfect-tunefab-recorder-for-your-needs/"><u>[Updated] 2024 Approved Discover the Perfect Tunefab Recorder for Your Needs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-selecting-the-finest-screen-recorders-1-to-5-android/"><u>[Updated] In 2024, Selecting the Finest Screen Recorders, #1 to #5 (Android)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/360-degree-cameras-vs-3d-cameras-what-are-the-differences-in-2024/"><u>360 Degree Cameras Vs 3D Cameras What Are the Differences, In 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-oppo-reno-11-pro-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Oppo Reno 11 Pro 5G? Try These Fixes</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-honor-90-pro-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-tecno-camon-20-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Tecno Camon 20 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-realme-v30-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Realme V30 for Streaming | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/lockdowns-and-stay-at-home-orders/"><u>Lockdowns and Stay-at-Home Orders</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-methods-for-discovering-and-deleting-aged-data-on-your-windows-11-pc/"><u>Quick Methods for Discovering and Deleting Aged Data on Your Windows 11 PC</u></a></li>
<li><a href="https://win-forum.techidaily.com/retro-tech-goes-open-source-microsofts-dos-40-from-the-late-80s-ready-to-download/"><u>Retro Tech Goes Open Source: Microsoft's DOS 4.0 From the Late '80S Ready to Download!</u></a></li>
<li><a href="https://win-forum.techidaily.com/save-big-secure-microsoft-windows-11-pro-with-an-impressive-88-price-cut/"><u>Save Big: Secure Microsoft Windows 11 Pro with an Impressive 88% Price Cut!</u></a></li>
<li><a href="https://win-forum.techidaily.com/secure-your-childs-digital-space-a-step-by-step-tutorial-for-enabling-parental-controls-in-windows-11/"><u>Secure Your Child's Digital Space: A Step-by-Step Tutorial for Enabling Parental Controls in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-removing-items-from-clipboard-memory-in-windows-11/"><u>Step-by-Step Guide: Removing Items From Clipboard Memory in Windows 11</u></a></li>
</ul></div>

