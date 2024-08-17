---
title: Stop Windows From Prompting for Updates
date: 2024-08-16T02:38:26.444Z
updated: 2024-08-17T02:38:26.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Prompting for Updates
excerpt: This Article Describes Stop Windows From Prompting for Updates
keywords: Stop Update Prompts -,Avoid Windows Update Alerts -,Prevent Windows Update Requests -,No More Update Prompts on Windows -,Block Windows Update Interruption -,Defer Windows Update Notifications -,Disable Windows Update Warnings -
thumbnail: https://thmb.techidaily.com/bb00ebc3d89d1362ca9b186657d254b37c10a245e721f7dc9d791e4530e6a65b.jpeg
---

## Stop Windows From Prompting for Updates

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-eye-catching-insta-highlights-unveiling-3-secrets/"><u>[New] 2024 Approved  Eye-Catching Insta Highlights  Unveiling 3 Secrets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-youtube-presence-with-masterful-editing-skills/"><u>[New] In 2024, Elevate Your YouTube Presence with Masterful Editing Skills</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-banner-brilliance-elevating-your-game-channel-image/"><u>[Updated] In 2024, Banner Brilliance  Elevating Your Game Channel Image</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-license-expiration-alert-on-windows-11/"><u>Addressing 'License Expiration' Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-hdd-or-ssd-through-windows-settings/"><u>Ascertain HDD or SSD Through Windows Settings</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/capturing-online-seminars-for-2024/"><u>Capturing Online Seminars for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-the-status-bar-a-guide-to-including-a-weather-icon-in-windows-11/"><u>Customize the Status Bar: A Guide to Including a Weather Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-opengl-error-3-nvidia-solutions-win1011/"><u>Eliminating OpenGL Error 3: Nvidia Solutions (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-local-sam-service-error-on-computers/"><u>Fix for Local SAM Service Error on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microphone-blackout-during-powerpoint-video-recording/"><u>Fixing Microphone Blackout During PowerPoint Video Recording</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722902138416-get-the-scoop-on-android-16-free-download-info-launch-timeline-and-speculated-features/"><u>Get the Scoop on Android 16: Free Download Info, Launch Timeline & Speculated Features!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-decode-and-clear-windows-10s-activity-archive/"><u>How to Decode and Clear Windows 10'S Activity Archive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-touchpad-gestures-not-working-in-windows/"><u>How to Fix Touchpad Gestures Not Working in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-t2-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/how-to-smoothly-integrate-linktree-into-your-tiktok-bio-space/"><u>How to Smoothly Integrate Linktree Into Your TikTok Bio Space</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-effective-strategies-to-capture-and-save-google-voice-dialogues/"><u>In 2024, Effective Strategies to Capture and Save Google Voice Dialogues</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-xiaomi-redmi-a2plus-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Xiaomi Redmi A2+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-navigating-the-world-of-9gag-memes-made-easy/"><u>In 2024, Navigating the World of 9GAG Memes Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-obsolete-directx-applications-using-dxvk/"><u>Overhauling Obsolete DirectX Applications Using DXVK</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/secure-stylish-and-smart-choose-from-these-5-recorders-for-2024/"><u>Secure, Stylish and Smart - Choose From These 5 Recorders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-unlock-a-locked-out-windows-11-with-error-22/"><u>Strategies to Unlock a Locked Out Windows 11 with Error 22</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-best-ispoofer-alternative-to-try-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-3-sites-to-find-free-gionee-unlock-codes-to-unlock-your-gionee-phone-by-drfone-android/"><u>Top 3 Sites to Find Free Gionee Unlock Codes to Unlock Your Gionee Phone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-vivo-y36i-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Vivo Y36i Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-top-rated-and-totally-free-the-best-online-video-editors-without-watermarks-for-2024/"><u>Updated Top-Rated and Totally Free The Best Online Video Editors without Watermarks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
</ul></div>
