---
title: Mastering Device Connectivity Troubleshooting on Win OS
date: 2024-06-25T17:03:38.730Z
updated: 2024-06-26T17:03:38.730Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Device Connectivity Troubleshooting on Win OS
excerpt: This Article Describes Mastering Device Connectivity Troubleshooting on Win OS
keywords: Windows Connect Issues,Fixing Devices Protocol,WinOS Linkage Solutions,Device Comm Connection,WinLink Errors,Operating System Network,OS Device Troubleshoot
thumbnail: https://thmb.techidaily.com/ab4dfc265d3ec072f529482c24c8089138367c7bb9b170bcd6c98cca628f2064.jpg
---

## Mastering Device Connectivity Troubleshooting on Win OS

 Are you encountering the "Windows cannot access the specified device, path, or file." error on Windows 10 or 11? This issue usually appears when you try to run an EXE application or open a document. When this error happens, you can't run some programs or access some documents, limiting your computer's usefulness.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.

## 1\. Run the App as an Administrator

 Some programs, for a variety of reasons, need administrator privileges to perform specific tasks. In fact in certain situations, you might not be able to open them either.

 In your case, the "Windows Cannot Access the Specified Device, Path or File” error might be the result of this error as well. So if you are looking to fix this error, running it as an administrator will be your best bet. Here’s how you can get started:

1. Right-click on the app you want to run.
2. From the context menu, select **Run as administrator**.

 If the issue was the lack of administrator privileges, your app will run by the end of these steps.

## 2\. Disable Potentially Unwanted App Blocking

 Unwanted app blocking is a [Windows Security](https://www.makeuseof.com/windows-11-quick-security-guide/) feature that prevents low-reputation apps and software from running. That feature can cause the "cannot access the specified device" error when enabled. You can check if unwanted app blocking is enabled and disable it as follows:

1. Double-click the shield (Windows Security) icon inside the system tray area on the right of the taskbar. You may also need to click a small up arrow on the taskbar to see the system tray icons.
2. Select the **App & browser control** tab in Windows Security.
3. Then click the **Reputation-based protection** **settings** link to view more settings.  
![The Reputation-based protection settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reputation-based-settings-option.jpg)
4. Deselect the **Block apps** checkbox if that feature is enabled.  
![The Block apps checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-block-apps-checkbox.jpg)

## 3\. Deselect the "Unblock File" Setting

 Sometimes [Windows blocks access to files or folders](https://www.makeuseof.com/windows-askadmin-guide/) downloaded from untrusted online sources, which can cause the "cannot access the specified device" error. When that happens, you'll see an **Unblock** checkbox on an affected files properties window. This is how you can deselect the "unblock file" setting:

 Make sure that you trust the file's source before doing this. If you unblock an infected file, it can damage your computer and cause file loss.

1. Right-click **Start** (the taskbar button) and select the **File Explorer** option from the menu.  
![The File Explorer shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/file-explorer.jpg)
2. Open a folder that includes a file for which the error occurs.
3. Right-click the affected file and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/properties-option.jpg)
4. Click **General** if the properties window doesn't open with that tab by default.
5. Then uncheck the selected **Unblock** checkbox if you can see one.  
![The Unblock checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unblock-checkbox.jpg)
6. Select **Apply** to save the new file settings.
7. Click **OK** to close the file's properties window.

## 4\. Edit the File's Permissions

 Another cause of the "cannot access the specified device" error message is insufficient file permissions. That's something you can remedy by editing the permissions for affected files. So, try editing an affected file's permissions as follows:

1. Bring up a directory with a file that throws up the "cannot access the specified device" error.
2. Click an affected file with the right mouse button and select its **Properties** option.
3. Select **Security** in the properties window.
4. Then select the Windows user account you signed into.
5. Press the **Edit** button.
6. Select your Windows user account on the permissions window that opens.
7. Deselect (uncheck) all selected **Deny** permission checkboxes.  
![The Deny checkboxes for file permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deny-checkboxes.jpg)
8. Select **Apply** to set the new permission settings.
9. Press the **OK** buttons on all windows.

## 5\. Recreate a Program's Shortcut

 If the "cannot access the specified device" error occurs when you try to run a program shortcut, the issue might lie within the shortcut itself. In this case, setting up a new shortcut for affected software could resolve the issue. This is how to do so on your desktop:

1. Right-click any part of the desktop without overlapping icons to select **New**.
2. Click **Shortcut** to bring up a tool for adding desktop shortcuts.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/shortcut-option.jpg)
3. Then click **Browse** to select an EXE file the error occurs for and press the **OK** button.  
![The Create Shortcut tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/create-shortcut-window.jpg)
4. Select **Next** and input a shortcut title in the text box.
5. Click **Finish** to add the new program shortcut.
6. Right-click the program's old shortcut to select **Delete** (the trash can button in Windows 11).

