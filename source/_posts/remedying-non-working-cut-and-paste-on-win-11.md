---
title: Remedying Non-Working Cut & Paste on Win 11
date: 2024-08-16T02:47:42.200Z
updated: 2024-08-17T02:47:42.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying Non-Working Cut & Paste on Win 11
excerpt: This Article Describes Remedying Non-Working Cut & Paste on Win 11
keywords: Fix Clipboard Issue Win 11,Restore Copy/Paste in Windows 11,Solve Pasting Error Wins 11,Correct Copy Failure Windows 11,Adjust Non-Working Paste Function,Enhance Cut & Paste Windows 11,Tweak Win 11 Clipboard Performance
thumbnail: https://thmb.techidaily.com/e46847f4d730c4e71d01b69ffbbf4867ec32380919d66b5ed5af5b5df6bd28ce.jpg
---

## Remedying Non-Working Cut & Paste on Win 11

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
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
3. Next, click on **Other troubleshooters**.  
![Windows 11 Settings showing the Keyboard troubleshooter option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-keyboard-troubleshooter-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
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

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

## 8\. Run the System File Checker

 If your keyboard is working, scan your system for potential system file corruption. The built-in System File Checker and Deployment Image Service and Management tool can find and fix system-level errors.

 To run the System File Checker tool, open the Command Prompt as Administrator and execute the commands:

1. Press the **Win** key, and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator.**  
![Windows 11 Command Prompt running the System File Checker utility.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 9\. Create a New Local User Account

 You can create a new local user account in Windows 11 to check if the problem is limited to the current user. You can [create a new local user account in Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) using the Accounts option in the Settings app.

 Once done, log in to your new local account and try to perform a copy-paste. If it works, you can [try to repair the previous account account](https://www.makeuseof.com/tag/recover-lost-windows-10-user-profile/) or continue to use the new local account.

 If nothing helps, try to repair and install Windows 11\. This involves performing an in-place upgrade to reinstall the OS without affecting your system settings or files.

 Windows 11 comes with an improved clipboard that lets you copy multiple items to the clipboard and paste them as needed. However, the copy and paste function can stop working on your Windows 11 computer.

 This issue can occur because of corrupt system files or temporary glitches with Windows File Explorer. Here are a few troubleshooting steps to help you fix and restore the copy-and-paste functionality in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 3\. Update Your Windows

 If the clipboard issue is caused by a known Windows 11 bug, check the Windows Update tab to see if a new patch or fix is available.

 To install Windows updates:

1. Open **Start** and click on **Settings**.
2. Next, open the **Windows Update** tab in the left pane.
3. If you don't see pending updates, click on **Check for updates.** Windows will look for new updates and list them accordingly.
4. Install all critical updates and restart your PC.

![Windows 11 Settings showing the Windows Update tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/check-for-windows-update.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Restart File Explorer

 File Explorer helps you navigate through the directories and browse files on Windows. Since it is an integral part of the Windows graphical user interface, [restarting the File Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) can help you restore the copy-and-paste function in Windows 11\.

 To restart File Explorer:

1. Press **Win + X** to open the **WinX** menu.
2. Click on **Task Manager** to open the app.
3. In the **Processes** tab, locate and select **Windows Explorer.**
4. Next, click on **Restart** to restart the process. Your screen may flicker when File Explorer restarts.

![Windows 11 Task Manager showing the Windows Explorer process.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/restart-windows-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
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

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-climbing-the-feed-ladder-the-most-effective-hashtags-for-likes-and-followers-on-insta/"><u>[New] 2024 Approved  Climbing the Feed Ladder  The Most Effective Hashtags for Likes and Followers on Insta</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-leading-titles-in-editing-webcam-videos-effectively/"><u>[New] 2024 Approved  Leading Titles in Editing Webcam Videos Effectively</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-examining-the-performance-of-recmeister-for-screen-recording-for-2024/"><u>[New] Examining the Performance of Recmeister for Screen Recording for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-expert-techniques-for-uploading-youtubes-on-dailymotion/"><u>[New] Expert Techniques for Uploading YouTubes on Dailymotion</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-blueprint-to-youtube-wealth-smart-strategies-for-facebook-video-marketing/"><u>[New] In 2024, The Blueprint to YouTube Wealth  Smart Strategies for Facebook Video Marketing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-mastering-video-transfer-youtube-to-dailymotion-conversion/"><u>[New] Mastering Video Transfer  YouTube to Dailymotion Conversion</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-premium-free-graphic-havens-a-comprehensive-guide-to-top-art-portals/"><u>[New] Premium-Free Graphic Havens  A Comprehensive Guide to Top Art Portals</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-simple-steps-to-change-iphones-call-alert-sounds/"><u>[New] Simple Steps to Change iPhones' Call Alert Sounds</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-tailoring-your-viewing-experience-with-youtube-tv/"><u>[New] Tailoring Your Viewing Experience with YouTube TV</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-top-20-chill-country-tracks-for-unwinding-and-grooving-on-tiktok/"><u>[New] Top 20 Chill Country Tracks for Unwinding & Grooving on TikTok</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-exclusive-list-best-4k-laptops-for-playing-games/"><u>[Updated] Exclusive List  Best 4K Laptops for Playing Games</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-perfect-iphone-photos-quick-editing-hacks/"><u>[Updated] Perfect iPhone Photos  Quick Editing Hacks</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-step-by-step-perfecting-fbs-360-streams/"><u>[Updated] Step-by-Step  Perfecting FB's 360 Streams</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-supercharged-productivity-while-flipping-audio-switches/"><u>[Updated] Supercharged Productivity While Flipping Audio Switches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-the-control-panel-on-windows/"><u>11 Ways to Open the Control Panel on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-essential-steps-to-clear-overflowing-c-drive-data/"><u>3 Essential Steps to Clear Overflowing C: Drive Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-copy-file-and-folder-paths-in-windows-11/"><u>6 Ways to Copy File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-calendar-revolution-customizing-your-scheduling-tool-on-windows-pc/"><u>A Calendar Revolution: Customizing Your Scheduling Tool on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-windows-beginning-navigating-3-reset-routes/"><u>A Fresh Windows Beginning: Navigating 3 Reset Routes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-eliminate-hardware-detection-faults/"><u>A Quick Guide to Eliminate Hardware Detection Faults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-file-management-with-seamless-multi-folder-crafting-on-windows-pcs/"><u>Accelerate File Management with Seamless Multi-Folder Crafting on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-clipchamp-integration-windows-11-setup-solved/"><u>Achieve ClipChamp Integration: Windows 11 Setup Solved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-performance-with-powertoys-win11/"><u>Achieving Optimal Performance with PowerToys (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-directx-update-problems-in-windows-os/"><u>Addressing DirectX Update Problems in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-insufficient-installation-privilege-issue-on-win-1011/"><u>Addressing Insufficient Installation Privilege Issue on Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-icon-glitches-in-win-108/"><u>Addressing Taskbar Icon Glitches in Win 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tactics-for-superior-windows-navigation-eliminating-ls/"><u>Advanced Tactics for Superior Windows Navigation: Eliminating LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amend-f-key-malfunctions-restore-control-in-windows-11/"><u>Amend: F Key Malfunctions - Restore Control in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/antivirus-alert-7-significant-windows-functions-under-scrutiny/"><u>Antivirus Alert: 7 Significant Windows Functions Under Scrutiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-some-websites-not-opening-in-any-browser-on-windows-7-ways-to-fix-it/"><u>Are Some Websites Not Opening in Any Browser on Windows? 7 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-deadlock-in-windows-desktop-menu-navigation/"><u>Avoiding Deadlock in Windows Desktop Menu Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperature-troubleshooting-tips-w11/"><u>Avoiding High-Temperature Troubleshooting Tips: W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unwanted-termination-messages-in-roblox-games/"><u>Avoiding Unwanted Termination Messages in Roblox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windowed-app-movement-windows-task-managing-tips/"><u>Avoiding Windowed App Movement: Windows Task Managing Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11-lock-screen-effortlessly/"><u>Avoiding Windows 11 Lock Screen Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-black-glare-from-window-8-displays/"><u>Banishing the Black Glare From Window 8 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-video-transformers-from-the-world-of-windows/"><u>Best Video Transformers From the World of Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-code-ai-reshaping-windows-tech-landscape/"><u>Beyond Code: AI Reshaping Windows Tech Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-space-for-storage-sluggishness-sets-in/"><u>Blackview: Space for Storage, Sluggishness Sets In</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-setting-up-automatic-deletions-in-win11/"><u>Boost Productivity: Setting Up Automatic Deletions in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-management-via-cmd/"><u>Boost Your System Management via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-performance-on-windows-11-top-seven-tweaks-for-game-enthusiasts/"><u>Boosting Performance on Windows 11: Top Seven Tweaks for Game Enthusiasts</u></a></li>
<li><a href="https://fox-that.techidaily.com/correcting-mistaken-identities-a-guide-to-editing-apples-photo-library/"><u>Correcting Mistaken Identities: A Guide to Editing Apple's Photo Library</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/cutthroat-countdown-best-zombies-in-gaming-unveiled/"><u>Cutthroat Countdown  Best Zombies In Gaming Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/engaging-consumer-openings-for-2024/"><u>Engaging Consumer Openings for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-excel-2007-has-encountered-a-problem-by-stellar-guide/"><u>How to Fix Excel 2007 has Encountered a Problem</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-motorola-edge-40-neo-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Motorola Edge 40 Neo Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-10-missing-iphone-x-tips-and-tricks-for-you-to-pick-up/"><u>In 2024, 10 Missing iPhone X Tips and Tricks For You to Pick Up</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-tips-for-cutting-and-splicing-360-degree-footage-in-adobe-premiere/"><u>In 2024, Expert Tips for Cutting and Splicing 360-Degree Footage in Adobe Premiere</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-samsung-galaxy-s24-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Samsung Galaxy S24 Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-screen-mirroring-tips-to-fix-miracast-rejected-by-device/"><u>Mastering Screen Mirroring: Tips to Fix 'Miracast Rejected by Device'</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-best-websites-to-download-nature-sounds/"><u>New 2024 Approved Best Websites to Download Nature Sounds</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/short-vid-star-spotlight-check/"><u>Short Vid Star Spotlight Check</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719332049172-swiftly-addressing-windows-faults-with-easy-fixes/"><u>Swiftly Addressing Windows Faults with Easy Fixes!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-gt-neo-5-se-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme GT Neo 5 SE</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-realme-v30t-frp-by-drfone-android/"><u>The Updated Method to Bypass Realme V30T FRP</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-xiaomi-mix-fold-3-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Xiaomi Mix Fold 3</u></a></li>
</ul></div>
