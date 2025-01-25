---
title: Can't Set an Account as Administrator on Windows? Here's the Fix
date: 2025-01-19T18:59:56.970Z
updated: 2025-01-25T00:06:50.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Can't Set an Account as Administrator on Windows? Here's the Fix
excerpt: This Article Describes Can't Set an Account as Administrator on Windows? Here's the Fix
keywords: Admin Access Issue,Change User Type,Windows Admin Settings,Unlock Admin Pw,Regedit for Admin,PowerShell Adm Priv,Gain Admin Rights Fix
thumbnail: https://thmb.techidaily.com/dadc574a72620fb10d26a05d18b7bc541d4008da38e3f5b8b4a33a2f717ba587.jpg
---

## Can't Set an Account as Administrator on Windows? Here's the Fix

 Administrator accounts offer extensive control over the system, granting the ability to manage settings, install software, and access critical system files. However, occasionally, users may encounter issues when attempting to switch from their standard user account to an admin account.

 Below, we explore various effective fixes to resolve this problem permanently.

## 1\. Modify the User Account Control (UAC) Settings

 User Account Control (UAC) is a security feature that prevents users from making unauthorized changes to the computer. It typically appears as a dialog box, prompting you to confirm the action by clicking the "Yes" or "No" option.

 In the case of this specific error, you might be facing the issue because of misconfigured or incorrect UAC settings. Here is how you can ensure UAC is enabled and set to a suitable level:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "control" in the text field and click **Enter**.
3. In the following window, navigate to **System and Security** \> **Security and Maintenance**.
4. Choose **Change User Account Control settings**.
5. In the dialog that appears, move the slider to the desired level (recommended: notify only when apps try to make changes to your computer) and click **OK** to save the changes.  
![The User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-uac-settings.jpg)

 Once done, close the Command Prompt and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Activate the Built-In Administrator Account

