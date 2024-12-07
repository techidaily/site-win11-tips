---
title: Detailed Guide to Fixing WinError 0X80071a90
date: 2024-11-30T23:48:17.734Z
updated: 2024-12-06T21:50:57.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Detailed Guide to Fixing WinError 0X80071a90
excerpt: This Article Describes Detailed Guide to Fixing WinError 0X80071a90
keywords: Error Code 0X80071a90 Solution,WinError Repair Methods,Resolve Windows Error 7190,Troubleshoot 0X80071A90 Issue,Fixing 0X80071A90 Error Guide,System Error 0X80071A90 Fixes,WinError 0X80071a90 Correction Steps
thumbnail: https://thmb.techidaily.com/abed13984f00a4dafd781b81f7c6f09556b0fa71bac5479c9b32307596f6cf87.jpg
---

## Detailed Guide to Fixing WinError 0X80071a90

 The Windows Features error 0x80071A90 occurs when the users try to install or enable a features component such as .NET Framework but the process fails. This typically happens when there is an issue within the Windows component store which maintains the system components.

 Below, we take a look at why this error occurs, and the solutions to try to resolve it for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Factors That Might Be Contributing to the 0x80071A90 Error

 While there are several factors that might be contributing to the Windows Features error, here are the most common ones:

* **Antivirus interruption** : If you are using a third-party security program on your computer, there is a chance that it is blocking the installation or enablement of Windows features by detecting them as potentially harmful or unwanted. This is often a false security alarm.
* **Third-party software conflicts** : Sometimes, a third-party program running in the background can interfere with the installation or enablement of Windows features, leading to the error code 0x80071A90.
* **Corrupted system files** : If the system files that are critical for the installation or enablement of Windows features are missing or corrupted, you are likely to run into the error under consideration.
* **Outdated incomplete Windows updates** : Your system might be outdated, which is resulting in compatibility issues and preventing you from installing/enabling certain Windows features.
* **Other hardware or software issues** : In some cases, hardware or software issues like problems with the device drivers or registry settings can also lead to the Windows Features error.

 Regardless of what might be causing the problem in your case, the troubleshooting methods we have listed above should help you fix it in no time. Proceed with the method that fits your situation the best.

## 1\. Disable Your Antivirus

 Antivirus programs are designed to protect your computer from harmful software and viruses but in doing so, they may also prevent some legitimate Windows components and features from installing or updating properly. This typically happens when the antivirus falsely considers the feature to be harmful.

 Some programs can also interfere with the Windows component store or the update process, leading to the problem.

 This is why, we recommend getting started with disabling your antivirus program temporarily. The exact steps of doing so may differ, depending upon the security program you are using. However, typically, you can achieve this by right-clicking on the antivirus icon in the taskbar and choosing**Disable until the computer is restarted** .

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Once the security program is disabled, try enabling the targeted Windows feature again and check if the problem is now fixed. If the antivirus program happens to be the culprit, you can consider switching to a better alternative.

## 2\. Perform the Action in Safe Mode

 As we mentioned earlier, certain applications and processes running in the background can also interfere with the installation or enablement of Windows features. To prevent any potential third-party software conflicts, you can try performing the action in Safe Mode.

 This mode launches Windows with only the necessary drivers and services, allowing you to finish tasks without interference from third-party software.

 Once you[boot into Safe Mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) , launch the Windows Features utility and try performing the action that was initially triggering the error. If a background process was leading to it, you should be able to enable the targeted feature without any problems now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Rebuild the WMI Repository

 You might also be facing the problem due to a corrupted WMI Repository.

 This repository is like a database where your system stores information about hardware, software, and other related settings. This information can be used by software programs and administrative scripts to manage the system settings and if the repository has corrupt or missing files, it can lead to issues like Windows Features error.

 To fix issues with the WMI repository, you can rebuild it, which will essentially check the repository for any inconsistencies and reset it to its default state. This can help fix any issues that were preventing the installation or enablement of Windows features.

