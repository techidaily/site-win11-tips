---
title: Designing the UI for Windows 11'S Self-Update Checker
date: 2024-06-25T16:29:14.055Z
updated: 2024-06-26T16:29:14.055Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Designing the UI for Windows 11'S Self-Update Checker
excerpt: This Article Describes Designing the UI for Windows 11'S Self-Update Checker
keywords: Win11UIUpdCheck,UISelfUpdateWin,Windows11UiUpdate,UIDesignWinUpdate,UIselfUpdateWin,UpdateUIWindows11,UIWin11SelfCheck
thumbnail: https://thmb.techidaily.com/517296fb76b2495d3ca7ac9af3e02d36cfd22dc3a1d76f74a4f77913c7df7881.jpg
---

## Designing the UI for Windows 11'S Self-Update Checker

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/master-your-recordings-best-no-fee-windows-editors/"><u>Master Your Recordings: Best No-Fee Windows Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-setup-service-via-command-line-utilities/"><u>Adjusting Setup Service via Command-Line Utilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-android-into-windows-11-select-the-best-6-companion-apps/"><u>Integrating Android Into Windows 11: Select the Best 6 Companion Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-peaceful-sleep-windows-1011-automatic-shutdown/"><u>Securing Peaceful Sleep: Windows 10/11 Automatic Shutdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-windows-steam-broadcaster-errors/"><u>Combatting Windows Steam Broadcaster Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-failure-windows-update-issue-code-0x80242016/"><u>Avoid Failure: Windows Update Issue Code 0X80242016</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-for-perfect-directx-setup-and-updates/"><u>Easy Steps for Perfect DirectX Setup & Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-upgrading-isnt-feeling-right-for-many-to-windows-11/"><u>Why Upgrading Isn't Feeling Right for Many to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-installed-optional-windows-functions-a-7-step-guide/"><u>Fixing Non-Installed Optional Windows Functions: A 7-Step Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-conquer-windows-screenshots-5-recommended-recorders/"><u>[Updated] 2024 Approved  Conquer Windows Screenshots  #5 Recommended Recorders</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-from-iphone-xs-max-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock From iPhone XS Max?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/revamped-podcast-chats-attracting-true-fans-for-2024/"><u>Revamped Podcast Chats  Attracting True Fans for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-hidden-powerhouses-in-your-instagram-toolkit/"><u>[Updated] 2024 Approved  The Hidden Powerhouses in Your Instagram Toolkit</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-unlock-the-secrets-of-instagrams-latest-filters/"><u>[New] In 2024, Unlock the Secrets of Instagram's Latest Filters</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-iphone-14-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of iPhone 14 Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/easy-guide-to-using-your-phone-as-an-alternative-camera-for-2024/"><u>Easy Guide to Using Your Phone as an Alternative Camera for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-itel-a70-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Itel A70 to iPhone Easily | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>