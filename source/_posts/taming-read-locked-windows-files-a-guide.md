---
title: "Taming Read-Locked Windows Files: A Guide"
date: 2024-09-27T01:21:13.676Z
updated: 2024-10-03T21:18:55.726Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Taming Read-Locked Windows Files: A Guide"
excerpt: "This Article Describes Taming Read-Locked Windows Files: A Guide"
keywords: Tame Read-Locks,Fixing Locked Files,File Unlocking Guide,Windows File Access,Overcoming Read-Locks,Data Recovery Steps,Secure File Retrieval
thumbnail: https://thmb.techidaily.com/1441934e237c52f497a6fd0ab6f056661ecffacc05322a198ecbbd0ad48fbaf8.jpg
---

## Taming Read-Locked Windows Files: A Guide

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-global-leaderboard-top-subscribers-by-youtube-star/"><u>[New] In 2024, Global Leaderboard Top Subscribers by YouTube Star</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/hy-youtubes-viewer-numbers-matter-more-than-you-think/"><u>[New] Why YouTube's Viewer Numbers Matter More Than You Think</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-high-end-sound-pumping-tools-pcs-and-smartphones-for-2024/"><u>[Updated] High-End Sound Pumping Tools PCs & Smartphones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-editing-the-8-pinnacle-software-titles-for-windows-users/"><u>Conquer Editing: The 8 Pinnacle Software Titles for Windows Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/easy-steam-recordings-with-team-fortress-2s-latest-update/"><u>Easy Steam Recordings with Team Fortress 2'S Latest Update</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/effizientes-video-rendering-mit-adobe-after-effects-professionelle-tipps-zur-exportierung/"><u>Effizientes Vidéo-Rendering Mit Adobe After Effects - Professionelle Tipps Zur Exportierung</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-farmers-hangout-top-10-friendly-agricultural-games-to-bond-with-friends/"><u>In 2024, Farmers' Hangout Top 10 Friendly Agricultural Games to Bond With Friends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-with-reimagined-windows-11-widgets/"><u>Maximizing Productivity with Reimagined Windows 11 Widgets</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-stutters-on-civi-3-and-stops-randomly-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV stutters on Civi 3 and stops randomly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-experience-outlook-preview-for-windows-11-enthusiasts/"><u>Optimize Your Experience: Outlook Preview for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-ethernet-connectivity-on-windows/"><u>Re-Establishing Ethernet Connectivity on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-invisible-connection-on-microsofts-new-os/"><u>Resurrecting Your Invisible Connection on Microsoft's New OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-blocking-insecure-device-connections-on-windows/"><u>Tips for Blocking Insecure Device Connections on Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/turn-your-photos-into-funny-cartoons-online/"><u>Turn Your Photos Into Funny Cartoons Online</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unlock-adobe-premieres-full-potential-top-15-plugins-free-download/"><u>Unlock Adobe Premieres Full Potential Top 15 Plugins (Free Download)</u></a></li>
</ul></div>

