---
title: Augmenting File Explorer Menus with Auto-Update Features
date: 2024-06-25T16:19:13.966Z
updated: 2024-06-26T16:19:13.966Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Augmenting File Explorer Menus with Auto-Update Features
excerpt: This Article Describes Augmenting File Explorer Menus with Auto-Update Features
keywords: File Explorer Updates,Menu Enhancement,Auto-Refresh Feature,Dynamic Navigation Help,ExploreUpdates Tool,RealTimeMenu UI,LiveUI Filesystem
thumbnail: https://thmb.techidaily.com/b23f7aea0239ccf0208f3f76d9301c76c818b9985a4f6edf3b35f62e51fa261d.jpg
---

## Augmenting File Explorer Menus with Auto-Update Features

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
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-slow-downloads-in-steam-a-windows-guide/"><u>Troubleshoot Slow Downloads in Steam - A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-drive-discovering-excessive-disk-space-consumers/"><u>Declutter Your Drive: Discovering Excessive Disk Space Consumers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-strategies-for-unlocking-store-apps-directory/"><u>Proven Strategies for Unlocking Store Apps Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-updates-and-error-windows-0x800f0845/"><u>Fixing Updates and Error: Windows 0X800F0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-customize-windows-11-and-11-with-winbubble/"><u>8 Ways to Customize Windows 11 and 11 With WinBubble</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevate-media-projects-engaging-with-windows-11-movie-maker-for-2024/"><u>Elevate Media Projects  Engaging with Windows 11 Movie Maker for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-art-of-effortless-video-size-transformation-on-macos/"><u>[Updated] The Art of Effortless Video Size Transformation on MacOS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-concluding-your-instagram-journey-a-detailed-breakdown/"><u>2024 Approved  Concluding Your Instagram Journey  A Detailed Breakdown</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-easy-sound-transformation-ios-tools-to-convert-youtube-songs-to-mp3-files/"><u>[Updated] 2024 Approved  Easy Sound Transformation  IOS Tools to Convert YouTube Songs to MP3 Files</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-avoid-common-errors-while-spinning-videos-in-android-apps/"><u>In 2024, Avoid Common Errors While Spinning Videos in Android Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-broadcasting-brilliance-share-your-twitch-stream-on-fb/"><u>In 2024, Broadcasting Brilliance  Share Your Twitch Stream on FB</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-in-2024-burn-photos-to-dvd-how-to-burn-photos-to-dvd-with-transitions-and-music/"><u>New In 2024, Burn Photos to DVD | How to Burn Photos to DVD with Transitions and Music</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-tier-session-identifier-generator/"><u>[New] Top-Tier Session Identifier Generator</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-top15-apps-and-websites-to-use-to-add-music-to-a-video-for-2024/"><u>New Top15 Apps & Websites to Use to Add Music to a Video for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-unveiling-the-finest-no-cost-recording-software-today/"><u>[New] In 2024, Unveiling the Finest No-Cost Recording Software Today</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>