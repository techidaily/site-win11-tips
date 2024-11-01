---
title: Steps to Eliminate LSA Problems on Windows 10
date: 2024-10-28T17:08:30.778Z
updated: 2024-11-01T18:22:57.346Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Eliminate LSA Problems on Windows 10
excerpt: This Article Describes Steps to Eliminate LSA Problems on Windows 10
keywords: Win10 LSA Fix Guide,LSA Issue Resolution,Eradicate LSA Errors,Windows 10 SysTroubleshoot,Eliminate LSA on W10,LSA Problem Solver W10,Win10 LSA Diagnostics
thumbnail: https://thmb.techidaily.com/5e9bfb6a7e4a347d52ac2274763d8cb00a024229f1f3b2af38f5058bc81f8e98.jpg
---

## Steps to Eliminate LSA Problems on Windows 10

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
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-navigating-digital-earnings-a-side-by-side-comparison/"><u>[New] 2024 Approved Navigating Digital Earnings A Side-by-Side Comparison</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-essential-tips-for-recording-movies-on-all-devices/"><u>[New] Essential Tips for Recording Movies on All Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-strategic-use-of-instagrams-music-emojis-on-posts/"><u>[Updated] 2024 Approved Strategic Use of Instagram’s Music Emojis on Posts</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-erase-unwanted-black-fringes-on-youtube-tracks-for-2024/"><u>[Updated] Erase Unwanted Black Fringes on YouTube Tracks for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-practices-apps-and-sites-mastering-photo-framing/"><u>2024 Approved Best Practices Apps & Sites - Mastering Photo Framing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-executable-format-pe/"><u>Exploring Windows Executable Format (PE)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-make-word-open-email-attachments-in-read-only-by-default/"><u>Guidelines to Make Word Open Email Attachments in Read-Only by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disguise-taskbars-search-in-windows-11/"><u>How To Disguise Taskbar's Search in Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-talent-hunters-unite-top-10-video-roundup/"><u>In 2024, Talent Hunters Unite! Top 10 Video Roundup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-look-for-task-managers-launch-screen-win11/"><u>New Look for Task Manager's Launch Screen (Win11)</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-game-delays-proven-fixes-and-tips-for-a-smooth-pc-experience-in/"><u>Overcoming Game Delays: Proven Fixes and Tips for a Smooth PC Experience In</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-oppo-a78-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Oppo A78 Device</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-youtube-video-titles-creator-tools-for-2024/"><u>Ultimate YouTube Video Titles Creator Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ip-port-inspection-strategies/"><u>Windows IP Port Inspection Strategies</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    