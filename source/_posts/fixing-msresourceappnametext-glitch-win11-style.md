---
title: "Fixing 'MsResource:AppName/Text Glitch', Win11 Style"
date: 2024-06-25T16:28:19.958Z
updated: 2024-06-26T16:28:19.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing 'MsResource:AppName/Text Glitch', Win11 Style"
excerpt: "This Article Describes Fixing 'MsResource:AppName/Text Glitch', Win11 Style"
keywords: MsResource Text Fix,AppName Win11 Text Issue,Win11 Resource Glitch Resolve,Text Bug in Win11 Resources,Addressing Win11 MsResource Errors,Win11 App Name Text Fix,Correction of 'MsResource' Glitches,Win11 MsResource Text Fix,Glitch,Solve 'MsResource' Text Issue in Win11,Quick Repair Win11 Resource Errors,Fix MsResource Internal Problems Windows 11,Address 'MsResource' Glitch in Win11,Remedy Text Issues with MsResource Win11
thumbnail: https://thmb.techidaily.com/fa44e4072bbca8fffcfb2ff9a75f7dc0fad47a3e60bc93d2b05739fc57c6b83c.jpg
---

## Fixing 'MsResource:AppName/Text Glitch', Win11 Style

 If you have performed an upgrade recently and noticed a weird "ms-resource:Appname/text" entry in the Start Menu, you are not alone. You may also encounter this error when opening a setting or app.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

## 1\. How to Fix the "ms-resource:Appname/Text" Error in the Start Menu

 You can remove the "ms-resource:Appname/Text" entry from the Start Menu by removing the affected application package using PowerShell. Additionally, you can kill the StartMenuExperienceHost.exe process in Task Manager to restart the service.

 Before attempting to remove the app, package, and restart the services, check if you have any Windows updates pending. If you are running a fresh install, try to install all the pending Windows updates. These updates often include bug fixes and may be the only thing you need to do to fix this issue.

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 To check and install Windows updates:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Windows Update** tab.
3. Click on **Check of updates**. Continue to download and install all pending updates.
4. Restart your computer to apply the updates and check if the issue is resolved.

 If the issue persists, you can use PowerShell to remove the affected app package and then restart the associated services to fix the problem.

 To remove the "ms-resource:Appname/Text" entry from the Start Menu:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows** **PowerShell** and select **Run as administrator**.  
![remove holographicsfirstrun app powershell windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-holographicsfirstrun-app-powershell-windows.jpg)
3. In the PowerShell window, type the following command and press **Enter**:  
`Get-AppxPackage -all *HolographicFirstRun* | Remove-AppPackage -AllUsers`

 Once you've run the command, be sure to restart your computer.

1. After the computer restarts, [open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/).
2. Next, open the **Details** tab in Task Manager. On Windows 11, click the three horizontal lines icon to access the details tab.
3. Now you need to locate both **StartMenuExperienceHost.exe** and **Explorer** **.exe**. On Windows 11, you can use the search feature in **Task Manager** to locate the processes.  
![end start menu experience host task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/end-start-menu-experience-host-task-manager.jpg)
4. Right-click on each process and **End Task**.
5. In Task Manager, click **Run new task**. On Windows 10 and older versions, click **File** and select **Run new task**.  
![run new task open tempstate folder file explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-new-task-open-tempstate-folder-file-explorer.jpg)
6. In the **Create new task** dialog, type the following path and click the **Browse** button.  
`%localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy`
7. In the File Explorer window, delete the **TempState** folder.
8. Go back to Task Manager, and click **Run new task**.
9. Type **explorer.exe** and select the **Create this task with administrative privileges** option.

 Once done, give your PC another restart.

## 2\. Re-Register Your Microsoft Store Apps

 You can [re-register Microsoft Store apps using PowerShell](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) to stop the error appearing when using Microsoft apps. Doing so should remove any leftover entries showing up in the Start Menu after the update.

 Wait for the process to complete. This may take a few minutes as the command will try to re-register all the apps, including existing ones. Once the process is complete, restart your computer and check for any improvements.

## 3\. Check the Microsoft Store for App Updates

 You may see the "ms-resource:Appname/Text" entry if Windows attempted an unsuccessful app installation. To fix the issue, check if an update exists for the app in the Microsoft Store.

 To determine the app name click on the app entry and check if you can find any information about the app. If not, right-click on the app entry in the **Start Menu** and select **Open File Location**.

![view application folder windows 11 run shell apps folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/view-application-folder-windows-11-run-shell-apps-folder.jpg)

 Alternatively, you can view the application directory to view the installed apps. Press **Win + R** to open Run, type **shell:appsfolder**, and click **OK**. It will open the **Applications** folder. Go through the apps to see if you can locate an app named **ms-resource:Appname/Text** or similar to the entry in the Start Menu.

 Once you have the app name, open the Microsoft Store. Search for the app and check if an update exists. Click **Update** to download and install the update. Once installed, restart your computer and check for any improvements.

## What if the "Ms-resource:Appname/Text" Error Appears When Launching an App?

 At times, you may encounter this error when opening a built-in Microsoft Store app. In this instance, you can run the Microsoft Store apps troubleshooter to fix the issue. Here are a few additional troubleshooting steps to fix this error when launching an app.

