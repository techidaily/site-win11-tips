---
title: "Troubleshooting: Reactivate Windows 11 MS Store Apps"
date: 2024-10-13T18:44:35.343Z
updated: 2024-10-21T03:43:55.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Reactivate Windows 11 MS Store Apps"
excerpt: "This Article Describes Troubleshooting: Reactivate Windows 11 MS Store Apps"
keywords: Reactivating Windows 11 Apps,MS Store Reset,Fixing MS Store Errors,Restore MS Store Functionality,Enable MS Store,Windows 11 App Activation,Reactivate MS Store
thumbnail: https://thmb.techidaily.com/05fdd1e1f79925f7174d27adc0ae3abbe1009fc921370376e92e90f7d158bcf8.jpg
---

## Troubleshooting: Reactivate Windows 11 MS Store Apps

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
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-unpacking-newscreenx-pros-recording-innovations/"><u>[New] In 2024, Unpacking NewScreenX Pro’s Recording Innovations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-swift-solution-tweeting-videos-not-functioning-chrome-for-2024/"><u>[New] Swift Solution Tweeting Videos Not Functioning Chrome for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-enhancement-the-art-of-background-blur/"><u>[New] YouTube Enhancement The Art of Background Blur</u></a></li>
<li><a href="https://win-able.techidaily.com/demystifying-nvidia-geforce-error-0x0003-effective-strategies-to-rectify-the-issue/"><u>Demystifying NVIDIA GeForce Error 0X0003: Effective Strategies to Rectify the Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-view-images-in-windows-11/"><u>How To Quickly View Images in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-nokia-g22-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Nokia G22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovations-in-computing-6-best-tracking-software-for-pc/"><u>Innovations in Computing: 6 Best Tracking Software for PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-logitech-steering-wheel-software-on-windows-versions-7810/"><u>Install Logitech Steering Wheel Software on Windows (Versions 7/8/10)</u></a></li>
<li><a href="https://win-studio.techidaily.com/ipad-videos-ubertragen-methoden-fur-den-aufwand-von-tablet-zu-tablet/"><u>IPad-Videos Übertragen - Methoden Für Den Aufwand Von Tablet Zu Tablet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-rainmeter-fixes-common-bugs-and-workarounds/"><u>Mastering Rainmeter Fixes: Common Bugs and Workarounds</u></a></li>
<li><a href="https://discord-videos.techidaily.com/navigating-discords-video-sharing-feature-with-expertise-for-2024/"><u>Navigating Discord's Video Sharing Feature with Expertise for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-realme-gt-neo-5-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Realme GT Neo 5 and Browser | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-performance-sluggishness-in-windows-with-dual-screen-views/"><u>Preventing Performance Sluggishness in Windows with Dual Screen Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-lost-panes-a-sixfold-approach-for-windows-users/"><u>Rediscovering Lost Panes: A Sixfold Approach for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-fixed-power-settings-on-windows-11/"><u>Solutions for Fixed Power Settings on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-common-caption-issues-on-windows-10-systems/"><u>Tackling Common Caption Issues on Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-tracker-titans-wins-best-tools-for-peak-efficiency/"><u>Time Tracker Titans: Win's Best Tools for Peak Efficiency</u></a></li>
</ul></div>

