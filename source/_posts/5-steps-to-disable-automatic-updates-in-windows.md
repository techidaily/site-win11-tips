---
title: 5 Steps To Disable Automatic Updates in Windows
date: 2024-07-12T17:20:03.746Z
updated: 2024-07-13T17:20:03.747Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Steps To Disable Automatic Updates in Windows
excerpt: This Article Describes 5 Steps To Disable Automatic Updates in Windows
keywords: Auto Update Windows Off,Stop Windows Update,Disable OS Updates,No Auto Windows Updates,Turn Off Windows Update,Block Windows Automatic Update,Prevent Windows Update,Stop OS Auto-Update,Prevent Windows Updates (Already Included as 7Th Keyword),No Automatic Windows Update,Disable Windows Update (Already Included as a Keyword),Block Windows Auto-Updater,Turn Off Window's Update Mechanism
thumbnail: https://thmb.techidaily.com/8bc720ee0adbf09ae88a648a38e027832e102c5d3884a2078035ea55eb60772c.jpg
---

## 5 Steps To Disable Automatic Updates in Windows

 By default, all your Office apps are set to update themselves automatically in the background. Although this approach keeps your Office apps updated with the latest features and improvements, these updates can sometimes overwhelm you or worse, cause new problems.

 Fortunately, there are several ways to disable automatic Office updates on Windows. Let's go over each of those methods one by one.

## 1\. How to Stop Automatic Office Updates via the Settings App

 Windows lets you check for any pending Office updates directly from the Settings app. This allows you to install Office updates along with other system updates. If you don’t want that, you can disable the**Receive updates for other Microsoft products** option in the Settings app. Here are the steps for the same.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Windows Update** from the left sidebar.
3. Select**Advanced options** .
4. Disable the toggle next to**Receive updates for other Microsoft products** .  
![Stop Automatic Office Updates Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-the-settings-app.jpg)

## 2\. How to Stop Automatic Office Updates Using One of Its Apps

 You can also opt out of automatic Office updates by using one of its apps, such as Word or Excel. Here’s how you can go about it.

1. Open any Office app, such as Word.
2. Click the**File** menu in the top left corner.
3. Select**Account** from the left pane.
4. Click the**Update Options** drop-down menu in the Manage Account section and choose**Disable Updates** .
5. Select**Yes** to confirm.  
![Stop Office Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-office-updates.jpg)

 Once you complete the above steps, your Office apps will not check for and install newer updates. Don't worry, you'll still be able to install updates manually.

 If you want to re-enable automatic updates later, use the same steps above and select**Enable Update** in the**Update Options** menu.

## 3\. How to Stop Automatic Office Updates Using the Group Policy Editor

 Another way to disable automatic Office updates is via the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor on Professional, Education, or Enterprise editions of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 By default, the Group Policy Editor does not include any modules for managing Microsoft Office settings. So, in order to stop automatic Office updates via the Group Policy Editor, first, you’ll have to download and install Administrative Templates for Microsoft Office products. Here are the steps for the same.

