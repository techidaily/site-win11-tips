---
title: "Regaining Control: Reclaiming Microsoft Store on Windows 11"
date: 2024-12-11T19:30:03.517Z
updated: 2024-12-12T19:03:22.398Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regaining Control: Reclaiming Microsoft Store on Windows 11"
excerpt: "This Article Describes Regaining Control: Reclaiming Microsoft Store on Windows 11"
keywords: WinStore Regain Control,Microsoft Store Redemption,W11 Microsoft Reentry,Reviving Windows Shop,Retrieve MS Windows Store,Take Back Windows XPS,Control MS Store on W11
thumbnail: https://thmb.techidaily.com/0a1a7225cf59c67660e5517795e22301d6d92dc2445c6377515e5503eb99dcd0.jpg
---

## Regaining Control: Reclaiming Microsoft Store on Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-unleashing-video-power-the-galaxy-s8-in-4k/"><u>[Updated] 2024 Approved Unleashing Video Power The Galaxy S8 in 4K</u></a></li>
<li><a href="https://win-updates.techidaily.com/windows-7-hdd/"><u>「ディスクイメージとしてのWindows 7 HDD保存手順」</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-window-management-hotkey-based-reworking-mastery/"><u>Conquer Window Management: Hotkey-Based Reworking Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-lack-of-privilege-during-os-setup/"><u>Correcting Lack of Privilege During OS Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-workflow-with-smart-multitasking-tactics-for-windows-11/"><u>Elevate Workflow with Smart Multitasking Tactics for Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-strategies-to-combat-last-epoch-crashing-on-your-pc/"><u>Expert Strategies to Combat 'Last Epoch Crashing' On Your PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726027694141-fm/"><u>FM放送特別番組の聴取記録化手順:易しいガイド</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-htc-u23-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from HTC U23 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-guide-to-saving-real-time-screen-chats/"><u>In 2024, Guide to Saving Real-Time Screen Chats</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-resolution-of-error-0x800700e1-in-windows-11-systems/"><u>Mastering the Resolution of Error 0X800700E1 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-examination-identifying-pcs-graphics-card-makeup/"><u>Rapid Examination: Identifying PC's Graphics Card Makeup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-hidden-additional-monitor-in-windows-11/"><u>Rectifying Hidden Additional Monitor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-chrome-networking-hiccup-in-windows-settings/"><u>Remedy for Chrome Networking Hiccup in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-screen-savers-for-your-win11-pc/"><u>Tailor-Made Screen Savers for Your Win11 PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-xiaomi-13-ultra-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Xiaomi 13 Ultra Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-notch-apps-to-refine-your-iphone-and-android-gopro-videos-for-2024/"><u>Top-Notch Apps to Refine Your iPhone & Android GoPro Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/updating-default-document-printer-for-pdfs-in-windows/"><u>Updating Default Document Printer for PDFs in Windows</u></a></li>
</ul></div>

