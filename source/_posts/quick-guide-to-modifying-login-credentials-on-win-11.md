---
title: Quick Guide to Modifying Login Credentials on Win 11
date: 2024-07-12T17:42:28.367Z
updated: 2024-07-13T17:42:28.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Modifying Login Credentials on Win 11
excerpt: This Article Describes Quick Guide to Modifying Login Credentials on Win 11
keywords: Win 11 Login Change,Windows 11 Password Update,11PC User Settings,Altering Win 11 Logins,Win Credentials Edit,11 PC Security Passwords,Modify Win 11 Accounts
thumbnail: https://thmb.techidaily.com/b46b34fd5ad4244a5b3542fda6e0ba281358e5c36628241992e02c966a06886d.jpg
---

## Quick Guide to Modifying Login Credentials on Win 11

 Despite Microsoft’s attempt to push more users towards adopting the Windows Hello-based sign-in options, the old password-based login is still part of Windows 11\. And for a good reason.

 Even if you prefer a PIN over the conventional password sign-in, you can set an account password as a backup option. It is a handy way to sign in if you forget your PIN or encounter an error. But what if you have forgotten your account password? Let's explore the many ways to change your account password in Windows 11.

## What If You Have Forgotten Your Windows Administrator Password?

 Most Windows computers have more than one sign-in option. So, if your [Windows user account PIN isn’t working](https://www.makeuseof.com/something-happened-your-pin-isnt-available-windows/) , you can use the account password to sign in and vice versa.

 To be able to change your account password, you must either remember your current password or be able to log in to your PC with an alternate sign-in option. If you are locked out of your account without no option to sign in, follow our guide to [reset a forgotten Windows administrator password](https://www.makeuseof.com/tag/3-ways-to-reset-the-forgotten-windows-administrator-password/) instead.

## 1\. Change the Account Password Using Ctrl + Alt + Delete

 Ctrl + Alt + Delete combo is often used if an app causes the PC to become unresponsive and if you want to perform a restart or access Task Manager. However, the combo offers access to other useful tools, including a password change option.

 Follow these steps to quickly change your account password from the Ctrl + Alt + Delete user menu:

1. Press**Ctrl + Alt + Delete** on your keyboard to view the available options.
2. Next, click on**Change** **a password** option.  
![ctrl alt delete change password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/ctrl-alt-delete-change-password.jpg)
3. Next, enter your old account password.
4. Next, you need to provide a new password and confirm the same.  
![ctrl alt delete change password new password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/ctrl-alt-delete-change-password-new-password.jpg)
5. Press**Enter** or click the right arrow icon to change the password.
6. It’s a quick way to change your account password. If this doesn’t work, you can use the Settings app to do the same.

## 2\. Change Your Account Password via the Settings App

 You can easily change your local account password from the Settings app. However, to do this, you must know your current account password. If not, skip to the password reset method below.

To change the account password:

1. Press**Win + I** to open**Settings** .
2. In the left pane, open the**Accounts** tab.  
![change user account password settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/change-user-account-password-settings.jpg)
3. Next, click on**Sign-in options.**
4. Click and expand the**Password** option.
5. Click on**Change** and enter your current password.
6. Click**Next** .  
![change user account password settings new password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/change-user-account-password-settings-new-password.jpg)
7. Next, enter your new password and re-enter the password to confirm the same.
8. You can also add a password hint. If not, leave it blank.
9. Click**Next** and then click on**Finish** to save the changes.

## 3\. Reset Windows User Account Password Using User Accounts (If You Have Forgotten Your Password)

 If you don’t know your current password but can log in using an alternate option, you can reset the password using the User Accounts utility. It allows you to add or remove a user account and reset the password without needing the current password.

 Note that you can only reset the password for a different user account, not your currently logged-in account. Make sure to log in with a different administrator account. If you don't have another account with administrator privilege, you can [enable the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) and reset the user account password.

To reset the user account password:

1. Sign out from the account for which you want to reset the password and log in with a different user account.
2. Next, press**Win + R** to open**Run** .
3. Type**netplwiz** and click**OK** .
4. Select the user account to reset the password in the**User Accounts** dialog.  
![user accounts reset password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-reset-password.jpg)
5. Next, click on the**Reset Password** button.  
![user accounts reset password new password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-reset-password-new-password.jpg)
6. In the**Reset Password** dialog, enter your new password and confirm the same.
7. Click**OK** to save the changes.
8. Close the**User Account** dialog, and you can now log in with your new password.

## 4\. Reset Account Password Using Command Prompt
![reset user account password command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-user-account-password-command-prompt.jpg)

 An easy way to change your account password is via Command Prompt. Again, useful if you want to change your password without knowing the old password.

 To reset the password, you can use the**net user** command followed by the user name and your new password. Follow these steps to change your account password using Command Prompt:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** from the menu. Click**Yes** if prompted by**UAC** .
3. In Windows Terminal, click the drop-down button near the**New Tab** icon and select**Command Prompt.**
4. In the Command Prompt tab, type the following command and press**Enter** to view all the user accounts available on your computer:  
`net user`
5. Next, type the following command and press**Enter** to reset the password for the specified user account:  
`net user username newpassword`

1. In the above command, replace**username** with the account username and**newpassword** with the password you want to set.
2. For example, if you want to reset the password for the**Guest** user account, the complete command will look something like this:  
`net user guest guest@123`
3. Make sure to use a password with a combination of upper- and lower-case letters, numbers, and preferably special characters to create a strong password. You may also want to note it down for the time being.
4. Once the password is reset, you’ll see the**command completed successfully** message in Command Prompt.
5. Type**exit** and press**Enter** to close Command Prompt.

## 5\. Change the Account Password Using the Control Panel

 The classic Control Panel still has most of its system setting functions intact. You can use it in Windows 11 to change your user account password and more.

To change the Windows account password using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** .
3. In Control Panel, go to**User Accounts** and then click on**User Accounts** again.  
![user accounts control panel 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-control-panel-1.jpg)
4. Next, click on**Manage another account.**  
![user accounts control panel manage another account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-control-panel-manage-another-account.jpg)
5. Select the user account for which you want to change the password.
6. Next, click on the**Change the password** option under**Make changes to User’s account.**  
![user accounts control panel change the password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-control-panel-change-the-password.jpg)
7. Type your current password and then enter the new password. Confirm the new password and type in a hint. This will be useful if you forget your password again.  
![user accounts control panel change the password new password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/user-accounts-control-panel-change-the-password-new-password.jpg)
8. Click**Change password** to save the changes.

## 6\. Change Account Password Using Local Users and Groups

 Local Users and Groups snap-in lets you make advanced changes to your user account. You can use it to [set password expiration for Windows user accounts](https://www.makeuseof.com/enable-disable-password-expiration-windows-11/) , add account expiry and restrict users from changing account passwords.

 Additionally, it also allows you to reset your user account password. Follow these steps to change the user account password using lusrmgr.

1. Press**Win + R** to open**Run** .
2. Type**lusrmgr.exe** and click**OK** .
3. In the**Local Users** **and Groups** dialog, select the**Users** folder**.**  
![local users and groups set password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-users-and-groups-set-password.jpg)
4. In the right pane, right-click on a user account and select**Set Password** . This will trigger a password reset warning. Read the description and click**Proceed** .  
![local users and groups set password warning](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-users-and-groups-set-password-warning.jpg)
5. Next, enter your new password and confirm the same in the given field.  
![local users and groups set password new password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-users-and-groups-set-password-new-password.jpg)
6. Click**OK** to reset the password and save the changes.

## How to Change Microsoft Account Password

 If you sign in with a Microsoft account, you can reset the password for the Microsoft account online. Here’s how to do it.

1. Go to the [Microsoft account security page](https://account.microsoft.com/security) and sign in with your username and password.  
![microsoft account online password security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/microsoft-account-online-password-security.jpg)
2. Next, click on the**Password** security block.  
![change my password microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/change-my-password-microsoft-account.jpg)
3. To change the password, fill in your current password. Then, fill in your new password and re-enter the password to confirm.
4. Click**Save** to change the password.

 You can use the new password to sign in to your computer using a Microsoft account.

## Change Windows Account Password in Windows 11

 You can easily change your Windows account password if you remember the current password or have an alternate login option. If you are locked out of your PC, these methods will not work.

 That said, you can still reset your forgotten admin account password using a Command Prompt hack and the Windows Recovery Environment.


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
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://extra-hints.techidaily.com/craft-the-perfect-cinematic-journey-with-imovie-for-2024/"><u>Craft the Perfect Cinematic Journey with iMovie for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-java-development-kit-setup-in-windows-11/"><u>Essential Steps to Java Development Kit Setup in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-daily-digest-downloader/"><u>In 2024, Daily Digest Downloader</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lsassexe-unable-to-locate-error-simple-steps/"><u>Fixing 'lsass.exe' Unable to Locate Error - Simple Steps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-expert-techniques-to-elevate-your-fullscreen-experience-in-premiere/"><u>2024 Approved  Expert Techniques to Elevate Your Fullscreen Experience in Premiere</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-most-popular-free-gaming-platforms-for-pc-and-android/"><u>2024 Approved 10 Most Popular Free Gaming Platforms for PC and Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-comprehensive-guide-to-youtube-video-captioning/"><u>[Updated] In 2024, Comprehensive Guide to YouTube Video Captioning</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-a05-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy A05</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-empty-folder-error-message-on-win-11/"><u>Removing the 'Empty Folder' Error Message on Win 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-motorola-g54-5g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Motorola G54 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-access-rectifying-unreachable-ea-services/"><u>Reestablishing Access: Rectifying Unreachable EA Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fixes-for-non-responsive-backlight-on-windows-pcs/"><u>Five Fixes for Non-Responsive Backlight on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-unveiling-the-6-top-rated-digital-libraries-for-haunting-audio-effects-2e-update/"><u>New 2024 Approved Unveiling the 6 Top-Rated Digital Libraries for Haunting Audio Effects (2E Update)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-audacity-audio-basics-for-new-mac-users/"><u>In 2024, Audacity Audio Basics for New Mac Users</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-iphone-se-2022-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your iPhone SE (2022) and iPad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
</ul></div>
