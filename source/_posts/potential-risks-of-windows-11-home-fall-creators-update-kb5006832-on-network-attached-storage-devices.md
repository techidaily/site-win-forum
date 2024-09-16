---
title: Potential Risks of Windows 11 Home Fall Creators Update (KB5006832) on Network-Attached Storage Devices
date: 2024-09-12T16:52:08.125Z
updated: 2024-09-16T16:41:18.944Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/windows-11-3.jpg
---

## Potential Risks of Windows 11 Home Fall Creators Update (KB5006832) on Network-Attached Storage Devices

The Windows 11 24H2 update is nearing release, and it comes with a few changes that could break specific apps and workflows. Microsoft is now warning people (again) about changes to SMB connections that might impact NAS drives.

 Microsoft just [released the Windows 11 24H2 update in the Release Preview Channel](https://some-knowledge.techidaily.com/in-2024-illumination-in-high-dynamic-range-a-smart-option/), ahead of its rollout to all Windows 11 PCs in a few months. The update requires SMB signing on all connections and removes support for guest fallback on Windows 11 Pro edition. Those are important security upgrades, but they also mean some network drives and folders won’t work anymore without changes to settings or software upgrades.

 Microsoft said in a blog post, “SMB signing has been available in Windows for 30 years but, for the first time, is now required by default on all connections. Guest has been disabled in Windows for 25 years and SMB guest fallback disabled since Windows 10 in Enterprise, Education, and Pro for Workstation editions. Both changes will make billions of devices more secure. They've been in Windows Insider Dev and Canary builds for a year.”

 This will mainly affect older NAS devices and other network devices that aren’t configured for SMB signing. Newer NAS hardware should already have that working and configured, but there’s a chance some device manufacturers didn’t bother because it wasn’t strictly required (until now).

 Microsoft recommends setting up SMB signing on your NAS, setting up a username and password, and turning off guest sign in. If none of those options are available, you can try checking for software updates on the NAS—the manufacturer might have implemented those features after the device was shipped.

 For NAS devices that don’t support the required security features and don’t have any updates, there will be a workaround available in the Edit Group Policy app. However, Microsoft warns that that the steps “will make your Windows device and your data much less safe.”

 Windows 24H2 is expected to be released in a few months, but it might take longer than that to roll out to all Windows 11 PCs automatically.

 Source: [Microsoft Blog](https://techcommunity.microsoft.com/t5/storage-at-microsoft/accessing-a-third-party-nas-with-smb-in-windows-11-24h2-may-fail/ba-p/4154300)

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
<li><a href="https://some-approaches.techidaily.com/aic4-mp4/"><u>AIC変換無料プログラムトップ4: MP4ファイルを効率良く変換する方法</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mkv-files-on-moto-g24-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do you play MKV files on Moto G24?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mastering-color-grading-techniques-in-gopro-studio/"><u>In 2024, Mastering Color Grading Techniques in GoPro Studio</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your iPhone 11 Pro Max</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-year-ahead-exploring-instagrams-innovative-filters-for-2024/"><u>The Year Ahead Exploring Instagram's Innovative Filters for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/uncover-the-secrets-of-windows-11-explore-11-essential-yet-overlooked-features/"><u>Uncover the Secrets of Windows 11 - Explore 11 Essential Yet Overlooked Features!</u></a></li>
<li><a href="https://win-forum.techidaily.com/understanding-microsofts-recall-capability-advanced-tech-beyond-artificial-intelligence-requirements/"><u>Understanding Microsoft's 'Recall' Capability – Advanced Tech Beyond Artificial Intelligence Requirements</u></a></li>
<li><a href="https://win-forum.techidaily.com/upcoming-windows-11-v24h2-removes-support-for-vbscript-technology/"><u>Upcoming Windows 11 V.24H2 Removes Support for VBScript Technology</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

