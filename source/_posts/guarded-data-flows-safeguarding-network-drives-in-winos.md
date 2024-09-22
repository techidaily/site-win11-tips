---
title: "Guarded Data Flows: Safeguarding Network Drives in WinOS"
date: 2024-09-17T00:03:12.604Z
updated: 2024-09-21T23:30:34.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guarded Data Flows: Safeguarding Network Drives in WinOS"
excerpt: "This Article Describes Guarded Data Flows: Safeguarding Network Drives in WinOS"
keywords: Secure Data Transfer OS,WinData Guarding,Safe Network Storage,Protected OS Storage,OS Data Security,Encrypted Drive OS,WinOS Safeguard
thumbnail: https://thmb.techidaily.com/8607afd112c21db80344a74ef1409282fa825e22bfc978ed73479483276176d5.jpg
---

## Guarded Data Flows: Safeguarding Network Drives in WinOS

 File Explorer in Windows displays any internal or external drives that are connected to your system by default. However, if you don't want a certain drive to appear in File Explorer, you can always hide it.

 By hiding a drive on Windows, you can prevent others from accessing sensitive files within that drive and keep them safe. If you're interested in doing that, this guide will walk you through four different methods to hide drives on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Hide a Drive Using the Disk Management App

 The Disk Management tool on Windows makes it easy to perform various storage-related tasks such as formatting hard disk partitions, assigning drive letters, managing disk space, and more. You can also use it to hide a drive partition on Windows. Here's how:

1. Press**Win + R** or use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
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

 If you like using Command Prompt, why not check our guide on[how to master the Command Prompt in Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) ?

## 3\. Hide a Drive Using the Group Policy Editor

 The Local Group Policy Editor is a tool that allows you to configure a wide range of settings on your computer. You can use it to hide a drive from your Windows computer.

 The Local Group Policy Editor is only available in Professional, Enterprise, and Education editions of Windows. If you're using the Windows Home edition, check our guide on[how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Hide a Drive in Windows via the Registry Editor

 Another brilliant tool that allows you to configure system settings in Windows easily is the Registry Editor. You can use Registry Editor to hide a drive if none of the above methods work. However, you must be careful[not to accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) in the process.

 To be safe, you should back up all the registry files before proceeding. If you need help with that, check our guide on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-adding-media-to-enhance-content/"><u>[New] 2024 Approved Adding Media to Enhance Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-become-the-brand-you-want-with-our-exclusive-set-of-free-graphics-for-2024/"><u>[New] Become the Brand You Want With Our Exclusive Set of FREE Graphics for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-beginners-guide-to-mesmerizing-bokeh-in-instagram-stories-for-2024/"><u>[New] The Beginner’s Guide to Mesmerizing Bokeh in Instagram Stories for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-free-youtube-end-screen-resources-enhance-video-impact/"><u>[Updated] Free YouTube End Screen Resources - Enhance Video Impact</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-navigating-video-migration-youtube-to-dailymotion-process/"><u>[Updated] In 2024, Navigating Video Migration YouTube to Dailymotion Process</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-cutting-edge-video-processing-free-hd1080p-from-ff-videos/"><u>2024 Approved Cutting Edge Video Processing Free HD/1080P From FF Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/como-convertir-archivos-wmv-a-formato-avi-gratuito-online-con-convertidor-de-movavi/"><u>Cómo Convertir Archivos WMV a Formato AVI Gratuito Online Con Convertidor De Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversion-de-archivos-mp3-a-mp4-gratuita-y-facil-con-movavi-online/"><u>Conversión De Archivos MP3 a MP4 Gratuita Y Fácil Con Movavi Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-change-your-files-from-ape-to-wav-format-with-movavi/"><u>Free Online Converter: Change Your Files From APE to WAV Format with Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-mp4-to-gif-converter-movavi-guide/"><u>Free Online MP4 to GIF Converter - Movavi Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-tecno-pova-5-devices-by-drfone-android/"><u>How to Reset Gmail Password on Tecno Pova 5 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-installazione-e-conversione-gratuita-di-ts-file-online/"><u>Movavi: Installazione E Conversione Gratuita Di TS File Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforma-tu-fotografia-raw-en-jpeg-con-facilidad-y-gratuitamente-mediante-movavi/"><u>Transforma Tu Fotografía RAW en JPEG Con Facilidad Y Gratuitamente Mediante Movavi</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-from-chrome-to-pro-running-professional-video-editing-software-on-your-chromebook/"><u>Updated 2024 Approved From Chrome to Pro Running Professional Video Editing Software on Your Chromebook</u></a></li>
</ul></div>

