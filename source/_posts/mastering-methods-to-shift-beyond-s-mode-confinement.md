---
title: Mastering Methods to Shift Beyond S Mode Confinement
date: 2024-12-21T03:03:29.785Z
updated: 2024-12-21T19:57:24.327Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Methods to Shift Beyond S Mode Confinement
excerpt: This Article Describes Mastering Methods to Shift Beyond S Mode Confinement
keywords: Mastering SEO Techniques,Overcoming S Mode Limits,Advanced Search Optimization,Strategies for Improved Visibility,Navigating Out-of-Bounds States,Elevate SEO Practices,Beyond Confinement Tactics
thumbnail: https://thmb.techidaily.com/c48a785cefdb0843c6e76d439ab755593afd7522af39269117f83ccabe84316f.png
---

## Mastering Methods to Shift Beyond S Mode Confinement

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click on the **Profile >** **Sign in** \> **Select** your Microsoft Account and click on **Continue**.  
![Sign in to Microsoft Store-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/sign-in-to-microsoft-store-1.jpg)
6. Enter your PC **PIN** and then complete the login process.
7. Retry switching out of S mode.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Reset the Microsoft Store

 The Microsoft Store app can stop working correctly due to corrupt cache files. So, you must [reset the Microsoft Store via Settings or the Terminal](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/).

## 8\. Re-register All System Apps

 If resetting the Microsoft Store doesn’t resolve the issue, you must re-register all system apps, including the Microsoft Store. Here’s how to do it:

1. Open the [PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/).
2. Type the following command and press **Enter** to execute it:  
`Get-AppXPackage -AllUsers |Where-Object {$_.InstallLocation -like "SystemApps"} | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![Reset All System Apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/reset-all-system-apps.jpg)
3. Closethe Command Prompt windows and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-step-by-step-process-for-integrating-music-in-facebook-videos/"><u>[Updated] In 2024, Step-by-Step Process for Integrating Music in Facebook Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-tiktok-mastery-securing-your-content-with-android-and-ios-tools-for-2024/"><u>[Updated] TikTok Mastery Securing Your Content with Android & iOS Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-open-the-authorization-manager-in-windows-11/"><u>How to Open the Authorization Manager in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-6-plus-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 6 Plus without Passcode</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-infinix-note-30i-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Infinix Note 30i FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-obstacles-reinstate-mspm-in-windows-7/"><u>Overcome Obstacles: Reinstate MSPM in Windows 7</u></a></li>
<li><a href="https://vp-tips.techidaily.com/resonant-rhythms-where-to-download-classical-ringtones/"><u>Resonant Rhythms Where to Download Classical Ringtones</u></a></li>
<li><a href="https://discover-blog.techidaily.com/simplify-scanning-on-iphoneipad-add-new-abbyy-siri-shortcuts-for-textgrabber-and-finescanner-applications/"><u>Simplify Scanning on iPhone/iPad - Add New ABBYY Siri Shortcuts for TextGrabber and FineScanner Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slow-sell-of-windows-11-why-users-prefer-the-oldie/"><u>Slow Sell of Windows 11: Why Users Prefer the Oldie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-reconnecting-malwarebytes-services-in-windows-11-os/"><u>Steps for Reconnecting Malwarebytes Services in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-arrange-bunched-up-taskbar-icons/"><u>Strategies to Arrange Bunched-Up Taskbar Icons</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-complexity-how-transfer-learning-simplifies-ai/"><u>Unraveling Complexity: How Transfer Learning Simplifies AI</u></a></li>
</ul></div>

