---
title: "Mastering Unique Devices Names: Erase 'In Use' Issues on PCs"
date: 2024-07-12T17:36:06.004Z
updated: 2024-07-13T17:36:06.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Unique Devices Names: Erase 'In Use' Issues on PCs"
excerpt: "This Article Describes Mastering Unique Devices Names: Erase 'In Use' Issues on PCs"
keywords: Device Uniqueness Mastery,Clearing In-Use Labels,PC Name Fix Guide,Reset Usage Icon Error,Erase 'In Use' On PC,Devices Management Tips,Solve Usage Markers Issue
thumbnail: https://thmb.techidaily.com/7618ed5212ad2fa17c4d0cff006f1dcb4d7c52766a583e2029f0351c0b405229.jpg
---

## Mastering Unique Devices Names: Erase 'In Use' Issues on PCs

 The Local device name is already in use error is not particularly unusual. If you work with any type of network, even a local network, you are quite likely to encounter it at some point. Luckily, it is also usually easy to resolve.

 Here are the most common causes of this error, along with the most likely solutions.

## What Causes the Local Device Name Error?

 There can be a couple of possible causes of this error, but pinpointing the exact cause can be difficult. The most common are unassigned drive letters and incorrect file and printer sharing settings.

 It is also possible that a lack of space on the network server can result in this error appearing. You should check this possibility first. If lack of storage is the cause, none of the following solutions will make a difference.

 If the network server has ample space, you can move on to trying the methods below to solve the problem on your local device.

## 1 Enable File and Printer Sharing

