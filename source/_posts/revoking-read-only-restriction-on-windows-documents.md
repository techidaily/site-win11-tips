---
title: Revoking Read-Only Restriction on Windows Documents
date: 2024-08-08T11:13:16.356Z
updated: 2024-08-09T11:13:16.356Z
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

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-curb-automated-youtube-content-feeds/"><u>[New] 2024 Approved  Curb Automated YouTube Content Feeds</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-review-magix-video-edit-suite/"><u>[New] Review  MAGIX Video Edit Suite</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtube-to-animated-gifs-conversion-guide-online-tutorial-for-success/"><u>[New] Youtube to Animated GIFs Conversion Guide  Online Tutorial for Success</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723007487653-solved-nba-2k20-crash-issue-quickly-and-easily/"><u>[SOLVED] NBA 2K20 Crash Issue | Quickly & Easily!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-precision-timing-crafting-your-ideal-video-conference/"><u>[Updated] 2024 Approved  Precision Timing  Crafting Your Ideal Video Conference</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-video-flexibility-unleashed-5-powerful-online-methods-to-edit-videos-on-vimeo/"><u>[Updated] 2024 Approved  Video Flexibility Unleashed  5 Powerful Online Methods to Edit Videos on Vimeo</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-define-new-destination-for-mac-screenshots/"><u>[Updated] Define New Destination for Mac Screenshots</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-enjoy-every-goal-the-free-football-broadcast-guide/"><u>[Updated] How to Enjoy Every Goal  The FREE Football Broadcast Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-a-visual-marvel-unveiled-eizos-coloredge-cg318-4k-reviewed/"><u>2024 Approved  A Visual Marvel Unveiled  EIZO's ColorEdge CG318-4K Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-fresh-perspective-key-modifications-in-windows-11-marketplace/"><u>A Fresh Perspective: Key Modifications in Windows 11' Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-focus-and-time-management-best-rated-windows-pomodoro-apps/"><u>Boost Your Focus and Time Management: Best-Rated Windows Pomodoro Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-mold-reinventing-yourself-with-a-new-username-in-windows-11/"><u>Breaking the Mold: Reinventing Yourself with a New UserName in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clarifying-auditory-data-handling-wasd-in-windows-os/"><u>Clarifying Auditory Data Handling: WASD in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-linking-drives-on-new-windows-version/"><u>Efficiently Linking Drives on New Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-keys-to-unlocking-email-access-issues-in-windows-11-mail-service/"><u>Five Keys to Unlocking Email Access Issues in Windows 11 Mail Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonstop-techsign-in-issues-in-ms-teams-windows/"><u>Fixing Nonstop TechSign In Issues in MS Teams Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-the-power-button-from-the-start-menu-on-windows-11-and-11/"><u>How to Hide the Power Button From the Start Menu on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-the-forgotten-windows-start-menu/"><u>How to Reactivate the Forgotten Windows Start Menu</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-motorola-moto-g13-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Motorola Moto G13 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-the-pulse-of-internet-stability-at-work/"><u>Keeping the Pulse of Internet Stability at Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leading-the-way-in-qr-decoding-with-your-windows-machine/"><u>Leading the Way in QR Decoding with Your Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-the-power-of-combined-android-and-windows-11-displays/"><u>Leveraging the Power of Combined Android & Windows 11 Displays</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-tackle-non-responsive-function-keys-for-brighness-on-windows-11/"><u>Methods to Tackle Non-Responsive Function Keys for Brighness on Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-the-ultimate-list-of-free-video-editing-software-for-newcomers/"><u>New 2024 Approved The Ultimate List of Free Video Editing Software for Newcomers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-microsoft-store-crash-code-error-0x80072efd/"><u>Swift Fixes for Microsoft Store Crash Code Error 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-steam-disk-write-failures-effectively/"><u>Tackling Windows Steam Disk Write Failures Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-uninstall-guide-enhancing-your-workflow-in-windows/"><u>The Ultimate Uninstall Guide: Enhancing Your Workflow in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-game-pass-error-code-0x00000001-on-windows-os/"><u>Troubleshooting Xbox Game Pass Error Code 0X00000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-with-ease-a-guide-for-surface-computer-owners/"><u>Update with Ease: A Guide for Surface Computer Owners</u></a></li>
</ul></div>
