---
title: Creating Context Menus to Signal Software Patches
date: 2024-12-18T05:11:02.873Z
updated: 2024-12-21T17:46:25.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Creating Context Menus to Signal Software Patches
excerpt: This Article Describes Creating Context Menus to Signal Software Patches
keywords: Patch Notification Tool,Softwar Updates Menu,Code Refresh Alerts,Update Signaling Utility,Contextual Patch Cues,Software Update Messenger,System Patch Indicator
thumbnail: https://thmb.techidaily.com/858d049547f59eac162cc6b5d9eb7989714fa411349a02f09dbf44dd53eeb23e.jpg
---

## Creating Context Menus to Signal Software Patches

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-best-live-stream-screen-recorders-for-youtube-for-2024/"><u>[New] Best Live Stream Screen Recorders for YouTube for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-comprehensive-breakdown-vsco-photography-tools/"><u>[New] Comprehensive Breakdown VSCO Photography Tools</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/oing-against-gravity-reversing-your-vids-for-2024/"><u>[New] Going Against Gravity Reversing Your Vids for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-top-free-video-calls-on-pcmac-os-for-easy-online-meetings/"><u>[New] Top Free Video Calls on PC/Mac OS for Easy Online Meetings</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-realme-c51-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Realme C51 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-notetaking-techniques-for-windows-users/"><u>Effective Notetaking Techniques for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hide-and-seek-the-secret-of-the-shutdown-icon/"><u>Hide and Seek: The Secret of the Shutdown Icon</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/high-staking-habitats-critical-commentary/"><u>HIGH-STAKING HABITATS Critical Commentary</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restart-print-spooler-service-on-windows/"><u>How to Restart Print Spooler Service on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/iphones-path-to-film-retrospection-for-2024/"><u>IPhone's Path to Film Retrospection for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-stop-bsod-errors-with-tcpipsys-fixes-on-windows-10-7-and-8/"><u>Resolved: Stop BSoD Errors with TCP/IP.sys Fixes on Windows 10, 7 & 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-disabled-windows-protection-barrier/"><u>Strategies to Overcome Disabled Windows Protection Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-3-routes-to-unveil-windows-group-policies/"><u>The 3 Routes to Unveil Windows Group Policies</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722901063721-unleash-musical-bliss-8-amazing-free-melodies-apps-for-ios-devices/"><u>Unleash Musical Bliss: 8 Amazing Free Melodies Apps for iOS Devices.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-history-of-your-windows-pc/"><u>Unraveling the History of Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-10-guide-essential-tools-for-novices/"><u>Windows 10 Guide: Essential Tools for Novices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-chatter-removal-its-consequences-explored/"><u>Windows 11 Taskbar Chatter Removal: Its Consequences Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woes-uncovering-7-critical-risks-of-inexpensive-auth-keys/"><u>Windows Woes: Uncovering 7 Critical Risks of Inexpensive Auth Keys</u></a></li>
</ul></div>

