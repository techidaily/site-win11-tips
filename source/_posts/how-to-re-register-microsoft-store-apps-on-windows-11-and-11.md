---
title: How to Re-Register Microsoft Store Apps on Windows 11 & 11
date: 2024-10-08T02:04:26.598Z
updated: 2024-10-08T16:01:00.229Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Re-Register Microsoft Store Apps on Windows 11 & 11
excerpt: This Article Describes How to Re-Register Microsoft Store Apps on Windows 11 & 11
keywords: Regain MS Store Access,Resetting App Permissions,Reactivate Microsoft Apps,Renewing OS Licenses,Reinstalling Windows Store,Restore Store Functionality,Update Windows 11 Apps
thumbnail: https://thmb.techidaily.com/6038b4e1d0b30613cb41c0ccc8733d5ac9ac78f0122128d3845aaea9056bae9f.jpg
---

## How to Re-Register Microsoft Store Apps on Windows 11 & 11

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
<a href="https://aligracehair.sjv.io/c/5597632/1959764/19272" target="_top" id="1959764">
  <img src="//a.impactradius-go.com/display-ad/19272-1959764" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959764/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-analyzing-bandicam-as-a-key-tool-in-digital-content-creation/"><u>[New] 2024 Approved Analyzing Bandicam as a Key Tool in Digital Content Creation</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-safe-no-cost-methods-for-youtube-tracks-extraction/"><u>[New] 2024 Approved Safe, No-Cost Methods for YouTube Tracks Extraction</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/omprehensively-reviewing-youtubes-restrictions-vs-cc-flexibility/"><u>[New] Comprehensively Reviewing YouTube's Restrictions Vs. CC Flexibility</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guidance-for-effortless-addition-of-youtube-playlists-to-your-site-for-2024/"><u>[New] Guidance for Effortless Addition of YouTube Playlists to Your Site for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-harness-the-power-of-post-production-top-11-techniques-for-vibrant-colors-for-2024/"><u>[Updated] Harness the Power of Post-Production Top 11 Techniques for Vibrant Colors for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-streamlining-film-shoots-a-beginners-guide/"><u>[Updated] In 2024, Streamlining Film Shoots A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-try-now-bluetooth-hurdle-on-pcs-and-tablets/"><u>Bypass 'Try Now' Bluetooth Hurdle on PCs & Tablets</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-icloud-on-apple-iphone-6-smoothly-by-drfone-ios/"><u>How To Remove iCloud On Apple iPhone 6 Smoothly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-barricades-implement-these-7-windows-protections/"><u>Network Barricades: Implement These 7 Windows Protections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-inaccessible-folder-issue-fix-steps-for-windows-based-pcs/"><u>Solving 'Inaccessible Folder' Issue: Fix Steps for Windows-Based PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-flaws-with-non-working-ccleaner-in-win1011/"><u>Techniques to Overcome Flaws with Non-Working CCleaner in Win10/11</u></a></li>
</ul></div>

