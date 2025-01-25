---
title: "Bring Back the Store: Reactivation Steps for MS in Windows 11"
date: 2025-01-22T20:40:16.788Z
updated: 2025-01-24T23:39:23.995Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bring Back the Store: Reactivation Steps for MS in Windows 11"
excerpt: "This Article Describes Bring Back the Store: Reactivation Steps for MS in Windows 11"
keywords: Revive Win11 Stores,ReactWinMS Shop,StoreRevive Windows11,MS Marketplace Update,Reinstall WinStore,Win11 Retail Service,MS Store Reactivation
thumbnail: https://thmb.techidaily.com/16d13254afac9149dce0a2e443b3fbb7f20249bb61b5f6680c7797d944c293aa.jpg
---

## Bring Back the Store: Reactivation Steps for MS in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-your-first-encounter-with-snapseed-image-editing-for-2024/"><u>[New] Your First Encounter with Snapseed Image Editing for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-anime-inspired-filters-and-overlays-for-trendy-tiktok-videos/"><u>[Updated] 2024 Approved Anime-Inspired Filters & Overlays for Trendy TikTok Videos</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-front-seat-pleasures-not-so-sporty-top-ten/"><u>[Updated] 2024 Approved Front Seat Pleasures Not So Sporty Top Ten</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unleash-creativity-harnessing-gs-power-in-kinemaster/"><u>2024 Approved Unleash Creativity Harnessing GS Power in KineMaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-crashing-screens-winning-strategies-for-sonic-games-w11/"><u>Conquering Crashing Screens: Winning Strategies for Sonic Games (W11)</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-vivo-s17-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-running-the-sfc-command-in-windows/"><u>Guide to Running the SFC Command in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-much-power-does-my-windows-pc-use-heres-how-to-find-out/"><u>How Much Power Does My Windows PC Use? Here's How to Find Out</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-apple-iphone-6s-by-drfone-ios/"><u>How to Fix Locked Apple ID on Apple iPhone 6s</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-oppo-f23-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Oppo F23 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-how-to-view-gpx-files-online-and-offline-solutions-of-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>In 2024, How to View GPX Files Online and Offline Solutions Of Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-vscode-running-smoothly-w11-style/"><u>Keeping VSCode Running Smoothly W11-Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11-with-simple-app-resets/"><u>Optimizing Windows 11 with Simple App Resets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-and-thx-spatial-sound/"><u>Realigning Windows and THX Spatial Sound</u></a></li>
<li><a href="https://win-answers.techidaily.com/wmvipad2/"><u>WMVビデオ簡単にiPadで楽しめる、2つの解決法をご紹介</u></a></li>
</ul></div>

