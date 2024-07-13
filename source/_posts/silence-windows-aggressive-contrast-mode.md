---
title: Silence Windows' Aggressive Contrast Mode
date: 2024-07-12T17:28:55.960Z
updated: 2024-07-13T17:28:55.960Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Silence Windows' Aggressive Contrast Mode
excerpt: This Article Describes Silence Windows' Aggressive Contrast Mode
keywords: Silent Contrast Windows,Aggressive Window Mode,High Contrast Windows,Silence Dark Mode,Contrasty Windows UI,Windows Dark Mode,Intense Window Contrast
thumbnail: https://thmb.techidaily.com/0f9975c7424be8ab80f0e3edfa04cf204d756fbbde35db8886dbe8cbc049b368.jpg
---

## Silence Windows' Aggressive Contrast Mode

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
<li><a href="https://win11-tips.techidaily.com/prioritize-protection-activating-tpm-and-secure-boot-before-w11-update/"><u>Prioritize Protection: Activating TPM and Secure Boot Before W11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-microsoft-store-functionality-in-windows-11/"><u>Restoring Microsoft Store Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-connection-between-windows-11-and-print-devices/"><u>Restoring Connection Between Windows 11 and Print Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-windows-11s-stealthy-taskbar-spotlight/"><u>Triggering Windows 11'S Stealthy Taskbar Spotlight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-lag-and-enhance-fps-in-roblox-win-edition/"><u>Minimize Lag & Enhance FPS in Roblox Win Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapidly-reach-word-definitions-on-your-system/"><u>Rapidly Reach Word Definitions on Your System</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-mastering-tempo-adjustments-aligning-audio-and-visuals-in-fcpx-for-2024/"><u>Updated Mastering Tempo Adjustments Aligning Audio and Visuals in FCPX for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-windows-11-admin-details-effectively/"><u>Revamp Your Windows 11 Admin Details Effectively</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/tracking-and-boosting-identifying-the-best-tools-for-instagram-analysis/"><u>Tracking and Boosting  Identifying the Best Tools for Instagram Analysis</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-vivo-x-flip-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Vivo X Flip to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-detectable-windows-commands/"><u>Strategies for Fixing Non-Detectable Windows Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-net-speeds-unlock-efficient-adapter-checking/"><u>Navigate Net Speeds: Unlock Efficient Adapter Checking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-functional-headphonesspeakers-in-windows/"><u>Resolving Non-Functional Headphones/Speakers in WINDOWS</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-foundation-to-finery-top-6-mc-home-designs-made-simple/"><u>[New] In 2024, Foundation to Finery  Top 6 MC Home Designs Made Simple</u></a></li>
<li><a href="https://video-capture.techidaily.com/capture-and-store-screen-content-free-in-2024/"><u>Capture and Store Screen Content, FREE, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purple-pandemonium-restore-your-pcs-color-calibration/"><u>Purple Pandemonium? Restore Your PC's Color Calibration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slick-techniques-for-masking-windows-11-task-view/"><u>Slick Techniques for Masking Windows 11 Task View</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-uncomplicate-your-workflow-5-free-online-tone-tools/"><u>New In 2024, Uncomplicate Your Workflow 5 Free Online Tone Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-emulated-titles-in-playnite/"><u>Seamless Integration of Emulated Titles in Playnite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-win-lsa-troubleshooting/"><u>Mastering the Art of Win LSA Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-1110-setup-with-rightful-permissions/"><u>Navigating Windows 11/10 Setup with Rightful Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-dns-configuration-process-on-windows-11/"><u>Navigating the DNS Configuration Process on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-get-back-to-creating-on-tiktok-after-app-hiccups/"><u>[Updated] In 2024, Get Back to Creating on TikTok After App Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-pc-identifying-the-7-most-suspicious-windows-processes/"><u>Protect Your PC: Identifying the 7 Most Suspicious Windows Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-failures-on-older-windows-versions/"><u>Troubleshooting Installer Failures on Older Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-power-for-photo-renewal-with-windows/"><u>Transformative Power for Photo Renewal with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-broken-system-defragmenter-execution/"><u>Rectifying Broken System Defragmenter Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-utorrent-performance-in-win-os/"><u>Optimizing uTorrent Performance in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-voice-commands-keyboard-shortcut-essentials/"><u>Mastering Windows 11'S Voice Commands: Keyboard Shortcut Essentials</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-unlock-vimeos-potential-cutting-edge-video-tools/"><u>[New] In 2024, Unlock Vimeo's Potential  Cutting Edge Video Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-proven-film-edits-that-enhance-visual-storytelling/"><u>[Updated] Proven Film Edits That Enhance Visual Storytelling</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-apple-video-editing-mastery-essential-software-you-need/"><u>Updated In 2024, Apple Video Editing Mastery Essential Software You Need</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/craft-your-contents-voyage-from-camera-to-instagram-tv/"><u>Craft Your Content's Voyage From Camera to Instagram TV</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-erase-unwanted-boards-from-old-youtube-videos-for-clearer-viewing/"><u>2024 Approved  Erase Unwanted Boards From Old YouTube Videos for Clearer Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-your-windows-overcome-geforce-experience-failures/"><u>Mend Your Windows: Overcome GeForce Experience Failures</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-y100a-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo Y100A to iPod | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/amplify-your-storytelling-seamlessly-insert-music-into-youtube-videos/"><u>Amplify Your Storytelling  Seamlessly Insert Music Into YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-archival-steganography-in-photos-windows-11/"><u>The Art of Archival Steganography in Photos (Windows 11)</u></a></li>
</ul></div>
