---
title: Overcoming the Stuck GPSVC Hang in Windows
date: 2024-12-08T18:42:42.118Z
updated: 2024-12-13T01:08:11.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Stuck GPSVC Hang in Windows
excerpt: This Article Describes Overcoming the Stuck GPSVC Hang in Windows
keywords: Fixing Windows GPSVC Freeze,Resolve Windows GPSVC Error,Unfreeze GPSVC in Win,Stop GPSVC Hang on PC,Windows GPSVC Stuck Fix,Eliminate GPSVC Hang Windows,Clearing GPSVC Glitches
thumbnail: https://thmb.techidaily.com/7e858d7102e5ef6f6137f0acdeeba112d7b0daf0c9e0dad5ba4b3979a33bb860.jpg
---

## Overcoming the Stuck GPSVC Hang in Windows

 The "Please wait for the GPSVC" loop in Windows is a frustrating issue that can cause the system to get stuck upon a shutdown attempt. This loop is related to the Group Policy Client Service (GPSVC).

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.

## What Does “Please Wait for the GPSVC” Mean?

 The "Please wait for the GPSVC" statement occurs while the system is waiting for the Group Policy Client Service (GPSVC) to complete certain active processes. This service works by managing and applying the group policies in your Windows system.

 The time this service takes to complete the process can depend upon factors such as the complexity of the Group Policy settings, network connectivity, and the performance of the system. While it is generally recommended to avoid interrupting the process till it completes, there are times when this loop can take forever to end.

 This normally happens due to one or more of the following reasons:

* **Group Policy errors**: The Group Policy settings in your computer may have been corrupted, which is preventing the GPSVC process from completing successfully.
* **Third-party software conflicts**: A third-party software or services might be conflicting with the GPSVC process, causing it to get stuck in a loop.
* **System file corruption**: If the essential system files on which the Group Policy or the GPSVC processes depend become corrupted or damaged, it can lead to the system getting stuck in loops, improper shutdowns, disk errors, or malware infections.
* **Malware or viruses**: Malware can also interrupt system processes deliberately. The malware or virus in your system might be attempting to gain control over your system by interfering with GPE.

 It is essential to note that the exact cause of this loop can vary, depending upon different circumstances. However, regardless of what the cause might be, the troubleshooting methods we have listed below are sure to help you fix the issue for good.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Setting Up Your PC for Troubleshooting

 To start the troubleshooting, you must be able to access your system. This can be done in two ways; you can either [perform a Windows reboot](https://www.makeuseof.com/windows-restart-methods/) to break the loop using the Ctrl + Alt + Delete menu or enter the Safe Mode.

 If you have tried rebooting but the error pops up again, you can boot into the Safe Mode through Windows Recovery Environment.

 This will launch the system with a set of only the necessary drivers and services. Once you are in Safe Mode, you can take further steps to diagnose the issue and fix it.

 Here is how you can do that:

1. Shut down your computer and use the power button to restart.
2. When the computer is loading, use the power button to force shutdown again. You can do this by pressing and holding the power button).
3. Repeat this twice and on the third attempt, Windows will boot into the Recovery Environment automatically.
4. Choose **Troubleshoot** \> **Advanced options**.  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
5. Click on **Startup settings** and select **Restart**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Wait for the computer to restart and then press the 4, 5, or 6 keys to boot into Safe Mode.

 Once you are in Safe Mode, proceed with the solutions we have listed below.

## 1\. Restart the Group Policy Client Service

 The GPSVC service itself might be dealing with a temporary glitch or a corruption error that is causing it to malfunction. The easiest way to fix issues with the service is by restarting it.

 Here is how you can do that:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "services.msc" in Run and click **Enter**.
3. In the following window, look for the Group Policy Client service and right-click on it.
4. Choose **Properties** from the context menu.  
![Access the Group Policy Client properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-client-properties.jpg)
5. Now, click on the **Stop** button, wait for a few seconds, and click **Start**.
6. Expand the dropdown for Startup type and choose **Automatic**.
7. Click **Apply** \> **OK** to save the changes.

 You can now exit the Services window and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Reset the Local Group Policy Settings

![Reset Group Policy using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Reset-Group-Policy-using-Command-Prompt.jpg)

 As we mentioned earlier, there can be an issue with the Local Group Policy settings. To check if this is the case in your situation, you can reset the Local Group Policy settings. This will restore the configurations to the default state, eliminating any potential conflicts that may have caused the issue.

 However, before you proceed, it is important to note that this will also remove any customizations or modifications you made via GPE.

 If that is not a problem, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "cmd" in Run and press **Ctrl** \+ **Shift** \+ **Enter** keys together.
