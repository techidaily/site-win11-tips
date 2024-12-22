---
title: What Purpose Does the Windows ~BT Directory Serve?
date: 2024-12-19T08:23:16.657Z
updated: 2024-12-21T20:52:33.646Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Purpose Does the Windows ~BT Directory Serve?
excerpt: This Article Describes What Purpose Does the Windows ~BT Directory Serve?
keywords: BT Directory Usage,Windows BT Folder Role,BT Directory Function,Windows BT Purpose,BT in Windows OS,Understanding Windows BT,Windows BT Structure
thumbnail: https://thmb.techidaily.com/cd61def31c266f510e96724b2a8477792657278ca4fb179ccb3f421fcf0aa55a.jpg
---

## What Purpose Does the Windows ~BT Directory Serve?

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-top-10-open-source-os-friendly-videography-software/"><u>[New] 2024 Approved Top 10 Open-Source OS-Friendly Videography Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-harvest-hacks-ginger-valley-edition/"><u>[New] In 2024, Harvest Hacks Ginger Valley Edition</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-the-dynamics-of-home-security-manycam-vs-single-camera-tech/"><u>[Updated] The Dynamics of Home Security ManyCam Vs. Single-Camera Tech</u></a></li>
<li><a href="https://discover-help.techidaily.com/1726029291332-h264avi/"><u>「H264ビデオファイルをAVI形式へ変換：品質を失わない方法」</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-the-something-went-wrong-error-with-ios-photos/"><u>Fixes for the 'Something Went Wrong' Error with iOS Photos</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guia-completo-para-iniciar-sessao-com-o-movavi-em-computadores-apple-instrucoes-detalhadas/"><u>Guia Completo Para Iniciar Sessão Com O Movavi Em Computadores Apple - Instruções Detalhadas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-malwarebytes-runtime-error-could-not-call-proc-issue-in-windows-1110/"><u>How to Fix the Malwarebytes Runtime Error: Could Not Call Proc Issue in Windows 11/10</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/iphones-or-samsung-phones-in-depth-guide-to-help-you-pick-your-perfect-mobile-device/"><u>IPhones or Samsung Phones? In-Depth Guide to Help You Pick Your Perfect Mobile Device</u></a></li>
<li><a href="https://fox-links.techidaily.com/sculpt-your-memories-with-iphone-burst-shots/"><u>Sculpt Your Memories with iPhone Burst Shots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-power-of-connectedness-wp-galaxy-via-flow-app/"><u>The Power of Connectedness - WP-Galaxy via Flow App</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/trois-techniques-innovantes-pour-retirer-un-objet-dune-image-en-2024/"><u>Trois Techniques Innovantes Pour Retirer Un Objet D'une Image en 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-teams-screen-sharing-on-windows/"><u>Troubleshoot Teams Screen Sharing on Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshoot-your-ios-tvremote-app-a-comprehensive-fixing-guide/"><u>Troubleshoot Your iOS TVRemote App - A Comprehensive Fixing Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-toolkit-keyboard-cars-for-optimal-tasks/"><u>Ultimate Toolkit: Keyboard Cars for Optimal Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-vintage-makeover-transform-into-classic-windows-98/"><u>Windows 11 Vintage Makeover: Transform Into Classic Windows 98</u></a></li>
</ul></div>

