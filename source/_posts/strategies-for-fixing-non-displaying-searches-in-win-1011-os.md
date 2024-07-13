---
title: Strategies for Fixing Non-Displaying Searches in Win 10/11 OS
date: 2024-07-12T17:05:09.823Z
updated: 2024-07-13T17:05:09.823Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Fixing Non-Displaying Searches in Win 10/11 OS
excerpt: This Article Describes Strategies for Fixing Non-Displaying Searches in Win 10/11 OS
keywords: Windows Display Optimization,Fixed No Show Links,SEO Win 10 Strategies,Non-Display Searches Solved,Fixing Missing Web Results,OS XSEO Tips for Display,Enhance Search Visibility Win
thumbnail: https://thmb.techidaily.com/0b4edc9260dee73e74c6f70d4608ea90c51d96ccbc3b5f5a0008c722859666ad.jpg
---

## Strategies for Fixing Non-Displaying Searches in Win 10/11 OS

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
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-discontinue-repeated-edge-icons/"><u>Solutions to Discontinue Repeated Edge Icons</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-learn-to-convert-your-vids-into-music-on-instagram-today/"><u>[New] Learn to Convert Your Vids Into Music on Instagram Today</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-photo-cinematic-conversions-sonic-enhancements/"><u>[Updated] 2024 Approved  Photo Cinematic Conversions  Sonic Enhancements</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-adding-visuals-on-instagram-quickly/"><u>[Updated] 2024 Approved  Adding Visuals on Instagram Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-determining-the-perfect-orientation-for-fb-videos/"><u>[Updated] In 2024, Determining the Perfect Orientation for FB Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-improve-youtube-video-quality-and-clarity/"><u>[New] How to Improve YouTube Video Quality and Clarity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-empty-folder-error-message-on-win-11/"><u>Removing the 'Empty Folder' Error Message on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-keyboard-commands-to-sharpen-your-3d-skills/"><u>Essential Keyboard Commands to Sharpen Your 3D Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-videocapture-analysis-hub/"><u>[Updated] In 2024, VideoCapture Analysis Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fixes-for-non-responsive-backlight-on-windows-pcs/"><u>Five Fixes for Non-Responsive Backlight on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-the-ultimate-guide-to-mp3-modification-software-for-mac-uncovering-the-best-tools-and-comparisons/"><u>2024 Approved The Ultimate Guide to MP3 Modification Software for Mac Uncovering the Best Tools and Comparisons .</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/compiling-the-finest-ios-psp-game-tools-1-5/"><u>Compiling the Finest iOS PSP Game Tools #1-5</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-y78-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/deciphering-hdr-mastery-through-luminance-testing/"><u>Deciphering HDR Mastery Through Luminance Testing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-iphone-video-editing-showdown-top-5-apps-compared/"><u>New 2024 Approved IPhone Video Editing Showdown Top 5 Apps Compared</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigms-of-administrative-control-in-windows-environments/"><u>Shifting Paradigms of Administrative Control in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-access-rectifying-unreachable-ea-services/"><u>Reestablishing Access: Rectifying Unreachable EA Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lsassexe-unable-to-locate-error-simple-steps/"><u>Fixing 'lsass.exe' Unable to Locate Error - Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-to-buy-and-install-adobe-reader-via-ms-store/"><u>Simplified Guide to Buy and Install Adobe Reader via MS Store</u></a></li>
<li><a href="https://extra-skills.techidaily.com/laughter-labyrayer-with-adobes-help-for-2024/"><u>Laughter Labyrayer with Adobe's Help for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-to-java-development-kit-setup-in-windows-11/"><u>Essential Steps to Java Development Kit Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-glitches-with-ps/"><u>Resolving Windows Glitches with PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sony-bdp-s6700-review-updated-for-2024/"><u>Sony BDP-S6700 Review - Updated for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/auditory-sculpture-in-motion-constructing-vibrant-audio-visual-compositions-with-premiere-pro-for-2024/"><u>Auditory Sculpture in Motion Constructing Vibrant Audio-Visual Compositions with Premiere Pro for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-hand-trackings-evolution-and-practice/"><u>[Updated] Unveiling Hand Tracking's Evolution and Practice</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-quick-guide-to-professional-video-filming-with-your-macs-webcam-5-easy-methods/"><u>[New] Quick Guide to Professional Video Filming with Your Mac's Webcam (5 Easy Methods)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-expert-tips-on-producing-high-quality-facebook-video/"><u>[New] 2024 Approved  Expert Tips on Producing High-Quality Facebook Video</u></a></li>
<li><a href="https://extra-hints.techidaily.com/transferring-media-pc-files-to-your-ios-device/"><u>Transferring Media  PC Files To Your iOS Device</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-2024-approved-top-10-streaming-services-worth-a-try/"><u>Updated 2024 Approved Top 10 Streaming Services Worth a Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-cleaning-for-a-functional-windows-11-space/"><u>Effortless Cleaning for a Functional Windows 11 Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pcs-dns-cache-efficiently/"><u>Revamp Your PC's DNS Cache Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/androidiphones-ultimate-guide-top-10-free-photo-overlay-hacks/"><u>Android/iPhone's Ultimate Guide  Top 10 Free Photo Overlay Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-writing-rights-denied-on-windows-devices/"><u>Remedying Writing Rights Denied on Windows Devices</u></a></li>
</ul></div>
