---
title: Mastering File Compression Techniques for Disk Optimization
date: 2024-12-06T22:42:13.017Z
updated: 2024-12-13T01:52:41.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering File Compression Techniques for Disk Optimization
excerpt: This Article Describes Mastering File Compression Techniques for Disk Optimization
keywords: File Compression Mastery,Disk Optimize Strategies,Compression Methods Guide,Data Reduction Tactics,Efficient Storage Solutions,Optimization Techniques Save Space,Advanced Compression Skills
thumbnail: https://thmb.techidaily.com/769d83492280fd0660acd0112190d1d990d0e4305860168c39e79719f29b2ea7.jpg
---

## Mastering File Compression Techniques for Disk Optimization

 Is your Windows computer running out of storage? There are plenty of ways to remove redundant data and free up some extra space. Among all, the most preferred method is using NTFS file compression.

 NTFS file compression is a Windows feature that compresses files and folders by removing reductant data from them. The best part about this feature is that it does its job without damaging the file and losing the data.

 Nevertheless, let's check out some ways to enable NTFS file compression in Windows 11.

## 1\. Enable NTFS File Compression Through the File Explorer

 The quickest way to enable NTFS[file compression](https://www.makeuseof.com/windows-11-file-compression-guide/) is through File Explorer. Below are the steps to compress a folder:

1. Open the File Explorer and head toward the folder you want to compress.
2. Right-click on the target folder and choose**Properties** from the context menu.
3. In the**General** tab, select the**Advanced** option.
4. Under the**Compress or Encrypt attributes** section, check the**Compress contents to save disk space** box and click**OK** .  
![Compress content to save disk option in Folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/compress-content-to-save-disk-option.jpg)
5. Click**Apply** \>**OK** to save the changes.
6. In the confirmation dialog box that crops up, choose the **Apply changes to this folder, subfolders, and files option** .  
![Apply changes option in folder properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/apply-changes-option.jpg)
7. Click**OK.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 That's it, the folder has now been compressed. You can confirm this by comparing the current folder size with its previous size.

 From now on, every file or folder that you will move inside the compressed folder will be compressed automatically. To disable compression, uncheck the**Compress contents to save disk space** box and save the changes.

Similarly, you can compress an entire drive. Here's how:

1. Open the File Explorer, and right-click on the drive you want to compress.
2. In the**General** tab, check the**Compress this drive to save disk space** box.  
![Driver properties in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/driver-properties.jpg)
3. Click**Apply** and then click**OK** on the confirmation box that crops up.

## 2\. Enable NTFS File Compression Using the Command Prompt

 If you are a power user, you can use the Command Prompt to enable file compression on Windows 11\. Here are the steps to do it:

1. Press the**Win + S** hotkeys to open the**Windows Search.**
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane. If this method is not working, you can use any other way to[open Command Prompt with admin rights](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Type the following command and press**Enter** to enable file compression.  
`fsutil behavior set disablecompression 0`

![File compression command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/file-compression-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll see the "**A reboot is required for this change to take effect** " message on the console. So, restart your computer to apply the changes.

 If you want to disable File Compression, execute the following command in the elevated Command Prompt window, followed by a system restart.

`fsutil behavior set disablecompression 1`

## 3\. Enable NTFS File Compression Using the Registry Editor

 Another quick way to enable compression is through the Registry Editor. Follow the below steps to do it:

1. Open the**Run dialog box** by pressing the**Win + R** hotkeys.
2. Type**regedit** in the text field and click**OK.**
3. In the Registry Editor, navigate to the below location:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Policies`
4. Right-click on the**Policies** folder in the left sidebar, hover the cursor to**New,** and choose**DWORD** **(32-bit) Value** from the context menu.  
![Choosing DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-dword.jpg)
5. Right-click on the newly created value and choose**Rename** .
6. Type**Ntfsenablecompression** in the text field.
7. Select and right-click on**Ntfsenablecompression** again, and choose**Modify** .
8. Type**1** in the**Value data** .  
![Editing Ntfsenablecompression in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-ntfsenablecompression.jpg)
9. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 File compression is now enabled on your computer. If you want to disable it, type 0 in Value data and save the changes.

## 4\. Enable NTFS File Compression Using the Local Group Policy Editor

 The Local Group Policy Editor is the go-to place to configure important Windows policies. To use it to enable file compression, follow the below instructions:

1. In the Run dialog box, type**gpedit.msc** and click**OK.**
2. Head towards the following location in the Local Group Policy Editor:  
`Computer Configuration\Administrative Templates\System\Filesystem\NTFS`
3. Double-click on the**Do not allow compression on all NTFS volumes policy** to open its properties window.
4. Choose the**Disabled** option.  
![Disabling policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-policy.jpg)
5. Click**Apply** \>**OK** to enable file compression.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can disable the file compression by choosing the**Enabled** option in the**Do not allow compression on all NTFS volumes policy** properties window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Free Up Space on Windows 11 With File Compression

 Enabling file compression is a great way to free up some space on Windows 11\. Using this feature can come in handy when you are running out of space but also don't want to compress your files using third-party compression tools.

 Meanwhile, you might be interested in learning more about the NTFS file system.

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
<li><a href="https://facebook-video-content.techidaily.com/new-correct-iosandroid-video-failures-on-fb-for-2024/"><u>[New] Correct iOS/Android Video Failures on FB for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-why-av1-may-outshine-vp9-in-video-compression/"><u>[New] In 2024, Why AV1 May Outshine VP9 in Video Compression</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lullabies-on-a-screen-analysis-of-story-tapes-for-sleep/"><u>[New] Lullabies on a Screen Analysis of Story Tapes for Sleep</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-comprehensively-understanding-recmeisters-screen-recording-strengths/"><u>[Updated] In 2024, Comprehensively Understanding Recmeister's Screen Recording Strengths</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-elevate-engagement-with-these-10-premier-youtube-seo-instruments/"><u>[Updated] In 2024, Elevate Engagement with These 10 Premier YouTube SEO Instruments</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-laughing-alongside-the-metaverse-diy-humor-tips-and-tricks-for-2024/"><u>[Updated] Laughing Alongside the Metaverse DIY Humor Tips & Tricks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-driven-mastery-unlock-4-steps-for-accessing-disk-management-in-win11/"><u>Data-Driven Mastery: Unlock 4 Steps for Accessing Disk Management in Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/digital-precision-the-art-of-perfect-online-image-trimming/"><u>Digital Precision The Art of Perfect Online Image Trimming</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/mastering-email-metrics-in-2011-essential-kpis-and-innovative-techniques-with-massmail-tools/"><u>Mastering Email Metrics in 2011: Essential KPIs and Innovative Techniques with Massmail Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-connection-mainteninas-a-rust-windows-solution-guide/"><u>Mastering Steam Connection Mainteninas: A Rust-Windows Solution Guide</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/mobile-scanning-and-ocr-technology-for-documents-convert-pdf-jpg-to-text-with-iphone-app/"><u>Mobile Scanning & OCR Technology for Documents - Convert PDF, JPG to Text with iPhone App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-cannot-find-gpeditmsc-error-in-windows/"><u>Overcoming Common Cannot Find Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsoft-store-glitch-error-x80072f30-fix-guide/"><u>Overcoming Microsoft Store Glitch: Error X80072F30 Fix Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/quick-guide-free-methods-to-fix-damaged-mp4-files-on-windows-and-macos/"><u>Quick Guide: Free Methods to Fix Damaged MP4 Files on Windows and macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-skyrim-with-script-enhancement-fixes/"><u>Reigniting Skyrim with Script Enhancement Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-eliminating-isdonedll-issues-on-windows/"><u>Step-by-Step Tutorial: Eliminating ISDone.dll Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-nullifying-internal-pc-keys/"><u>Techniques for Nullifying Internal PC Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/thermal-efficiency-for-gamers-laptops-while-playing/"><u>Thermal Efficiency for Gamers' Laptops While Playing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-server-stumbled-error-for-a-smooth-microsoft-store-experience-on-windows-11-and-11/"><u>Unblocking Server Stumbled Error for a Smooth Microsoft Store Experience on Windows 11 & 11</u></a></li>
</ul></div>

