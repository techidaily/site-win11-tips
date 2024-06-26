---
title: Mastering the Art of Win LSA Troubleshooting
date: 2024-06-25T16:30:24.193Z
updated: 2024-06-26T16:30:24.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Win LSA Troubleshooting
excerpt: This Article Describes Mastering the Art of Win LSA Troubleshooting
keywords: Art of LSA Fixing,LSA Mastery,LSA Techniques,Win LSA Tips,Resolve LSA Issues,LSA Expertise,LSA Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/cc90cfb91ad0a20c12f9d720fc85b3d9e0382268e1d979284c574fcec450998c.jpg
---

## Mastering the Art of Win LSA Troubleshooting

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/steps-for-stabilizing-inconsistent-windows-printers/"><u>Steps for Stabilizing Inconsistent Windows Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-resolving-rdp-errors-in-windows-11/"><u>Essential Tips for Resolving RDP Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-and-disable-the-windows-key/"><u>How to Enable and Disable the Windows Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-windows-spotlight-picture-whenever-you-want/"><u>How to Change the Windows Spotlight Picture Whenever You Want</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-bygone-era-to-future-tech-using-windows-7-key-in-11-setup/"><u>From Bygone Era to Future Tech: Using Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-productivity-the-most-compelling-task-list-software-on-windows-11/"><u>Harnessing Productivity: The Most Compelling Task List Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-loss-of-pin-access-in-windows-11-post-update-fallout/"><u>Fix for Loss of PIN Access in Windows 11 Post-Update Fallout</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-premier-stop-motion-works-the-ultimate-15-selection/"><u>2024 Approved  Premier Stop-Motion Works  The Ultimate 15 Selection</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Realme 11 Pro+? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-plotting-your-path-in-the-realm-of-visual-arts/"><u>[Updated] Plotting Your Path in the Realm of Visual Arts</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-magic-5-lite-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Honor Magic 5 Lite Screen | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-master-mixing-suite-your-perfect-mac-mp3-harmony-tool/"><u>Updated Master Mixing Suite - Your Perfect Mac MP3 Harmony Tool</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-essential-websites-for-optimizing-mp3-audio-volume-the-top-3-list/"><u>New In 2024, Essential Websites for Optimizing MP3 Audio Volume The Top 3 List</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-dive-deep-into-the-world-of-creator-studio/"><u>[New] 2024 Approved  Dive Deep Into the World of Creator Studio</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-mastering-the-art-of-youtube-posts-via-instagram-stories/"><u>[Updated] 2024 Approved  Mastering the Art of YouTube Posts via Instagram Stories</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ajay-the-creative-content-creators-profitable-venture-on-youtube-for-2024/"><u>AJay  The Creative Content Creator's Profitable Venture on YouTube for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>