---
title: Quick Fix for Non-Functional Microsoft Store in Windows 11
date: 2024-09-11T22:52:02.609Z
updated: 2024-09-16T19:12:45.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
excerpt: This Article Describes Quick Fix for Non-Functional Microsoft Store in Windows 11
keywords: Windows 11 Store Issue,Microsoft Store Repair,Fixing Microsoft Store,Functioning MS Store,Quick Microsoft Fix,Restore MS Store,Stop Non-Functional Store
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Quick Fix for Non-Functional Microsoft Store in Windows 11

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

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-ultimate-checklist-seamless-conversion-of-phone-photos-to-snapchat/"><u>[New] 2024 Approved The Ultimate Checklist Seamless Conversion of Phone Photos to Snapchat</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-recording-game-changer-for-facebook-streams/"><u>[New] The Recording Game-Changer for Facebook Streams</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-essential-list-for-screen-clarity-top-7-android-adblockers/"><u>[Updated] The Essential List for Screen Clarity Top 7 Android AdBlockers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-odbc-data-source-wizard/"><u>Exploring Windows ODBC Data Source Wizard</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-asus-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Asus Phone Screen?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-for-windows-11-rgb-lighting/"><u>Instructions for Windows 11 RGB Lighting</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-windows-activation-flaw-0x803f700f/"><u>Mastering the Resolution of Windows Activation Flaw 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weather-software-for-w10w11-pcs/"><u>Prime Weather Software for W10/W11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-xc0351000-error-lack-of-hypervisor-in-windows-sandbox/"><u>Solving XC0351000 Error - Lack of Hypervisor in Windows Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-successful-application-use-after-a-windows-glitch/"><u>Unlocking Successful Application Use After a Windows Glitch</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

