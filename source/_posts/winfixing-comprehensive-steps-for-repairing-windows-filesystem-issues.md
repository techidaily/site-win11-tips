---
title: "Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues"
date: 2024-07-12T17:34:33.342Z
updated: 2024-07-13T17:34:33.342Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues"
excerpt: "This Article Describes Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues"
keywords: FixWindowsIssues,FilesystemRepair,WindowsFixSteps,FileSystemHealing,RepairWindowsFiles,SolveWindowsError,WindowsDataRecovery
thumbnail: https://thmb.techidaily.com/2a86960040387567ee8a74265a39e135c9493f594810dac12c910c9d9ffd0bfb.jpg
---

## Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues

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
<li><a href="https://win11-tips.techidaily.com/navigating-non-uniform-colour-realms-in-windows/"><u>Navigating Non-Uniform Colour Realms in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-useful-screen-recorder-for-teachers/"><u>[New] Useful Screen Recorder for Teachers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-device-disconnection-on-win-1011/"><u>Navigating and Fixing Device Disconnection on Win 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-v13-document-with-digital-signature-service-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a PDF v1.3 document with digital signature service</u></a></li>
<li><a href="https://android-frp.techidaily.com/lava-blaze-2-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Lava Blaze 2 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-problems-with-saving-windows-volume-configurations/"><u>Overcoming Problems with Saving Window's Volume Configurations</u></a></li>
<li><a href="https://some-guidance.techidaily.com/uncovering-the-invisible-how-to-inspect-facebooks-data-trails-for-2024/"><u>Uncovering the Invisible  How to Inspect Facebook's Data Trails for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-ping-in-routine-windows-tasks/"><u>Seamless Integration of Ping in Routine Windows Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quash-windows-data-on-launches-tracking/"><u>Quash Windows Data on Launches Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-your-voice-to-text-in-real-time-with-whisper-desktop/"><u>How to Turn Your Voice to Text in Real Time With Whisper Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-empower-your-taskbar-with-new-features/"><u>How to Empower Your Taskbar with New Features</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/youtubes-adsense-income-strategy-calculating-per-thousand-viewers/"><u>Youtube's AdSense Income Strategy  Calculating Per Thousand Viewers</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-experience-the-viral-trend-with-these-top-tiktoks-for-2024/"><u>[Updated] Experience the Viral Trend with These Top TikToks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-for-eliminating-windows-temp-files/"><u>Expert Advice for Eliminating Windows' Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-memory-landscape-identify-ram-straightforwardly/"><u>Exploring Windows Memory Landscape: Identify RAM Straightforwardly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-steam-data-flow-escaping-slowdown-traps/"><u>Revitalizing Steam Data Flow: Escaping Slowdown Traps</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-price-friendly-nimbus-space-wide-file-vault/"><u>In 2024, Price-Friendly Nimbus Space  Wide File Vault</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-d3d11-gpu-error-landscape-for-windows-1110/"><u>Navigating the D3D11 GPU Error Landscape for Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-exception-breakpoint-obstacle/"><u>Overcoming Windows Exception Breakpoint Obstacle</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-unlock-tiktoks-potential-with-our-sizzling-template-selection/"><u>[Updated] In 2024, Unlock TikTok’s Potential with Our Sizzling Template Selection</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-samsung-galaxy-z-fold-5-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Samsung Galaxy Z Fold 5 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-game-on-mastering-the-art-of-play-with-kinemaster-on-android/"><u>[New] Game On! Mastering the Art of Play with KineMaster on Android</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-sync-up-your-studio-setup-the-8-most-popular-music-production-applications-for-mac-and-windows/"><u>Updated 2024 Approved Sync-Up Your Studio Setup The 8 Most Popular Music Production Applications for Mac and Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-explained-easy-mobile-dialing-on-the-latest-windows-11/"><u>Intel Unison Explained: Easy Mobile Dialing on the Latest Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-changing-windows-11-search-icons-backwards/"><u>Guidelines for Changing Windows 11 Search Icons Backwards</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-long-does-it-take-to-edit-videos/"><u>Updated 2024 Approved How Long Does It Take To Edit Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-halted-warcraft-update-sequence/"><u>Navigating a Halted Warcraft Update Sequence</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-master-the-art-of-mac-screen-record-via-shortcuts-for-2024/"><u>[New] Master the Art of Mac Screen Record via Shortcuts for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/delving-into-nvidias-g-sync-a-breakthrough-in-graphics/"><u>Delving Into Nvidia's G-Sync: A Breakthrough in Graphics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-basic-equipment-for-travel-video-creators/"><u>2024 Approved  Basic Equipment for Travel Video Creators</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/how-to-climb-higher-on-tiktoks-rankings-a-guide-for-more-interactions/"><u>How to Climb Higher on TikTok's Rankings  A Guide for More Interactions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-data-theft-controlling-removable-storage-on-pcs/"><u>Preventing Data Theft: Controlling Removable Storage on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-instantaneously-generating-multiple-subfolders-in-windows/"><u>Innovative Approaches to Instantaneously Generating Multiple Subfolders in Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-artistic-zoomers-handbook-a-filters-journey-for-2024/"><u>The Artistic Zoomer's Handbook  A Filters Journey for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivation-guide-for-your-frozen-windows-11-search-box/"><u>Reactivation Guide for Your Frozen Windows 11 Search Box</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-server-issues-fixes-and-tips-for-apex-on-windows-(156-chars/"><u>Overcoming 'No Server' Issues: Fixes and Tips for Apex on Windows (<156 Chars)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-effective-ways-to-decelerate-audio-pieces-without-impacting-tonal-integrity/"><u>2024 Approved Effective Ways to Decelerate Audio Pieces without Impacting Tonal Integrity</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-a-step-by-step-guide-to-seeing-whos-watching/"><u>In 2024, A Step-by-Step Guide to Seeing Who's Watching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reset-and-reactivate-a-windows-users-guide-for-ms-store/"><u>Reset and Reactivate: A Windows User's Guide for MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/open-sound-settings-efficiently-using-these-9-strategies-in-windows-11/"><u>Open Sound Settings Efficiently Using These 9 Strategies in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version.</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-samsung-galaxy-s24-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Samsung Galaxy S24.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-unreadable-source-issue-on-your-windows-pc/"><u>How to Fix ‘Unreadable Source’ Issue on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-your-pcs-bluetooth-on-windows-11/"><u>How to Resurrect Your PC's Bluetooth on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/latency-free-leap-essential-tips-for-clean-video-windows-streams/"><u>Latency-Free Leap: Essential Tips for Clean Video Windows Streams</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-through-the-maze-creating-seamless-video-experienences-in-pixiz/"><u>Navigating Through the Maze  Creating Seamless Video Experienences in Pixiz</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/learn-how-to-lock-stolen-your-apple-iphone-se-2020-properly-by-drfone-ios/"><u>Learn How To Lock Stolen Your Apple iPhone SE (2020) Properly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-realme-narzo-n55-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Realme Narzo N55 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-windows-process-hostaggregate-use-and-security-implications/"><u>Investigating Windows' Process HostAggregate: Use & Security Implications</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-explore-nitro-a-deep-dive-into-discords-elite-service/"><u>[Updated] In 2024, Explore Nitro  A Deep Dive Into Discord's Elite Service</u></a></li>
</ul></div>
