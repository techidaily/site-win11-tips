---
title: Tap Out of High Contrast in Windows Environment
date: 2024-07-12T17:34:25.403Z
updated: 2024-07-13T17:34:25.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tap Out of High Contrast in Windows Environment
excerpt: This Article Describes Tap Out of High Contrast in Windows Environment
keywords: High Contrast Exit,Windows High Contrast,Out of Contrast Mode,Accessibility Window Feature,Disable High Contrast,Windows Dark Mode Exit,Navigate Out of HC
thumbnail: https://thmb.techidaily.com/716b773a3a0bbb4238a628ab28cfde8731d3dd391169cbf818a66e733201ea5d.jpg
---

## Tap Out of High Contrast in Windows Environment

 Microsoft first introduced high-contrast themes with Windows 7\. The idea was to add a theme that helps users with low vision or photosensitivity see screen elements better. But not everyone needs the high contrast mode on Windows 11 or older versions. Maybe you turned it on by accident and are now struggling to turn it off.

 High contrast mode makes the screen elements darker to increase clarity, but the result may not look inviting for every user. As such, we will explore multiple methods to turn off the high contrast mode on Windows 11 or older operating systems.

## What Is High Contrast Mode?

 High Contrast Mode is an accessibility feature that comes free with Windows. It makes certain screen elements darker and more distinguishable so that users with low vision can see everything. High contrast mode isn’t limited to Windows only; you can also find it in Android, iOS, macOS, Linux, and more.

 But there is a dark mode on Windows 11, isn't there? So, why do we need high-contrast themes? It is because dark mode can reduce the strain on the eyes and is helpful for users who don’t have problems with their vision. But dark mode makes everything black except the text and people with low vision may struggle with it.

 High contrast themes offer customizability to tweak different screen elements, like text, links, background, button text, and more. It's a lot more helpful than dark mode, which just adds a dark or black-grayish background with a white color.

## How to Disable High Contrast Mode on Windows

 If High Contrast Mode has been turned on and you'd like to change that, there are multiple ways to get the job done.

### 1\. Using the High Contrast Mode Shortcut keys

 To disable high contrast mode on Windows using keyboard shortcuts, press the**Left Alt + Left Shift + Print Screen** keys at once. You won’t see any pop-up window to confirm the action, but you will hear a “beep” sound before the system reverts to the default theme. You can use this shortcut again if you need to re-enable High Contrast mode.

### 2\. Using the Settings app

 To disable the high contrast mode using the Settings app on Windows 8 and above, do as follows.

1. Press**Win + I** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) on your system.
2. Navigate to the left-hand side menu and click on**Personalization** .
3. Click on the**Themes** option under Personalization. Scroll down and click on the**Contrast Themes** option.
4. Click on the drop-down menu in the Contrast Themes option and select the**None** option.  
![Disable High Contrast Mode Using Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-settings-app.jpg)
5. Then, click on the**Apply** option. Windows will change back to the previous theme.

### 3\. Using the Sign-in screen

 You can even disable the high contrast mode on Windows 11 and 10 before you sign in. Here’s how to do it:

1. Power on your Windows PC. Press any key or click the mouse key to go to the sign-in screen.
2. Navigate to the bottom-right area and click on the**Accessibility** icon.
3. The Accessibility menu will pop up. Click on the**Contrast Theme** toggle to disable it.  
![Disable High Contrast Mode Using Sign In Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-sign-in-screen.jpg)
4. Windows will revert to the default theme. Enter your PIN or password and log in.

### 4\. Using the Control Panel

 To disable the high contrast mode in Windows 11 and 10, do as follows:

1. Press the**Win + S** to bring up Windows Search. Type Control Panel and click on the search result
2. The Control Panel will launch. Click on the**Appearance and Personalization** option.
3. Select the Ease of Access option and click on the**Set Up high contrast** option.
4. Now, select the**Choose a high contrast theme** option.  
![Disable High Contrast Mode Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-control-panel.jpg)
5. Navigate to**Themes > Contrast Themes** .
6. Click on the drop-down menu in the Contrast Themes option and select the**None** option.
7. Then, click on the**Apply** button.

 Windows 7 doesn’t have a Settings app, so the process of disabling high contrast mode using the Control Panel is a bit different:

1. Press the**Win** key and click on the Control Panel option.
2. Navigate to**Appearance and Personalization > Personalization** .
3. Click on the Windows classic theme or any other system theme.
4. Windows 7 will switch from the high contrast theme to a normal theme.

### 5\. Using the Run Dialog Box

 Repeat the following steps to disable high contrast mode using the run command box:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}** ” in the text input area and press the Enter key.  
![Disable High Contrast Mode Using Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-run-box.jpg)
3. The old personalization settings control panel window will launch.
4. Click on any system theme. It will deactivate the current high-contrast theme and apply the selected theme.

### 6\. Using Another Theme

 You can disable the high-contrast theme by applying another theme to your system. Here’s how to do it:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Personalization > Themes** .
3. Move to the**Current theme** section and click on any default system theme or a downloaded theme.  
![Disable High Contrast Mode Using A Different Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-different-theme.jpg)
4. Windows will apply the selected theme.

 If you want to re-enable the high-contrast theme, you have to visit the "high contrast theme" section here and choose a compatible theme.

### 7\. Using a Script

 It is also possible to revert to a system theme using a script file on Windows. It will take less time as opposed to navigating the settings app to disable the high contrast mode. Here’s how to do it:

1. Go to the desktop. Right-click on the desktop and click on**New > Text Document** .
2. Open the newly created text file and paste the following script into it.  
@echo off C:\Windows\resources\Themes\aero.themetaskkill /F /IM systemsettings.exe
3. Now, press**Ctrl + S** to save the file. Type the name “**disablehc.bat** ” and click on the**save** button.  
![Disable High Contrast Mode Using a script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-script.jpg)
4. Go to the desktop again and right-click on the newly created .bat file.
5. Select the**Run as administrator** option in the context menu.
6. UAC will pop up. Click on the**Yes** button to grant administrator privileges to the .bat file. Otherwise, it won’t be able to make changes to the system theme.
7. The command prompt will pop up for a few seconds, run the script, and then close automatically. Your Windows system will disable the high contrast mode and switch to the aero theme.

