---
title: "Adjusting Windows Files: Write Access No More Restrictions"
date: 2024-07-12T17:25:15.548Z
updated: 2024-07-13T17:25:15.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adjusting Windows Files: Write Access No More Restrictions"
excerpt: "This Article Describes Adjusting Windows Files: Write Access No More Restrictions"
keywords: Windows File Permissions,Disable Write Access,Windows Security Lockdown,Editing Files Restricted,Remove Write Loss,Permissions No More,Windows Read-Only Mode
thumbnail: https://thmb.techidaily.com/ebbfd91fc57bf5ea9818d4e87d8cfd35544a71921ce7ca73b2986ee75e83dd45.jpg
---

## Adjusting Windows Files: Write Access No More Restrictions

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
<li><a href="https://fox-http.techidaily.com/2024-approved-select-the-best-cameras-beyond-your-gopro-companion/"><u>2024 Approved  Select the Best Cameras Beyond Your GoPro Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-surface-laptop-go-3-gains-processor-yet-fails-to-shine/"><u>Microsoft's Surface Laptop Go 3 Gains Processor, Yet Fails to Shine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-security-top-5-fixes-for-access-denied-errors/"><u>Mastering Windows 11 Security: Top 5 Fixes for Access Denied Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-0x00000709-operation-could-not-be-completed-on-windows/"><u>How to Fix Error 0X00000709: Operation Could Not Be Completed on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fix-geforce-experience-on-windows-pcs/"><u>Quick Guide to Fix GeForce Experience on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-movement-eradicate-slowness-on-sw-battlefront-windows/"><u>Master Movement: Eradicate Slowness on SW Battlefront Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-expert-tips-on-tracking-your-videos-view-counts-and-earnings-potential/"><u>In 2024, Expert Tips on Tracking Your Video's View Counts & Earnings Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-files-optimizing-drives-defrag-for-win11-users/"><u>Organizing Files, Optimizing Drives: Defrag for Win11 Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-merging-melodies-the-art-of-crossfading-for-2024/"><u>[New] Merging Melodies  The Art of Crossfading for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-pc-essential-free-tools-for-win11-users/"><u>Mastering Your PC: Essential Free Tools for Win11 Users</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-create-a-stunning-video-montage-a-step-by-step-guide/"><u>New Create a Stunning Video Montage A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harness-the-virtual-world-with-hyper-v-in-windows-11/"><u>Harness the Virtual World with Hyper-V in Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-redmi-note-12-pro-4g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Redmi Note 12 Pro 4G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/limiting-users-ability-to-modify-windows-safescreen/"><u>Limiting Users' Ability to Modify Windows SafeScreen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/money-making-tactics-from-the-w11-windowware/"><u>Money-Making Tactics From the W11 Windowware</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-samsung-galaxy-a15-4g-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Samsung Galaxy A15 4G?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-make-your-windows-11-unique/"><u>Innovative Ways to Make Your Windows 11 Unique</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-outlook-and-gmail-synergy-on-your-pc/"><u>Mastering Outlook & Gmail Synergy on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/map-screenshot-archives-in-windows/"><u>Map Screenshot Archives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/learn-and-apply-techniques-for-lockunlock-fn-button/"><u>Learn & Apply Techniques for Lock/Unlock Fn Button</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-pick-for-pen-notes-7-ultimate-windows-apps/"><u>Prime Pick for Pen Notes: 7 Ultimate Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-old-user-id-prompt-in-windows-login-screen/"><u>How to Disable 'Old User ID' Prompt in Windows Login Screen</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-skyeconomys-haven-budget-friendly-large-data-space/"><u>[New] In 2024, SkyEconomy's Haven  Budget-Friendly Large Data Space</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-free-or-paid-the-complete-guide-to-joining-disconitro/"><u>[New] Free or Paid? The Complete Guide to Joining DiscoNitro</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-fine-tuning-filmic-soundtracks-integrating-music-into-your-video-projects-in-premiere-pro/"><u>New In 2024, Fine-Tuning Filmic Soundtracks Integrating Music Into Your Video Projects in Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-network-issues-a-comprehensible-guide-for-windows-11-users/"><u>Navigating Network Issues: A Comprehensible Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/monetization-approaches-for-microsoft-and-windows-11/"><u>Monetization Approaches for Microsoft & Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-ten-essential-cam-covers-to-upgrade-your-security/"><u>[New] 2024 Approved  Ten Essential Cam Covers to Upgrade Your Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-store-faults-rectify-error-0x80072f17/"><u>Mending Windows Store Faults: Rectify Error 0X80072f17</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-streamline-your-life-quick-tips-to-beginning-on-discord-broadcasts/"><u>[Updated] 2024 Approved  Streamline Your Life  Quick Tips to Beginning on Discord Broadcasts</u></a></li>
</ul></div>
