---
title: "Preventing Data Theft: Controlling Removable Storage on PCs"
date: 2024-07-12T16:37:49.248Z
updated: 2024-07-13T16:37:49.248Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
excerpt: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
keywords: Data Thievery Prevention,Secure Removable Storage,Control USB Devices,Protect Data Portals,Anti-Data Theft Tactics,Safe Media Handling,Limit External Drives
thumbnail: https://thmb.techidaily.com/c3ecdd732aca091f9e06be3caec567f3fcd17c056bf2dd14982465e8c7b5b6a1.jpg
---

## Preventing Data Theft: Controlling Removable Storage on PCs

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor
![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://smart-video-creator.techidaily.com/discover-the-top-hand-drawing-whiteboard-animation-creators-for-2024/"><u>Discover the Top Hand Drawing Whiteboard Animation Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cd-production-from-mp3-files-an-efficient-guide-to-using-imgburn-in-windows/"><u>Mastering Audio CD Production From MP3 Files: An Efficient Guide to Using ImgBurn in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-task-managers-dominance-over-desktop-applications/"><u>Mastering Task Manager's Dominance Over Desktop Applications</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-ultimate-image-ratio-calculator-tips-and-tricks-for-2024/"><u>The Ultimate Image Ratio Calculator Tips and Tricks for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-compact-guide-to-macs-screen-recording-shortcuts/"><u>2024 Approved  Compact Guide to Mac's Screen Recording Shortcuts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-the-game-changer-elevating-your-virtual-reality-film-quality/"><u>In 2024, The Game Changer  Elevating Your Virtual Reality Film Quality</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stronger-defense-through-longer-passcodes-windows-11-and-11-tips/"><u>Stronger Defense Through Longer Passcodes: Windows 11 and 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-custom-window-bg-in-winterm/"><u>Implementing Custom Window Bg in WinTerm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-unnecessary-system-updates-on-windows-11/"><u>Mute Unnecessary System Updates on Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-discover-the-best-video-blur-tools-for-iphone-and-android-users/"><u>Updated 2024 Approved Discover the Best Video Blur Tools for iPhone and Android Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/office-integration-a-concise-guide-to-windows-1011/"><u>Office Integration: A Concise Guide to Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-non-installing-java-in-windows-environment/"><u>Solutions for Non-Installing Java in Windows Environment</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-vivo-y56-5g-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Vivo Y56 5G PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070522-resolving-client-permissions-issue-on-windows-systems/"><u>Overcoming 0X80070522: Resolving Client Permissions Issue on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-your-pc-mastering-the-art-of-program-minimization/"><u>Speed Up Your PC: Mastering the Art of Program Minimization</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/complete-tutorial-sending-photos-from-apple-iphone-14-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>Complete Tutorial Sending Photos From Apple iPhone 14 to iPad | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-the-new-windows-taskbar-design/"><u>Maximizing the New Windows Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-correcting-rdp-fails-in-modern-windows-os/"><u>Preventing and Correcting RDP Fails in Modern Windows OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-spotlight-secrets-perfecting-vlogger-lights/"><u>[Updated] Spotlight Secrets  Perfecting Vlogger Lights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-windows-app-speed-revitalize-their-web-connection/"><u>Propel Window's App Speed: Revitalize Their Web Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-bandwidth-visualization-for-users/"><u>Real-Time Bandwidth Visualization for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-blocked-app-alert-on-windows-systems/"><u>Removing Blocked App Alert on Windows Systems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-inside-tiktoks-dynamic-world-filters-and-animation/"><u>In 2024, Inside TikTok's Dynamic World (Filters & Animation)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-transparent-taskbar-creation/"><u>Steps for Windows 11 Transparent Taskbar Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-a-non-functional-windows-download-folder/"><u>Methods to Reactivate a Non-Functional Windows Download Folder</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-ott-file-electronically-by-ldigisigner-sign-a-word-sign-a-word/"><u>How do i sign a .ott file electronically</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-cutting-edge-techniques-for-efficient-hp-notebook-screen-recording/"><u>In 2024, Cutting-Edge Techniques for Efficient HP Notebook Screen Recording</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-smooth-video-flow-from-your-photobooth-app/"><u>[New] Unlock Smooth Video Flow From Your Photobooth App</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-x-flip-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo X Flip by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructingdarkmodeonwindowsnotepad/"><u>InstructingDarkModeOnWindowsNotepad</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-best-mac-screen-grabbers-compiled-here-for-2024/"><u>[Updated] Best Mac Screen Grabbers Compiled Here for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-snapping-in-depth-guide-to-powertoy-window-layouts/"><u>Master the Art of Snapping: In-Depth Guide to PowerToy Window Layouts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-art-of-text-overlay-in-short-form-video-content-for-2024/"><u>The Art of Text Overlay in Short Form Video Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-directdraw-faults-on-windows-oses/"><u>Steps to Eliminate DirectDraw Faults on Windows OSes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/step-by-step-guide-to-protected-youtube-to-mp3-conversions-for-2024/"><u>Step-by-Step Guide to Protected YouTube-to-MP3 Conversions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-directdraw-a-focused-guide-for-win11-enthusiasts/"><u>Troubleshooting DirectDraw: A Focused Guide for Win11 Enthusiasts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-app-engagement-in-modern-window-os/"><u>Speedy App Engagement in Modern Window OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-edge-always-active-on-windows-11-guide/"><u>Is Edge Always Active on Windows 11? Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-harnessing-the-power-of-hashtags-to-amplify-your-igtv-content/"><u>[New] In 2024, Harnessing the Power of Hashtags to Amplify Your IGTV Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-dxgi-error-messages-windows-1011/"><u>Navigating Through DXGI Error Messages (Windows 10/11)</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-from-apple-iphone-11-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working From Apple iPhone 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-ms-resource-and-apperror/"><u>Solving Windows 11'S Ms-Resource and AppError</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-clearing-admin-not-allowed-message-in-os/"><u>Strategies for Clearing Admin Not Allowed Message in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-old-school-gaming-adventures-integrate-trophies-through-retroarch/"><u>Revitalize Your Old-School Gaming Adventures - Integrate Trophies Through Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-a-toolbar-update-check-feature-into-windows-11plus11-interface/"><u>Integrating a Toolbar Update Check Feature Into Windows 11+11 Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-updater-error-0xca00a009/"><u>Repairing Windows Updater Error #0xCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-proxy-configurations-on-windows-11/"><u>Mastering the Art of Proxy Configurations on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-lava-yuva-3-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Lava Yuva 3 without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-fixing-nvidia-cp-error-in-ws1110/"><u>Methodical Approach: Fixing Nvidia CP Error in WS11/10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-virtual-vision-creation-shaping-a-humorous-self-portrait/"><u>[New] 2024 Approved  Virtual Vision Creation  Shaping a Humorous Self-Portrait</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-minimizing-cpu-load-on-computers/"><u>Mastery of Minimizing CPU Load on Computers</u></a></li>
</ul></div>
