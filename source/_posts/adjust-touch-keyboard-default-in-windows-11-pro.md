---
title: Adjust Touch Keyboard Default in Windows 11 Pro
date: 2025-01-28T00:11:11.318Z
updated: 2025-02-01T04:14:45.142Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
excerpt: This Article Describes Adjust Touch Keyboard Default in Windows 11 Pro
keywords: Win11 Keyboard Adjust,Default Keyboard Set,Change Touch Keys,Windows Touch Settings,Keyboard Config W11,Pro Windows Keyboard Adj,Update Touch Key Prefs
thumbnail: https://thmb.techidaily.com/44cba3f77a25fb10a15058a95ecd605b31dd154fe2d91aae028e5e688022e444.jpg
---

## Adjust Touch Keyboard Default in Windows 11 Pro

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a [backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-from-standard-to-spectacular-the-transformative-power-of-high-dynamic-range/"><u>[New] In 2024, From Standard to Spectacular The Transformative Power of High Dynamic Range</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-elevate-your-videos-with-expert-tips-on-vlc-spinning/"><u>[Updated] Elevate Your Videos with Expert Tips on VLC Spinning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-user-identity-extracting-sids-in-windows-11/"><u>Decoding User Identity: Extracting SIDs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-saving-of-windows-mixer-levels-properly/"><u>Ensuring Saving of Windows Mixer Levels Properly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-fixing-directdraw-crashes-in-windows-1011/"><u>Essential Tips for Fixing DirectDraw Crashes in Windows 10/11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-gaming-evolution-with-razers-deathadder-v3-tailor-your-controllers-speed-like-never-before/"><u>Experience Gaming Evolution with Razer's DeathAdder V3 – Tailor Your Controller’s Speed Like Never Before!</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/gratiswmv-player-die-superlative-software-zum-kostenlosen-abspielen-von-wmv-videos-auf-macos-und-windows/"><u>GratisWMV-Player: Die Superlative Software Zum Kostenlosen Abspielen Von WMV-Videos Auf macOS Und Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-depth-guide-to-optimizing-photos-using-polarr/"><u>In 2024, In-Depth Guide to Optimizing Photos Using Polarr</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/legal-steps-for-overcoming-a-youtube-copyright-strike/"><u>Legal Steps for Overcoming a YouTube Copyright Strike</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-window-display-settings-in-win11/"><u>Mastering Window Display Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-tweaks-using-alomwares-power-suite/"><u>Mastering Windows Tweaks: Using AlomWare's Power Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-graphics-issues-dxgi-error-fixes/"><u>Mastery over Graphics Issues: DXGI Error Fixes</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-todays-tech-landscape-a-look-inside-toms-hardware/"><u>Navigating Today's Tech Landscape: A Look Inside Tom's Hardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotting-hidden-pane-panes-strategies-to-try-with-win11/"><u>Spotting Hidden Pane Panes: Strategies to Try with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-battlenet-login-failure-on-windows-systems/"><u>Steps to Resolve Battle.net Login Failure on Windows Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tidy-up-your-pictures-top-10-online-unblur-tools/"><u>Tidy Up Your Pictures Top 10 Online Unblur Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-11-7-holiday-upgrades/"><u>Transforming Windows 11: 7 Holiday Upgrades</u></a></li>
<li><a href="https://win-guides.techidaily.com/vier-ansatze-zur-wiederherstellung-von-windows-11-aus-einer-fruheren-windows-10-version/"><u>Vier Ansätze Zur Wiederherstellung Von Windows 11 Aus Einer Früheren Windows 10-Version</u></a></li>
</ul></div>

