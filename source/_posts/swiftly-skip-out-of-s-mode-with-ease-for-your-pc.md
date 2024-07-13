---
title: Swiftly Skip Out of S Mode with Ease for Your PC
date: 2024-07-12T17:08:17.792Z
updated: 2024-07-13T17:08:17.792Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Skip Out of S Mode with Ease for Your PC
excerpt: This Article Describes Swiftly Skip Out of S Mode with Ease for Your PC
keywords: Swift Switch to Windows 10 (Easy),Skip Modes, Fast Exit,Ease Out of S Mode,Quick S Mode Unlock PC,Simplify Windows Upgrade,Exit S Mode Swiftly,Effortless Windows 10 Switch
thumbnail: https://thmb.techidaily.com/749e7224dc77351db9654f3d5b625401a4538e3e09d897a36274e3de6aadbd39.jpg
---

## Swiftly Skip Out of S Mode with Ease for Your PC

### Key Takeaways

* If you cannot switch out of Windows S Mode, it may be due to issues with Microsoft servers.
* Restart the wauserv service in the Task Manager to fix any glitches with the Microsoft Update service, which handles update-related tasks on your PC.
* Try signing out of the Microsoft Store and signing back in before attempting to exit Windows S Mode again.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

 Windows S Mode is a restricted version of Windows 11 and 10 where you can only install apps from the Microsoft Store, cannot access the Registry or the Group Policy Editor, and are stuck with Edge and Bing as the default browser and search engine. To install an app unavailable in the Microsoft Store, you must get out of Windows S Mode and upgrade. But sometimes, you can't switch out of the S mode because of an error.

 Try these fixes to get out of the Windows S mode for good.

## 1\. Check Microsoft Servers Status

