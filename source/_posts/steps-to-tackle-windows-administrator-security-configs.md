---
title: Steps to Tackle Windows Administrator Security Configs
date: 2024-07-12T17:40:35.982Z
updated: 2024-07-13T17:40:35.982Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Tackle Windows Administrator Security Configs
excerpt: This Article Describes Steps to Tackle Windows Administrator Security Configs
keywords: Admin Secure Steps,Windows Admin Safeguarding,Managing Win Admins Safely,Securing Admin Configs,Admin Security Best Practices,Protecting Win Admin Settings,Optimizing Admin Config
thumbnail: https://thmb.techidaily.com/75acee6ab640019b74d394195d334c99ef1bc00597a90331917637ac51654852.png
---

## Steps to Tackle Windows Administrator Security Configs

 Some users have reported they can’t set Windows Security options because of an error that says, “This setting is managed by your administrator.” Those users see that error message just above options within the**Virus & threat protection** and**App & browser tabs** of that app. Consequently, they can’t turn on important Windows Security settings there that are grayed out and disabled.

 That issue has little to do with admin rights. Many users who encounter the issue are already utilizing Windows administrator accounts. This is how you can fix the “setting is managed by your administrator” error in Windows 11.

## 1\. Check for and Install Available Windows 11 Updates

 Although not the most likely potential solution, some users have said installing available Windows 11 updates helped them resolve this error. Patchers for Windows 11 usually address Windows bugs reported by users.

 If you're not sure how to do this, visit [how to install Windows 11 updates](https://www.makeuseof.com/windows-11-install-updates/) for a step-by-step guide.

