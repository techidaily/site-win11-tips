---
title: Amplifying Explorer Tooltips with Auto-Update Notifications
date: 2024-07-12T16:55:00.847Z
updated: 2024-07-13T16:55:00.847Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Amplifying Explorer Tooltips with Auto-Update Notifications
excerpt: This Article Describes Amplifying Explorer Tooltips with Auto-Update Notifications
keywords: Explore Tooltip Updates,Auto-Update Alerts,Enhance Exploration Tips,Real-Time Tip Notifications,Tooltips Auto Sync,Update Tooltip Features,Notifications for Tips
thumbnail: https://thmb.techidaily.com/1226fbaa741004693d1f4b8bc9bf88f0e71c8201ee5e911ba173ac8995ac7535.jpg
---

## Amplifying Explorer Tooltips with Auto-Update Notifications

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-you-can-try-final-cut-pro-for-90-days-absolutely-free-final-cut-pros-latest-version-is-available-for-a-free-trial-learn-everything-about-it-righ/"><u>New In 2024, You Can Try Final Cut Pro for 90 Days Absolutely Free. Final Cut Pros Latest Version Is Available for a Free Trial. Learn Everything About It Right Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-setting-up-windows-outlook-preview/"><u>Quick Guide: Setting Up Windows' Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-facebook-cinematic-capture-tool-for-2024/"><u>[Updated] Facebook Cinematic Capture Tool for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-from-flat-to-fabulous-adding-3d-effects-to-your-windows-videos/"><u>Updated In 2024, From Flat to Fabulous Adding 3D Effects to Your Windows Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-tackling-youtube-challenges-head-on-with-insights-from-hub-of-creators/"><u>2024 Approved  Tackling YouTube Challenges Head-On with Insights From Hub of Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-systemsettings-issues-on-win11/"><u>Strategies to Overcome SystemSettings Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-razer-devices-detection-via-synapse-on-windows/"><u>Steps to Restore Razer Devices Detection via Synapse on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-prevent-apex-legends-crashes-w11/"><u>Strategies to Prevent Apex Legends Crashes W11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-exploring-screen-recording-tools-beyond-apowersoft-for-2024/"><u>[New] Exploring Screen Recording Tools Beyond Apowersoft for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-picpopjokes-satirical-image-maker/"><u>2024 Approved  PicPopJokes  Satirical Image Maker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-file-lockdowns-access-restoration-on-pcs/"><u>Reversing File Lockdowns: Access Restoration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-app-install-issues-on-microsoft-store/"><u>Fixing App Install Issues on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguarding-internal-builds-in-windows-11/"><u>Safeguarding Internal Builds in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-exploring-easy-to-use-game-recording-and-edit-software/"><u>In 2024, Exploring Easy-to-Use Game Recording & Edit Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-tecno-spark-go-2023-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Tecno Spark Go (2023) Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-top-whatsapp-status-generator-tools-and-apps/"><u>New Top WhatsApp Status Generator Tools and Apps</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/free-to-fiscal-determining-view-counts-for-youtube-earnings-for-2024/"><u>From Free to Fiscal  Determining View Counts for YouTube Earnings for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-ghostly-movies-innovation-in-recorders/"><u>[Updated] Ghostly Movies  Innovation in Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsoft-pc-manager-bar-tools-on-w11/"><u>Navigating Microsoft PC Manager Bar Tools on W11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-stay-ahead-the-creme-de-la-liste-of-tiktok-font-generators/"><u>[Updated] 2024 Approved  Stay Ahead  The Crème De La Liste of TikTok Font Generators</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/upload-mastery-understanding-and-using-correct-video-sizes-on-youtube/"><u>Upload Mastery  Understanding and Using Correct Video Sizes on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://extra-hints.techidaily.com/summit-of-virtual-reality-resolution/"><u>Summit of Virtual Reality Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-speech-output-in-windows-environment/"><u>Mastering Speech Output in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unclog-the-windows-vds-startup-process/"><u>How to Unclog the Windows VDS Startup Process</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-ultimate-vlc-guide-slow-motion-video-playback-on-desktop-and-mobile-devices/"><u>New 2024 Approved The Ultimate VLC Guide Slow Motion Video Playback on Desktop and Mobile Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-zero-fee-technique-for-pixel-perfection/"><u>[New] Best Zero-Fee Technique for Pixel Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-o365-sync-failures-in-win11/"><u>Overcoming the Challenges of O365 Sync Failures in Win11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-exploring-shades-insights-from-the-best-11-color-guides/"><u>2024 Approved  Exploring Shades  Insights From the Best 11 Color Guides</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-backpack-essentials-for-filming-tours/"><u>[Updated] 2024 Approved  Backpack Essentials for Filming Tours</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-window-steam-connectivity/"><u>Restoring Lost Window-Steam Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-freeing-up-your-c-drive-space/"><u>Mastering the Art of Freeing Up Your C: Drive Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-to-turn-off-lurking-apps-in-window-11/"><u>Secrets to Turn Off Lurking Apps in Window 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-lost-wireless-ties-with-these-10-windows-10-tweaks/"><u>Reclaiming Lost Wireless Ties with These 10 Windows 10 Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-security-by-learning-the-quickest-ways-to-access-credentials-in-win11/"><u>Skyrocket Security by Learning the Quickest Ways to Access Credentials in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-interface-adding-portable-software-to-w11/"><u>Optimize Your Interface: Adding Portable Software to W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-standard-power-profile/"><u>Restoring Windows' Standard Power Profile</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-gamers-top-picks-1-ranked-4k-laptops/"><u>In 2024, Gamers' Top Picks  #1 Ranked 4K Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-needed-parts-error-on-windows-1011-systems/"><u>Solving Needed Parts Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/neatness-noted-navigating-a-tidier-windowed-explore/"><u>Neatness Noted: Navigating a Tidier Windowed Explore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solutions-for-we-encountered-an-error-during-oculus-install/"><u>Step-By Step Solutions for We Encountered an Error During Oculus Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/method-to-start-windows-11s-admin-powershell-instance/"><u>Method to Start Windows 11'S Admin PowerShell Instance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-edthemes-in-windows-11/"><u>Implementing EdThemes in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/elevate-your-content-game-top-20-best-practices-for-captivating-tiktok-captions-for-2024/"><u>Elevate Your Content Game  Top 20 Best Practices for Captivating TikTok Captions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-modifying-windows-passcode/"><u>Quick Tips for Modifying Windows Passcode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-internet-unreachability-issue/"><u>Overcoming Internet Unreachability Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-inactive-icons-on-the-desktop-bar/"><u>Fixing Inactive Icons on the Desktop Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-guide-lost-d3dx939dll-in-windows-11-os/"><u>Fix Guide: Lost D3DX9_39.dll in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-failure-to-install-win11s-v22h2-update/"><u>Navigating Through Failure to Install Win11's V22H2 Update</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-best-music-visualizers/"><u>In 2024, Best Music Visualizers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-counteract-internal-error-with-remote-desktop/"><u>Strategies to Counteract Internal Error with Remote Desktop</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-routines-for-volume-balancing-in-fl-studio/"><u>2024 Approved  Expert Routines for Volume Balancing in FL Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-and-reinforcing-win-1011-menu-functionality/"><u>Reactivating and Reinforcing Win 10/11 Menu Functionality</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-realme-gt-5-pro-drfone-by-drfone-android/"><u>How to Screen Mirroring Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-windows-storage-expansion-methods/"><u>Safe Windows Storage Expansion Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-resource-usage-in-windows-modules-installer/"><u>Lowering Resource Usage in Windows Modules Installer</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-professional-voice-capture-on-mac-compiling-the-best-5-apps/"><u>[Updated] In 2024, Professional Voice Capture on Mac  Compiling The Best 5 Apps</u></a></li>
</ul></div>
