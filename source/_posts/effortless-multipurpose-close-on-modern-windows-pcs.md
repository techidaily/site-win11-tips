---
title: Effortless Multipurpose Close on Modern Windows PCs
date: 2024-08-28T01:11:51.120Z
updated: 2024-08-29T01:11:51.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Multipurpose Close on Modern Windows PCs
excerpt: This Article Describes Effortless Multipurpose Close on Modern Windows PCs
keywords: Modern Window Tech,Multi-Purpose Screens,Easy Close Mechanism,Windows PC Adjustments,Closure Systems Design,Simplified Screen Use,Innovative PC Frames
thumbnail: https://thmb.techidaily.com/12e88707f59d2cf337816f66e57d39a5f3c787beb919eddcfabef3a341868406.jpg
---

## Effortless Multipurpose Close on Modern Windows PCs

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-ideal-dialogue-architect-forum/"><u>[New] Ideal Dialogue Architect Forum</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-mp3-broadcasting-toolkit-convert-upload-and-stream-youtube/"><u>[New] In 2024, MP3 Broadcasting Toolkit  Convert, Upload & Stream YouTube</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-comedy-kings-and-queens-of-2023-for-2024/"><u>[Updated] Comedy Kings & Queens of 2023 for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-video-mastery-step-by-step-guide-to-cropping-and-exporting-for-insta/"><u>[Updated] In 2024, Video Mastery  Step by Step Guide to Cropping and Exporting for Insta</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-laughter-is-free-access-to-top-meme-creations-for-2024/"><u>[Updated] Laughter Is Free  Access to Top Meme Creations for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-unmarked-image-accumulation-essentials/"><u>2024 Approved  Unmarked Image Accumulation Essentials</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-realme-gt-neo-5-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Realme GT Neo 5 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-internal-auditory-graph-layouts/"><u>Deciphering Windows' Internal Auditory Graph Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrypting-secure-connections-windows-11s-hidden-tricks/"><u>Decrypting Secure Connections: Windows 11'S Hidden Tricks</u></a></li>
<li><a href="https://driver-error.techidaily.com/download-microsoft-xbox-one-controller-driver-for-windows/"><u>Download Microsoft Xbox One Controller Driver for Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/entering-vr-top-10-must-try-mobile-gaming-hits/"><u>Entering VR  Top 10 Must-Try Mobile Gaming Hits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-filtering-in-task-manager-and-theme-implementation-in-windows-11/"><u>Essential Guide to Filtering in Task Manager & Theme Implementation in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/fast-and-easy-setup-for-your-linksys-ae2500-driver/"><u>Fast & Easy Setup for Your Linksys AE2500 Driver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-the-perfect-windows-11-match-for-you-home-or-pro/"><u>Finding the Perfect Windows 11 Match for You: Home or Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-invisible-windows-11-account-entry-screen/"><u>Fixes for Invisible Windows 11 Account Entry Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-glitches-on-windows-11-sound-error-code-0xc00d36b4/"><u>Fixing Glitches on Windows 11: Sound Error, Code 0xC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-too-little-memory-warning-for-virtual-machines/"><u>Fixing Too Little Memory Warning for Virtual Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-overcome-camera-error-on-win11-system/"><u>Guides to Overcome Camera Error on Win11 System</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-vivo-s18e-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Vivo S18e For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-spotify-code-4-connection-error-in-windows-11-and-11/"><u>How to Fix the Spotify Code 4 Connection Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rotate-the-windows-display-by-90-degrees-and-why-you-should/"><u>How to Rotate the Windows Display by 90 Degrees (and Why You Should)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nubia Red Magic 8S Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introduction-to-administering-windows-component-tool/"><u>Introduction to Administering Windows' Component Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberate-your-laptop-slimline-windows-11/"><u>Liberate Your Laptop: Slimline Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-11-task-manager-filter-wizard-and-aesthetic-tweaks-guide/"><u>Master the Windows 11 Task Manager: Filter Wizard & Aesthetic Tweaks Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microphone-trouble-in-google-meet-for-windows-users/"><u>Microphone Trouble in Google Meet for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ms-project-skills-keyboard-speedup-secrets/"><u>MS Project Skills: Keyboard Speedup Secrets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-hardware-space-w10-and-w11-insights/"><u>Navigating Your Hardware Space: W10 & W11 Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-delayed-audio-in-windows/"><u>Overcoming Delayed Audio in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-default-settings-for-folder-display-mode/"><u>Reclaiming Default Settings for Folder Display Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-low-usb-port-space-on-desktops/"><u>Rectifying Low USB Port Space on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-lost-5ghz-connectivity-for-your-windows-11-pc/"><u>Regain Lost 5GHz Connectivity for Your Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstall-success-fixing-clipchamp-on-windows-11/"><u>Reinstall Success: Fixing ClipChamp on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-timers-on-the-fly-fixing-scheduler-problems/"><u>Resolve Timers on the Fly: Fixing Scheduler Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-optimal-operation-of-windows-metrics-tool/"><u>Restoring Optimal Operation of Windows Metrics Tool</u></a></li>
<li><a href="https://extra-resources.techidaily.com/srt-mastery-curating-the-best-mac-and-windows-turbo-boosts/"><u>SRT Mastery  Curating the Best Mac & Windows Turbo Boosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-reboot-and-reset-file-explorer-ui/"><u>Strategies to Reboot and Reset File Explorer UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-steps-unlocking-the-windows-11-folder-of-applications/"><u>Streamlined Steps: Unlocking the Windows 11 Folder of Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-thumbnails-on-your-pc-a-guide/"><u>Tailoring Thumbnails on Your PC: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskers-puzzle-edge-and-other-processes/"><u>Tasker's Puzzle: Edge and Other Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-beginners-blueprint-for-windows-11-desktop-art/"><u>The Beginner's Blueprint for Windows 11 Desktop Art</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-t2x-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo T2x 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-stop-built-in-laptop-input-device-on-desktop/"><u>Tips to Stop Built-In Laptop Input Device on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-windows-discord-latency-issues/"><u>Troubleshooting: Resolving Windows Discord Latency Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-free-space-tackling-temporary-files-head-on/"><u>Win-Free Space: Tackling Temporary Files Head On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-functionality-and-purpose/"><u>Windows 11 S Mode: Functionality and Purpose?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-photos-command-center-key-navigation/"><u>Windows Photos: Command Center Key Navigation</u></a></li>
</ul></div>
