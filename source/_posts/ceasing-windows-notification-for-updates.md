---
title: Ceasing Windows Notification for Updates
date: 2024-06-25T16:18:21.590Z
updated: 2024-06-26T16:18:21.590Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ceasing Windows Notification for Updates
excerpt: This Article Describes Ceasing Windows Notification for Updates
keywords: Stop Update Alerts (Windows),End Windows Update Notifications,Disable Windows Update Warnings,Cease Windows Update Tips,Quiet Windows Update Prompts,Turn Off Windows Updates,Mute Windows Update Announcements
thumbnail: https://thmb.techidaily.com/97b5d85adaa70d7cf066a732f43c0486f51d36a4ba60d02434a07b91f944e872.jpg
---

## Ceasing Windows Notification for Updates

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-printer-settings-in-windows-environment/"><u>Seamless Integration of Printer Settings in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-lowering-cpu-intensity-in-gaming-windows/"><u>Solutions for Lowering CPU Intensity in Gaming Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-error-0xc00000f-in-windows-pcs/"><u>Understanding and Resolving Error 0Xc00000f in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unplugging-problems-addressing-frequent-ps4-disconnection-in-pc/"><u>Unplugging Problems: Addressing Frequent PS4 Disconnection in PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-winservicesexe-deciphering-windows-process/"><u>Understanding WinServices.exe: Deciphering Windows Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-poco-c51-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Poco C51? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/saving-your-social-media-face-from-spurious-support/"><u>Saving Your Social Media Face From Spurious Support</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-y02t-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo Y02T Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-video-creation-understanding-the-role-of-camera-lenses-in-vlogging/"><u>In 2024, Master Video Creation  Understanding the Role of Camera Lenses in Vlogging</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-guide-to-the-best-7-android-adblock-tools/"><u>[New] The Ultimate Guide to the Best 7 Android AdBlock Tools</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-realme-c51-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Realme C51 Phone?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-huawei-p60-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Huawei P60 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-infinix-smart-8-pro-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Infinix Smart 8 Pro Users</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-12-pro-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 12 Pro | Dr.fone</u></a></li>
</ul></div>
