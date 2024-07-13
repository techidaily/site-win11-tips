---
title: Steps to Tackle Windows Security Faults Effectively
date: 2024-07-12T16:55:44.435Z
updated: 2024-07-13T16:55:44.435Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Tackle Windows Security Faults Effectively
excerpt: This Article Describes Steps to Tackle Windows Security Faults Effectively
keywords: Windows Security Fixes,Secure Windows Update,Fix Windows Vulnerabilities,Enhance Windows Safety,Stronger Windows Defense,Improve Windows Protection,Effective Windows Hardening
thumbnail: https://thmb.techidaily.com/5eb42b490725ed54872c9c11b47aee171fe6d79191204bcd93add24c922b6881.jpg
---

## Steps to Tackle Windows Security Faults Effectively

 Windows Security incorporates the Microsoft Defender antivirus utility. However, some users can’t select to run Microsoft Defender scans because of an error message that says: “Unexpected error. Sorry, we ran into a problem.” That “Unexpected error” message pops up for some users when they select the**Virus & threat protection** tab in Windows Security.

 Consequently, the**Virus and threat protection tab** is inaccessible. That error means there’s an issue with the Windows antivirus tool. This is how you can resolve the “Unexpected error” issue.

## 1\. Check for New Windows Updates

 First, check for and install available Windows patch updates. Microsoft releases many patches to update Microsoft Defender. So, a patch update could feasibly resolve a Windows Security bug. Our [guide to manually updating Windows](https://www.makeuseof.com/update-windows-manually/#:~:text=Press%20the%20Win%20%2B%20I%20hotkeys,the%20Check%20for%20updates%20button.) tells you how to check for and install new updates in Settings.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 2\. Run System File and Image Scans

 System file issues might be causing the “Unexpected error” on your PC. To check if that’s the case, run a System File Checker scan within the Command Prompt. Such a scan will repair the corrupted system files detected. Our guide on [utilizing the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to scan system files with that utility.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-sfc-scannow-command.jpg)

 It’s also recommended to run a Deployment Image Servicing and Management scan, which can resolve Windows system image issues. The System File Checker tool doesn’t work when there are issues with the system image. So, try executing this command before the SFC scan as well:

`Dism /Online /Cleanup-Image /RestoreHealth`

## 3\. Remove Third-Party Antivirus Software

 Do you have an alternative third-party antivirus tool installed on your PC? If so, then there’s a possibility that antivirus software is causing the issue by conflicting with Microsoft Defender. At least try turning off the third-party AV utility by right-clicking the system tray icon for the app and selecting a disable context menu setting.

 If disabling the third-party antivirus software works, you have two options. You can re-enable that antivirus software and utilize the alternative antivirus scanner it provides. Or you can completely uninstall the third-party antivirus software if you prefer Microsoft Defender. Our guide to removing Windows software includes numerous methods for uninstalling programs.

## 4\. Modify the Windows Defender Registry Key

 This registry tweak for modifying a**DisableAntiSpyware** DWORD is one of the most widely confirmed fixes for the “Unexpected error” issue. So, maybe this could the “Unexpected error” solution you’re looking for as well. To apply this potential fix, edit the registry as follows:

1. Open Run, input**regedit** , and click**OK** .
2. Erase the current registry path and input this registry key location inside the address box:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
3. You can skip through to step five if the Windows Defender key includes a**DisableAntiSpyware** DWORD. However, users who can’t see that DWORD will need to right-click the**Windows Defender** key and select**New** \>**DWORD** .  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-new-key-options.jpg)
4. Type**DisableAntiSpyware** in the DWORD’s text box.
5. Double-click the**DisableAntiSpyware** DWORD to access its**Value** box.
6. Input**0** in the data box if that’s not the current value set.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-edit-dword-window.jpg)
7. Select**OK** to confirm the value for the DWORD.

