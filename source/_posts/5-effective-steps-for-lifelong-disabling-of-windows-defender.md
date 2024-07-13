---
title: 5 Effective Steps for Lifelong Disabling of Windows Defender
date: 2024-07-12T17:32:29.445Z
updated: 2024-07-13T17:32:29.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Effective Steps for Lifelong Disabling of Windows Defender
excerpt: This Article Describes 5 Effective Steps for Lifelong Disabling of Windows Defender
keywords: Stop Windows Defender,Ending Defender Locks,Eliminate Antivirus Block,Remove Windows Security,Deactivate Defender Pro,Disable WinDefend,Turn Off Windows Protection
thumbnail: https://thmb.techidaily.com/964056d5a42fd554adb9e457ea6c862e5065495ad6b360af575e17501ef981e0.png
---

## 5 Effective Steps for Lifelong Disabling of Windows Defender

 Microsoft bundles an antivirus program with every copy of the Windows operating system. Microsoft Defender was released in 2006 and has since been integral to every new Windows operating system release. Surprisingly, it is good at identifying and isolating malware on your system and offering real-time protection.

 But have you ever tried disabling Microsoft Defender? Unless you install a third-party antivirus program, it continues to run and monitor your system. Even if you disable the real-time protection, it turns back on after some time. Don’t worry! We will discuss multiple methods to disable Microsoft Defender for good.

## Why Does Microsoft Make It Difficult to Disable Microsoft Defender?

 Microsoft Defender offers robust security against malware and has evolved over time. You can use it to keep your system safe from malware and do not need to spend on any third-party antivirus app. But Microsoft realizes that users can expose their system to attackers if they disable Microsoft Defender completely.

 So, as a fail-safe method, Microsoft Defender turns back on after some time, even if you disable it. In the older version of Windows, disabling real-time protection was enough, but now it takes a lot more to disable Microsoft Defender.

 But what if you want to install and use a third-party app that Microsoft Defender repeatedly flags as malicious? Or if you want to reduce the load on your system resources? Well, then you have to dive deep into Windows Security settings and disable real-time protection as well as other associated protection measures.

 This guide will teach you how to disable Microsoft Defender permanently. It will stay off until you undo the steps you perform in this guide. If you only want Microsoft Defender to turn off for a short amount of time, check out [how to turn off Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) for a more temporary solution.

## Disable Tamper Protection First

 Tamper Protection makes sure that no other apps can make changes to the Microsoft Defender settings on your computer. You don't need to [enable Tamper Protection](https://www.makeuseof.com/how-to-activate-tamper-protection-defender/) because it is active by default. If you want to completely disable Microsoft Defender (including real-time protection), you must disable Tamper Protection first. Here’s how to do it:

1. Press**Win + S** and type Windows Security. Click on the**Open** option to launch the app.
2. Click on the**Virus and threat protection** option on the home page.
3. Find the Virus and threat protection settings section and click on the**Manage settings** option.
4. Scroll down and click on the**Tamper Protection** toggle to disable it.  
![Disable Tamper Protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Disable-Tamper-Protection-2.jpg)
5. Close the Windows Security app.

## How to Disable Microsoft Defender in Windows 11

 We have already disabled Tamper Protection, so it won't interfere when you disable Microsoft Defender using GPE, Registry Editor, or any third-party tool. Here are the following methods that work flawlessly to disable the inbuilt security app on Windows 11:

### 1\. Disable Microsoft Defender Using Group Policy Editor

 Group Policy Editor is an excellent tool using which you can customize Windows settings with ease. However, it is only reserved for Windows Pro and Enterprise users. Check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you're using that version.

 Here’s how to disable Microsoft Defender using Group Policy Editor:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**gpedit.msc** in the text input area and press the Enter key.
2. Group Policy Editor will launch. Click on the**Computer Configuration** option on the home page.
3. Navigate to**Administrative Templates > Windows Components** .
4. Locate and click on the Microsoft Defender Antivirus option. Double-click on the**Turn-off Microsoft Defender Antivirus** policy to edit its settings.  
![Disable Windows Defender Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-policy-editor.jpg)
5. Select the**Enabled** radio button and click on the**Apply** button.
6. Lastly, click on the**OK** button and close the Group Policy Editor. Restart your system and open Windows Security.

