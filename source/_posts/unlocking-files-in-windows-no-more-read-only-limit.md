---
title: "Unlocking Files in Windows: No More Read-Only Limit"
date: 2024-12-07T18:56:56.755Z
updated: 2024-12-13T02:20:59.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Files in Windows: No More Read-Only Limit"
excerpt: "This Article Describes Unlocking Files in Windows: No More Read-Only Limit"
keywords: Unlock File Access,Remove RWLimit,Bypass Read-Only,Windows File Edit,Disable File Locks,Windows Freeze Files,Edit Files Windows
thumbnail: https://thmb.techidaily.com/61e5e75a143019f7f7c8689be3de97fce55d395ac791171ba491fd10d2883ba4.jpeg
---

## Unlocking Files in Windows: No More Read-Only Limit

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-influencing-up-a-comprehensive-instagram-growth-strategy/"><u>[New] 2024 Approved Influencing Up A Comprehensive Instagram Growth Strategy</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-dynamic-images-made-simple-in-illustrator/"><u>[New] In 2024, Dynamic Images Made Simple in Illustrator</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-15-best-funny-youtube-channels-to-watch-when-youre-bored/"><u>[Updated] 15 Best Funny YouTube Channels to Watch When You're Bored</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-watch-deleted-youtube-videos-online-in-2-ways/"><u>[Updated] In 2024, How to Watch Deleted YouTube Videos Online in 2 Ways</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-the-metaverse-6-compelling-realities-unveiled/"><u>2024 Approved Understanding the Metaverse 6 Compelling Realities Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-lifetime-deal-get-612-on-black-friday-for-win10-life/"><u>Exclusive Lifetime Deal: Get $6.12 on Black Friday for Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-offer-612-annual-win10-just-for-you/"><u>Exclusive Offer: $6.12 Annual Win10 - Just for You</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/five-superior-timelapse-filmmakers/"><u>Five Superior Timelapse Filmmakers</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722890290958-get-ready-for-macos-15-sequoia-coming-soon-with-exciting-new-features/"><u>Get Ready for MacOS 15 Sequoia: Coming Soon with Exciting New Features!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-align-your-windows-id-with-microsoft-accounts/"><u>How to Align Your Windows ID with Microsoft Accounts</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-commands-accelerated-translation-on-windows-11-devices/"><u>Keyboard Commands: Accelerated Translation on Windows 11 Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-samsung-galaxy-s23-fe-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Samsung Galaxy S23 FE? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-malfunctioning-ccleaner-in-win11/"><u>Mending Malfunctioning CCleaner in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-integrating-intels-network-devices-on-os-x/"><u>Quick Guide: Integrating Intel's Network Devices on OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reacquiring-your-windows-11-pin-a-fix-guide/"><u>Reacquiring Your Windows 11 PIN: A Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-concealingdisplaying-firewall-zones/"><u>Windows Security: Concealing/Displaying Firewall Zones</u></a></li>
</ul></div>

