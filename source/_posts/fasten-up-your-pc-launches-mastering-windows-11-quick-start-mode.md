---
title: "Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode"
date: 2024-08-16T01:28:15.819Z
updated: 2024-08-17T01:28:15.819Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode"
excerpt: "This Article Describes Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode"
keywords: Win11 Quick Start,Fast PC Setup,Optimize W11 Boot,Pro PC Launch,Streamline OS Install,Speed Windows Setup,Efficient System Init
thumbnail: https://thmb.techidaily.com/8122148ffac7fe0a0e1d193ba9a136b7cccae081b7348173d3861777fbb2c2bf.jpg
---

## Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode

 Windows 11 has kept many of the useful features from its predecessor, including Fast Startup. As the name suggests, Fast Startup allows your computer to start up faster after a shutdown.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

## Why Should You Enable or Disable Fast Startup?

 With the release of Windows 8, Microsoft updated and renamed the default shutdown scenario as Fast Startup. It begins with the shutdown process by writing data to disk, similar to the hibernate process.

 However, unlike hibernation, it logs off all the user sessions and writes the remaining boot information to the hiberfil file. So, instead of loading everything from scratch, Windows loads data from the Hiberfil.sys file into memory when you restart your computer, significantly reducing the boot time.

 That said, Fast Startup is not without its shortcomings. For example, [according to Microsoft](http://docs.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup), you may face difficulties installing Windows updates on Fast Startup-enabled systems. Another reason is the [missing dual boot option because of the disabled delayed start function](https://www.makeuseof.com/windows-10-dual-boot-option-not-showing/). To learn more, read our explainer on [how Fast Startup works and why you should disable it](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/).

## How to Check if Fast Startup Is On or Off
![check fast startup status windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-fast-startup-status-windows-11-powershell.jpg)

 Often, a major Windows feature update may overwrite the power settings and disable Hibernate, thus disabling Fast Startup. Or you may experience unusual boot behavior even when you think Fast Startup is on. Before attempting to troubleshoot your computer, check if Fast Startup is on or off.

 You can use Command Prompt to check the Fast Startup status:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator**. Click **Yes** if prompted by User Account Control.
3. In the PowerShell console, copy and paste the following command and press Enter:  
`(GP "HKLM:\SYSTEM\CurrentControlSet\Control\Session Manager\Power")."HiberbootEnabled"`
4. The above command uses the **Get-Item (GP)** cmdlet to retrieve power-related settings and information about the **HiberBootEnabled** value in the Windows Registry.
5. A returned value of **1** means Fast Startup is On. A **0** would indicate Fast Startup as Off.

 If the hybrid boot is off, you can follow the steps below to enable Hibernation and then Fast Startup on your computer.

 To turn on Fast Startup, you must have Hibernate feature enabled on your computer. To check if Hibernate is enabled on your PC:

1. Press the **Win** key to open the **Start menu**.
2. Next, click on **Power** (power icon) and check if **Hibernate** is shown among other power options.
3. If disabled, the **Hibernate** option will not appear in the Power menu.

 Alternatively, check if Hibernate, while available, is hidden in the Control Panel. To do this:

1. Press **Win + R** to open **Run**.
2. Type **powercfg.cpl** and click **OK** to open Power Options in Control Panel.  
![choose what the power buttons do control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-what-the-power-buttons-do-control-panel-windows-11.jpg)
3. In the **Control Panel** dialog, click **Choose what the power buttons do** in the left pane.
4. Click **Change settings that are currently unavailable**.  
![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
5. Under **Shutdown settings**, check if **Hibernate** is available. If available, select **Hibernate** and click **Save changes** to show **Hibernate** in the Power menu.

 If the Hibernate option is missing, you can enable it using a Command Prompt command.

## How to Enable Hibernation in Windows 11
![turn on hibernate Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-hibernate-Windows-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

 Fast Startup is only available on systems compatible with the Hibernate feature available on almost all modern computers. However, this option is often disabled by default on lower-end systems.

 To enable Hibernate on Windows 11:

1. Type **cmd** in the Windows search bar.
2. Right-click on Command Prompt and select **Run as Administrator.**
3. In the Command Prompt window, type the following command and hit enter to turn on Hibernate:  
`Powercfg -h on`

 Now that you have enabled the hibernate feature, below are the various ways to enable and disable Fast Startup on your Windows computer.

## How to Turn On or Off Fast Startup in the Control Panel
![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 The easiest way to turn on Fast Startup is via the Control Panel's power settings. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. Go to **System and Security** and then click on **Power Options**.
4. In the left pane, click on **Choose what the power buttons do.**
5. Next, click the **Change settings that are currently unavailable** link.
6. Under the **Shutdown settings** section, check the **Turn on fast startup (recommended)** option to turn on the feature.
7. Uncheck the **Turn on fast startup option** to disable Fast Startup.
8. Click **Save changes** to apply the changes.

## How to Turn On or Off Fast Startup Using the Registry Editor
![turn on off fast startup registry register](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-fast-startup-registry-register.png)

 The next set of methods involves modifying the Windows registry. If something goes wrong, restoring your system to a functioning state can become difficult. So, [create a restore point](https://www.makeuseof.com/tag/create-system-restore-point/) before attempting to edit your registry entries. This will allow you to undo the changes if your system breaks during the process.

 Once done, do the following:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** when prompted by UAC.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power`
4. You can also copy/paste the above path for quicker navigation.
5. In the right-pane, scroll down and locate the DWORD value **HiberbootEnabled.**
6. Right-click on **HiberbootEnabled** and select **Modify**.
7. Type **1** in the **Value data** field and click **OK** to save the changes.
8. To turn off Fast Startup, enter **0** in the **Value data** field and click **OK**.
9. Close the Registry Editor and reboot your computer.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## How to Turn On or Off Fast Startup Using a Registry File
![turn on off registry file fast startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-registry-file-fast-startup.png)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t want to work with the Registry Editor, you can create a REG file and run it to achieve the same. Here’s how to do it.

1. Press the **Win** key, search for the **Notepad** app and open it.
2. To enable Fast Startup, copy and paste the following code in the Notepad file:  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000001`
3. To disable fast startup, copy and paste the following code instead.  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000000`
4. Click on **File** and select **Save As.**
5. Enter file name as **Enable\_fast\_startup.reg** or **Disable\_fast-startup.reg**.
6. Click on **Save as** type drop-down and select **All Files.**
7. Next, click **Save**.
8. Double-click on the **Enable\_fast-startup.reg** file to run. Then click **Yes**, and **Yes** to confirm the action.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Enable or Disable Fast Startup in the Group Policy Editor
![require use of fast startup group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/require-use-of-fast-startup-group-policy-editor-1.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Group Policy Editor allows you to configure your Group Policy settings to allow or restrict features as required. You can use it to enable or disable the Fast Startup feature on your Windows computer.

 Note that the Group Policy Editor is only available in Windows Edu, Pro, and Enterprise editions of the OS. If you are running Home, here's how to [access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Follow these steps to turn on Fast Startup on Windows 11:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open Group Policy Editor.
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\System\Shutdown`
4. In the right pane, right-click on **Require use of fast startup** and select **Edit**.
5. Select **Enabled** to turn on Fast Startup.
6. Or Select **Disabled** to turn off Fast Startup.
7. Click **Apply** and **OK** to save the changes.

## How to Turn Off Fast Startup Using the Command Prompt
![disable fast startup hibernate Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/disable-fast-startup-hibernate-Windows-2.png)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Since fast startup depends on the Hibernate feature, you can disable Hibernate to turn off Fast start. However, this will also turn off Hibernate in Power options, so tread carefully.

1. Press **Win + R** to open **Run**.
2. Type **cmd** into the box and then press **Ctrl + Shift + Enter** to open the Command Prompt as administrator.
3. In the Command Prompt window, type the following command and hit enter:  
`Powercfg -h off`
4. This will disable the Hibernate feature and also turn off Fast Startup.

## Making Your Windows 11 PC Boot Better

 The Fast Startup feature works like a charm on the older and slower systems with traditional HDDs or hybrid configurations. While you can shave off a few seconds even on an SSD, the incompatibility with dual boot and issues with Windows updates is an annoyance for many.

 Whether you want to turn Fast Startup on or off depends on what problem you are trying to solve. Try experimenting with the feature to see if it works for you. If not, you can always undo the changes.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



