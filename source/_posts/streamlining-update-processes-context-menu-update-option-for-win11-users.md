---
title: "Streamlining Update Processes: Context Menu Update Option for Win11 Users"
date: 2024-07-12T17:09:19.306Z
updated: 2024-07-13T17:09:19.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Update Processes: Context Menu Update Option for Win11 Users"
excerpt: "This Article Describes Streamlining Update Processes: Context Menu Update Option for Win11 Users"
keywords: Win11 Menu Streamline,Win11 Update Opt,Win11 Menu Update,Menu Streamline Win11,Context Menu Win11,Win11 User Update,Quick Win11 Menu Fix
thumbnail: https://thmb.techidaily.com/9658b467055670b82a39baa210ea870282b123ee6ed50ee4c51fdd504d8349ee.jpg
---

## Streamlining Update Processes: Context Menu Update Option for Win11 Users

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
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-reviving-the-dormant-wsreset-on-windows/"><u>A Step-by-Step Plan: Reviving the Dormant WSReset on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-prevent-and-repair-vmstart-errors-in-wm11os/"><u>8 Ways to Prevent and Repair VMstart Errors in WM11OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-displays-that-wont-ignite-on-new-windows-versions/"><u>Addressing Displays That Won't Ignite On New Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-and-annotate-comics-easily-on-win11/"><u>Access and Annotate Comics Easily on Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-playbook-for-crafting-engaging-podcast-titles/"><u>2024 Approved  The Ultimate Playbook for Crafting Engaging Podcast Titles</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/best-practices-for-efficient-slide-capture/"><u>Best Practices for Efficient Slide Capture</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-videos-back-from-s23plus-by-fonelab-android-recover-video/"><u>Simple ways to get lost videos back from S23+</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-2024-approved-exploring-the-best-text-to-speech-online-tools-to-use/"><u>Updated 2024 Approved Exploring The Best Text-to-Speech Online Tools To Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719358153094-unlocking-cloud-storage-integrating-dropbox-and-google-drive-via-c/"><u>Unlocking Cloud Storage: Integrating Dropbox and Google Drive via C:</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-capture-hearts-on-tiktok-designed-templates-for-visual-impact/"><u>[Updated] Capture Hearts on TikTok  Designed Templates for Visual Impact</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-oppo-a78-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Oppo A78 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-social-caricature-craft-design-your-distinctive-avatar/"><u>[New] Social Caricature Craft  Design Your Distinctive Avatar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-quickly-solve-windows-screen-problems/"><u>5 Tips to Quickly Solve Windows Screen Problems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-zte-blade-a73-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On ZTE Blade A73 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719372954607-swift-rescue-solving-windows-problems-with-expertise/"><u>Swift Rescue: Solving Windows Problems with Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292309532-revolutionize-incompatibility-on-windows-without-tools/"><u>Revolutionize Incompatibility on Windows without Tools!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-affordable-windows-10-licensing-and-deals/"><u>A Deep Dive Into Affordable Windows 10 Licensing & Deals</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-decoding-the-functionality-of-youtubes-media-hub-for-2024/"><u>[New] Decoding the Functionality of YouTube's Media Hub for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/discover-the-magic-of-high-dynamic-range-in-photography-for-2024/"><u>Discover the Magic of High Dynamic Range in Photography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-os-public-ip-command-prompt-tricks/"><u>Accessing OS Public IP: Command Prompt Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-absence-of-msvcr110dll-a-guide/"><u>Addressing the Absence of msvcr110.dll: A Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-essential-adobe-premiere-plugins-for-creators-top-picks-free-and-premium-for-2024/"><u>Updated Essential Adobe Premiere Plugins for Creators Top Picks (Free & Premium) for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-effective-interview-techniques/"><u>2024 Approved  Mastering Effective Interview Techniques</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-show-your-love-how-to-create-a-beautiful-valentines-day-video-montage/"><u>Updated Show Your Love How to Create a Beautiful Valentines Day Video Montage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-enable-telnet-in-windows-10-and-11/"><u>3 Ways to Enable Telnet in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-detected-proxy-settings-on-windows-immediately/"><u>Addressing Non-Detected Proxy Settings on Windows Immediately</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-critical-list-of-5-striking-social-media-brand-animations/"><u>2024 Approved  Critical List of 5 Striking Social Media Brand Animations</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-critical-chrome-extensions-for-easy-vimeo-access/"><u>[New] 2024 Approved  Critical Chrome Extensions for Easy Vimeo Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-awareness-custom-notification-for-win11-users/"><u>Accelerating Battery Awareness: Custom Notification for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-responsive-windows-11-context-items/"><u>Addressing Non-Responsive Windows 11 Context Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-nighttime-display-in-notepad-windows-11-edition/"><u>Activating Nighttime Display in Notepad Windows 11 Edition</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-5-essential-steps-to-prevent-blank-screen-issues-in-obs/"><u>[New] 2024 Approved  5 Essential Steps to Prevent Blank-Screen Issues in OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-routes-to-rescue-your-stream-with-a-fixed-obs-link-on-windows/"><u>7 Routes to Rescue Your Stream with a Fixed OBS Link on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatingdeactivating-windows-key-made-simple/"><u>Activating/Deactivating Windows Key Made Simple</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-tips-for-enabling-grid-on-google-meet/"><u>[Updated] 2024 Approved  Tips for Enabling Grid on Google Meet</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-itel-p40plus-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Itel P40+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/2024s-top-windows-gear-a-comprehensive-review-list/"><u>2024'S Top Windows Gear - A Comprehensive Review List</u></a></li>
</ul></div>
