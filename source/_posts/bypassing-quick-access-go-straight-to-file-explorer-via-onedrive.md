---
title: "Bypassing Quick Access: Go Straight to File Explorer via OneDrive"
date: 2025-01-16T18:17:47.175Z
updated: 2025-01-18T18:31:44.411Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypassing Quick Access: Go Straight to File Explorer via OneDrive"
excerpt: "This Article Describes Bypassing Quick Access: Go Straight to File Explorer via OneDrive"
keywords: Bypass Quick Access,Direct File Explorer,OneDrive Save,Avoid Windows Menu,Fast File Explorer,Navigate To OneDrive,Direct OneDrive Open
thumbnail: https://thmb.techidaily.com/d0e21788f29958fdaba0fdac4398d13da9177082545009c2bddd22992fae44fc.jpg
---

## Bypassing Quick Access: Go Straight to File Explorer via OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-audio-allies-the-new-tiktok-trend/"><u>[Updated] In 2024, Audio Allies The New TikTok Trend</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-scripted-time-warps-a-cinematic-approach/"><u>[Updated] Scripted Time Warps A Cinematic Approach</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-your-course-to-youtube-riches-the-essential-500-threshold/"><u>Chart Your Course to Youtube Riches The Essential 500 Threshold</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-forbidden-save-messages-on-windows-pcs/"><u>Clearing Up 'Forbidden Save' Messages on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/error-code-2e-strategies-for-windows-update-fix/"><u>Error Code 2E: Strategies for Windows Update Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-automatically-shut-down-a-windows-10-and-11-pc-when-its-idle/"><u>How to Automatically Shut Down a Windows 10 and 11 PC When It's Idle</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-gratitude-freepaid-outro-template-selections/"><u>In 2024, Gratitude Free/Paid Outro Template Selections</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-unveiling-the-secrets-to-thriving-with-youtube-adsense/"><u>In 2024, Unveiling the Secrets to Thriving With YouTube AdSense</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-wasteful-resource-usage-by-ntoskrnlexe/"><u>Lowering Wasteful Resource Usage by Ntoskrnl.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system-fixes-reviving-troubleshooters-in-windows-11/"><u>Mastering System Fixes: Reviving Troubleshooters in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-copy-pasting-errors-in-popular-web-browsers/"><u>Overcoming Copy-Pasting Errors in Popular Web Browsers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protect-your-child-online-windows-11-safety-guide/"><u>Protect Your Child Online: Windows 11 Safety Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tricks-bridging-airpods-and-windows-devices/"><u>Tech Tricks: Bridging AirPods & Windows Devices</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-12-prominent-vivo-y27s-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo Y27s Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-steps-resolving-five-nights-at-freddys-security-breach-pc-glitches/"><u>Troubleshooting Steps: Resolving 'Five Nights at Freddy's Security Breach PC Glitches</u></a></li>
</ul></div>

