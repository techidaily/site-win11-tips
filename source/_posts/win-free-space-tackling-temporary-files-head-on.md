---
title: "Win-Free Space: Tackling Temporary Files Head On"
date: 2024-08-23T07:05:50.995Z
updated: 2024-08-24T07:05:50.995Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win-Free Space: Tackling Temporary Files Head On"
excerpt: "This Article Describes Win-Free Space: Tackling Temporary Files Head On"
keywords: FreeSpaceWin,TempFilesClean,FileOptimizer,UnusedSpaceRemoval,OptimalStorageTips,TemporaryFileManagement,SpaceEfficiencyGuru
thumbnail: https://thmb.techidaily.com/6c7b51dcfdae2a8da726c75853a324eb9a3939b33880d7b4a364119150ff2caf.jpg
---

## Win-Free Space: Tackling Temporary Files Head On

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your PC after this and try to delete temporary files once again.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-progressive-audio-softening-methods/"><u>[New] 2024 Approved  Progressive Audio Softening Methods</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-evaluating-the-leading-video-calling-platforms-for-tech-enthusiasts/"><u>[Updated] 2024 Approved  Evaluating the Leading Video Calling Platforms for Tech Enthusiasts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-get-close-or-farther-with-ease-on-instagram-stories/"><u>[Updated] 2024 Approved  Get Close or Farther with Ease on Instagram Stories</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-digital-dissection-the-vll-review-process/"><u>[Updated] Digital Dissection  The VLL Review Process</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-professional-techniques-to-make-a-standout-gopro-time-lapse-for-2024/"><u>[Updated] Professional Techniques to Make a Standout GoPro Time-Lapse for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-convert-google-meet-chats-into-youtube-livestream-easily/"><u>2024 Approved  Convert Google Meet Chats Into YouTube Livestream Easily</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-android-photography-alterations/"><u>2024 Approved  Premium Android Photography Alterations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-extracting-nested-archives-in-windows/"><u>Comprehensive Guide to Extracting Nested Archives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-directdraw-fails-a-practical-approach-for-win11-users/"><u>Conquering DirectDraw Fails: A Practical Approach for Win11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-the-future-workplace-with-vr-technology/"><u>Crafting the Future Workplace with VR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/developing-a-feature-to-showcase-latest-updates-in-explorer/"><u>Developing a Feature to Showcase Latest Updates in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-disk-read-problems-in-windows/"><u>Eliminating Disk Read Problems in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unidentified-device-errors-on-w11w10/"><u>Eliminating Unidentified Device Errors on W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-toranse-of-wsl-in-windows-environment/"><u>End-Toranse of WSL in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-to-ensure-utorrent-operates-correctly-in-windows/"><u>Fixes to Ensure uTorrent Operates Correctly in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-inputs-reviving-xbox-mic-functionality-on-windows-11/"><u>Fixing Blank Inputs: Reviving Xbox Mic Functionality on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-common-windows-11-error-code-0xc0000001/"><u>Fixing the Common Windows 11 Error Code 0XC0000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-unhandled-exception-a-step-by-step-process/"><u>Fixing Windows 'Unhandled Exception': A Step-by-Step Process</u></a></li>
<li><a href="https://discord-videos.techidaily.com/from-anonymity-to-authority-the-essential-pathway-for-raising-issues-on-digital-platforms-like-discord-for-2024/"><u>From Anonymity to Authority  The Essential Pathway for Raising Issues on Digital Platforms Like Discord for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/frugal-cloud-loft-economical-space-for-huge-file-stashes/"><u>Frugal Cloud Loft  Economical Space for Huge File Stashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-rectify-windows-bluetooth-outputs-music-only/"><u>Guidelines to Rectify Windows Bluetooth Outputs - Music Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-unstrand-your-gaming-experience-in-windows/"><u>How to Correctly Unstrand Your Gaming Experience in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-ethernet-speed-capped-at-100mbps-on-windows/"><u>How to Fix Your Ethernet Speed Capped at 100Mbps on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-poco-x5-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Poco X5 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-regain-file-viewing-rights-on-your-pc/"><u>How to Regain File Viewing Rights on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-retrieve-lost-default-volume-levels-on-pc/"><u>How to Retrieve Lost Default Volume Levels on PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-leading-edge-mp3-sync-service-at-no-cost/"><u>In 2024, Leading Edge MP3 Sync Service at No Cost</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-youtube-a-guide-for-gamers-live-broadcasts/"><u>In 2024, Mastering YouTube  A Guide for Gamers' Live Broadcasts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-tiny-tranquil-houses-japanese-style/"><u>In 2024, Tiny Tranquil Houses  Japanese Style</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-iphone-photo-hacks-to-enhance-your-landscapes/"><u>In 2024, Top iPhone Photo Hacks to Enhance Your Landscapes</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-success-with-office-works-setup-in-win11/"><u>Instant Success with Office Works Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-your-linux-environment-into-windows-11-seamlessly/"><u>Integrating Your Linux Environment Into Windows 11 Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intelligent-battery-alerts-set-up-full-charges-in-windows-11/"><u>Intelligent Battery Alerts: Set Up Full Charges in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-fast-virtual-machines-on-windows-heres-how/"><u>Lightning-Fast Virtual Machines on Windows - Here's How</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-computers-sound-output-on-windows-with-updated-drivers/"><u>Master Your Computer's Sound Output on Windows with Updated Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restoring-lost-ps4-input-connection/"><u>Mastering the Art of Restoring Lost PS4 Input Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-gaps-between-explore-elements/"><u>Mending Gaps Between Explore Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-geforce-now-xc0f1103f-fix/"><u>Mending Windows 11’S GeForce Now: Xc0f1103f Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-ad-ds-printer-errors-a-user-friendly-approach-for-windows-users/"><u>Navigating AD DS Printer Errors: A User-Friendly Approach for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-defective-battery-life-meter-on-windows-11-machines/"><u>Realigning Defective Battery Life Meter on Windows 11 Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refresh-classics-atlasos-gaming-update/"><u>Refresh Classics: AtlasOS Gaming Update</u></a></li>
<li><a href="https://technical-tips.techidaily.com/resolved-troubleshooting-oculus-setup-issues-on-windows-11-and-10/"><u>Resolved: Troubleshooting Oculus Setup Issues on Windows 11 & 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-haven-10-secure-sites-for-windows-free-apps/"><u>Safe Haven: 10 Secure Sites for Windows FREE Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securely-implementing-new-os-windows-11-and-vmware-edition/"><u>Securely Implementing New OS: Windows 11 & VMWare Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-method-to-disable-wired-keys-for-pcs-running-windows/"><u>Stepwise Method to Disable Wired Keys for PCs Running Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-windows-11-photos-experience-with-slide-shows-and-image-spot-repair/"><u>Streamline Your Windows 11 Photos Experience with Slide Shows & Image Spot Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-android-studio-operations-a-win32-guide/"><u>Streamlining Android Studio Operations: A Win32 Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/supreme-top-4k-tvs-for-gamers-for-2024/"><u>Supreme Top 4K TVs for Gamers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-off-internal-display-hardware-in-win-810/"><u>Switching Off Internal Display Hardware in Win 8/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-into-a-world-of-innovation-with-ms-store-apps/"><u>Tap Into a World of Innovation with MS Store Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-trigger-camera-notification-in-win11-os/"><u>Techniques to Trigger Camera Notification in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-to-easier-network-management-windows-guide/"><u>The Pathway to Easier Network Management: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-ensure-camera-activity-notifications-in-ws11/"><u>Tips to Ensure Camera Activity Notifications in WS11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-playtime-preventing-league-of-legends-offline-on-pc/"><u>Uninterrupted Playtime: Preventing League of Legends Offline on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-login-story-valiant-entries-or-fumbled-attempts/"><u>Unveiling the Login Story: Valiant Entries or Fumbled Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-ps4-input-drop-outs-on-personal-computers/"><u>Winning Against PS4 Input Drop-Outs on Personal Computers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>