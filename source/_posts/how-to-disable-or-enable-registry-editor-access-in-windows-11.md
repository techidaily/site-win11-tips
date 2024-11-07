---
title: How to Disable or Enable Registry Editor Access in Windows 11
date: 2024-11-01T16:46:19.587Z
updated: 2024-11-07T01:07:32.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable or Enable Registry Editor Access in Windows 11
excerpt: This Article Describes How to Disable or Enable Registry Editor Access in Windows 11
keywords: Win11 RegEdit Control,Windows Registry Lock,Enable/Disable Windows Registry,Windows 11 RegKey Accessibility,RegEdit Security Settings,Windows Registry Permission,Change RegEdit Status in Win11
thumbnail: https://thmb.techidaily.com/0132287bf7d51b07521a43a3870f625dc6e6364d7e4121c0d057d3f42a0a988f.jpg
---

## How to Disable or Enable Registry Editor Access in Windows 11

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
4. Click the **File** menu and select **Save as**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144273/7443" target="_top" id="2144273">
  <img src="//a.impactradius-go.com/display-ad/7443-2144273" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144273/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-ultimate-zoom-audio-capture-techniques/"><u>[New] In 2024, Ultimate ZOOM Audio Capture Techniques</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-the-quintessential-list-of-top-15-masterpieces-in-stop-motion/"><u>[New] The Quintessential List of Top 15 Masterpieces in Stop Motion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-discovering-beyond-vidcon-key-youtube-occasions/"><u>[Updated] 2024 Approved Discovering Beyond VidCon Key Youtube Occasions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/1716069203858-updated-in-2024-essential-offline-ios-game-list-unplugged-fun-awaits/"><u>[Updated] In 2024, Essential Offline iOS Game List - Unplugged Fun Awaits!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-typing-experience-the-win-enter-key-fix/"><u>Enhancing Typing Experience: The Win Enter Key Fix</u></a></li>
<li><a href="https://fox-that.techidaily.com/four-key-strategies-to-accelerate-safari-speed-issues-on-ios-devices/"><u>Four Key Strategies to Accelerate Safari Speed Issues on iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-failed-connections-with-secure-vpn-access/"><u>How to Mend Failed Connections with Secure VPN Access</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ipad-pro-versus-macbook-air-determining-the-ideal-device-for-your-needs-techradar/"><u>IPad Pro Versus MacBook Air: Determining the Ideal Device for Your Needs | TechRadar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-memory-overuse-in-windows-via-edges-webview2/"><u>Minimizing Memory Overuse in Windows via Edge's WebView2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-iomap64sys-blue-screen-errors-on-windows-os/"><u>Solving IOMap64.sys Blue Screen Errors on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-insights-for-free-players-on-old-chessboard-mastery/"><u>Strategic Insights for Free-Players on Old Chessboard Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-maintaining-vscode-on-windows-11/"><u>Strategies for Maintaining VSCode on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-conversion-software-roundup-for-win-users/"><u>Top Conversion Software Roundup for Win Users</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-tasks-with-chatgpt-for-professional-success/"><u>Transforming Tasks with ChatGPT for Professional Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-now-webcam-and-mic-functionality-check/"><u>Troubleshoot Now: Webcam & Mic Functionality Check</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-ai-chatbots-the-reason-behind-their-rising-popularity/"><u>Understanding AI Chatbots: The Reason Behind Their Rising Popularity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-correcting-windows-update-hiccup-error-0x800f080a/"><u>Unraveling & Correcting Window's Update Hiccup Error 0X800f080a</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-mobile-video-mastery-top-split-screen-apps-for-iphone-and-android-for-2024/"><u>Updated Mobile Video Mastery Top Split Screen Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-motorola-razr-40-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Motorola Razr 40 Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    