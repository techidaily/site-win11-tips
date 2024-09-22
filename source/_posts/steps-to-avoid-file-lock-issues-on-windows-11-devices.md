---
title: Steps to Avoid File Lock Issues on Windows 11 Devices
date: 2024-09-16T00:05:41.471Z
updated: 2024-09-22T01:50:19.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Avoid File Lock Issues on Windows 11 Devices
excerpt: This Article Describes Steps to Avoid File Lock Issues on Windows 11 Devices
keywords: Windows 11 File Security,Preventing Data Corruption,Win11 Filesync Safety,Freeze-Avoidance in Windows,Avoiding Locked Files Windows,Windows 11 Sync Guard,Secure File Handling W11
thumbnail: https://thmb.techidaily.com/3119c4d644ca38982b7a0f68d251b6e048a299751591496c468d996da741d28a.jpg
---

## Steps to Avoid File Lock Issues on Windows 11 Devices

 Users have reported “the requested resource in use” error message pops up on their PCs when trying to copy or move files from mobile devices to their Windows PCs. That error message’s heading also says, “error copying file or folder.” As a result, users can’t copy the files they need to.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check if the File Is Already in Use

![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-end-task-option.jpg)

 The “requested resource is in use” error message hints that the file (resource) you’re trying to copy is already in use. Thus, the copy operation cannot be completed because something else is using the file or folder. So, you might need to close some background processes to address this issue.

 First, move your mouse’s cursor over the File Explorer taskbar icon to see if there are any windows for active file operations. Cancel any active file operations you see. Then try copying the file again.

 If that doesn’t work, go into Task Manager and close superfluous third-party app background processes. Our guide to [fixing too many background processes on Windows](https://www.makeuseof.com/windows-pc-too-many-background-processes/) provides further instructions for how you can do that.

## 2\. Disable File Explorer’s Preview Pane

 Many users have fixed the “requested resource is in use” error by disabling File Explorer’s preview pane. That preview pane can hinder the file copy operation. You can disable File Explorer’s preview pane in Windows 11 as follows:

1. Press the **Win + E** key combination to launch File Explorer.
2. Then click the **View** menu button.
3. Select the **Show** submenu.
4. Deselect the **Preview pane** option.  
![The Preview pane option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/preview-pane-option.jpg)
5. Then try moving or copying your files again.

 The layout in Windows 10 File Explorer is a little different. To disable preview panes in that file manager, you’ll need to click the **View** tab. Then click **Preview pane** to deselect that option.

![The View tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-view-tab.jpg)

 Note that just disabling the preview pane might not always be enough. If that doesn’t work, try turning off the icon file view. To do so in Windows 11 File Explorer, click **View** and select the **List** or **Details view** option. You can select the same options on the **View** tab in Windows 10 File Explorer.

## 3\. Run a Malware Scan

 If the previous two resolutions don’t work for you, it’s probably the case that malware is causing the “requested resource is in use” error on your PC. SmartService is a trojan known to cause the “required source is in use” error. So, try running an antivirus scan with third-party software or Windows Security to kill SmartService. You can run an antivirus scan with Windows Security like this:

1. Double-click Windows Security’s icon in the system tray (the shield).
2. Click **Virus & threat protection** \> **Scan options** to access the Microsoft Defender antivirus tool.  
![The Scan options navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-scan-options.jpg)
3. Select the **Full scan** setting.
4. Click **Scan now** to initiate the malware scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-full-scan-radio-button.jpg)
5. Wait for the scanning to finish and select **Start actions** to remove detected malware.

 If you find Microsoft Defender is disabled and cannot turn it on, that’s a surefire sign the SmartService malware has infected your PC. SmartService is a rootkit trojan that blocks users from utilizing antivirus tools. That malware can also block the installation of some antivirus apps. In this case, the “requested resource in use” error can also occur when you try to run security apps.

 To circumvent such a block, try running a Windows Security or third-party app antivirus scan in safe mode instead. Our guide to [booting into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) includes a few different methods for entering that troubleshooting mode. Select to enable safe mode with networking.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Disable Any Unknown Programs in Task Manager

 You might be able to disable a SmartService trojan from starting with Windows via Task Manager’s Startup tab. Look for and disable any suspicious programs listed on the **Startup** tab as follows:

