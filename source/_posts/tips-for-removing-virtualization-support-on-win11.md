---
title: Tips for Removing Virtualization Support on Win11
date: 2024-08-16T02:30:05.444Z
updated: 2024-08-17T02:30:05.444Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## Why You May Need to Disable Hyper-V

 By design, only one virtualization tool can use the integrated virtualization extension, such as Intel VT-x and AMD-V, available on your processor. If you need to use third-party virtualization software, including VMware WorkStation and Virtual Box, you must disable the Hyper-V Hypervisor.

 You may also need to disable other hypervisor-dependent features, including Device Guard, Credential Guard, and memory integrity feature part of Core Isolation in Windows Security.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Check if Hyper-V Is Running on Windows 11
![System information hyper has been detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/system-information-hyper-has-been-detected.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can access the System Information app to determine if the Hyper-V virtualization is running. This is useful if you need to verify the Hyper-V hypervisor status after or before disabling it.

 To check the Hyper-V hypervisor status on your computer:

1. Press **Win + R** to open **Run**.
2. Type **msinfo32.exe** and click **OK** to open the apps.
3. Next, check if the following entry is available at the bottom of the details tab:  
`A hypervisor has been detected. Features required for Hyper-V will not be displayed.`
4. If yes, you'll need to disable Hyper-V, Memory integrity, and the Credential Guard feature, as discussed below, to use other virtualization tools without any error.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Disable Hyper-V via Windows Optional Features

 The [Windows Features dialog lets you add additional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) disabled by default in Windows 11\. You can also use it to disable some advanced features, including Hyper-V.

 Note that to fix the Hyper-V detected error, you must disable the Virtual Machine Platform and Windows Hypervisor Platform feature in addition to Hyper-V.

 To disable Hyper-V using the Windows Features dialog:

1. Press the **Win + R** key to open the **Run** dialog.
2. Type **control** and click **OK** to open the **Control Panel.**
3. In the **Control Panel,** click on **Programs**.  
![Control Panel programs in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/control-panel-programs-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Next, click on **Programs and Features.**
5. In the left pane, click on **Turn Windows features on or off.**  
![Turn Windows features on or off with Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/turn-windows-featureson-off-windows-11-control-panel.jpg)

1. In the Windows Features dialog, locate **Hyper-V.**
2. Uncheck the **Hyper-V** option to disable the feature.  
![Windows features dialog disable Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Windows-features-dialog-disable-hyper-v.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, scroll down and locate the **Virtual Machine Platform** and **Windows Hypervisor Platform** options.  
![Windows features dialog disable virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Windows-features-dialog-disable-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. Unselect both options and click **OK**.
5. Windows will uninstall Hyper-V and other features from your system.
6. Once done, restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. How to Disable Hyper-V Using BCDEDIT
![Disable Hyper-V command prompt BCDedit tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-command-prompt-bcdedit-tool.jpg)

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

## 3\. How to Uninstall Hyper-V Using the Command Prompt
![disable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-command-prompt.jpg)

 If the Windows Features dialog fails to remove Hyper-V, you can use the Command Prompt to disable the hypervisor. Here's how to do it:

1. [Open Command Prompt as administrator](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the Command Prompt window, type the following command and press Enter:  
`dism /online /disable-feature /featurename:Microsoft-hyper-v-all`
3. Upon execution, the DISM tool will disable Hyper-V and show the operation completed successfully message to indicate successful execution.
4. Type **exit,** press Enter to close the Command Prompt**,** and restart your PC.

 After the restart, you can run your games and other hypervisors without the error. If not, open the Windows Features dialog, disable the **Virtual Machine Platform** and **Windows Hypervisor Platform** options, and restart your PC to turn off Hyper-V Hypervisor.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. How to Disable Hyper-V Using PowerShell
![Powershell disable Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/powershell-disable-hyper-v.jpg)

 If you prefer PowerShell, use the WindowsOptionalFeature cmdlet to disable Hyper-V in Windows 11\. To do this, [launch PowerShell with admin privileges](https://www.makeuseof.com/windows-open-command-prompt-powershell/) and execute the command. Here's how to do it:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. Click **Yes** when prompted by **User Account Control.**
4. In the PowerShell window, copy and paste the command below and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
5. Wait for the process to complete. Once done, close PowerShell and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
2. Click **OK** to save the changes.
3. Next, in Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard`
4. In the right pane, check if the **EnableVirtualizationBasedSecurity** value exists. If not, right-click the **DeviceGuard** subkey and select **New > DWORD (32-bit) Value**.  
![Windows registry editor Device Guard subkey create new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-device-guard-subkey-create-new-dword-value.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Next, rename the key as **EnableVirtualizationBasedSecurity** and set its value to **0**.  
![Windows registry editor device guard subkey value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/windows-registry-editor-device-guard-subkey-value-0.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

 Restart your computer to apply the changes and disable Device Guard and Credential Guard. If you ever need to enable these features, modify the value data and change it to **1**.

## Disable Hyper-V in Windows 11 to Run Third-Party Virtualization Tools and Apps

 Hyper-V is an excellent utility if you want an out-of-the-box virtualization solution. However, you must disable Hyper-V to use third-party virtualization software, including VirtualBox and WMware Workstation.

 Fortunately, you can easily disable the Hyper-V Hypervisor and other Virtualization-based Security solutions to use third-party hypervisors without errors.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