Follow these steps to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press**Ctrl** +**Shift** +**Enter** keys together. This will launch Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt, execute the following commands one by one:  
`winmgmt /salvagerepositorywinmgmt /verifyrepositorywinmgmt /resetrepository`
5. Wait for the commands to execute and then exit Command Prompt. You can now check if the issue is resolved.

## 4\. Try Some Generic Windows-Based Fixes for Errors

 If nothing else works, these general WIndows fixes can help you fix the issue:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Update Windows

![install windows 11 feature update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-windows-11-feature-update.jpg)

 If you haven’t installed the latest Windows updates in a while, then you might be facing the problem due to an outdated system. This can be due to a compatibility issue or because your system lacks updates/hotfixes that were released by Microsoft to address specific issues related to Windows features.

 In this case, we recommend taking your time to[install any pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) available. This will ensure that the drivers and software are compatible with the latest version of Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Check the System for Corruption Errors

![Run SFC scan in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/sfc-scan-1-1.jpg)

 In order to install or enable Windows features, the system relies on critical files and the Windows component store. If any of these files or the store becomes corrupted, it can impede the system's access to the necessary components for feature installation or enablement, leading to errors like the one at hand.

 To fix such corruption errors, you can use a tool like the System File Checker (SFC) to scan and repair system files or the Deployment Image Servicing and Management (DISM) tool to repair the Windows component store. You can run both these utilities via Command Prompt.

 Follow the correct steps for running SFC and DISM in Windows in our guide on[how to fix file system errors on Windows](https://www.makeuseof.com/fix-file-system-errors-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Enable Your Windows Features Again

 The Windows Features error 0x80071A90 is a frustrating problem that can prevent you from installing/enabling certain Windows features. Fortunately, there are several troubleshooting methods that can help you fix it for good.

 To prevent any such issues from occurring in the future, we highly recommend keeping your Windows up-to-date at all times. Additionally, make sure you use a reputable antivirus and avoid unsafe third-party programs that can interfere with the system processes.

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
<li><a href="https://hardware-help.techidaily.com/comprehensive-guide-for-rectifying-realtek-rtl8723be-driver-malfunctions/"><u>Comprehensive Guide for Rectifying Realtek RTL8723BE Driver Malfunctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-proper-installation-of-windows-11/"><u>Ensuring Proper Installation of Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/high-octane-comparison-gopro-hero-4-vs-drift-ghost-s-for-2024/"><u>High Octane Comparison GoPro Hero 4 Vs. Drift Ghost-S for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-identify-and-eliminate-null-space-on-your-pc-drive/"><u>How to Quickly Identify & Eliminate Null Space on Your PC Drive</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-navigating-social-surveys-instagram-stories-edition/"><u>In 2024, Navigating Social Surveys Instagram Stories Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-meizu-21-pro-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Meizu 21 Pro Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/landmarks-of-virtual-reality-showcases-for-2024/"><u>Landmarks of Virtual Reality Showcases for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-handle-windows-update-error-0x800f0845/"><u>Steps to Handle Windows Update Error: 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-errors-during-win10win11-remote-access-attempts/"><u>Tackling Errors During Win10/Win11 Remote Access Attempts</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/tapez-vous-vos-videos-mp4-un-guide-etape-par-etape-pour-la-recuperation-de-fichiers/"><u>Tapez-Vous Vos Vidéos MP4 : Un Guide Étape Par Étape Pour La Récupération De Fichiers</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-modern-wifi-technologies-detailed-overview-of-80211ax-80211ac-and-beyond/"><u>Understanding Modern WiFi Technologies: Detailed Overview of 802.11Ax, 802.11Ac and Beyond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-a-guide-to-5-effective-window-folder-habits/"><u>Unleash Potential: A Guide to 5 Effective Window Folder Habits</u></a></li>
</ul></div>

