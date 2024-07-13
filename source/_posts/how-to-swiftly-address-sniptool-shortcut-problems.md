---
title: How to Swiftly Address SnipTool Shortcut Problems
date: 2024-07-12T17:45:22.606Z
updated: 2024-07-13T17:45:22.606Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Swiftly Address SnipTool Shortcut Problems
excerpt: This Article Describes How to Swiftly Address SnipTool Shortcut Problems
keywords: Fixing Toolbar Issues Quickly,Solving SnipError Effectively,Troubleshooting SnipTrick Fast,Accelerate Snipping Errors,Efficient SnipTool Fixes,Swift SnipProblem Resolution,Rapid Rectify SnipShortcut
thumbnail: https://thmb.techidaily.com/099f29eab2c71ad55d4343f08e03217de8a45609b98e37e8d331924ca8f4791a.jpg
---

## How to Swiftly Address SnipTool Shortcut Problems

 Whether you need to capture an error message or share something specific with someone, screenshots can be a lifesaver. The Win + Shift + S shortcut makes it easy to take screenshots with the Snipping Tool, but what if that shortcut stops responding?

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

## 1\. Restart the Computer

 It might sound simple, but restarting your computer often solves minor problems. This can help clear out any glitches that may prevent the shortcut from working correctly.

 To restart your computer, close any running programs. Now, open the Start menu and choose **Restart** in the list of options.

## 2\. Check Your Keyboard

 Check the keyboard for any dirt or debris that may obstruct the keys. Clean off dust, crumbs, and other particles with compressed air. Ensure that all the keys are working correctly and that none are stuck or pressed down. If the keys have been damaged or worn down, consider replacing your keyboard.

## 3\. Enable the Clipboard History

 If keyboard dirt and debris are not the issues, you may need to enable the clipboard history feature. This will help you restore any screenshots taken with Win + Shift + S that have been lost.

![Enable the Clipboard History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-the-clipboard-history.jpg)

 To enable it, open Settings and navigate to **System** \> **Clipboard**. There, you'll find the toggle for **Clipboard history** – turn it on.

 You can also use the Windows search bar to type in **Clipboard settings** and open it directly. If you prefer shortcuts, hit **Win + R** or type **ms-settings:clipboard** into Run.

## 4\. Turn on Snipping Tool Notification Toggle

 When you press Win + Shift + S on your keyboard, a notification should appear in the bottom-right corner of the screen. This notification toggle helps you quickly access screenshots taken with the shortcut.

 If you don't see a notification, that means the toggle is off, and you may need to enable it manually. Here's how to do it:

1. Right-click on Start and select **Settings**.
2. In the Settings window, navigate to **System** \> **Notifications**.
3. Under **Notifications from apps and other senders**, scroll down to the bottom and turn on the Snipping Tool notification toggle.  
![Turn on Snipping Tool Notification Toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-snipping-tool-notification-toggle.jpg)

 Once you have enabled this option, press **Win + Shift + S** to take a screenshot. If the shortcut works, you will see a notification that the screenshot is saved to the clipboard.

## 5\. Reset the Snipping Tool

 Another solution is to reset the Snipping Tool. It restores the default settings and can help if something goes wrong.

 To reset it, right-click on the **Start** menu and select **Installed apps**. Find **Snipping Tool** in the list, click three dots, and select **Advanced options**.

 You can also use **Win + R** or type **ms-settings:appsfeatures** in the Run dialog box to open Installed apps. From there, you can find the Advanced options for the Snipping Tool.

![Reset Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-snipping-tool.jpg)

 On the next page, scroll down to the **Reset** section. Select **Reset** and then click on **Reset** again in the confirmation popup. After resetting the Snipping Tool, check if the Win + Shift + S shortcut works.

## 6\. Reinstall the Snipping Tool

 If resetting doesn't solve the problem, try reinstalling the Snipping Tool. It will resolve any issues you may have with your current installation.

 To reinstall the Snipping Tool, open the System Settings. Select **Apps** \> **Installed apps**, then find and select **Snipping Tool** from the list of installed programs.

