---
title: Guide to Reinstating Missing PIN After Win 11 Updates
date: 2024-07-12T17:14:59.566Z
updated: 2024-07-13T17:14:59.566Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Reinstating Missing PIN After Win 11 Updates
excerpt: This Article Describes Guide to Reinstating Missing PIN After Win 11 Updates
keywords: Win 11 PIN Recovery Guide,Restore Lost Windows PIN,Update Fix,Reinstate Missing PIN Win 11,Win 11 Password Reset Steps,Correcting PIN Error Post-Update,Regain Access
thumbnail: https://thmb.techidaily.com/fea69578f265b77158961ce9649233eee0ace50ab1ad8d0ca655a5decd1786bf.jpg
---

## Guide to Reinstating Missing PIN After Win 11 Updates

 On Windows 10 and 11, you can log in with a password or PIN. On compatible systems, you can also use iris scan and fingerprint unlock. While a PIN makes the login process faster than a password, you may encounter the Something happened and your PIN isn't available error when trying to sign in using the same.

 Similarly, something went wrong and your PIN isn't available (status: 0xc000006d) is another variation of the error. These errors are often triggered due to a bad security update, issues with the NGC folder, and system file corruption.

 Here are a few troubleshooting steps to help you fix this errorand log in with your PIN successfully on Windows 11.

## 1\. Login With the Account Password

 If you have set up a Microsoft user account or local user account, you can use it to log in with a password. Once done, you can reset the login PIN to fix the problem. Here's how to do it.

 Note that the below steps will not work for Microsoft account if you have enabled the **Only allow Windows Hello sign-in for Microsoft account on this device** option.

1. On the lock screen, press any key to view the**Sign-in** screen.
2. Next, click on**Sign-in options** to view the available options.  
![sign in options windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11.jpg)
3. Click the**Key** icon to select the**password sign-in** option.  
![sign in options windows 11 password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sign-in-options-windows-11-password.jpg)
4. Type in your password and press**Enter** to log in.

 Now that you can log in to your account, follow these steps to change your PIN:

1. Press**Win + I** to open**Settings** .
2. Open the**Account** tab in the left pane.
3. Next, click on the**Sign-in options.**  
![windows 11 sign in options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-1.jpg)
4. Click on**PIN (Windows Hello).**
5. Here, you will see the options to**Change PIN** and**Remove PIN** . To change your PIN, you must know your old PIN. So, we'll proceed with**Remove PIN** to remove the current PIN and then add a new one.
6. So, click on the**Remove** button for**Remove this sign-in option** . Click on**Remove** once more to confirm the action.  
![windows 11 sign in options remove pin confirm](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-remove-pin-confirm-1.jpg)
7. Now you need to verify your admin credentials. So, enter your user account password and click**OK** . Windows will remove your PIN successfully.
8. Next, click on**Set up to add a new PIN** . Enter your user account password to verify the account.  
![windows 11 sign in options add new pin 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-sign-in-options-add-new-pin-1.jpg)
9. In the**Set up a PIN** dialog, type a new PIN for your account. Repeat the same in the**confirm PIN** field and click**OK** .

 If you want, you can also add letters and symbols to your PIN to make it secure. Make sure to select the**Include letters and symbols** option in the**Set up a PIN** dialog and then add your new PIN.

 To test your new PIN, press**Win + L** to lock your screen. Next, enter the new PIN in the login screen to confirm the changes.

## What If I Don't Remember My Account Password?

 If you have forgotten your account password, you can reset it from the sign-in screen by answering the security questions for your account.

To reset your user account password:

1. On the login screen, click on**Sign-in options.**
2. Select the**Password** option. Here, enter anything as your password and press**Enter** . Windows will show the**Password is incorrect** screen. Click**OK** .  
![the password is incorrect](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-password-is-incorrect.jpg)
3. Next, click on the**Reset Password** option. This will open the reset password dialog.  
![reset password lock screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-password-lock-screen.jpg)
4. Next, you need to answer the three security questions and press**Enter** .
5. When successful, Windows will ask you to enter your new password. So, enter your new password and confirm the same. Press enter to save the password.

 Now you can sign in with your new account password. Next, change your PIN following the steps described above.

## 2\. Delete the NGC Folder
![delete ngc folder windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-ngc-folder-windows-11-1.jpg)

 If the issue persists when signing in with a PIN, check the NGC folder for permission issues. The NGC folder is where Windows stores your login information. If the folder is corrupted or lacks sufficient permission, it can result in the Something happened and your PIN isn't available error.

 To fix the corrupted folder, you'll need to delete the folder and let Windows recreate it. Here's how to delete the NGC folder to add a new PIN to your account.

To delete your NGC folder:

1. Make sure you log in with an administrator account.
2. Press**Win + E** to open**File Explorer** .
3. Click on**View > Show** and select**Hidden Items** . Make sure Hidden Item option has a check mark.  
![show hidden item file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/show-hidden-item-file-explorer.jpg)
4. Next, navigate to the following path:  
`C:\Windows\ServiceProfiles\LocalService\AppData\Local\Microsoft`
5. Next, right-click on the**Ngc** folder and select**Delete** . Click on**Delete** again to confirm the action.

 If you see the**You need permission to perform this action** prompt, you'll need to [take the folder ownership on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) to delete the folder. After taking ownership, try to delete the Ngc folder again, and you should be able to fix the error. Once done, you can set up a new PIN from the sign-in options in the Settings app.

## 3\. Uninstall Windows Updates
![advanced options uninstall updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-options-uninstall-updates-3.jpg)

 If you determine the error to have appeared after installing a Windows update, uninstalling the same should help you undo the changes and fix the error.

 There are [many ways to uninstall updates in Windows 10 and 11](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) , including from the Settings app and Windows Recovery Environment. If you are unable to sign in using a password, you can use the Windows Recovery Environment method to uninstall Windows updates.

## 4\. Perform a System Restore Using Restore Point

 Windows creates automatic restore points before a major change is made to your system, including installing an update. You can use the restore point to restore your PC to an earlier time when it was working without an error.

 If you can log in to your PC, follow the instructions to [use a restore point to restore your Windows 11 system](https://www.makeuseof.com/windows-11-create-restore-point/) . If not, here is how to use the system restore point from Windows Recovery Environment.

1. From the sign-in screen, click on the**Power** icon in the bottom left corner.
2. Next, press and hold the**Shift** key and click on**Restart** . Click on**Restart anyway** if a confirmation prompt appears. Make sure to hold the Shift key until the PC starts to restart.  
![choose an option windows recovery environment](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-1.jpg)
3. In the**System Recovery** section, click on**Troubleshoot** .  
![choose an option windows recovery environment advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-advanced-options-1.jpg)
4. Next, select**Advanced options** .
5. Click on**System Restore.**  
![choose an option windows recovery environment advanced options system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/choose-an-option-windows-recovery-environment-advanced-options-system-restore-1.jpg)

1. Next, your system will restart in the**System Restore** environment.  
![system restore windows recovery environment 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/system-restore-windows-recovery-environment-1.jpg)
2. Click on your user account name under**Choose an account to continue.**
3. Next, you'll need to enter the password for the selected account and click**Continue** . If your user account doesn't have a password, then press**Enter** to continue without the password.
4. In the**System Restore** dialog, select the most recent restore point and click**Next** .
5. Follow on-screen instructions to complete the system restore. Your PC will restart with a success or failure message. Once the restore is complete, try to log in with the same PIN to see if the error is resolved.

## 5\. Perform a Startup Repair
![advanced options startup repair](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-options-startup-repair-3.jpg)

 Startup repair is a built-in troubleshooting tool on Windows to fix issues with files required to boot the OS. You can run Startup Repair from the Windows Recovery Environment. Here's how to do it.

1. In the sign-in screen, click on the**Power** icon. Then press and hold the**Shift** key and click on**Restart** . Hold the key until the PC restarts.
2. Next, under**Choose an option,** go to**Troubleshoot > Advanced Options.**
3. Click on**Startup Repair** . Windows will start diagnosing your PC and repair any issues with the startup files.

## 6\. Perform a System Reset
![reset this pc windows 11 recovery](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-this-pc-windows-11-recovery-1.jpg)

 A system reset helps you reset your computer to its factory default removing all the system settings and configuration, including login credentials.

 Windows reset lets you keep or remove your personal files and then reinstall Windows. However, you'll need to reinstall all your third-party apps from scratch.

To perform a system reset:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Recovery** .
3. Under reset**Reset this PC** , click on**Reset PC** .
4. Under **Choose an option, you can choose to keep or remove your files** . Confirm the option to reset your PC.

 If you are unable to sign in, follow this guide to [factory reset Windows 11 without the admin password](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) .

## Restore the PIN Sign-in Functionality on Windows 11

 Windows may refuse to accept your sign-in PIN if the folder containing the information is corrupted or due to system file issues. Before trying any advanced troubleshooting steps, try to use an alternate login method to sign in and remove and change your PIN. If not, you can use system repair to fix startup issues or restore your PC using a restore point.

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
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-installing-java-in-windows-environment/"><u>Solutions for Non-Installing Java in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-drive-space-recognizing-the-leviathans-in-windows-pcs/"><u>Declutter Drive Space: Recognizing the Leviathans in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-transparent-taskbar-creation/"><u>Steps for Windows 11 Transparent Taskbar Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-windows-11-boot-tracks-step-by-step-guide/"><u>Clearing Windows 11 Boot Tracks: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-win10-use-strategies-post-upgrade-decision/"><u>Efficient Win10 Use Strategies Post Upgrade Decision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-directdraw-a-focused-guide-for-win11-enthusiasts/"><u>Troubleshooting DirectDraw: A Focused Guide for Win11 Enthusiasts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-uncover-the-leading-free-online-subtitle-makers-srt/"><u>[New] 2024 Approved  Uncover the Leading Free Online Subtitle Makers (Srt)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-unwanted-scrolling-windows-edition/"><u>Combat Unwanted Scrolling: Windows Edition</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/effortless-android-screenshot-and-screen-record-for-2024/"><u>Effortless Android Screenshot & Screen Record for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-integrated-video-on-windows-1011/"><u>Bypassing Integrated Video on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-win11s-sticky-notes-with-ease/"><u>Conquer Win11's Sticky Notes with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-ms-resource-and-apperror/"><u>Solving Windows 11'S Ms-Resource and AppError</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-bandwidth-visualization-for-users/"><u>Real-Time Bandwidth Visualization for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultra-quick-turn-off-windows-11-dings/"><u>Ultra-Quick Turn Off Windows 11 Dings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-app-usage-a-comprehensive-review/"><u>Window's App Usage: A Comprehensive Review</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-oneplus-ace-3-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset OnePlus Ace 3 without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-oculus-errors-on-ws11wc10-systems/"><u>Troubleshooting Oculus Errors on WS11/WC10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-needs-user-id-login-failures/"><u>Troubleshooting Windows Needs User ID Login Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-updater-error-0xca00a009/"><u>Repairing Windows Updater Error #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-deep-the-ultimate-win11-mouse-properties-guide/"><u>Dive Deep: The Ultimate Win11 Mouse Properties Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-mcuicntexe-non-existent-window-complaint/"><u>Dealing with McUICnt.exe Non-Existent Window Complaint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-app-engagement-in-modern-window-os/"><u>Speedy App Engagement in Modern Window OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-directdraw-faults-on-windows-oses/"><u>Steps to Eliminate DirectDraw Faults on Windows OSes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-launching-an-impactful-instagram-live-session/"><u>[New] Launching an Impactful Instagram Live Session</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-pc-mastering-the-art-of-program-minimization/"><u>Speed Up Your PC: Mastering the Art of Program Minimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-windows-task-scheduler/"><u>Troubleshooting Non-Functional Windows Task Scheduler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-blocked-app-alert-on-windows-systems/"><u>Removing Blocked App Alert on Windows Systems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-swiftly-get-your-favorite-skype-tones-from-here/"><u>In 2024, Swiftly Get Your Favorite Skype Tones From Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-old-school-gaming-adventures-integrate-trophies-through-retroarch/"><u>Revitalize Your Old-School Gaming Adventures - Integrate Trophies Through Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-managing-extraneous-tasks-on-windows/"><u>Efficiently Managing Extraneous Tasks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-ms-defenders-restrictions-for-additional-virus-protection/"><u>Bypassing MS Defender's Restrictions for Additional Virus Protection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-skirting-windows-account-sign-ins/"><u>Avoidance Tactics: Skirting Windows Account Sign-Ins</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-fastest-video-speed-editors-for-windows-and-macos/"><u>New 2024 Approved Fastest Video Speed Editors for Windows and macOS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-hevc-files-on-huawei-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Failed to play HEVC files on Huawei </u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-echoes-of-the-game-unveiling-high-quality-cricket-sounds/"><u>New Echoes of the Game Unveiling High-Quality Cricket Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-clearance-ways-keeping-files-on-win11-safe-max-156-chars/"><u>Drive Clearance Ways: Keeping Files on Win11 Safe (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfettered-functions-embrace-tiny11s-power/"><u>Unfettered Functions: Embrace Tiny11's Power</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-samsung-galaxy-s21-fe-5g-2023-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Samsung Galaxy S21 FE 5G (2023) to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-top-ai-video-makers-to-create-captivating-videos-with-pictures/"><u>New 2024 Approved Top AI Video Makers to Create Captivating Videos with Pictures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stronger-defense-through-longer-passcodes-windows-11-and-11-tips/"><u>Stronger Defense Through Longer Passcodes: Windows 11 and 11 Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-90-lite-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor 90 Lite to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-missing-pages-in-microsoft-store-windows/"><u>Dealing with Missing Pages in Microsoft Store Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-efficient-temperature-management-strategy/"><u>Windows' Efficient Temperature Management Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-navigating-through-collective-media-on-messenger/"><u>[New] Navigating Through Collective Media on Messenger</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-clearing-admin-not-allowed-message-in-os/"><u>Strategies for Clearing Admin Not Allowed Message in OS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-reacting-when-youre-seen-in-a-video-on-fb-messenger/"><u>2024 Approved  Reacting When You're Seen In a Video On FB Messenger</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-worlds-most-famous-tiktokers-a-must-see-list-for-2024/"><u>[New] The World's Most Famous TikTokers  A Must-See List for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-for-text-in-the-windows-snip-tool/"><u>Advanced Techniques for Text in the Windows Snip Tool</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlock-professional-results-with-these-key-pixlr-techniques/"><u>[New] Unlock Professional Results with These Key Pixlr Techniques</u></a></li>
</ul></div>
