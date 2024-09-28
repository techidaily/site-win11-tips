---
title: Bypass Incompatible System Mark on Windows 11
date: 2024-07-29T08:12:34.319Z
updated: 2024-07-30T08:12:34.319Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypass Incompatible System Mark on Windows 11
excerpt: This Article Describes Bypass Incompatible System Mark on Windows 11
keywords: Bypassing OS Errors,Win11 Compatibility Fix,Remove System Marks,XP/Vista Support Windows 11,Eliminate OS Warning,Windows Upgrade Assistance,Clear OS Incompatibility
thumbnail: https://thmb.techidaily.com/d09e418474d756f5a8ffe485c9482504fd4de6868009955288d3f3888a8492e7.jpg
---

## Bypass Incompatible System Mark on Windows 11

### Key Takeaways

* Windows 11 has stricter hardware requirements, resulting in a "System requirements not met" watermark for unsupported hardware.
* You can remove the watermark by modifying the Registry Editor or using the Group Policy Editor.
* New updates may cause the watermark to reappear, requiring you to repeat the removal steps.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

## Why Does Windows 11 Show the "System Requirements Not Met" Watermark?

 Microsoft Windows 11 has a much [stricter hardware requirement](https://www.makeuseof.com/can-your-pc-run-windows-11/) than its predecessors. If your system does not meet the minimum system requirement, including TPM 2.0, the installation will stop abruptly.

 However, with the problem came many workarounds that allowed you to [bypass the restriction and install Windows 11](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) on unsupported hardware.

 While Microsoft initially allowed installation on unsupported hardware with a warning about security issues and lack of future updates, it has now [decided to put a permanent watermark](https://www.makeuseof.com/microsoft-windows-11-unsupported-watermark/) to remind the users that their system is not supported. A similar message may also appear in the Settings app.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
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
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Removing the "System Requirement Not Met" Watermark in Windows 11

 If you have bypassed the TPM secure boot requirement to install Windows 11, you will likely see the System requirement not met watermark on your PC. Fortunately, you can remove the watermark by modifying a Windows registry entry or configuring a group policy using GPedit.

 If you are running Windows 11 on unsupported hardware, the newer operating system version will show a "System requirement not met" watermark in the bottom left corner of your screen.

 This may not be a concern if you use the OS in a virtual machine. But a watermark can stick out like a sore thumb for most people. Fortunately, you can remove the system requirements not met watermark with a registry hack and the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![Create new key for unsupported hardware notification cache.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/create-new-key-unsupported-hardware-notification-cache.jpeg)
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
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
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Group policy editor Hide messages when Windows system requirements are not met](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met.jpg)
5. Next, select and double-click on the policy to open its properties.
6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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


