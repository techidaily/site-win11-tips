---
title: Correcting Failing Copy Functionality in Windows 11
date: 2024-11-10T18:39:01.793Z
updated: 2024-11-17T18:42:47.496Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failing Copy Functionality in Windows 11
excerpt: This Article Describes Correcting Failing Copy Functionality in Windows 11
keywords: Fix Windows 11 Copy Errors,Resolve Win11 Shell Issue,Stop Copy Failures in Win11,Enhance Windows 11 Clipboard,Correct Copy Function, Win11,Tackle Copy Glitches Win11,Improve Win11 Copy Processing
thumbnail: https://thmb.techidaily.com/6169c8a9aeeb67674aa07a2a9dad06d0ae5fef5e196eb54e46717e8334c8bace.jpg
---

## Correcting Failing Copy Functionality in Windows 11

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094483/7443" target="_top" id="2094483">
  <img src="//a.impactradius-go.com/display-ad/7443-2094483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934292/19272" target="_top" id="1934292">
  <img src="//a.impactradius-go.com/display-ad/19272-1934292" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934292/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1977032">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977032.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977032">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977032.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977032%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977032/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/updated-pinnacle-studios-evaluation-an-in-depth-study-for-2024/"><u>[Updated] Pinnacle Studios Evaluation An In-Depth Study for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-sharpen-the-scene-expert-insights-for-cropping-videos-with-insta-flair/"><u>[Updated] Sharpen the Scene Expert Insights for Cropping Videos with Insta Flair</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/a-comprehensive-guide-to-apple-iphone-7-plus-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>A Comprehensive Guide to Apple iPhone 7 Plus Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/acoustic-amplification-of-social-media-content-on-facebook/"><u>Acoustic Amplification of Social Media Content on Facebook</u></a></li>
<li><a href="https://extra-hints.techidaily.com/blueprinting-a-thrilling-film-flashpoint/"><u>Blueprinting a Thrilling Film Flashpoint</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-guide-to-apple-tvs-latest-model-the-4k-upgrade-with-siri-accessibility/"><u>Comprehensive Guide to Apple TV's Latest Model: The 4K Upgrade with Siri Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dual-virus-scanners-think-twice-windows/"><u>Dual Virus Scanners? Think Twice, Windows!</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-crashes-overcome-modern-warfare-stuttering-issues-on-your-pc/"><u>Fixing Crashes: Overcome 'Modern Warfare' Stuttering Issues on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-zoom-glitches-mitigating-code-1132-in-windows-11/"><u>Fixing Zoom Glitches: Mitigating Code #1132 in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-operatic-install-delays-with-window-wise-fixes/"><u>Mend Your Operatic Install Delays with Window Wise Fixes</u></a></li>
<li><a href="https://blog-min.techidaily.com/strategies-de-recherche-et-reponses-aux-questions-les-plus-courantes-sur-winxvideo-ai/"><u>Stratégies De Recherche Et Réponses Aux Questions Les Plus Courantes Sur WinxVideo AI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-window-bar-timeline-from-85-to-now/"><u>The Window Bar Timeline: From '85 to Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-spotlight-icons-a-guide-to-removal/"><u>Windows 11'S Spotlight Icons: A Guide to Removal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixer-how-to-rectify-unreachable-network-on-windows-11/"><u>Winfixer: How to Rectify Unreachable Network on Windows 11</u></a></li>
</ul></div>

