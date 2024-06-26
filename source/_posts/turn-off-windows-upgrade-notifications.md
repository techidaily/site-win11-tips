---
title: Turn Off Windows Upgrade Notifications
date: 2024-06-25T16:11:52.877Z
updated: 2024-06-26T16:11:52.877Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off Windows Upgrade Notifications
excerpt: This Article Describes Turn Off Windows Upgrade Notifications
keywords: Stop Update Alerts,End Windows Push Notices,Halt Auto-Updates,Disable UGIN Prompts,Quiet System Patches,Cease Upgrade Warnings,Block Windows Push Notifications
thumbnail: https://thmb.techidaily.com/d5d13fb577cc5620ebbaf2970abea56dace77d9e5a84a022ba162f616f0fcf69.png
---

## Turn Off Windows Upgrade Notifications

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
<li><a href="https://win11-tips.techidaily.com/strategies-to-maintain-saving-windows-audio-configuration/"><u>Strategies to Maintain Saving Windows Audio Configuration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-generation-inquiry-on-windows-8-efficient-approaches/"><u>CPU Generation Inquiry on Windows – 8 Efficient Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-combat-gaming-induced-laptop-overheating/"><u>Steps to Combat Gaming-Induced Laptop Overheating</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-virtualboxs-0x80004005-failure-on-win/"><u>Dealing with VirtualBox's 0X80004005 Failure on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-methodology-for-windows-update-reset/"><u>Stepwise Methodology for Windows Update Reset</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-mastering-twitter-video-dimensions-aspect-ratio-best-practices/"><u>In 2024, Mastering Twitter Video Dimensions Aspect Ratio Best Practices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-copyright-safe-techniques-for-youtube-to-mp4/"><u>[New] 2024 Approved  Copyright-Safe Techniques for Youtube-to-MP4</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-capture-the-moment-enhancing-and-cutting-video-for-instagram-impact/"><u>[New] Capture the Moment  Enhancing and Cutting Video for Instagram Impact</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-backgrounds-for-live-streaming/"><u>In 2024, Best Backgrounds for Live Streaming</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-oneplus-ace-2v-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead OnePlus Ace 2V Safely | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-audio-aficionados-curated-selection-of-free-lut-links-for-2024/"><u>[Updated] Audio Aficionados' Curated Selection of Free LUT Links for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-everything-from-apple-iphone-12-mini-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Everything from Apple iPhone 12 mini to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unforgettable-stop-motion-films-the-top-15-list-for-2024/"><u>Unforgettable Stop-Motion Films - The Top 15 List for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-honor-play-8t-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Honor Play 8T.</u></a></li>
</ul></div>
