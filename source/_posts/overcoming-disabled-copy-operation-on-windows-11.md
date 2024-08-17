---
title: Overcoming Disabled Copy Operation on Windows 11
date: 2024-08-16T01:24:27.977Z
updated: 2024-08-17T01:24:27.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Disabled Copy Operation on Windows 11
excerpt: This Article Describes Overcoming Disabled Copy Operation on Windows 11
keywords: W11 Accessibility Issues,Fixing Copy Errors Win11,Windows 11 Usability Hacks,Disabled Copies Resolution,Overcoming Operation Restrictions,Enhancing Win11 Functionality,Accessible File Operations Win11
thumbnail: https://thmb.techidaily.com/c7faa06295ae09ceb9c04771af8ef4a70065bcb58f83238cd328dc914caf4d9a.jpg
---

## Overcoming Disabled Copy Operation on Windows 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
4. Check the **Hide all Microsoft services** box. This will hide all the essential system services necessary to operate the system so that you don’t accidentally disable them.
5. Click the **Disable All** button to disable third-party services.

1. Open the **Startup** tab and click **Open Task Manager.**
2. The Task Manager will open in the **Startup** tab.  
![Windows 11 Task Manager showing the Startup tab.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/disable-startup-apps-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

## 5\. Run the Keyboard Troubleshooter

 Windows 11 features a built-in keyboard troubleshooter to find and fix common issues. It fixes issues triggered due to malfunctioning drivers and incorrect keyboard configuration.

 To run the keyboard troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshoot**.  
![Windows 11 Settings app showing the Troubleshoot option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-11-troubleshoot.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
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
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
3. Select all the **Startup** apps one by one and click **Disable**.
4. Once you have disabled all the startup apps, go back to the **System Configuration** dialog. Click **Apply** and **OK** to save the changes.
5. Click **Restart** to reboot your PC in clean boot mode.

 After the restart, see if you can successfully copy and paste. If the problem is fixed, it's safe to assume a third-party app caused it. To find the troublesome app, open Task Manager and start enabling startup apps one by one until you find the problematic app.

 If the issue persists in the clean boot mode, proceed with the next steps. Before that, enable all the disabled services in System Configuration.

 To disable the clean boot mode and start Windows normally, open the **System Configuration** utility, go to the **General** tab, then select the **normal startup** option.

![Windows 11 System Configuration dialog.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/normal-startup-windows-11-system-configuration.jpg)

 Click **Apply** and **OK** to save the changes. When prompted, click **Restart Now** to reboot your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
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
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To restart the process, in the Task Manager, click **Run new task**, type **rdpclip.exe**, and click **OK**.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 7\. Check Your Keyboard for Hardware Issues

 If you have [remapped your keyboard keys on Windows,](https://www.makeuseof.com/tag/missing-key-remap-fix-keyboard-layout/) make sure the **Ctrl + C / Ctrl + V** shortcut is set correctly. Also, look for issues with the Ctrl keys. Your keyboard likely features multiple Ctrl keys. Try to use the additional Ctrl key at the bottom right of your keyboard to copy and paste. If it works, you are likely dealing with a faulty left Ctrl key. If there is a faulty key, there are ways to [fix broken keys on your computer keyboard](https://www.makeuseof.com/how-to-fix-keyboard-keys/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
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
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## 1\. Clear Clipboard Data

 If conflicting data formats and corrupted data are causing the issue, [clearing your clipboard data](https://www.makeuseof.com/windows-11-clear-clipboard-history/) can help. Doing so will delete your clipboard history, except for pinned items.

 To do this, press **Win+I** to open **Settings** and go to **System > Clipboard**. Click the **Clear** button next to **Clear clipboard data** to delete the history.

![Windows 11 Settings app showing the Clipboard settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-settings-app-showing-the-clipboard-settings.png)

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
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
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->

 If the issue persists, perform a quick restart to refresh hardware components and Windows services and apps to fix temporary glitches with your computer.

## 2\. Perform a Clean Boot

 You can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to determine if a third-party app conflict is causing the copy-and-paste functionality to malfunction. Third-party app conflicts are among the common contributing factors to this problem.

 In clean boot mode, Windows starts with a minimal set of drivers. To do this, you will need to manually disable all the non-essential services and startup programs and restart your PC. To perform a clean boot:

1. Press **Win + R** to open **Run**.
2. Type **msconfig.msc** and click **OK** to open **System Configuration**. You can also search for system configuration in **Windows Search** and open the app.
3. In the **System Configuration** window, open the **Services** tab.  
![Windows 11 System Configuration App showing Hide all Microsoft services option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/hide-all-microsoft-services-clean-boot-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
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
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Scroll down to **Keyboard** and click on **Run**. Wait for the troubleshooter to detect and fix any issues with your keyboard.

 The keyboard troubleshooter may not be available on Windows 11 23H2 and above. If so, you can run it using Command Prompt.

 So, click **Start**, type **cmd**, and click to open **Command Prompt** from search results. In Command Prompt, type the following command and press Enter:

`msdt.exe /id KeyboardDiagnostic`

 In the Keyboard troubleshooter dialog, click **Advanced**, select the **Apply repairs automatically** option, and click **Next**. The troubleshooter will scan your computer for known keyboard issues and try to fix them automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 6\. Reset the rdpclip.exe Process

 If the copy-paste function does not work when using Remote Desktop Connection, restarting the Rdpclip.exe process can help you copy and paste text and files between your local and remote computers.

![Windows 11 Task Manager showing end task option for rdpclip-exe process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-showing-end-task-option-for-rdpclip-exe-process.png)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 To restart the rdpclip.exe process, press **Win+X** and choose **Task Manager**. In Task Manager, open the **Details** tab and locate the **rdpclip.exe** process. To end the process, right-click on **rdpclip.exe** and choose **End task**.

![Windows 11 Task Manager create new task dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/04/windows-11-task-manager-create-new-task-dialog.png)
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->

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
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the Command Prompt window, type the following commands one by one and press Enter:  
`DISM /Online /Cleanup-Image /RestoreHealth  
Sfc /scannow`
4. First, DISM will scan and repair the Windows image. Then System File Checker will begin the verification phase. It will scan for all protected system files and replace corrupted or missing files. This process may take some time, so wait till the verification is 100% complete.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-free-banner-templates-and-makers-for-youtube/"><u>[New] 2024 Approved  Free Banner Templates & Makers for YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-pixelpilot-screen-recorder-critique-plus-backups/"><u>[New] In 2024, PixelPilot Screen Recorder Critique + Backups</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-maximizing-game-capture-with-bandicam-essentials-for-the-year-2023/"><u>[New] Maximizing Game Capture with Bandicam - Essentials for the Year 2023</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tapping-into-trends-5-game-changing-strategies-for-influencers-for-2024/"><u>[New] Tapping Into Trends  5 Game-Changing Strategies for Influencers for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-unlocking-the-art-of-video-capturing-everywhere/"><u>[New] Unlocking the Art of Video Capturing Everywhere</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlocking-the-power-of-revenue-streams-youtubers-adsense-manual/"><u>[New] Unlocking the Power of Revenue Streams  YouTubers' AdSense Manual</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-behind-the-camera-glory-spotlight-on-top-10-female-youtubers/"><u>[Updated] 2024 Approved  Behind-the-Camera Glory  Spotlight on Top 10 Female YouTubers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-an-easy-to-follow-guide-adding-youtube-playlists-to-your-online-platform/"><u>[Updated] In 2024, An Easy-to-Follow Guide  Adding YouTube Playlists to Your Online Platform</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-secure-your-shots-above-all-unlimited-free-options-and-premium-subscription-picks/"><u>[Updated] Secure Your Shots Above All  Unlimited Free Options & Premium Subscription Picks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-streaming-supremacy-pick-the-best-tool-for-your-vlogs-and-streams/"><u>[Updated] Streaming Supremacy  Pick the Best Tool for Your Vlogs & Streams</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-elevate-your-fb-campaigns-the-20-premier-video-tactics/"><u>2024 Approved  Elevate Your FB Campaigns  The 20 Premier Video Tactics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-key-to-engaging-audiences-instagram-video-descriptions/"><u>2024 Approved  The Key to Engaging Audiences  Instagram Video Descriptions</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-ultimate-roadmap-for-spotify-ad-mastery/"><u>2024 Approved  The Ultimate Roadmap for Spotify Ad Mastery</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-a-complete-guide-to-audio-logging-for-your-conversations-in-google-voice/"><u>2024 Approved A Complete Guide to Audio Logging for Your Conversations in Google Voice</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-poco-m6-pro-4g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-fixes-conquer-the-windows-update-hurdles/"><u>7 Essential Fixes: Conquer the Windows Update Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-stuck-function-keys-on-windows-11-desktop/"><u>Address: Stuck Function Keys on Windows 11 Desktop</u></a></li>
<li><a href="https://extra-information.techidaily.com/archive-artistry-seamlessly-fuse-infinite-no-charge-cloud-and-premium-subscriptions/"><u>Archive Artistry  Seamlessly Fuse Infinite, No-Charge Cloud & Premium Subscriptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-mass-rename-with-powertoys/"><u>Automate Mass Rename with PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-bonanza-lifelong-windows-10-priced-low-612/"><u>Black Friday Bonanza: Lifelong Windows 10 Priced Low ($6.12)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-customized-cmd-shortcuts-and-windows/"><u>Boost Efficiency with Customized Cmd Shortcuts and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-battlenet-speed-fasten-your-windows-pace/"><u>Boosting Battle.net Speed: Fasten Your Windows Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chatgpt-launch-procedure-for-windows-users/"><u>ChatGPT Launch Procedure for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-window-11-notebook-space-you-love/"><u>Creating a Window 11 Notebook Space You Love</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-access-control-constructing-your-windows-personal-pins/"><u>Cutting-Edge Access Control: Constructing Your Windows Personal Pins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/documentation-skills-snapping-windows-uac-prompts/"><u>Documentation Skills: Snapping Windows UAC Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-the-heat-cutting-down-vanguard-writes-on-your-computer/"><u>Easing the Heat: Cutting Down Vanguard’ Writes on Your Computer</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-techniques-to-halt-non-essential-application-processes-in-the-android-operating-environment/"><u>Effective Techniques to Halt Non-Essential Application Processes in the Android Operating Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-no-network-reachable-errors-win/"><u>Eradicating No Network Reachable Errors (WIN)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gaming-unbound-android-in-desktop-windows-with-google-play-service/"><u>Experience Gaming Unbound: Android in Desktop Windows with Google Play Service</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fix-your-visual-problems-with-updated-window-compatible-driver-solutions/"><u>Fix Your Visual Problems with Updated Window-Compatible Driver Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-selecting-the-best-win-notebook/"><u>Fundamentals of Selecting the Best Win Notebook</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-narzo-60-pro-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Realme Narzo 60 Pro 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208162474-how-to-repair-broken-voice-communication-on-overwatch-instantly/"><u>How to Repair Broken Voice Communication on Overwatch Instantly!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-tecno-spark-20-proplus-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Tecno Spark 20 Pro+ to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-infinix-smart-7-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-clear-shots-a-guide-to-still-image-stability/"><u>In 2024, Clear Shots  A Guide to Still Image Stability</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-from-imovie-to-hollywood-mastering-movie-making-on-mac/"><u>In 2024, From iMovie to Hollywood Mastering Movie Making on Mac</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-6-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 6 Device from iCloud</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-apple-iphone-13-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From Apple iPhone 13</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XS Passcode without Computer?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locating-and-opening-system32-windows-11/"><u>Locating and Opening System32 (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719336383556-mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-non-responsive-windows-services-management-tool/"><u>Navigating the Maze of Non-Responsive Windows Services Management Tool</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/optimal-webcams-for-enhanced-clarity-in-all-your-zoom-calls/"><u>Optimal Webcams for Enhanced Clarity in All Your Zoom Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-end-specs-in-windows-game-capture/"><u>Overcoming Low-End Specs in Windows Game Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pitfalls-of-the-promotional-assessing-risks-with-low-price-auth-codes/"><u>Pitfalls of the Promotional: Assessing Risks with Low-Price Auth Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-elusive-link-finding-missing-launcher/"><u>Re-Establishing Elusive Link: Finding Missing Launcher</u></a></li>
<li><a href="https://common-error.techidaily.com/rectifying-system-deficiency-msvcr71/"><u>Rectifying System Deficiency - MSVCR71</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-chromes-firewallantivirus-denial-error-on-pc/"><u>Resolving Chrome's Firewall/Antivirus Denial Error on PC</u></a></li>
<li><a href="https://media-tips.techidaily.com/simplified-guide-transforming-mpg-videos-to-mp4-on-a-macbook/"><u>Simplified Guide: Transforming MPG Videos to MP4 on a MacBook</u></a></li>
<li><a href="https://extra-information.techidaily.com/simplify-complex-designs-by-mastering-figmas-backdrop-cleansing/"><u>Simplify Complex Designs by Mastering Figma's Backdrop Cleansing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaky-storage-solutions-hiding-zips-within-computer-photos/"><u>Sneaky Storage Solutions: Hiding ZIPs Within Computer Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-restarting-non-responsive-resource-monitors-in-windows-11/"><u>Strategies for Restarting Non-Responsive Resource Monitors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-successful-java-setup-in-windows/"><u>Strategies for Successful Java Setup in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategizing-user-focused-gpo-settings-for-windows-1111-oses/"><u>Strategizing User-Focused GPO Settings for Windows 11/11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cr2-conversion-to-jpg-in-windows-environment/"><u>Streamline CR2 Conversion to JPG in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-power-peaks-controlling-wlanext-usage/"><u>Taming Power Peaks: Controlling WLANEXT Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-sudo-tool-is-coming-to-windows-how-and-why-to-use-it/"><u>The Sudo Tool Is Coming to Windows: How and Why to Use It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-manual-for-chrome-and-windows-11/"><u>The Ultimate Manual for Chrome and Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-zte-axon-40-lite-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from ZTE Axon 40 Lite to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-optional-windows-extras-in-7-steps/"><u>Troubleshooting Missing Optional Windows Extras in 7 Steps</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-steps-resolving-issues-with-battle-royale-call-of-duty-warzone-not-locating-pvp-games/"><u>Troubleshooting Steps: Resolving Issues with Battle Royale - Call of Duty: Warzone Not Locating PvP Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-pc-vram-with-windows-1011-tips-and-tricks/"><u>Turbocharging PC VRAM with Windows 10/11 Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-effect-of-eliminating-windows-11-taskbar-chat-on-you/"><u>Understanding the Effect of Eliminating Windows 11 Taskbar Chat on You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-games-again-steams-achievement-reboot/"><u>Unlocking Games Again: Steam's Achievement Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-browser-security-with-trusted-site-listing/"><u>Upgrade Browser Security with Trusted Site Listing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-resource-tracking-efficiency-via-windows-interfaces/"><u>Upgrade Resource Tracking Efficiency via Window's Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-error-unsigned-update-files-fix-guide/"><u>Windows Error: Unsigned Update Files; Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-guide-mkv-to-mp4-conversion-process/"><u>Windows Guide: MKV to MP4 Conversion Process</u></a></li>
</ul></div>
