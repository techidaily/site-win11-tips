---
title: "Adjusting Windows Files: Write Access No More Restrictions"
date: 2024-06-25T16:54:17.945Z
updated: 2024-06-26T16:54:17.945Z
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
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80073cf3-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error Code 0X80073CF3 in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/put-a-halt-on-application-start-tracking-in-windows/"><u>Put a Halt on Application Start-Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ascertain-hdd-or-ssd-through-windows-settings/"><u>Ascertain HDD or SSD Through Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-store-error-with-xbox-games/"><u>Troubleshooting Windows Store Error with Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-storage-demands-on-windows-os/"><u>Decoding the Storage Demands on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-webp-visualization-with-these-excellent-tools/"><u>Enhance WebP Visualization with These Excellent Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-windows-display-embrace-wmfresh-look/"><u>Transform Windows Display: Embrace WMFresh Look</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-a-compre-written-in-the-stars-how-to-choose-an-ideal-podcast-title/"><u>[New] A Compre Written in the Stars  How to Choose an Ideal Podcast Title</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-ultimate-guide-to-recording-video-without-auditory-disruption/"><u>[New] 2024 Approved  The Ultimate Guide to Recording Video without Auditory Disruption</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-skincare-secrets-for-success/"><u>2024 Approved  Skincare Secrets for Success</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-top-5-digital-audio-organizers-for-seamless-mp3-management/"><u>2024 Approved Top 5 Digital Audio Organizers for Seamless MP3 Management</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-realme-c53mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Realme C53Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-masterpiece-maker-top-free-editors-for-android-devices/"><u>[Updated] Masterpiece Maker  Top Free Editors for Android Devices</u></a></li>
<li><a href="https://extra-information.techidaily.com/hue-alignment-assistant/"><u>Hue Alignment Assistant</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-channel-growth-on-a-dime-attracting-sponsors-with-simplicity/"><u>[Updated] 2024 Approved  Channel Growth on a Dime  Attracting Sponsors with Simplicity</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-shoot-spectaculr-igtv-videos-using-smartphonedlsr-cameras/"><u>[Updated] In 2024, How to Shoot Spectaculr IGTV Videos Using Smartphone/DLSR Cameras</u></a></li>
</ul></div>
