---
title: "Batch Closing Tips: End All Windows Tasks Simultaneously"
date: 2024-07-12T18:08:51.097Z
updated: 2024-07-13T18:08:51.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Batch Closing Tips: End All Windows Tasks Simultaneously"
excerpt: "This Article Describes Batch Closing Tips: End All Windows Tasks Simultaneously"
keywords: Batch Close Tasks,Windows Closing Guide,End Task Efficiently,Simultaneous Task Shutdown,Productivity Boost Tips,Safe System Cleanup,Automated Task Management
thumbnail: https://thmb.techidaily.com/3cdd3221236d54f354b9655c53899223c63a3525ea895a2e29db68bcb7da9bba.jpg
---

## Batch Closing Tips: End All Windows Tasks Simultaneously

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://win11-tips.techidaily.com/audio-drivers-for-windows-a-comprehensive-update-guide/"><u>Audio Drivers for Windows: A Comprehensive Update Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-system-conquering-power-save-errors/"><u>Awaken Your System: Conquering Power Save Errors</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-enhance-playstation-2-gaming-the-ultimate-guide-to-android-emulation-tools/"><u>In 2024, Enhance PlayStation 2 Gaming  The Ultimate Guide to Android Emulation Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insight-into-runtime-brokers-role-on-your-machine/"><u>An Insight Into Runtime Broker's Role on Your Machine</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolution-fixing-nvidia-install-issue/"><u>Resolution: Fixing NVIDIA Install Issue</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-8-best-free-3d-video-player-for-window-and-mac-for-2024/"><u>[New] 8 Best Free 3D Video Player for Window and Mac for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/thriving-in-the-social-media-jungle-facebooks-essentials-for-2024/"><u>Thriving in the Social Media Jungle  Facebook's Essentials for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-typing-velocity-with-windows-powertools/"><u>Boost Typing Velocity with Windows' PowerTools</u></a></li>
<li><a href="https://facebook.techidaily.com/analyzing-the-cost-benefit-of-meta-verified-users/"><u>Analyzing the Cost-Benefit of Meta Verified Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-unwanted-updates-in-windows-11-with-proactive-measures/"><u>Avoid Unwanted Updates in Windows 11 with Proactive Measures</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-nokia-c12-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Nokia C12 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-pixireview-criticism-app/"><u>In 2024, PixiReview Criticism App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/androidwindows-twinning-effortless-sync-instructions/"><u>Android/Windows Twinning: Effortless Sync Instructions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-complete-guide-for-capturing-stunning-details-on-film/"><u>The Complete Guide for Capturing Stunning Details on Film</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-foremost-frame-openers-identifying-the-most-effective-16-youtube-intros/"><u>[Updated] Foremost Frame Openers  Identifying the Most Effective 16 YouTube Intros</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-remote-auditory-engineers-toolkit-optimizing-playback-velocity-and-harmonic-content-online/"><u>The Remote Auditory Engineers Toolkit Optimizing Playback Velocity and Harmonic Content Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-productivity-top-7-tips-for-mastering-windows-11/"><u>Boosting Productivity: Top 7 Tips for Mastering Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-mobility-center-activation-in-w11-systems/"><u>Avoid Mobility Center Activation in W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/anti-virus-ram-usage-strategies-for-efficiency-boost/"><u>Anti-Virus RAM Usage: Strategies for Efficiency Boost</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-oneplus-ace-2v-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advice-when-windows-doesnt-recognize-powershell-commands/"><u>Advice When Windows Doesn't Recognize PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-flexibility-with-additional-menus/"><u>Boost Windows Flexibility with Additional Menus</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-lava-blaze-2-5g-frp-by-drfone-android/"><u>How Can We Bypass Lava Blaze 2 5G FRP?</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unbranded-and-unbeatable-the-best-free-online-video-editors/"><u>In 2024, Unbranded and Unbeatable The Best Free Online Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-essential-wsl-2-approaches-for-win-users/"><u>Boost Performance: Essential WSL 2 Approaches for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audacity-sound-error-step-by-step-windows-fix-guide/"><u>Audacity Sound Error: Step-by-Step Windows Fix Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pickus-triumph-in-android-photo-editing-a-comprehensible-review-for-2024/"><u>PickU's Triumph in Android Photo Editing – A Comprehensible Review for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-printer-frustration-in-the-latest-os-win11-guide/"><u>Avoid Printer Frustration in the Latest OS: Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-pen-tablet-glitches-and-freezes/"><u>Addressing Windows PEN Tablet Glitches and Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-delay-in-sw-top-tips-to-speed-up-your-bf2-gameplay/"><u>Beat Delay in SW: Top Tips to Speed Up Your BF2 Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-with-these-5-unique-windows-pc-time-saver-tools/"><u>Boost Productivity with These 5 Unique Windows PC Time Saver Tools</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-video-editing-software-like-virtualdub-top-picks-and-reviews/"><u>2024 Approved Video Editing Software Like VirtualDub Top Picks and Reviews</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/is-avs-video-editor-worth-it-a-comprehensive-review/"><u>Is AVS Video Editor Worth It? A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auditory-capture-made-simple-with-microsofts-win-11/"><u>Auditory Capture Made Simple with Microsoft's Win 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-boosting-your-channel-a-guide-to-gaining-viewers/"><u>[New] 2024 Approved  Boosting Your Channel  A Guide to Gaining Viewers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-clashes-among-windows-icons/"><u>Avoid Clashes Among Window's Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackout-brilliance-using-dark-settings-in-microsoft-paint/"><u>Blackout Brilliance: Using Dark Settings in Microsoft Paint</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-and-control-windows-screenshots-for-better-use/"><u>Adjust and Control Windows Screenshots for Better Use</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-taste-trek-journey-through-global-cuisine-secrets/"><u>[Updated] In 2024, Taste Trek  Journey Through Global Cuisine Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-virtual-disk-startup-issues-in-windows-disk-manager/"><u>Addressing Virtual Disk Startup Issues in Windows Disk Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-11-desktop-appeal-live-and-animated-backgrounds/"><u>Boost Your Windows 11 Desktop Appeal: Live and Animated Backgrounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-frustrations-mastering-windows-11-management-tool-access/"><u>Avoiding Frustrations: Mastering Windows 11 Management Tool Access</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-easy-steps-to-deactivate-igtv-for-2024/"><u>[Updated] Easy Steps to Deactivate IGTV for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-skyrocketing-video-performance-on-vimeo/"><u>[New] 2024 Approved  Skyrocketing Video Performance on Vimeo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-awareness-of-power-levels-with-win-1011/"><u>Boosting Awareness of Power Levels with Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-automatic-windows-updates/"><u>Banishing Automatic Windows Updates</u></a></li>
</ul></div>