## The Windows High Contrast Theme Won’t Bother You Anymore

 These were the seven methods using which you can disable the high contrast theme on Windows. The quickest way is to use the hotkeys for contrast themes or use a BAT script. If you want to save your eyes from the harsh white light but cannot stand high-contrast themes, use a dark theme on Windows 11.

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
<li><a href="https://win11-tips.techidaily.com/why-bypass-chatbot-assistance-in-win-11-key-gen/"><u>Why Bypass Chatbot Assistance in Win 11 Key Gen</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-xiaomi-13t-pro-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Xiaomi 13T Pro? Look No Further | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unleash-the-power-of-live-broadcast-recording-techniques-online/"><u>Unleash the Power of Live Broadcast  Recording Techniques Online</u></a></li>
<li><a href="https://extra-tips.techidaily.com/green-frameworks-30plus-downloads-that-transform-your-videography-skills/"><u>Green Frameworks  30+ Downloads That Transform Your Videography Skills</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-a15-4g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy A15 4G Pattern Lock Screen</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-intova-x-pushing-video-tech-boundaries/"><u>In 2024, Inside Intova X  Pushing Video Tech Boundaries</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-tecno-spark-20-pro-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Tecno Spark 20 Pro FRP Bypass Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-storage-repositioning-in-onedrive-for-win-11/"><u>Tailor-Made Storage Repositioning in OneDrive for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-enhanced-lg-bp550-review-2023-update/"><u>[Updated] In 2024, The Enhanced LG BP550 Review - 2023 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-eradicate-wow-error-132-in-1011/"><u>Winning Strategies: Eradicate WoW Error 132 in 10/11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-streamline-video-calls-using-google-hangouts-efficiently/"><u>[New] In 2024, Streamline Video Calls  Using Google Hangouts Efficiently</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-how-i-animate-discord-profile-pictures-and-you-can-too/"><u>New In 2024, How I Animate Discord Profile Pictures (& You Can Too)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-video-production-with-clear-sound-effects/"><u>2024 Approved  Streamlining Video Production with Clear Sound Effects</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-reclaiming-acoustics-lost-in-social-media-videos-for-2024/"><u>[New] Reclaiming Acoustics Lost in Social Media Videos for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-contacts-after-xiaomi-redmi-note-13-pro-5g-has-been-deleted-by-fonelab-android-recover-contacts/"><u>Recover your contacts after Xiaomi Redmi Note 13 Pro 5G has been deleted.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-journey-through-data-storage-saving-fb-chats-as-video-files/"><u>[New] Journey Through Data Storage  Saving FB Chats as Video Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-identifying-what-sets-them-aside/"><u>Windows Terminal and PowerShell: Identifying What Sets Them Aside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win11-written-in-devhomes-script/"><u>Deciphering Win11' Written in DevHome's Script</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-steam-downloads-for-windows-users/"><u>Turbo-Charging Steam Downloads for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-brightness-managers-for-windows-multiscreen-professionals/"><u>The Ultimate List of Brightness Managers For Windows Multiscreen Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-pro-efficient-docx-to-pdf-conversion-made-simple/"><u>Win 11 Pro: Efficient DOCX to PDF Conversion Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-censored-windows-11-theme-options-with-registry/"><u>Unveiling Censored Windows 11 Theme Options with Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-access-to-hardware-spaces-via-win-1011-disks/"><u>Efficient Access to Hardware Spaces via Win 10/11 Disks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-short-form-video-rivals-can-likes-overtake-tiktoks-global-fanbase/"><u>2024 Approved  Short-Form Video Rivals  Can Likes Overtake TikTok’s Global Fanbase?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-mastering-video-editing-for-sony-camcorder-footage-2023-guide/"><u>Updated In 2024, Mastering Video Editing for Sony Camcorder Footage (2023 Guide)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-update-processes-windows-os-explored/"><u>Dissecting Update Processes: Windows OS Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-an-educational-ambiance-for-windows/"><u>Creating an Educational Ambiance for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-top-windows-platforms-for-ndsswitch-players/"><u>Cutting Edge: Top Windows Platforms for NDS/Switch Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-the-windows-11-ui-to-prompt-users-for-system-updates/"><u>Tailoring the Windows 11 UI to Prompt Users for System Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-library-no-sync-error-solution/"><u>Tackling Steam Library: No Sync Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-usability-through-windows-apps/"><u>Boosting macOS Usability Through Windows Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-craft-captivating-content-with-30-video-ideas/"><u>In 2024, Craft Captivating Content with 30 Video Ideas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-for-static-energy-controls-on-windows-11/"><u>Workarounds for Static Energy Controls on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-action-an-insight-into-sj-cam-s6/"><u>[New] Mastering Action  An Insight Into SJ-CAM S6</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-file-path-of-your-current-wallpaper/"><u>Discover the File Path of Your Current Wallpaper</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transforming-spaces-the-art-of-metaphysical-marketing/"><u>In 2024, Transforming Spaces  The Art of Metaphysical Marketing</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-win10s-favorite-video-grabber-tools/"><u>[Updated] In 2024, Win10's Favorite Video Grabber Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-activatingdeactivating-touch-typing-on-windows/"><u>Tips for Activating/Deactivating Touch Typing on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fix-the-too-many-different-cell-formats-error-in-excel-2003-by-stellar-guide/"><u>Fix the Too many different cell formats Error in Excel 2003?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-desktop-experience-with-winbubbles-best-practices/"><u>Tailor Your Desktop Experience with WinBubble's Best Practices</u></a></li>
</ul></div>
