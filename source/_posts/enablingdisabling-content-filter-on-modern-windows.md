---
title: Enabling/Disabling Content Filter on Modern Windows
date: 2024-10-25T17:19:20.979Z
updated: 2024-11-01T16:37:46.896Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Content Filter on Modern Windows
excerpt: This Article Describes Enabling/Disabling Content Filter on Modern Windows
keywords: Disable Windows Filtering,Enable OS Filter Off,Windows Content Filter Toggle,Modern OS Block Control,Windows Filters Switch,Change Windows Content Restriction,Adjust Windows Content Filtering
thumbnail: https://thmb.techidaily.com/904e4358c32651c8870cd752598cbad0b1afa3205d185e4b265bf0a0d105bd32.jpg
---

## Enabling/Disabling Content Filter on Modern Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To enable the SmartScreen filter, type **1** in the **Value data** field and click **O**K.
5. Close the **Registry Editor** and restart your PC to apply the changes.

 You can further tweak the registry to create a new **String Value** to set the blocking level to **Warn** or **Block**. Using **Warn** will show a SmartScreen warning with an option to proceed. In contrast, the **Block** option will show a warning and block the app from running on your computer.

 To set a new ShellSmartScreenLevel String Value in Registry Editor:

1. Right-click on the **System** subkey and select **New > String Value**. Rename the value as **ShellSmartScreenLevel**.  
![registry editor create New String ShellSmartScreenLevel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/registry-editor-create-new-string-shellsmartscreenlevel.jpg)
2. Next, right-click on **ShellSmartScreenLevel** and select **Modify**.;  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/new-elevate-your-messaging-game-with-hidden-whatsapp-secrets-for-2024/"><u>[New] Elevate Your Messaging Game with Hidden WhatsApp Secrets for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-best-aggregate-video-chat-and-multi-user-platforms-for-2024/"><u>[Updated] Best Aggregate Video Chat & Multi-User Platforms for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-instant-video-posting-to-twitter-from-phone-avoid-the-retweet-for-2024/"><u>[Updated] Instant Video Posting to Twitter From Phone – Avoid the Retweet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-enlarge-pins-best-practices-in-windows-1111/"><u>Boost Security, Enlarge Pins: Best Practices in Windows 11/11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-samsung-galaxy-a23-5g-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Samsung Galaxy A23 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-on-windows-a-step-by-step-guide/"><u>Converting Gmail To Outlook on Windows – A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-loading-messages-in-windows-discord-client/"><u>Correcting Non-Loading Messages in Windows Discord Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-the-words-start-talking-windows-11s-method/"><u>Cut the Words, Start Talking: Windows 11'S Method</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-nord-ce-3-5g-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Nord CE 3 5G?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-mastering-video-edits-post-upload-techniques/"><u>In 2024, Mastering Video Edits Post-Upload Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-clear-up-a-white-login-screen-on-windows-1011/"><u>Tips to Clear Up a White Login Screen on Windows 10/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-civi-3-disney-100th-anniversary-edition-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi Civi 3 Disney 100th Anniversary Edition Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-potential-top-7-efficiency-enhancing-widgets-for-win-11/"><u>Unleashing Your Potential: Top 7 Efficiency Enhancing Widgets for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-and-dxgidll-fix-for-a-missing-crucial-file/"><u>Win11 & Dxgi.dll: Fix for a Missing Crucial File</u></a></li>
<li><a href="https://win11.techidaily.com/winning-torrent-clients-the-best-of-windows-list/"><u>Winning Torrent Clients: The Best of Windows List</u></a></li>
</ul></div>