[Windows S mode has its merits and drawbacks](https://www.makeuseof.com/windows-11-s-mode-guide/); the only way to exit it is via the Microsoft Store. But if Microsoft Servers are down due to any issues, you will face issues when trying to get out of the S mode. So, check the official [Microsoft Service status](https://admin.microsoft.com/servicestatus) website or Microsoft Store's [X page](https://twitter.com/MicrosoftStore) for outage reports.

 You can also check out third-party websites like [Down Detector](https://downdetector.com/). In such a case, patiently wait while Microsoft fixes the issue. If you use a [VPN service](https://www.makeuseof.com/tag/5-great-free-vpn-services-compared-which-is-fastest/) on your PC, temporarily disconnect from it and then retry exiting the S mode.

## 2\. Check the Microsoft Store Install Service

 Microsoft Update service handles all the update-related tasks on your PC. With any glitch, you must restart it to get it working again.

1. Press **Ctrl + Shift + Esc** to open Task Manger.
2. Click on **Services**.
3. Find the **wauserv** service in the list and right-click on it. Select **Restart**.  
![Restart the Windows Update service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/restart-the-windows-update-service.jpg)
4. Exitthe Task Manager.

## 3\. Sign out and Sign in Again

 You can try signing out of the Microsoft Store and then signing back in. After that, you can reattempt exiting the S mode.

1. Launch Microsoft Store.
2. Click on **Profile >** **Sign out**.
3. ![Sign out of Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-out-of-microsoft-store-1.jpg)
4. Close and relaunch the Microsoft Store app.
5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

## 4\. Update All Store Apps

 Outdated apps, including the Microsoft Store, can pose issues while trying to leave S mode. You must update all of them using the Microsoft Store update section. Even the update for the Microsoft Store app is available here.

1. Launch the Microsoft Store app.
2. Navigate to the bottom left area and click on the **Library** icon.
3. Click on the **Get updates** button to check for all the available updates.
4. Click on the **Update all** button.
5. Wait for the updates to install, and then close the Microsoft Store app.
6. Restartyour PC.

## 5\. Set the Correct Date and Time

 Incorrect date and time settings on your PC can cause problems while installing or removing Windows features. So, you must manually sync the date and time settings with Windows servers.

1. Go to the system tray notifications area and right-click the **Date and time** icon.
2. Click on the **Adjust date and time** option.
3. Scroll down to the **Additional settings** section and click the **Sync now** button.  
![Sync the Date and Time](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sync-the-date-and-time.jpg)
4. Closethe Settings app.

## 6\. Rename the SoftwareDistribuiton Folder

 The SoftwareDistribution folder contains temporary Windows update files. Rename the folder if there are issues with the app or Windows updates. Windows will recreate the folder when you try to check and download the updates.

1. Open the [Command Prompt window as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type the following commands and press **Enter** to stop the Windows Update Service and Background Intelligent Transfer Service:  
`net stop wuauserv  
 net stop bits`
3. Execute the following command to rename the SoftwareDistribution folder:  
`rename %windir%\SoftwareDistribution SoftwareDistribution.bak`
4. Execute the following commands to restart the Windows Update Service and Background Intelligent Transfer Service:  
`net start wuauserv  
 net start bits`  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/rename-the-softwaredistribution-folder.jpg)
5. Closethe Command Prompt window.
6. Restartyour PC.

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

## 9\. Do an In-place Upgrade

 You can [do an In-place upgrade on your Windows PC](https://www.makeuseof.com/in-place-upgrade-windows-11/) to get out of the S mode. It is better than resetting your Windows PC because an In-place upgrade preserves all your files, apps, and data stored in the C drive.

## Get Rid of Windows S Mode

 It's not difficult to solve why you can't exit the S mode on your Windows PC. Check Microsoft services, update the Microsoft Store app, and sign out and sign in again. Then, rename the SoftwareDistribution folder, reset all system apps, and do an In-place Upgrade to fix the issue if everything fails.

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
<li><a href="https://win11-tips.techidaily.com/asus-vivobook-s-15-a-comprehensive-compromise-of-design/"><u>ASUS Vivobook S 15 - A Comprehensive Compromise of Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chatgpt-launch-procedure-for-windows-users/"><u>ChatGPT Launch Procedure for Windows Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-premiere-pro-transition-plugins-expert-picks/"><u>Updated Best Premiere Pro Transition Plugins Expert Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-stuck-function-keys-on-windows-11-desktop/"><u>Address: Stuck Function Keys on Windows 11 Desktop</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-extract-youtube-srt-effortlessly-in-3-ways-for-2024/"><u>How to Extract YouTube SRT Effortlessly in 3 Ways for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-which-video-editor-reigns-supreme-final-cut-pro-or-lumafusion-in-2024/"><u>Updated Which Video Editor Reigns Supreme Final Cut Pro or LumaFusion, In 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/best-way-to-color-grading-and-color-correction-in-filmora/"><u>Best Way To Color Grading & Color Correction in Filmora</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/jumpstart-your-snapchat-learn-to-create-top-boomers-for-2024/"><u>Jumpstart Your Snapchat  Learn to Create Top Boomers for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-deciding-on-your-video-recorder-heroes-obs-or-bandicam-for-2024/"><u>[Updated] Deciding on Your Video Recorder Heroes  OBS or Bandicam for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamlined-file-sharing-from-your-computer-to-iphone/"><u>Streamlined File Sharing  From Your Computer To iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-customized-cmd-shortcuts-and-windows/"><u>Boost Efficiency with Customized Cmd Shortcuts and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-saving-techniques-for-a-functional-windows-time-service/"><u>Time-Saving Techniques for a Functional Windows Time Service</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-ultimate-guide-to-splitting-videos-in-windows-live-movie-maker-2023-edition-for-2024/"><u>The Ultimate Guide to Splitting Videos in Windows Live Movie Maker (2023 Edition) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winservicesexe-explained-troubleshooting-guide/"><u>WinServices.exe Explained: Troubleshooting Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-guide-to-preferred-applications-vtubers-sonic-transformation-journey/"><u>[New] Guide to Preferred Applications  Vtuber's Sonic Transformation Journey</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-13c-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi 13C 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-visibility-of-your-notebooks-on-win/"><u>Ensuring Top-Visibility of Your Notebooks on Win</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-free-converters-at-your-fingertenaside-download-and-enjoy-videos-anywhere-for-2024/"><u>[New] Free Converters at Your Fingertenaside  Download & Enjoy Videos Anywhere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-10-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 10 & 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-tiktok-tricks-for-striking-visual-results/"><u>[New] TikTok Tricks for Striking Visual Results</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on ZTE Nubia Z60 Ultra? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-sky-high-improvement-ultimate-video-rescale/"><u>[New] Sky-High Improvement  Ultimate Video Rescale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-analysis-of-windows-lav-filter-usage-and-outputs/"><u>A Comprehensive Analysis of Windows LAV Filter Usage and Outputs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-the-heat-cutting-down-vanguard-writes-on-your-computer/"><u>Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-non-starting-adobe-photoshopping-in-windows-11/"><u>How to Enable Non-Starting Adobe Photoshopping in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-engaging-windows-11s-calculator/"><u>The Essential Guide to Engaging Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deskanywhere-failures-in-windows-11/"><u>Troubleshooting DeskAnywhere Failures in WIndows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-assessment-made-easy/"><u>Windows Memory Assessment Made Easy</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-3-safe-strategies-for-converting-youtube-videos-into-mp3-files-for-2024/"><u>Top 3 Safe Strategies for Converting YouTube Videos Into MP3 Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-defenders-error-0x80004004/"><u>Troubleshooting Defender's Error 0X80004004</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-talk-the-key-to-a-visible-mouse-indicator-in-windows-os/"><u>Tech Talk: The Key to a Visible Mouse Indicator in Windows OS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-leading-edge-social-media-movie-batch/"><u>[New] 2024 Approved  Leading Edge  Social Media Movie Batch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-tackle-the-icloud-install-issue-on-windows/"><u>Comprehensively Tackle the iCloud Install Issue on Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-free-and-fabulous-top-10-mp4-video-editors/"><u>Updated In 2024, Free and Fabulous Top 10 MP4 Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-stuck-photoshopping-in-windows-11-versions-2023/"><u>Unfreezing Stuck Photoshopping in Windows 11, Versions 2023</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-extensive-appraisal-a-look-into-bublcam-360-for-2024/"><u>[Updated] Extensive Appraisal  A Look Into Bublcam 360 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-annoyance-of-a-never-ending-update-loop/"><u>Avoid the Annoyance of a Never-Ending Update Loop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncompromised-security-in-windows-app-downloads/"><u>Uncompromised Security in Windows App Downloads</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-simplified-path-to-mastery-in-using-cc-licenses/"><u>In 2024, Simplified Path to Mastery in Using CC Licenses</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-14-plus-in-different-conditionsin-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone 14 Plus In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/aximizing-your-youtube-click-through-rate-upload-schedule-insights/"><u>[New] Maximizing Your YouTube Click-Through Rate  Upload Schedule Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-efficient-bluescreenview-use/"><u>Essential Tips for Efficient BlueScreenView Use</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-top-qp-value-enhancing-gradual-movement-vids/"><u>[Updated] Top QP Value Enhancing Gradual Movement Vids</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-drone-racing-all-you-need-to-know-and-5-best-fpv-racing-drones/"><u>[New] Drone Racing  All You Need to Know and 5 Best FPV Racing Drones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-your-preferred-soft-install-tool-on-win-devices/"><u>Finding Your Preferred Soft Install Tool on Win Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-igtv-techniques-seamlessly-transforming-vlogs-for-maximum-views-for-2024/"><u>[Updated] IGTV Techniques  Seamlessly Transforming Vlogs for Maximum Views for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-window-11-notebook-space-you-love/"><u>Creating a Window 11 Notebook Space You Love</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unleash-the-power-of-digital-advertising-with-our-comprehensive-set-of-50-free-youtube-banners/"><u>In 2024, Unleash the Power of Digital Advertising with Our Comprehensive Set of 50 FREE YouTube Banners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-battlenet-speed-fasten-your-windows-pace/"><u>Boosting Battle.net Speed: Fasten Your Windows Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-network-reachable-errors-win/"><u>Eradicating No Network Reachable Errors (WIN)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-post-display-adjustment-in-windows-power-configuration/"><u>Hide Post-Display Adjustment in Windows Power Configuration</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-alternative-views-to-googles-ar-sticker-experience/"><u>2024 Approved  Alternative Views to Google's AR Sticker Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowing-wonderland-personalized-monitor-settings-in-win1011/"><u>Windowing Wonderland: Personalized Monitor Settings in Win10/11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-complete-guide-to-make-an-intro-video/"><u>Updated Complete Guide to Make an Intro Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-ways-the-best-fixes-to-skip-the-long-wait-in-install-steps/"><u>Winning Ways: The Best Fixes to Skip the Long Wait in Install Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-selection-of-4-webp-viewer-software/"><u>The Ultimate Selection of 4 WebP Viewer Software</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-dialing-up-the-success-on-tiktok-a-strategy-guide-for-higher-interactions-for-2024/"><u>[Updated] Dialing up the Success on TikTok  A Strategy Guide for Higher Interactions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-selecting-the-best-win-notebook/"><u>Fundamentals of Selecting the Best Win Notebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-power-of-ping-windows-application-essentials/"><u>Unveiling the Power of Ping: Windows Application Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gaming-unbound-android-in-desktop-windows-with-google-play-service/"><u>Experience Gaming Unbound: Android in Desktop Windows with Google Play Service</u></a></li>
</ul></div>
