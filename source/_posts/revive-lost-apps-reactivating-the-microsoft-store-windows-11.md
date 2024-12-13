---
title: "Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
date: 2024-12-09T00:00:02.064Z
updated: 2024-12-12T17:22:16.662Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
excerpt: "This Article Describes Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)"
keywords: WinStore Revive Guide,Windows Reinstalls,Activate Windows Store,MS Store Restore,Reactivate Apps Windows,Microsoft Store Reset,Lost Apps Fix Windows 11
thumbnail: https://thmb.techidaily.com/b926e430c3910450366f0c5eac6f2faf425580bfe11541a9628c11209d7640f5.jpg
---

## Revive Lost Apps: Reactivating the Microsoft Store (Windows 11)

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-the-complete-laptop-and-mobile-manual-for-old-fb-stories/"><u>[New] In 2024, The Complete Laptop & Mobile Manual for Old FB Stories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-extensive-analysis-djis-latest-uav-inspire-1/"><u>[Updated] Extensive Analysis DJI's Latest UAV, Inspire 1</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-how-does-youtube-pay-you/"><u>2024 Approved How Does YouTube Pay You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cambia-gratis-i-file-aiff-in-formato-m4r-online-con-convertitore-audiovideo-movavi/"><u>Cambia Gratis I File AIFF in Formato M4R Online Con Convertitore Audiovideo - Movavi</u></a></li>
<li><a href="https://solve-hot.techidaily.com/easy-tutorial-on-transforming-tivo-files-into-high-quality-mp4-videos/"><u>Easy Tutorial on Transforming TiVo Files Into High-Quality MP4 Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/essential-guide-connecting-your-mac-and-television-with-airplay/"><u>Essential Guide: Connecting Your Mac and Television with AirPlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-tga-images-into-bmp-format/"><u>Free Online Converter: Transforming TGA Images Into BMP Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-moegenoefening-livestreamen-met-jeldende-videoprogramma-movavi/"><u>Gratis Moegenoefening Livestreamen Met Jeldende Videoprogramma - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuit-swf-filament-naar-format-m4v-omzetten-leergids-van-movavi-online/"><u>Gratuit SWF-Filament Naar Format M4V Omzetten: Leergids Van Movavi Online</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-enhance-your-music-library-top-6-free-ios-apps-for-audio-conversion/"><u>In 2024, Enhance Your Music Library Top 6 Free iOS Apps for Audio Conversion</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-v30-lite-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo V30 Lite 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/komt-een-kostenlose-conversie-aan-ogg-adres-met-movavi-voor-online-activiteiten-afvallend-au-inlevering-gratis/"><u>Komt Een Kostenlose Conversie Aan: OGG-Adres Met Movavi Voor Online Activiteiten, Afvallend .au - Inlevering Gratis</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/premier-pro-expertise-for-sound-switchers-for-2024/"><u>Premier Pro Expertise for Sound Switchers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-video-conversion-free-webm-and-mkv-transformers-at-movavis-digital-library/"><u>Streamline Video Conversion: Free Webm and MKV Transformers at Movavi's Digital Library</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-top-9-replacement-editing-software-for-windows-users-seeking-an-alternative-to-final-cut-pro/"><u>The Top 9 Replacement Editing Software for Windows Users Seeking an Alternative to Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformez-votre-contenu-video-mkv-en-audio-mp3-sur-internet-gratuitement-techniques-de-convertisseur-video/"><u>Transformez Votre Contenu Vidéo MKV en Audio MP3 Sur Internet Gratuitement - Techniques De Convertisseur Vidéo</u></a></li>
</ul></div>

