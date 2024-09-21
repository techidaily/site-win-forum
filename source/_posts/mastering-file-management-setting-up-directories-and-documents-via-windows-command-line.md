---
title: "Mastering File Management: Setting Up Directories & Documents via Windows Command Line"
date: 2024-09-14T16:14:04.678Z
updated: 2024-09-21T17:22:09.375Z
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

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135414/19272" target="_top" id="2135414">
  <img src="//a.impactradius-go.com/display-ad/19272-2135414" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135414/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Make sure to enclose the folder name with double quotes if its name has spaces.

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-the-magic-behind-immersive-world-creation/"><u>[New] 2024 Approved The Magic Behind Immersive World Creation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-lifelike-linkage-logistics-softwares-substance-over-hardwares-hustle/"><u>[New] Lifelike Linkage Logistics Software's Substance over Hardware's Hustle</u></a></li>
<li><a href="https://win-forum.techidaily.com/movaviwebmwmv/"><u>使用Movavi將WebM自動無條件地轉換成WMV格式 - 在線免費服務</u></a></li>
<li><a href="https://win-forum.techidaily.com/conversion-gratuita-transforma-tu-musica-de-wma-a-mp3-directamente-desde-el-web/"><u>Conversión Gratuita: Transforma Tu Música De WMA a MP3 Directamente Desde El Web</u></a></li>
<li><a href="https://win-forum.techidaily.com/converti-gif-in-file-ogv-senza-costi-su-internet-con-movavi-il-modo-piu-veloce-e-facile/"><u>Converti GIF in File OGV Senza Costi Su Internet Con Movavi - Il Modo Più Veloce E Facile!</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortlessly-resize-and-snip-iphone-footage-using-our-5-tricks-tutorial/"><u>Effortlessly Resize & Snip iPhone Footage Using Our 5-Tricks Tutorial</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-launchpad-gear-list-enhance-your-beginners-gopro-journey/"><u>In 2024, Launchpad Gear List - Enhance Your Beginner's GoPro Journey</u></a></li>
<li><a href="https://win-forum.techidaily.com/metodo-simple-para-convertir-archivos-flv-en-mp3-online-sin-gasto-recomendado-por-movavi/"><u>Método Simple Para Convertir Archivos FLV en MP3 Online Sin Gasto: Recomendado Por Movavi</u></a></li>
<li><a href="https://win-forum.techidaily.com/online-free-mp4-a-aac-convertidor-pelo-site-movavi-sem-custo/"><u>Online Free MP4 a AAC Convertidor Pelo Site Movavi - Sem Custo!</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/organize-your-videos-with-ease-top-8-mac-metadata-editors/"><u>Organize Your Videos with Ease Top 8 Mac Metadata Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quashing-games-recommendations-on-win11-systems/"><u>Quashing Games Recommendations on Win11 Systems</u></a></li>
<li><a href="https://techtrends.techidaily.com/smart-assistants-face-off-why-alexa-or-google-assistant-might-be-your-ideal-pick/"><u>Smart Assistants Face-Off: Why Alexa or Google Assistant Might Be Your Ideal Pick</u></a></li>
<li><a href="https://win-forum.techidaily.com/top-7-mejores-capturadoras-de-video-en-la-web-movavi/"><u>Top 7 Mejores Capturadoras De Video en La Web - Movavi</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/transform-yourfb-watchlist-with-easy-youtube-video-autoplay-configuration/"><u>Transform YourFB Watchlist with Easy Youtube Video Autoplay Configuration</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-guide-for-linksys-ae1200-wireless-router-driver-installation-best-practices-and-fixes/"><u>Troubleshooting Guide for Linksys AE1200 Wireless Router Driver Installation – Best Practices & Fixes</u></a></li>
</ul></div>