## 6\. Double-Check the File's Location

 Do you install software and save some files to an external or network drive? If so, it could be the case that the access error is occurring because a file is on a drive that's not currently accessible.

 Double-check the locations of the files you're trying to run or open by right-clicking desktop shortcuts for them and selecting **Properties**. Then you can check the path for the shortcut in the **Targe**t box shown directly below.

![The Target box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-target-box.jpg)

 That **Target** box will show whether the file is on another drive. If it is, connect the external drive that includes the file to your PC to access it. Double-check that the file specified hasn't been deleted if the **Target** box references the local C: drive. To do that, open the folder path specified in File Explorer.

 Should you discover a shortcut's file has been deleted, you might be able to retrieve it. Open the Recycle Bin to see if the file is in it. If so, right-click the file and select **Restore**.

## 7\. Enable Admin Permissions With the Group Policy Editor

 Users have confirmed enabling admin approval mode in Group Policy Editor can resolve this file access error. However, Group Policy Editor is only available in Windows 11 and 10 Pro and Enterprise editions. If you can utilize Group Policy Editor, try enabling admin approval mode as follows:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and select **Computer Configuration** in that utility.
2. Double-click **Windows Settings** to expand that configuration category.
3. Then double-click **Security Settings** \> **Local Policies** \> **Security Options** in Group Policy Editor's sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/group-policy-editor.jpg)
4. Double-click the **Admin Approval Mode for Built-in Administrator** account policy.
5. Then select the **Enabled** radio button.  
![The Admin Approval Mode policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-admin-approval-mode-policy-settings.jpg)
6. Click **Apply** to set the policy.
7. Select **OK** to exit the window for the policy setting and close the Group Policy Manager utility.

## 8\. Set Up a Windows Security Exclusion Affected Software or File

 As Windows Security blocks can cause this error, we recommend users add affected files to that antivirus app's exclusion list. Doing so will exclude the file from Defender's antivirus protection. Check out our guide to [whitelisting files in Microsoft (formerly Windows) Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) for details about how to apply this potential solution.

![Add an exclusion button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-exclusion-button.jpg)

## 9\. Temporarily Disable Any Active Third-Party Security Software

 Some third-party antivirus apps share similar app-blocking features to Windows Security. Thus, alternative security software can also feasibly cause the same issue to occur much the same. So, try turning off any third-party antivirus software installed on your PC before attempting to run affected EXE software.

![A laptop computer is seen on a desk during an antivirus scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/manual-antivirus-scan.jpg)

 How exactly you turn off different third-party antivirus apps varies slightly. However, most have context menus from which you can select to disable their shields. Click the system tray icon for your antivirus software with the right mouse button to view its context menu. Then choose an option for disabling its antivirus shield from there.

 Should this potential solution work, you'll know what's causing it. However, don't leave your antivirus software disabled. Add affected files to the security software's exceptions list.

## 10\. Repair or Reinstall the File

 If you are facing this issue due to corruption in the file, then repairing or reinstalling it is your best bet. Using the Control Panel will be your best bet in this case. Here's how you can do it:

1. Head to the **Start menu** search bar, type in 'control panel', and select the best match.
2. From there, head to the **Programs**.
3. Then, select **Programs and Features**.
4. Right-click on any program and select **Uninstall/Change**.

![control panel on windows pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/control-panel-on-windows-pc.jpg)

 Depending on the app, you will get an option to either uninstall the app or change its settings. That's it—from there just follow the on-screen instructions, and you will be done in no time. If you installed the app, make sure you get it from a trusted source again and then see if you are facing the same error again.

## Get the "Cannot Access the Specified Device" Error Sorted in Windows 10 and 11

 We don't promise guaranteed solutions, but the potential resolutions here will likely resolve the "cannot access the specified device" error on your PC. Many users have sorted that file access issue out in Windows by applying the above fixes.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>