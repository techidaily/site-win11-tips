---
title: Integrating Check for Updates in System Context Menu
date: 2024-08-16T01:43:46.788Z
updated: 2024-08-17T01:43:46.788Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-dynamic-website-content-incorporating-youtube-playlists/"><u>[New] 2024 Approved  Dynamic Website Content  Incorporating YouTube Playlists</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mastering-video-size-for-standout-instagram-content/"><u>[New] 2024 Approved  Mastering Video Size for Standout Instagram Content</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ompre-web-resources-for-effortless-youtube-template-access-for-2024/"><u>[New] Compre-Web Resources for Effortless YouTube Template Access for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-the-art-of-filter-and-music-integration-in-windows-10-photos/"><u>[New] Mastering the Art of Filter & Music Integration in Windows 10 Photos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-smart-buying-top-value-action-cam-models/"><u>[New] Smart Buying  Top Value Action Cam Models</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-quickvideocapture-simple-desktop-app-for-w10/"><u>[Updated] 2024 Approved  QuickVideoCapture  Simple Desktop App for W10</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-perfecting-webp-conversion-to-jpeg-format/"><u>[Updated] In 2024, Perfecting WebP Conversion to JPEG Format</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-pursuing-perfection-on-track-compiling-top-5-simulators/"><u>[Updated] Pursuing Perfection on Track  Compiling Top 5 Simulators</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-spotlight-websites-offering-youtube-branding-collaborations/"><u>[Updated] Spotlight  Websites Offering YouTube Branding Collaborations</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-xiaomi-14-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Xiaomi 14 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-virtualitys-verse-inspirational-reflections-in-arvr-space/"><u>2024 Approved  Virtuality's Verse  Inspirational Reflections in AR/VR Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-your-non-operational-windows-11-hotspot/"><u>Activating Your Non-Operational Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-security-implementing-controlled-access-in-windows/"><u>Command Security: Implementing Controlled Access in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-error-0x8000ffff-in-windows-based-printers/"><u>Conquering Error 0X8000FFFF in Windows-Based Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-the-perfect-christmas-look-in-windows-11/"><u>Craft the Perfect Christmas Look in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-prime-8-video-cutter-tools-on-windows/"><u>Discover the Prime 8 Video Cutter Tools on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-wintoys-a-brief-dive-into-a-formidable-windows-feature/"><u>Discovering WinToys: A Brief Dive Into a Formidable Windows Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-the-depth-of-complete-screenshots-via-windows-snipping-tool/"><u>Dive Into the Depth of Complete Screenshots via Windows' Snipping Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-way-to-unlink-wi-fi-on-windows-11/"><u>Efficient Way to Unlink Wi-Fi on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-savings-with-w11-pro-key-access-prime-deals/"><u>Elevate Savings with W11 Pro Key: Access Prime Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-work-with-multiple-displays-in-win11/"><u>Elevate Your Work with Multiple Displays in Win11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-wakeup-solutions-ranking-the-best-alarm-clock-apps-available-today/"><u>Essential Wakeup Solutions: Ranking the Best Alarm Clock Apps Available Today</u></a></li>
<li><a href="https://media-tips.techidaily.com/expert-tips-on-improving-video-quality-through-skillful-sound-editing/"><u>Expert Tips on Improving Video Quality Through Skillful Sound Editing</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-chrome-freeze-and-blank-screens/"><u>Fixing the Chrome Freeze and Blank Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-updates-and-error-windows-0x800f0845/"><u>Fixing Updates and Error: Windows 0X800F0845</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-infinix-hot-40-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722978074753-hassle-free-setup-for-the-latest-acer-sound-card-drivers-learn-how/"><u>Hassle-Free Setup for the Latest Acer Sound Card Drivers - Learn How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-window-management-feature-in-windows-11-end-task/"><u>How to Engage Window Management Feature in Windows 11 (End Task)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-internal-portaudio-error-in-windows-10-and-11/"><u>How to Fix Audacity’s Internal PortAudio Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-lock-windows-safescreen-state-against-user-change/"><u>How to Lock Windows SafeScreen State Against User Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-suppression-of-windows-11-notifications/"><u>Immediate Suppression of Windows 11 Notifications</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-honor-magic5-ultimate-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Honor Magic5 Ultimate Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-dive-into-filmmaking-the-role-of-lenses-in-videos/"><u>In 2024, Dive Into Filmmaking  The Role of Lenses in Videos</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-usb-wi-fi-adapter-not-connecting-or-working-on-windows-8-ways-to-fix-it/"><u>Is Your USB Wi-Fi Adapter Not Connecting or Working on Windows? 8 Ways to Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jolt-from-hibernation-freeze-on-your-pc/"><u>Jolt From Hibernation Freeze on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-frustrations-installation-fixes-for-missing-windows-upgrades/"><u>No More Frustrations! Installation Fixes for Missing Windows Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-unlock-pin-function-in-windows-11/"><u>Overcoming Greyed Out Unlock Pin Function in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-irregular-beats-soundcard-irq-solutions/"><u>Quelling Irregular Beats: Soundcard IRQ Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-discord-interface-fixing-a-dormant-overlay/"><u>Reclaim Your Discord Interface: Fixing a Dormant Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-of-lock-screen-delay-on-pcs/"><u>Regaining Control of Lock Screen Delay on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365826035-resolve-camera-woes-in-windows-heres-how/"><u>Resolve Camera Woes in Windows, Here’s How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-wobbling-keyboard-arrows-in-windows-environments/"><u>Revive Wobbling Keyboard Arrows in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/say-farewell-to-windows-subsys-embracing-alternatives-for-android/"><u>Say Farewell to Windows Subsys: Embracing Alternatives for Android</u></a></li>
<li><a href="https://win-able.techidaily.com/1722994303669-say-goodbye-to-freezes-improving-pc-performance-for-subnautica-below-zero-players/"><u>Say Goodbye to Freezes! Improving PC Performance for Subnautica: Below Zero Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sculpt-sketch-and-color-like-never-before-microsoft-paint-enhancements/"><u>Sculpt, Sketch & Color Like Never Before: Microsoft Paint Enhancements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-dolby-atmos-installation-in-windows-1111/"><u>Seamless Dolby Atmos Installation in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-administrator-privileges-denial-in-cmd-prompt/"><u>Solving Administrator Privileges Denial in Cmd Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-insufficient-access-during-uninstall/"><u>Steps to Overcome Insufficient Access During Uninstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-amend-out-of-memory-issues-in-hogwarts-adventures/"><u>Strategies to Amend Out of Memory Issues in Hogwarts Adventures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-connections-how-to-clear-dns-in-steam-settings/"><u>Streamline Connections: How to Clear DNS in Steam Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unusual-wsl-error-4294967295-on-pcs/"><u>Tackling Unusual WSL Error 4294967295 on PCs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tailor-made-video-hosting-on-vimeo-pick-your-perfect-level-for-2024/"><u>Tailor-Made Video Hosting on Vimeo  Pick Your Perfect Level for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-s-mode-essential-tips-for-windows-1011/"><u>Transitioning From S Mode: Essential Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11s-operation-elevation-issue-740/"><u>Troubleshooting Windows 11'S Operation Elevation Issue #740</u></a></li>
<li><a href="https://buynow-info.techidaily.com/uncovering-the-potential-of-netgears-orbi-rbs50y-for-outdoor-wi-fi-networks/"><u>Uncovering the Potential of Netgear's Orbi RBS50Y for Outdoor Wi-Fi Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-11-screen-recording-techniques-combining-audio-and-visual-features-in-snipping-tool-max-156/"><u>Unveiling Windows 11 Screen Recording Techniques: Combining Audio & Visual Features in Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-simplification-recapturing-default-rights/"><u>Windows 11 Simplification: Recapturing Default Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-promise-of-next-generation-in-the-upcoming-moment/"><u>Windows 11: The Promise of Next Generation in the Upcoming Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
</ul></div>
