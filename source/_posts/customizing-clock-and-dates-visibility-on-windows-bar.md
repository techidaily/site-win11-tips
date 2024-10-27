---
title: Customizing Clock and Dates Visibility on Windows Bar
date: 2024-10-22T16:22:13.278Z
updated: 2024-10-26T23:33:12.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Clock and Dates Visibility on Windows Bar
excerpt: This Article Describes Customizing Clock and Dates Visibility on Windows Bar
keywords: Visible Clock Windows,Custom Date Display PC,Windows Bar Time Adjust,Set Clock Appearance WIN,Personalize Date View Win,Clock Window Settings PC,Date Window Customization Windows
thumbnail: https://thmb.techidaily.com/1e95a148d850ecdd275c10a51292b0ccb900f6b4eff5c9989165ba5b957b7575.jpg
---

## Customizing Clock and Dates Visibility on Windows Bar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .

6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-energetic-speaker-review-iteration-viii/"><u>[New] In 2024, Energetic Speaker Review - Iteration VIII</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-delving-into-youtubes-digital-video-workshop/"><u>[Updated] In 2024, Delving Into YouTube's Digital Video Workshop</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-discovering-movavis-advanced-video-editor-plus-plus/"><u>2024 Approved Discovering Movavi's Advanced Video Editor Plus +</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/cut-the-chatter-capture-game-moments-easily/"><u>Cut the Chatter Capture Game Moments Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-wacatacbml-signature-and-defense-for-windows-users/"><u>Exploring the Depths of Wacatac.B!ml: Signature & Defense for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/google-wireless-nest-doorbell-a-comprehensive-review-for-battery-operated-models/"><u>Google Wireless Nest Doorbell - A Comprehensive Review for Battery-Operated Models</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-audacity-error-code-9999-in-windows-1110/"><u>How to Fix the Audacity Error Code 9999 in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-11-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-nvidia-control-panel-access-denied-error-in-windows-1110/"><u>How to Fix the NVIDIA Control Panel “Access Denied” Error in Windows 11/10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-ios-system-issues-of-iphone-11-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iOS System Issues of iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-blue-screen-recovery-steps/"><u>Mastering Windows 11 Blue Screen Recovery Steps</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-flip-your-tiktok-videos-a-comprehensive-guide-to-reversing-clips/"><u>New In 2024, Flip Your TikTok Videos A Comprehensive Guide to Reversing Clips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieving-lost-actions-from-winrunhist/"><u>Retrieving Lost Actions From WinRunHist</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strategies-to-combat-windows-1011-error-740/"><u>Swift Strategies to Combat Windows 10/11 Error 740</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/there-are-five-classes-of-fire-based-on-fuel-type-a-b-c-d-and-k/"><u>There Are Five Classes of Fire Based on Fuel Type: A, B, C, D, and K</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-podcast-editing-101-how-to-edit-a-podcast/"><u>Updated In 2024, Podcast Editing 101 How to Edit a Podcast</u></a></li>
</ul></div>

