---
title: Guides to Resolve Windows 11 Search Tool Errors
date: 2024-07-12T16:32:29.205Z
updated: 2024-07-13T16:32:29.205Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guides to Resolve Windows 11 Search Tool Errors
excerpt: This Article Describes Guides to Resolve Windows 11 Search Tool Errors
keywords: Fix Windows 11 Search Error,Troubleshoot Win11 Search,Solve Win11 Search Issue,Correcting Win11 Search Faults,Resolving Win11 Search Problems,Address Win11 Search Glitches,Overcome Windows 11 Search Error
thumbnail: https://thmb.techidaily.com/a05ae5ee6982c15ff3eed9139528bca4d5df10563908a6200578c04353f69c36.jpg
---

## Guides to Resolve Windows 11 Search Tool Errors

 Most users probably utilize the Windows 11/10 search tool to find apps and files. However, some users have reported their search tools don’t display any results. Some users see a “No results found” message whenever they search. Or the search tool displays nothing except a blank white screen in other instances.

 Either way, users can’t find things with the Windows search tool when it doesn’t display results right. Is your search tool not showing results either? If that’s the case, you can fix your search tool not displaying results in Windows 11/10 with these potential resolutions.

## 1\. Update Windows

 Microsoft releases a multitude of patch updates to fix Windows bugs and issues. So, it’s recommended to manually check for and download any available Windows updates for the sake of fixing the search tool. That also includes build updates for new Windows versions. Here’s how you can manually download and install Windows 11/10 updates.

1. Press the**Windows** key, and select the pinned Settings app shortcut on the Start menu that opens.
2. Select**Windows Update** along the left of Settings. In Windows 10, click**Update & Security** on Settings’ home screen.
3. Then press**Check for updates** to initiate a search. Most available updates will download and install automatically.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-check-for-updates-button.jpg)
4. If selecting**Check for updates** doesn’t automatically install everything available, click the**Download and Install** buttons for any other updates (including version 22H2).

## 2\. Run the Search Troubleshooting Tool

 Windows has troubleshooters that can fix all kinds of errors and issues. The Search and Indexing troubleshooter is the one for resolving search-related issues that occur in Windows. You may be able to fix the search tool not displaying results with that troubleshooter as follows:

1. Use one of the many ways to open Settings on Windows, then open the Setting's**System** tab.
2. Click**Troubleshoot** inside the Settings app’s**System** tab.
3. Select**Other trouble-shooters** to reach the Windows troubleshooters.
4. Press**Run** for the Search and Indexing troubleshooter.  
![The Run button for the Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-run-button-for-the-search-and-indexing-troubleshooter.jpg)
5. Click the**Can't start a search or see results** checkbox, and select the troubleshooter’s**Next** option. The **Files, folders, apps, or settings don't appear in results** checkbox is also a suitable option to select for troubleshooting this issue.  
![The Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-search-and-indexing-troubleshooter.jpg)

 The steps for opening the Search and Indexing troubleshooter in Windows 10’s Settings app aren’t exactly the same. Click**Update & Security** \>**Troubleshoot** in Windows 10’s Settings app. Selecting**Additional troubleshooters** will bring up the list. Then you can click**Run the troubleshooter** for Search and Indexing to open it from there.

## 3\. Select the Enhanced Search Option

 The Settings app has some search options that can affect the effectiveness of the search tool. You can set the search utility to fully search a PC by selecting an**Enhanced** option. Try selecting that option in the following steps:

1. Click**Settings** on the Start or Power User (**Win** +**X**) menu.
2. Select the**Privacy & security** tab to view navigation options for Windows permissions.
3. Click the**Searching Windows** navigation option.  
![The Search Windows navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-searching-windows-navigation-option.jpg)
4. Then select the**Enhanced** radio button.  
![The Enhanced radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-enhanced-radio-button.jpg)
5. Click the menu buttons for all excluded search folders listed below that option and select**Remove** .  
![The Remove option for excluded folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-remove-option.jpg)

## 4\. Start the Windows Search Service

 The search tool won’t display results if the Windows Search service it’s based on isn’t running. So, check the Windows Search is enabled and running:

1. To access Run, press**Win** +**R** . You can also use any method in our guide on [how to open Run on Windows](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Then type**services.msc** inside the**Open** box, and select Run’s**OK** option.
3. Double-click**Windows Search** within the Services app.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-services-window2.jpg)
4. Click the drop-down menu for the**Startup type** option to select the service’s**Automatic** option.  
![The Windows Search Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-windows-search-properties-window.jpg)
5. Press**Start** in the properties window if the search service isn’t running.
6. To save the changed settings, click the**Apply** option.
7. Select**OK** to close Windows Search Properties.

 If the Windows Search service is already running, try restarting it. Select the**Stop** option for Windows Search. Wait a few minutes, and click the**Start** button for the service to restart it.

