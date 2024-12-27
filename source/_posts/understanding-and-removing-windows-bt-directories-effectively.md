---
title: Understanding and Removing Windows ~BT Directories Effectively
date: 2024-12-23T17:40:13.865Z
updated: 2024-12-27T19:05:31.463Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Removing Windows ~BT Directories Effectively
excerpt: This Article Describes Understanding and Removing Windows ~BT Directories Effectively
keywords: Windows BT Directory Cleaning,BT Directories in Windows,Remove Windows Directories,Windows Directory Structure,Effective BT Removal Tools,Delete Windows BT Folders,Optimize Windows ~BT Storage
thumbnail: https://thmb.techidaily.com/c2838348b746990136e05e229d4b40bfea769dde8bb07eb48712190cd8997d0c.jpg
---

## Understanding and Removing Windows ~BT Directories Effectively

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-explore-the-globe-top-10-travelers-youtube-guide/"><u>[New] In 2024, Explore the Globe Top 10 Traveler's YouTube Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-leading-voice-modifying-apps-magical-calls-and-more/"><u>[Updated] Leading Voice-Modifying Apps Magical Calls & More</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pro-fishing-visionaries-discovering-our-5-best-cameras/"><u>[Updated] Pro-Fishing Visionaries Discovering Our 5 Best Cameras</u></a></li>
<li><a href="https://win-bytes.techidaily.com/convertir-audio-desde-el-tipo-de-archivo-ape-al-m4a-directamente-en-internet-gratuito-con-movavi/"><u>Convertir Audio Desde El Tipo De Archivo APE Al M4A Directamente en Internet Gratuito Con Movavi</u></a></li>
<li><a href="https://review-topics.techidaily.com/does-vivo-y100t-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Vivo Y100t Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-file-management-instantaneously-duplicating-folders-on-windows/"><u>Expedite File Management: Instantaneously Duplicating Folders on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-newcomer-to-pro-classic-diablo-techniques/"><u>From Newcomer to Pro: Classic Diablo Techniques</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-oppo-reno-10-pro-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Oppo Reno 10 Pro 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-budget-friendly-ultra-panoramic-video-cameras/"><u>In 2024, Budget-Friendly Ultra-Panoramic Video Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insider-take-unveiling-key-upgrades-in-feb-update/"><u>Insider Take: Unveiling Key Upgrades in FEB Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-windows-shortcuts-for-uwp-apps/"><u>Mastering the Art of Windows Shortcuts for UWP Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-csgo-playthrough-speed-with-these-tips/"><u>Maximize CSGO Playthrough Speed with These Tips</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-the-job-market-with-ai-expertise-essential-tech-skills-employers-seek-for-future-hires-insights-from-zdnet/"><u>Navigating the Job Market with AI Expertise: Essential Tech Skills Employers Seek for Future Hires - Insights From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-win-11-recycle-bin-crashes-and-issues/"><u>Overcoming Win 11 Recycle Bin Crashes & Issues</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/quick-start-guide-to-arranging-engaging-google-sessions/"><u>Quick Start Guide to Arranging Engaging Google Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution</u></a></li>
</ul></div>