## 5\. Reset the Windows Security App

 Resetting Windows Security is worth trying whenever that app isn’t working right. In this case, something is up with the antivirus component of that app. You can reset that app within Settings or by executing a PowerShell command. Our article about [resetting Windows Security](https://www.makeuseof.com/windows-11-reset-windows-security/) tells you how to apply this potential resolution in three different ways.

![The Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-option.jpg)

## 6\. Run a Malwarebytes Scan

 The “Unexpected error” can sometimes be caused by malware targeting Windows Security. Yet, users can’t purge malware with Windows Security because of the error. So, try running a scan with the freeware Malwarebytes version. Some users have said utilizing that software helped them resolve the “Unexpected error” issue. This is how you can run a Malwarebytes scan:

1. Open the [Malwarebytes](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2024249/https://www.malwarebytes.com/) website.
2. Click the**Free Download** button.
3. Activate Explorer by holding the**Windows** logo key and pressing**E** .
4. Go to the folder location containing the Malwarebytes setup file.
5. Double-click the**MBSetup.exe** file.
6. Click**Install** to add Malwarebytes to a default directory path.  
![The Install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-button-for-malwarebytes.jpg)
7. Select**Me or my family** (for personal use) at the production selection step and click**Next** .
8. Click**Skip this for now** if you prefer not to install the additional Malwarebytes Browser Guard software.  
![The Skip this for now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/skip-this-for-now-option.jpg)
9. Select**Done** to finish.
10. Malwarebytes will then open automatically. Select**Get started** \>**Maybe later** within the Malwarebytes window.
11. Click**Get started** again.
12. Select Malwarebytes’**Scan** option.  
![The Scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-option.jpg)
13. Press the**Quarantine** button after the scan.

 If this potential resolution works, you can keep Malwarebytes installed for manual scanning. It’s a 14-day trial of the Premium version, and the real-time protection will only last a couple of weeks. However, you can disable the Malwarebytes protection to ensure it doesn’t conflict with Microsoft Defender by right-clicking the utility’s system tray icon and deselecting the**Malware** ,**Ransomware** ,**Exploit** , and**Web Protection** options.

 The Microsoft Safety Scanner is an alternative to Malwarebytes you can run a malware scan with as well. However, that’s only a temporary scanning utility that expires after 10 days. You can download that utility from this [Microsoft page](https://learn.microsoft.com/en-us/microsoft-365/security/intelligence/safety-scanner-download?view=o365-worldwide) . Check out [our Microsoft Safety Scanner guide](https://www.makeuseof.com/microsoft-safety-scanner-guide/) for details about to purge malware with that tool.

## 7\. Check the "Turn Off Microsoft Defender Antivirus" Group Policy Setting

 If you’re a Windows Pro or Enterprise user, check that the the**Turn Off Microsoft Defender Antivirus** policy isn’t enabled in Group Policy. You can check that policy in the following steps:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) by pressing the**Windows** logo +**S** hotkey, entering**gpedit.msc** in the search box, and selecting the**gpedit.msc** result.
2. Then navigate to this policy location in Group Policy’s sidebar:  
`Computer Configuration\Administrative Templates\Windows Components\Microsoft Defender Antivirus`
3. Next, double-click**Turn Off Microsoft Defender Antivirus** to check that policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-defender-antivirus-policy-settings.jpg)
4. Click**Not Configured** if that policy is set to**Enabled** .  
![The Turn Off Microsoft Defender Antivirus policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-microsoft-defender-antivirus.jpg)
5. Select the policy’s**Apply** and**OK** options.

## 8\. Reset Windows or Perform an In-Place Upgrade

 Resetting Windows is a troubleshooting method that restores the platform to a default (factory) configuration. The Reset this PC tool gives you a simple way to reinstall the platform and preserve user files, but you’ll need to reinstall apps.

[Applying a Windows reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) might resolve some deeper system issues causing the “Unexpected error” issue. However, it’s only advised to do so if none of the other potential solutions suggested here work.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-this-pc-tool.jpg)

 An in-place upgrade is an alternative troubleshooting method to resetting Windows. Performing an in-place upgrade will reinstall Windows by installing the latest build version. So, it’s like a reset, but the advantage is that an in-place upgrade preserves the apps you’ve installed. This guide to [performing an in-place upgrade on Windows](https://www.makeuseof.com/in-place-upgrade-windows-11/) provides full instructions for upgrading Windows 11 in such a way.

 However, you could feasibly upgrade to a new Windows version via Settings. Open**Windows Update** in the Settings app to see if there’s a version upgrade available. If so, select to upgrade to the latest Windows build from there.

## Run a Scan With Windows Security Again

 You’ll probably be able to access the antivirus-scanning options in Windows Security again after applying the potential solutions covered here. So, try applying all those potential “Unexpected error” resolutions in the order specified to find one that works on your Windows PC. You can also contact the [Microsoft Windows support service](https://support.microsoft.com/en-us/home/contact?SourceApp=smc2&ContactUsExperienceEntryPointAssetId=Google) for further assistance but give the potential fixes outlined here a try first.

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
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-vivo-y36-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Vivo Y36 Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modern-standby-anomalies-in-the-windows-ecosystem/"><u>Modern Standby Anomalies in the Windows Ecosystem</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-avchd-video-editing-software-top-recommendations/"><u>Updated In 2024, AVCHD Video Editing Software Top Recommendations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitmedia-mastery-elevate-your-tweet-game-for-2024/"><u>[New] TwitMedia Mastery  Elevate Your Tweet Game for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-chrome-induced-system-time-missteps-windows/"><u>Rectifying Chrome-Induced System Time Missteps (Windows)</u></a></li>
<li><a href="https://fox-http.techidaily.com/accelerate-artistry-in-windows-11-photoshop-for-2024/"><u>Accelerate Artistry in Windows 11 Photoshop for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-3-actionable-ways-to-create-countdown-animation-for-videos/"><u>Updated 3 Actionable Ways to Create Countdown Animation for Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-windows-autoshrink-mechanism/"><u>Taming Window's Autoshrink Mechanism</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-inexpensive-screenshot-and-record-software-guide/"><u>[New] Inexpensive Screenshot & Record Software Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-intel-unison-for-convenient-windows-11-calls/"><u>Making the Most of Intel Unison for Convenient Windows 11 Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-error-e1-code-on-w10w11-systems/"><u>Eradicating Error E1 Code on W10/W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-control-of-security-answers-in-windows-11-local-account/"><u>Taking Control of Security Answers in Windows 11 Local Account</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-sparkle-in-a-snap-effortless-stellar-tiktok-videos-with-pre-designed-graphics-for-2024/"><u>[New] Sparkle in a Snap  Effortless Stellar TikTok Videos with Pre-Designed Graphics for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-oppo-find-n3-flip-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Oppo Find N3 Flip Phone?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mac-users-top-4-choices-for-exquisite-music-editing-software/"><u>Mac Users Top 4 Choices for Exquisite Music Editing Software</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advanced-color-grading-with-luts-in-premiere-pro/"><u>Advanced Color Grading with LUTs in Premiere Pro</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-disabled-iphone-14-proipad-without-computer-by-drfone-ios/"><u>How to Unlock Disabled iPhone 14 Pro/iPad Without Computer</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-definitive-guide-to-perfecting-vimeo-recordings-for-2024/"><u>[New] The Definitive Guide to Perfecting Vimeo Recordings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-security-with-new-passwords-in-win-11/"><u>Streamline Security with New Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-persistent-issues-windows-obs-not-opening-troubleshooting/"><u>Tackling Persistent Issues: Windows OBS Not Opening Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-reactivate-an-inactive-hotspot-in-windows-11/"><u>Guidelines to Reactivate an Inactive Hotspot in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-techniques-transform-mkv-videos-into-windows-mp4-files/"><u>Simple Techniques: Transform MKV Videos Into Windows MP4 Files</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-tiktok-unboxing-hacks-spin-your-video-into-a-viral-hit/"><u>[Updated] TikTok Unboxing Hacks  Spin Your Video Into a Viral Hit</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-12plus-stunning-instagram-gif-stickers/"><u>New In 2024, 12+ Stunning Instagram GIF Stickers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-iphones-secret-to-quick-cost-free-red-eye-removal-revealed/"><u>[New] IPhone's Secret to Quick, Cost-Free Red-Eye Removal Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-snip-tool-text-edits-on-win-11/"><u>Perfecting Snip Tool Text Edits on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-playback-lags-a-guide-for-chromium-users/"><u>Overcoming Playback Lags: A Guide for Chromium Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-finder-high-speed-pics-on-win-11/"><u>[Updated] Expert Finder  High-Speed Pics on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-your-spoken-words-into-written-sense-using-whisper/"><u>Turn Your Spoken Words Into Written Sense Using Whisper</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-guide-to-picking-ideal-youtube-partnership-allies/"><u>The Guide to Picking Ideal YouTube Partnership Allies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unraveling-vloggers-terrors-and-techniques-to-triumph/"><u>2024 Approved  Unraveling Vloggers' Terrors and Techniques to Triumph</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-repair-code-0xc00ce556-on-windows/"><u>Mastering Error Repair: Code 0xC00CE556 on WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-windows-11-pc-manager-tools-guide/"><u>Enhance Productivity: Windows 11 PC Manager Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ensure-complete-ram-usage-by-windows-os/"><u>Strategies to Ensure Complete RAM Usage by Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-escape-the-slow-gpsvc-cycle/"><u>Expert Tips to Escape the Slow GPSVC Cycle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-custom-keybinds-quick-paste-in-win-1011/"><u>Master Custom Keybinds: Quick Paste in Win 10/11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/echoing-together-fusing-audio-elements-to-enhance-video-experience-for-2024/"><u>Echoing Together Fusing Audio Elements to Enhance Video Experience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vac-denied-access-in-steam-windows/"><u>Troubleshooting VAC Denied Access in Steam Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-more-keyboard-confusion-30-ways-to-fix/"><u>No More Keyboard Confusion: 30 Ways to Fix</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-integrating-annotations-for-enhanced-engagement/"><u>2024 Approved  Integrating Annotations for Enhanced Engagement</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-honor-80-pro-straight-screen-edition-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Honor 80 Pro Straight Screen Edition? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-valentines-day-2023-a-step-by-step-guide-to-making-a-romantic-video/"><u>In 2024, Valentines Day 2023 A Step-by-Step Guide to Making a Romantic Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-student-essentials-asus-vivobook-s-15-reviewed/"><u>The Ultimate Student Essentials - ASUS Vivobook S 15 Reviewed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-essentials-of-editing-your-social-media-profile-picture/"><u>[New] 2024 Approved  Essentials of Editing Your Social Media Profile Picture</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-create-a-playlist-on-youtube-a-complete-guide/"><u>[New] In 2024, How to Create a Playlist on Youtube - a Complete Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/he-branding-edge-design-strategies-for-game-changing-banners/"><u>[New] The Branding Edge  Design Strategies for Game-Changing Banners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-disabling-discords-auto-checkup-at-startup/"><u>Strategies for Disabling Discord's Auto-Checkup at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-conflicts-for-print-job-success/"><u>Eradicating Conflicts for Print Job Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-device-opens-issue-on-audacity-in-windows/"><u>Steps to Correct Device Opens Issue on Audacity in Windows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/inute-by-minute-mastery-the-top-ten-on-youtube-daily-for-2024/"><u>[New] Minute-by-Minute Mastery  The Top Ten on YouTube Daily for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalized-lock-pattern-creation-guide-for-windows-11-pcs/"><u>Personalized Lock Pattern Creation Guide for Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-wild-high-on-your-windows-desktop/"><u>Taming the Wild High on Your Windows Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-teamsters-downtime-on-windows-11-10/"><u>Troubleshooting Teamsters Downtime on Windows 11, 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-video-processing-on-windows-embrace-distributed-power-via-tdarr/"><u>Elevate Video Processing on Windows: Embrace Distributed Power via Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/four-steps-for-pausing-windows-update/"><u>Four Steps for Pausing Windows Update</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-5-kid-friendly-flying-toys/"><u>[New] Top 5 Kid-Friendly Flying Toys</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-5-best-4k-monitors-color-grading/"><u>[Updated] In 2024, 5 Best 4K Monitors Color Grading</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-windows-safe-mode-limitation-on-office-suite/"><u>Resolving the Windows-Safe Mode Limitation on Office Suite</u></a></li>
</ul></div>
