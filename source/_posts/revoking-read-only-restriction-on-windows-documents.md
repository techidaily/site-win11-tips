---
title: Revoking Read-Only Restriction on Windows Documents
date: 2024-12-30T00:22:54.651Z
updated: 2025-01-06T09:36:49.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Revoking Read-Only Restriction on Windows Documents
excerpt: This Article Describes Revoking Read-Only Restriction on Windows Documents
keywords: Remove Doc Read-Only Limit,Disable Doc Protection,End Doc Write Restrictions,Unlock Windows Doc Access,Lift Windows File Lockout,Eliminate Doc Read-Only,Release Doc Editability,Remove Doc Lockdown,Disable Read-Only Mode,Unlock File Editing,Lift Security Restrictions,Alter Permissions Windows,Ease Doc Access Control,Modify File Sharing Options
thumbnail: https://thmb.techidaily.com/3a086eb5f8446de2870210890acaafe476fc2c59adb7aa3e00420e9a95422cb6.jpg
---

## Revoking Read-Only Restriction on Windows Documents

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-building-brand-buzz-the-power-of-instagram-story-quizzes/"><u>[New] Building Brand Buzz The Power of Instagram Story Quizzes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-through-instagram-video-woes-with-ease-for-2024/"><u>[Updated] Navigating Through Instagram Video Woes with Ease for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/enhancing-your-computing-experience-bridging-airpods-with-personal-computers/"><u>Enhancing Your Computing Experience Bridging AirPods with Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-windows-users-chatgpt-application/"><u>Essential Steps for Windows Users: ChatGPT Application</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-advice-to-correct-microsoft-outlook-access-issues-efficiently/"><u>Expert Advice to Correct Microsoft Outlook Access Issues Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-audacity-paudio-glitches-in-windows-1011/"><u>Fixing Audacity PAudio Glitches in Windows 10/11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-xiaomi-redmi-a2plus-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Xiaomi Redmi A2+ Location on Skout | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/innovative-methods-to-log-gaming-sessions-for-2024/"><u>Innovative Methods to Log Gaming Sessions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/liberate-windows-talk-the-freedomgpt-way/"><u>Liberate Windows Talk: The FreedomGPT Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-new-additions-for-efficient-workflow-in-windows/"><u>Mastering New Additions for Efficient Workflow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-format-switches-from-word-docs-to-windows-11-pdfs/"><u>Optimizing File Format Switches: From Word Docs to Windows 11 PDFs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/proven-tactics-for-unblemished-image-sourcing/"><u>Proven Tactics for Unblemished Image Sourcing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taking-windows-next-discover-new-additions-in-update-wxx/"><u>Taking Windows Next: Discover New Additions in Update W.x.x</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-streamers-guide-to-selecting-a-peak-provider-for-2024/"><u>The Ultimate Streamer's Guide to Selecting a Peak Provider for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-10-and-11-efficiency-custom-keybindings-to-copy-text/"><u>Win 10 & 11 Efficiency: Custom Keybindings to Copy Text</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-store-fix-overcome-error-0x80072f17/"><u>Windows Store Fix: Overcome Error 0X80072F17</u></a></li>
<li><a href="https://techtrends.techidaily.com/your-complete-playstation-portal-guide-launch-date-cost-breakdown-hardware-info-and-where-to-shop/"><u>Your Complete PlayStation Portal Guide: Launch Date, Cost Breakdown, Hardware Info & Where to Shop</u></a></li>
</ul></div>

