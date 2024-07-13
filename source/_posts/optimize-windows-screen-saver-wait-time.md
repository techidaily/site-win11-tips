---
title: Optimize Windows Screen Saver Wait Time
date: 2024-07-12T17:30:03.874Z
updated: 2024-07-13T17:30:03.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize Windows Screen Saver Wait Time
excerpt: This Article Describes Optimize Windows Screen Saver Wait Time
keywords: Optimal Wait Saver,Short Saver Delay,Minimize Saver Time,Quick Saver Fix,Reduce Saver Halt,Efficient Saver Timer,Accelerate Screen Pause
thumbnail: https://thmb.techidaily.com/8a309f6aebab825a6cd0baff1d0b8550d45fadce34f31fb21e5a5f2109ae3299.jpg
---

## Optimize Windows Screen Saver Wait Time

 The Windows lock screen usually displays images when you power on your device or wake it from sleep mode. By default, the lock screen will only appear for about a minute, and then your screen will go blank.

 Meanwhile, the screen saver is an image or animation that appears when your PC has been inactive for a while. Just like the lock screen, the screen saver will also appear for about one minute.

 Wondering how you can display the lock screen or screen saver for longer?

 This article will show you the various ways to change the Windows lock screen and screen saver timeout settings.

## 1\. How to Change the Lock Screen Timeout Settings

 Let’s first take a look at how you can configure the Windows 10 lock screen timeout settings.

### Use the Windows System Settings

 The Windows system settings always come in handy in various situations. Let’s check out how you can use them to change the Windows 10 screen lock timeout settings:

1. Press **Win + I** to open the system settings.
2. Select the **Personalization** option from the menu items.
3. Click the **Lock screen** option on the left-hand side pane.
4. Scroll down on the right-hand side and select the **Screen timeout settings** option.
5. Click the **On battery power** drop-down menu on the right-hand side pane and select your preferred option.

