---
title: "Command: Enable/Disable Registry Access in Win11"
date: 2024-10-28T16:27:45.659Z
updated: 2024-11-01T18:19:13.357Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command: Enable/Disable Registry Access in Win11"
excerpt: "This Article Describes Command: Enable/Disable Registry Access in Win11"
keywords: Win11 Registry Control,Disable RegEdit Win11,Enable Windows Registry,Win11 RegAcess Management,Restrict Win11 RegEdit,Turn On/Off Win11 Reg,Manage Win11 Reg Access
thumbnail: https://thmb.techidaily.com/64d6132273fa0f5624faa24b024a9043c67b09153100a262ca37e1659c74f36a.jpg
---

## Command: Enable/Disable Registry Access in Win11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-in-2024-achieving-excellence-in-game-recording-techniques-windows-11-style/"><u>[New] In 2024, Achieving Excellence in Game Recording Techniques, Windows 11 Style</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-direct-download-of-youtube-content-for-2024/"><u>[Updated] Direct Download of YouTube Content for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-from-black-and-white-to-richness-embracing-hdrs-power-for-2024/"><u>[Updated] From Black and White to Richness Embracing HDR's Power for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-harnessing-video-magic-channel-creation-wizardry/"><u>2024 Approved Harnessing Video Magic Channel Creation Wizardry</u></a></li>
<li><a href="https://buynow-info.techidaily.com/beatit-bt-d11-power-surge-kit-review-a-comprehensive-look-at-high-impact-charging/"><u>Beatit BT-D11 Power Surge Kit Review: A Comprehensive Look at High Impact Charging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-windows-defense-with-customizable-firewall-options-in-context-menu/"><u>Elevate Windows Defense with Customizable Firewall Options in Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-windows-to-keep-files-organized-quickly/"><u>Empower Windows to Keep Files Organized Quickly</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-samsung-galaxy-z-flip-5-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Samsung Galaxy Z Flip 5 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-youtube-shorts-earnings-guide-must-knows-and-future-potential/"><u>In 2024, Youtube Shorts Earnings Guide Must-Knows & Future Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-resolving-disk-read-failed-error/"><u>Quick Guide: Resolving 'Disk Read Failed' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-window-world-8-customization-strategies-by-winbubble/"><u>Redefine Your Window World: 8 Customization Strategies by WinBubble</u></a></li>
<li><a href="https://some-guidance.techidaily.com/solve-your-youtube-display-issues-eliminate-black-screens-completely/"><u>Solve Your YouTube Display Issues - Eliminate Black Screens Completely!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-heic-files-into-jpeg-on-windows-11-platform/"><u>Streamlining HEIC Files Into JPEG on Windows 11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-resolve-w11-photoshop-not-launching-issue/"><u>Tips to Resolve W11 Photoshop Not Launching Issue</u></a></li>
</ul></div>

