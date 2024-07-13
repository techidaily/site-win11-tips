---
title: Adjusting Setup Service via Command-Line Utilities
date: 2024-07-12T16:40:25.082Z
updated: 2024-07-13T16:40:25.082Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Setup Service via Command-Line Utilities
excerpt: This Article Describes Adjusting Setup Service via Command-Line Utilities
keywords: CLI Setup Adjustment,Command Line Services,Utility Commands Guide,Service Configuration CLI,Command-Line Configuring,Web Admin Tools,Online Setup Controls
thumbnail: https://thmb.techidaily.com/d20682484ee39b27689e93ff94b9b7638592055fcb925a693073d87e930189fb.jpg
---

## Adjusting Setup Service via Command-Line Utilities

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first [activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to [launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-essential-tips-for-stepping-away-from-a-discord-chat-room/"><u>[Updated] In 2024, Essential Tips for Stepping Away From a Discord Chat Room</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-detailed-steps-to-rotate-videos-in-blender/"><u>In 2024, Detailed Steps to Rotate Videos in Blender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-missing-optional-windows-extras-in-7-steps/"><u>Troubleshooting Missing Optional Windows Extras in 7 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-data-protection-top-7-win-apps-148-chars/"><u>Enhancing Data Protection: Top 7 Win Apps (148 Chars)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/simplifying-cross-platform-sharing-instagram-and-facebook-integration-for-2024/"><u>Simplifying Cross-Platform Sharing  Instagram & Facebook Integration for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-picturing-laughter-building-memes-with-text-tool/"><u>2024 Approved  Picturing Laughter  Building Memes with Text Tool</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-from-apple-iphone-xr-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock from Apple iPhone XR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-guide-mkv-to-mp4-conversion-process/"><u>Windows Guide: MKV to MP4 Conversion Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-the-dead-zone-fix-for-stranded-xbox-on-windows-11/"><u>Dodging the Dead Zone: Fix for Stranded Xbox on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-11-editions-a-compre-point-by-point-analysis/"><u>Deciphering Windows 11 Editions: A Compre Point-by-Point Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-platform-android-entertainment-in-windows-11-via-play-services/"><u>Cross-Platform Android Entertainment in Windows 11 via Play Services</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-prime-desktopmobile-communication-alternatives-to-zoom/"><u>[New] In 2024, Prime Desktop/Mobile Communication Alternatives to Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ating-through-the-world-of-cosmetics-youtubes-top-artists-for-2024/"><u>Navigating Through the World of Cosmetics  YouTube's Top Artists for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-epic-journey-through-memory-lane-advanced-methods-for-capturing-your-sims-digital-adventures-for-2024/"><u>The Epic Journey Through Memory Lane  Advanced Methods for Capturing Your Sims' Digital Adventures for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/5-solutions-for-huawei-nova-y91-unlock-without-password-by-drfone-android/"><u>5 Solutions For Huawei Nova Y91 Unlock Without Password</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-navigating-iphone-audio-modification-first-time-users-introduction-to-voice-changer-plus/"><u>Updated Navigating iPhone Audio Modification First-Time Users Introduction to Voice Changer Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-xps-error-0x80300024-issue/"><u>Addressing Windows XP's Error 0X80300024 Issue</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-obs-vs-twitch-hub-best-platform-debate/"><u>2024 Approved  OBS Vs. Twitch Hub  Best Platform Debate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disguised-delayers-innocuous-apps-hindering-pc-speed/"><u>Disguised Delayers: Innocuous Apps Hindering PC Speed</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-quick-start-guide-easy-steps-for-effective-video-calling-on-zoom/"><u>In 2024, Quick Start Guide  Easy Steps for Effective Video Calling on Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-taskbar-inactivity-in-windows-os/"><u>Addressing Taskbar Inactivity in Windows OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-enhance-your-reel-with-rhythms-instagrams-music-guide/"><u>[Updated] In 2024, Enhance Your Reel with Rhythms  Instagram's Music Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-pixlr-essentials-10-pro-tips-to-transform-your-images/"><u>[New] In 2024, Pixlr Essentials  10 Pro Tips to Transform Your Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-fixes-for-non-displaying-storepages-on-win-10/"><u>Unveiling Fixes for Non-Displaying Storepages on Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-uninstallreinstall-issues-for-windows-store/"><u>Fix Uninstall/Reinstall Issues for Windows Store</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-mastering-pip-a-step-by-step-guide-to-creating-picture-in-picture-effects-in-final-cut-pro/"><u>Updated Mastering PiP A Step-by-Step Guide to Creating Picture-in-Picture Effects in Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-note-clarity-obsidian-canvas-methods/"><u>Enhancing Note Clarity: Obsidian Canvas Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-obsolete-to-optimal-atlasos-makeover/"><u>From Obsolete to Optimal: AtlasOS Makeover</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366220535-effortless-assistance-for-your-common-windows-complaints/"><u>Effortless Assistance for Your Common Windows Complaints!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-top-video-editing-software-with-ai-powered-reframing/"><u>2024 Approved Top Video Editing Software with AI-Powered Reframing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/website-standoffs-on-pc-seven-saving-strategies-for-cross-browser-issues/"><u>Website Standoffs on PC: Seven Saving Strategies for Cross-Browser Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-setup-windows-11-arm-from-an-iso-file-stepwise-approach/"><u>Efficiently Setup Windows 11 ARM From an ISO File Stepwise Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-game-launch-freezes-steps-to-mend-windows-11-steam/"><u>Troubleshooting Game Launch Freezes: Steps to Mend Windows 11 Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/astra-pilot-disappearance-steps-for-windows-11-users/"><u>Astra Pilot Disappearance? Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-failed-file-creation-on-11-camera-app/"><u>Bypassing Failed File Creation on 11 Camera App</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-discovering-the-top-screen-grabber-software-win11/"><u>2024 Approved  Discovering the Top Screen Grabber Software Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-efficiency-mastering-ms-projectenaside-from-what-ive-provided-please-give-me-5-new-book-titles-related-to-ai-in-healthcare/"><u>Unlock Efficiency: Mastering MS Project'enaside From What I've Provided, Please Give Me 5 New Book Titles Related to AI in Healthcare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-how-clockdate-shows-in-window-11/"><u>Customizing How Clock/Date Shows in Window 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-mini-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 mini To Other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-avoiding-career-pitfalls-in-graphic-artistry/"><u>In 2024, Avoiding Career Pitfalls in Graphic Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-through-the-haze-9-tips-for-crystal-clear-pc-monitors/"><u>Cutting Through the Haze: 9 Tips for Crystal-Clear PC Monitors</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-zooms-best-audio-practices-2-simple-steps-to-enhanced-quality/"><u>2024 Approved  Zoom's Best Audio Practices  2 Simple Steps to Enhanced Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-7-prime-free-password-generators-for-pcs/"><u>Explore 7 Prime Free Password Generators for PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-valorants-audio-sync-on-microsoft-devices/"><u>Correcting Valorant's Audio Sync on Microsoft Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-power-of-csgo-in-w11/"><u>Unlocking the Power of CS:GO in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-disk-distinctions-c-and-d/"><u>A Guide to Understanding Disk Distinctions (C & D)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-browser-copy-paste-woes-in-windows/"><u>Essential Fixes for Browser Copy-Paste Woes in Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-the-anatomy-of-apple-m1-chip-redefining-tech/"><u>[New] 2024 Approved  The Anatomy of Apple M1 Chip, Redefining Tech</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-comprehensive-tutorial-adding-timer-functionality-to-obs/"><u>[Updated] Comprehensive Tutorial  Adding Timer Functionality to OBS</u></a></li>
<li><a href="https://change-location.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-vivo-y36i-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-blaze-2-5g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Blaze 2 5G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-resolving-active-directory-printer-issues-on-win11/"><u>Tips & Tricks for Resolving Active Directory Printer Issues on Win11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-instantly-engage-in-video-talks-using-whatsapp-web-from-your-laptop-for-2024/"><u>[New] Instantly Engage in Video Talks Using WhatsApp Web From Your Laptop for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/exclusive-leaderboard-luminary-youtube-videographers-guide/"><u>Exclusive Leaderboard Luminary  YouTube Videographer's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/years-best-sale-612-for-eternal-windows-10-life/"><u>Year's Best Sale: $6.12 for Eternal Windows 10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x0000011b-operation-failure-on-windows-11/"><u>Correcting 0X0000011B Operation Failure on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-mandatory-elements-alert-on-windows-10and11-os/"><u>Counteracting Mandatory Elements Alert on Windows 10&11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-nvidia-geforce-connection-hurdle-in-win-11/"><u>Bypassing the Nvidia GeForce Connection Hurdle in Win 11</u></a></li>
</ul></div>
