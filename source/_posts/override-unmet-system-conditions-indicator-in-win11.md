---
title: Override Unmet System Conditions Indicator in Win11
date: 2024-12-21T21:20:15.032Z
updated: 2024-12-27T18:26:39.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Override Unmet System Conditions Indicator in Win11
excerpt: This Article Describes Override Unmet System Conditions Indicator in Win11
keywords: Windows Override Conditions,System Status Override,Win11 Condition Adjustment,Unmet Conditions Fix,Indicator Overriding,OS Exception Handling,Compatibility Settings Tweaks
thumbnail: https://thmb.techidaily.com/de1ed084e4e7384a82650c7f3de48e6d0c70a32a5eeabfb4f334c0a2440c4fac.jpeg
---

## Override Unmet System Conditions Indicator in Win11

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
3. Next, right-click on the new key and select **New > DWORD (64-bit)** value.
4. Rename the value as **SV2**.
5. Next, modify the **SV2 DWORD** value and set its **Value data** to **2**.
6. Click **OK** to save the changes.

 The watermark may reappear with new updates. So, you must repeat the steps after installing the update to keep your desktop clean.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Select **Enabled** to enable the policy setting.  
![Group policy editor Hide messages when Windows system requirements are not met enable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/group-policy-editor-hide-messages-when-windows-system-requirements-are-not-met-enable.jpg)
7. Click **Apply** and **OK** to save the changes.

 Now, you need to restart your computer to apply the changes. After the restart, the "minimum system requirements are not met message" will not be displayed on the desktop.;

 If you need to revert the changes, open the **Hide messages when Windows system requirements are not met** policy again and set it to **Not Configured**.

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
<li><a href="https://eaxpv-info.techidaily.com/1-top-performing-h265hevc-accelerator-software-effortless-transcoding-for-enhanced-hd-videos/"><u>1. Top Performing H.265/HEVC Accelerator Software: Effortless Transcoding for Enhanced HD Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-art-of-engaging-crafting-compelling-reddit-content/"><u>2024 Approved The Art of Engaging Crafting Compelling Reddit Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-best-tools-for-road-tripping-films/"><u>2024 Approved The Best Tools for Road Tripping Films</u></a></li>
<li><a href="https://win-answers.techidaily.com/age-of-empires-4-lag-solutions-techniques-for-uninterrupted-play/"><u>Age of Empires 4 Lag Solutions: Techniques for Uninterrupted Play</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/chorus-cache-secure-and-inspect-audio-recordings/"><u>Chorus Cache Secure & Inspect Audio Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-erratic-power-estimate-display-in-windows-11-os/"><u>Correcting the Erratic Power Estimate Display in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-your-gaming-experience-with-faster-yuzu/"><u>Ignite Your Gaming Experience with Faster Yuzu</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-c51-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Poco C51 Phone Without Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mouse-keys-unite-wake-up-sleeping-devices-post-sleep/"><u>Mouse, Keys Unite! Wake Up Sleeping Devices Post-Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prolific-powerhouses-in-win-11-best-productivity-widgets-list/"><u>Prolific Powerhouses in Win 11: Best Productivity Widgets List</u></a></li>
<li><a href="https://some-guidance.techidaily.com/setting-up-your-capture-device-on-windows-game-bar-enabling-video-and-audio-recording-via-xboxdvr/"><u>Setting Up Your Capture Device on Windows Game Bar – Enabling Video & Audio Recording via XboxDVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-key-to-unhindered-play-fixing-intermittent-ps4-connection-in-windows/"><u>The Key to Unhindered Play: Fixing Intermittent PS4 Connection in Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/thorough-method-rebuilding-graphic-card-drivers/"><u>Thorough Method: Rebuilding Graphic Card Drivers</u></a></li>
</ul></div>

