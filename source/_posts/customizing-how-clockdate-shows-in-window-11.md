---
title: Customizing How Clock/Date Shows in Window 11
date: 2024-06-25T16:58:02.408Z
updated: 2024-06-26T16:58:02.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing How Clock/Date Shows in Window 11
excerpt: This Article Describes Customizing How Clock/Date Shows in Window 11
keywords: Windows Clock Personalization,Set Date Display Mode,Customize Time Format,Adjust Window 11 Time,Clock Appearance Control,Windows 11 Date Settings,Time Display Preferences
thumbnail: https://thmb.techidaily.com/96ca9c739207d23d042e7f8016b381f18f2564ff73ddf98034c5d696bcc3f7e9.jpg
---

## Customizing How Clock/Date Shows in Window 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

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

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

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
<li><a href="https://win11-tips.techidaily.com/deciph-written-as-a-dialogue-between-two-characters-user-and-assistant-in-an-online-forum-setting-discussing-the-topic-of-what-is-aggregatorhostexe-on-windo37/"><u>Deciph Written as a Dialogue Between Two Characters (User and Assistant) in an Online Forum Setting Discussing the Topic of What Is AggregatorHost.exe on Windows, and Is It Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-system-integration-windows-plus-kali-linux-setup/"><u>Conquering System Integration: Windows + Kali Linux Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719220019899-unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-vmware-freeze-ups-on-windows-11/"><u>Clearing Up VMware Freeze-Ups on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-wasd-isolation-necessity-or-concern/"><u>Understanding WASD Isolation: Necessity or Concern?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-top-6-computer-utilization-monitors-on-pcs/"><u>Discover the Top 6 Computer Utilization Monitors on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-jump-to-notes-starting-windows-with-immediate-access/"><u>Quick Jump to Notes: Starting Windows with Immediate Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intelligent-interface-ais-role-in-windows-evolution/"><u>The Intelligent Interface: AI's Role in Windows Evolution</u></a></li>
<li><a href="https://youtube-web.techidaily.com/mlining-video-dispatch-to-facebook-from-youtube/"><u>Streamlining Video Dispatch to Facebook From YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-ultimate-guide-to-documenting-your-ps4-journey/"><u>[New] In 2024, Ultimate Guide to Documenting Your PS4 Journey</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-incorporating-creative-effects-into-your-zoom-meetings-step-by-step/"><u>[Updated] Incorporating Creative Effects Into Your Zoom Meetings Step-by-Step</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-vivo-y100t-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Vivo Y100t Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-dji-phantom-3-a-complete-technical-review-for-2024/"><u>Unveiling DJI Phantom 3  A Complete Technical Review for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/resize-videos-in-no-time-a-simple-tutorial/"><u>Resize Videos in No Time A Simple Tutorial</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uilding-a-diverse-content-portfolio-on-youtube-shorts-for-2024/"><u>[New] Building a Diverse Content Portfolio on YouTube Shorts for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/dissecting-obs-technology-for-top-level-recording/"><u>Dissecting OBS Technology for Top-Level Recording</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-mastering-image-dimensions-how-to-calculate-the-perfect-ratio/"><u>Updated In 2024, Mastering Image Dimensions How to Calculate the Perfect Ratio</u></a></li>
</ul></div>
