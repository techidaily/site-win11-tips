---
title: "Reset and Reactivate: A Windows User's Guide for MS Store"
date: 2024-07-12T16:37:52.436Z
updated: 2024-07-13T16:37:52.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
excerpt: "This Article Describes Reset and Reactivate: A Windows User's Guide for MS Store"
keywords: Windows Reset Tips,Revive MS Store Apps,MS Store Reinstalls,Troubleshoot MS Errors,Reactivate Windows Store,Fixing MS Store Issues,Restart Microsoft Services
thumbnail: https://thmb.techidaily.com/a6c09f57496c52b8e907a972b91ffe1ac4bdb6bfabe268a90cf22a89412c015d.jpg
---

## Reset and Reactivate: A Windows User's Guide for MS Store

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users
![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users
![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://tiktok-video-recordings.techidaily.com/the-artists-guide-to-crafting-impactful-tiktok-backdrops-for-2024/"><u>The Artist's Guide to Crafting Impactful TikTok Backdrops for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-10-step-roadmap-to-winrm/"><u>Unraveling the 10-Step Roadmap to WinRM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-installation-time-with-proper-deps-setup/"><u>Cut Down Installation Time with Proper Deps Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-honor-100-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Honor 100 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-eliminating-nvidia-experience-disconnect-issues/"><u>Strategies for Eliminating Nvidia Experience Disconnect Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-reasons-to-choose-win11-over-apples-macos/"><u>Top Reasons to Choose Win11 Over Apple's macOS</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-say-goodbye-to-shaky-footage-advanced-stabilization-in-after-effects-for-2024/"><u>New Say Goodbye to Shaky Footage Advanced Stabilization in After Effects for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-loading-messages-in-windows-discord-client/"><u>Correcting Non-Loading Messages in Windows Discord Client</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-minimizing-disruptions-in-windows-updates/"><u>The Art of Minimizing Disruptions in Windows Updates</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-security-enlarge-pins-best-practices-in-windows-1111/"><u>Boost Security, Enlarge Pins: Best Practices in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-access-and-manage-gpo-settings-in-win11/"><u>Swiftly Access and Manage GPO Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-winrars-summation-missteps-with-6-fixes/"><u>Combatting WinRAR's Summation Missteps with 6 Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-a-comprehensible-guide-to-srt-fundamentals/"><u>In 2024, A Comprehensible Guide to SRT Fundamentals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-the-words-start-talking-windows-11s-method/"><u>Cut the Words, Start Talking: Windows 11'S Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-windows-11-writable-memory-protection/"><u>Correcting Windows 11' Writable Memory Protection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-the-win11-vision-disturbance/"><u>[FIXED] The Win11 Vision Disturbance</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secure-boot-status-a-windows-bios-solution-manual/"><u>Unlocking Secure Boot Status: A Windows BIOS Solution Manual</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-9-powerful-applications-for-saving-youtube-content-on-android/"><u>In 2024, 9 Powerful Applications for Saving YouTube Content on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-for-winerror-0x80072746-in-outlook/"><u>The Ultimate Fix for WinError 0X80072746 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-dormant-devices-with-synapse-on-windows-11/"><u>Reviving Dormant Devices with Synapse on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-clutter-unwanted-windows-tools-and-how-to-eliminate-them/"><u>Tackle Clutter: Unwanted Windows Tools and How to Eliminate Them</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-deactivated-office-alerts-in-windows/"><u>Resolving Deactivated Office Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-current-frames-crafting-future-windows/"><u>Beyond Current Frames: Crafting Future Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-how-to-download-facebook-videos-on-windows-and-mac/"><u>In 2024, How to Download Facebook Videos on Windows and Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-for-successful-intel-lan-setup-on-vista/"><u>The Essentials for Successful Intel LAN Setup on Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-2023-laptop-reveals-ifa-edition/"><u>Top 2023 Laptop Reveals - IFA Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-yuzu-game-performance-in-windows/"><u>Boosting Yuzu Game Performance in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-windows-1011-revamping-using-winbubble/"><u>The Complete Guide to Windows 10/11 Revamping Using WinBubble</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-top-10-tiktok-viral-videos-on-twitter-for-2024/"><u>[Updated] Top 10 TikTok Viral Videos on Twitter for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seize-the-deal-unmissable-black-friday-612-win10/"><u>Seize the Deal: Unmissable Black Friday - $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auto-shutdown-mastery-for-idle-pcs-in-w10w11/"><u>Auto Shutdown Mastery for Idle PCs in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-boot-speed-heres-how/"><u>Turbocharge Windows 11 Boot Speed – Here’s How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-windows-trick-sticky-notes-open-up-with-system-boot/"><u>Tailored Windows Trick: Sticky Notes Open-Up With System Boot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-on-windows-a-step-by-step-guide/"><u>Converting Gmail To Outlook on Windows – A Step-by-Step Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-web-based-movie-trailer-design-studios/"><u>In 2024, Web-Based Movie Trailer Design Studios</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-for-social-media-savants-distinguishing-between-igtv-and-youtube/"><u>[Updated] For Social Media Savants  Distinguishing Between IGTV & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-default-silence-camera-activation-in-win11/"><u>Breaking the Default Silence: Camera Activation in Win11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-old-school-cool-best-apps-for-adding-vintage-vhs-effects-to-your-videos/"><u>Updated 2024 Approved Old School Cool Best Apps for Adding Vintage VHS Effects to Your Videos</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-best-slow-motion-camera-apps-for-best-content-creation/"><u>Updated Best Slow Motion Camera Apps for Best Content Creation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-truth-behind-the-windows-store-dodging-digital-duplicates/"><u>The Truth Behind the Windows Store: Dodging Digital Duplicates</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-rapid-windows-photo-examiner-for-enhanced-efficiency/"><u>[Updated] Rapid Windows Photo Examiner for Enhanced Efficiency</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-mastering-visual-content-size-videos-correctly-for-instagram/"><u>[Updated] 2024 Approved  Mastering Visual Content  Size Videos Correctly for Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-malfunctioning-office-notification-system/"><u>Solving Malfunctioning Office Notification System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-your-windows-devices-microsoft-store-error-code-x800704cf/"><u>Unlocking Your Windows Devices: Microsoft Store Error Code X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-windows-11-character-map/"><u>Step-by-Step to Windows 11 Character Map</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-smiles-to-text-where-to-find-amusing-tones/"><u>2024 Approved  Smiles to Text  Where to Find Amusing Tones?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/aiming-high-selecting-the-best-webcams-for-live-gameplay-streams-for-2024/"><u>Aiming High  Selecting the Best Webcams for Live Gameplay Streams for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/iscover-these-27-purely-free-youtube-audio-ripper-tools-for-2024/"><u>[New] Discover These 27 Purely Free YouTube Audio Ripper Tools for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-xiaomi-redmi-k70-pro-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Xiaomi Redmi K70 Pro System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-live-streaming-made-simple-mastering-ps4-captures-using-obs/"><u>In 2024, Live Streaming Made Simple  Mastering PS4 Captures Using OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-battlenet-not-available-errors-on-win-1011/"><u>Tips for Resolving Battle.net Not Available Errors on Win 10/11</u></a></li>
</ul></div>
