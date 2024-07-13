---
title: Abort Windows' Over-the-Top Contrast Mode
date: 2024-07-12T17:49:23.135Z
updated: 2024-07-13T17:49:23.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Abort Windows' Over-the-Top Contrast Mode
excerpt: This Article Describes Abort Windows' Over-the-Top Contrast Mode
keywords: Abort OTTOM,Windows Contrast,Over-the-Top Mode,Visual Contrast Windows,Abort High Contrast,Windows OTTMode,Contrast Enhancement
thumbnail: https://thmb.techidaily.com/dfca7fb0aa6438e6377385ff2f472549907a4325f08f8d8aadbe962a7502b81d.jpg
---

## Abort Windows' Over-the-Top Contrast Mode

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
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-hot-beats-exploring-viral-tiktok-rap-hits-today/"><u>2024 Approved  Hot Beats  Exploring Viral TikTok Rap Hits Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10plus-strategies-for-system-settings-entry/"><u>10+ Strategies for System Settings Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-fast-passes-to-the-control-settings-hub/"><u>11 Fast Passes to the Control Settings Hub</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-tiktok-creator-fund-how-to-join-it-and-make-money-filmora/"><u>In 2024, TikTok Creator Fund  How to Join It and Make Money | Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719203477260-how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-from-screens-to-gifs-the-art-of-converting-vimeo-footage/"><u>In 2024, From Screens to Gifs  The Art of Converting Vimeo Footage</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-top-20-adobe-premiere-titleintro-templates-free-download-for-2024/"><u>Updated Top 20 Adobe Premiere Title/Intro Templates Free Download for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719192555427-environment-variables-configuration/"><u>Environment Variables Configuration:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719233153106-eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-simplified-techniques-to-winrm-tool/"><u>10 Simplified Techniques to WinRM Tool</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-tips-for-restoring-fbm-functionality-on-desktop/"><u>10 Key Tips for Restoring FBM Functionality on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-simplify-network-connection-configurations-in-winos/"><u>10 Ways to Simplify Network Connection Configurations in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-compelling-narratives-with-b-cut-footage/"><u>2024 Approved  Crafting Compelling Narratives with B-Cut Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-straightforward-steps-to-engage-repair-tool/"><u>10 Straightforward Steps to Engage Repair Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-open-the-remote-desktop-connection-tool-in-windows-11/"><u>10 Ways to Open the Remote Desktop Connection Tool in Windows 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-15-best-booktok-books-recommendation-tiktok-books/"><u>[Updated] In 2024, 15 Best Booktok Books Recommendation [TikTok Books]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-command-routes-for-fast-diagnostic-center-entry/"><u>10 Command Routes for Fast Diagnostic Center Entry</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-motorola-moto-g73-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Motorola Moto G73 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719241162172-update-drivers-make-sure-your-graphics-card-drivers-are-up-to-date-for-optimal-performance/"><u>Update Drivers: Make Sure Your Graphics Card Drivers Are up to Date for Optimal Performance.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-strategies-for-managing-windows-connections-tool/"><u>10 Key Strategies for Managing Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
</ul></div>
