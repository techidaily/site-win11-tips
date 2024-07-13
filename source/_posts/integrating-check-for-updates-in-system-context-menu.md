---
title: Integrating Check for Updates in System Context Menu
date: 2024-07-12T17:23:37.358Z
updated: 2024-07-13T17:23:37.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Check for Updates in System Context Menu
excerpt: This Article Describes Integrating Check for Updates in System Context Menu
keywords: System Update Alerts,UI Change Notifier,Menu Refresh Options,User Feedback on Updates,Checkup Integration Guide,Contextual Update Dialogues,Proactive Update Messenger
thumbnail: https://thmb.techidaily.com/052918d3e56b96021eca7b3225588078d8b2ee409e0b799bdcb8f9f006f59b01.jpg
---

## Integrating Check for Updates in System Context Menu

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
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-capture-your-sounds-on-pc-with-x-recorder/"><u>[Updated] In 2024, Capture Your Sounds on PC with X-Recorder</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-smooth-file-transfers-tips-and-tricks-for-windows-users/"><u>Securing Smooth File Transfers: Tips & Tricks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-audio-issues-with-windows-tone-test/"><u>Resolving Audio Issues with Windows Tone Test</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-changes-essential-windows-programs-for-editing-file-dates/"><u>Timely Changes: Essential Windows Programs for Editing File Dates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-application-could-not-load-qt-plugin-error/"><u>Rectifying the 'Application Could Not Load Qt Plugin' Error</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-ultimate-list-top-10-free-online-video-editors-with-no-watermark-for-2024/"><u>New The Ultimate List Top 10 Free Online Video Editors with No Watermark for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/printer-not-working-on-windows-11-heres-how-to-fix-it/"><u>Printer Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-store-clearing-error-code-x80072f30/"><u>Troubleshoot Windows Store: Clearing Error Code X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-screen-line-parity/"><u>Correcting Screen Line Parity</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-the-gold-standard-in-selecting-accurate-3ds-simulators/"><u>2024 Approved  The Gold Standard in Selecting Accurate 3DS Simulators</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-stabilizers-choosing-the-best-for-high-res-cameras/"><u>Top Stabilizers  Choosing the Best for High-Res Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-failure-lockout-period-on-sign-in-errors/"><u>Personalizing Failure Lockout Period on Sign In Errors</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unboxing-ubiquity-the-profitable-vloggers-playbook/"><u>Unboxing Ubiquity  The Profitable Vlogger's Playbook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-no-lags-smoother-youtube-videos-on-windows/"><u>Navigate No Lags: Smoother YouTube Videos on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-premiere-pro-rapid-transitions/"><u>[New] Premiere Pro Rapid Transitions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-dism-failure-0x800f082f/"><u>Mastering the Art of Rectifying DISM Failure: 0X800F082F</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-top-voice-harmonizing-tools-to-enhance-live-performances-online/"><u>Updated Top Voice Harmonizing Tools to Enhance Live Performances Online</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-iphone-6-plus-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your iPhone 6 Plus Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-down-excessive-cpu-usage-in-windows-hosts/"><u>Trimming Down Excessive CPU Usage in Windows Hosts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-highly-ranked-drone-selections-for-gopro-videos-and-shoots/"><u>[Updated] Highly Ranked Drone Selections for GoPro Videos & Shoots</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-10-online-video-rotation-solutions-to-elevate-your-content/"><u>New In 2024, 10 Online Video Rotation Solutions to Elevate Your Content</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-honor-90-gt-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Honor 90 GT Without Password | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-cannot-continue-error-in-amd-installation/"><u>Overcoming the 'Cannot Continue' Error in AMD Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-smart-with-windows-hidden-folders/"><u>Starting Smart with Windows' Hidden Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-windows-no-internet-issue/"><u>Steps for Overcoming Windows No Internet Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-unwanted-launch-of-snipping-tool-via-print-screen-in-win-11/"><u>Prevent Unwanted Launch of Snipping Tool via Print Screen in Win 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-video-perfection-crafting-squares-for-facebook-popularity/"><u>[New] Video Perfection  Crafting Squares for Facebook Popularity</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-samsung-galaxy-a14-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Samsung Galaxy A14 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-camera-kings-battle-ultimate-sj6-vs-xiaomis-yi-kickstart-dream/"><u>[New] Camera Kings Battle  Ultimate SJ6 Vs. Xiaomi’s Yi Kickstart Dream</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-diving-into-instagrams-restriction-for-video-content-for-2024/"><u>[Updated] Diving Into Instagram's Restriction for Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-techniques-how-to-utilize-the-background-blur-on-w11-photos/"><u>Streamlined Techniques: How to Utilize the Background Blur on W11 Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-productivity-essential-windows-based-tools-listed/"><u>Revolutionize Productivity: Essential Windows-Based Tools Listed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80131500-on-microsoft-shop/"><u>Unlocking Error #0X80131500 on Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-drag-recover-lost-functionality-fast/"><u>Win11 Drag: Recover Lost Functionality Fast</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-10-pricing-with-smart-key-acquisition/"><u>Mastering Windows 10 Pricing with Smart Key Acquisition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-your-worldwide-address-through-cmd-windows/"><u>Unmasking Your Worldwide Address Through CMD, Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/overview-fb-video-dimension-categories-for-2024/"><u>Overview  FB Video Dimension Categories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-tyranny-of-inconsistent-colors-in-windows/"><u>Taming the Tyranny of Inconsistent Colors in Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-acquiring-safe-gratis-vlc-media-player-on-macos-systems/"><u>2024 Approved  Acquiring Safe, Gratis VLC Media Player on macOS Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disconnections-windows-and-printers/"><u>Overcoming Disconnections: Windows & Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-resurrect-non-responsive-windows-discord-elements/"><u>Tactics to Resurrect Non-Responsive Windows Discord Elements</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-snapchat-spotlight-how-and-why-it-matters/"><u>2024 Approved  Snapchat Spotlight  How & Why It Matters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-search-enhancements-in-windows-11-file-explorer/"><u>Visual Search Enhancements in Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-your-guide-to-repairing-windows-software-glitches/"><u>Immediate Actions: Your Guide to Repairing Windows Software Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-msvcr120-deficiency-windows-wise/"><u>Tips for Troubleshooting Msvcr120 Deficiency Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-network-issues-demystifying-windows-error-0x800704b3/"><u>Tackling Network Issues - Demystifying Windows' Error: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-apps-facilitating-the-switch-from-macos-to-windows/"><u>The Ultimate List of Apps Facilitating the Switch From MACOS to WINDOWS</u></a></li>
</ul></div>
