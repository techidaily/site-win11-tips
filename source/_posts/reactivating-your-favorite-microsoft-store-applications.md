---
title: Reactivating Your Favorite Microsoft Store Applications
date: 2024-12-05T22:18:01.577Z
updated: 2024-12-13T01:57:35.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Your Favorite Microsoft Store Applications
excerpt: This Article Describes Reactivating Your Favorite Microsoft Store Applications
keywords: Reactivate MS Store Apps,Reinstalling Microsoft Apps,Microsoft App Restart,Bringing Back MS Apps,Update Microsoft Software,Resurrect MS Suite,Revive Windows Store Apps
thumbnail: https://thmb.techidaily.com/30033eb1d439e3a5ccb9587805c5084ce6ce6344b14d88b85b8e477a0430e0fc.jpg
---

## Reactivating Your Favorite Microsoft Store Applications

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-fundamentals-of-designing-high-converting-snap-ads/"><u>[New] 2024 Approved Fundamentals of Designing High-Converting Snap Ads</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-small-channels-big-opportunities-an-affiliate-approach/"><u>[Updated] Small Channels, Big Opportunities An Affiliate Approach</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-crafting-captivating-images-using-leading-lines-iphone/"><u>2024 Approved Crafting Captivating Images Using Leading Lines (iPhone)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-local-users-and-groups-management-in-windows-11-and-10-home/"><u>How to Enable Local Users and Groups Management in Windows 11 and 10 Home</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-jailbreak-icloud-locked-iphone-x-by-drfone-ios/"><u>How to jailbreak iCloud locked iPhone X</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Samsung Galaxy M34 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-apple-iphone-12-pro-by-name-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Apple iPhone 12 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-silencing-geforce-ui/"><u>Mastering the Art of Silencing GeForce UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-compression-rectifying-checksum-errors-with-winrar/"><u>Precision in Compression: Rectifying Checksum Errors with WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-responsive-brighness-fn-key-on-windows-11/"><u>Resolving Non-Responsive Brighness Fn Key on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-a-revolutionary-calculator-for-your-ipad-is-it-so-advanced-youll-need-to-get-an-apple-pencil-insights/"><u>Unveiling a Revolutionary Calculator for Your iPad – Is It So Advanced You'll Need to Get an Apple Pencil? Insights</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-windows-media-seamless-cd-extraction-for-2024/"><u>Unveiling Windows Media Seamless CD Extraction for 2024</u></a></li>
</ul></div>

