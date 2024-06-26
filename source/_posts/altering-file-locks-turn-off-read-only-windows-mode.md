---
title: "Altering File Locks: Turn Off Read-Only Windows Mode"
date: 2024-06-25T16:22:53.000Z
updated: 2024-06-26T16:22:53.000Z
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
<li><a href="https://win11-tips.techidaily.com/the-mechanism-behind-windows-sound-graph-isolation/"><u>The Mechanism Behind Windows Sound Graph Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-faulty-resource-monitors-on-windows-11/"><u>Resetting Techniques for Faulty Resource Monitors on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-language-skills-quick-translate-via-windows-key-combinations/"><u>Elevate Language Skills: Quick Translate via Windows Key Combinations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-the-red-x-its-role-in-file-system-navigation/"><u>Explaining the Red “X”: Its Role in File System Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-qt-plugin-during-software-application-initiation/"><u>Overcoming Missing Qt Plugin During Software Application Initiation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-windows-issue-file-explorer-failsafe-mode/"><u>Solve Windows Issue: File Explorer Failsafe Mode</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-enhanced-video-calls-innovative-approaches-4/"><u>[Updated] Enhanced Video Calls  Innovative Approaches #4</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-x-fold-2-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo X Fold 2 Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unbeatable-candidates-the-very-best-phones-at-video-recording/"><u>[New] Unbeatable Candidates  The Very Best Phones at Video Recording</u></a></li>
<li><a href="https://extra-resources.techidaily.com/9-techniques-for-attractive-and-engaging-unboxings-on-instagram/"><u>9 Techniques for Attractive and Engaging Unboxings on Instagram</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-calculate-timecodes-like-a-pro-9-essential-tools/"><u>New 2024 Approved Calculate Timecodes Like a Pro 9 Essential Tools</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-meizu-21-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prestigious-top-8-sites-combining-vivid-3d-graphics-and-luxe-text/"><u>Prestigious Top 8 Sites Combining Vivid 3D Graphics & Luxe Text</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-visual-power-in-gaming-channels-a-template-guidebook/"><u>In 2024, Visual Power in Gaming Channels  A Template Guidebook</u></a></li>
</ul></div>
