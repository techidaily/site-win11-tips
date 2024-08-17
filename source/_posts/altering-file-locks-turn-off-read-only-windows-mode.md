---
title: "Altering File Locks: Turn Off Read-Only Windows Mode"
date: 2024-08-16T02:17:08.598Z
updated: 2024-08-17T02:17:08.598Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering File Locks: Turn Off Read-Only Windows Mode"
excerpt: "This Article Describes Altering File Locks: Turn Off Read-Only Windows Mode"
keywords: Disable Read-Only Files,Turn Off WIN ReadLock,Remove File Read-Only Status,Stop WIN Read-Only Mode,Eliminate Windows Locks,Bypass Read-Only Windows,Override File Permissions
thumbnail: https://thmb.techidaily.com/80fee98e39755278bb461fd482dd243762bcc8eb6156836ba9860fa44be8739e.jpg
---

## Altering File Locks: Turn Off Read-Only Windows Mode

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

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
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-files.techidaily.com/new-from-portrait-to-panorama-a-guide-to-instagrams-rotation-revolution/"><u>[New] From Portrait to Panorama  A Guide to Instagram's Rotation Revolution</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-vlc-video-record-a-critique/"><u>[Updated] 2024 Approved  VLC Video Record  A Critique</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevate-engagement-personalized-youtube-thumbnail-guide/"><u>[Updated] In 2024, Elevate Engagement  Personalized YouTube Thumbnail Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-elevate-your-reel-game-on-insta-with-tiktoks-best-practices/"><u>[Updated] In 2024, Elevate Your Reel Game on Insta with TikTok's Best Practices</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-invaluable-resource-for-zero-cost-video-and-photo-providers/"><u>[Updated] Invaluable Resource for Zero-Cost Video and Photo Providers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-moviegenius-for-windows-8/"><u>[Updated] MovieGenius for Windows 8</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-real-time-streaming-obs-to-instagram-for-2024/"><u>[Updated] Real-Time Streaming  OBS to Instagram for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-revolutionize-mobile-broadcasting-integrating-obs-studio-into-android/"><u>[Updated] Revolutionize Mobile Broadcasting  Integrating OBS Studio Into Android</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-step-by-step-guide-how-to-convert-youtube-streaming-into-a-free-screencast/"><u>[Updated] Step by Step Guide  How To Convert YouTube Streaming Into a Free Screencast</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-essence-of-authenticity-applying-personalized-watermarks-in-insta-for-2024/"><u>[Updated] The Essence of Authenticity  Applying Personalized Watermarks in Insta for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-steam-must-be-running-to-play-this-game-error-in-windows-11/"><u>7 Ways to Fix the Steam Must Be Running to Play This Game Error in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-oppo-reno-11-pro-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Oppo Reno 11 Pro 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-virtual-machine-security-with-vboxs-secure-boot-toggle/"><u>Boost Virtual Machine Security with VBox's Secure Boot Toggle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-into-peace-five-tactics-to-overcome-windows-security-failures/"><u>Boot Into Peace: Five Tactics to Overcome Windows Security Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-blackout-with-easy-tips-and-tricks/"><u>Bypass Windows 11 Blackout with Easy Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-privilege-needed-blue-screen-windows-fix-guide/"><u>Bypassing 'Privilege Needed' Blue Screen: Windows Fix Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/first-offset-guide-affordable-channel-buys-to-monetize-for-2024/"><u>First Offset Guide  Affordable Channel Buys to Monetize for 2024</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-vivo-s18e-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Vivo S18e Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-infinix-smart-7-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Infinix Smart 7 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-7-plus-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 7 Plus To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-comprehensively-guide-to-collecting-visual-backgrounds/"><u>In 2024, Comprehensively Guide to Collecting Visual Backgrounds</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-infinix-hot-40-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Infinix Hot 40 Phone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-phone-number-from-your-apple-id-from-your-iphone-se-by-drfone-ios/"><u>In 2024, How To Remove Phone Number From Your Apple ID from Your iPhone SE?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-toolkit-for-dominating-social-media-management-smm/"><u>In 2024, The Ultimate Toolkit for Dominating Social Media Management (SMM)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lighter-browsing-experience-on-the-desktop-top-7-test-results/"><u>Lighter Browsing Experience on the Desktop: Top 7 Test Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organize-windows-icons-harmoniously/"><u>Organize Windows Icons Harmoniously</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-nvidia-connect-error-in-windows-oses/"><u>Overcoming NVIDIA Connect Error in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win11s-security-measures-through-rufus-mastery/"><u>Overcoming Win11's Security Measures Through Rufus Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-system-cooling-policy-in-pcs/"><u>Reinstating Absent System Cooling Policy in PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-nokia-c32-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Nokia C32</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-revitalize-stuck-and-slow-downloads-in-windows-directory/"><u>Steps to Revitalize Stuck and Slow Downloads in Windows Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unlocking-screen-pin-free-windows-projection/"><u>Stop Unlocking Screen: PIN-Free Windows Projection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-lcd-panels-simplified-guide/"><u>Switching LCD Panels Simplified Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-music-choices-for-captivating-video-experiences-for-2024/"><u>Top Music Choices for Captivating Video Experiences for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-content-restricted-in-windows-steam/"><u>Unraveling Content Restricted in Windows Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
</ul></div>
