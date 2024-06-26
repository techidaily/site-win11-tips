---
title: Exclusive Removal of Win11's Official Store
date: 2024-06-25T16:48:11.598Z
updated: 2024-06-26T16:48:11.598Z
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
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-speed-up-system-restart-with-windows-11/"><u>Tricks to Speed Up System Restart with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-game-learning-windows-shorthand/"><u>Elevate Your Computer Game: Learning Windows Shorthand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-utorrent-installation-hiccups-in-windows-78/"><u>Handling uTorrent Installation Hiccups in Windows 7/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-innovators-guide-leveraging-windows-11-widgets/"><u>Tech Innovators Guide: Leveraging Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-1011-zoom-glitch-1132/"><u>Overcoming Windows 10/11 Zoom Glitch 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-email-setup-connecting-your-gmail-to-outlook-windows/"><u>Simplifying Email Setup: Connecting Your Gmail to Outlook Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-nokia-g310-by-drfone-android/"><u>How to Bypass FRP from Nokia G310?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-oppo-a18-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Oppo A18 Phone Now with These Tips</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-techs-time-capsule-a-screen-review/"><u>[Updated] Tech's Time Capsule  A Screen Review</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-xiaomi-redmi-k70-pro-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Xiaomi Redmi K70 Pro? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-prime-methods-to-speed-up-or-slow-down-songs-on-spotify/"><u>[New] Prime Methods to Speed Up or Slow Down Songs on Spotify</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-virtual-gathering-film-cutter/"><u>[New] 2024 Approved  Virtual Gathering Film Cutter</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-neon-font-generators-create-stunning-text-in-minutes/"><u>Best Neon Font Generators Create Stunning Text in Minutes</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-simplified-sequences-the-top-tiktok-dances/"><u>[New] Simplified Sequences  The Top TikTok Dances</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-harnessing-the-power-of-influencers-in-tiktok-marketing/"><u>[New] 2024 Approved  Harnessing the Power of Influencers in TikTok Marketing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-s17e-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo S17e</u></a></li>
</ul></div>
