---
title: "Silent Data Exchange: Safeguarding Files Across WS11/W10"
date: 2024-07-12T17:09:13.913Z
updated: 2024-07-13T17:09:13.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Silent Data Exchange: Safeguarding Files Across WS11/W10"
excerpt: "This Article Describes Silent Data Exchange: Safeguarding Files Across WS11/W10"
keywords: Silent File Transfer,Secure Data Sync,Cross-Version Safe Share,WS11/W10 Files Protection,Stealthy Data Sharing,WS/WX Compatible Exchange,Encrypted File Transferring
thumbnail: https://thmb.techidaily.com/d91a8e4d3e328994798cbf4d4f5c1573225bbff13640403fc40b5c32e2b3cd22.jpg
---

## Silent Data Exchange: Safeguarding Files Across WS11/W10

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
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-11-pro-to-an-older-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 11 Pro to an Older Version? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-picturesegment-appraisal/"><u>[Updated] 2024 Approved  PictureSegment Appraisal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-volume-shadow-copy-on-pcs/"><u>Addressing Disabled Volume Shadow Copy on PCs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-make-the-most-of-your-youtube-watches-gif-magic-for-devices-for-2024/"><u>[New] How to Make the Most of Your YouTube Watches  GIF Magic for Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-gmail-to-windows-outlook-seamless-integration-method/"><u>Adding Gmail to Windows Outlook: Seamless Integration Method</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-no-connected-systems-error-windows/"><u>Addressing No Connected Systems Error Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-savvy-seekers-guide-to-spotting-superb-photos-on-pexels-for-2024/"><u>The Savvy Seeker's Guide to Spotting Superb Photos on Pexels for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-pitfalls-going-for-low-cost-windows-license-keys/"><u>8 Pitfalls: Going for Low-Cost Windows License Keys</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-change-boot-menu-timeout-in-windows-11/"><u>4 Ways to Change Boot Menu Timeout in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-network-disconnect-in-windows-11-a-step-by-step-guide/"><u>Addressing Network Disconnect in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719309481571-streamline-non-responsive-shift-in-windows/"><u>Streamline Non-Responsive Shift in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/get-your-printer-back-in-action-on-windows-11/"><u>Get Your Printer Back in Action on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-10-step-guide-to-windows-health-reports/"><u>A 10-Step Guide to Windows Health Reports</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/must-play-openworld-experiences/"><u>Must-Play Openworld Experiences</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-top-picks-essential-tools-to-play-ps1-games-on-your-computer/"><u>[Updated] In 2024, Top Picks - Essential Tools to Play PS1 Games on Your Computer</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-revitalize-your-reels-selecting-the-best-5-enhancers/"><u>In 2024, Revitalize Your Reels  Selecting the Best 5 Enhancers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-driver-verifier-on-windows-11/"><u>Activating Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-your-online-gaming-experience-with-discord-on-windows/"><u>Accelerating Your Online Gaming Experience with Discord on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334255604-win11-chrome-issues-jumpstart-solution-suggestions/"><u>Win11 Chrome Issues? Jumpstart Solution Suggestions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-clipchamp-integration-windows-11-setup-solved/"><u>Achieve ClipChamp Integration: Windows 11 Setup Solved</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-resize-like-a-pro-the-top-technique-for-vertical-video-success/"><u>In 2024, Resize Like a Pro The Top Technique for Vertical Video Success</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-oppo-find-n3-flip-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Oppo Find N3 Flip Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-glimpse-into-gloom-crafting-art-in-paints-dim-modes/"><u>A Glimpse Into Gloom: Crafting Art in Paint's Dim Modes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319912746-launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-excellence-perfecting-your-consoles-gamepad-functionality/"><u>Achieving Excellence: Perfecting Your Console's Gamepad Functionality</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-opposite-ends-of-the-coin-creative-youtube-rewind-strategies/"><u>In 2024, Opposite Ends of the Coin  Creative Youtube Rewind Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-windows-firewall-configuration/"><u>7 Strategies for Windows Firewall Configuration</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-oppo-find-n3-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Oppo Find N3 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mp3-broadcasting-made-easy-upload-tutorial-for-youtube/"><u>2024 Approved  MP3 Broadcasting Made Easy  Upload Tutorial for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-blank-screens-on-system-ignition/"><u>Addressing Blank Screens on System Ignition</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-cut-to-the-chase-newest-method-for-idevice-screen-recordings-2023/"><u>[New] 2024 Approved  Cut-to-the-Chase  Newest Method for iDevice Screen Recordings, 2023</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-tecno-spark-20-proplus-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Tecno Spark 20 Pro+ phone? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-samsung-galaxy-xcover-7-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Samsung Galaxy XCover 7 for Free? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-look-up-definitions-in-windows-11/"><u>3 Quick Ways to Look Up Definitions in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-windows-10-sound-sensation-a-step-by-step-audio-capture-tutorial/"><u>Updated Windows 10 Sound Sensation A Step-by-Step Audio Capture Tutorial</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-enhancing-view-in-roblox-worlds/"><u>In 2024, Step-By-Step  Enhancing View in Roblox Worlds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719360477145-reigniting-your-computers-print-functionality-with-effective-wwin-solutions/"><u>Reigniting Your Computer's Print Functionality with Effective WWin Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oppo-reno-10-proplus-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Oppo Reno 10 Pro+ 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-approach-to-batch-installations-on-windows-11-via-winstall/"><u>A Comprehensible Approach to Batch Installations on Windows 11 via Winstall</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-tale-of-time-the-windows-taskbar-saga-19852023/"><u>A Tale of Time: The Windows Taskbar Saga (1985–2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268444157-eliminate-non-responsive-printer-a-guide-for-wwin-issues-on-pcs/"><u>Eliminate Non-Responsive Printer: A Guide for WWin Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-erased-typing-on-windows-systems/"><u>Addressing the Issue of Erased Typing on Windows Systems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/audience-appeal-the-ultimate-guide-to-youtube-video-formats/"><u>Audience Appeal  The Ultimate Guide to YouTube Video Formats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-steps-for-dealing-with-windows-http-error-0x80860010/"><u>7 Essential Steps for Dealing with Windows' HTTP Error 0X80860010</u></a></li>
</ul></div>