1. Right-click a space on the taskbar to select a **Task Manager** context menu shortcut.
2. Next, click **Startup** to view that tab.
3. Look for any programs you don’t recognize on the **Startup** tab.
4. If you see anything suspicious, select that item and click the **Disable** button.  
![The Disable button on Task Manager's Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-button.jpg)
5. Then restart your PC to see if the issue persists.

## 5\. Uninstall Any Suspicious-Looking Programs

 The SmartService trojan might also be listed within the Programs and Features Control Panel applet for uninstalling software. If you notice suspicious-looking software in Programs and Features, you can also select to uninstall it from there.

 Try uninstalling suspicious programs like this:

1. Bring up the Windows uninstaller tool with a method in our guide to opening Programs and Features.
2. Look through the list of installed software to see if there’s any suspicious-looking program there. Look for a program you can’t recall installing with an unknown publisher title.  
![The Uninstall option in Programs and Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option4.jpg)
3. Right-click on the suspected SmartService malware and select **Uninstall**.
4. If you can’t uninstall the suspicious software, restart Windows in safe mode. Then try removing the same suspicious item via Programs and Features in safe mode.

 Also, clear temporary data after uninstalling SmartService to ensure the malware can’t re-emerge. To do so, you’ll need to clear out the Temp folder. This article about [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes alternative methods for clearing data in the Temp folder.

## 6\. Perform a Factory Reset

 If the “requested resource is in use” error remains unresolved after trying all the potential resolutions above, performing a factory reset is the last resort. A factory reset will remove all programs not pre-installed with Windows and restore your PC to its default configuration. Applying this potential fix will likely eradicate malware causing the “requested resource is in use” error.

 The "Reset this PC" utility lets you factory reset Windows 11 and 10\. That tool includes an option you can select to stop the reset deleting user files. Our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) guide provides detailed guidelines for resetting the platform.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-keep-my-files-option.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030129/11832" target="_top" id="1030129">
  <img src="//a.impactradius-go.com/display-ad/11832-1030129" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030129/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the “Requested Resource Is in Use” Error Sorted on Windows

 The potential solutions covered here are widely confirmed to resolve the “requested resource is in use” error. If it’s not caused by malware, disabling Explorer’s preview pane, as covered in resolution two, will usually fix the issue. Users confirm running an antivirus scan in safe mode (solution three) can fix the “required resource is in use” error when caused by malware.

 Here is how you can fix the “requested resource is in use” error on a Windows 10 or 11 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-advanced-subtitle-tools-navigate-through-the-best-10-web-edits/"><u>[New] 2024 Approved Advanced Subtitle Tools - Navigate Through the Best 10 Web Edits</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-experience-the-power-of-visuals-discover-all-50-banners-in-our-digital-collection/"><u>[Updated] In 2024, Experience the Power of Visuals Discover All 50 Banners in Our Digital Collection</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-essential-guide-to-motion-blur-from-theory-to-practice-in-ps/"><u>2024 Approved The Essential Guide to Motion Blur From Theory to Practice in PS</u></a></li>
<li><a href="https://win-amazing.techidaily.com/getting-your-iphone-up-and-running-on-windows-10-with-easy-driver-installation/"><u>Getting Your iPhone Up & Running on Windows 10 with Easy Driver Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recognize-and-implement-execution-monikers/"><u>How to Recognize and Implement Execution Monikers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y27-4g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Vivo Y27 4G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-lowering-high-cpu-demand-in-windows-by-tiworkerexe/"><u>Methods for Lowering High CPU Demand in Windows by TiWorker.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-eliminate-spontaneous-key-press-responses/"><u>Methods to Eliminate Spontaneous Key Press Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-windows-11-installation-with-these-top-configuration-tweaks/"><u>Perfect Your Windows 11 Installation with These Top Configuration Tweaks</u></a></li>
<li><a href="https://extra-information.techidaily.com/premium-list-high-end-ios-tune-creators/"><u>Premium List High-End iOS Tune Creators</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-asus-rog-phone-7-ultimate-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Asus ROG Phone 7 Ultimate Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-error-xc0f1103f-in-windows-11-with-nvidia/"><u>Reconciling Error Xc0f1103f in Windows 11 with NVIDIA</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-panel-presets-optimizing-your-samsung-4k-tv-display/"><u>Top Panel Presets: Optimizing Your Samsung 4K TV Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-win11-remote-storage-integration/"><u>Unlocking the Potential of Win11 Remote Storage Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-error-code-fixing-unreachable-wifi-connections/"><u>Windows 11 Error Code - Fixing Unreachable WiFi Connections</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    