3. Choose **Yes** in the User Account Control prompt.
4. In Command Prompt, execute the command below:  
`RD /S /Q "%WinDir%\System32\GroupPolicyUsers" && RD /S /Q "%WinDir%\System32\GroupPolicy"`
5. Once the command executes, proceed with the following command:  
`gpupdate.exe /force`
6. Finally, restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Modify the GPSVC Registry File

 There is also a chance that the GPSVC registry keys are missing or corrupt, which is preventing the service from functioning properly. Such issues can be fixed by modifying the relevant values as shown below.

 Before proceeding, we recommend that you [create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe. Once that is done, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below:  
`​​​​​​​​​​​​​​Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Svchost`
5. Right-click on **Svchost** and choose **New** \> **Key**.
6. Name this key as **GPSvcGroup**.
7. Double-click on **GPSvcGroup** and right-click anywhere in the right pane.
8. Choose **New** \> **DWORD (32-bit) Value** and rename this value as **AuthenticationCapabilities**.
9. Double-click on **AuthenticationCapabilities** and select the Base to **Decimal**.
10. Type "12320" in Value data and click **OK**.  
![AuthenticationCapabilities key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/authentican-key.jpg)
11. Now, create another key **CoInitializeSecurityParam** in a similar way.
12. Set its base to **Hexadecimal** and type "1" in Value data.  
![CoInitializeSecurityParam key in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/coinitializesecurityparam-key.jpg)
13. Click **OK** to save the changes and then restart your PC. Hopefully, upon reboot, you will no longer face the error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Apart from these specific fixes, you can also try [performing a system restore](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) or scanning the system [using the built-in SFC and DISM Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/). The former will help revert the system to an older, error-free state, while performing a system scan will help fix any corruption errors in the system that might be contributing to the problem.

## GPSVC Loops on Windows, Fixed

 The "Please Wait for the GPSVC" loop doesn't have to be a permanent problem. Hopefully, the solutions above will help you fix this issue for good. If the problem persists, it is always recommended to seek assistance from technical experts or Microsoft support.

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-ultimate-guide-to-creating-engaging-video-posts/"><u>[New] The Ultimate Guide to Creating Engaging Video Posts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-how-to-use-video-titles-and-youtube-tags-for-more-views/"><u>[Updated] How to Use Video Titles and YouTube Tags for More Views?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-to-mix-unveiling-two-dji-devices-with-20-luts-complimentary/"><u>2024 Approved Free to Mix - Unveiling Two DJI Devices with 20 LUTS Complimentary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-asking-too-many-hands-at-once-issue-on-windows/"><u>Conquering “Asking Too Many Hands at Once” Issue on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demonstrative-instructions-for-successful-implementation-of-law-filters-in-windows/"><u>Demonstrative Instructions for Successful Implementation of LAW Filters in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-footage-to-frame-crafting-youtube-thumbnails-on-mobile-devices-for-2024/"><u>From Footage to Frame Crafting YouTube Thumbnails on Mobile Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-tracking-of-programs-opened-in-windows/"><u>Halt Tracking of Programs Opened in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-honor-x7b-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Honor X7b Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-craft-your-narrative-best-free-mobile-editors-android-focus/"><u>In 2024, Craft Your Narrative Best Free Mobile Editors, Android Focus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-surface-overcoming-the-plugged-in-not-charging-dilemnma-easily/"><u>Microsoft Surface: Overcoming the 'Plugged in, Not Charging' Dilemnma Easily</u></a></li>
<li><a href="https://fix-guide.techidaily.com/nubia-red-magic-8s-proplus-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nubia Red Magic 8S Pro+ Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/purestream-app-audit-report/"><u>PureStream App Audit Report</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-lost-upgrades-in-windows-11-fix-for-missing-tab/"><u>Revive Lost Upgrades in Windows 11 - Fix for Missing Tab</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-guide-efficiently-managing-your-programs-on-windows/"><u>The Quick Guide: Efficiently Managing Your Programs on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-efficiently-removing-steam-dns-information/"><u>Tips for Efficiently Removing Steam DNS Information</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722866197956-top-7-essential-note-taking-applications-for-your-ipad-and-ipad-pro/"><u>Top 7 Essential Note-Taking Applications for Your iPad & iPad Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undercover-window-wiz-windows-11s-hidden-tools-exposed/"><u>Undercover Window Wiz: Windows 11'S Hidden Tools Exposed</u></a></li>
</ul></div>

