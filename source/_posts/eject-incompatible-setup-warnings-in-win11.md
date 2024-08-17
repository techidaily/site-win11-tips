---
title: Eject Incompatible Setup Warnings in Win11
date: 2024-08-16T01:57:42.351Z
updated: 2024-08-17T01:57:42.351Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eject Incompatible Setup Warnings in Win11
excerpt: This Article Describes Eject Incompatible Setup Warnings in Win11
keywords: Windows Eject Errors,Win11 Compatibility Issues,Setup Warning Fixes,Installation Alert Removal,Incompatible Warning Solutions,System Update Recommendations,Warnings in Windows 11 Update
thumbnail: https://thmb.techidaily.com/474c5054a0eaa723712bc3725331bacf73663ebfef0031bd8bc1879804e39c8f.jpg
---

## Eject Incompatible Setup Warnings in Win11

### Key Takeaways

* Windows 11 has stricter hardware requirements, resulting in a "System requirements not met" watermark for unsupported hardware.
* You can remove the watermark by modifying the Registry Editor or using the Group Policy Editor.
* New updates may cause the watermark to reappear, requiring you to repeat the removal steps.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

## 1\. Remove the "System Requirement Not Met" Watermark Using the Registry Editor

 If you see the "system requirements not met" watermark on your PC, you can remove it by modifying a DWORD value in Registry Editor.

 As modifying the Windows Registry involves risk, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes using the Registry Editor.

 Follow these steps to remove the "System requirement not met" watermark in Windows 11:

1. Press **Win + R** to open the **Run** dialog.
2. Type **regedit** and click **OK** to open the Registry Editor.
3. In the Registry Editor, navigate to the following path. You can also copy and paste the path in the Registry Editor address bar for quick navigation.  
HKEY_CURRENT_USER\Control Panel\UnsupportedHardwareNotificationCache
4. In the right pane, right-click on the **SV2 DWORD** value and select **Modify**.
5. Enter **0** into the value data field.  
![Edit sv2 value to remove the system requirement not met watermark.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/edit-sv2-value-remove-system-requirement-not-met-watermark.jpg)
6. Click **OK** to save the changes.
7. Close the Registry Editor and restart your PC to apply the changes. After restarting, Windows 11 will no longer show the unsupported hardware watermark.

 If you don’t have the UnsupportedHardwareNotificationCache key, you must create a new one and set its value. To do this:

