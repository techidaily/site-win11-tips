---
title: "Mending Errors: A Guide to FS Repair in Win11"
date: 2024-07-12T17:38:12.554Z
updated: 2024-07-13T17:38:12.554Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mending Errors: A Guide to FS Repair in Win11"
excerpt: "This Article Describes Mending Errors: A Guide to FS Repair in Win11"
keywords: Fix Windows Errors,Win11 Repair Tips,FS Error Troubleshooting,Win11 System Fixes,Error Handling in Windows,Win11 Recovery Guide,Boot Loader Mending
thumbnail: https://thmb.techidaily.com/ade566529a7bc97aed23a78dd1be17314340f234a16c9d2f0b2b465091d3ea91.jpg
---

## Mending Errors: A Guide to FS Repair in Win11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on [how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to [utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://win11-tips.techidaily.com/1719364670351-create-a-gratis-local-gptclone-with-gpt4all-for-windows/"><u>Create a Gratis, Local GPTClone with GPT4All for Windows.</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-your-images-with-gorgeous-mosaics/"><u>Elevate Your Images with Gorgeous Mosaics</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-camera-excellence-the-top-10-4k-ready-shoulder-rigs/"><u>2024 Approved  Camera Excellence  The Top 10 4K-Ready Shoulder Rigs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-effortless-screen-recording-on-modern-pcs/"><u>[New] Effortless Screen Recording on Modern PCs</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-forget-the-14-password-or-pattern-lock-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you forget the 14 password or pattern lock</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-recommended-portals-accessing-custom-ringers/"><u>[New] Recommended Portals  Accessing Custom Ringers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-snip-and-sketch-with-one-move/"><u>Launching Windows Snip & Sketch With One Move</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-access-the-high-level-command-prompt-in-w11-os/"><u>How to Access the High-Level Command Prompt in W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-sticky-context-menus-in-windows-11-edition/"><u>Addressing Sticky Context Menus in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-time-and-date-on-windows-11-taskbar/"><u>Configuring Time and Date on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-the-promise-of-next-generation-in-the-upcoming-moment/"><u>Windows 11: The Promise of Next Generation in the Upcoming Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-insight-determining-your-intel-cpus-generation/"><u>Windows Insight: Determining Your Intel CPU's Generation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/create-a-seamless-workflow-with-alt-tab-in-win1110/"><u>Create a Seamless Workflow with Alt-Tab in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confronting-memory-write-issues-in-windows/"><u>Confronting 'Memory Write' Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-molds-changing-the-winadmin-access-paradigm/"><u>Breaking Molds: Changing the WinAdmin Access Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-modifying-the-reset-counter-post-failed-logon-attempts-win-11/"><u>Enhancing Security: Modifying the Reset Counter Post Failed Logon Attempts, Win 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-apple-iphone-12-pro-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your Apple iPhone 12 Pro and iPad?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-straightforward-guide-to-photo-uploads-on-instagram/"><u>In 2024, The Straightforward Guide to Photo Uploads on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-copy-and-paste-on-chrome-edge-firefox-os/"><u>Overhauling Copy & Paste on Chrome, Edge, Firefox OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-leading-15-android-virtual-machines-for-your-devices-for-2024/"><u>[Updated] The Leading 15 Android Virtual Machines for Your Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-non-admin-account-permissions-in-windows/"><u>Fine-Tuning Non-Admin Account Permissions in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>How To Activate and Use Life360 Ghost Mode On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/github-desktop-essentials-for-effective-windows-git-control/"><u>GitHub Desktop Essentials for Effective Windows Git Control</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-pro-choice-top-picks-of-10-premium-vimeo-video-download-tools/"><u>2024 Approved  Pro Choice  Top Picks of 10 Premium Vimeo Video Download Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-configure-end-task-feature-for-efficient-task-execution-windows-11/"><u>How to Configure End Task Feature for Efficient Task Execution (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-startup-folder-in-windows-os-quickly/"><u>Navigating to Startup Folder in Windows OS Quickly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-stand-out-in-the-crowd-top-15-innovative-snapchat-posts/"><u>[New] 2024 Approved  Stand Out in the Crowd  Top 15 Innovative Snapchat Posts</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-k11x-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-mastering-content-discovery-with-powerful-title-and-tag-use/"><u>[New] Mastering Content Discovery with Powerful Title & Tag Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responding-spotify-app-in-w10-and-w11/"><u>Fixing Non-Responding Spotify App in W10 & W11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-cyberspace-supplement-facebook-story-saver/"><u>[New] Cyberspace Supplement  Facebook Story Saver</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-streamline-your-social-media-uploading-on-twitter-for-2024/"><u>[Updated] Streamline Your Social Media  Uploading on Twitter for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-custom-inactive-period-setting/"><u>Windows: Custom Inactive Period Setting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-seamless-shift-to-workspace-with-windows-1011/"><u>A Seamless Shift to Workspace with Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-navigation-turn-off-acceleration-windows-1011/"><u>Mastering Mouse Navigation: Turn Off Acceleration Windows 10/11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/chordcatcher-software-insight-for-2024/"><u>ChordCatcher Software Insight for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-printer-disconnection-in-windows-10-and-11-systems/"><u>Fast Track Printer Disconnection in Windows 10 & 11 Systems</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-unlocking-the-potential-of-recording-google-voice-calls/"><u>[New] 2024 Approved  Unlocking the Potential of Recording Google Voice Calls</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-precision-techniques-for-capturing-the-essence-of-moments-with-gopro/"><u>[Updated] 2024 Approved  Precision Techniques for Capturing the Essence of Moments with GoPro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-smart-color-settings-in-windows-11-programs/"><u>Enable Smart Color Settings in Windows 11 Programs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-budget-friendly-hd-video-capturing-for-home-studios/"><u>[New] Budget-Friendly HD Video Capturing for Home Studios</u></a></li>
<li><a href="https://screen-capture.techidaily.com/offline-masterpieces-top-10-ios-game-selections-without-internet/"><u>Offline Masterpieces  Top 10 iOS Game Selections Without Internet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compelling-case-for-continuing-with-windows-10-win10/"><u>Compelling Case for Continuing with Windows 10 (Win10)</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-the-beat-goes-on-finding-song-titles-using-your-ios-devices-audio-cues/"><u>New In 2024, The Beat Goes On Finding Song Titles Using Your iOS Devices Audio Cues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-your-pcs-health-report-efficiently/"><u>Navigate to Your PC’s Health Report Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-bandwidth-methods-for-assessing-your-networks-velocity/"><u>Boost Bandwidth: Methods for Assessing Your Network's Velocity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-self-initiating-open-of-search-bar-win11-help/"><u>Cease Self-Initiating Open of Search Bar, Win11 Help</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/transforming-your-video-content-making-square-format-footage-for-instagram-for-2024/"><u>Transforming Your Video Content  Making Square-Format Footage for Instagram for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/charting-a-course-through-websites-of-youtube-affiliates-for-2024/"><u>Charting a Course Through Websites of YouTube Affiliates for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-ultimate-guide-to-iphone-video-editing-top-5-apps-for-2024/"><u>The Ultimate Guide to iPhone Video Editing Top 5 Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-calculator-display-timeframe-on-windows/"><u>Maximizing Calculator Display Timeframe on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-route-to-recent-windows-documents/"><u>Direct Route to Recent Windows Documents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-windows-audio-amplification-feature/"><u>Cease Windows Audio Amplification Feature</u></a></li>
<li><a href="https://extra-resources.techidaily.com/feathered-salsa-dancer/"><u>Feathered Salsa Dancer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitfort-fractured-stay-the-course-before-change/"><u>BitFort Fractured: Stay the Course Before Change</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ways-to-expand-hard-drive-capacity-in-windows-for-free/"><u>Efficient Ways to Expand Hard Drive Capacity in Windows, For Free</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-harmonizing-soundscape-a-comprehensive-guide-to-eq-adjustments/"><u>New 2024 Approved Harmonizing Soundscape A Comprehensive Guide to EQ Adjustments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreachable-status-for-malwarebytes-services-in-win11/"><u>How to Fix Unreachable Status for Malwarebytes' Services in Win11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/masterful-mashups-our-picks-for-10-premium-audio-amplifiers/"><u>Masterful Mashups  Our Picks for 10 Premium Audio Amplifiers</u></a></li>
</ul></div>
