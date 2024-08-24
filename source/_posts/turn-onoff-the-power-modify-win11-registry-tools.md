---
title: "Turn On/Off the Power: Modify Win11 Registry Tools"
date: 2024-08-23T07:08:46.571Z
updated: 2024-08-24T07:08:46.571Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Turn On/Off the Power: Modify Win11 Registry Tools"
excerpt: "This Article Describes Turn On/Off the Power: Modify Win11 Registry Tools"
keywords: Turn Windows Power Control,Win11 Power Switching,Edit Windows Registry,Enable Win11 Settings,Disable Win11 Features,Modify Windows Tools,Access Win11 Options
thumbnail: https://thmb.techidaily.com/5b80927e68923eec1d1361008f6bde3827f135dcc6188baf767c77fe55f4ad9e.png
---

## Turn On/Off the Power: Modify Win11 Registry Tools

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

## 1\. How to Disable or Enable Registry Editor Access via the Group Policy Editor

 The most straightforward way to block access to the Registry Editor on Windows is via the Group Policy Editor. However, it’s important to note that this tool is only available on Windows Pro, Education, and Enterprise editions. If you happen to be using Windows Home, refer to our guide on [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > System**.
4. Double-click the **Prevent access to registry editing tools** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** followed by **OK**.  
![Block Registry Editor Access via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-group-policy-editor.jpg)

 Following this, users will see the “Registry editing has been disabled by your administrator” message when they attempt to access the Registry Editor. If you want to re-enable Registry Editor later, repeat the above steps and set the **Prevent access to registry editing tools** policy to **Not configured** or **Disabled**.

## 2\. How to Disable or Enable Registry Editor Access via the Registry Editor

 Another way to restrict the Registry Editor access on Windows involves using the Registry Editor itself. Here are the steps you can follow.

1. Click the **search icon** on the taskbar to access the search menu.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when [the User Account Control (UAC) prompt](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies**.
5. Right-click on the **Policies** key and select **New > Key**. Name it **System**.
6. Right-click on the **System** key and select **New > DWORD (32-bit) Value**. Name it **DisableRegistryTools**.
7. Double-click the newly created DWORD, type **1** in the Value data field, and hit **OK**.  
![Block Registry Editor Access via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-registry-editor.jpg)

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
4. Click the **File** menu and select **Save as**.
5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-elevate-your-fb-presence-with-top-10-music-videos-guide/"><u>[New] Elevate Your FB Presence with Top 10 Music Videos Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-linking-your-favorite-tiktoks-seamlessly-to-facebook-for-2024/"><u>[New] Linking Your Favorite TikToks Seamlessly to Facebook for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-photoshops-secret-weapon-advanced-techniques-for-3d-lut-mastery/"><u>[New] Photoshop's Secret Weapon  Advanced Techniques for 3D Lut Mastery</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-satirists-web-workshop/"><u>[New] Satirist's Web Workshop</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-dell-p2715q-review-a-glimpse-into-ultra-hd-technology/"><u>2024 Approved  Dell P2715Q Review  A Glimpse Into Ultra HD Technology</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sketch-up-your-ideas-an-essential-guide-to-the-top-8-drawing-tools-on-ios/"><u>2024 Approved  Sketch Up Your Ideas  An Essential Guide to the Top 8 Drawing Tools on iOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tune-up-the-mundane-how-to-add-custom-ringtones-and-sounds-for-a-unique-auditory-experience-on-android/"><u>2024 Approved  Tune Up the Mundane  How to Add Custom Ringtones & Sounds for a Unique Auditory Experience on Android</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/customize-and-download-free-outro-video-templates-for-2024/"><u>Customize and Download Free Outro Video Templates for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-and-mending-windows-audio-glitch-code-9999/"><u>Demystifying and Mending Windows Audio Glitch: Code 9999</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/digital-revolution-integrating-dslr-into-online-platforms-from-home-pcsmacs-for-2024/"><u>Digital Revolution  Integrating DSLR Into Online Platforms From Home PCs/Macs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-quick-and-efficient-ways-to-access-windows-11-sounds/"><u>Discover Quick and Efficient Ways to Access Windows 11 Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-method-for-converting-heic-to-jpeg-with-windows-11/"><u>Effective Method for Converting HEIC to JPEG with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-media-player-server-issue/"><u>Eliminating Media Player Server Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-smooth-xbox-microphone-integration-in-windows-11-ecosystem/"><u>Ensuring Smooth Xbox Microphone Integration in Windows 11 Ecosystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-windows-flashing-screen-in-windows-11-pcs/"><u>Fix Window's Flashing Screen in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-apps-clash-over-camera-access-code-0xa00f4243/"><u>Fixing Apps Clash Over Camera Access: Code 0xA00F4243</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-the-hidden-taskbar-search-in-windows-11/"><u>How to Enable the Hidden Taskbar Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-world-of-warcraft-update-stuck-on-initializing-on-windows/"><u>How to Fix a World of Warcraft Update Stuck on Initializing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-your-closed-windows-console-instantly/"><u>How to Resurrect Your Closed Windows Console Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-correcting-directionally-biased-windows-earbuds/"><u>Identifying & Correcting Directionally Biased Windows Earbuds</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-xiaomi-redmi-13c-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Xiaomi Redmi 13C 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-perfect-your-watchlist-with-controlled-netflix-frame-rate/"><u>In 2024, Perfect Your Watchlist with Controlled Netflix Frame Rate</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-virtual-horizons-on-android-a-guide-to-the-top-15-games/"><u>In 2024, Virtual Horizons on Android  A Guide to the Top 15 Games</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/iphones-and-gifs-perfecting-your-visual-playlist-for-2024/"><u>IPhones & GIFs  Perfecting Your Visual Playlist for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-your-android-a-guide-to-utilizing-the-measure-tool/"><u>Mastering Your Android: A Guide to Utilizing the Measure Tool</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-samsung-galaxy-s23-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Samsung Galaxy S23 – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritizing-productivity-make-terminal-first/"><u>Prioritizing Productivity: Make Terminal First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-guide-resurrect-your-chrome-browser-in-w11/"><u>Quick Fix Guide: Resurrect Your Chrome Browser in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-control-over-your-text-editor-fixing-windows-notepad-open-issues/"><u>Regain Control Over Your Text Editor: Fixing Windows Notepad Open Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-transition-from-windows-7-to-windows-11/"><u>Seamless Transition From Windows 7 to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-system-changes-mastery-of-cli-and-registry-modifications/"><u>Simplifying System Changes: Mastery of CLI and Registry Modifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fixes-to-steam-logins-in-rust-on-your-windows-machine/"><u>Step-by-Step Fixes to Steam Logins in Rust on Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-inaccessible-game-sessions-due-to-steams-vac/"><u>Tackling Inaccessible Game Sessions Due to Steam’s VAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-notebook-aesthetics-with-windows-11-themes-and-fonts-guide/"><u>Tailoring Notebook Aesthetics with Windows 11 Themes & Fonts Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-risks-of-using-a-chatgpt-mobile-application-why-it-might-not-be-worth-your-time/"><u>The Risks of Using a ChatGPT Mobile Application: Why It Might Not Be Worth Your Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-a-brighter-bolder-cursor-on-windows/"><u>The Ultimate Guide to a Brighter, Bolder Cursor on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-o365-sync-issues-on-windows/"><u>Troubleshooting O365 Sync Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-5-fixes-rectifying-secure-key-mismatch-errors/"><u>Win11's 5 Fixes: Rectifying Secure Key Mismatch Errors</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>