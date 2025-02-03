---
title: Batch-Processing Closure for Busy Windows Users
date: 2025-01-27T17:34:44.803Z
updated: 2025-02-01T02:57:15.542Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Batch-Processing Closure for Busy Windows Users
excerpt: This Article Describes Batch-Processing Closure for Busy Windows Users
keywords: Batch Close Windows,Efficient Process Exit,Closure for Windows Users,Quick Batch Closing,Time-Saving Windows Shutdown,Streamlined Busy PC Closure,Accelerated Task Ending Windows
thumbnail: https://thmb.techidaily.com/f03d30631576de9c6f4ebbf1b70482dc429c1bbf94f405ab42db14407ed62e05.jpg
---

## Batch-Processing Closure for Busy Windows Users

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-top-ranked-hd-screen-replay-units/"><u>[New] 2024 Approved Top-Ranked HD Screen Replay Units</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-sdr-vs-hdr-embracing-hdr-for-enhanced-video-production/"><u>[Updated] 2024 Approved SDR vs HDR Embracing HDR for Enhanced Video Production</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-top-screen-capture-software-for-discord-androidios/"><u>[Updated] In 2024, Top Screen Capture Software for Discord (Android/iOS)</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-unlock-flawless-facetime-call-recordings-a-complete-walkthrough-for-2024/"><u>[Updated] Unlock Flawless FaceTime Call Recordings A Complete Walkthrough for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-redesign-instant-twitter-video-view/"><u>2024 Approved Redesign Instant Twitter Video View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-absent-tabs-in-system-navigator/"><u>Combatting Absent Tabs in System Navigator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-audio-to-alphabets-transcribing-talk-on-your-pc-with-whisper/"><u>From Audio to Alphabets: Transcribing Talk on Your PC with Whisper</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-luts-as-the-key-to-vivid-film-colors/"><u>In 2024, Luts as the Key to Vivid Film Colors</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-pioneering-programs-3d-animation-crafting/"><u>In 2024, Pioneering Programs 3D Animation Crafting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-basics-of-printer-settings-in-win11-max-56-chars/"><u>Mastering the Basics of Printer Settings in Win11 (Max 56 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-troubleshooting-windows-remote-desktop-errors/"><u>Mastering Troubleshooting Windows Remote Desktop Errors</u></a></li>
<li><a href="https://driver-download.techidaily.com/realtek-sound-device-software-updates-for-windows-11-10-and-e7-users-start-your-download-here/"><u>Realtek Sound Device Software Updates for Windows 11, 10 and E7 Users - Start Your Download Here.</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-update-error-0x8024200d-expert-tips-and-tricks-fixed/"><u>Resolving Windows Update Error 0X8024200d – Expert Tips and Tricks [FIXED]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-connection-setting-up-intel-wireless-devices-on-ubuntu/"><u>Securing Your Connection: Setting Up Intel Wireless Devices on Ubuntu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-shortage-of-usb-ports-in-windows-os/"><u>Tackling Shortage of USB Ports in Windows OS</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-professionals-secret-utilizing-windows-movie-maker-expertly-in-windows-8-systems/"><u>The Professional's Secret Utilizing Windows Movie Maker Expertly in Windows 8 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-correcting-directdraw-fails-in-win1011/"><u>The Ultimate Guide to Correcting DirectDraw Fails in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-the-game-of-access-paths-to-opening-directories/"><u>Win the Game of Access: Paths to Opening Directories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-users-guide-to-playnite-and-emulators/"><u>Windows Users' Guide to Playnite and Emulators</u></a></li>
</ul></div>

