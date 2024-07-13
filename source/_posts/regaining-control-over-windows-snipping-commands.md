---
title: Regaining Control Over Windows' Snipping Commands
date: 2024-07-12T17:25:54.970Z
updated: 2024-07-13T17:25:54.970Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Control Over Windows' Snipping Commands
excerpt: This Article Describes Regaining Control Over Windows' Snipping Commands
keywords: Snipping Tools Control,Windows Snip Commands,Restore Snipping Power,Manage Screenshot Tools,Snip Command Regain,Screenshot Oversight,Control Window Snip
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## Regaining Control Over Windows' Snipping Commands

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
<li><a href="https://win11-tips.techidaily.com/reconciling-system-with-a-fresh-net-framework-max-156/"><u>Reconciling System with a Fresh .NET Framework (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-page-load-failure-on-microsoft-store-windows-app/"><u>Resolving 'Page Load Failure' On Microsoft Store Windows App</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tailored-timeline-management-best-twitter-unfollow-tools-ranked/"><u>[Updated] In 2024, Tailored Timeline Management  Best Twitter Unfollow Tools Ranked</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-top-picks-7-best-free-convertors-turning-tiktop-videos-to-mp3s-online/"><u>[New] 2024 Approved  Top Picks  7 Best FREE Convertors Turning TikTop Videos To MP3s Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-corner-design-in-win11/"><u>Rectify Corner Design in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-windows-11-error-code-22-lockout/"><u>Steps to Rectify Windows 11 Error Code 22 Lockout</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nubia-red-magic-8s-proplus-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-beat-makers-playbook-ranking-the-top-8-daw-applications-for-contemporary-urban-music-for-2024/"><u>New The Beat Makers Playbook Ranking the Top 8 DAW Applications for Contemporary Urban Music for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-absence-of-tab-functionality-in-os-x/"><u>Navigating the Absence of Tab Functionality in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-fixing-windows-11-help-menu-failure/"><u>Steps for Fixing Windows 11 Help Menu Failure</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/5-best-dvd-creators-for-macos-sierra/"><u>5 Best DVD Creators for macOS Sierra</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162065608-top-4-ios-superior-game-boy-advance-emulators/"><u>Top 4 iOS: Superior Game Boy Advance Emulators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-mp4-to-mp3-conversion-made-easy-best-software/"><u>Updated MP4 to MP3 Conversion Made Easy Best Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-screen-splitting-problems-in-win-10/"><u>Solutions for Screen Splitting Problems in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-invisible-wi-fi-on-windows/"><u>Master the Art of Invisible Wi-Fi on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-gmaps-windows-pc-guide/"><u>Setting Up GMaps: Windows PC Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-step-into-the-future-youtubes-best-vr-experiences/"><u>In 2024, Step Into the Future  YouTube's Best VR Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-steam-network-error-in-windows-11-systems/"><u>Remedying Steam Network Error in Windows 11 Systems</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-apple-iphone-x-and-ipad-screen-mirroring-app-drfone-by-drfone-ios/"><u>In 2024, Best Apple iPhone X & iPad Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-black-windows-display-with-ease/"><u>Navigate Black Windows Display with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-vs-new-why-users-favor-windows-10-over-11/"><u>Old vs New: Why Users Favor Windows 10 Over 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-fixing-system-call-error-on-windows-11/"><u>Preventing and Fixing System Call Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-unrecoverable-windows-errors/"><u>Solutions to Unrecoverable Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stops-repeated-edge-icons-on-workspace/"><u>Stops Repeated Edge Icons on Workspace</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-harness-the-power-of-engagement-boosting-youtube-traffic/"><u>2024 Approved  Harness the Power of Engagement  Boosting YouTube Traffic</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-samsung-galaxy-s24-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Samsung Galaxy S24 Device</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essentials-of-professional-level-audio-crossfade/"><u>In 2024, The Essentials of Professional-Level Audio Crossfade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-7-easy-steps-for-a-subscriber-surge-on-youtube/"><u>[New] In 2024, 7 Easy Steps for a Subscriber Surge on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-way-a-guide-to-mapping-drives-on-windows-11/"><u>Navigate Your Way: A Guide to Mapping Drives on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalized-lock-patterns-on-windows-11/"><u>Mastering Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-sliceshot-synopsis/"><u>2024 Approved  SliceShot Synopsis</u></a></li>
</ul></div>