![Using Windows System Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-Windows-System-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 Apply the same settings for the **When plugged** in option on the right-hand side pane. From there, close the **system settings** and restart your device to save these changes.

### Use the Edit Plan Settings (via the Control Panel)

 The Control Panel is a reliable Windows tool that helps you configure various system settings. We’ll show you how you can use it to configure the screen saver timeout settings.

 In this case, we’ll use the Control Panel to navigate to the Edit Plan settings.

 Here are the steps you need to follow:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**.
2. Click the **View by** drop-down menu and select **Small icons**.
3. Select **Power Options** from the menu items.
4. Click the **Change plan settings** option on the right-hand side.
5. Locate the **Turn off the display** option. From there, select your preferred options on the **On battery** and **When plugged in** drop-down menus.
6. Finally, click the **Save changes** button.

![Using the Edit Plan Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Edit-Plan-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

### Use the Advanced Power Options (via the Control Panel)

 You can also use the Control Panel's advanced power settings to configure the lock screen timeout settings.

 Simply follow these steps:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Control Panel** and then press **OK**.
3. Select **Power Options** from the menu items.
4. Click **Change plan settings**. From there, select the **Change advanced power settings** option on the next screen.
5. Scroll down and click the **Display** option. Next, click the **Turn off display after** option.
6. Select the **On battery** option, and then configure the lock screen timeout settings using the **arrow buttons**. From there, apply the same settings for the **Plugged in** option.

![Using the Advanced Power Options to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Advanced-Power-Options-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 When you're done, click **Apply** and then click **OK**. Finally, close the **Control Panel** and then restart your device to save these changes.

### Use the Command Prompt

 The Command Prompt is a reliable tool that can help you [troubleshoot various Windows system issues](https://www.makeuseof.com/how-to-troubleshoot-faulty-windows-pc/). Interestingly, this tool can also help you configure the settings on your device.

 Here’s how to configure the Windows lock screen timeout settings [using the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/):

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Next, type the following commands—one at a time—and press **Enter** in each case:

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOIDLE 60

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 60

 The "**60**" in the command indicates the duration (seconds) in which the lock screen will be displayed. If you want to increase the lock screen duration, apply the previous steps and change "**60**" to a different value of your choice.

 When you finish, type the following command and press **Enter**:

powercfg.exe /SETACTIVE SCHEME_CURRENT

 Finally, restart your PC to save these changes.

## How to Change the Screen Saver Timeout Settings

 Now, let's explore how you can change the screen saver timeout settings.

### Use the System Settings
![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Here's how to change the duration of the screen saver using the system settings:

1. Press **Win + I** to open the system settings.
2. Type **screen saver** in the Settings search bar and select the **Change screen saver** option.

 Bear in mind that you can change the screen saver timeout settings only if the screen saver is enabled. If the screen saver is currently disabled, click the **Screen saver** drop-down menu and select your preferred image.

![Enabling the screensaver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Enabling-the-screensaver-option.jpg)

 From there, follow these steps to configure the screen saver timeout settings:

1. Navigate to the **Wait** option on the Screen Saver Settings window.
2. Click the **arrow buttons** to select the screen saver duration (in minutes).

![Using the System Settings to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-System-Settings-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 Finally, press **Apply** and then press **OK** to save these changes.

### Use the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is an incredible tool that makes it easy for you to configure various system settings. Now, here's how you can use this tool to configure the screen saver timeout settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates> Control Panel > Personalization**.
4. Double-click the **Screen saver timeout** option on the right-hand side.

![Using the LGPE to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-LGPE-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 In the next window, select the **Enabled** option. From there, use the **arrow buttons** next to the **Seconds** box to select the duration of the screen saver.

 Press **Apply**, press **OK**, and then close the **LGPE**. Finally, restart your device to save these changes.

 If you want to disable the screen saver settings, here are the steps you need to follow:

1. Navigate to the **Personalization** option on the LGPE as per the previous steps.
2. Double-click the **Screen saver timeout** option and select either the **Disabled** or the **Not Configured** option.
3. Finally, press **Apply**, press **OK**, and then close the **LGPE**.

 Still looking for more tips on how to increase screen time on your laptop? We've got one more solution for you!

### Use the Registry Editor
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor can help you tweak the screen-saver timeout settings with ease. But it's quite a sensitive tool, so you should consider [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed.

 Now, here's how to configure the screen-saver timeout settings with the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **OK** to open the Registry Editor.
3. Copy-paste the following command into the address bar:

HKEY_USERS\.DEFAULT\Control Panel\Desktop

 Locate the **ScreenSaveTimeOut** option on the right-hand side.

 If the key is missing, right-click on a blank space on the right and select **New > DWORD (32-bit) Value**. From there, rename the value as **ScreenSaveTimeOut** and press **Enter**.

 Next, double-click the **ScreenSaveTimeOut** value.

![Clicking the "ScreenSaveTimeOut" value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-screensavetimeout-value.jpg)

 Now, type the screen saver timeout duration (in seconds) in the **Value data** box. The default option is usually **900** seconds (15 minutes), but you can enter your desired value. Finally, click **OK** and then restart your device to save these changes.

## Tweak Your Lock Screen Timeout Settings Without a Hassle

 Wondering how to increase laptop screen time? Or do you want to lock your PC and ensure that it doesn’t fully go into sleep mode?

 Try increasing the lock screen and screen saver timeout settings using the solutions we’ve covered. From there, you can explore other cool things, such as how to automatically lock your Windows 11 PC when you’re away.


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
<li><a href="https://twitter-clips.techidaily.com/twitters-videography-policy-including-aspect-ratios-is-crucial/"><u>Twitter's Videography Policy  Including Aspect Ratios Is Crucial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-to-wipe-login-page-contacts/"><u>Guiding You to Wipe Login Page Contacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-law-filters-into-your-windows-workflows/"><u>Integrating LAW Filters Into Your Windows Workflows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/game-explorer-3-ways-to-access-directories-on-windows-pcs/"><u>Game Explorer: 3 Ways to Access Directories on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-note-clarity-obsidian-canvas-methods/"><u>Enhancing Note Clarity: Obsidian Canvas Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obsolete-to-optimal-atlasos-makeover/"><u>From Obsolete to Optimal: AtlasOS Makeover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-into-windows-11s-silent-camera-alert-system/"><u>Hacking Into Windows 11'S Silent Camera Alert System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-like-a-pro/"><u>Navigating Windows Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-hurdles-restoring-file-transfer-on-win11/"><u>Navigating Network Hurdles: Restoring File Transfer on WIN11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-setting-up-a-taskbar-on-windows-11-tablets/"><u>Guide to Setting Up a Taskbar on Windows 11 Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-track-of-windows-shots-folders/"><u>Keeping Track of Windows Shots' Folders</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-amazons-all-star-series-most-retweeted-and-watched-originals/"><u>2024 Approved  Amazon's All-Star Series  Most Retweeted & Watched Originals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-solving-win-os-device-errors/"><u>Navigating and Solving Win OS Device Errors</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/is-your-apple-iphone-15-plus-in-security-lockout-proper-ways-to-unlock-by-drfone-ios/"><u>Is Your Apple iPhone 15 Plus in Security Lockout? Proper Ways To Unlock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-windows-open-eliminate-automatic-lock/"><u>Keep Windows Open: Eliminate Automatic Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-art-of-epic-save-preservation/"><u>Navigating the Art of Epic Save Preservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-video-from-mkv-to-mp4-on-windows-pcs/"><u>Optimizing Video: From MKV to MP4 on Windows PCs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-twitch-live-to-youtube-watchability-a-comprehensive-tutorial/"><u>[Updated] In 2024, From Twitch Live to YouTube Watchability  A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-advanced-tech-webcams-the-ultimate-guide-to-the-top-5-with-sound/"><u>[Updated] Advanced Tech Webcams - The Ultimate Guide to the Top 5 With Sound</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-essential-guide-to-screencasting-with-google-meet/"><u>[New] 2024 Approved  Essential Guide to Screencasting with Google Meet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-winerror-installation-fault-0xc004f050/"><u>How to Resolve WinError: Installation Fault #0XC004F050</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-hourly-high-stakes-views-yts-1-to-10-rankings/"><u>[New] In 2024, Hourly High-Stakes Views  YT's #1 to #10 Rankings</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-minitool-movie-maker-is-it-worth-it-plus-top-alternatives/"><u>2024 Approved Minitool Movie Maker Is It Worth It? Plus Top Alternatives</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-itel-p55-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Itel P55 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-device-access-after-encountering-error-22-in-windows-11/"><u>How to Unlock Device Access After Encountering Error 22 in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-unveiling-tiktoks-anime-essence-a-treasury-of-dancing-audio-visuals-and-memes/"><u>[New] 2024 Approved  Unveiling TikTok’s Anime Essence  A Treasury of Dancing, Audio-Visuals & Memes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-screen-unresponsive-error-on-windows-11/"><u>Overcoming 'Screen Unresponsive' Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
</ul></div>
