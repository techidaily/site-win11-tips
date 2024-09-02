---
title: Incorporating Update Info Into Right-Click Context Menu
date: 2024-09-01T05:17:11.415Z
updated: 2024-09-02T05:17:11.415Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Incorporating Update Info Into Right-Click Context Menu
excerpt: This Article Describes Incorporating Update Info Into Right-Click Context Menu
keywords: Right-Menu Updates,Click Context Advice,Menu Update Tips,Update Right-Click,Menu Info Integration,Context Menu Changes,Right-Click Features
thumbnail: https://thmb.techidaily.com/9304676ddebde0491fac069817e2e83439806cdb3bbe061f637b22cd4655ca5f.jpg
---

## Incorporating Update Info Into Right-Click Context Menu

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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-2023-facebook-video-downloader-application-for-mobilewinmac/"><u>[Updated] In 2024, 2023 | Facebook Video Downloader Application for Mobile/Win/Mac</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-essential-guide-to-creating-stellar-films-with-win11s-movie-maker/"><u>[Updated] In 2024, Essential Guide to Creating Stellar Films with Win11's Movie Maker</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-photoshop-basics-for-beginners-10-must-know-tricks/"><u>2024 Approved  Photoshop Basics for Beginners  10 Must-Know Tricks</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/affordable-hp-37-inch-wqhdplus-ultrawide-monitor-ips-panel-for-serious-professionals-not-pricey-like-oleds/"><u>Affordable HP 37-Inch WQHD+ Ultrawide Monitor: IPS Panel for Serious Professionals, Not Pricey Like OLEDs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/are-you-struggling-with-blizzard-battlenet-understanding-the-difference-between-server-downtime-and-personal-connection-issues/"><u>Are You Struggling with Blizzard Battle.net? Understanding the Difference Between Server Downtime and Personal Connection Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-method-to-delete-wsl/"><u>Comprehensive Method to Delete WSL</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-operation-failure-x709-on-pc/"><u>Correcting Operation Failure X709 on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-out-delays-for-administrator-level-terminals/"><u>Cut Out Delays for Administrator-Level Terminals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designating-menu-triggers-for-software-patch-alerts/"><u>Designating Menu Triggers for Software Patch Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dialogue-initiation-on-modern-windows-pcs/"><u>Dialogue Initiation on Modern Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-diversity-of-windows-n-versions/"><u>Dissecting the Diversity of Windows N Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-to-fix-windowss-dotnet-problems-max-156/"><u>Efficient Steps to Fix Windows's DotNet Problems (Max 156)</u></a></li>
<li><a href="https://win-blog.techidaily.com/elevate-your-play-strategies-to-achieve-higher-fps-and-less-lag-in-fall-guys/"><u>Elevate Your Play - Strategies to Achieve Higher FPS & Less Lag in Fall Guys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expand-your-windows-reach-incorporating-enhanced-script-tools/"><u>Expand Your Window's Reach: Incorporating Enhanced Script Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-and-workarounds-for-windows-and-xbox-collision/"><u>Fixes & Workarounds for Windows and Xbox Collision</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signatures-for-word-2010-by-ldigisigner-sign-a-word-sign-a-word/"><u>Free electronic signatures for Word 2010</u></a></li>
<li><a href="https://buynow-info.techidaily.com/has-your-ipad-become-an-outdated-tech-relic/"><u>Has Your iPad Become an Outdated Tech Relic?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/heaviest-airborran-aerial-haulers-ultimate-choices-for-2024/"><u>Heaviest Airborran Aerial Haulers - Ultimate Choices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-controlled-folder-access-in-windows-10-and-11/"><u>How to Enable Controlled Folder Access in Windows 10 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-apple-iphone-xs-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your Apple iPhone XS and iPad</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-xs-when-phone-is-broken-drfone-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone XS when Phone is Broken? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-reload-of-printer-service/"><u>Immediate Reload of Printer Service</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-effective-strategies-to-capture-and-save-google-voice-dialogues/"><u>In 2024, Effective Strategies to Capture and Save Google Voice Dialogues</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-flip-the-script-on-classic-films-7-list/"><u>In 2024, Flip the Script on Classic Films, #7 List</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-vivo-x100-pro-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Vivo X100 Pro Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-eradicating-audacity-error-9999/"><u>Mastering the Art of Eradicating Audacity Error 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-approaches-for-effective-windows-file-browsing-sans-ls/"><u>Proven Approaches for Effective Windows File Browsing Sans LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixed-guide-for-frozen-epic-game-launcher/"><u>Quick Fixed Guide for Frozen Epic Game Launcher</u></a></li>
<li><a href="https://win11-tips.techidaily.com/relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-browsing-with-microsoft-edge-on-win10w11/"><u>Speeding Up Browsing with Microsoft Edge on Win10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-your-battlenet-game-downloads-on-pc/"><u>Speeding Up Your Battle.net Game Downloads on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-up-synergy-launching-sticky-notes-with-windows-logon/"><u>Start-Up Synergy: Launching Sticky Notes with Windows Logon</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-keeping-calc-always-on-windows/"><u>Strategies for Keeping Calc Always On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-reestablishing-remote-network-links-in-winvpn/"><u>Strategies for Reestablishing Remote Network Links in WinVPN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-lag-solving-windows-pc-vs-mobile-internet-speeds/"><u>Tackling Lag: Solving Windows PC vs Mobile Internet Speeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-unavailable-error-on-your-pcs-windows-apps/"><u>Tackling the 'Unavailable' Error on Your PC's Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-charge-of-your-computer-task-manager-elevated-mode-demystified-in-win11/"><u>Take Charge of Your Computer: Task Manager Elevated Mode Demystified in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-silencing-chrome-pop-ups/"><u>Tips for Silencing Chrome Pop-Ups</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/trending-tactics-select-keywords-that-ignite-social-media-traffic-for-2024/"><u>Trending Tactics  Select Keywords That Ignite Social Media Traffic for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unboxing-the-stars-latest-laptops-from-ifa-2023/"><u>Unboxing the Stars - Latest Laptops From IFA 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-importance-of-cplusplus-redistributors/"><u>Understanding the Importance of C++ Redistributors</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-innovative-ideas-using-chatgpt-to-elevate-content-strategies/"><u>Unlocking Innovative Ideas: Using ChatGPT to Elevate Content Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-quick-fixed-for-11-windows-issues/"><u>Unveiling Secrets: Quick Fixed for 11 Windows Issues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/why-pay-full-price-trade-in-at-newegg-and-receive-300i9-14900k-220ryzen-7-7800x3d-unlock-savings-with-their-new-program/"><u>Why Pay Full Price? Trade in at Newegg & Receive $300/I9-14900K, $220/Ryzen 7 7800X3D - Unlock Savings with Their New Program</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-intel-cores-epoch-discover-through-windows-8-ways/"><u>Your Intel Core's Epoch: Discover Through Windows (8 Ways)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>