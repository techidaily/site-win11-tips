---
title: How To Rectify Failures From Windows Memory Tool
date: 2024-07-12T17:12:01.976Z
updated: 2024-07-13T17:12:01.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Rectify Failures From Windows Memory Tool
excerpt: This Article Describes How To Rectify Failures From Windows Memory Tool
keywords: Fixing Windows MemTool Errors,Windows Memory Correction Guide,Troubleshoot Windows RAM Issues,Remedy Windows Memory Problems,Resolve Windows Memory Tool Failures,Windows RAM Repair Steps,Correcting Memory Tools in Windows
thumbnail: https://thmb.techidaily.com/f1c57303ea622caa2e3702d3e2a77e00493f995e737fa90087cc4940fcb0139c.jpg
---

## How To Rectify Failures From Windows Memory Tool

 Using the Windows Memory Diagnostic tool, you can diagnose memory issues on your Windows computer. If there is a problem, it will return an error. One common Windows Memory Diagnostic error you may encounter is "Hardware problems were detected; contact manufacturer," followed by the "You have a memory problem" dialog.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.

## What Causes the Windows Memory Diagnostic Hardware Problems Were Detected Error?

 This error is often triggered after a blue screen of death (BSOD) or the system freezing issues. The reason for the error can vary and include faulty memory slots and memory sticks. It can also be a false positive due to a Windows OS glitch.

## 1\. Check for Overclocking Issues

 Incorrect overclocking can cause hardware issues. While faster RAM can help you achieve good performance, it is important to consider the hardware limitations before applying the tweaks.

 If you have overclocked your RAM, try to lower the frequencies to see if the error goes away. Do this until you find a safe frequency, or reset it to factory default settings.

 If you are unsure about the default memory frequencies, try to perform a BIOS reset. Load the BIOS default, which should reset the RAM frequencies to its factory default. Refer to your motherboard manufacturer manual for specific instructions.

## 2\. Run the Hardware Troubleshooter

 The built-in Windows hardware troubleshooter can scan for hardware-related issues and even try to perform a repair if possible. If you haven’t tried already, run the hardware troubleshooter using the Command Prompt to resolve the problem.

 Note that it is a legacy troubleshooter, and you may not find it in the Windows 11 version newer than 22H2\.

 To run the Windows Hardware Troubleshooter:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**. Click **Yes** if prompted by the User Account Control dialog.  
