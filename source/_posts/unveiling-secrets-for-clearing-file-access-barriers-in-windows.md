---
title: Unveiling Secrets for Clearing File Access Barriers in Windows
date: 2024-12-02T01:15:26.440Z
updated: 2024-12-07T01:35:14.910Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling Secrets for Clearing File Access Barriers in Windows
excerpt: This Article Describes Unveiling Secrets for Clearing File Access Barriers in Windows
keywords: Windows File Access Guide,Unblocking Files Windows,Clear File Permissions Wins,Remove Access Errors Windows,Enhance File Permissions Win,Overcoming File Barriers Win,Fix Windows File Locks Quickly
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
---

## Unveiling Secrets for Clearing File Access Barriers in Windows

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-mastering-tiktokenas-a-game-changer-top-30-unique-username-suggestions/"><u>[Updated] In 2024, Mastering TikTok'enas a Game Changer Top 30 Unique Username Suggestions</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-parody-playground-top-10-laugh-out-loud-songs-for-2024/"><u>[Updated] Parody Playground Top 10 Laugh-Out-Loud Songs for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-revolutionizing-video-revenue-a-conducive-guide-to-youtube-profits/"><u>[Updated] Revolutionizing Video Revenue A Conducive Guide to Youtube Profits</u></a></li>
<li><a href="https://techtrends.techidaily.com/aprende-el-oficio-con-winxvideo-ai-una-guia-completa-para-mejorar-grabar-editar-comprimir-y-convertir-videos-perfectamente/"><u>Aprende El Oficio Con Winxvideo AI: Una Guía Completa Para Mejorar, Grabar, Editar, Comprimir Y Convertir Vídeos Perfectamente</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-effective-strategy-for-eradicating-windows-mail-error-0x800713f/"><u>Crafting an Effective Strategy for Eradicating Windows Mail Error 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-m365-error-code-30015-26-on-windows/"><u>Deciphering and Solving M365 Error Code 30015-26 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fortifying-internal-builds-against-breaches/"><u>Fortifying Internal Builds Against Breaches</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-unboxing-and-testing-the-27000mah-chargetech-portable-power-station/"><u>In-Depth Analysis: Unboxing and Testing the 27000mAh ChargeTech Portable Power Station</u></a></li>
<li><a href="https://tech-revival.techidaily.com/los-mejores-grabadores-de-pantalla-para-computadoras-windows-capturando-la-totalidad-en-versiones-10-8-o-7/"><u>Los Mejores Grabadores De Pantalla Para Computadoras Windows: Capturando La Totalidad en Versiones 10, 8 O 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-11-strategies-for-resolving-win11-bluescreen-issues/"><u>Mastering 11 Strategies for Resolving Win11 Bluescreen Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/tips-of-transferring-messages-from-realme-narzo-n55-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Tips of Transferring Messages from Realme Narzo N55 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-the-power-to-repair-predominant-windows-rainmeter-issues/"><u>Unleashing the Power to Repair Predominant Windows Rainmeter Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficiency-shortcuts-for-windows-11s-microphone/"><u>Unlocking Efficiency: Shortcuts for Windows 11'S Microphone</u></a></li>
</ul></div>

