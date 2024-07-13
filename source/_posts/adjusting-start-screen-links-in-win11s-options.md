---
title: Adjusting Start Screen Links in Win11's Options
date: 2024-07-12T16:47:48.181Z
updated: 2024-07-13T16:47:48.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Start Screen Links in Win11's Options
excerpt: This Article Describes Adjusting Start Screen Links in Win11's Options
keywords: Windows Start Link Customization,Win11 Settings Adjustment,Start Menu URL Update,Win11 UI Tweaks,Start Screen Link Edit,Windows 11 Config Options,System Preferences Change
thumbnail: https://thmb.techidaily.com/80c97e26a42ec85426e926d8a619570205ae66ef3c841d342bad4a1013bf8d86.jpg
---

## Adjusting Start Screen Links in Win11's Options

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
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-apple-iphone-6-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On Apple iPhone 6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-yellow-discoloration-in-windows-laptop-screens/"><u>Resolving Yellow Discoloration in Windows Laptop Screens</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-mastering-multilingual-subtitling-a-comprehensive-approach-vimeo/"><u>In 2024, Mastering Multilingual Subtitling  A Comprehensive Approach (Vimeo)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-giggles-galore-7-entertaining-video-sets-for-chuckleheads-for-2024/"><u>[Updated] Giggles Galore  7 Entertaining Video Sets for Chuckleheads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-labyrinth-a-guide-to-windows-11s-services/"><u>Navigating the Labyrinth: A Guide to Windows 11'S Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-writability-enabledisable-ntfs-compression/"><u>Unlocking Windows 11' Writability: Enable/Disable NTFS Compression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-moving-windows-11-folders-with-tabs/"><u>Maximizing Efficiency: Moving Windows 11 Folders with Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-directx-downloads-issue-in-os/"><u>Mending DirectX Downloads Issue in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-windows-dialogue-the-freedomgpt-way/"><u>Open Windows Dialogue: The FreedomGPT Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-mp3-conversion-windows-and-imgburn-a-guide-to-creating-professional-audio-cds/"><u>Streamlining MP3 Conversion: Windows & ImgBurn - A Guide to Creating Professional Audio CDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amplify-vram-in-windows-os/"><u>Strategies to Amplify VRAM in Windows OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-top-10-economical-platforms-for-seamless-online-video-meetings-for-2024/"><u>The Top 10 Economical Platforms for Seamless Online Video Meetings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-stalled-google-nearby-share-on-pc/"><u>Unveiling Fixes for Stalled Google Nearby Share on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-mystery-fixing-windows-error-code-0x0000004e/"><u>Tackling the Mystery: Fixing Windows Error Code 0X0000004E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steam-deck-windows-installation-essentials/"><u>Steam Deck: Windows Installation Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-esd-to-iso-transformation-on-windows-pcs/"><u>Step-by-Step ESD to ISO Transformation on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-winvpn-error-remote-computer-not-reachable/"><u>Quick Guide: WinVPN Error Remote Computer Not Reachable</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-cushy-comfort-best-idle-pc-games/"><u>[Updated] 2024 Approved  Cushy Comfort  Best Idle PC Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/run-a-local-and-free-chatgpt-clone-on-your-windows-pc-with-gpt4all/"><u>Run a Local and Free ChatGPT Clone on Your Windows PC With GPT4All</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-finding-your-perfect-tone-strategies-for-personalized-vocal-change/"><u>Updated Finding Your Perfect Tone Strategies for Personalized Vocal Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-techniques-for-scrubbing-windows-safety-files/"><u>Simplified Techniques for Scrubbing Windows' Safety Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-failure-error-0x8024800c/"><u>Resolving Windows Update Failure (Error 0X8024800C)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-now-error-xc0f1103f-in-windows-11/"><u>Overcoming GeForce Now Error Xc0f1103f in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-xiaomi-civi-3-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Xiaomi Civi 3</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-essential-skills-for-recording-private-whatsapp-talks/"><u>In 2024, Essential Skills for Recording Private WhatsApp Talks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-program-installation-on-windows-11/"><u>Mastering Program Installation on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-settings-unveiled/"><u>Windows 11 Settings Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-usb-health-in-windows-a-troubleshooting-checklist/"><u>Restoring USB Health in Windows: A Troubleshooting Checklist</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-highpoint-design-suite-examination/"><u>In 2024, Highpoint Design Suite Examination</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-whats-going-wrong-sideways-videos-on-instagram/"><u>In 2024, What's Going Wrong  Sideways Videos on Instagram</u></a></li>
</ul></div>