![run windows hardware troubleshooter command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-windows-hardware-troubleshooter-command-prompt.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`msdt.exe -id DeviceDiagnostic`
4. In the **Hardware and Devices** dialog, click **Next**. By default, the troubleshooter is set to apply any repairs available. To disable automatic repair, click **Advanced** and uncheck the **Apply repairs automatically** option.  
![hardware and devices troubleshooter windows 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-windows-1.jpg)
5. It will scan your computer for issues, which may take a few minutes. If an issue is detected, select to automatically apply the repair.
6. If the suggested problem is unrelated to memory, you can skip it to see the next problem. The troubleshooter will detect additional issues. If an issue is found, apply the fixes and check for any improvements.

## 3\. Remove and Reinsert Your Memory Sticks

 If you work with multiple memory sticks, remove all the sticks and wipe the card to remove dust and debris. Reboot the computer and check for any improvements.

 Still not working? Remove all but one stick and reboot your computer to see if the error is resolved. If not, repeat the procedure with all the sticks individually to determine and detect a faulty memory stick. If you find a faulty memory module, you can get a replacement or claim a warranty if available.

 If the issue persists, check your memory (RAM) slots for fault. Insert a memory stick into one of the slots and reboot your computer. If there is no error, test other slots and check if you can find a malfunctioning slot.

 If you determine a faulty RAM slot to have caused the issue, repairing it is tedious. First, RAM slots aren’t easily accessible like memory sticks. Second, to replace the slot, you’ll need to find a spare but compatible motherboard with working slots and then solder the connections onto your motherboard.

 If repairing the slots is not possible, your only option is a motherboard replacement. Depending on your system configuration, this can be an expensive solution. Or you can continue to use the system without utilizing the faulty memory slot, albeit with reduced performance.

## 4\. Test Your RAM with MemTest86+

 If the troubleshooter fails to detect any issue, you can perform a memory test using the MemTest86+ utility. It is an open-source memory testing tool to check for fails in your computer memory.

 MemTest86+ is a bootable utility and cannot be used from within Windows. To test your RAM with Memetst86+, you’ll need a USB drive. You can use the Memtest86+ Windows installer to create a bootable drive and boot from it.

 As of writing this article, Memtest86+ wasn’t compatible with Windows Secure Boot. So, you’ll need to disable Secure Boot to use the utility.

 To perform a memory test using Memtest86+:

1. Connect a USB flash drive to your computer. Take a backup of important data in the drive, as all the data will be deleted during the process.
2. Next, go to the [metest86+ page](https://www.memtest.org/) and download the latest version available.
3. Run the installer and select your USB drive. Make sure to select the format option.  
![memtest86 plus create bootable usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-create-bootable-usb-drive.jpg)
4. Click **Next** and wait for the installer to create a bootable drive.
5. Next, if you haven’t already, [disable Secure Boot on your Windows computer](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/).
6. Next, power off your computer. You may also need to clear your motherboard CMOS to reset your BIOS to factory default settings. You can also [reset BIOS to its default configuration](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) from the BIOS menu.  
![memtest86 plus memory integrity test in progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/memtest86-plus-memory-integrity-test-in-progress.png)
7. Next, plug the Memtest86+ bootable USB drive into your computer and turn it on.
8. Boot into the Boot Menu and select the bootable USB drive as the boot device. The hotkey key to enter the Boot Menu may vary depending on your computer manufacturer. You can press **F9** on an **HP** computer, **F12** on a **Dell** computer and so on to access the **Boot Menu**.
9. Memtest86+ will automatically start the memory integrity check. Let Memtest86+ complete at least 2 passes; the more, the better. Press the **Esc** key to stop the test if there are no errors after multiple passes.

 If an error is detected during testing, it is likely a case of faulty RAM and may need replacement. But to be on the safer side, ensure you test each RAM separately to find the odd one out.

 Not all the errors detected by the Memtest86+ are due to faulty hardware. Some errors may occur due to compatibility issues. Check your RAM module and the motherboard specifications to determine any compatibility issues. You can also test the RAM modules by inserting them into a different motherboard and see if it works.

## 5\. Perform a Repair Reinstall or Clean Install Windows

 If the Windows Memory Diagnostic tool continues to show the hardware problem was detected error, even after the Memtest86+ passed the test, check if the problem is due to issues with the Windows operating system.

 To fix critical issues with your Windows image, you can perform a [repair reinstall of Windows 11 without deleting apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/). If that does not work, perform a clean install. This will reinstall the operating system but delete all your apps and data from the computer. So, backup any data you need before attempting a clean install.

## Fixing the Memory Diagnostic Tool "Hardware Problem Detected" Error

 When an error is detected with your memory modules, the Windows Memory Diagnostic tool will show an error. While memory-related issues are often due to faulty hardware, make sure to run the device hardware troubleshooter to detect and resolve minor glitches.

 Alternatively, perform a memory integrity check using the Memtest86 tool. If the memory modules pass the Memtest86, you may need to perform a Windows OS clean install to fix issues with the Windows system files.

 This error can be a false positive. You can also confirm the same by using a third-party memory diagnostic tool. In case of a hardware issue, you may need to replace the memory stick or repair the memory slot, if possible.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/essential-insights-on-keeping-windows-11s-notifications-alive/"><u>Essential Insights on Keeping Windows 11'S Notifications Alive</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-a-compreomed-approach-to-filmmaking-mastering-movie-maker-windows-8-techniques/"><u>[Updated] A Compreomed Approach to Filmmaking  Mastering Movie Maker (Windows 8) Techniques</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-how-to-make-your-instagram-pop-with-sharing-gifs-in-4-easy-steps/"><u>[Updated] In 2024, How to Make Your Instagram Pop with Sharing GIFs in 4 Easy Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-gptclone-at-home-for-free-on-windows/"><u>Experience GPTClone at Home for FREE on Windows!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-erratic-windows-error-x8019/"><u>Overcoming Erratic Windows Error: X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invisible-hardware-on-microsoft-oses/"><u>Addressing Invisible Hardware on Microsoft OSes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exclusive-listing-of-best-5-sd-cards-for-gopro-hero-cameras-for-2024/"><u>Exclusive Listing of Best 5 SD Cards for GoPro HERO Cameras for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-samsung-galaxy-a54-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Samsung Galaxy A54 5G without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-recurring-edge-shortcuts-on-desktop/"><u>Eliminating Recurring Edge Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-battery-alert-strategies-for-win-users/"><u>Proactive Battery Alert Strategies for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-11s-default-touch-panel-settings-and-positioning/"><u>Restoring Windows 11'S Default Touch Panel Settings & Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-the-unchanged-status-of-windows-screensaver/"><u>Ensuring the Unchanged Status of Windows Screensaver</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-snap-and-save-professional-screen-recording-11-version-for-2024/"><u>[New] Snap & Save  Professional Screen Recording 11-Version for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/simplified-guide-to-transform-vimeo-video-into-mp3-for-2024/"><u>Simplified Guide to Transform Vimeo Video Into MP3 for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/5-must-have-linux-audio-capture-utilities-and-advanced-strategies-for-high-quality-recordings-for-2024/"><u>5 Must-Have Linux Audio Capture Utilities and Advanced Strategies for High-Quality Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-fixes-dealing-with-directdraw-glitches-in-win1011/"><u>Fast-Track Fixes: Dealing with DirectDraw Glitches in Win10/11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-top-3-strategies-for-capturing-real-time-sports-events-online/"><u>[New] In 2024, Top 3 Strategies for Capturing Real-Time Sports Events Online</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-proven-approaches-to-amass-elite-copyright-free-imagery/"><u>[Updated] Proven Approaches to Amass Elite, Copyright-Free Imagery</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-top-rated-apps-for-instagrams-vertical-igtv-content-enhancement/"><u>[Updated] Top-Rated Apps for Instagram's Vertical IGTV Content Enhancement</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-honor-magic-5-lite-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Honor Magic 5 Lite without App | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-dangers-of-keygen-malware-symptoms-and-removal-strategies/"><u>Exploring the Dangers of Keygen Malware: Symptoms & Removal Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/feature-context-menu-alert-for-windows-updates-in-win11plus11/"><u>Feature: Context Menu Alert for Windows Updates in Win11+11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-windows-11s-disguised-search-action/"><u>Initiating Windows 11'S Disguised Search Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-tackle-error-0x800700e1-on-windows-11-devices/"><u>Approaches to Tackle Error 0X800700E1 on Windows 11 Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/breathing-life-into-art-top-6-for-revolutionary-nftos/"><u>Breathing Life Into Art  Top 6 for Revolutionary NFTOs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-enhancement-streamlined-file-exploration-for-windows-11/"><u>Effortless Enhancement: Streamlined File Exploration for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-cpu-and-gpu-for-smooth-online-engagement/"><u>Balancing CPU and GPU for Smooth Online Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/determining-win11s-best-fit-home-vs-professional-setup/"><u>Determining Win11's Best Fit: Home Vs. Professional Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-stacking-windows-sticky-notes-high/"><u>Pro Tips: Stacking Windows Sticky Notes High</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-vr-clarity-achieved/"><u>In 2024, Ultimate VR Clarity Achieved</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-permission-errors-a-step-by-step-guide-on-windows/"><u>Resolving Permission Errors: A Step-by-Step Guide on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-detection-hurdles-for-controllers-on-steam/"><u>Overcoming Detection Hurdles for Controllers on Steam</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-graphics-to-emojis-turning-gifs-into-stickers-on-telegram-and-more-for-2024/"><u>From Graphics to Emojis  Turning GIFs Into Stickers on Telegram & More for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-quick-fix-for-active-directory-domain-services-printer-errors/"><u>Comprehensible Guide: Quick Fix for Active Directory Domain Services Printer Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/enthralling-narratives-discover-the-top-8-story-centric-universities/"><u>Enthralling Narratives  Discover the Top 8 Story-Centric Universities</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/soundscaping-stories-musical-elements-in-reels-for-2024/"><u>Soundscaping Stories  Musical Elements in Reels for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-seamless-video-communication-in-whatsapp-web-for-laptops-and-desktops/"><u>[New] 2024 Approved  Seamless Video Communication in WhatsApp Web for Laptops and Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delaying-the-end-extending-windows-11-shutdown-with-running-tasks/"><u>Delaying the End: Extending Windows 11 Shutdown with Running Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-update-your-amd-radeon-graphics-drivers-on-windows-11/"><u>How to Update Your AMD Radeon Graphics Drivers on Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/seeking-the-best-ps2-games-try-these-5-android-emulators-in-2024/"><u>Seeking the Best PS2 Games? Try These 5 Android Emulators, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-latency-strategies-to-fasten-windows-discord/"><u>Lowering Latency: Strategies to Fasten Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-office-error-0x80041015-in-ms-word-and-excel/"><u>Overcoming Office Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-windows-11-eradicate-delays-and-lags/"><u>Accelerating Windows 11: Eradicate Delays and Lags</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-google-pixel-8-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Google Pixel 8 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-restart-file-explorer-in-windows-11-and-11/"><u>4 Ways to Restart File Explorer in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-discord-installer-errors-on-windows-devices/"><u>Resolving Discord Installer Errors on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-task-tracking-in-project-management/"><u>Master the Art of Task Tracking in Project Management</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-science-of-choosing-music-for-movie-previews-for-2024/"><u>The Science of Choosing Music for Movie Previews for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/unbranded-video-merging-7-reliable-options-to-try-for-2024/"><u>Unbranded Video Merging 7 Reliable Options to Try for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-your-window-to-better-recording-best-apps-ranked-in-win11w10/"><u>[New] In 2024, Your Window to Better Recording  Best Apps Ranked in Win11/W10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-ultimate-guide-to-configuring-and-analyzing-facebooks-instream-ads/"><u>[Updated] In 2024, The Ultimate Guide to Configuring & Analyzing Facebook's Instream Ads</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ultimate-catcher-showdown/"><u>Ultimate Catcher Showdown</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-recordingrealm-expedition-unveiling-snapcastpro-2023/"><u>[Updated] 2024 Approved  RecordingRealm Expedition  Unveiling 'SnapCastPro' 2023</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-resize-photos-to-perfection-8-top-online-ratio-editors/"><u>New 2024 Approved Resize Photos to Perfection 8 Top Online Ratio Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-utorrent-not-installing-on-windows/"><u>How to Fix uTorrent Not Installing on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-windows-11-and-intel-unison-for-smooth-phone-integration/"><u>Leveraging Windows 11 & Intel Unison for Smooth Phone Integration</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-get-it-right-a-beginners-guide-to-iphone-screen-shots/"><u>[New] 2024 Approved  Get It Right  A Beginner's Guide to iPhone Screen Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-restoration-techniques-to-reactivate-virus-protection-in-windows/"><u>Quick Restoration Techniques to Reactivate Virus Protection in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/closed-folder-fixes-for-w11w10-double-click-malfunction/"><u>Closed Folder Fixes for W11/W10 Double-Click Malfunction</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/from-observer-to-participant-tips-for-guesting-on-tiktoks/"><u>From Observer to Participant  Tips for Guesting on TikToks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-synapse-functionality-with-razer-devices-on-windows/"><u>Restoring Synapse Functionality with Razer Devices on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-realme-11-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Realme 11 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/expert-tips-to-enhance-your-iphone-memo-making-skills-for-2024/"><u>Expert Tips to Enhance Your iPhone Memo-Making Skills for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/evaluating-windows-devices-essential-decisions-before-purchasing/"><u>Evaluating WIndows Devices: Essential Decisions Before Purchasing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-printmanagement-in-system-configuration/"><u>Addressing Absence of 'PrintManagement' In System Configuration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-expert-video-making-opt-for-studio-versus-beta-version/"><u>[New] 2024 Approved  Expert Video Making  Opt for Studio Versus Beta Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-address-sniptool-shortcut-problems/"><u>How to Swiftly Address SnipTool Shortcut Problems</u></a></li>
</ul></div>
