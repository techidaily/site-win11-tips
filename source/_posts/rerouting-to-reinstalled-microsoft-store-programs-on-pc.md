---
title: Rerouting to Reinstalled Microsoft Store Programs on PC
date: 2024-09-16T03:01:34.398Z
updated: 2024-09-21T20:45:11.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rerouting to Reinstalled Microsoft Store Programs on PC
excerpt: This Article Describes Rerouting to Reinstalled Microsoft Store Programs on PC
keywords: Store Redirection,MS Store Update,Reinstall Microsoft Apps,Pc Software Relaunch,System Restore for MS Store,Retry Microsoft Installation,PC Store Refresh
thumbnail: https://thmb.techidaily.com/db39cf974b891a971b269fa1b5c545ac5598c4412d012bd826ff7f5dff9de440.png
---

## Rerouting to Reinstalled Microsoft Store Programs on PC

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
<li><a href="https://snapchat-videos.techidaily.com/new-enhancing-video-longeayer-androidmac-app-utilization/"><u>[New] Enhancing Video Longeayer Android/Mac App Utilization</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-vdx-quickcapture-evaluation-complete-reviews/"><u>[New] VDX QuickCapture Evaluation Complete Reviews</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-videography-essentials-7-free-audio-choices/"><u>[New] YouTube Videography Essentials - 7 Free Audio Choices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-amplify-earnings-monetize-youtube-on-the-go-with-effective-techniques/"><u>[Updated] Amplify Earnings Monetize YouTube on the Go with Effective Techniques</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-guide-to-equipment-selection-for-youtube-creators-for-2024/"><u>[Updated] Guide to Equipment Selection for YouTube Creators for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-speech-file-extract-and-critical-assessment/"><u>[Updated] In 2024, Speech File Extract & Critical Assessment</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/beyond-the-smile-your-guide-to-authentic-instagram-selfies-for-2024/"><u>Beyond the Smile - Your Guide to Authentic Instagram Selfies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/developing-an-in-context-notifier-for-automatic-software-updates-in-win11/"><u>Developing an In-Context Notifier for Automatic Software Updates in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-extend-your-win11-menu-with-portables/"><u>Effortlessly Extend Your Win11 Menu With Portables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-or-remove-the-run-as-different-user-option-to-start-on-windows-11/"><u>How to Add or Remove the “Run as Different User” Option to Start on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-defective-zip-operations-in-win-11-os/"><u>Tackling Defective ZIP Operations in Win 11 OS</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

