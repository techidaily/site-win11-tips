---
title: Bringing Back Original Settings to Windows 11 Touch Panel
date: 2025-01-19T21:58:49.583Z
updated: 2025-01-25T01:29:14.307Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bringing Back Original Settings to Windows 11 Touch Panel
excerpt: This Article Describes Bringing Back Original Settings to Windows 11 Touch Panel
keywords: Win11 Original Panels,Revive Windows Tiles,Nostalgic Window Settings,Redesign W11 Display,Restore Windows Touch Panel,Classic Windows UI Update,Echoed Windows Features
thumbnail: https://thmb.techidaily.com/cb769af3708fc15b594c9ede31a115d7b902d54d4fbcec56dcebaeb9d186f784.jpg
---

## Bringing Back Original Settings to Windows 11 Touch Panel

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/new-capturing-life-in-new-ways-hero-4-and-hero-5/"><u>[New] Capturing Life in New Ways Hero 4 & Hero 5</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-a-compre-written-in-code-deciphering-youtube-backlink-building-techniques/"><u>[Updated] A Compre Written in Code Deciphering YouTube Backlink Building Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-maximizing-fun-finding-hot-images-at-pexelscom/"><u>[Updated] Maximizing Fun Finding Hot Images at Pexels.com</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleashing-potential-the-easy-path-to-blending-linktree-with-tiktok-bios/"><u>[Updated] Unleashing Potential The Easy Path to Blending Linktree with TikTok Bios</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://discover-community.techidaily.com/iuwfqomdouinoplusaxuuawueazltroqjjmhrbljahkuirnmotlrrnph4lkozkui3lrzjlnkjmqptmoyjnmotpjkoqqqi/"><u>全面解決方法:記憶卡上的容量和不存在檔案的錯誤</u></a></li>
<li><a href="https://win-cheats.techidaily.com/1728482257786-iphone/"><u>现在可用！iPhone数据救援之王：【最适合的前两者】【刚更新完成】</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-tech-behind-windows-11s-file-protection-features/"><u>Delving Into the Tech Behind Windows 11'S File Protection Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-frame-rate-and-performance-in-win-based-roblox/"><u>Optimizing Frame Rate & Performance in Win-Based Roblox</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-sysware-device-lacks-os-compatibility/"><u>Solved: SysWare Device Lacks OS Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-with-an-emulated-mac-os-look-using-these-5-steps/"><u>Streamline Windows with an Emulated Mac OS Look Using These 5 Steps</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-and-repairing-missing-d3dx9dll-errors-on-your-computer/"><u>Troubleshooting and Repairing Missing d3dx9_^.dll Errors on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/user-management-mastery-for-win1110-home-editions/"><u>User Management Mastery for WIN11/10 Home Editions</u></a></li>
</ul></div>

