---
title: Troubleshooting Windows LSA Errors
date: 2025-02-28T01:07:13.460Z
updated: 2025-03-04T16:49:26.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows LSA Errors
excerpt: This Article Describes Troubleshooting Windows LSA Errors
keywords: Windows LSA Fix Guide,Resolve LSA Error,Win LSA Troubleshoot,LSA Issue in Windows,Correcting LSA Failure,Windows Authentication Errors,Fixing LSA Windows Problems
thumbnail: https://thmb.techidaily.com/dccb34317888d85bf5b03242f6ff077822b2720dd93141b57f6f0f2fbe555fd1.jpg
---

## Troubleshooting Windows LSA Errors

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

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

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-the-ultimate-mac-dvd-authorization-handbook/"><u>[New] 2024 Approved The Ultimate Mac DVD Authorization Handbook</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-a-practical-guide-elevating-your-podcast-with-an-iconic-title-for-2024/"><u>[New] A Practical Guide Elevating Your Podcast with an Iconic Title for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-adjust-your-android-images-right-here/"><u>[Updated] In 2024, Adjust Your Android Images Right Here</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-maximize-engagement-discover-the-8-best-timers-for-android-and-iphone-for-2024/"><u>[Updated] Maximize Engagement Discover the 8 Best Timers for Android & iPhone for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-prime-8-converters-seamless-sub-and-srt-transition/"><u>2024 Approved Prime 8 Converters Seamless Sub and SRT Transition</u></a></li>
<li><a href="https://fox-http.techidaily.com/360-degree-cameras-vs-3d-cameras-what-are-the-differences-in-2024/"><u>360 Degree Cameras Vs 3D Cameras What Are the Differences, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-en-ligne-gratuite-convertir-un-mp3-en-fichier-3g2-avec-movavi/"><u>Conversion en Ligne Gratuite: Convertir Un MP3 en Fichier 3G2 Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gratis-online-video-converter-mp4-to-mp3-and-more-easy-mpg-conversions-with-movavi/"><u>Gratis Online Video Converter: MP4 to MP3 & More - Easy MPG Conversions with Movavi</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/incorporating-secondary-footage-a-filmmakers-guide/"><u>Incorporating Secondary Footage A Filmmaker's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/les-5-applications-phares-pour-une-transformation-videoprofessionnelle-superieure-en-2024/"><u>Les 5 Applications Phares Pour Une Transformation Videoprofessionnelle Supérieure en 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-video-editor-suite-comprehensive-features-with-tutti-and-unlimited-plans/"><u>Movavi Video Editor Suite: Comprehensive Features with Tutti and Unlimited Plans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-archivos-webm-gratuitamente-en-gif-utilizando-servicios-en-linea-como-movavi/"><u>Transforma Archivos WebM Gratuitamente en GIF Utilizando Servicios en Línea Como Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vtuber202-cups-15-x-7-plus-134x-plus-8/"><u>VTuber之路上的秘密诀窍：如何在202 Cups = (1/5) X -7 + (1/3)(4X + 8)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-best-video-editing-tools-a-comprehensive-guide-to-top-picks/"><u>Windows 11'S Best Video Editing Tools: A Comprehensive Guide to Top Picks</u></a></li>
</ul></div>

