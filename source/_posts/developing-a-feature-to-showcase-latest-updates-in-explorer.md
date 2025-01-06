---
title: Developing a Feature to Showcase Latest Updates in Explorer
date: 2025-01-03T04:58:57.391Z
updated: 2025-01-06T00:30:58.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Developing a Feature to Showcase Latest Updates in Explorer
excerpt: This Article Describes Developing a Feature to Showcase Latest Updates in Explorer
keywords: Explore Latest Updates,New Features Highlight,Update Notifications,Expand Explorer Features,Show Latest Changes,Innovative Explorer Updates,Featured Explorer News
thumbnail: https://thmb.techidaily.com/88d3ccdcb9182fe6ab85d78619b5ff79c9f842144c7f0589af82188a3ec75add.jpg
---

## Developing a Feature to Showcase Latest Updates in Explorer

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-unveiling-the-foundations-of-virtual-storytelling/"><u>[New] 2024 Approved Unveiling the Foundations of Virtual Storytelling</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-navigate-the-maze-of-macos-for-streamlined-video-resizing-to-instagram/"><u>[Updated] 2024 Approved Navigate the Maze of MacOS for Streamlined Video Resizing to Instagram</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-swipe-right-on-virality-blend-tiktok-trends-into-insta-reels-for-2024/"><u>[Updated] Swipe Right on Virality Blend TikTok Trends Into Insta Reels for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-highlighted-visions-is-intensified-lighting-the-future-of-hd-in-hdr/"><u>2024 Approved Highlighted Visions Is Intensified Lighting the Future of HD in HDR?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/comment-transformer-un-fichier-dvd-en-format-divx-optimal-pour-lannee-2023/"><u>Comment Transformer Un Fichier DVD en Format DivX Optimal Pour L'année 2023 ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-prime-and-window-11-for-uninterrupted-audio-subtitles/"><u>Harmonize Prime and Window 11 for Uninterrupted Audio-Subtitles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-windows-11-home-menu/"><u>How To Unlock Your Windows 11 Home Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-issues-with-deactivated-windows-11-license/"><u>Overcoming Issues with Deactivated Windows 11 License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-taskbar-interaction-proposing-key-changes-to-microsofts-design/"><u>Redefining Taskbar Interaction: Proposing Key Changes to Microsoft's Design</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/story-2-the-cohort-confusion/"><u>Story 2: The Cohort Confusion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-understanding-windows-reserved-memory/"><u>The Essentials of Understanding Windows' Reserved Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-undoing-personalization-changes-to-search-on-windows-11/"><u>Tips for Undoing Personalization Changes to Search on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-internet-interfaces-into-windowed-apps/"><u>Transforming Internet Interfaces Into Windowed Apps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/understanding-and-repairing-the-apple-watchs-touch-sensor-issues/"><u>Understanding and Repairing the Apple Watch's Touch Sensor Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-widespread-gaming-and-utilities-in-windows-2023-ms-store/"><u>Unleash Widespread Gaming and Utilities in Windows 2023 MS Store</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unleashing-the-potential-of-the-portable-beast-in-depth-look-at-apples-ipad-mini-5/"><u>Unleashing the Potential of the Portable Beast - In Depth Look at Apple's iPad Mini 5</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/what-is-the-difference-between-an-ipad-and-a-tablet/"><u>What Is the Difference Between an iPad and a Tablet?</u></a></li>
</ul></div>

