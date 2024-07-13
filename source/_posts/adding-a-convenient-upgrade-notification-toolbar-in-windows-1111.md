---
title: Adding a Convenient Upgrade Notification Toolbar in Windows 11/11
date: 2024-07-12T17:32:32.649Z
updated: 2024-07-13T17:32:32.649Z
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
<li><a href="https://win11-tips.techidaily.com/5-warning-indicators-that-call-for-a-full-reboot/"><u>5 Warning Indicators That Call For a Full Reboot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-note-taking-with-obsidians-artistic-touch/"><u>Elevate Note-Taking with Obsidian's Artistic Touch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-digital-desktop-with-engaging-time-themed-screensavers-using-these-5-tools/"><u>Enhance Your Digital Desktop with Engaging Time-Themed Screensavers Using These 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719216451577-achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-customized-keyboard-tricks-for-win-os/"><u>Boost Efficiency: Customized Keyboard Tricks for WIN OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-simple-approach-to-getting-clownfish-voice-changer-on-windows/"><u>[Updated] In 2024, Simple Approach to Getting Clownfish Voice Changer on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/windows-11-auditory-setup-a-how-to/"><u>Windows 11 Auditory Setup  A How-To</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-batch-installing-apps-using-winstall-in-windows-11/"><u>A Step-by-Step Approach to Batch Installing Apps Using Winstall in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-install-windows-11-arm-with-a-focus-on-iso-guide/"><u>Download & Install Windows 11 ARM with a Focus on ISO Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-failure-windows-update-issue-code-0x80242016/"><u>Avoid Failure: Windows Update Issue Code 0X80242016</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-tecno-pova-5-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Tecno Pova 5 Device</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/rank-the-best-tools-top-8-apps-to-increase-likes-on-fb-for-2024/"><u>Rank the Best Tools  Top 8 Apps to Increase Likes on FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-overcoming-windows-notepad-hangups/"><u>Tips for Overcoming Windows Notepad Hangups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-policy-editor-in-windows-11/"><u>Unlock the Full Potential of Policy Editor in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-monitoring-ram-gpu-and-cpu-status-guide/"><u>Efficient System Monitoring: RAM, GPU, and CPU Status Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/aperture-allstars-the-best-camera-lenses-to-capture-the-moment-ranked-1-10-for-2024/"><u>Aperture Allstars  The Best Camera Lenses to Capture the Moment, Ranked #1-10 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-synchronized-note-taking-in-windows-11/"><u>The Art of Synchronized Note-Taking in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-cant-you-see-a-drive-letter-on-your-windows-machine/"><u>Why Can't You See a Drive Letter on Your Windows Machine?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/iphone-photography-secrets-unveiled-for-2024/"><u>IPhone Photography Secrets Unveiled for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-finest-windows-11-drawers-here/"><u>Explore the Finest Windows 11 Drawers Here</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-silence-is-golden-removing-background-noise-in-final-cut-pro-x-made-easy-for-2024/"><u>Updated Silence Is Golden Removing Background Noise in Final Cut Pro X Made Easy for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-honor-x50i-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Honor X50i Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-system-details-locate-windows-ip-and-mac-via-powershell/"><u>Unveiling System Details: Locate Windows' IP and MAC via Powershell</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/which-is-the-better-gopro-for-pro-video-max-or-hero-11/"><u>Which Is The Better GoPro for Pro Video? Max or Hero 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-communication-translate-foreign-words-with-hotkeys/"><u>Enhance Communication: Translate Foreign Words with Hotkeys</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-honor-play-40c-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Honor Play 40C Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flight-paths-revealed-full-review-of-dji-phantom-4-for-2024/"><u>Flight Paths Revealed  Full Review of DJI Phantom 4 for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-essential-7-android-apps-to-eliminate-intrusive-ads/"><u>In 2024, Essential 7 Android Apps to Eliminate Intrusive Ads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/add-color-to-your-digital-dialogue-with-these-free-emoji-sites-for-2024/"><u>Add Color to Your Digital Dialogue with These Free Emoji Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-the-path-to-successful-screen-startup-post-update/"><u>Clearing the Path to Successful Screen Startup Post-Update</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-create-epic-music-videos-with-these-10-top-rated-tools/"><u>Updated 2024 Approved Create Epic Music Videos with These 10 Top-Rated Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-instructional-paper-on-windows-11s-speed-boost-feature/"><u>The Ultimate Instructional Paper on Windows 11'S Speed Boost Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-office-365-issue-code-30015-26/"><u>Correcting Office 365 Issue: Code 30015-26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-voice-activated-accessibility-features/"><u>Unlocking the Power of Voice-Activated Accessibility Features</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-comprehensive-overview-of-cost-free-livestream-apps-and-solutions-for-everyone/"><u>2024 Approved  Comprehensive Overview of Cost-Free Livestream Apps & Solutions for Everyone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-smartphone-potential-as-windows-microphone/"><u>Unlocking Smartphone Potential as Windows Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-correction-of-windows-error-0xc00000f/"><u>Avoidance and Correction of Windows Error: 0Xc00000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-language-skills-quick-translate-via-windows-key-combinations/"><u>Elevate Language Skills: Quick Translate via Windows Key Combinations</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-infinix-hot-30i-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-strategies-for-disconnected-steam-content-servers-on-pc/"><u>Fix Strategies for Disconnected Steam Content Servers on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-mobility-control-deactivation-win-11/"><u>Dive Into Mobility Control Deactivation (Win 11)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-explore-these-ten-booming-youtube-sources-to-uplift-yourself/"><u>[Updated] Explore These Ten Booming YouTube Sources to Uplift Yourself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decrease-overhead-memory-use-by-antivirus-programs/"><u>Decrease Overhead Memory Use by Antivirus Programs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-control-over-windows-with-alomware-tools/"><u>Empower Control Over Windows With AlomWare Tools</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-prose-with-these-5-pc-apps/"><u>Boost Your Prose with These 5 PC Apps</u></a></li>
</ul></div>
