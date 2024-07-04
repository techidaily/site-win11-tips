---
title: "Optimizing User Authentication: Windows 11, Domains"
date: 2024-06-25T17:10:55.699Z
updated: 2024-06-26T17:10:55.699Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
excerpt: "This Article Describes Optimizing User Authentication: Windows 11, Domains"
keywords: Win11 Auth Optimize,Domain Authentication,Secure Login Windows,Access Control Windows 11,Identity Verification PC,User Credentials Management,Security Windows Protocols
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Optimizing User Authentication: Windows 11, Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/speeding-up-battlenet-game-transfers-on-win-pc/"><u>Speeding Up Battle.net Game Transfers on Win-PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieving-lost-actions-from-winrunhist/"><u>Retrieving Lost Actions From WinRunHist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/suspending-windows-update-activations/"><u>Suspending Windows Update Activations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-annoyance-of-a-never-ending-update-loop/"><u>Avoid the Annoyance of a Never-Ending Update Loop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-bypassing-ssi-and-installing-unverified-drivers/"><u>Mastering Windows: Bypassing SSI & Installing Unverified Drivers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-secure-your-privacy-with-easy-to-follow-picscanner-methods-for-2024/"><u>[New] Secure Your Privacy with Easy-to-Follow PicScanner Methods for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/advanced-screen-recording-methods-on-dell-laptops/"><u>Advanced Screen Recording Methods on Dell Laptops</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-asus-rog-phone-7-ultimate-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Asus ROG Phone 7 Ultimate Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-forgotten-tiktok-reload-a-quick-fix-in-2024/"><u>[Updated] Forgotten TikTok Reload  A Quick Fix, In 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-quick-youtube-revenue-assessments-available/"><u>In 2024, Quick YouTube Revenue Assessments Available</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-thriving-in-the-youtube-landscape-with-data-driven-approach/"><u>In 2024, Thriving in the YouTube Landscape with Data-Driven Approach</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/epiccollab-unify-instagram-videos-on-devices-for-2024/"><u>EpicCollab  Unify Instagram Videos on Devices for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-capitalizing-on-hairstyle-demonstrations/"><u>[New] In 2024, Capitalizing on Hairstyle Demonstrations</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>