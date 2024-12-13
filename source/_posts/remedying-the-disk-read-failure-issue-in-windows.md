---
title: Remedying the Disk Read Failure Issue in Windows
date: 2024-12-10T00:01:46.736Z
updated: 2024-12-12T16:34:39.157Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying the Disk Read Failure Issue in Windows
excerpt: This Article Describes Remedying the Disk Read Failure Issue in Windows
keywords: Fixing Disk Errors Win,Stop Disk Failure Windows,Resolve Disk Read Woes,Correct Disk Access Issues,Tackle Windows Disk Errors,End Read Failures in Win OS,Alleviate Disk Read Failure
thumbnail: https://thmb.techidaily.com/a26306e3d205a36c4a6b9d44bd1cf9f948f504e389465c9417b498ad1381c72e.jpg
---

## Remedying the Disk Read Failure Issue in Windows

 Users often need to copy (or transfer) files to or from external drives connected to Windows PCs. However, some users can’t do so because of an error that says, “Can’t read from the source file or disk.”

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

## 1\. Check if the File Names Include Unsupported Characters

 Unsupported file name characters can cause the “Cannot read from the source file” error. Mac computers enable users to save files with characters like ?, <, >, :, \*, /, \\, |, and “. However, Windows 11 and 10 don’t support any of those characters for file names. Thus, users can’t copy files from external drives that include those characters onto a Windows PC.

 So, check if any files you’re trying to copy from an external drive include those characters. If you find any that do, right-click the files and select **Rename**. Then delete all unsupported characters from their file names. Or remove all kinds of special characters.

![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-option-1.jpg)

## 2\. Run a Check Disk Scan

 Running a Check Disk scan is a widely confirmed fix for the “Cannot read from the source file” error. That highlights this error is often caused by bad disk sectors on drives. Running a Check Disk scan via the Command Prompt for the drive that includes the files will usually remedy such a cause. Our [how to run a CHKDSK scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,to%20get%20stuck%20on%20occasion.) article tells you how to apply this potential fix.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-chkdsk-command2.jpg)

## 3\. Try a Different USB Cable or Port for External Drives

 Another possible cause for the “Cannot read from the source file or disk” error is that there’s an issue with your USB cable or a port on your PC. So, connect your external drive to a different USB port to see if that makes a difference. If you have an alternative USB cable available, try connecting the drive to your PC with it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Compress the Files You’re Trying to Copy Into a ZIP Folder

 Some users have been able to fix the “Cannot read from the source file or disk” error by compressing the files they need to copy into ZIP archives. Doing so will reduce the overall size of one or more files to copy. You can set up a ZIP archive before copy files onto a drive by following the instructions in our article about [creating ZIP files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/).

![The Send to option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-send-to-option.jpg)

## 5\. Check the Permissions for the Affected Files

 You might need to fix the “Cannot read from the source file or disk” because one of the files you’re trying to copy doesn’t have full control permissions set. You can check and fix permissions for affected files as follows:

1. First, bring up Explorer (press**Win + E**) and navigate to the folder that includes the files you need to copy.
2. Right-click a file you need to copy and select **Properties**.
3. Then select **Edit** on the **Security** tab.  
![The Edit button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-edit-button.jpg)
4. Next, select the checkbox labeled **Full control** with the **Allow** column.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-full-control-checkbox.jpg)
5. Press **Apply** to save the file’s permission settings.
6. Click **OK** to exit.

 If you can’t see your account username within the Group box, you’ll need to add it. To do so, click **Add** on the **Security** tab to bring up a Select Users or Group window; then click **Advanced** \> **Find now** to select your user account. Click **OK** to add the selected account.

![The Find now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-find-now-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Access Files on Mac-Formatted Drives With Third-Party Software

 The “Can’t read from the source file” error can also occur because of file system incompatibility on source drives. For example, Mac-formatted HFS or APFS drives aren’t compatible with Windows PCs.

 You can check the file system of any connected drive by right-clicking it in File Explorer and selecting **Properties**. Then check the File system detail on the General tab. NTFS and FAT32 file systems are fine for Windows, but HFS and APFS aren’t.

![The File system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-file-system-detail.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re trying to copy files from Mac-formatted drives, you can access them with third-party software. Software packages like MacDrive, UFS Explorer, and Paragon HFS+ enable users to access files on Mac-formatted drives on Windows PCs. Our article about [reading Mac-formatted drives on Windows](https://www.makeuseof.com/tag/4-ways-read-mac-formatted-drive-windows/) provides details on how to apply this potential resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Copy Files Between Drives on Your Windows PC Again

 Applying those solutions will usually resolve the “Cannot read from the source file” error on Windows. Then you can copy all the files you need between your Windows PC and external drives.

 One other resolution for this error recommended by some users is to utilize data recovery software. Such software provides another way to copy or transfer files from one drive to another. Stellar Data Recovery, Recuva, MiniTool Data Recovery, and Disk Drill are among the best data recovery software to utilize for that purpose.

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/updated-a-comprehensible-guide-on-saving-instagram-story-content-for-2024/"><u>[Updated] A Comprehensible Guide on Saving Instagram Story Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-digital-storyboard-studio/"><u>[Updated] In 2024, Digital Storyboard Studio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-make-gif-on-iphone-top-10-gif-apps-for-iphone-x876/"><u>[Updated] Make GIF on iPhone Top 10 GIF Apps for iPhone X/8/7/6</u></a></li>
<li><a href="https://win-lab.techidaily.com/asushddssd/"><u>ASUS筆電體驗改造：高效率更換HDD為SSD指南</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expanded-functionality-how-to-tailor-win-11s-menu-bar/"><u>Expanded Functionality: How to Tailor Win 11'S Menu Bar</u></a></li>
<li><a href="https://win-advanced.techidaily.com/faca-conexao-agora-com-o-departamento-de-suporte-e-vendas-do-aomei-backupper-para-assistencia-personalizada/"><u>Faça Conexão Agora Com O Departamento De Suporte E Vendas Do AOMEI Backupper Para Assistência Personalizada!</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-the-blue-screen-of-death-error-code-0xc000021a-in-windows-10-and-8-complete-guide/"><u>Fixing the 'Blue Screen of Death' Error Code 0xC000021A in Windows 10 and 8 - Complete Guide</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-from-apple-iphone-6s-plus-to-samsung-galaxy-s20-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer from Apple iPhone 6s Plus to Samsung Galaxy S20? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightning-speed-locate-your-gpu-on-windows-11-pc/"><u>Lightning Speed: Locate Your GPU on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-non-operational-win11-licenses-work/"><u>Making Non-Operational Win11 Licenses Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-malfunctioning-mouse-context-menus/"><u>Mastery Over Malfunctioning Mouse Context Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-issues-with-windows-virtual-disks-and-services/"><u>Mitigating Issues with Windows' Virtual Disks and Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powershell-command-for-assessing-folder-capacity-in-windows/"><u>PowerShell Command for Assessing Folder Capacity in Windows</u></a></li>
<li><a href="https://fox-place.techidaily.com/splitting-and-merging-file-techniques-in-windows-operating-system-with-tips-from-yl-software-experts/"><u>Splitting and Merging File Techniques in Windows Operating System with Tips From YL Software Experts</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-integrating-slack-with-your-apple-watch-for-instant-updates-tips/"><u>Step-by-Step Guide: Integrating Slack with Your Apple Watch for Instant Updates - Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surface-studio-2-review-the-closer-to-ideal-device-for-artists/"><u>Surface Studio 2 Review: The Closer to Ideal Device for Artists?</u></a></li>
</ul></div>

