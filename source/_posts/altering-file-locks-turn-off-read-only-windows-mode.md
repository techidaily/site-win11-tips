---
title: "Altering File Locks: Turn Off Read-Only Windows Mode"
date: 2024-07-12T16:48:53.530Z
updated: 2024-07-13T16:48:53.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Altering File Locks: Turn Off Read-Only Windows Mode"
excerpt: "This Article Describes Altering File Locks: Turn Off Read-Only Windows Mode"
keywords: Disable Read-Only Files,Turn Off WIN ReadLock,Remove File Read-Only Status,Stop WIN Read-Only Mode,Eliminate Windows Locks,Bypass Read-Only Windows,Override File Permissions
thumbnail: https://thmb.techidaily.com/80fee98e39755278bb461fd482dd243762bcc8eb6156836ba9860fa44be8739e.jpg
---

## Altering File Locks: Turn Off Read-Only Windows Mode

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on [how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn [how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Lava Storm 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-correct-xbox-mic-issues-in-os/"><u>Guidelines to Correct Xbox Mic Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-evaluating-live-stream-giants-twitch-and-youtube-for-2024/"><u>[New] Evaluating Live Stream Giants  Twitch & YouTube for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-personalized-secure-locks-for-windows-11/"><u>Designing Personalized Secure Locks for Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-pedagogic-pros-the-finest-lecture-recording-devices-for-instructors/"><u>[New] Pedagogic Pros  The Finest Lecture Recording Devices for Instructors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-cooldown-chart-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-audio-subtitle-symphony-streamlining-prime-viewing-in-windows-11/"><u>Decoding Audio-Subtitle Symphony: Streamlining Prime Viewing in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/click-without-the-rush-learn-to-deactivate-mouse-acceleration-windows-style/"><u>Click Without the Rush: Learn to Deactivate Mouse Acceleration Windows Style</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-compreenas-guide-inserting-captions-into-mp4-files-2024/"><u>[Updated] Compreenas Guide  Inserting Captions Into MP4 Files 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-cash-creation-101-the-snapchat-edition/"><u>[New] 2024 Approved  Cash Creation 101  The Snapchat Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-laptop-onoff-trick-for-energy-conservation/"><u>Boost Your Laptop: On/Off Trick for Energy Conservation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-realme-narzo-60-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Realme Narzo 60 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harnessing-the-potential-of-quantum-hdr-imaging/"><u>In 2024, Harnessing the Potential of Quantum HDR Imaging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-what-sets-ai-hardware-on-a-distinct-path/"><u>Analyzing What Sets AI Hardware on a Distinct Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-how-to-remove-audio-from-avi/"><u>Updated How to Remove Audio From AVI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-proven-methods-to-perfectly-capture-iptv-broadcasts-for-2024/"><u>[New] Proven Methods to Perfectly Capture IPTV Broadcasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-direct-video-tweet-release-avoid-the-rt/"><u>[New] Direct Video Tweet Release  Avoid the 'RT'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-local-user-policies-a-guide-to-windows-11-and-11-systems/"><u>Adjusting Local User Policies: A Guide to Windows 11 & 11 Systems</u></a></li>
<li><a href="https://facebook.techidaily.com/dissecting-the-most-impactful-press-stories-of-google/"><u>Dissecting the Most Impactful Press Stories of Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-nostalgia-edition-revisiting-goofy-film/"><u>[Updated] The Nostalgia Edition  Revisiting Goofy Film</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-15-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 15 iOS System? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-is-monetization-a-feature-in-review-blogs/"><u>[Updated] Is Monetization a Feature in Review Blogs?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-oppo-f23-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Oppo F23 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-filter-mastery-essential-skills-for-2024/"><u>Instagram Filter Mastery - Essential Skills for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-trim-cut-and-edit-videos-for-free-no-watermarks-attached/"><u>New 2024 Approved Trim, Cut, and Edit Videos for Free No Watermarks Attached</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steam-cloud-connection-problems/"><u>Correcting Steam Cloud Connection Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/5-premier-free-tools-for-enhancing-your-vocal-range/"><u>5 Premier Free Tools for Enhancing Your Vocal Range</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-tecno-pova-5-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Tecno Pova 5?</u></a></li>
</ul></div>
