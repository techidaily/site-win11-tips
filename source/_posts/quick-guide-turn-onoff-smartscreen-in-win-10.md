---
title: "Quick Guide: Turn On/Off SmartScreen in Win 10"
date: 2025-01-07T19:30:05.119Z
updated: 2025-01-12T16:39:37.176Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Turn On/Off SmartScreen in Win 10"
excerpt: "This Article Describes Quick Guide: Turn On/Off SmartScreen in Win 10"
keywords: Windows SmartScreen Control,Win 10 Security Screen Switch,Enable/Disable Win 10 Smartscreen,SmartScreen Win 10 Guide,Turn On/Off Windows SmartGuard,Activate/Deactivate Win 10 Screen,Manage Win 10 SmartSecurity
thumbnail: https://thmb.techidaily.com/720039bdcfeba97eefefa9824f21f9715183b78c763bbf782b71c474fcdd45b6.jpg
---

## Quick Guide: Turn On/Off SmartScreen in Win 10

### Key Takeaways

* Microsoft Defender SmartScreen is enabled by default in Windows and provides reputation-based protection against malicious apps and websites. It can be disabled if it mistakenly blocks safe files.
* SmartScreen is also a part of Microsoft Edge's security settings and can be turned off or on from the browser's settings menu. It helps protect against phishing sites and blocks potentially unwanted apps.
* SmartScreen can be turned off or on using various methods, including the Windows Security settings, Microsoft Edge settings, Internet Properties dialog, Registry Editor, and Group Policy Editor. It is recommended to enable SmartScreen for added PC security.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.
4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Close Group Policy Editor and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

 Microsoft Defender SmartScreen is part of the Windows Security solution. It helps you protect against common threats by warning against downloading or installing potentially malicious files from other computers.

 SmartScreen is enabled by default in Windows. However, sometimes, you may want to disable the feature if it identifies and blocks genuine apps and files as malicious. Fortunately, you can disable SmartScreen easily. Here, we show you how to disable the SmartScreen filter in Windows.

## How Does Windows SmartScreen Filter Work?

 SmartScreen relies on reputation-based protection to protect your device from malicious or potentially unwanted apps and websites.

 When enabled, SmartScreen screens your downloads against known suspicious sites and developers. When a match is found, it blocks the download or site access and warns the user about the action taken.

 You can configure it to block apps and files by checking unrecognized apps and files from the web. It can also protect you from Microsoft Store and third-party sourced apps that are low on reputation and known to cause unexpected behavior.

