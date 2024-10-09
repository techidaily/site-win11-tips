---
title: Embedding System Status Updates in Explorer Tooltips
date: 2024-10-07T03:41:13.995Z
updated: 2024-10-08T21:52:20.987Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Embedding System Status Updates in Explorer Tooltips
excerpt: This Article Describes Embedding System Status Updates in Explorer Tooltips
keywords: Status Update Indicator,Exploratory Tooltip Embed,Status Info Display,Real-Time Explorer Tip,Dynamic Tooltip Content,System Status Feature,Interactive Explorer Cues
thumbnail: https://thmb.techidaily.com/127593239da9ddf3aa0e35e9fdfe9cdfb96622adf462fe90ad515f1ed2896ad3.jpg
---

## Embedding System Status Updates in Explorer Tooltips

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
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

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-files.techidaily.com/new-best-quality-frames-at-low-motion-velocity-for-2024/"><u>[New] Best Quality Frames at Low Motion Velocity for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-fb-live-demystified-how-to-watch-2023-update-for-2024/"><u>[New] FB Live Demystified How to Watch, 2023 Update for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-getting-started-with-snapchats-new-spotlight/"><u>[New] Getting Started with Snapchat's New Spotlight</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-leading-platforms-for-digital-graffiti-fonts/"><u>[New] In 2024, Leading Platforms for Digital Graffiti Fonts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-flashfreeze-video-cut-out-instruction/"><u>2024 Approved FlashFreeze Video Cut-Out Instruction</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-streamlined-techniques-for-efficient-apple-screenshots/"><u>2024 Approved Streamlined Techniques for Efficient Apple Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-to-follow-pathway-accessing-wordpad-on-pcs/"><u>Easy-to-Follow Pathway: Accessing WordPad on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-speed-status-in-windows-desktop-area/"><u>Effortless Speed Status in Windows Desktop Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-your-user-experience-customizing-windows-11-defaults/"><u>Enhancing Your User Experience: Customizing Windows 11 Defaults</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-dark-mode-in-notepad-on-windows-10-and-11/"><u>How to Enable Dark Mode in Notepad on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-default-file-savings-in-windows-pcs/"><u>How to Solve Default File Savings in Windows PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-infinix-smart-8-plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-back-to-joy-playing-classics-on-dosbox-x/"><u>Jump Back to Joy: Playing Classics on DOSBox-X</u></a></li>
<li><a href="https://win-able.techidaily.com/monster-hunter-stories-2-wings-of-ruin-troubleshooting-steps-for-game-installation-issues/"><u>Monster Hunter Stories 2: Wings of Ruin - Troubleshooting Steps for Game Installation Issues</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-pc-boost-with-free-gb-memory-driver-for-windows/"><u>Quick PC Boost with Free GB Memory Driver for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-hidden-remove-button-for-windows-11-security/"><u>Reactivating Hidden 'Remove' Button for Windows 11 Security</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-14-pro-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone 14 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-not-certified-by-microsoft-on-pc/"><u>Troubleshooting 'App Not Certified by Microsoft' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microsoft-store-error-0x80073d26/"><u>Troubleshooting Microsoft Store Error 0X80073D26</u></a></li>
</ul></div>