1. Open up your web browser and head over to Microsoft Download Center to [download the Administrative Template files (ADMX/ADML) for Office apps](https://www.microsoft.com/en-us/download/details.aspx?id=49030) .  
![Download Office Administrative Templates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/download-office-administrative-templates.jpg)
2. Double-click the downloaded**EXE file** to run it.
3. Accept the license terms and click the**Continue** button.
4. The installer will prompt you for a location to extract the contents. Select an empty folder and hit**OK** .
5. Go to the location where you extracted the files and open the**admx** folder.
6. Select all the**admx files** and press**Ctrl + C** to copy them.
7. Head to**C: > Windows > PolicyDefinitions** folder.
8. Paste all the admx files in the**PolicyDefinitions** folder.  
![Copy Office ADMX files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-admx-files-to-policydefinitions-folder.jpg)
9. Return to the folder where you extracted the files and open the**admx** folder again.
10. Open the**en-US** folder and copy all the**adml files** within.
11. Head to**C: > Windows > PolicyDefinitions** \>**en-US** folder and paste all the**adml files** .  
![Copy Office ADML files to PolicyDefinitions Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/copy-office-adml-files-to-policydefinitions-folder.jpg)

 After completing the above steps, you’re all set to disable automatic Office updates via the Group Policy Editor. Here are the steps you can follow.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **Local Computer Policy > Computer Configuration > Administrative Templates > Microsoft Office 2016 > Updates** .
4. Double-click the**Enable Automatic Updates** policy on your right.  
![Stop Automatic Office Updates Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/stop-automatic-office-updates-using-group-policy-editor.jpg)
5. Select the**Disabled** option.
6. Hit**Apply** followed by**OK** .
7. Next, press**Win + R** to open the Run dialog.
8. Type**cmd** in the text box and press**Ctrl + Shift + Enter** to [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
9. Type**gpupdate /force** in the console and hit**Enter** to apply the Group Policy changes.

 If you want to re-enable automatic updates for Office apps later, simply set the**Enable Automatic Updates** policy to**Enabled** .

## 4\. How to Stop Automatic Office Updates With the Registry Editor

 You can also use the Registry Editor to make the above policy change and disable automatic Office updates on your computer. Since Registry Editor holds important settings for Windows and its apps, you should only use this method if you’re comfortable editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 If you decide to use this method, make sure you back up all the registry files or create a restore point beforehand. If you need help, refer to our guide on [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and follow the steps outlined there.

 Once you've done that, use the following steps to disable automatic Office updates via the Registry Editor.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **Computer > HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft** .  
![Registry Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor.jpg)
5. Right-click the**Microsoft** key and select**New > Key** .

1. Rename the key as**Office** .
2. Right-click on the**Office** key and select**New > Key** .
3. Rename the key as**16.0** .
4. Right-click the**16.0** key and select**New > Key** .
5. Rename the key as**Common** .
6. Within the**Common** key, create another key named**OfficeUpdate** .
7. Right-click the**OfficeUpdate** key and select**New > DWORD (32-bit) Value** . Name this new DWORD**EnableAutomaticUpdates** .
8. Double-click**EnableAutomaticUpdates** DWORD and set its**Value Data** to**0** .
9. Click**OK** .  
![Turn Off Automatic Office Updates Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-automatic-office-updates-using-registry-editor.jpg)

 After completing the above steps, restart your computer. Following that, Office apps won’t update automatically on your computer. If you want to undo this change, open the Registry Editor again and delete the**EnableAutomaticUpdates** DWORD.

## Stop Automatic Office Updates on Windows

 It is almost always preferable to keep your Office apps up to date so that you can benefit from new features and security updates. Hence, if you disable automatic Office updates for some reason, don’t forget to check for new updates manually every once in a while.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-vimeos-no-money-solution-easy-editing-basics/"><u>In 2024, Vimeo's No-Money Solution  Easy Editing Basics</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-beatmatching-your-vids-syncing-music-seamlessly-on-facebook/"><u>[Updated] 2024 Approved  Beatmatching Your Vids  Syncing Music Seamlessly on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pc-with-w11-taskbar-adjustments/"><u>Elevate Your PC with W11 Taskbar Adjustments</u></a></li>
<li><a href="https://network-issues.techidaily.com/challenge-cleared-combat-corrected/"><u>Challenge Cleared: Combat Corrected</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-glitches-to-achieve-uninterrupted-gameplay-win-11/"><u>Overcoming Steam Glitches to Achieve Uninterrupted Gameplay Win 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/stepping-through-sound-decline-a-step-by-step-approach-to-audio-fade-outs/"><u>Stepping Through Sound Decline A Step-by-Step Approach to Audio Fade Outs</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-future-of-pc-gaming-meet-eizos-cg318-4k-for-2024/"><u>The Future of PC Gaming  Meet EIZO's CG318-4K for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-windows-11-desktop-menu-layout/"><u>Personalizing Your Windows 11 Desktop Menu Layout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-closure-opening-folderfile-secrets-quickly/"><u>Inside Closure: Opening Folder/File Secrets Quickly</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-view-gpx-files-online-and-offline-solutions-of-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>How to View GPX Files Online and Offline Solutions Of Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovery-of-missing-widgets-and-icons-on-windows-11/"><u>Recovery of Missing Widgets and Icons on Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-unlock-more-views-twitch-to-facebook-streaming-tips/"><u>2024 Approved  Unlock More Views  Twitch to Facebook Streaming Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-key-screen-snapping-programs-for-content-sharing/"><u>2024 Approved  Key Screen-Snapping Programs for Content Sharing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-win-11-gaming-landscape-with-these-fps-counters/"><u>Mastering the Win 11 Gaming Landscape with These FPS Counters</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Xiaomi Redmi Note 12 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-comparing-streamlabs-with-obs-for-professional-broadcasts/"><u>In 2024, Comparing Streamlabs with OBS for Professional Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fortify-windows-11-security-integrating-firewalls-into-the-menubar-ui/"><u>Fortify Windows 11 Security: Integrating Firewalls Into the Menubar UI</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/quick-time-cameo-evaluation/"><u>Quick-Time Cameo Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-protocol-port-vulnerability-check-for-windows/"><u>Network Protocol Port Vulnerability Check for Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Realme C55? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-smart-adjustments-color-control-in-win11-apps/"><u>Enabling Smart Adjustments: Color Control in Win11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-address-error-0x800700e1-issues-on-windows-11-pcs/"><u>Essential Steps to Address Error 0X800700E1 Issues on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-elusive-windows-search-responses/"><u>Recovering Elusive Windows Search Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-engaging-photoshop-on-modern-windows-machines/"><u>Effortlessly Engaging Photoshop on Modern Windows Machines</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-choosing-the-best-cameras-and-lenses-for-vloggers/"><u>2024 Approved  Choosing the Best Cameras & Lenses for Vloggers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/for-the-newcomer-in-windows-11-world-sidestep-these-8-missteps/"><u>For the Newcomer in Windows 11 World, Sidestep These 8 Missteps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-infinix-note-30-vip-racing-edition-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Infinix Note 30 VIP Racing Edition FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-remote-desktop-tricks-without-passwords-on-windows-11/"><u>Breaking Barriers: Remote Desktop Tricks without Passwords on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-through-windows-11s-pin-blockade/"><u>Cut Through Windows 11'S PIN Blockade</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-free-video-editor-options-for-beginners-desktop-online-and-mobile-apps/"><u>New Free Video Editor Options for Beginners Desktop, Online, and Mobile Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/techniques-for-elevating-your-tiktok-unboxing-popularity/"><u>Techniques for Elevating Your TikTok Unboxing Popularity</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/hot-snapshots-eye-catching-filters-and-lenses-explored/"><u>Hot Snapshots  Eye-Catching Filters & Lenses Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-overlapping-app-symbols-on-pc-screen/"><u>Rectifying Overlapping App Symbols on PC Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-failed-projection-links-on-windows-os/"><u>How to Tackle Failed Projection Links on Windows OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/capture-nostalgia-uploading-past-photos-as-snaps-for-2024/"><u>Capture Nostalgia - Uploading Past Photos as Snaps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-intrusions-top-7-windows-safeguarding-methods/"><u>Preventing Intrusions: Top 7 Windows Safeguarding Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-win-gameplay-with-dxvk-why-gamers-should-care/"><u>Maximize Win Gameplay with DXVK – Why Gamers Should Care</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-iphone-6s-drfone-by-drfone-ios/"><u>How to Remove and Reset Face ID on iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-secure-and-simple-the-top-10-trusted-online-transformers/"><u>In 2024, Secure and Simple  The Top 10 Trusted Online Transformers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-desktop-capture-the-windows-user-guide/"><u>[New] In 2024, Desktop Capture  The Windows User Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-change-new-directions-for-winadmin-access-control/"><u>Initiating Change: New Directions for WinAdmin Access Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-error-31-steps-for-fixing-network-connectivity-issues/"><u>Decoding Windows Error 31: Steps for Fixing Network Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identity-infiltration-windows-fingerprints-in-the-crosshairs/"><u>Identity Infiltration: Windows Fingerprints in the Crosshairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-recovery-for-non-functional-windows-software/"><u>Immediate Recovery for Non-Functional Windows Software</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-transitions-fading-techniques-in-premiere-pro/"><u>Mastering Transitions  Fading Techniques in Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-school-explorer-revival-strategies/"><u>Old-School Explorer Revival Strategies</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ing-a-powerful-content-strategy-uncover-the-best-5-youtube-marketing-tactics/"><u>Crafting a Powerful Content Strategy  Uncover the Best 5 YouTube Marketing Tactics</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-8-free-online-courses-for-beginner-youtube-creators/"><u>[New] 2024 Approved  8 Free Online Courses for Beginner YouTube Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-operation-requirement-issues-on-windows-11-and-11/"><u>Demystifying Operation Requirement Issues on Windows 11 & 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-eco-filmmaking-simplified-youtubes-green-screen-wonders/"><u>In 2024, Eco-Filmmaking Simplified  YouTube's Green Screen Wonders</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-solemn-sonatas-classic-music-selections-to-enhance-wedding-cinematography-for-2024/"><u>New Solemn Sonatas Classic Music Selections to Enhance Wedding Cinematography for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-iphone-picture-import-glitches/"><u>Fixing Windows 10/11 iPhone Picture Import Glitches</u></a></li>
</ul></div>
