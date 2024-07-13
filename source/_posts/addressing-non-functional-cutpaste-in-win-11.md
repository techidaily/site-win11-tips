---
title: Addressing Non-Functional Cut/Paste in Win 11
date: 2024-07-12T17:57:48.357Z
updated: 2024-07-13T17:57:48.357Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Non-Functional Cut/Paste in Win 11
excerpt: This Article Describes Addressing Non-Functional Cut/Paste in Win 11
keywords: Win 11 Clipboard Issues,Fix Paste Problems Win 11,Win 11 Copy Error,Non-Functional Cut Windows,Win 11 Unstable Copy/Paste,Correcting Ctrl+C/V in Win 11,Resolve Win 11 Paste Faults
thumbnail: https://thmb.techidaily.com/9083264d1e9ed82c0a8d3858961cbcacf8dd6e0e896428761bc70aaa3b066e45.jpg
---

## Addressing Non-Functional Cut/Paste in Win 11

### Quick Links

* [Clear Clipboard Data](#clear-clipboard-data)
* [Perform a Clean Boot](#perform-a-clean-boot)
* [Update Your Windows](#update-your-windows)
* [Restart File Explorer](#restart-file-explorer)
* [Run the Keyboard Troubleshooter](#run-the-keyboard-troubleshooter)
* [Reset the rdpclip.exe Process](#reset-the-rdpclip-exe-process)
* [Check Your Keyboard for Hardware Issues](#check-your-keyboard-for-hardware-issues)
* [Run the System File Checker](#run-the-system-file-checker)
* [Create a New Local User Account](#create-a-new-local-user-account)

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.


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
<li><a href="https://ai-vdieo-software.techidaily.com/new-get-ahead-with-fcpx-the-best-online-tutorials-and-guides/"><u>New Get Ahead with FCPX The Best Online Tutorials and Guides</u></a></li>
<li><a href="https://extra-hints.techidaily.com/brief-path-to-past-posts-reinstating-reddit-removals-quickly-for-2024/"><u>Brief Path to Past Posts  Reinstating Reddit Removals Quickly for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/master-your-snapchats-the-top-6-editing-apps-for-both-devices-for-2024/"><u>Master Your Snapchats  The Top 6 Editing Apps for Both Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-workshop-generating-and-deciphering-system-insights/"><u>The Windows Workshop: Generating & Deciphering System Insights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-access-to-top-7-highly-rated-cost-free-pc-passwords/"><u>Exclusive Access to Top 7 Highly Rated, Cost-Free PC Passwords</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-christmas-ify-your-windows-11/"><u>7 Ways to Christmas-Ify Your Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-control-external-hard-drive-usage/"><u>Effective Strategies to Control External Hard Drive Usage</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-lag-in-civilization-v-pc/"><u>Addressing Lag in Civilization V PC</u></a></li>
<li><a href="https://network-issues.techidaily.com/solved-call-of-duty-cold-war-not-connecting-to-online-services-2024/"><u>[SOLVED] Call of Duty Cold War Not Connecting to Online Services 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-reducing-decibels-gradually-in-fl/"><u>2024 Approved  Reducing Decibels Gradually in FL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-enabledisable-bing-ai-on-windows-11-search-bar/"><u>Turbo Enable/Disable: Bing AI on Windows 11 Search Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-evolutionary-leap-with-ai-copilot-in-windows-11-life/"><u>The Evolutionary Leap with AI Copilot in Windows 11 Life</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/starting-up-in-periscope-tips-to-launch-your-wealth-journey-for-2024/"><u>Starting Up in Periscope  Tips to Launch Your Wealth Journey for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-steps-to-disable-automatic-updates-in-windows/"><u>5 Steps To Disable Automatic Updates in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-complete-blueprint-incorporating-audio-in-kinemaster/"><u>New 2024 Approved The Complete Blueprint Incorporating Audio in KineMaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-routines-to-pause-windows-and-office-software-updates/"><u>4 Routines to Pause Windows & Office Software Updates</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-prime-bot-squadrons-on-discord-platform-for-2024/"><u>[Updated] Prime Bot Squadrons on Discord Platform for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-best-online-locations-to-find-and-download-open-source-closing-music/"><u>In 2024, Best Online Locations to Find and Download Open-Source Closing Music</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleash-the-potential-elevating-your-tiktok-unboxing-contents-like-count/"><u>In 2024, Unleash the Potential  Elevating Your TikTok Unboxing Content's Like Count</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-identifying-the-perfect-hashtag-for-your-tiktok-profile-for-2024/"><u>[New] Identifying the Perfect Hashtag for Your TikTok Profile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10s-guide-to-effortlessly-merge-data/"><u>Win 10'S Guide to Effortlessly Merge Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-troubled-tracker-fixes-for-frozen-torrents/"><u>Tackling the Troubled Tracker: Fixes for Frozen Torrents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-behind-windows-11s-disappearing-thumbnail-issue-fixes-here/"><u>What's Behind Windows 11'S Disappearing Thumbnail Issue? Fixes Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-right-video-coding-technique-for-win-os-users/"><u>Deciphering the Right Video Coding Technique for Win OS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-26/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncharted-errors-the-8-most-crucial-mistakes-for-new-windows-11-users/"><u>Uncharted Errors: The 8 Most Crucial Mistakes for New Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/too-much-glitches-handle-deps-before-virtualbox-on-win/"><u>Too Much Glitches? Handle Deps Before VirtualBox on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719307808288-tackling-windows-glitches-find-solutions-now/"><u>Tackling Windows Glitches: Find Solutions Now!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-honor-100-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Honor 100</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-window-lock-out-duration-in-windows/"><u>Customize Window Lock-Out Duration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-how-to-disguise-taskbar-on-win-11/"><u>Expert Guide: How to Disguise Taskbar on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-tutorials-for-new-folder-navigation-in-win11/"><u>Tactical Tutorials for New Folder Navigation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-users-with-erratic-gesture-inputs-in-windows/"><u>Assisting Users with Erratic Gesture Inputs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-troubleshooting-winning-against-camera-app-failures/"><u>Effortless Troubleshooting: Winning Against Camera App Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dims-masterclass-restoring-and-repairing-win11-images/"><u>DIMS Masterclass: Restoring and Repairing Win11 Images</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-the-art-of-audio-integration-on-social-media-videos/"><u>Mastering the Art of Audio Integration on Social Media Videos</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-dissecting-iconic-discord-emoticons-and-their-designers/"><u>2024 Approved  Dissecting Iconic Discord Emoticons and Their Designers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-use-b-roll-footage-for-2024/"><u>How to Use B Roll Footage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-powershell-errors-with-script-enablement-fixes/"><u>Troubleshooting PowerShell Errors with Script Enablement Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-list-of-public-domain-picture-banks/"><u>Ultimate List of Public Domain Picture Banks</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-nvidia-method-to-perfect-gaming-replays-for-2024/"><u>The NVIDIA Method to Perfect Gaming Replays for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-initiate-seamless-gaming-streams-mastering-obs-recording-for-2024/"><u>[Updated] Initiate Seamless Gaming Streams  Mastering OBS Recording for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-issues-of-iphone-14-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System Issues of iPhone 14? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-isolating-and-fixing-unilateral-audio-malfunction/"><u>Win10: Isolating and Fixing Unilateral Audio Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-windows-print-management-tool-and-how-do-you-access-it/"><u>What Is the Windows Print Management Tool, and How Do You Access It?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-word-2007-electronically-by-ldigisigner-sign-a-word-sign-a-word/"><u>How do i sign a Word 2007 electronically</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-navigating-the-world-of-instagram-puzzles-for-peak-performance/"><u>[Updated] In 2024, Navigating the World of Instagram Puzzles for Peak Performance</u></a></li>
</ul></div>
