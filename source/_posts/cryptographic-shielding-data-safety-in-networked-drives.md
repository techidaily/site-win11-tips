---
title: "Cryptographic Shielding: Data Safety in Networked Drives"
date: 2024-07-12T16:49:04.280Z
updated: 2024-07-13T16:49:04.280Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cryptographic Shielding: Data Safety in Networked Drives"
excerpt: "This Article Describes Cryptographic Shielding: Data Safety in Networked Drives"
keywords: Drive Encryption,Network Security,Crypto Protection,Safe Data Storage,Secure Drives,Digital Shielding,Cyber Safeguard
thumbnail: https://thmb.techidaily.com/c930e94b907356f9a15f0bf147840ab473cafcc143e2f86bb990ae121e306783.png
---

## Cryptographic Shielding: Data Safety in Networked Drives

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**diskmgmt.msc** in the text field and press**Enter** .
3. In the Disk Management window that opens, right-click on the drive you wish to hide and select**Change Drive Letter and Paths** .
4. Now, click the**Remove** button from the pop-up window.
5. Choose**Yes** when the warning message appears.  
![Hide a Drive Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-disk-management.jpg)

 Once you complete the above steps, your drive will no longer appear in File Explorer.

## 2\. Hide a Drive in Windows With Diskpart Command

 If you're a power user who prefers to make changes via the command-line interface, you can use the diskpart command to hide a drive on Windows. Fortunately, this isn't as intimidating as it might sound.

To hide a drive in Windows with Command Prompt, follow these steps:

1. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
2. Select**Yes** when the User Account Control (UAC) prompt shows up.
3. In the console, type**diskpart** and press**Enter** .
4. Input the following command in the console and press**Enter** to view a list of drives connected to your system:  
`list volume`  
![List of Drives in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/list-of-drives-in-command-prompt.jpg)
5. Note down the letter of the drive you want to hide from the**Ltr** column.
6. Type the following command to select your drive. Make sure you replace**X** in the command with the drive letter noted in the last step.  
`select volume X`
7. Lastly, run the following command to remove the drive letter and hide the volume.  
`remove letter X`  
![Hide a Drive Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-using-command-prompt.jpg)

 You should see a message that reads **Diskpart successfully removed the drive letter or mount point** . Following that, the drive will no longer appear on your PC.

 If you like using Command Prompt, why not check our guide on [how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

Here's what you need to do:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and click**OK** .
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > File Explorer** .
5. Double-click the**Hide these specified drives in My Computer** policy on your right.  
![Hide a Drive With Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-with-group-policy-editor.jpg)
6. Select the**Enabled** option.
7. Under**Options** , select the drive you want to hide.
8. Click**Apply** followed by**OK** .

 Once you complete the above steps, Windows will hide the specified drive from File Explorer. If you want to unhide the drive later, use the same steps and set the**Hide these specified drives in My Computer policy** to**Not configured** .

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful [not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you're done with that, use the following steps to hide a drive using Windows Registry:

1. Press**Win + S** to open the search menu.
2. Type**registry editor** in the box and select the first result that appears.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > Software > Microsoft > Windows > CurrentVersion > Policies > Explorer** .
5. Right-click on the**Explorer** key and go to**New** and select**DWORD (32-bit) Value** from the sub-menu.
6. Rename the DWORD to**NoDrives** .
7. Double-click the**NoDrives** DWORD.
8. In the**Edit DWORD (32-bit) Value** dialog box, select**Decimal** as the Base.  
![Hide a Drive via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/hide-a-drive-via-registry-editor.jpg)
9. Enter a number corresponding to the drive you want to hide in the**Value data** field and click**OK** . Refer to the table below to determine which number to use.  
![Drive Letter Refrence for Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/drive-letter-refrence-for-registry-editor.jpg)

 For instance, if you were to hide the**E:** drive from your computer, you'd enter**16** in the Value data field.

 You can also use this method to hide multiple drives at the same time. To do so, add the decimal numbers for both drives and enter the total in the Value data field. For example, if you're looking to hide drive**G:** and**H:** from your computer, you should enter**192** (64 + 128) in the Value data field.

 You'll have to restart your PC to apply the changes. Following that, the drive will not appear in File Explorer. You can undo the above changes at any point by deleting the**NoDrives** DWORD.

## Hiding Drives in Windows Is Easy

 Regardless of the method you use, hiding a drive on Windows is fairly simple and shouldn't take more than a few minutes.

 Alternatively, if you don't want to hide an entire drive, Windows also lets you hide specific files and folders in a few easy steps.


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
<li><a href="https://fox-blue.techidaily.com/2024-approved-transform-your-visuals-with-these-11-expert-strategies/"><u>2024 Approved  Transform Your Visuals with These 11 Expert Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-operation-of-microsofts-phone-link-app/"><u>Demystifying the Operation of Microsoft's 'Phone Link' App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-voice-your-message-on-discord-tts-essentials/"><u>[New] Voice Your Message on Discord  TTS Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-setting-powershell-policies/"><u>A Practical Approach to Setting PowerShell Policies</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-customization-increasing-icon-dimensions-in-w11/"><u>Winning at Customization: Increasing Icon Dimensions in W11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/uncovering-whatsapp-written-off-tricks-and-tips/"><u>Uncovering WhatsApp' Written Off Tricks and Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-historical-knowledge-at-your-fingertips-best-yt-history-channels/"><u>In 2024, Historical Knowledge at Your Fingertips  Best YT History Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-troubleshooting-for-elusive-temp-files/"><u>Windows Troubleshooting for Elusive Temp Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-reducing-excessive-background-load/"><u>Balancing Act: Reducing Excessive Background Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thriving-without-11-upgrade-boost-your-pc-health/"><u>Thriving Without 11 Upgrade: Boost Your PC Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-spoken-words-into-written-phrases-a-guide-for-windows-users/"><u>Turning Spoken Words Into Written Phrases: A Guide for Windows Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-take-it-upward-expert-techniques-for-phones/"><u>2024 Approved  Take It Upward  Expert Techniques for Phones</u></a></li>
<li><a href="https://video-capture.techidaily.com/decoding-fraps-video-capturing-techniques/"><u>Decoding Fraps Video Capturing Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rebuilding-windows-icons/"><u>Strategies for Rebuilding Windows Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-address-unsuccessful-onedrive-procedures/"><u>Strategies to Address Unsuccessful OneDrive Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-win11-ui-with-enlarged-icons/"><u>Transform Your Win11 UI with Enlarged Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-error-0x00000709/"><u>Steps to Rectify Error 0X00000709</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resolve-the-blue-screen-error-code-0x8007007e/"><u>Strategies to Resolve the Blue Screen Error: Code 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-torrent-clients-for-windows/"><u>The 5 Best Torrent Clients for Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-avoid-boredom-learn-to-shuffle-youtube-lists/"><u>[Updated] 2024 Approved  Avoid Boredom  Learn to Shuffle YouTube Lists</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-step-by-step-guide-to-designing-impactful-imagery/"><u>2024 Approved  Step-by-Step Guide to Designing Impactful Imagery</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-social-media-spotlight-top-twitters-for-2024/"><u>[Updated] Social Media Spotlight  Top Twitters for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-full-potential-of-the-windows-key/"><u>Unlocking Full Potential of the Windows Key</u></a></li>
<li><a href="https://extra-information.techidaily.com/accelerated-conversion-guide-from-complex-srt-to-txt-2023-for-2024/"><u>Accelerated Conversion Guide  From Complex SRT to TXT 2023 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-for-fine-tuning-windows-11-installation/"><u>The Ultimate Checklist for Fine-Tuning Windows 11 Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-activate-educational-themes/"><u>Win 11: Activate Educational Themes</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/enhancing-audacitys-capabilities-installation-of-the-lame-mp3-encoder/"><u>Enhancing Audacitys Capabilities Installation of the Lame MP3 Encoder</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Vivo Y100 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-youtube-watch-on-chrome-windows/"><u>Accelerate Your YouTube Watch on Chrome Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reactivate-deactivated-windows-email-rule-settings/"><u>Steps to Reactivate Deactivated Windows Email Rule Settings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-in-depth-look-at-fraps-screen-capture/"><u>In 2024, In-Depth Look at Fraps Screen Capture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298672852-leveraging-local-links-to-global-drives-dropbox-and-googledrive-via-c/"><u>Leveraging Local Links to Global Drives: Dropbox & GoogleDrive via C:</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/navigating-the-download-of-auditory-broadcasts-on-home-computers-for-2024/"><u>Navigating the Download of Auditory Broadcasts on Home Computers for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/maximize-screen-time-top-10-free-youtube-playlist-extractors/"><u>Maximize Screen Time  Top 10 Free YouTube Playlist Extractors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-boosting-yield-strategies-for-successful-money-making-on-mobile-youtube/"><u>[New] 2024 Approved  Boosting Yield  Strategies for Successful Money-Making on Mobile YouTube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-remove-images-background-in-canva/"><u>How to Remove Image's Background In Canva</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-trio-top-apps-making-pc-switch-easier/"><u>Transition Trio: Top Apps Making PC Switch Easier</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/5-ways-to-transfer-music-from-apple-iphone-13-pro-max-to-android-drfone-by-drfone-transfer-from-ios/"><u>5 Ways to Transfer Music from Apple iPhone 13 Pro Max to Android | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719341208077-pause-on-snipwise-discover-fixes-today-here/"><u>Pause on SnipWise? Discover Fixes Today, Here</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-download-youtube-responsibly-legal-mp4-conversion-methods-for-2024/"><u>[New] Download YouTube Responsibly  Legal MP4 Conversion Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unlocking-screen-pin-free-windows-projection/"><u>Stop Unlocking Screen: PIN-Free Windows Projection</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-honor-play-40c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Honor Play 40C | Dr.fone</u></a></li>
</ul></div>
