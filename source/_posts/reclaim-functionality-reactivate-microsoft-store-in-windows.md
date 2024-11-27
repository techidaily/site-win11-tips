---
title: "Reclaim Functionality: Reactivate Microsoft Store in Windows"
date: 2024-11-22T16:35:33.450Z
updated: 2024-11-27T16:38:43.538Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reclaim Functionality: Reactivate Microsoft Store in Windows"
excerpt: "This Article Describes Reclaim Functionality: Reactivate Microsoft Store in Windows"
keywords: Activate MS Store,Restore Microsoft Shop,Revive Windows Store,Reinstate MS Apps,Enable MS Functionality,Reactivate OS Marketplace,Resurrect Microsoft Store
thumbnail: https://thmb.techidaily.com/26fc91ea31b084d9024cbf2c3260379dfbc09b55f5ef939a3a4cdd1934973c13.jpeg
---

## Reclaim Functionality: Reactivate Microsoft Store in Windows

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/new-advanced-tools-for-efficiently-converting-xmlssattml-to-srt/"><u>[New] Advanced Tools for Efficiently Converting XML/SSA/TTML to SRT</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-champion-avc-player-for-seamless-viewing/"><u>[New] In 2024, Champion AVC Player for Seamless Viewing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-make-a-statement-with-free-profile-pics/"><u>[Updated] Make a Statement With Free Profile Pics</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-meme-makers-guide-for-iphones/"><u>2024 Approved Meme Makers' Guide (For iPhones)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/adding-emotion-and-context-narration-for-videos-for-2024/"><u>Adding Emotion and Context Narration for Videos for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-fixes-to-solve-iphone-x-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>Complete Fixes To Solve iPhone X Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://some-guidance.techidaily.com/convertir-archivos-flv-a-ogv-sin-coste-guia-completa-de-movavi/"><u>Convertir Archivos FLV a OGV Sin Coste: Guía Completa De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-hardware-assisted-graphics-ordering/"><u>Decoding Windows' Hardware-Assisted Graphics Ordering</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delineating-differences-cloud-downloads-vs-disk-based-windows-setup/"><u>Delineating Differences: Cloud Downloads vs Disk-Based Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-system-efficiency-reducing-tiworkerexe-resource-use/"><u>Enhancing System Efficiency: Reducing TiWorker.exe Resource Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-grayed-out-trash-can-icon-in-win11-os/"><u>Fixing Grayed-Out Trash Can Icon in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-unresponsive-razer-synapse-in-windows-11/"><u>Guide to Fixing Unresponsive Razer Synapse in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-troubleshoot-malfunctioning-google-nearby-share/"><u>Guidelines to Troubleshoot Malfunctioning Google Nearby Share</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-iphone-se-2022-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass iPhone SE (2022) Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-virtual-memory-a-comprehensive-guide-for-win-11/"><u>Managing Virtual Memory: A Comprehensive Guide for Win 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/outsmarting-the-obtrusive-fb-video-ads-for-2024/"><u>Outsmarting the Obtrusive FB Video Ads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-ip-addressing-on-your-win11-pc/"><u>Streamline IP Addressing on Your Win11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-dissecting-and-organizing-windows-storage/"><u>The Complete Guide to Dissecting and Organizing Windows Storage</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-rated-mac-video-editing-software-by-apple/"><u>Top-Rated Mac Video Editing Software by Apple</u></a></li>
</ul></div>

