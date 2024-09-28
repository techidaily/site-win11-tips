---
title: Altering Windows 11 Start Menu Preferences
date: 2024-08-16T01:07:31.205Z
updated: 2024-08-17T01:07:31.205Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows 11 Start Menu Preferences
excerpt: This Article Describes Altering Windows 11 Start Menu Preferences
keywords: Win11 Start Menu,Customize Start Screen,Adjust Windows UI,Menu Bar Changes,Launcher Settings,Interface Tweaks,Start Preferences
thumbnail: https://thmb.techidaily.com/cf39f69dc8e53bbf12e067db4360c2c57f8f63b2613fefed65baa25cc0a615d2.jpeg
---

## Altering Windows 11 Start Menu Preferences

### Key Takeaways

* You can remove the Home page from the Settings app in Windows 11 using the Group Policy Editor or the Registry Editor.
* The Group Policy Editor is only available in certain editions of Windows, but there are workarounds for enabling it in the Home edition.
* It's important to back up registry files or create a restore point before making changes, as incorrect modifications can cause serious issues.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.


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




