---
title: "Command: Enable/Disable Registry Access in Win11"
date: 2024-10-21T21:35:22.430Z
updated: 2024-10-26T19:21:26.525Z
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
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-brain-eaters-unleashed-a-compelling-list/"><u>[New] Brain-Eaters Unleashed A Compelling List</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-filmoras-quick-start-approach-for-youtube-trailers/"><u>[Updated] 2024 Approved Filmora's Quick-Start Approach for YouTube Trailers</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-mastering-podcast-name-selection-step-by-step-guide-plus-50plus-top-ideas-list/"><u>2024 Approved Mastering Podcast Name Selection Step-by-Step Guide + 50+ Top Ideas List</u></a></li>
<li><a href="https://vp-tips.techidaily.com/dvdmacx-dvd-ripper-promac/"><u>進化型DVDライティングソフトウェア「Macx DVD Ripper Pro」の最新バージョンでMacパワーアップ</u></a></li>
<li><a href="https://fox-info.techidaily.com/effortless-edits-bending-image-into-shape/"><u>Effortless Edits Bending Image Into Shape</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978959404-elevate-your-pcs-performance-with-msi-z370-a-pro-drivers-free-download-available-now/"><u>Elevate Your PC's Performance with MSI Z370-A Pro Drivers – Free Download Available Now!</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-top-gaming-thumbs-for-immersive-experience/"><u>In 2024, Top Gaming Thumbs for Immersive Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-updater-problem-code-0x8019/"><u>Overcoming Updater Problem: Code 0X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-slow-or-non-responsive-windows-download-area/"><u>Repairing Slow or Non-Responsive Windows Download Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-windows-os-not-found-error/"><u>Swift Solution to Windows OS 'Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-zero-error-mystery-in-windows-11-updates/"><u>Unraveling Zero-Error Mystery in Windows 11 Updates</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    