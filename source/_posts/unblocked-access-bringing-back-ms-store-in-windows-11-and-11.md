---
title: "Unblocked Access: Bringing Back MS Store in Windows 11 & 11"
date: 2024-10-16T03:04:43.104Z
updated: 2024-10-20T22:04:09.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unblocked Access: Bringing Back MS Store in Windows 11 & 11"
excerpt: "This Article Describes Unblocked Access: Bringing Back MS Store in Windows 11 & 11"
keywords: WinMSStoreRevive,UnlockWindowsStore,Windows11MSAccess,MSStoreBackInWin11,ReleaseMSStoreWin11,AccessRestoredMS,BringingBackMSWin11
thumbnail: https://thmb.techidaily.com/26300a30b40be91fd1403de278cb19bb64bc0cc7c24d1ddb32b678a579f7aa1d.jpg
---

## Unblocked Access: Bringing Back MS Store in Windows 11 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-photo-refinement-essentials-expert-tips-for-efficient-background-clearance/"><u>[New] 2024 Approved Photo Refinement Essentials Expert Tips for Efficient Background Clearance</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-professional-drones-pro-level-editing-software-showdown/"><u>[Updated] Professional Drones, Pro-Level Editing Software Showdown</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-perfect-your-android-experience-with-screen-and-video-tech/"><u>2024 Approved Perfect Your Android Experience with Screen & Video Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-next-gen-windows-with-meaningful-improvements/"><u>Crafting Next-Gen Windows with Meaningful Improvements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-adjust-application-size-with-a-press-on-windows-11/"><u>Effortlessly Adjust Application Size with a Press on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Pause Life360 Location Sharing For Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/making-money-with-media-mastery-of-merchandise-musings-for-2024/"><u>Making Money with Media Mastery of Merchandise Musings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-we-encountered-an-error-in-oculus-app-setup/"><u>Overcoming We Encountered an Error in Oculus App Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h-265-on-samsung-galaxy-xcover-7-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Samsung Galaxy XCover 7, is it possible?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-lost-bluetooth-with-these-essential-win-11-solutions/"><u>Reignite Lost Bluetooth with These Essential Win 11 Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-system-cooling-settings-in-windows-os/"><u>Tailoring System Cooling Settings in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-setup-rgb-lighting-windows-11/"><u>Tips to Setup RGB Lighting Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/transform-your-screen-pip-tutorials-for-macos-enthusiasts/"><u>Transform Your Screen PIP Tutorials for macOS Enthusiasts</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-for-call-of-duty-modern-warfares-persistent-crashing-problem/"><u>Troubleshooting Guide for Call of Duty: Modern Warfare's Persistent Crashing Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steams-read-only-library-error-on-win-11/"><u>Troubleshooting Steam's Read-Only Library Error on Win 11</u></a></li>
</ul></div>