![Reset the Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-snipping-tool.jpg)

 Click the three dots and select **Uninstall**. Now follow the on-screen instructions to complete the process. Once done, download and install a new version of the Snipping Tool from the Microsoft Store app.

## 7\. Turn on Windows Hotkeys

 If your Windows hotkeys are disabled for some reason, the shortcut keys will not work. In such cases, you will need to enable the Windows hotkeys through the group policy editor. Here's how to do it:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **gpedit.msc** in the dialog box and hit Enter. This will open the Group Policy Editor window.  
![Turn on Windows Hotkeys Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-group-policy.jpg)
3. Navigate to the path:  
`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, double-click on the **Turn off Windows Key hotkeys** option.
5. Select Enabled in the settings window and click **Apply** \> **OK**.

 After making these changes, try taking a screenshot with Win + Shift + S shortcut. It should work now.

 One thing to remember is that this method will only work with Windows Pro and Enterprise editions. If you have the Home edition, you can't access the Group Policy Editor. In such a case, you'll need to [enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated, skip this method and use the Registry Editor instead.

 To enable Windows Hotkeys through the Registry Editor, follow these steps:

* Click on Start, type **regedit**, and hit **Enter**.
* If the UAC window pops up, click Yes to open the registry editor.  
`Navigate to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer`
* If you don't see the Explorer folder, right-click on **Policies** and select **New > Key**. Name the newly created key **Explorer**.
* Now right-click on **Explorer** and select **New** \> **DWORD 32-bit**.
* Name the DWORD **NoWinKeys**.
* Double-click on **NoWinKeys** and set the value data to **0**.  
![Turn on Windows Hotkeys Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-registry.jpg)
* Select Base as **Hexadecimal** and click **OK** to save the changes.

 After that, exit the registry editor and restart your computer. Once the system reboots, check if the issue has been resolved.

## 8\. Perform Some Generic Fixes

 There are a few general fixes that might help you get the Win + Shift + S keyboard shortcut working. Here's what you need to do:

1. Check the keyboard driver status and update it if needed.
2. Try [running the SFC utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to fix corrupted system files.
3. Make sure you are [running the latest version of Windows](https://www.makeuseof.com/update-windows-manually/).
4. [Run a full scan with your antivirus program](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and see if it solves the issue.
5. If the issue still persists, there's a chance that third-party applications are interfering with the Snipping Tool shortcut. In such a case, [try performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This will temporarily disable all the third-party applications and allow you to check if they were causing the issue.

## Taking Screenshots Is Easy With Shortcut Keys

 Keyboard shortcuts provide quick and easy access to different functions on your PC. It allows you to easily switch between applications and perform tasks. There are times, though, when the Win + Shift + S hotkey does not work properly. Hopefully, one of the above methods fixed this issue for you.

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-touchpad-gestures-not-working-in-windows/"><u>How to Fix Touchpad Gestures Not Working in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-windows-hosts-overuse-a-guide/"><u>Reducing Windows Host's Overuse: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-11-bluetooth-try-connecting-error/"><u>Steps to Resolve Windows 11 Bluetooth 'Try Connecting' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-flawed-windows-safety-features-in-win-11/"><u>Fixing Flawed Windows Safety Features in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-entry-into-your-windows-11s-application-arcade/"><u>Effortless Entry Into Your Windows 11'S Application Arcade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-gpo-application-one-user-approach-for-windows-1111/"><u>Focusing GPO Application: One-User Approach for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-constant-windows-printer-selection/"><u>Guidelines for Constant Windows Printer Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-the-status-bar-a-guide-to-including-a-weather-icon-in-windows-11/"><u>Customize the Status Bar: A Guide to Including a Weather Icon in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-decode-and-clear-windows-10s-activity-archive/"><u>How to Decode and Clear Windows 10'S Activity Archive</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-through-your-new-m1-max-clip-world/"><u>In 2024, Navigating Through Your New M1 Max Clip World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-ai-enhance-windows-11-usability/"><u>How Does AI Enhance Windows 11 Usability?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-strategies-for-sustained-top-level-visibility-on-win-os/"><u>Sticky Notes Strategies for Sustained Top-Level Visibility on Win OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y36-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y36</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-enhancing-your-listening-experience-the-essentials-of-recording-with-audacity-on-mac/"><u>[New] 2024 Approved  Enhancing Your Listening Experience  The Essentials of Recording with Audacity on Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cybersecurity-insight-key-windows-activities-that-could-conceal-threats/"><u>Cybersecurity Insight: Key Windows Activities That Could Conceal Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-window-management-active-periods-not-permanent-disruptions/"><u>Efficient Window Management: Active Periods, Not Permanent Disruptions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-culinary-waves-top-10-flavorful-tiktok-recipes/"><u>2024 Approved  Culinary Waves  Top 10 Flavorful TikTok Recipes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-local-sam-service-error-on-computers/"><u>Fix for Local SAM Service Error on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-security-running-as-administrator/"><u>Navigating Windows Security: Running As Administrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-non-active-vss-service-states/"><u>Restoring Non-Active VSS Service States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-opengl-error-3-nvidia-solutions-win1011/"><u>Eliminating OpenGL Error 3: Nvidia Solutions (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-win-11-taskbar/"><u>Mastering Time Display on Win 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-fixing-media-creators-error-0x8007043c/"><u>Methods for Fixing Media Creator's Error 0X8007043C</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/build-your-ai-twitch-streamer-with-animated-avatars-for-2024/"><u>Build Your AI Twitch Streamer with Animated Avatars for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-invalid-steam-response-issue/"><u>Steps to Resolve Invalid Steam Response Issue</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-the-ultimate-2023-checklist-for-camstudio-video-recording/"><u>[Updated] 2024 Approved  The Ultimate 2023 Checklist for CamStudio Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microphone-blackout-during-powerpoint-video-recording/"><u>Fixing Microphone Blackout During PowerPoint Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-the-gaming-revolution-integrate-trophies-and-awards-using-retroarch/"><u>Reignite the Gaming Revolution - Integrate Trophies and Awards Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-nexus-of-networked-realities-unveiling-metaverse-vs-omniverse/"><u>2024 Approved  Nexus of Networked Realities  Unveiling Metaverse Vs. Omniverse</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-obsolete-directx-applications-using-dxvk/"><u>Overhauling Obsolete DirectX Applications Using DXVK</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-photos-files-on-xiaomi-redmi-note-12-4g-by-fonelab-android-recover-photos/"><u>Complete guide for recovering photos files on Xiaomi Redmi Note 12 4G.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-themes-for-enhanced-terminal-views/"><u>Innovative Themes for Enhanced Terminal Views</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-graphicgrind-studio/"><u>[Updated] 2024 Approved  GraphicGrind Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-grammarly-a-dead-service-on-your-desktop/"><u>Reactivating Grammarly, a Dead Service on Your Desktop</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-update-top-5-ipad-video-editors-for-creators-and-beginners/"><u>New 2024 Approved Update Top 5 iPad Video Editors for Creators and Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-re-entry-to-your-shared-windows-spot/"><u>Seamless Re-Entry to Your Shared Windows Spot</u></a></li>
<li><a href="https://fox-direct.techidaily.com/best-options-cheap-but-premium-4k-projector-systems/"><u>Best Options  Cheap but Premium 4K Projector Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-remove-button-for-windows-11-pins/"><u>Reinstating Absent 'Remove' Button for Windows 11 PINs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-valheims-flora-frontier-unlocking-the-best-seeds-for-2024/"><u>[New] Valheim's Flora Frontier  Unlocking the Best Seeds for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
</ul></div>