[You should always keep your firewall enabled](https://www.makeuseof.com/tag/5-reasons-use-firewall/) , but it can sometimes interfere with file and printer sharing. This can lead to seeing the Local device name is already in use error. Luckily you can enable file and printer sharing easily in the firewall settings.

 If you're using a third-party firewall, refer to the documentation to find the setting. Here's how to enable file and printer sharing in the Microsoft Firewall.

1. Search for Control Panel using Windows Search, and click the search result to open it.
2. Click**System and Security > Windows Defender Firewall** to see the firewall settings.
3. In the left menu, click**Allow an app or feature through the firewall** and then click the**Change settings** button.  
![Windows firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-printer-sharing.jpg)
4. Scroll down to find**File and Printer Sharing** in the list, and click the**Public** checkbox.
5. Click**Ok** and restart your computer to apply the change.

 Occasionally, the file and printer sharing settings for the firewall can get reset after a major update. Just because you know you have enabled it in the past, it is worth checking again.

## 2 Remap the Network Drive With Command Prompt

 Windows will automatically assign a letter to your network drive. During network mapping, the assigned letters can become mixed and even be missing altogether. Remapping the network drive can fix this and prevent the error.

1. The best way to remap the network drive is through the Command Prompt. Search for**cmd** in Windows Search and select**Run as Administrator** .
2. At the cursor, type:**net use D /delete** . Replace**D** with the drive letter you want to delete. Then press**Enter** .  
![the remap network drive command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remap-network-drive.jpg)
3. Now remap the drive by typing:**net use D: \\\\server\\share /user:username password** . Replace the drive letter and user and username password with the relevant details.

 If this doesn't help, you may need to try reassigning the drive letters manually. The end result is similar, but sometimes remapping won't work when manually reassigning the drive path will work.

## 3 Re-assign Drive Letters

 Another common cause of this error is an incorrectly assigned drive letter. Reassigning a drive letter is easy, as long as you don't run into the Drive letter not available error.

1. Search for**Disk Management** using Windows Search, or right-click the Start Menu and select it from the hidden menu.
2. In Disk Management, find the partition or drive you want to change and right-click on it.
3. Select**Change Drive Letter and Paths** , and then click the**Add** button.  
![reassigning drive letter in disk management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reassign-drive-letter.jpg)
4. Click**Assign the following drive letter** and use the drop-down menu to choose a new letter for the partition or drive.

 If the drive letter you require is not available, it may already be being used on another drive or partition. It could also be associated with a removable drive that is not currently connected. If the A and B drive letters are available, and they often aren't, it is best not to use them. These letters are traditionally reserved for floppy drives and for use with old OS versions.

 Learn more about [why drive letters usually start with C on Windows](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

## 4 Reinitialize the Computer Browser

 A less likely solution to this error, but one that does sometimes help, is reinitializing the browser. Browser settings can, in some cases, interfere with network drive settings. By stopping the browser and reinitializing it, those settings should be reverted.

1. Open Windows Search and type**cmd** . In the result, select**Command Prompt** and click**Run as Administrator** .
2. At the Command Prompt cursor, type:**net stop "Computer Browser"** and then press**Enter** .  
![reinitialize the browser on command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinitialize-browser.jpg)
3. When the command finishes executing, type:**net start "Computer Browser"** and press**Enter** .
4. You can now close the Registry Editor and check to see if the error persists.

 Reinitializing the browser is different from simply closing and reopening the browser window. It is a much more forceful solution to clearing any browser settings that may be in conflict.

 Learn how to optimize and get the most from your computer with these [essential Windows performance tips](https://www.makeuseof.com/tag/windows-10-faster-performance/) .

## 5 Delete the MountPoints Registry Key

 If none of the above solutions have fixed the problem, you can try deleting the MountPoints registry key as a last resort. This key stores data about USB and other removable drives. Deleting the key can sometimes resolve conflicts in drive letter assignments.

1. Deleting the MountPoints key shouldn't cause problems, but it is best to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case. Do this before you continue.
2. Open the Registry Editor by searching for it in Windows Search.
3. Navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\Explorer** .  
![delete mountpoints in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-mountpoints.jpg)
4. Look for the**MountPoints2** key in the right-hand panel, right-click on it and select**Delete** .
5. Close the Registry Editor and restart your computer.

 The MountPoint registry key will be regenerated after deleting and restarting. You can then check to see if this fixed the Local Device name is already in use error.

## Fixing Local Device Name Errors on Windows

 The Local device name is already in use error is not uncommon, and it can be frustrating. But by working through the solutions here, you will normally be able to fix it within a few minutes. Just be sure to check the remaining storage on the network server before you start digging deeper.


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
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-samsung-galaxy-z-fold-5-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Samsung Galaxy Z Fold 5 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-navigating-the-landscape-a-guide-to-using-hashtags-on-facebook/"><u>[New] Navigating the Landscape  A Guide to Using Hashtags on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-color-convincingness-like-a-pro/"><u>2024 Approved  Crafting Color Convincingness Like a Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/mastering-quick-play-tiktok-speed-skipping-guide-for-2024/"><u>Mastering Quick Play  TikTok Speed Skipping Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-lsassexe-unable-to-locate-error-simple-steps/"><u>Fixing 'lsass.exe' Unable to Locate Error - Simple Steps</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-cutting-edge-techniques-for-setting-the-optimal-size-of-your-youtube-videos/"><u>[New] 2024 Approved  Cutting-Edge Techniques for Setting the Optimal Size of Your YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/boosting-tiktok-the-leading-tools-and-metrics-ranked/"><u>Boosting TikTok  The Leading Tools and Metrics Ranked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-navigating-the-world-of-video-capturing-on-diverse-devices/"><u>2024 Approved  Navigating the World of Video Capturing on Diverse Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://fox-direct.techidaily.com/top-ai-enhanced-photoshop-suite-for-2024/"><u>Top AI Enhanced Photoshop Suite for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-5-key-strategies-to-correct-iphone-hdri-premiere-pro-edition/"><u>2024 Approved  5 Key Strategies to Correct iPhone HDRI  Premiere Pro Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-phones-to-cameras-enhancing-your-live-stream-setup/"><u>[Updated] In 2024, Phones to Cameras  Enhancing Your Live Stream Setup</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-top-5-trimming-titles-tailored-to-your-youtube-needs/"><u>In 2024, Top 5 Trimming Titles Tailored to Your YouTube Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Tecno Camon 20 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-10-cameras-for-smooth-cinematic-captures/"><u>Leading 10 Cameras for Smooth Cinematic Captures</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-complete-analysis-of-the-new-picsart-guide-and-review-for-updated-app/"><u>2024 Approved  A Complete Analysis of the New PicsArt – Guide & Review for Updated App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-power-of-irecorder-in-action-for-2024/"><u>The Power of iRecorder in Action for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-innovative-windows-10-cameras-unveiled/"><u>[Updated] In 2024, Innovative Windows 10 Cameras Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-13-mini-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone 13 mini without Apple Account</u></a></li>
<li><a href="https://youtube-web.techidaily.com/sh-your-videos-full-potential-with-these-seo-mastery-tips/"><u>Unleash Your Videos' Full Potential with These SEO Mastery Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
</ul></div>
