---
title: "Unlocking Files in Windows: No More Read-Only Limit"
date: 2024-08-23T07:02:24.111Z
updated: 2024-08-24T07:02:24.111Z
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

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

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

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-igtv-content-size-requirements/"><u>[New] 2024 Approved  IGTV Content Size Requirements</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-correct-obs-blackout-error-in-gaming-capture/"><u>[New] Correct OBS Blackout Error in Gaming Capture</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-turbocharge-touch-ups-learn-speedy-skills-for-win10-photos-editing/"><u>[New] In 2024, Turbocharge Touch-Ups  Learn Speedy Skills for WIN10 Photos Editing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-superior-suggestions-prime-platforms-for-grabbing-snapalert-rhythms/"><u>[Updated] Superior Suggestions  Prime Platforms for Grabbing SnapAlert Rhythms</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-a-spectrum-of-excellence-top-5-tvs-for-grading-mastery/"><u>2024 Approved  A Spectrum of Excellence  Top 5 TVs for Grading Mastery</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-ultimate-playlist-15-ways-to-revamp-a-live-stream/"><u>2024 Approved  The Ultimate Playlist  15 Ways to Revamp a Live Stream</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-iphone-se-2022-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On iPhone SE (2022) How to Bypass?</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-from-iphone-15-plus-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock From iPhone 15 Plus? How to Fix it?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensively-integrating-dolby-atmos-into-windows-1111/"><u>Comprehensively Integrating Dolby Atmos Into Windows 11/11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/detailed-steps-to-using-azure-speech-recognition/"><u>Detailed Steps to Using Azure Speech Recognition</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-your-epson-xp-440-printer-driver-with-simple-steps/"><u>Download and Update Your Epson XP-440 Printer Driver with Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-steps-for-altering-windows-pin/"><u>Efficient Steps for Altering Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-device-efficiency-surface-computers-firmware-update-processes/"><u>Enhancing Device Efficiency: Surface Computers' Firmware Update Processes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-itel-a70-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Itel A70</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-overcoming-microsoft-store-crashes-0x80073d26-fix/"><u>Guide to Overcoming Microsoft Store Crashes: 0X80073D26 Fix</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-download-and-install-the-newest-amd-radeon-r5-drivers-on-your-windows-pc/"><u>How to Download and Install the Newest AMD Radeon R5 Drivers on Your Windows PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-itel-p55plus-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Itel P55+ Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-mouse-acceleration-in-windows-11-and-11/"><u>How to Turn Off Mouse Acceleration in Windows 11 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-3-ways-of-how-to-get-someones-apple-id-off-apple-iphone-6s-plus-without-password-by-drfone-ios/"><u>In 2024, 3 Ways of How to Get Someones Apple ID Off Apple iPhone 6s Plus without Password</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-on-your-apple-iphone-13-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID On Your Apple iPhone 13</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-6s-plus-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 6s Plus Passcode without Computer?</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-art-of-iphone-hdr-photo-perfection/"><u>In 2024, The Art of iPhone HDR Photo Perfection</u></a></li>
<li><a href="https://buynow-info.techidaily.com/inexpensive-tp-link-re180-ax700-wireless-signal-enhancer-overview-and-test-results/"><u>Inexpensive TP-Link RE180 AX700 Wireless Signal Enhancer Overview and Test Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-github-desktops-potential-on-windows-devices/"><u>Leveraging GitHub Desktop's Potential on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-basics-starting-microsoft-paint-in-windows-11/"><u>Mastering the Basics: Starting Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-brighten-up-dark-windows-display/"><u>Methods to Brighten Up Dark Windows Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-energy-spike-during-intense-gaming-on-windows/"><u>Minimizing Energy Spike During Intense Gaming on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-invisible-displays-at-os-ignition/"><u>Overcoming Invisible Displays at OS Ignition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-windows-transformers-for-video-files/"><u>Perfect Windows Transformers for Video Files</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/piecing-together-an-epic-tiktok-conclusion-for-2024/"><u>Piecing Together an Epic TikTok Conclusion for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigning-in-the-chaos-five-ways-to-tackle-no-mail-in-windows-11-mail-app/"><u>Reigning in the Chaos: Five Ways to Tackle No Mail in Windows 11 Mail App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-deleted-default-energy-management-in-win-11/"><u>Reinstating Deleted Default Energy Management in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/relocating-qbittorrent-on-windows-a-comprehensive-instructional-walkthrough/"><u>Relocating qBittorrent on Windows: A Comprehensive Instructional Walkthrough</u></a></li>
<li><a href="https://extra-skills.techidaily.com/restore-pristine-photos-easily-discover-top-10-online-enhancers-for-2024/"><u>Restore Pristine Photos Easily  Discover Top 10 Online Enhancers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-the-reset-account-lockout-after-incorrect-passwords-on-windows-11/"><u>Revamping the Reset Account Lockout After Incorrect Passwords on Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solve-call-of-duty-warzone-no-match-found-problems-on-windows-computers/"><u>Solve 'Call of Duty Warzone' No Match Found Problems on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-office-tasks-with-powerful-windows-shortcuts/"><u>Speed Up Office Tasks With Powerful Windows Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-uninstall-strategies-personalizing-the-win-1110-menu/"><u>Speedy Uninstall Strategies: Personalizing the Win 11/10 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-windows-admin-centrally-managed-errors/"><u>Strategies to Overcome Windows' Admin-Centrally-Managed Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-repair-non-responsive-installation-of-ccleaner-on-win1011/"><u>Strategies to Repair Non-Responsive Installation of CCleaner on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-endless-unlocked-windows-experience/"><u>Tips for Endless Unlocked Windows Experience</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-7-downfalls-of-implementing-generative-ai-technology-in-chat-platforms/"><u>Top 7 Downfalls of Implementing Generative AI Technology in Chat Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfreezing-frozen-windows-run-logs/"><u>Unfreezing Frozen Windows Run Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-and-resolving-entry-not-found-error/"><u>Unveiling and Resolving 'Entry Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-truth-how-to-detect-your-hard-drivessd-status-in-windows/"><u>Unveiling the Truth: How to Detect Your Hard Drive/SSD Status in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-windows-11-s-mode-and-should-you-use-it/"><u>What Is Windows 11 S Mode, and Should You Use It?</u></a></li>
</ul></div>
