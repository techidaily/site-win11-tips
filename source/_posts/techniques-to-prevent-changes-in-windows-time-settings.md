---
title: Techniques to Prevent Changes in Windows Time Settings
date: 2024-12-23T18:58:44.771Z
updated: 2024-12-27T20:57:20.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Prevent Changes in Windows Time Settings
excerpt: This Article Describes Techniques to Prevent Changes in Windows Time Settings
keywords: Windows Time Fix,Stable Windows Clock,Time Change Prevention,Secure Time Settings,Update Time Configuration,Anti-Time Adjust,Guard Windows Time
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
---

## Techniques to Prevent Changes in Windows Time Settings

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-childhood-cruisers-crafted-games/"><u>[Updated] 2024 Approved Childhood Cruisers, Crafted Games</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unraveling-the-imovie-video-edge-policy/"><u>[Updated] Unraveling the iMovie Video Edge Policy</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-quick-snapback-to-loss-prevention/"><u>2024 Approved Quick Snapback to Loss Prevention</u></a></li>
<li><a href="https://extra-tips.techidaily.com/breezy-collage-creation-with-picshots-innovations/"><u>Breezy Collage Creation with Picshot's Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-error-x0001-on-geforce-for-windows-11/"><u>Clearing Up Error X0001 on GeForce for Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-vivo-y100a-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-unseen-camera-issue-in-windows-device-manager/"><u>Fix Unseen Camera Issue in Windows Device Manager</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-amateurs-to-aviators-9-top-rated-drone-editors-reviewed/"><u>From Amateurs to Aviators 9 Top-Rated Drone Editors Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-and-solve-windows-os-errors-with-ease/"><u>Navigate and Solve Windows OS Errors with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-file-maintenance-utilizing-windows-11s-auto-delete-feature/"><u>Streamline File Maintenance: Utilizing Windows 11’S Auto Delete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surviving-windows-10-system-failsafe/"><u>Surviving Windows 10 System Failsafe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-fixers-companion-overcoming-blue-screen-woes/"><u>The Fixer's Companion: Overcoming Blue Screen Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-internal-gpu-a-guide-for-windows-users/"><u>Turn Off Internal GPU: A Guide for Windows Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-final-cut-pro-2023-unlocking-professional-color-correction-for-2024/"><u>Updated Final Cut Pro 2023 Unlocking Professional Color Correction for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/1728473506065-windows-11/"><u>Windows 11 : システムファイル容量オーバー防止ガイド</u></a></li>
</ul></div>

