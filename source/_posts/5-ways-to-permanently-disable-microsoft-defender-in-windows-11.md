---
title: 5 Ways to Permanently Disable Microsoft Defender in Windows 11
date: 2024-07-12T17:48:01.739Z
updated: 2024-07-13T17:48:01.739Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Permanently Disable Microsoft Defender in Windows 11
excerpt: This Article Describes 5 Ways to Permanently Disable Microsoft Defender in Windows 11
keywords: Disable Defender Windows 11,Turn Off Windows Security,Stop Windows Defender Pro,Halt Microsoft Antivirus,Deactivate Windows Defender,Quiet Windows Safety,Inactive Windows Defender
thumbnail: https://thmb.techidaily.com/bb71352b27a9f0530f59cc2c36b568ff3e277e8a2296dc605c5a7f11777f7220.jpg
---

## 5 Ways to Permanently Disable Microsoft Defender in Windows 11

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
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-for-fine-tuning-windows-11-installation/"><u>The Ultimate Checklist for Fine-Tuning Windows 11 Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-restore-responsive-shortcut-keys-in-windows-11/"><u>Rectify: Restore Responsive Shortcut Keys in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-wirelessly-link-dualshock-3-and-win/"><u>Seamless Integration: Wirelessly Link DualShock 3 & Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rushing-past-stuck-warcraft-64-patches/"><u>Rushing Past Stuck Warcraft 6.4 Patches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-switch-the-best-windows-apps-for-ex-mac-users/"><u>Smooth Switch: The Best Windows Apps for Ex-Mac Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-samsung-galaxy-a14-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Samsung Galaxy A14 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-youtube-watch-on-chrome-windows/"><u>Accelerate Your YouTube Watch on Chrome Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-disable-usb-sleep-on-windows-11-pc/"><u>Stay Connected: Disable USB Sleep on Windows 11 PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-concept-to-screen-channel-yt-for-pioneering-filmmaking-techniques/"><u>[New] In 2024, From Concept to Screen  Channel YT for Pioneering Filmmaking Techniques</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-all-in-one-screen-capture-az-insights-and-alternatives/"><u>[New] 2024 Approved  All-in-One Screen Capture - AZ Insights & Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341208077-pause-on-snipwise-discover-fixes-today-here/"><u>Pause on SnipWise? Discover Fixes Today, Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-win11-ui-with-enlarged-icons/"><u>Transform Your Win11 UI with Enlarged Icons</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-a-comprehensive-guide-to-using-chrome-pip-across-devices/"><u>[Updated] In 2024, A Comprehensive Guide to Using Chrome PIP Across Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-old-files-enabling-the-autodelete-option-on-windows-11/"><u>Say Goodbye to Old Files: Enabling the Autodelete Option on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-video-privacy-made-easy-top-blur-apps-for-face-and-background/"><u>New 2024 Approved Video Privacy Made Easy Top Blur Apps for Face and Background</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-2024-what-is-ai-pixel-art-generator/"><u>In 2024, What Is AI Pixel Art Generator?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-top-5-reaction-video-creators-you-need-to-know/"><u>Updated Top 5 Reaction Video Creators You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-oppo-reno-11-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Oppo Reno 11 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/best-websites-to-erase-tiktok-watermarks-from-videos/"><u>Best Websites to Erase TikTok Watermarks From Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-avoiding-virtual-reality-nausea-tips-and-tricks/"><u>2024 Approved  Avoiding Virtual Reality Nausea  Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-deactivated-windows-email-rule-settings/"><u>Steps to Reactivate Deactivated Windows Email Rule Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unlocking-screen-pin-free-windows-projection/"><u>Stop Unlocking Screen: PIN-Free Windows Projection</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-transforming-vids-10-leading-apps-for-instagram-video-editing/"><u>2024 Approved  Transforming Vids  10 Leading Apps for Instagram Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-unreachable-network-paths/"><u>Overcoming Windows' Unreachable Network Paths</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-premiere-gear-optimal-panoramic-recorders/"><u>[New] 2024 Approved  Premiere Gear  Optimal Panoramic Recorders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rebuilding-windows-icons/"><u>Strategies for Rebuilding Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-trio-top-apps-making-pc-switch-easier/"><u>Transition Trio: Top Apps Making PC Switch Easier</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unveiling-top-10-gaming-talents-on-tiktok-for-2024/"><u>[Updated] Unveiling Top 10 Gaming Talents on TikTok for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://extra-resources.techidaily.com/perfect-frame-rate-selection-a-guide-to-best-slow-motion-filmmaking-techniques/"><u>Perfect Frame Rate Selection  A Guide to Best Slow Motion Filmmaking Techniques</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-3-best-effects-to-appear-on-camera-made-with-filmora-for-2024/"><u>Updated 3 Best Effects to Appear on Camera Made with Filmora for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-screen-savvy-starting-point-deciphering-display-standards/"><u>[Updated] 2024 Approved  Screen-Savvy Starting Point  Deciphering Display Standards</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-irecorder-demystified-a-deep-dive-into-features-for-2024/"><u>[New] IRecorder Demystified  A Deep Dive Into Features for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-beyond-headsets-ultimate-vr-gear-guide/"><u>2024 Approved  Beyond Headsets  Ultimate VR Gear Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-the-blue-screen-error-code-0x8007007e/"><u>Strategies to Resolve the Blue Screen Error: Code 0X8007007E</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/digital-cutting-edge-streamlined-strategies-for-editing-videos-on-vimeo/"><u>Digital Cutting Edge  Streamlined Strategies for Editing Videos on Vimeo</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revolutionary-fix-for-win10s-dual-nvidia-and-intel-graphics/"><u>Revolutionary Fix for Win10's Dual NVIDIA & Intel Graphics</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-x-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone X to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/from-adventure-to-audience-transforming-gopro-footage-with-social-media/"><u>From Adventure to Audience  Transforming Gopro Footage with Social Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-setting-powershell-policies/"><u>A Practical Approach to Setting PowerShell Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-stepping-stones-on-windows-11-top-8-to-skip/"><u>Safe Stepping Stones on Windows 11: Top 8 To Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-nokia-c02-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Nokia C02 Phone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-essential-8-android-group-calls-over-4-users/"><u>2024 Approved  Essential 8 Android Group Calls  Over 4 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-maximize-your-mobile-top-10-free-image-enhancement-tools-for-2024/"><u>[Updated] Maximize Your Mobile  Top 10 Free Image Enhancement Tools for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/meta-and-fb-data-protection-vr-headset-user-guide/"><u>Meta and FB Data Protection: VR Headset User Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-virtual-background-magic-a-streamers-guide-to-chroma-key/"><u>In 2024, Unveiling Virtual Background Magic  A Streamer's Guide to Chroma Key</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-do-you-want-to-know-how-to-freeze-video-check-this-article-and-find-the-easiest-way-to-freeze-frame-of-your-video-for-2024/"><u>New Do You Want to Know How to Freeze Video? Check This Article and Find the Easiest Way to Freeze Frame of Your Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://fox-links.techidaily.com/pros-in-mac-streaming-the-top-5-applications/"><u>Pros in Mac Streaming  The Top 5 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bringing-down-the-time-barrier-for-fastening-fb-video-content/"><u>Bringing Down the Time Barrier for Fastening FB Video Content</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-achieving-convenient-multi-screen-browsing-with-chrome-pip/"><u>[Updated] Achieving Convenient Multi-Screen Browsing With Chrome PIP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298672852-leveraging-local-links-to-global-drives-dropbox-and-googledrive-via-c/"><u>Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-access-premium-imagery-no-copyright-restrictions/"><u>In 2024, Access Premium Imagery, No Copyright Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
</ul></div>