1. In Registry Editor, right-click the **Control** key (**HKEY\_CURRENT\_USER\\Control Panel**) and select **New > Key.**
2. Next, rename the key as **UnsupportedHardwareNotificationCache.**  
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the System Requirement Not Met Message Using the Group Policy Editor

 You can use the Group Policy Editor to turn off the System requirements not met message in Windows 11\. To achieve this, we’ll need to modify the **Hide messages when Windows system requirements are not met** Group Policy and set it to enabled.

 Only the Windows 11 Pro, Enterprise, and Education edition comes with the Local Group Policy Editor installed by default. If running the Home edition, follow these steps to [enable the Group Policy Editor in Windows Home](http://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To turn off the System requirement not message using GPedit:

1. Press **Win + R** to open the **Run** dialog.
2. Type **gpedit.msc** and click **OK** to open **Group Policy Editor**. Click **Yes** if prompted by **User Account Control**.
3. In Group Policy Editor, navigate to the following location:  
`Local Computer Policy > Computer Configuration > Administrative Templates > System`
4. In the right pane, scroll down and locate the **Hide messages when Windows system requirements are not met** policy.  
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.


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
<li><a href="https://instagram-video-files.techidaily.com/new-strategies-to-skyrocket-instagram-video-views/"><u>[New] Strategies to Skyrocket Instagram Video Views</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-melodymaster-recording-software-guide/"><u>[Updated] 2024 Approved  MelodyMaster Recording Software Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mastering-ps3-classics-on-your-pc-with-top-tools/"><u>[Updated] Mastering PS3 Classics on Your PC with Top Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-pixelplay-logger-analysis/"><u>2024 Approved  PixelPlay Logger Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-get-the-most-out-of-the-windows-11-start-menu/"><u>7 Ways to Get the Most Out of the Windows 11 Start Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-deals-bf-black-friday-612-win10-for-life/"><u>Best Deals: BF Black Friday - $6.12 Win10 for Life</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/boosting-or-slowing-down-the-netflix-playback-rate-guide-for-2024/"><u>Boosting or Slowing Down  The Netflix Playback Rate Guide for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/boosting-views-with-captivating-intros-filmed-in-imovie/"><u>Boosting Views with Captivating Intros Filmed in iMovie</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bringing-pinnacle-clarity-to-your-w11-desktop-wallpaper/"><u>Bringing Pinnacle Clarity to Your W11 Desktop Wallpaper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-software-aid-the-best-windows-apps-that-facilitate-mac-switch/"><u>Crucial Software Aid: The Best Windows Apps That Facilitate MAC Switch</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Honor X8b | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-xiaomi-13t-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Xiaomi 13T Phone? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-xiaomi-redmi-a2-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Xiaomi Redmi A2 Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-folder-management-resetting-critical-components-on-ws11/"><u>Effortless Folder Management: Resetting Critical Components on WS11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/enhance-your-imagery-a-step-by-step-guide-for-instagram-videos/"><u>Enhance Your Imagery  A Step-by-Step Guide for Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-iomap64-syscall-failures-on-windows-pcs/"><u>Essential Fixes for IOMap64 Syscall Failures on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-window-11-settings-for-clear-prime-video-texts/"><u>Harmonize Window 11 Settings for Clear Prime Video Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-edges-from-popping-up/"><u>How to Stop Microsoft Edges From Popping Up</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6s-to-other-iphone-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6s To Other iPhone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-local-security-not-functioning-warning/"><u>Immediate Actions for 'Local Security Not Functioning' Warning</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-the-essential-audio-interface-for-your-podcaster/"><u>In 2024, The Essential Audio Interface for Your Podcaster</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-honor-play-7t-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Honor Play 7T FRP</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-this-article-we-will-introduce-you-vn-video-editor-pro-apk-download-and-bring-you-some-of-its-alternatives-for-2024/"><u>In This Article, We Will Introduce You Vn Video Editor Pro Apk Download and Bring You some of Its Alternatives for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-clear-desktop-instructions-for-windows-recycle-bin-auto-empty/"><u>Master Clear Desktop: Instructions for Windows Recycle Bin Auto-Empty</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-proxy-configurations-on-windows-11/"><u>Mastering the Art of Proxy Configurations on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-books-8-effective-studying-tips-on-windows/"><u>Mastering the Books: 8 Effective Studying Tips on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-unnecessary-system-updates-on-windows-11/"><u>Mute Unnecessary System Updates on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-clipchamps-windows-11-install-troubles/"><u>Navigate Through ClipChamp's Windows 11 Install Troubles</u></a></li>
<li><a href="https://vp-tips.techidaily.com/next-gen-sound-and-vision-leading-devices-of-24-for-2024/"><u>Next-Gen Sound and Vision  Leading Devices of '24 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-bandwidth-visualization-for-users/"><u>Real-Time Bandwidth Visualization for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-old-school-gaming-adventures-integrate-trophies-through-retroarch/"><u>Revitalize Your Old-School Gaming Adventures - Integrate Trophies Through Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-sketch-vs-prtsc-which-screen-capture-wins/"><u>Snip & Sketch Vs. PrtSc: Which Screen Capture Wins?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-undetermined-value-messages-on-windows/"><u>Solutions for 'Undetermined' Value Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-successfully-locating-policy-management-tools/"><u>Steps to Successfully Locating Policy Management Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-administrator-security-configs/"><u>Steps to Tackle Windows Administrator Security Configs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-removing-signature-rejection-on-pcs/"><u>Strategies for Removing Signature Rejection on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-savvy-tips-restarting-windows-11-apps/"><u>Tech Savvy Tips: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-shutdown-playbook-avoiding-windows-11-activities/"><u>The Shutdown Playbook: Avoiding Windows 11 Activities</u></a></li>
<li><a href="https://extra-information.techidaily.com/transform-video-quality-on-tiktok-2-ways/"><u>Transform Video Quality on TikTok (2 Ways)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-notepads-display-from-light-to-dark-theme-win-11/"><u>Transitioning Notepad's Display From Light to Dark Theme (Win 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-directdraw-a-focused-guide-for-win11-enthusiasts/"><u>Troubleshooting DirectDraw: A Focused Guide for Win11 Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-oculus-errors-on-ws11wc10-systems/"><u>Troubleshooting Oculus Errors on WS11/WC10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfettered-functions-embrace-tiny11s-power/"><u>Unfettered Functions: Embrace Tiny11's Power</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-the-full-potential-of-windows-photos-app-with-visual-and-audio-tweaks-for-2024/"><u>Unlock the Full Potential of Windows Photos App with Visual & Audio Tweaks for 2024</u></a></li>
</ul></div>
