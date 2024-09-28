---
title: Revising the Start Page to a New Preference in Win11
date: 2024-08-16T01:32:39.262Z
updated: 2024-08-17T01:32:39.262Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revising the Start Page to a New Preference in Win11
excerpt: This Article Describes Revising the Start Page to a New Preference in Win11
keywords: Win11 Start Page Revision,New Windows Start Choice,Update Win11 Defaults,Redesign Win11 Homepage,Optimize Win11 Settings,Customize Win11 Launcher,Enhance Win11 UI
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Revising the Start Page to a New Preference in Win11

### Key Takeaways

* You can remove the Home page from the Settings app in Windows 11 using the Group Policy Editor or the Registry Editor.
* The Group Policy Editor is only available in certain editions of Windows, but there are workarounds for enabling it in the Home edition.
* It's important to back up registry files or create a restore point before making changes, as incorrect modifications can cause serious issues.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
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
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
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
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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