[SmartScreen is also part of Microsoft Edge's security settings](https://www.makeuseof.com/guide-to-security-settings-in-microsoft-edge/). When enabled, it helps protect your computer against malicious and phishing sites and block downloads.

 SmartScreen is enabled by default on all the Windows OS running systems. However, some experienced users may find the feature annoying as it can block safe apps, requiring additional steps to run the setup.

 While we recommend you always turn the SmartScreen filter on, you can disable it easily from the Windows Security settings. Here's how to do it.

## 1\. How to Turn Off SmartScreen Using Windows' Security Settings

 The easiest way to turn off SmartScreen is via the Windows Settings panel. You can configure all the aspects of your system security from the Windows Security panel. Here's how to do it.

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy and Security** tab in the left pane.
3. Click on **Windows Security.**  
![Open Windows Security Windows 11 Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings.jpg)
4. Next, click on **Open Windows Security.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
5. Open the **App & browser control** tab in the left pane.
6. Click on **Reputation-based protection settings** under **Reputation-based protection.**  
![App and browser control windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/app-and-browser-control-windows-security.jpg)
7. Here, you'll find four different SmartScreen filters you can individually enable or disable. If you want to turn off the filter for files and executables, turn off **Check apps and files** and **Potentially unwanted app blocking** filters. The other two filters are for **Microsoft Edge** and **Microsoft Store apps**.  
![windows security turn off smartscreen filter apps files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-security-turn-off-smartscreen-filter-apps-files.jpg)
8. If you want to turn off SmartScreen completely, disable all four filters.

 When you have difficulty accessing the Windows Security window, refer to our troubleshooting guide to [fix a blank Windows security screen](https://www.makeuseof.com/windows-10-security-showing-blank-white-screen/).

 If any of the SmartScreen filters are grayed out with the message "this setting is managed by your administrator," you must contact your administrator or try another method.

## 2\. How to Disable SmartScreen for Microsoft Edge

![turn off smartscreen filter microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-smartscreen-filter-microsoft-edge.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Microsoft Edge has a built-in option to enable and disable Microsoft Defender SmartScreen. Here's how to access it:

1. Launch **Microsoft Edge** and click the **three-dots** menu icon in the top right corner.
2. Click on **Settings**.
3. Open the **Privacy**, **search, and services** tab in the left pane.
4. Scroll down to the **Security** section.
5. Toggle the switch for **Microsoft Defender SmartScreen** to turn it off. This will disable the **Block potentially unwanted apps** option as well.
6. If you choose to enable SmartScreen again, you must manually enable the **Block potentially unwanted apps** feature.

 Additionally, you can disable SmartScreen for Microsoft Edge using the Windows Security app and Registry Editor. Here’s how to do it.

### Disable Microsoft Edge SmartScreen Using Windows Security

 Microsoft Edge SmartScreen is for your browsing safety against phishing and malware sites and software you download. Unless an administrator manages it, you can turn it off.

1. Press **Win + R** to open **Run**.
2. Type **windowsdefender://** and click **OK** to open the **Windows Security** app.  
![Run open Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/run-open-windows-security.jpg)
3. Open the **App & browser control** tab in the left pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, click the **Reputation-based protection settings** link under **Reputation-based protection**.  
![smartscreen disabled Microsoft Edge Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/smartscreen-disabled-microsoft-edge-windows-security.jpg)
5. Toggle the switch for **SmartScreen for Microsoft Edge** to turn off Microsoft Defender SmartScreen for the Edge browser.

### Disable SmartScreen for Microsoft Edge Using Registry Editor

 Editing the registry entry is an alternative (but more complicated) method to disable the SmartScreen for the Edge browser permanently.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open Registry Editor.
3. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Microsoft\Edge\SmartScreenEnabled`
4. In the right pane, right-click on the **Default value** and select **Modify**.  
![registry editor SmartScreen Edge Enabled default value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-smartscreen-edge-enabled-default-value.jpg)
5. Type **1** in the **Value data** field and click **OK** to save the changes.  
![edge smartscreen disabled registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edge-smartscreen-disabled-registry-editor.jpg)
6. You may need to restart your computer to see the changes live.

## 3\. How to Turn Off Windows Defender SmartScreen Using Internet Properties

 You can turn on or off Windows Defender SmartScreen using the Internet Properties dialog in Windows 10\. Also known as Internet Options, it lets you configure security and access settings, add-ons, Active-X controls, and more.

 Follow these steps to turn off SmartScreen using Internet Options:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the **Control Panel**.
3. Click on **Network and Internet.**  
![Windows control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel.jpg)
4. Next, click on **Internet Options.**
5. In the **Internet Properties** window, open the **Advanced** tab.  
![Windows Control Panel Network Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-control-panel-network-options.jpg)
6. Scroll down to the **Security** section.  
![enable Windows defender smartscreen Internet Options Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/enable-windows-defender-smartscreen-internet-options-windows.jpg)
7. Uncheck the **Enable Windows Defender SmartScreen** option.
8. Click **Apply** and **OK** to save the changes.

 On a newer version of Windows, including Windows 11, you may not find any option to enable or disable Windows Defender SmartScreen in Internet Properties.

## 4\. How to Enable or Disable SmartScreen Using Registry Editor

 You can also turn the Windows Defender SmartScreen on or off using the Registry Editor. Useful if you cannot access it from the Settings app or Internet Properties.

 Note that incorrect modification to the registry entries can cause system malfunction. Therefore, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

1. Press **Win + R** to open Run.
2. Type **regedit** and click **OK** to open the **Registry Editor.** Click **Yes** if prompted by UAC to grant administrative privilege.
3. In the Registry Editor, navigate to the following location:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\System
4. In the right pane, locate the **EnableSmartScreen** filter value. You will need to create a new value if no value is found.  
![create new value enable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/create-new-value-enablesmartscreen-registry-editor.jpg)
5. To create a new value, right-click on the **System** key and select **New > DWORD (32-bit) Value.**

1. Rename the value as **EnableSmartScreen.**
2. Next, right-click on the **EnableSmartScreen** value and select **Modify**.  
![disable smartscreen registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-smartscreen-registry-editor.jpg)
3. Type **0** in the **Value data** field and click **OK** to save the changes.
4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  
![registry editor shellsmartscreenlevel warn](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-shellsmartscreenlevel-warn.jpg)
3. Type **Warn** or **Block** depending on what you want the **SmartScreen Level** to do. Click **OK** to save the changes and exit Registry Editor.

## 5\. How to Turn the SmartScreen Filter On or Off Using the Group Policy Editor

 If you want to manage the SmartScreen filter for multiple computers at your organization, you can use the Group Policy Editor to do this task.

 Note that Group Policy Editor is only available on Windows Pro, Edu, and Enterprise editions of the OS. If you are using Home, explore our guide to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To configure the SmartScreen filter using GPEdit:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor.**
3. Next, navigate to the following location in Group Policy Editor:  
`Computer Configuration > Administrative Templates > Windows Components > File Explorer.`
4. In the right pane, right-click on **Configure Windows Defender SmartScreen** policy and select **Edit**.  
![configure Windows Defender Smartscreen Gpeditor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor.jpg)
5. To disable **SmartScreen**, select **Disabled**.
6. If you want to enable SmartScreen, select **Not Configured** or **Enabled**.  
![configure Windows Defender Smartscreen Gpeditor disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/configure-Windows-Defender-Smartscreen-Gpeditor-disable.jpg)
7. Click **Apply** and **OK** to save the changes.
8. Close Group Policy Editor and restart your PC.

## Manage the SmartScreen Filter in Windows

 While you can easily disable the SmartScreen filter in Windows, it is an extremely useful security tool. It can protect you against malicious files and programs and screen and block suspicious sites. It's an added layer of protection to Windows Defender and helps keep your PC safe. Make sure to enable the SmartScreen filter once the task is finished.

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
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-the-updated-windows-11-interface/"><u>2024 Approved Exploring the Updated Windows 11 Interface</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-navigating-through-a-tiktok-live-session-a-comprehensive-overview/"><u>2024 Approved Navigating Through a TikTok Live Session A Comprehensive Overview</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-samsung-galaxy-s23plus-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Samsung Galaxy S23+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-pcs-visual-fidelity-with-updated-radeon-drivers-windows-edition/"><u>Elevating Your PC's Visual Fidelity with Updated Radeon Drivers, Windows Edition</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-motorola-moto-g14-by-fonelab-android-recover-music/"><u>How to recover old music from your Motorola Moto G14</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-assessing-splitcams-standards-in-the-videographer-space/"><u>In 2024, Assessing SplitCam’s Standards in the Videographer Space</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-becoming-a-pinning-pro-snapchats-best-practices/"><u>In 2024, Becoming a Pinning Pro Snapchat's Best Practices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-frontier-gadgets-galore-top-10-vr-accessories/"><u>In 2024, Frontier Gadgets Galore Top 10 VR Accessories</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-unlocking-innovations-a-comparison-between-iphones-face-id-and-galaxy-recognition/"><u>In 2024, Unlocking Innovations A Comparison Between iPhone's Face ID & Galaxy Recognition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-notes-prominent/"><u>Keeping Your Windows Notes Prominent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-linkage-airpods-and-windows-harmony/"><u>Master the Linkage: AirPods & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-powerpoint-print-errors-with-9-effective-methods/"><u>Overcoming Common PowerPoint Print Errors with 9 Effective Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://youtube-web.techidaily.com/g-the-way-for-individuality-in-the-digital-age-your-youtube-journey/"><u>Paving the Way for Individuality in the Digital Age Your YouTube Journey</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-tecno-spark-10-4g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Tecno Spark 10 4G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-starting-windows-and-accessing-notepad-quickly/"><u>Sync Success: Starting Windows and Accessing Notepad Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-remedy-access-denied-on-windows/"><u>Tactics to Remedy 'Access Denied' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-path-to-clear-visible-notes-obsidian/"><u>The Ultimate Path to Clear, Visible Notes: Obsidian</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-the-tide-restoring-daylight-from-dark-theme/"><u>Turning the Tide: Restoring Daylight From Dark Theme</u></a></li>
</ul></div>

