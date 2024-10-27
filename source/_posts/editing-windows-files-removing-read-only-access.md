---
title: "Editing Windows Files: Removing Read-Only Access"
date: 2024-10-23T18:03:39.842Z
updated: 2024-10-26T18:00:31.595Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Editing Windows Files: Removing Read-Only Access"
excerpt: "This Article Describes Editing Windows Files: Removing Read-Only Access"
keywords: Remove Read-Only Windows,Edit File Permissions,Unlock Windows Files,Disable RW Access,Modify Windows File Rights,Change File Read-Only Status,Delete RW Lock Windows
thumbnail: https://thmb.techidaily.com/6afde60cdf2c4ed08818a0c3bb279e1893a9ceb4675945a4f5d57ab92e9d6ef9.jpg
---

## Editing Windows Files: Removing Read-Only Access

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-help.techidaily.com/new-indulge-in-9-holiday-blockbusters-free-online-christmas-viewing/"><u>[New] Indulge in 9 Holiday Blockbusters Free Online Christmas Viewing</u></a></li>
<li><a href="https://article-files.techidaily.com/new-transform-into-a-metaverse-virtuoso-essential-tools-list-for-2024/"><u>[New] Transform Into a Metaverse Virtuoso - Essential Tools List for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-bite-sized-video-knowledge-now/"><u>[Updated] In 2024, Bite-Sized Video Knowledge Now!</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-enriched-video-presentation-implementing-lc-and-bb-on-social-platforms/"><u>2024 Approved Enriched Video Presentation Implementing LC and BB on Social Platforms</u></a></li>
<li><a href="https://extra-tips.techidaily.com/360-video-stitching-tips-how-to-stitch-gopro-clips-into-360-videos/"><u>360 Video Stitching Tips How to Stitch GoPro Clips Into 360 Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-wasted-space-in-windows-with-temp-file-fixes/"><u>Eliminate Wasted Space in Windows with Temp File Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-permanent-deletion-of-files-with-desktop-trash-on-windows-11/"><u>Ensuring Permanent Deletion of Files with Desktop Trash on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-iphone-skills-photo-resizing-guide/"><u>Essential iPhone Skills Photo Resizing Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-google-pixel-fold-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Google Pixel Fold Phone | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-zte-axon-40-lite-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your ZTE Axon 40 Lite via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x8007000f-on-running-tasks/"><u>Resolving Error Code 0X8007000F on Running Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-lost-visual-function-in-overwatch-2-on-windows/"><u>Restoring Lost Visual Function in Overwatch 2 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-windows-update-error-codes/"><u>Steps to Overcome Windows Update Error Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-halt-windows-pcs-from-booting-bios-mode/"><u>Strategies to Halt Windows PCs From Booting BIOS Mode</u></a></li>
</ul></div>