![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-built-in-admin-account.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Windows comes with a hidden administrator account that can allow you to have full control over the system. This account is typically disabled by default for security reasons but if you are having trouble switching to an administrator account, enabling the built-in Administrator account can be beneficial.

 Here's how to activate the built-in Administrator account:

1. Press the **Win** \+ **R** keys to open Run.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
3. Click **Yes** in the following dialog.
4. Once you are in the Command Prompt, type the command below and hit **Enter** to execute it:  
net user administrator /active:yes
5. After the command executes successfully, you should see a message in Command Prompt confirming it. If you want to set a password for this administrator account, execute the following command:  
​​​​​​​net user administrator *
6. Follow the prompts to set a new password.

 Alternatively, you can also use the Local Users and Groups management console to make these changes. Here is how you can do that:

1. Open Run by pressing **Win** \+ **R** keys together.
2. Type "lusrmgr.msc" in Run and click **Enter**.
3. In the left pane, expand **Users** and right-click on **Administrator**.
4. Choose **Properties** from the context menu.
5. Uncheck the **Account is disabled** option and click **OK**.  
![Enable the built-in admin account in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-admin-account.jpg)

 This should successfully activate the built-in administrator account. You can now access the Settings app again and check if you can switch the account type easily now.

## 3\. Make the Changes in Safe Mode

 It's possible that a background process or application is causing interference with system processes, which could be preventing you from switching to an administrator account.

 To determine if this is the cause of the issue, you can [boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/). Safe Mode launches the system with minimal drivers and programs, disabling any background processes that may be contributing to the problem. In this diagnostic state, you should be able to switch to the administrator account if such processes were previously causing the obstruction.

 Once you have booted into Safe Mode, try performing the action that was initially causing the problem. If it does not occur in Safe Mode, you can try eliminating the culprit by either uninstalling it manually or [using the System Restore utility](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) to revert to a stable, error-free state.

## 4\. Disable Your Antivirus Program

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you are using a third-party security program on your computer, it might be preventing you from switching to an admin account because of security reasons.

 In this case, you can try to temporarily disable your security program and see if that helps you switch to an administrator account. You can do this by right-clicking on your antivirus icon in the taskbar and choosing the **Shields Control** \> **Disable until the computer is restarted** option.

 If this works, you can consider [switching to a better security program for your Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) to prevent issues like this from occurring in the future.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Create a New Administrator Account

## Finally, if none of the methods above have helped you, you can try creating a new administrator account in Windows

 This will help with any corruption issues in the current account, as well as help you determine if the permission-related problems were user-specific. It is, however, important to note that you will require admin access to the system to proceed with the steps in this method, so you must enable the built-in administrator account beforehand.

 Once that is done, here is how you can proceed:

1. Open the Settings app by pressing the **Win** \+ **I** keys together.
2. Choose **Accounts** from the left pane and click on **Other users**.
3. Hit the **Add account** button for **Add other users** in the following window.  
![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)
4. Select **I don’t have this person’s sign-in information** \> **Add a user without a Microsoft account**.
5. In the next dialog, enter details like the username and password for the new account.
6. Click **Next**.
7. Once the account is created, click on the **Change account type** button associated with the newly created account.  
![The Change account type button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-change-account-type-option.jpg)
8. Expand the Account type dropdown and choose **Administrator** from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Click **OK** to save the changes.

 You can now log into the new administrator account and begin using it.

## Enjoy Administrative Access to Your Windows System

 The inability to change an account type to Administrator in Windows can be caused by a number of reasons, such as misconfigured User Account Control (UAC) settings or underlying system issues. However, with the right troubleshooting methods, you can overcome the account type change challenge and enjoy administrative access to the system.

 Below, we explore various effective fixes to resolve this problem permanently.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-expert-tips-for-seamless-instagram-streaming-using-obs/"><u>[Updated] 2024 Approved Expert Tips for Seamless Instagram Streaming Using OBS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-much-money-can-you-make-via-youtube-ad-revenue-and-cpm-rates/"><u>[Updated] 2024 Approved How Much Money Can You Make via YouTube Ad Revenue and CPM Rates?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-inside-the-drone-an-in-depth-review-of-dji-phantom-3-pro-for-2024/"><u>[Updated] Inside the Drone An In-Depth Review of DJI Phantom 3 Pro for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-chill-bites-analysis-in-depth-review-of-ice-cream-recorder/"><u>2024 Approved Chill Bites Analysis In-Depth Review of Ice Cream Recorder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dont-skip-the-savings-commit-to-regular-windows-backup/"><u>Don't Skip the Savings: Commit to Regular Windows Backup</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevating-visual-fidelity-introduction-to-4k/"><u>Elevating Visual Fidelity: Introduction to 4K</u></a></li>
<li><a href="https://howto.techidaily.com/hands-on-with-the-apple-iphone-15-pro/"><u>Hands-On With the Apple iPhone 15 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-other-application-uses-from-disrupting-sound/"><u>How to Stop 'Other Application Uses' From Disrupting Sound</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-update-bios-in-windows-11/"><u>How to Update BIOS in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722962199836-how-to-update-your-asus-dvd-drives-with-official-drivers-free-downloads/"><u>How to Update Your ASUS DVD Drives with Official Drivers - FREE Downloads!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructive-path-to-setup-windows-for-in-hand-typing/"><u>Instructive Path to Setup Windows for In-Hand Typing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inactive-outlook-delivery-reports-on-desktop/"><u>Overcoming Inactive Outlook Delivery Reports on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-windows-queries-using-everythingapp/"><u>Quick Windows Queries: Using EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-opengl-error-code-3-on-windows-and-nvidia-gpus/"><u>Remedy for OpenGL Error Code 3 on Windows & Nvidia GPUs</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-y100-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Vivo Y100</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-artificial-intelligence-applications-for-enhancing-content-creation-efficiency/"><u>Top 8 Artificial Intelligence Applications for Enhancing Content Creation Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-the-upcoming-expiry-message-on-w10-and-w11/"><u>Troubleshooting the “Upcoming Expiry” Message on W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-windows-fixes-for-unresponsive-keyboard-shortcuts-and-combinations/"><u>Unlock the Power of Windows: Fixes for Unresponsive Keyboard Shortcuts and Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-high-resolution-quests-expert-techniques-for-playing-classics-in-hd-on-windows/"><u>Winning at High-Resolution Quests: Expert Techniques for Playing Classics in HD on Windows</u></a></li>
</ul></div>

