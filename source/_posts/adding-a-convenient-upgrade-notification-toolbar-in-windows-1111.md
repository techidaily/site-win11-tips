---
title: Adding a Convenient Upgrade Notification Toolbar in Windows 11/11
date: 2024-08-16T01:34:11.640Z
updated: 2024-08-17T01:34:11.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding a Convenient Upgrade Notification Toolbar in Windows 11/11
excerpt: This Article Describes Adding a Convenient Upgrade Notification Toolbar in Windows 11/11
keywords: Win11 Upgrade Notifier,Update Toolbar Addition,Microsoft Windows Alerts,New Windows Toolbar Feature,Easy Upgrades in Windows 11,Notification Toolbar in Windows,Enhance Windows 11 UI
thumbnail: https://thmb.techidaily.com/9eb4aae367e8d7c80e3c075f7bffa3926b7f3e2ef755ab623092abbe72eca2c0.jpg
---

## Adding a Convenient Upgrade Notification Toolbar in Windows 11/11

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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-capture-perfection-the-best-live-stream-recorders-ranked/"><u>[New] 2024 Approved  Capture Perfection  The Best Live Stream Recorders Ranked</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-tips-to-smoothly-add-photo-capabilities-into-your-virtual-gatherings/"><u>[New] 2024 Approved  Tips to Smoothly Add Photo Capabilities Into Your Virtual Gatherings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-grading-and-correcting-with-ease-top-11-video-editing-tips/"><u>[New] Grading and Correcting with Ease  Top 11 Video Editing Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-the-art-of-youtube-channel-blocking-a-step-by-step-approach/"><u>[New] Mastering the Art of Youtube Channel Blocking  A Step-by-Step Approach</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-maximize-impact-tweeting-with-videos/"><u>[Updated] 2024 Approved  Maximize Impact  Tweeting with Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-3-copywriting-structure-for-facebook-ads/"><u>[Updated] In 2024, 3 Copywriting Structure for Facebook Ads</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-revolutionize-your-facebook-presence-with-these-10-strategies/"><u>[Updated] In 2024, Revolutionize Your Facebook Presence with These 10 Strategies</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-spotting-social-scene-shifters-videos-shared-across-platforms-for-2024/"><u>[Updated] Spotting Social Scene-Shifters  Videos Shared Across Platforms for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-vivo-y27-4g-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Vivo Y27 4G Fingerprint Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-search-performance-with-these-key-methods/"><u>Boosting Windows 11 Search Performance with These Key Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-camp-backing-up-your-hard-drive-solo/"><u>Boot Camp: Backing up Your Hard Drive Solo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/break-free-from-issues-restoring-windows-family-security/"><u>Break Free From Issues: Restoring Windows Family Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-the-fix-for-xbox-game-pass-error-0-on-windows-11-pcs/"><u>Breaking Down the Fix for Xbox Game Pass Error 0 on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breatenticating-healthy-windows-and-dotnet-status-max-156/"><u>Breatenticating Healthy Windows & DotNet Status (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-inactive-apps-in-windows-11/"><u>Breathing Life Into Inactive Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-devices-a-practical-guide-to-android-and-pc-synchro/"><u>Bridging Devices: A Practical Guide to Android & PC Synchro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-dual-windows-mastering-data-consistency-using-aoemi/"><u>Bridging Dual Windows: Mastering Data Consistency Using AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-void-spaces-in-windows-navigator/"><u>Bridging Void Spaces in Windows Navigator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-whats-lost-recovering-windows-11s-disappearing-bluetooth/"><u>Bring Back What's Lost: Recovering Windows 11’S Disappearing Bluetooth</u></a></li>
<li><a href="https://tech-haven.techidaily.com/build-your-balanced-eating-schedule-using-chatgpt-tips-and-tricks/"><u>Build Your Balanced Eating Schedule Using ChatGPT – Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-a-flask-based-python-server-for-networked-file-transfers/"><u>Building a Flask-Based Python Server for Networked File Transfers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-browser-requirement-a-new-user-guide/"><u>Bypassing Browser Requirement: A New User Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-disabled-accounts-fixing-windows-login-fails/"><u>Bypassing Disabled Accounts: Fixing Windows Login Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-hardware-errors-windows-1110-guide/"><u>Bypassing Hardware Errors: Windows 11/10 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-http-overload-in-win-based-software-0x80860010/"><u>Bypassing HTTP Overload in Win-Based Software (0X80860010)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-incompatibility-with-latest-windows-version/"><u>Bypassing Incompatibility with Latest Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-obstacle-dealing-with-device-error-22-on-windows-11/"><u>Bypassing the Obstacle: Dealing with Device Error 22 on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-workspace-failures-fixing-office-errors-in-winos/"><u>Bypassing Workspace Failures: Fixing Office Errors in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-use-the-program-compatibility-troubleshooter-on-windows-try-these-fixes/"><u>Can't Use the Program Compatibility Troubleshooter on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-windows-slideshow-execute-with-seven-simple-steps/"><u>Captivating Windows Slideshow - Execute with Seven Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-your-windows-terminal-color-scheme/"><u>Change Your Windows Terminal Color Scheme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-new-territories-top-7-updates-from-windows-11s-filesystem/"><u>Charting New Territories: Top 7 Updates From Windows 11'S Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-effective-real-time-file-transfer-software-google-and-windows-options/"><u>Choosing Effective Real-Time File Transfer Software: Google & Windows Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-preferred-pdf-application-on-windows/"><u>Choosing Preferred PDF Application on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/christmas-magic-for-your-windows-11-setup/"><u>Christmas Magic for Your Windows 11 Setup</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/explore-the-best-ps2-emulation-software-for-android/"><u>Explore the Best PS2 Emulation Software for Android</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-apple-iphone-15-pro-max-and-ipad-securely-drfone-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on Apple iPhone 15 Pro Max and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-five-trailblazers-shaping-the-webs-audiovideo-landscape/"><u>In 2024, Five Trailblazers Shaping the Web's Audio/Video Landscape</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-nubia-red-magic-8s-proplus-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Nubia Red Magic 8S Pro+</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-screen-casting-in-vlc-reviewed/"><u>In 2024, Screen Casting in VLC Reviewed</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-asus-rog-phone-7-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Asus ROG Phone 7 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-tecno-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Tecno</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-guide-retrieving-deleted-messages-across-iphone-models-iphone-5-4s-6-etc/"><u>Step-by-Step Guide: Retrieving Deleted Messages Across iPhone Models (iPhone 5, 4S, 6, Etc.)</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-windows-graphics-with-hp-driver-update/"><u>Streamline Window's Graphics with HP Driver Update</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-errors-with-outlooks-automatic-spell-correction-feature/"><u>Troubleshooting Errors with Outlook's Automatic Spell Correction Feature</u></a></li>
</ul></div>
