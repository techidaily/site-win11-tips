---
title: Exclusive Removal of Win11's Official Store
date: 2024-07-12T17:18:14.040Z
updated: 2024-07-13T17:18:14.040Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exclusive Removal of Win11's Official Store
excerpt: This Article Describes Exclusive Removal of Win11's Official Store
keywords: Win11 Uninstall Guide,Remove Win11 Officially,Win11 Removal Tutorial,Exclude Win11 Store,Win11 License Cancellation,Official Windows XPe Offload,Free Win11 Deletion Methods
thumbnail: https://thmb.techidaily.com/8f88442ac6dedc419a65e9e8bd02cadcc874f8f080f0e1330c1b328f3cf15bd0.jpg
---

## Exclusive Removal of Win11's Official Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://win11-tips.techidaily.com/1719333011753-4-proven-strategies-for-enhancing-window-shot-taking-on-windows-os/"><u>4 Proven Strategies for Enhancing Window Shot Taking on Windows OS.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353749292-navigate-compatibility-hurdles-with-easy-to-follow-steps/"><u>Navigate Compatibility Hurdles with Easy-to-Follow Steps.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invalid-update-file-signatures-on-winoses/"><u>Addressing Invalid Update File Signatures on WinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-improve-your-gaming-experience-on-a-windows-11-pc/"><u>7 Ways to Improve Your Gaming Experience on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-close-examination-of-9-key-factors-that-advantage-pcs/"><u>A Close Examination of 9 Key Factors That Advantage PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-range-of-fb-video-width-height-ratios/"><u>[Updated] 2024 Approved  Range of FB Video Width-Height Ratios</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-perfect-pixels-selecting-best-cameras-for-yt/"><u>[New] Perfect Pixels  Selecting Best Cameras For YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359918304-error-handling-strategies/"><u>Error Handling Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-overcoming-cannot-find-gpeditmsc/"><u>A Step-by-Step Guide to Overcoming Cannot Find Gpedit.msc</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-resolving-msvcr110dll-lack/"><u>Addressing and Resolving MSVCR110.dll Lack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-precise-methods-to-resolve-onedrive-errors/"><u>6 Precise Methods to Resolve OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-enabling-imessage-on-non-ios-devices/"><u>A Deep Dive Into Enabling iMessage on Non-iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-archiving-feature/"><u>Activating Windows 11'S Archiving Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373458449-learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719314760975-home-run-your-gptclone-on-windows-free-and-easy-with-gpt4all/"><u>Home-Run Your GPTClone on Windows – Free & Easy with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-way-through-windows-with-mouseclicklock-techniques/"><u>Ace Your Way Through Windows with MouseClickLock Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-transformative-tiktok-techniques-for-business-expansion/"><u>[Updated] Transformative TikTok Techniques for Business Expansion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-winning-strategy-for-moving-software-into-the-future-of-windows-11/"><u>A Winning Strategy for Moving Software Into the Future of Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essence-of-the-apple-m1-a-technological-marvel/"><u>2024 Approved  The Essence of the Apple M1  A Technological Marvel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-reasons-why-windows-11-is-better-than-macos/"><u>6 Reasons Why Windows 11 Is Better Than macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-windows-update-error-0x800f080a/"><u>6 Ways to Fix the Windows Update Error 0X800f080a</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-directories-to-w11s-right-click-menu-steps/"><u>Adding Directories to W11's Right-Click Menu Steps</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-from-apple-iphone-12-pro-max-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons From Apple iPhone 12 Pro Max? Find the Best Solution Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-system-insights-step-by-step/"><u>Accessing Windows System Insights Step-by-Step</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-using-dism-on-win11-systems/"><u>A Comprehensive Guide to Using Dism on Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-gmaps-installation-on-pc/"><u>A Step-by-Step Approach to GMaps Installation on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-htc-u23-pro-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive HTC U23 Pro Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-windows-11-collects-your-data/"><u>5 Ways Windows 11 Collects Your Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-anywhere-unveiling-gaming-data-in-windows/"><u>Access Anywhere: Unveiling Gaming Data in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-beginners-guide-to-using-windows-canary/"><u>A Step-by-Step Beginner’s Guide to Using Windows' Canary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-access-the-startup-folder-in-windows/"><u>5 Ways to Access the Startup Folder in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-max-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS Max with IMEI Code?</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-elite-fidelity-desktop-and-online-upconversion/"><u>[New] 2024 Approved  Elite Fidelity  Desktop & Online Upconversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-the-facebook-video-size-handbook-aspect-ratios-explained/"><u>In 2024, The Facebook Video Size Handbook Aspect Ratios Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/step-by-step-guide-to-reclaiming-lost-facebook-moments/"><u>Step-by-Step Guide to Reclaiming Lost Facebook Moments</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-perfecting-video-quality-on-zoom-through-filters-use/"><u>[New] In 2024, Perfecting Video Quality on Zoom Through Filters Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382715644-unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-the-quiet-zone-mastering-the-craft-of-muting-unwanted-web-based-sounds/"><u>Updated In 2024, The Quiet Zone Mastering the Craft of Muting Unwanted Web-Based Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-things-you-should-avoid-doing-on-windows-11/"><u>8 Things You Should Avoid Doing on Windows 11</u></a></li>
</ul></div>
