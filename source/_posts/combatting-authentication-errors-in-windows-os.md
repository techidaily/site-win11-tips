---
title: Combatting Authentication Errors in Windows OS
date: 2024-12-10T17:29:25.972Z
updated: 2024-12-12T18:48:52.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting Authentication Errors in Windows OS
excerpt: This Article Describes Combatting Authentication Errors in Windows OS
keywords: Fixing Login Failures,AuthError Resolution,Windows Access Issues,Unlocking OS Errors,Secure System Logins,WinOS Authentication Fixes,Troubleshooting Login Errors
thumbnail: https://thmb.techidaily.com/8e45fcad350df735f2b4416d42d7d71c8933e8227de663d1016dd55e7780d59f.jpg
---

## Combatting Authentication Errors in Windows OS

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-embedded-epicness-galaxy-games-chronicle-for-2024/"><u>[New] Embedded Epicness Galaxy Games Chronicle for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-m4r/"><u>線上靈活音樂格式轉換 - Movavi M4R自由版本</u></a></li>
<li><a href="https://win11-tips.techidaily.com/flvvobmovavi/"><u>迅速なFLVとVOB形式変換を提供する、Movaviの強力なオンライン無料プログラム</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/comprehensive-guide-to-diagnose-and-resolve-fat-drive-issues-on-your-windows-10-pc/"><u>Comprehensive Guide to Diagnose and Resolve FAT Drive Issues on Your Windows 10 PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-instructions-to-get-and-install-arduino-nano-drivers-on-windows-machines/"><u>Comprehensive Instructions to Get & Install Arduino Nano Drivers on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-mp3-to-wav-files-free-lossless-audio-conversion-with-movavi/"><u>Convert MP3 to WAV Files Free - Lossless Audio Conversion with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transforming-m1v-files-into-mpg-movavi-guide/"><u>Free Online Converter: Transforming M1V Files Into MPG - Movavi Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratuita-conversion-de-archivos-opus-a-formato-ogg-online-con-movavi/"><u>Gratuita Conversión De Archivos OPUS a Formato OGG Online Con Movavi</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-filming-with-simulated-environments-a-five-point-guide-by-movavi/"><u>Mastering the Art of Filming with Simulated Environments: A Five-Point Guide by Movavi</u></a></li>
<li><a href="https://program-issues.techidaily.com/star-wars-jedi-fallen-order-how-to-fix-non-launching-problems-on-your-device/"><u>Star Wars Jedi: Fallen Order - How to Fix Non-Launching Problems on Your Device</u></a></li>
<li><a href="https://article-files.techidaily.com/step-by-step-for-apple-podcast-integration/"><u>Step-by-Step for Apple Podcast Integration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-tecno-spark-20-pro-by-drfone-android/"><u>Three Ways to Sim Unlock Tecno Spark 20 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-15-innovadoras-tecnicas-para-crear-collage-de-fotografias-con-eficacia-guia-de-movavi/"><u>Top 15 Innovadoras Técnicas Para Crear Collage De Fotografías Con Eficacia - Guía De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-basta-dvd-riparatorer-for-mac-movavi-konverter/"><u>TOP 7 Bästa DVD-Riparatorer För Mac - Movavi Konverter</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-resolving-windows-11s-missing-coprocessor-drivers-easy-fixes-unveiled/"><u>Troubleshooting and Resolving Windows 11'S Missing Coprocessor Drivers: Easy Fixes Unveiled</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-solutions-for-your-ipad-instructions-on-initiating-recovery-mode/"><u>Unlocking Solutions for Your iPad: Instructions on Initiating Recovery Mode</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-world-of-ai-chatbots-why-are-they-preferred-by-users/"><u>Unveiling the World of AI Chatbots: Why Are They Preferred by Users?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mp4-to-mp3movavi/"><u>オンラインで自由にMP4 to MP3変換！Movavi 使ってみる手軽版 -快適なフリーサービス</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    