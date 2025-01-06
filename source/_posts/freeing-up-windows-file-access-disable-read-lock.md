---
title: "Freeing Up Windows File Access: Disable Read-Lock"
date: 2025-01-04T04:33:41.021Z
updated: 2025-01-05T17:29:58.803Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Freeing Up Windows File Access: Disable Read-Lock"
excerpt: "This Article Describes Freeing Up Windows File Access: Disable Read-Lock"
keywords: Free File Locks,Disable File Access,Unlock Windows Files,Remove Read Lock,Optimize File Access,Eliminate File Lock,Windows File Permission
thumbnail: https://thmb.techidaily.com/e7b26cce85084898820694a03b988f46853880c83b86563e047e92a3e8096101.jpg
---

## Freeing Up Windows File Access: Disable Read-Lock

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-achieving-professional-audio-in-home-recording-studios/"><u>[Updated] 2024 Approved Achieving Professional Audio in Home Recording Studios</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-pioneering-pathways-in-virtual-reality-biking/"><u>[Updated] In 2024, Pioneering Pathways in Virtual Reality Biking</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-innovating-your-way-through-tiktok-the-power-of-templated-content-for-2024/"><u>[Updated] Innovating Your Way Through TikTok The Power of Templated Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reintroduce-blocked-app-in-os/"><u>How to Reintroduce Blocked App in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-oversaturated-color-from-laptop-display/"><u>How to Remove Oversaturated Color From Laptop Display</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-unlock-iphone-15-plus-without-passcode-or-face-id-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock iPhone 15 Plus without Passcode or Face ID | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-lava-blaze-curve-5g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Lava Blaze Curve 5G</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/integrating-third-party-tools-with-your-win11-zoom-setup-for-2024/"><u>Integrating Third-Party Tools with Your Win11 Zoom Setup for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-tackling-windows-steam-restrictions/"><u>Mastery in Tackling Windows' Steam Restrictions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-data-storage-utilizing-diskusage-command-proficiency/"><u>Mastery Over Data Storage: Utilizing DiskUsage Command Proficiency</u></a></li>
<li><a href="https://tech-hub.techidaily.com/politeness-in-the-age-of-ai-engaging-with-gpt-alexa-and-more/"><u>Politeness in the Age of AI: Engaging with GPT, Alexa & More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-icons-a-quick-guide/"><u>Realigning Windows Icons: A Quick Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/techniques-for-swift-deletion-of-facebook-stories/"><u>Techniques for Swift Deletion of Facebook Stories</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleash-creativity-complimentary-premiere-pro-toolset/"><u>Unleash Creativity - Complimentary Premiere Pro Toolset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-setup-from-iso-file-to-operational-system/"><u>Windows 11 ARM Setup: From ISO File to Operational System</u></a></li>
</ul></div>

