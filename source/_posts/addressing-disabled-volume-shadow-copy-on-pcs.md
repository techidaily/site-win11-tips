---
title: Addressing Disabled Volume Shadow Copy on PCs
date: 2024-07-12T17:53:01.545Z
updated: 2024-07-13T17:53:01.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
excerpt: This Article Describes Addressing Disabled Volume Shadow Copy on PCs
keywords: Accessible VSS (Volume),Enable VSS for Disabled,Restore Previous System State,VSS Compliance Check,PC Shadow Copy Issue,Configure VSS Services,Re-Enable Shadow Copies
thumbnail: https://thmb.techidaily.com/7dae447899f95c82a6cf6fb6c187f3946b55a92e5def14d160bc07a7e668b288.jpg
---

## Addressing Disabled Volume Shadow Copy on PCs

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-problems-effective-assistance-guide/"><u>Conquer Windows Problems: Effective Assistance Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-complex-archives-efficiently-handling-multiple-zips-in-one-go/"><u>Decoding Complex Archives: Efficiently Handling Multiple ZIPS in One Go</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-crossfade-magic-using-audacity-effectively/"><u>In 2024, Unlocking Crossfade Magic  Using Audacity Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-resolve-windows-11-search-tool-errors/"><u>Guides to Resolve Windows 11 Search Tool Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-scripts-the-winexe-transformation-tutorial/"><u>Elevate Your Scripts: The WinEXE Transformation Tutorial</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-discover-the-top-30-free-intro-creators-on-youtube/"><u>[Updated] In 2024, Discover the Top 30 Free Intro Creators on YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-an-owners-guide-to-playlist-permutations-in-yt/"><u>[Updated] In 2024, An Owner's Guide to Playlist Permutations in YT</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-wondering-how-to-add-custom-transitions-in-obs-studio-here-are-the-steps-to-add-stinger-transitions-to-obs-get-a-better-obs-alternative-to-add-trans/"><u>Updated Wondering How to Add Custom Transitions in OBS Studio? Here Are the Steps to Add Stinger Transitions to OBS. Get a Better OBS Alternative to Add Transitions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-essential-guide-to-sharing-art-on-public-platforms-responsibly/"><u>[New] The Essential Guide to Sharing Art on Public Platforms Responsibly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-this-file-cannot-be-previewed-error-in-outlook-for-windows/"><u>How to Fix the This File Cannot Be Previewed Error in Outlook for Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagrams-video-content-regulations-simplified-for-2024/"><u>Instagram's Video Content Regulations Simplified for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-11-and-11/"><u>How to Highlight the Mouse Cursor in Windows 11 & 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pushing-boundaries-top-virtual-reality-game-development-tools/"><u>[New] Pushing Boundaries  Top Virtual Reality Game Development Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-delete-email-from-windows-sign-in-screen/"><u>Efficient Ways to Delete Email From Windows Sign-In Screen</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-self-portraits-that-talk-100-words-to-define-you-on-insta/"><u>[Updated] Self-Portraits That Talk  100 Words to Define You on Insta</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-video-speed-changers-for-windows-and-mac-free-and-paid-for-2024/"><u>Best Video Speed Changers for Windows and Mac Free and Paid for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-capture-clarity-enjoy-convenience-with-our-top-5-recorder-recommendations/"><u>In 2024, Capture Clarity, Enjoy Convenience with Our Top 5 Recorder Recommendations</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/enhanced-clarity-for-all-windows/"><u>Enhanced Clarity for All Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rejuvenate-itunes-that-wont-respond-on-windows/"><u>How to Rejuvenate iTunes That Won't Respond on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-the-v22h2-update-dilemma-on-win11-os/"><u>Efficient Fixes for the V22H2 Update Dilemma on Win11 OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/unleashing-the-power-of-social-proof-tips-to-amplify-brand-visibility-for-2024/"><u>Unleashing the Power of Social Proof  Tips to Amplify Brand Visibility for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-samsung-galaxy-f14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-filmmakers-handbook-to-pairing-melodies-and-movement-in-video-editing-through-filmora/"><u>Updated In 2024, Filmmakers Handbook to Pairing Melodies and Movement in Video Editing Through Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-live-streaming-tools-head-to-head-obs-vs-fraps/"><u>In 2024, Live Streaming Tools Head to Head  OBS vs Fraps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-top-10-sound-extractors-to-extract-sound-from-video/"><u>Updated 2024 Approved Top 10 Sound Extractors to Extract Sound From Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-expertise-in-speech-transcription-with-googles-tools/"><u>2024 Approved  Expertise in Speech Transcription with Google's Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-v27-pro-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo V27 Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-infinix-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Infinix?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-essential-mac-6-video-grabber-apps/"><u>[New] In 2024, Essential Mac 6 Video Grabber Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reopen-a-closed-nvidia-control-panel-on-windows-11/"><u>How to Reopen a Closed Nvidia Control Panel on Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-time-saving-sonic-tweaks-the-easy-path-to-adjusting-audio-playback-rate/"><u>Updated In 2024, Time-Saving Sonic Tweaks The Easy Path to Adjusting Audio Playback Rate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-setup-ensure-your-pcs-microphone-and-webcam/"><u>Efficient Setup: Ensure Your PC's Microphone & Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-taming-high-cpu-use-in-modern-windows-host/"><u>Deciphering and Taming High CPU Use in Modern Windows Host</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-checks-when-windows-obs-studio-wont-launch/"><u>Essential Checks When Windows' OBS Studio Won't Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifttt-and-microsoft-to-dot-synergy-explained/"><u>IFTTT & Microsoft To-Dot Synergy Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-colored-display-in-windows-based-devices/"><u>How to Adjust Colored Display in Windows-Based Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-magic-automating-archive-creation-in-windows/"><u>Command Line Magic: Automating Archive Creation in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/leading-edge-asmr-audio-gear-without-breaking-the-bank-for-2024/"><u>Leading-Edge ASMR Audio Gear Without Breaking the Bank for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tools-for-shaping-windows-esd-files-into-iso/"><u>Essential Tools for Shaping Windows' ESD Files Into ISO</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-flip-video-clips-in-final-cut-pro-a-4-step-guide-for-beginners/"><u>In 2024, Flip Video Clips in Final Cut Pro A 4-Step Guide for Beginners</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-revealed-top-windows-11-gems-that-could-boost-your-user-performance-for-2024/"><u>[Updated] Revealed  Top Windows 11 Gems That Could Boost Your User Performance for 2024</u></a></li>
</ul></div>
