---
title: Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled
date: 2024-07-12T16:50:31.436Z
updated: 2024-07-13T16:50:31.436Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled
excerpt: This Article Describes Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled
keywords: WinErrorCode0X070091Solutions,DirectoryEmptyIssueResolution,Error0X70091EmptyFolders,FixWindows0X80070091Error,0X70091UnresolvedDirectories,ZeroX70091WindowsErrorCause,ClearingZeroX70091Errors
thumbnail: https://thmb.techidaily.com/33493674183189bab67b88de79a85b9996c293935f6ec3a823ac568973956aae.jpg
---

## Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://win11-tips.techidaily.com/1719275215540-reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278644350-briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-beyond-hd-the-exceptional-experience-with-hp-envy-27/"><u>In 2024, Beyond HD - The Exceptional Experience with HP Envy 27</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-a-step-by-step-approach-to-crafting-your-video-market-standouts/"><u>[Updated] A Step-by-Step Approach to Crafting Your Video' Market Standouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-superior-features-added-to-windows-11-feb-update/"><u>9 Superior Features Added to Windows 11, Feb Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-health-monitoring-set-up-full-charge-indicators-in-win11/"><u>Accelerating Battery Health Monitoring: Set Up Full Charge Indicators in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-another-app-uses-same-speaker-windows-edition/"><u>Addressing Error: Another App Uses Same Speaker, Windows Edition</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-insiders-look-at-instagram-viewership-metrics-for-2024/"><u>[Updated] Insider's Look at Instagram Viewership Metrics for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-battlenet-not-opening-windows/"><u>Addressing the Issue of Battle.net Not Opening Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360119482-revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-what-are-youtube-tags-and-how-can-you-find-great-tags-for-your-videos-for-2024/"><u>[New] What Are YouTube Tags and How Can You Find Great Tags For Your Videos for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-the-ultimate-list-5-reaction-video-makers-to-watch/"><u>Updated In 2024, The Ultimate List 5 Reaction Video Makers to Watch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-walkthrough-to-establish-java-development-kit-in-windows-11/"><u>A Complete Walkthrough to Establish Java Development Kit in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-new-features-the-moment-4-update-added-to-windows-11/"><u>7 New Features the Moment 4 Update Added to Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-huawei-p60-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-tecno-spark-10-4g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Tecno Spark 10 4G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-transforming-visual-narratives-with-creative-use-of-luts-in-pro/"><u>[Updated] Transforming Visual Narratives with Creative Use of LUTs in Pro</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-best-discord-couple-chat-spaces/"><u>[Updated] 2024 Approved  Best Discord Couple Chat Spaces</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-pro-converter-mp4-videos-for-social-media-fb-focus/"><u>[New] In 2024, Pro Converter  MP4 Videos for Social Media (FB Focus)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor Phones with/without a PC</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-secure-your-videos-with-free-image-savers/"><u>2024 Approved  Secure Your Videos with FREE Image Savers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-missing-rockalldlldll-problem/"><u>Addressing the 'Missing Rockalldll.dll' Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-fixing-steam-contact-issues-on-win11/"><u>A Step-by-Step Guide to Fixing Steam Contact Issues on Win11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-innovating-messaging-sounds-a-guide-to-downloading-and-personalizing-whatsapp-ringtones/"><u>2024 Approved  Innovating Messaging Sounds  A Guide to Downloading & Personalizing WhatsApp Ringtones</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-instagram-tips-for-stunning-video-content/"><u>[New] Mastering Instagram  Tips for Stunning Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-phased-out-features-in-current-windows-design/"><u>6 Phased-Out Features in Current Windows Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simplified-approach-to-windows-odbc-data-management/"><u>A Simplified Approach to Windows ODBC Data Management</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-t-mobile-apple-iphone-15-pro-online-without-sim-card-by-drfone-ios/"><u>How to Unlock T-Mobile Apple iPhone 15 Pro online without SIM Card?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-mastering-windows-law-filters/"><u>A Practical Approach to Mastering Windows LAW Filters</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-speech-recognition-made-easy-your-route-to-streamlined-workflows-with-microsoft-words-features/"><u>[New] Speech Recognition Made Easy  Your Route to Streamlined Workflows with Microsoft Word's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-windows-keyboard-entry/"><u>Addressing Non-Operational Windows Keyboard Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-organizing-your-w11-space/"><u>A Step by Step Approach to Organizing Your W11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11-widget-bar-features/"><u>Activating Windows 11 Widget Bar Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-frozen-windows-guard-in-windows-11/"><u>Addressing Frozen Windows Guard in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-free-film-resource-highlights-where-to-start-your-search/"><u>[Updated] Free Film Resource Highlights  Where to Start Your Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-faulty-volume-adjustment-sliders/"><u>Addressing Faulty Volume Adjustment Sliders</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-high-quality-capture-with-obs-a-screencast-showcase/"><u>2024 Approved  High-Quality Capture with OBS  A Screencast Showcase</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-essential-mac-snippet-apps-a-compilation/"><u>In 2024, Essential Mac Snippet Apps  A Compilation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-discover-the-top-8-android-platforms-for-large-gatherings/"><u>[New] Discover the Top 8 Android Platforms for Large Gatherings</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xr-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XR With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-embarking-on-a-digital-persona-makeover-tiktok-username-transformation-techniques/"><u>[Updated] Embarking on a Digital Persona Makeover  TikTok Username Transformation Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-compute-with-essential-wintoy-tech/"><u>Accelerate Your Compute with Essential WinToy Tech</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-2024-the-best-text-to-audio-converters-of-all-times/"><u>In 2024, The Best Text-to-Audio Converters of All Times</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-ethical-and-safe-tiktok-following-hacks/"><u>In 2024, Ethical and Safe TikTok Following Hacks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-channel-design-mastery-selecting-the-right-yt-banner-and-art-sizes/"><u>[Updated] In 2024, Channel Design Mastery  Selecting the Right YT Banner & Art Sizes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absent-file-application-linkages-in-win10/"><u>Addressing Absent File Application Linkages in Win10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlining-the-update-process-for-accurate-tiktok-age-details/"><u>[Updated] Streamlining the Update Process for Accurate TikTok Age Details</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-swiftly-move-data-fast-and-reliable-methods-to-direct-files-onto-your-computer/"><u>In 2024, Swiftly Move Data  Fast and Reliable Methods to Direct Files Onto Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-load-in-win11/"><u>Accelerate System Load in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380036891-dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-best-ways-to-watch-360-videos-on-android/"><u>[Updated] Unveiling the Best Ways to Watch 360 Videos on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-handy-tutorial-to-combat-xfffeeee-in-windows/"><u>A Handy Tutorial to Combat XFFFEEEE in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-vivo-x-fold-2-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Vivo X Fold 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-ws11s-software-reset/"><u>A Step-By-Step Manual for WS11's Software Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-1000-club-achievement-monthly-tips-for-insta-success-and-growth-for-2024/"><u>[Updated] The 1,000 Club Achievement  Monthly Tips for Insta Success and Growth for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-sourav-joshis-strategy-for-youtube-earning-in-the-year-2024/"><u>[Updated] Sourav Joshi's Strategy for YouTube Earning in the Year 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-ultimate-path-to-a-thriving-instagram-community/"><u>[Updated] 2024 Approved  The Ultimate Path to a Thriving Instagram Community</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-pages-in-the-explorer-bar/"><u>Addressing Empty Pages in the Explorer Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-misaligned-windows-thx-listening-experience/"><u>Addressing Misaligned Windows THX Listening Experience</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quintessential-quests-screenwriting-gems/"><u>Quintessential Quests  Screenwriting Gems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/astering-youtube-google-meet-live-broadcast-steps/"><u>[New] Mastering YouTube  Google Meet Live Broadcast Steps</u></a></li>
</ul></div>