## 4\. Run the Microsoft Store Apps Troubleshooter ![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-run-button-for-the-app-troubleshooter.jpg)

 You can use the built-in Microsoft Store Apps troubleshooter to fix issues with the store apps. Here’s how to do it.

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.
3. Next, click on **Other troubleshooters**.
4. Click the **Run** button for **Windows Store Apps**. Wait for the troubleshooter to launch and follow the on-screen instructions. It will scan your system against the common Microsoft Store app issues. Apply any recommended fixes and restart your computer to see if the issue is resolved.

 If you don’t see a Windows Store App troubleshooter option, you are likely running a newer version of the OS without this option. In this instance, try to repair the Microsoft Store app.

## 5\. Repair the Microsoft Store App ![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 If the Windows Store Apps troubleshooter is missing or didn’t help, try to repair the Microsoft Store App. You can use the built-in repair option to find and fix common issues with the official app store.

 To repair the Microsoft Store app:

1. Press **Win + I** to open the **Settings** app.
2. Open the **Apps** tab and click on **Installed Apps.**
3. Locate and click the **three-dots** menu beside the **Microsoft Store** app.
4. Select **Advanced Options**.
5. Scroll down to the **Reset** section.
6. Click the **Repair** button, wait for the process to complete, and show a checkmark. If the repair is successful, restart your computer.

### Reset the Microsoft Store App

 In addition to performing a repair, you can also reset the Microsoft Store app to resolve common issues with the store apps. You can perform a reset from the Advanced Options section. Before that, run the wsreset.exe tool to clear the store cache to see if that helps.

 To reset the Microsoft Store App cache:

![wsreset.exe command in the Run tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsreset-exe-command.jpg)

1. Press **Win + R** to open the **Run** dialog.
2. Type **wsreset.exe** and click **OK**.

 Still not resolved? Try to [perform a Microsoft Store reset](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). Doing so will delete all app data, and you may need to sign in to your Microsoft account again.

## 6\. Other Troubleshooting Steps You Can Try

 If the issue persists, here are a few additional troubleshooting steps you can follow:

1. **Create a new user account** – Try to [create a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to see if the error exists in the new account. This is a handy workaround for a newly set up Windows computer.
2. **Perform a repair reinstall of Windows 11** – You can reinstall [Windows 11 without deleting your apps and files](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). This is an upgrade reinstall and should fix any issues triggered due to issues with the system files.
3. **Perform a reset** – If an in-place upgrade doesn’t help, consider [performing a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). You can perform a complete reset while choosing to keep your files, but all your apps will be removed.
4. **Clean install** – [Performing a Windows clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) will erase everything on your computer and reinstall Windows 11 from scratch. Make sure to back up important data before attempting a clean install.

## Fixing the "ms-resource:Appname/Text" Error in Windows 11

 Often this entry in the start menu is a ghost entry from an unsuccessful or leftover installation of a Microsoft app. To remove the entry or restore the app, you can re-register the Microsoft app, remove the affected app package or run the Windows Store Apps Troubleshooter.

 If the issue persists, an in-place upgrade, factory reset, or a clean install may be necessary to resolve the issue. This is a time-consuming process, and you may need to set up your computer from scratch.

 This entry in the Start Menu is a trace for a built-in app that has been removed in the successive upgrade. Depending on where you are seeing the error, follow the steps in the article below to resolve this error on your computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-computers-top-8-windows-tricks/"><u>Reinvigorating Computers: Top 8 Windows Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-printer-connectivity-in-windows-os/"><u>Restoring Printer Connectivity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-system-performance-via-alomware-settings-utility/"><u>Enhance System Performance via AlomWare Settings Utility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-digital-life-learn-these-5-essential-window-folder-tricks/"><u>Simplify Your Digital Life: Learn These 5 Essential Window Folder Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-copy-paste-in-chromeedgefirefox-windows/"><u>Fixing Non-Functional Copy-Paste in Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-badge-indicators-on-taskbars/"><u>Restoring Badge Indicators on Taskbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-latency-strategies-to-fasten-windows-discord/"><u>Lowering Latency: Strategies to Fasten Windows Discord</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streaming-showdown-best-channels-for-your-audience/"><u>In 2024, Streaming Showdown  Best Channels for Your Audience</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-easy-effective-strategy-immediate-clearance-of-unwanted-youtube-comments/"><u>[New] 2024 Approved  Easy, Effective Strategy  Immediate Clearance of Unwanted YouTube Comments</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essence-of-elongated-images-through-iphone-writings/"><u>2024 Approved  The Essence of Elongated Images Through iPhone’ Writings</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-samsung-galaxy-a25-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Samsung Galaxy A25 5G</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-efficient-techniques-for-personalizing-and-updating-social-media-coverage/"><u>[New] 2024 Approved  Efficient Techniques for Personalizing and Updating Social Media Coverage</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-from-iphone-7-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue From iPhone 7</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-pixel-perfect-preservation-the-best-practices-of-recording-games/"><u>[Updated] 2024 Approved  Pixel-Perfect Preservation  The Best Practices of Recording Games</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-exclusive-top-5-list-of-fb-video-downloaders-for-2024/"><u>[New] Exclusive TOP 5 List of FB Video Downloaders for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>