## 2\. Reset the Windows Security and Settings Apps

 Users who’ve fixed the “setting is managed by your administrator” error have confirmed resetting the Windows Security and Settings apps can work. Resetting those apps will clear their data. You can reset Windows Security via Settings, as outlined in our [how to reset apps on Windows](https://www.makeuseof.com/windows-reset-app/) guide.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-option.jpg)

 To reset Settings, you must open the Start menu and right-click the app’s shortcut. Select**App settings** to bring up some troubleshooting options for it. Then select the**Reset** troubleshooting option for the app.

## 3\. Uninstall Third-Party Antivirus Software

 Some third-party antivirus utilities can disable Windows Security features they effectively replace. If you’ve installed an overlapping third-party antivirus product, uninstalling it may resolve Windows Security’s administrator error. Uninstall antivirus software with a method within our guide on [how to remove Windows programs](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to see if that resolves the issue.

![The uninstaller tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-uninstaller-tool.jpg)

 Should this solution work, the issue will likely reoccur if you reinstall the same third-party antivirus virus software. Then you would have to choose between using the third-party antivirus utility or Windows Security.

## 4\. Edit the Registry

 Many users have been able to fix the Windows Security administrator error by applying this confirmed registry solution. This registry tweak involves modifying a DWORD value, but you don’t need to delete any key. To apply this potential resolution, edit the registry like this:

1. Run the Windows Registry Editor app, which you can open with any method included in our [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) [g](https://www.makeuseof.com/windows-11-open-registry-editor/) uide.
2. Click inside the address box at the top of Registry Editor and erase the text in it.
3. Input this key path in the registry address bar and press**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\DeviceGuard\Scenarios\HypervisorEnforcedCodeIntegrity`
4. Then double-click the**Enabled** DWORD within the**HypervisorEnforcedCodeIntegrity** key.  
![The HypervisorEnforced registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hypervisor-key.jpg)
5. Clear the**Data value** box, and then input**0** there.
6. Select**OK** to set the**Enabled** DWORD’s value.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-window.jpg)
7. Exit Registry Editor and click the**Power** \>**Restart** Start menu options.

## 5\. Set Group Policy’s Real-time Protection Settings to "Not Configured"

 A possibility for Windows 11 Pro and Enterprise users to consider is that Group Policy Editor could be blocking changes to Windows Security settings. If you can open Group Policy Editor on your PC, check real-time protection policy settings aren’t enabled there. This is how you can set real-time protection settings to not configured in Group Policy Editor:

1. Find Group Policy Editor by clicking the search magnifying glass icon and inputting**gpedit.msc** .
2. Select**gpedit.msc** to open the Group Policy Editor window.
3. Then select**Computer Configuration** to extend that category.
4. Double-click**Administrative Template** to access several setting categories.
5. Next, double-click**Windows Components** \>**Microsoft Defender Antivirus** \>**Real-time Protection** in the navigation sidebar.  
![The Real-time Protection policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-real-time-protection-policy-settings.jpg)
6. Double-click any policy setting that’s with an enabled state.
7. Then select the**Not configured radio** button.  
![The Not Configured radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/not-configured-option.jpg)
8. Click**Apply** \>**OK** in the window to set the change.
9. Repeat the previous three steps for all real-time protection policies set to enabled.

## 6\. Reinstall Windows Security

 You can’t reinstall Windows Security by uninstalling that app via Settings and downloading it from Microsoft Store. However, you can run a more general PowerShell command that reinstalls all apps pre-installed with Windows 11\. Try reinstalling Windows Security with that command as follows:

1. Open PowerShell with administrative rights. Our guide on [how to open PowerShell](https://www.makeuseof.com/windows-11-powershell-administrator/) includes various methods for opening that app.
2. Then input the following PowerShell command for reinstalling apps:  
`Get-AppXPackage -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall app PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reinstall-app-command.jpg)
3. Press**Enter** and wait for the command to finish.
4. Restart your laptop or desktop from the Start menu.

## 7\. Reinstall Windows 11 With the Media Creation Tool

 Reinstalling Windows 11 by downloading an ISO with Media Creation Tool is a drastic potential solution. However, users have confirmed updating Windows 11 in such a way works for fixing this error. Furthermore, you can select to preserve apps and files when reinstalling. This is how to reinstall Windows 11:

1. Download the latest Windows 11 ISO with the Media Creation Tool. Our guide on [how to download a Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) includes step-by-step instructions for how to do so.
2. Then double-click your downloaded Windows 11 ISO file.
3. Click**setup.exe** to open the Windows 11 installer.  
![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-setup-window.jpg)
4. Select**Next** to initiate a system check.
5. Press the**Accept** button for the license terms.
6. The**Keep personal files and apps** option will probably be set by default at the ready-to-install stage. However, you click**Change what to keep** to make sure the**Keep personal files and apps** option is selected.  
![The Keep personal files and apps radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keep-personal-files-option.jpg)
7. Then select**Next** to proceed to the last step.
8. Click**Install** to reinstall Windows 11.

## Change Windows Security’s Settings Again

 Those are the most widely cited ways to fix the “setting is managed by your administrator” error in Windows 11\. So, applying those potential resolutions will probably resolve the “setting is managed by your administrator” issue on your PC. Then you’ll be able to set all the options within Windows Security as required.

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
<li><a href="https://win11-tips.techidaily.com/essential-tools-for-shaping-windows-esd-files-into-iso/"><u>Essential Tools for Shaping Windows' ESD Files Into ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-virtualbox-usb-connection-issue-on-windows-devices/"><u>Overcoming VirtualBox USB Connection Issue on Windows Devices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-unique-thumbnails-for-youtube-content/"><u>In 2024, Crafting Unique Thumbnails for YouTube Content</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-watchnetflix-screenshare-master-screenrecording-on-macos/"><u>2024 Approved  WatchNetflix, Screenshare  Master ScreenRecording on MacOS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-discover-the-process-of-slowing-down-time-lapse-videos-on-your-iphone/"><u>Updated Discover the Process of Slowing Down Time-Lapse Videos on Your iPhone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-start-live-webcam-recording-with-vlc-media/"><u>[New] In 2024, Start Live Webcam Recording with VLC Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-complex-archives-efficiently-handling-multiple-zips-in-one-go/"><u>Decoding Complex Archives: Efficiently Handling Multiple ZIPS in One Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-fatal-javascript-issue-with-ease-on-win-11-discord/"><u>Conquering Fatal Javascript Issue with Ease on Win 11 Discord</u></a></li>
<li><a href="https://vp-tips.techidaily.com/perfecting-pics-a-full-guide-to-facetune-mastery-for-2024/"><u>Perfecting Pics - A Full Guide to Facetune Mastery for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-an-additional-monitor-without-gui-chipset/"><u>How to Use an Additional Monitor Without GUI Chipset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rejuvenate-itunes-that-wont-respond-on-windows/"><u>How to Rejuvenate iTunes That Won't Respond on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-setup-ensure-your-pcs-microphone-and-webcam/"><u>Efficient Setup: Ensure Your PC's Microphone & Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-nokia-130-music-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-imovies-cropping-an-in-depth-look/"><u>2024 Approved  IMovie's Cropping  An In-Depth Look</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-guide-on-populating-emojis-in-discord-user-status-field-for-2024/"><u>[Updated] Guide on Populating Emojis in Discord User Status Field for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-checks-when-windows-obs-studio-wont-launch/"><u>Essential Checks When Windows' OBS Studio Won't Launch</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-enable-usb-debugging-on-a-locked-honor-magic-v2-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Honor Magic V2 Phone</u></a></li>
<li><a href="https://network-issues.techidaily.com/the-next-step-windows-10-enhancements-with-amds-radeon-hd-6950-drivers/"><u>The Next Step: Windows 10 Enhancements with AMD's Radeon HD 6950 Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-taming-high-cpu-use-in-modern-windows-host/"><u>Deciphering and Taming High CPU Use in Modern Windows Host</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-the-variance-in-procedures-for-local-and-remote-windows-reinstallations/"><u>Analyzing the Variance in Procedures for Local and Remote Windows Reinstallations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-twitters-most-popular-video-hotspots/"><u>[Updated] In 2024, Twitter's Most Popular Video Hotspots</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/audioarchitect-designing-without-dacast-for-2024/"><u>AudioArchitect  Designing Without DaCast for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-of-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Avoidance of Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-uninterrupted-adventures-top-10-best-offline-ios-titles/"><u>[New] In 2024, Uninterrupted Adventures  Top 10 Best Offline iOS Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-troubleshooting-failed-capture-on-win11/"><u>Methods for Troubleshooting Failed Capture on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-colored-display-in-windows-based-devices/"><u>How to Adjust Colored Display in Windows-Based Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-hurdles-of-xbox-game-pass-error-code-0-essential-tips-for-windows-11-users/"><u>Avoiding the Hurdles of Xbox Game Pass Error Code 0: Essential Tips for Windows 11 Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-unveiling-the-secrets-of-obs-game-capture/"><u>2024 Approved  Unveiling the Secrets of OBS Game Capture</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-best-applications-tiktok-vs-youtubes-micro-video-realm/"><u>Exploring Best Applications  TikTok vs YouTube's Micro-Video Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reopen-a-closed-nvidia-control-panel-on-windows-11/"><u>How to Reopen a Closed Nvidia Control Panel on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-delete-email-from-windows-sign-in-screen/"><u>Efficient Ways to Delete Email From Windows Sign-In Screen</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-unleash-your-creativity-best-practices-for-snap-ad-success/"><u>[Updated] 2024 Approved  Unleash Your Creativity  Best Practices for Snap Ad Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-new-os-build-a-focused-and-effective-windows-11-boot-drive-in-three-ways/"><u>Conquer the New OS – Build a Focused and Effective Windows 11 Boot Drive in Three Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-scripts-the-winexe-transformation-tutorial/"><u>Elevate Your Scripts: The WinEXE Transformation Tutorial</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-your-youngsters-safety-in-ps5-world/"><u>Ensuring Your Youngster's Safety in PS5 World</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/skill-up-on-the-fly-with-top-10-freeware-art-apps-for-mac-for-2024/"><u>Skill Up on the Fly with Top 10 Freeware Art Apps for Mac for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-the-stuck-windows-enter-function/"><u>Mending the Stuck Windows 'Enter' Function</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-xiaomi-mix-fold-3-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Xiaomi Mix Fold 3 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-unending-teams-sign-in-requests/"><u>Overcoming Windows Error: Unending Teams Sign-In Requests</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-monetization-face-off-analyzing-dailymovement-and-youtube-profits/"><u>In 2024, Monetization Face-Off  Analyzing DailyMovement and Youtube Profits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-windows-problems-effective-assistance-guide/"><u>Conquer Windows Problems: Effective Assistance Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-making-and-dreams-of-virtual-entertainment-artists/"><u>The Making and Dreams of Virtual Entertainment Artists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guides-to-resolve-windows-11-search-tool-errors/"><u>Guides to Resolve Windows 11 Search Tool Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-this-file-cannot-be-previewed-error-in-outlook-for-windows/"><u>How to Fix the This File Cannot Be Previewed Error in Outlook for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-windows-11-visuality-with-app-sizing/"><u>Boosting Windows 11 Visuality with App Sizing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-webbrowsers-for-lighter-system-resource-use-on-os-x-windows-chromeos/"><u>Efficient Webbrowsers for Lighter System Resource Use on OS X, Windows, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-magic-automating-archive-creation-in-windows/"><u>Command Line Magic: Automating Archive Creation in Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-taming-the-sound-waves-with-audacity-seamless-setup-and-removal-processes-in-ubuntu/"><u>New Taming the Sound Waves with Audacity Seamless Setup and Removal Processes in Ubuntu</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/step-up-your-game-techniques-for-bordered-instagram-videos-for-2024/"><u>Step Up Your Game  Techniques for Bordered Instagram Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-camera-omission-from-windows-dm-display/"><u>Correct Camera Omission From Windows' DM Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-options-picking-right-nvidia-driver-type-for-you/"><u>Navigating Options, Picking Right Nvidia Driver Type For You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ifttt-and-microsoft-to-dot-synergy-explained/"><u>IFTTT & Microsoft To-Dot Synergy Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-functionality-fix-media-on-win11/"><u>Mastering the Art of Restoring Functionality: Fix Media on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-for-the-v22h2-update-dilemma-on-win11-os/"><u>Efficient Fixes for the V22H2 Update Dilemma on Win11 OS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtubes-essential-learning-resources-for-upcoming-directors/"><u>2024 Approved  YouTube's Essential Learning Resources for Upcoming Directors</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-detailed-instructions-mastering-the-art-of-uploading-vr-media-to-fb/"><u>[Updated] Detailed Instructions  Mastering the Art of Uploading VR Media to FB</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-highlight-hubs-choosing-the-right-online-aids/"><u>In 2024, Highlight Hubs  Choosing the Right Online Aids</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-essential-capture-tools-15-windows-11-recorder-apps/"><u>[Updated] Essential Capture Tools  #15 Windows 11 Recorder Apps</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-snapscreen-videorecorder-tool-for-2024/"><u>[New] SnapScreen Videorecorder Tool for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-demanded-assets-error-in-windows-1011-environments/"><u>Overcoming Demanded Assets Error in Windows 10/11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-isarcextract-error-in-windows-11-updates/"><u>Overcoming ISArcExtract Error in Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-highlight-the-mouse-cursor-in-windows-11-and-11/"><u>How to Highlight the Mouse Cursor in Windows 11 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-perfect-xiaomi-device-for-amateur-filmmakers/"><u>[New] 2024 Approved  The Perfect Xiaomi Device for Amateur Filmmakers</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-free-up-apple-iphone-13-mini-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up Apple iPhone 13 mini Space | Dr.fone</u></a></li>
</ul></div>
