---
title: Implementing a User-Friendly Update Alert Feature in Windows 11+11
date: 2024-09-30T19:08:55.344Z
updated: 2024-10-03T17:11:11.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing a User-Friendly Update Alert Feature in Windows 11+11
excerpt: This Article Describes Implementing a User-Friendly Update Alert Feature in Windows 11+11
keywords: Windows 11 Update Notifier,Enhanced OS Alert System,Friendly Upgrade Warnings,User-Centric Updates Guide,Seamless OS Update Prompts,Easy Update Notification Windows,Intuitive OS Feature Tips
thumbnail: https://thmb.techidaily.com/2bb5e1bc170b8c3f4a6ce1aff27e49a67b4dbeb274ccf0d0ed18fa3d929b62b2.jpg
---

## Implementing a User-Friendly Update Alert Feature in Windows 11+11

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
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/rom-script-to-splendor-animating-effects-unbound-for-2024/"><u>[New] From Script to Splendor Animating Effects Unbound for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-practices-in-upgrading-to-a-high-end-4k-camera-lens/"><u>[Updated] Best Practices in Upgrading to a High-End 4K Camera Lens</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-drafting-a-compelling-closing-statement-for-tiktok-for-2024/"><u>[Updated] Drafting a Compelling Closing Statement for TikTok for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/cutting-edge-comfort-customizing-steam-deck-with-windows/"><u>Cutting-Edge Comfort: Customizing Steam Deck with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-convert-and-optimize-esd-files-into-windows-iso-format/"><u>Efficiently Convert and Optimize ESD Files Into Windows ISO Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embracing-innovation-with-a-newer-windows-11-build/"><u>Embracing Innovation with a Newer Windows 11 Build</u></a></li>
<li><a href="https://techtrends.techidaily.com/final-farewells-on-social-media-the-how-to-manual-for-erasing-your-tiktok-existence/"><u>Final Farewells on Social Media: The How-To Manual for Erasing Your TikTok Existence</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721202678606-get-bitraser-drive-eraser-now-securely-wipe-usb-data/"><u>Get BitRaser Drive Eraser Now – Securely Wipe USB Data!</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-vivo-y100-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Vivo Y100 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-11-best-pokemon-go-spoofers-for-gps-spoofing-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Pokemon Go Spoofers for GPS Spoofing on Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-hunt-for-premium-costless-lut-files/"><u>In 2024, The Ultimate Hunt for Premium, Costless LUT Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-size-computation-powershell-on-windows/"><u>Mastering File Size Computation: PowerShell on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win-11-games-top-strategies-for-peak-performance/"><u>Mastering Win 11 Games: Top Strategies for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-pen-tab-malfunctions-in-windows/"><u>Resolve Pen-Tab Malfunctions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0x8007045d-blue-screen-error-in-windows-11/"><u>Resolving the 0X8007045D Blue Screen Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-mandatory-requirements-issue-on-modern-windows-11/"><u>Solving 'Mandatory Requirements' Issue on Modern Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-enhance-phone-sound-in-windows-pcs/"><u>Strategies to Enhance Phone Sound in Windows PCs</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/1723199722422-troubleshooting-the-unexpected-store-exception-error-in-windows-11-solved/"><u>Troubleshooting the 'Unexpected Store Exception' Error in Windows 11 – Solved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11s-virtual-living-room/"><u>Unveiling Windows 11'S Virtual Living Room</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    