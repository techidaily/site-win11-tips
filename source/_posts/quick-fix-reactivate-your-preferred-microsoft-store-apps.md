---
title: "Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
date: 2024-11-21T16:44:17.265Z
updated: 2024-11-27T16:56:11.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
excerpt: "This Article Describes Quick Fix: Reactivate Your Preferred Microsoft Store Apps"
keywords: Reactivate MS Store,Quick App Restore,Microsoft Store Revive,Renew Windows Purchases,Resurrect Purchased Games,Update MS Store Items,Reactivate Windows Store Apps
thumbnail: https://thmb.techidaily.com/0b17306a3ff43a3354c035a000988ea5867c75fb650ef14b9ada7d7d6b9ca442.jpg
---

## Quick Fix: Reactivate Your Preferred Microsoft Store Apps

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-retro-smile-captured-by-iphone-x-classic/"><u>[New] 2024 Approved Retro Smile Captured by iPhone X Classic</u></a></li>
<li><a href="https://screen-recording.techidaily.com/conquer-video-production-obs-studio-and-android-for-2024/"><u>Conquer Video Production OBS Studio and Android for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-unpreviews-in-windows-outlook-for-businesses/"><u>Conquering Unpreviews in Windows Outlook for Businesses</u></a></li>
<li><a href="https://fox-tips.techidaily.com/discover-the-art-of-effective-web-browsing-navigating-search-pages-with-ease/"><u>Discover the Art of Effective Web Browsing: Navigating Search Pages with Ease</u></a></li>
<li><a href="https://solve-hot.techidaily.com/enhancing-online-engagement-with-cookiebot-technology-solutions/"><u>Enhancing Online Engagement with Cookiebot Technology Solutions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-ideas-to-epics-leveraging-chatgpt-for-unparalleled-story-crafting-skills/"><u>From Ideas to Epics: Leveraging ChatGPT for Unparalleled Story Crafting Skills</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-se-2020-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-samsung-galaxy-a24-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Samsung Galaxy A24 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-contextual-menu-integration-new-folder-placement/"><u>Mastering Contextual Menu Integration: New Folder Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-education-on-windows-8-proven-methods/"><u>Mastering Education on Windows: 8 Proven Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-setting-up-jdk-on-your-windows-11-system/"><u>Mastering the Art of Setting Up JDK on Your Windows 11 System</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-ultimate-compilation-top-10-audio-processing-mobile-apps-ios-and-android-for-2024/"><u>New The Ultimate Compilation Top 10 Audio Processing Mobile Apps (iOS and Android) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-need-to-panic-solve-black-windows-issues-fast/"><u>No Need to Panic - Solve Black Windows Issues Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pagefilesys-explained-its-relevance-and-potential-risks/"><u>Pagefile.sys Explained: Its Relevance and Potential Risks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-high-gpu-load-on-windows-wm-window/"><u>Reducing High GPU Load on Windows WM Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-xc10100bf-for-non-playing-media/"><u>Resolving Error XC10100BF for Non-Playing Media</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/smartphone-tools-for-perfecting-your-pronunciation/"><u>Smartphone Tools for Perfecting Your Pronunciation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-minimizing-window-search-imagery/"><u>Tips for Minimizing Window Search Imagery</u></a></li>
</ul></div>

