---
title: "Silent Data Exchange: Safeguarding Files Across WS11/W10"
date: 2024-06-25T16:40:28.099Z
updated: 2024-06-26T16:40:28.099Z
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
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-steam-disk-write-failures-effectively/"><u>Tackling Windows Steam Disk Write Failures Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-save-photoerror-in-windows-11-os/"><u>How to Correct 'No Save' PhotoError in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-approach-to-allocated-ram/"><u>Understanding Windows' Approach to Allocated RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-implementation-of-updater-in-win11-version-22h2/"><u>Seamless Implementation of Updater in WIN11 Version 22H2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-your-potential-top-7-efficiency-enhancing-widgets-for-win-11/"><u>Unleashing Your Potential: Top 7 Efficiency Enhancing Widgets for Win 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-free-clip-art-for-your-designs/"><u>Unlocking Free Clip-Art for Your Designs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-building-a-stylish-tiktok-closing-credits-bar/"><u>[Updated] Building A Stylish TikTok Closing Credits Bar</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-the-definitive-guide-to-perfecting-vimeo-recordings/"><u>[Updated] In 2024, The Definitive Guide to Perfecting Vimeo Recordings</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-elevating-your-sound-experience-the-top-10-alternatives-to-audacity-across-computers-and-tablets/"><u>Updated In 2024, Elevating Your Sound Experience The Top 10 Alternatives to Audacity Across Computers and Tablets</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-sony-xperia-5-v-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Sony Xperia 5 V? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-nubia-z50s-pro-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Nubia Z50S Pro</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-free-video-editors-for-chrome-os-a-review-of-the-top-options/"><u>2024 Approved Free Video Editors for Chrome OS A Review of the Top Options</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-webcamwizardry-techniquesforperfectrecordings-for-2024/"><u>[Updated] WebCamWizardry  TechniquesForPerfectRecordings for 2024</u></a></li>
</ul></div>
