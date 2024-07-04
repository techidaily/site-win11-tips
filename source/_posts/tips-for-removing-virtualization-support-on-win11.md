---
title: Tips for Removing Virtualization Support on Win11
date: 2024-06-25T16:12:38.839Z
updated: 2024-06-26T16:12:38.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Removing Virtualization Support on Win11
excerpt: This Article Describes Tips for Removing Virtualization Support on Win11
keywords: Win11 Remove Extras,VM Support Elimination,Win11 Optimize Performance,Virtualization Removal Guide,Uninstall Win11 Tools,Enhance Windows 11 Speed,Disable Win11 Features
thumbnail: https://thmb.techidaily.com/1b2195440e349b5f0884d1401c71f047053f6f52811a1360983fce9511380f91.jpg
---

## Tips for Removing Virtualization Support on Win11

### Key Takeaways

* Hyper-V can conflict with third-party virtualization tools and apps on Windows 11, causing errors when launching them. Disabling Hyper-V can resolve this issue.
* You can disable Hyper-V using the Windows Features dialog or the BCDEdit tool. Restart your PC after making changes to apply them.
* If the Windows Features dialog fails, use the Command Prompt or PowerShell to disable Hyper-V. Uninstall Hyper-V's virtual network adapters and disable Memory Integrity and Device Guard/Credential Guard for optimal performance.

 Hyper-V comes pre-installed on Windows 11 computers. While this virtualization tool is not available out of the box on the Home edition of the OS, you can install it with a batch script.

 Unfortunately, Hyper-V can conflict with third-party apps on your PC, including other virtualization tools such as VMWare Workstation, VirtualBox, and emulators. As a result, you may encounter the Hyper-V detected error when trying to launch an app, PC games, or hardware tuning utilities.

 Luckily, you can disable Hyper-V in Windows 11 with the help of the classic Windows Features dialog, Command Prompt, and PowerShell.

## Why You May Need to Disable Hyper-V

 By design, only one virtualization tool can use the integrated virtualization extension, such as Intel VT-x and AMD-V, available on your processor. If you need to use third-party virtualization software, including VMware WorkStation and Virtual Box, you must disable the Hyper-V Hypervisor.

 You may also need to disable other hypervisor-dependent features, including Device Guard, Credential Guard, and memory integrity feature part of Core Isolation in Windows Security.

## How to Check if Hyper-V Is Running on Windows 11 ![System information hyper has been detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/system-information-hyper-has-been-detected.jpg)

 You can access the System Information app to determine if the Hyper-V virtualization is running. This is useful if you need to verify the Hyper-V hypervisor status after or before disabling it.

 To check the Hyper-V hypervisor status on your computer:

1. Press **Win + R** to open **Run**.
2. Type **msinfo32.exe** and click **OK** to open the apps.
3. Next, check if the following entry is available at the bottom of the details tab:  
`A hypervisor has been detected. Features required for Hyper-V will not be displayed.`
4. If yes, you'll need to disable Hyper-V, Memory integrity, and the Credential Guard feature, as discussed below, to use other virtualization tools without any error.

## 1\. How to Disable Hyper-V via Windows Optional Features

 The [Windows Features dialog lets you add additional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) disabled by default in Windows 11\. You can also use it to disable some advanced features, including Hyper-V.

 Note that to fix the Hyper-V detected error, you must disable the Virtual Machine Platform and Windows Hypervisor Platform feature in addition to Hyper-V.

 To disable Hyper-V using the Windows Features dialog:

1. Press the **Win + R** key to open the **Run** dialog.
2. Type **control** and click **OK** to open the **Control Panel.**
3. In the **Control Panel,** click on **Programs**.  
![Control Panel programs in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/control-panel-programs-windows-11.jpg)
4. Next, click on **Programs and Features.**
5. In the left pane, click on **Turn Windows features on or off.**  
![Turn Windows features on or off with Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/turn-windows-featureson-off-windows-11-control-panel.jpg)