## 5\. Run a Scan With the SFC Tool

 Microsoft recommends users run the System File Checker (SFC) tool when Windows functions aren’t working right. In this case, the search function isn’t displaying results, which could be because of corrupted Windows files on your PC. This is how you can start an SFC scan:

1. Launch the Run dialogue box as above, and enter**cmd** inside its**Open** box.
2. Press the**Ctrl** +**Shift** +**Enter** key combination to open Command Prompt with admin permissions.
3. First, run an image scan by entering this command text and pressing**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
4. Then start the SFC scan by executing the following command:  
`sfc /scannow`  
![The SFC scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-sfc-scan-command.jpg)
5. Wait for the SFC tool to show a Windows Resource Protection scan outcome.

## 6\. Rebuild the Search Tool’s Index

 A corrupted or outdated search index database is another potential cause for the search tool not displaying results. In this case, you may need to select to rebuild the search index. Doing so will wipe the current index’s content and restart the indexing. These are the steps for rebuilding the search index in Windows:

1. To open Control Panel, bring up Run first. Type**Control Panel** into Run and click**OK** . See [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/) for more methods.
2. Select**Large icons** on Control Panel’s**View by** menu.  
![The Large icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-large-icons-button.jpg)
3. Click**Indexing Options** to view that applet.
4. Select**Advanced** in the Indexing Options window.
5. Click**Rebuild** in the Index**Settings** tab.  
![The Rebuild button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-rebuild-option.jpg)
6. Wait for the rebuilding to finish.
7. Select**OK** \>**Close** to exit the indexing applet.

## 7\. Reinstall Cortana

 Cortana is an app that’s closely connected with the Windows search tool. Some users have been able to fix the search tool not displaying results by reinstalling that app. You can reinstall Cortana in PowerShell like this:

1. Press Task Manager’s**Ctrl** +**Shift** +**Esc** keyboard shortcut.
2. Click**File** and the**Run new task** option.
3. Type**PowerShell** inside the Create new task window’s**Open** box.
4. Select the checkbox for the**Create new task with administrative privileges** option.
5. Then select**OK** to access PowerShell.
6. Input the following command for reinstalling Cortana:  
`Get-AppXPackage -Name Microsoft.Windows.Cortana | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The command for reinstalling Cortana](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reinstall-cortana-command.jpg)
7. Press**Enter** to execute the PowerShell command.

## 8\. Reset Windows

 If nothing else fixes the search tool not showing results, this is the last-resort resolution to try. Resetting Windows reinstalls the platform by restoring it to a default configuration, which will most likely be enough to resolve this search issue. However, you’ll need to reinstall any software you previously installed after a reset.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-tool.jpg)

 You can perform a reset with the Reset this PC recovery tool. That utility includes an option for preserving user files. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this resolution with that tool.

## Find Apps and Files Again With the Windows Search Tool

 So, that’s how you can get your Windows search tool fixed when it’s not showing results. We recommend applying the suggested resolutions in the order specified above. There’s a reasonable chance one will sort your search utility out so that you can find the apps and files you’re looking for with it again.

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
<li><a href="https://win11-tips.techidaily.com/clearing-the-way-for-smooth-steam-disk-operations/"><u>Clearing the Way for Smooth Steam Disk Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/old-hardware-new-horizinas-guiding-windows-11-22h2-installation/"><u>Old Hardware, New Horizinas: Guiding Windows 11 22H2 Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-to-spotify-fixing-windows-11-errors/"><u>Reconnecting to Spotify: Fixing Windows 11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-exception-handling-breaking-point-solution/"><u>Mastering Windows Exception Handling: Breaking Point Solution</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-enhancing-your-videos-final-impression/"><u>In 2024, Enhancing Your Video's Final Impression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-removing-virtualization-support-on-win11/"><u>Tips for Removing Virtualization Support on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-explaining-watermarks-securing-online-media/"><u>[New] Explaining Watermarks  Securing Online Media</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-ultimate-guide-mastering-color-correction-and-grading/"><u>2024 Approved  Ultimate Guide  Mastering Color Correction & Grading</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-how-to-achieve-pristine-sound-quality-tactics-to-reduce-echo/"><u>Updated How to Achieve Pristine Sound Quality Tactics to Reduce Echo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-why-drives-vanish-on-windows-fix-guide-required/"><u>Unveiling Why Drives Vanish on Windows - Fix Guide Required</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-say-goodbye-to-clutter-how-to-convert-dvds-to-digital-files/"><u>New 2024 Approved Say Goodbye to Clutter How to Convert DVDs to Digital Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-win-microphone-functionality/"><u>Troubleshoot Win Microphone Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-troubleshooting-tactics-for-non-functional-firefox-in-windows/"><u>7 Troubleshooting Tactics for Non-Functional Firefox in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-user-support-4-new-windows-features/"><u>Transforming User Support: 4 New Windows Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-screencapture-pro-tips-your-guide-to-free-recording-options/"><u>[New] 2024 Approved  ScreenCapture Pro Tips – Your Guide to FREE Recording Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-roots-user-permissions-back-to-basics-in-win11/"><u>Restoring Roots: User Permissions Back to Basics in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-tasks-updating-window-11s-context-menu/"><u>Streamlining Tasks: Updating Window 11'S Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 15 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-craft-the-perfect-gif-message-in-snapchat-easy-steps/"><u>[New] 2024 Approved  Craft the Perfect Gif Message in Snapchat [Easy Steps]</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-outlook-problems-on-pcs/"><u>Understanding and Fixing Outlook Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-unregistered-package-error-in-win11-images/"><u>Steps to Resolve Unregistered Package Error in Win11 Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-for-windows-1011-search-that-fails-to-display-output/"><u>Troubleshooting for Windows 10/11 Search that Fails to Display Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://screen-capture.techidaily.com/enhance-live-stream-performance-with-these-5-pro-tips/"><u>Enhance Live Stream Performance with These 5 Pro Tips</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-windows-identifying-top-5-cutting-tools/"><u>[Updated] 2024 Approved  Mastering Windows  Identifying Top 5 Cutting Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/professional-photographers-top-10-best-4k-cameras-for-2024/"><u>Professional Photographers' Top 10  Best 4K Cameras for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-keyboard-command-center-mastery-of-shortcuts-for-fixed-paste-tasks/"><u>Win11's Keyboard Command Center: Mastery of Shortcuts for Fixed Paste Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-failed-updates-error-0x800f0845/"><u>Steps to Fix Failed Updates - Error 0X800f0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-pathway-for-changing-login-method-from-pin-to-passwords-on-windows-11/"><u>Unveiling the Pathway for Changing Login Method From PIN to Passwords on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-double-your-watch-time-on-youtube-with-these-tips-for-2024/"><u>[Updated] Double Your Watch Time on YouTube with These Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-adjustments-for-enhanced-windows-bar/"><u>Step-by-Step Adjustments for Enhanced Windows Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/universal-font-collection-windows-installation-steps/"><u>Universal Font Collection: Windows Installation Steps</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-notable-top-5-superlight-action-camera-picks-for-2024/"><u>[New] Notable Top 5 Superlight Action Camera Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-character-map-hurdles-a-step-by-step-solution/"><u>Breaking Down Windows Character Map Hurdles: A Step-by-Step Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-aggregatorhostexe-windows-functionality-and-safety-concerns/"><u>Understanding AggregatorHost.exe: Windows' Functionality & Safety Concerns</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-nubia-z50-ultra-device-sim-by-drfone-android/"><u>Easily Unlock Your Nubia Z50 Ultra Device SIM</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-optimal-free-webcam-video-grabber-app/"><u>[Updated] In 2024, Optimal Free Webcam Video Grabber App</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-magic-5-pro-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor Magic 5 Pro Reset Code | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-boost-your-tiktok-fandom-in-a-flash-critical-insights-shared/"><u>[New] In 2024, Boost Your TikTok Fandom in a Flash - Critical Insights Shared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-dialer-in-win-11/"><u>Using Dialer in Win 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-techniques-to-amplify-gopro-battery-duration/"><u>[Updated] Techniques to Amplify GoPro Battery Duration</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-expanding-your-circle-discord-friending-101/"><u>[New] In 2024, Expanding Your Circle  Discord Friending 101</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pc-boost-unearthing-windows-best-eight-restart-strategies/"><u>Quick PC Boost: Unearthing Windows' Best Eight Restart Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-double-click-3-essential-tips/"><u>Mastering Mouse Double-Click: 3 Essential Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-realme-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Realme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-task-managers-welcome-screenscape-in-win11/"><u>Adjusting Task Manager's Welcome Screenscape in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inactive-windows-file-alignment-service/"><u>Solutions for Inactive Windows File Alignment Service</u></a></li>
<li><a href="https://screen-capture.techidaily.com/prime-routines-for-documenting-live-sports-events/"><u>Prime Routines for Documenting Live Sports Events</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-microsofts-copilot-key-for-windows-11-users/"><u>Unveiling the Secrets of Microsoft's Copilot Key for Windows 11 Users</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-mastering-linux-audio-the-best-software-and-techniques-for-sound-capture/"><u>Updated 2024 Approved Mastering Linux Audio The Best Software and Techniques for Sound Capture</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-13-mini-to-factory-settings-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Reset Apple iPhone 13 mini to Factory Settings? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-resolving-face-swap-glitches-in-facebook-chat/"><u>[New] Resolving Face Swap Glitches in Facebook Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-windows-terminal-the-unshackled-experience/"><u>Restoring Windows Terminal: The Unshackled Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-transformation-editors-that-impress/"><u>[Updated] In 2024, Instagram Transformation  Editors That Impress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-methodology-for-adding-intel-ethernet-support/"><u>Comprehensible Methodology for Adding Intel Ethernet Support</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-from-mundane-to-memorable-transform-your-social-media-identity-with-these-tips/"><u>[Updated] 2024 Approved  From Mundane to Memorable  Transform Your Social Media Identity with These Tips</u></a></li>
</ul></div>