### 2\. Disable Microsoft Defender Using Registry Editor

 Windows 11 Home users cannot use the Group Policy Editor. But you can tweak the registry to disable Microsoft Defender on your system. However, before making any changes, please create a registry backup and create a system restore point. That way, you can always undo any changes you make to the registry.

Repeat the following steps to disable Microsoft Defender:

1. Press**Win + S** to open Windows Search and type**Regedit** . Click on the**Run as administrator** button.
2. In the Registry Editor windows, go to the address bar and paste the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender
3. Right-click and select**New > DWORD (32-bit) Value** .
4. \`Click on the newly created DWORD (32-bit) Value and name it**DisableAntiSpyware** .
5. Double-click on the DisableAntiSpyware value and set the**Value Dat** a to**1** . Keep the**Base** as**Hexadecimal** .  
![Disable Windows Defender Using Group Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-registry-editor.jpg)
6. Close the Registry Editor and restart your system to apply changes.
7. Launch Windows Security and visit the Virus and threat protection section. You will see a “ **No active antivirus provider. Your device is vulnerable.** ” message.

### 3\. Disable Microsoft Defender Using CMD

 You can even use the Command Prompt app to disable Microsoft Defender. All you need to do is paste a registry modification command, and it will keep Microsoft’s default antivirus solution out of the picture. Here’s how to do it:

1. Press**Win + R** to launch the Run command box. Type**cmd** in the text input area and press**Ctrl + Shift + Enter** key to launch Command Prompt with admin privileges.
2. Now, type the following command and press the enter key:  
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
3. You will see a “**The operation completed successfully.** ” message after the successful execution of the above command.  
![Disable Windows Defender Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-cmd.jpg)
4. Type**exit** to close the Command Prompt window and restart your system.

### 4\. Disable Microsoft Defender Using Winaero Tweaker

 If you hate tweaking the registry or find running commands too complex, you can use a Windows customization program like Winaero Tweaker. It is a GUI application, so you will find it easier to search for various Windows settings and disable them in a few clicks.

Repeat the following steps:

1. Visit the [Winaero Tweaker download](https://winaero.com/download-winaero-tweaker/) page and download the installer file on your system.
2. Install Winaero Tweaker and right-click on the application and select the**Run as administrator** option.
3. Click on the search icon and type Defender. Click on the**Microsoft Defender \\ Disable Microsoft Defender** search result.  
![Disable Windows Defender Using Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-winaero-tweaker.jpg)
4. Then, click on the**Disable Microsoft Defender** checkbox. Scroll down and click on the**Reboot now** button.
5. Wait for your computer to restart. Microsoft Defender will be inactive on your system.

### 5\. Disable Microsoft Defender Using Ultimate Windows Tweaker

 Like Winaero Tweaker, the Ultimate Windows Tweaker is also a Windows customization app. You can easily enable and disable multiple Windows operating system settings and features which are otherwise very difficult to locate. Repeat the following steps:

1. Go to the [Ultimate Windows Tweaker download webpage](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the tool.
2. Extract all its files into a separate folder. Then select the tool and run it with administrator privileges.
3. Click on the**Search For Tweaks** option and type defender. Then click on the**Go** button and select the**Disable Microsoft Defender** option from the list.
4. Select the checkbox next to the**Disable Microsoft Defender** option and click on the**Apply Tweaks** button. You will see a Windows popup that will inform you whether the tweak was successful or not.  
![Disable Windows Defender Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-ultimate-windows-tweaker.jpg)
5. Finally, click on the**Close** button and restart your system.

## Permanently Disable Microsoft Defender on Windows 11

 Microsoft Defender is a pain to disable on your system because of multiple fail-safe methods built into Windows Security. So, disable Tamper Protection and then process with a method to disable Microsoft Defender. However, do not leave your system open to malware infestation, and use a third-party antivirus if you don’t like Defender.


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
<li><a href="https://win11-tips.techidaily.com/resolving-windows-specific-error-403-in-roblox-space/"><u>Resolving Windows-Specific Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-output-decrease-time-harness-power-of-flow-launcher/"><u>Increase Output, Decrease Time: Harness Power of Flow Launcher</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-u23-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of U23?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-task-manager-welcome-panel-in-windows-11/"><u>Redefine Task Manager Welcome Panel in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-best-intro-creator-software-for-pc-online-and-offline-options/"><u>Updated Best Intro Creator Software for PC Online and Offline Options</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/conquering-swedish-alphabet-with-sound-tips/"><u>Conquering Swedish Alphabet with Sound Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-low-latency-techniques-for-discord-on-windows/"><u>Mastering Low-Latency Techniques for Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-persistent-failures-of-cp-configurations-on-win11/"><u>Mending Persistent Failures of CP Configurations on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-reducing-excessive-background-load/"><u>Balancing Act: Reducing Excessive Background Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-and-folder-combination-in-windows-11/"><u>Mastering File & Folder Combination in Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-perfecting-screen-capture-teams-meetings-on-pctablet-for-2024/"><u>[Updated] Perfecting Screen Capture  Teams' Meetings on PC/Tablet for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-device-drivers-detected-on-windows-setup/"><u>Resolving 'No Device Drivers Detected' On Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reworking-records-6-windows-applications-for-date-revision/"><u>Reworking Records: 6 Windows Applications for Date Revision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341208077-pause-on-snipwise-discover-fixes-today-here/"><u>Pause on SnipWise? Discover Fixes Today, Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-restore-lock-screen-timeout-mechanism/"><u>Guides to Restore Lock Screen Timeout Mechanism</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ringtone-archive-iphone-2024-edition/"><u>[Updated] Ringtone Archive  IPhone 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/probing-windows-bsod-files-and-their-residues/"><u>Probing Windows BSOD Files & Their Residues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-restoring-a-dysfunctional-downloads-hub-in-windows/"><u>Guidelines for Restoring a Dysfunctional Downloads Hub in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-erase-personal-info-from-sign-in-window/"><u>Guide to Erase Personal Info From Sign-In Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-video-lag-in-vlc-media-player-on-windows/"><u>How to Fix Video Lag in VLC Media Player on Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-join-the-hilarity-tearfulness-spectacle-of-top-memes-on-ig-for-2024/"><u>[Updated] Join the Hilarity-Tearfulness Spectacle of Top Memes on IG for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-xiaomi-14-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Xiaomi 14 Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-11-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 11 & 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-when-and-why-should-you-post-on-instagram/"><u>[Updated] In 2024, When and Why Should You Post on Instagram?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-d3dx939dll-error-on-win11/"><u>Recovering D3DX9_39.dll Error on Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/social-media-live-platforms-facebook-vs-youtube-live-and-twitter-periscope/"><u>Social Media Live Platforms  FACEbook Vs. YOUTube Live & Twitter Periscope</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-ad-ds-printer-fails-in-win-1011/"><u>Resolving AD DS Printer Fails in Win 10/11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-rectify-facebook-video-playback-issues-chrome/"><u>2024 Approved  Rectify Facebook Video Playback Issues (Chrome)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-youtube-watch-on-chrome-windows/"><u>Accelerate Your YouTube Watch on Chrome Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-untamed-video-preservation-units/"><u>[Updated] In 2024, Untamed Video Preservation Units</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obscure-yet-outstanding-windows-11-themes/"><u>Obscure yet Outstanding Windows 11 Themes</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-13-mini-by-drfone-ios/"><u>iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 13 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/raising-the-bar-for-user-interface-in-w11-larger-icons/"><u>Raising the Bar for User Interface in W11: Larger Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-save-settings-restoration-in-windows-1011s-pubg/"><u>Mastering Save Settings Restoration in Windows 10/11'S PUBG</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-pc-printer-link-fixes/"><u>Mastering PC Printer Link Fixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-keyword-strategies-for-youtube-success/"><u>2024 Approved  Navigating Keyword Strategies for YouTube Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unsuccessful-nvidia-connect-attempts-in-windows-11/"><u>Resolving Unsuccessful Nvidia Connect Attempts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-impacts-of-ditching-windows-11s-taskbar-chatting-feature/"><u>Exploring Impacts of Ditching Windows 11'S Taskbar Chatting Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-0x80072efd-in-windows-devicesstore-apps/"><u>Overcoming Error 0X80072EFD in Windows Devices/Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-setting-powershell-policies/"><u>A Practical Approach to Setting PowerShell Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-image-id-0x80780119-on-windows-os/"><u>How To Repair Image ID: 0X80780119 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functioning-office-outlook-alerts/"><u>Restoring Functioning Office Outlook Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rendition-accelerating-prints-on-windows-system/"><u>Rapid Rendition: Accelerating Prints on Windows System</u></a></li>
<li><a href="https://driver-install.techidaily.com/lenovo-z50-70-upgrades-without-struggle/"><u>Lenovo Z50-70: Upgrades Without Struggle</u></a></li>
</ul></div>