1. In the Windows Features dialog, locate **Hyper-V.**
2. Uncheck the **Hyper-V** option to disable the feature.  
![Windows features dialog disable Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Windows-features-dialog-disable-hyper-v.jpg)
3. Next, scroll down and locate the **Virtual Machine Platform** and **Windows Hypervisor Platform** options.  
![Windows features dialog disable virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Windows-features-dialog-disable-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. Unselect both options and click **OK**.
5. Windows will uninstall Hyper-V and other features from your system.
6. Once done, restart your PC to apply the changes.

## 2\. How to Disable Hyper-V Using BCDEDIT ![Disable Hyper-V command prompt BCDedit tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-command-prompt-bcdedit-tool.jpg)

 You can disable Hyper-V in boot configuration using the BCDEdit tool. This is useful if you only want to deactivate Hyper-V and not uninstall it completely.

 To disable Hyper-V using BCDEdit:

1. Press the **Win** key and type **cmd**.
2. Right-click on the **Command Prompt** and select **Run as administrator.**
3. In the Command Prompt window, type the following command and press Enter:  
`bcdedit /set hypervisorlaunchtype off`
4. When the success message appears, close the Command Prompt and restart your PC to apply the changes.
5. If you need to activate Hyper-V again, use the following command:  
`bcdedit /set hypervisorlaunchtype auto`
6. Make sure to restart your PC to apply the changes.

 Additionally, you can use the BCDEdit tool to perform other advanced tasks, such as [deleting the old boot menu options](https://www.makeuseof.com/tag/delete-boot-menu-options-windows/) and [adding a safe mode shortcut to the Windows 11 boot menu](https://www.makeuseof.com/windows-11-add-safe-mode-boot-menu/).

## 3\. How to Uninstall Hyper-V Using the Command Prompt ![disable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-command-prompt.jpg)

 If the Windows Features dialog fails to remove Hyper-V, you can use the Command Prompt to disable the hypervisor. Here's how to do it:

1. [Open Command Prompt as administrator](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the Command Prompt window, type the following command and press Enter:  
`dism /online /disable-feature /featurename:Microsoft-hyper-v-all`
3. Upon execution, the DISM tool will disable Hyper-V and show the operation completed successfully message to indicate successful execution.
4. Type **exit,** press Enter to close the Command Prompt**,** and restart your PC.

 After the restart, you can run your games and other hypervisors without the error. If not, open the Windows Features dialog, disable the **Virtual Machine Platform** and **Windows Hypervisor Platform** options, and restart your PC to turn off Hyper-V Hypervisor.

## 4\. How to Disable Hyper-V Using PowerShell ![Powershell disable Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/powershell-disable-hyper-v.jpg)

 If you prefer PowerShell, use the WindowsOptionalFeature cmdlet to disable Hyper-V in Windows 11\. To do this, [launch PowerShell with admin privileges](https://www.makeuseof.com/windows-open-command-prompt-powershell/) and execute the command. Here's how to do it:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. Click **Yes** when prompted by **User Account Control.**
4. In the PowerShell window, copy and paste the command below and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
5. Wait for the process to complete. Once done, close PowerShell and restart your PC to apply the changes.

## How to Uninstall the Hyper-V Virtual Network Adapter

 During the restart following the uninstallation of Hyper-V, you may frequently encounter the message, "We couldn't complete the updates, undoing changes." To resolve this issue, ensure the Hyper-V virtual network adapters are deleted from your PC. You can delete the virtual network adapter from Device Manager.

 To delete Hyper-V's virtual network adapters:

1. Press **Win + R** to open **Run**.
2. Type **dvmgmt.msc** and click **OK** to open **Device Manager.**
3. In Device Manager, expand the **Network Adapters** section to locate the **Hyper-V Virtual network adapters**.
4. If no virtual adapters associated with Hyper-V are listed, click **View** and select **Show hidden devices.**  
![device manager show hidden devices windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/device-manager-show-hidden-devices-windows-11.jpg)
5. Right-click on the **Hyper-V Virtual Ethernet Adapter** and select **Uninstall device**.  
 Do not remove the **Microsoft Wi-Fi Direct Virtual Adapter.**
6. Click **Uninstall** to confirm the action.  
![Uninstall Hyper-V virtual adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/uninstall-hyper-v-virtual-adapter.jpg)
7. Repeat the steps to delete all the virtual network adapters associated with Hyper-V.
8. Once done, close Device Manager and restart your PC. Next, uninstall Hyper-V and check for any improvements.

## How to Turn Off Virtualization-Based Security (Memory Integrity)

 If you encounter the Hyper-V detected issue even after you disable Hyper-V, try to disable the Memory integrity feature in Windows Security. The Memory integrity feature is part of Core Isolation. It helps prevent hackers from accessing and infecting high-security processes using malicious code.

 By default, Windows disables the Memory integrity feature to avoid conflict with apps and device drivers due to incompatibility issues. This can also cause issues with third-party virtualization tools and programs needing access to your system's virtualization hardware.

 To turn off Memory integrity in Windows Security:

1. Press **Win + I** to open the **Settings** app.
2. In the left pane, click on the **Privacy & security** tab.  
![Privacy and security Windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/privacy-and-security-windows-security.jpg)
3. Next, click on **Windows Security**.
4. Under the **Protection areas** section, click on **Device security.**  
![Windows 11 privacy and security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Windows-11-privacy-and-security.jpg)
5. Next, click on **Core isolation details** under the **Core isolation** section.  
![Windows device security core isolation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-device-security-core-isolation.jpg)
6. Toggle the switch under **Memory integrity** to turn it **Off**.  
![Windows 11 core isolation memory integrity turned off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-11-core-isolation-memory-integrity-off.jpg)
7. Restart your PC to apply the changes.

## How to Disable Device Guard and Credential Guard

 Device Guard and Credential Guard don't play well with other virtualization software, including VMware Workstation. You may encounter an error saying Device Guard/Credential Guard is enabled when trying to power on the VMware Workstation.

 Since you intend to use third-party virtualization software, you can safely disable Device Guard and Credential Guard using the Registry Editor.

 That said, modifying the Windows Registry involves risk. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting any modifications.

 To disable Device Guard and Credential Guard:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK** to open **Registry Editor**.
3. In Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa`
4. In the right pane, locate the **LsaCfgFlags** **DWORD** value. You'll need to create a new key if no such value exists.  
![Windows registry editor Lsa subkey create New value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-lsa-subkey-create-new-value.jpg)
5. To create a new key, right-click the **Lsa** subkey in the left pane and select **New < DWORD (32-bit)** **value**. Rename the value as **LsaCfgFlags**.

1. Next, double-click on **LsaCfgFlags** and type **0** in the **Value data** field.  
![Windows registry editor Lsa subkey value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-lsa-subkey-value-0.jpg)
2. Click **OK** to save the changes.
3. Next, in Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard`
4. In the right pane, check if the **EnableVirtualizationBasedSecurity** value exists. If not, right-click the **DeviceGuard** subkey and select **New > DWORD (32-bit) Value**.  
![Windows registry editor Device Guard subkey create new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-device-guard-subkey-create-new-dword-value.jpg)
5. Next, rename the key as **EnableVirtualizationBasedSecurity** and set its value to **0**.  
![Windows registry editor device guard subkey value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-device-guard-subkey-value-0.jpg)
6. Click **OK** to save the changes.

 Restart your computer to apply the changes and disable Device Guard and Credential Guard. If you ever need to enable these features, modify the value data and change it to **1**.

## Disable Hyper-V in Windows 11 to Run Third-Party Virtualization Tools and Apps

 Hyper-V is an excellent utility if you want an out-of-the-box virtualization solution. However, you must disable Hyper-V to use third-party virtualization software, including VirtualBox and WMware Workstation.

 Fortunately, you can easily disable the Hyper-V Hypervisor and other Virtualization-based Security solutions to use third-party hypervisors without errors.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-for-winerror-0x80072746-in-outlook/"><u>The Ultimate Fix for WinError 0X80072746 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-transition-website-to-desktop-compatibility/"><u>Seamless Transition: Website to Desktop Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-identifying-devices-with-windows-tools/"><u>In-Depth Analysis: Identifying Devices with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-operation-requirement-issues-on-windows-11-and-11/"><u>Demystifying Operation Requirement Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-machine-how-to-optimize-windows-11-settings/"><u>Master Your Machine: How to Optimize Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-critical-alerts-when-to-reset-windows/"><u>Nine Critical Alerts: When to Reset Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-users-through-admin-level-execution-woes/"><u>Guiding Users Through Admin-Level Execution Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-virtual-realities-shortcomings-for-2024/"><u>Exploring Virtual Realities' Shortcomings for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-picture-perfect-support-portal/"><u>[Updated] Picture Perfect Support Portal</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discords-best-servers-for-finding-a-mate/"><u>[New] 2024 Approved  Discord's Best Servers for Finding a Mate</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-samsung-galaxy-z-flip-5-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Samsung Galaxy Z Flip 5 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-from-one-to-many-building-your-reputation-by-cloning-yourself-on-tiktok/"><u>[New] From One to Many  Building Your Reputation by Cloning Yourself on TikTok</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pixels-to-perfection-design-tips-for-captivating-banners/"><u>In 2024, Pixels to Perfection  Design Tips for Captivating Banners</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-photoshop-stability-enhancement-essentiality/"><u>2024 Approved  Photoshop Stability Enhancement - Essentiality</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-top-rated-free-online-libraries-for-guitarists-high-quality-melodies-and-visuals-for-2024/"><u>Updated Top-Rated FREE Online Libraries for Guitarists High-Quality Melodies & Visuals for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-immortalize-gameplay-glories-with-samsung-devices/"><u>[Updated] In 2024, Immortalize Gameplay Glories with Samsung Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-xiaomi-14-ultra-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Xiaomi 14 Ultra Screen to PC Using WiFi | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>