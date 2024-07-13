---
title: Troubleshooting for Windows 10/11 Search that Fails to Display Output
date: 2024-07-12T16:37:05.845Z
updated: 2024-07-13T16:37:05.845Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting for Windows 10/11 Search that Fails to Display Output
excerpt: This Article Describes Troubleshooting for Windows 10/11 Search that Fails to Display Output
keywords: Windows 10 Search Issues,Fixing 11 Search Failures,Troubleshoot Search Not Showing Results,Resolve Windows 10/11 Search Problems,Enhance Output Display in Windows Search,Diagnose Non-Displaying Windows Searches,Correct Windows Search No Output
thumbnail: https://thmb.techidaily.com/0c4c453f95a612f76b387ff712305941e5398ae6df028882ef27bbdd6859fdde.jpg
---

## Troubleshooting for Windows 10/11 Search that Fails to Display Output

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
<li><a href="https://fox-boxes.techidaily.com/2024-approved-elite-virtuoso-broadcasting-services/"><u>2024 Approved  Elite Virtuoso Broadcasting Services</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-top-logo-evolutions-for-online-communities/"><u>[New] 2024 Approved  Top Logo Evolutions for Online Communities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-tricks-for-repairing-white-screen-on-store/"><u>Tips and Tricks for Repairing White Screen on Store</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-10-instagram-hashtag-that-you-should-be-using-today-for-2024/"><u>[New] 10 Instagram Hashtag That You Should Be Using Today for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-disabled-user-sign-in-on-windows/"><u>Troubleshooting Disabled User Sign-In on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-signature-approaches-to-capture-pc-hosted-television-sessions/"><u>In 2024, Signature Approaches to Capture PC-Hosted Television Sessions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-honor-x50-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Honor X50 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-procedure-for-gpu-detection-in-windows-11/"><u>Speedy Procedure for GPU Detection in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/exacting-education-pearsons-gsl-meets-mondly/"><u>Exacting Education: Pearson’s GSL Meets Mondly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-best-practices-for-ping-commands/"><u>Understanding Windows: Best Practices for Ping Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-bypassing-tpm-with-rufus/"><u>Unlocking Windows 11: Bypassing TPM with Rufus</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-precision-flight-matching-cameras-to-ideal-gimbal-models/"><u>[Updated] 2024 Approved  Precision Flight  Matching Cameras to Ideal Gimbal Models</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-optimizing-your-hp-experience-expert-guide-to-screen-capture/"><u>[Updated] Optimizing Your HP Experience  Expert Guide to Screen Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-xbox-stranded-message-quick-solution-for-windows-users/"><u>Overcome Xbox Stranded Message: Quick Solution for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackling-third-party-vendors-from-defender-constraints/"><u>Unshackling Third-Party Vendors From Defender Constraints</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-easily-erase-identity-blurring-techniques-in-videos-for-2024/"><u>[New] Easily Erase Identity  Blurring Techniques in Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-excess-usage-enhancing-efficiency-for-news-in-windows-1011/"><u>Slash Excess Usage: Enhancing Efficiency for News in Windows 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dust-off-the-glare-avoiding-gopro-misting/"><u>Dust Off the Glare  Avoiding GoPro Misting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/start-up-sync-automatic-windows-entry-with-sticky-notes/"><u>Start-Up Sync: Automatic Windows Entry with Sticky Notes</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-surfings-finest-high-quality-cam-companions/"><u>[Updated] 2024 Approved  Surfing's Finest  High-Quality Cam Companions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-cpu-usage-in-dropbox-on-windows-pcs/"><u>Tackling High CPU Usage in Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/separate-your-online-storage-onedrive-and-microsoft-ids/"><u>Separate Your Online Storage: OneDrive & Microsoft IDs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-updater-0x8024a205-issue/"><u>Overcoming Windows Updater 0X8024a205 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-typing-solutions-for-windows-pcs-7-must-dos/"><u>Speedy Typing Solutions for Windows PCs (#7 Must-Dos)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workspace-tackling-screen-lag-in-windows/"><u>Streamline Your Workspace: Tackling Screen Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-errors-how-to-fix-unopenable-packages/"><u>Navigating Windows Errors: How to Fix Unopenable Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-critical-alerts-when-to-reset-windows/"><u>Nine Critical Alerts: When to Reset Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/previewing-windows-wonders-with-vivetool-capabilities/"><u>Previewing Windows Wonders with ViVeTool Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-copilot-from-your-windows-environment/"><u>Removing Copilot From Your Windows Environment</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-edit-like-a-pro-fcp-audio-editing-techniques-for-video-creators/"><u>New Edit Like a Pro FCP Audio Editing Techniques for Video Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-to-record-clear-sound-in-windows-11/"><u>Simple Steps to Record Clear Sound in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-procedure-to-fix-a-disabled-windows-11-hotspot/"><u>Restarting Procedure to Fix a Disabled Windows 11 Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-reviving-non-functioning-reading-aloud-in-word-2016plus/"><u>Quick Guide to Reviving Non-Functioning Reading Aloud in Word 2016+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-reset-windows-paperwork-service/"><u>Quick Reset Windows' Paperwork Service</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-the-ultimate-list-of-gender-neutral-voice-editing-programs-for-aspiring-actors-updated/"><u>Updated 2024 Approved The Ultimate List of Gender-Neutral Voice Editing Programs for Aspiring Actors, Updated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-steam-symbols-on-pc/"><u>Resetting Steam Symbols on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-wows-fatal-issue-in-windows-1111/"><u>Troubleshooting WoW's Fatal Issue in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-dormant-folders-in-the-windows-11-ui/"><u>Unmasking Dormant Folders in the Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-user-rights-configuration-in-terminal/"><u>Troubleshooting User Rights Configuration in Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-copy-pasting-issues-across-chrome-edge-and-firefox-on-win/"><u>Troubleshooting Copy-Pasting Issues Across Chrome, Edge, & Firefox on Win</u></a></li>
</ul></div>
