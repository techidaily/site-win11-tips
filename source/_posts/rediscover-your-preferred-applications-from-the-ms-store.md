---
title: Rediscover Your Preferred Applications From the MS Store
date: 2024-11-26T16:25:12.370Z
updated: 2024-11-27T17:58:54.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rediscover Your Preferred Applications From the MS Store
excerpt: This Article Describes Rediscover Your Preferred Applications From the MS Store
keywords: Find MS Store Games,Explore MS Apps,Rediscover MS Apps,MS Store Updates,Revive Old MS Apps,Revisit MS Store Favorites,Uncover New MS Apps
thumbnail: https://thmb.techidaily.com/78fc2ce8486dc3d6564f3f5f4f837891a8fa189d01a8b699d519ecb10291bd82.jpg
---

## Rediscover Your Preferred Applications From the MS Store

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-how-to-make-a-photo-video-with-pixiz/"><u>[Updated] 2024 Approved How to Make a Photo Video with Pixiz?</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-leading-lights-in-the-land-of-vr-entertainment/"><u>[Updated] Leading Lights in the Land of VR Entertainment</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-turning-your-youtube-views-into-a-screen-capture-made-simple-and-free/"><u>[Updated] Turning Your YouTube Views Into a Screen Capture Made Simple and Free</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensive-guide-to-crafting-memes-on-9gag/"><u>A Comprehensive Guide to Crafting Memes on 9GAG</u></a></li>
<li><a href="https://blog-min.techidaily.com/encode-your-videos-with-av1-using-handbrake-step-by-step-tutorial/"><u>Encode Your Videos with AV1 Using HandBrake - Step-by-Step Tutorial</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-motorola-moto-g13-phone-by-drfone-android/"><u>How to Reset a Locked Motorola Moto G13 Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/linguistica-comparativa-50-palabras-inglesas-espanolas/"><u>Lingüística Comparativa: 50 Palabras Inglesas-Españolas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-the-load-strategies-to-reduce-ums-impact-on-your-system/"><u>Lowering the Load: Strategies to Reduce UMS Impact on Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-visuals-adjust-win11-scaling/"><u>Maximize Visuals: Adjust Win11 Scaling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-vintage-boot-settings-on-windows/"><u>Restoring Vintage BOOT Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-crashing-beast-flawless-fullscreen-in-windows-11s-sonic-games/"><u>Taming The Crashing Beast: Flawless Fullscreen in Windows 11'S Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80041015-in-ms-office-for-windows-users/"><u>Unlocking Error 0X80041015 in MS Office for Windows Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-the-potential-of-gopro-hero5-in-time-lapse-cinematography-for-2024/"><u>Unlocking the Potential of GoPro Hero5 in Time-Lapse Cinematography for 2024</u></a></li>
</ul></div>

