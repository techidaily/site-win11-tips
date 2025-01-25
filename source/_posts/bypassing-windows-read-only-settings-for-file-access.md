---
title: Bypassing Windows Read-Only Settings for File Access
date: 2025-01-22T20:49:22.020Z
updated: 2025-01-25T00:37:52.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows Read-Only Settings for File Access
excerpt: This Article Describes Bypassing Windows Read-Only Settings for File Access
keywords: Bypass ROD,Win READONLY,Unlock File Windows,Read-Only Access Bypass,Override ROD Settings,Windows READONLY Fix,File Unblocking Windows
thumbnail: https://thmb.techidaily.com/425081092e1a679d02f1bd0f9b8040f12a7c3e9a90f0ca40e490e9a1586e5331.jpg
---

## Bypassing Windows Read-Only Settings for File Access

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-enhancing-detail-in-minecraft-worlds/"><u>[New] In 2024, Enhancing Detail in Minecraft Worlds</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-professionally-speaking-the-top-5-drone-recommendations/"><u>[Updated] 2024 Approved Professionally Speaking The Top 5 Drone Recommendations</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-stay-ahead-of-the-curve-top-task-filled-ideas-for-maximizing-your-podcast-experience/"><u>[Updated] In 2024, Stay Ahead of the Curve Top Task-Filled Ideas for Maximizing Your Podcast Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-display-quality-with-windows-11s-auto-hdr/"><u>Elevating Display Quality with Windows 11'S Auto HDR</u></a></li>
<li><a href="https://blog-min.techidaily.com/fa-langtan-till-dig-3-effektera-for-vidkompression-for-instagram-guiden-av-movavi/"><u>Få Längtan Till Dig: 3 Effektera För Vidkompression För Instagram - Guiden Av Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovate-your-workspace-learn-how-to-customize-windows-using-winbubble/"><u>Innovate Your Workspace: Learn How to Customize Windows Using WinBubble</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ios-18-update-brings-crucial-new-message-security-enhancement-to-your-iphone-not-powered-by-artificial-intelligence-tech-news/"><u>IOS 18 Update Brings Crucial New Message Security Enhancement to Your iPhone – Not Powered by Artificial Intelligence | Tech News</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/mastering-meeting-media-converting-gotomeeting-files-g2m-into-various-video-formats-including-mp4-mov-and-wmv/"><u>Mastering Meeting Media: Converting GoToMeeting Files (G2M) Into Various Video Formats Including MP4, MOV, and WMV</u></a></li>
<li><a href="https://win-special.techidaily.com/protecting-virtual-environments-a-comprehensive-tutorial-on-vm-security-through-encryption/"><u>Protecting Virtual Environments: A Comprehensive Tutorial on VM Security Through Encryption</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-utilizing-lav-filters-for-optimized-windows-performance/"><u>The Art of Utilizing LAV Filters for Optimized Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-rejuvenate-stuck-hibernate-mode-on-pcs/"><u>Tips to Rejuvenate Stuck Hibernate Mode on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-context-menu-into-a-god-mode-hub/"><u>Transform Context Menu Into a God Mode Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-ai-via-vivetool-instructions/"><u>Unlock Windows AI via ViveTool Instructions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-reno-9a-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo Reno 9A Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-fixes-for-easing-up-locked-software-installation-checks/"><u>Win Fixes for Easing Up Locked Software Installation Checks</u></a></li>
</ul></div>

