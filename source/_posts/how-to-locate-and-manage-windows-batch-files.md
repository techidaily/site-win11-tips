---
title: How to Locate & Manage Windows Batch Files
date: 2024-10-02T06:12:45.136Z
updated: 2024-10-08T23:20:48.883Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Locate & Manage Windows Batch Files
excerpt: This Article Describes How to Locate & Manage Windows Batch Files
keywords: Find Windows Scripts,Manage Batch Files,Windows Batch File Guide,Batch File Location Tips,Batch File Management Tools,Handle Windows Executable Files,Locate & Edit Batch Files
thumbnail: https://thmb.techidaily.com/6f98ed833e99780ec633017bfd02ba19a6f592b2168edc5e24a71f77a22d913e.jpg
---

## How to Locate & Manage Windows Batch Files

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-resolving-bandwidth-issues-in-high-quality-obs/"><u>[Updated] 2024 Approved Resolving Bandwidth Issues in High Quality OBS</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-gain-cost-free-visuals-from-selective-4-youtube-feeds/"><u>[Updated] Gain Cost-Free Visuals From Selective 4 YouTube Feeds</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-get-savvy-with-screen-recording-on-xiaomi-mi-11/"><u>[Updated] Get Savvy with Screen Recording on Xiaomi Mi 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhanced-security-with-expressvpns-latest-update-introducing-the-built-in-password-safe/"><u>Enhanced Security with ExpressVPN's Latest Update - Introducing the Built-In Password Safe!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-timekeeping-tools-without-a-price/"><u>Expert Timekeeping Tools Without a Price</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovations-in-computing-6-best-tracking-software-for-pc/"><u>Innovations in Computing: 6 Best Tracking Software for PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-rainmeter-fixes-common-bugs-and-workarounds/"><u>Mastering Rainmeter Fixes: Common Bugs and Workarounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-performance-sluggishness-in-windows-with-dual-screen-views/"><u>Preventing Performance Sluggishness in Windows with Dual Screen Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rediscovering-lost-panes-a-sixfold-approach-for-windows-users/"><u>Rediscovering Lost Panes: A Sixfold Approach for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-common-caption-issues-on-windows-10-systems/"><u>Tackling Common Caption Issues on Windows 10 Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-fullscreen-potential-in-adobe-premiere-for-2024/"><u>Unlocking Fullscreen Potential in Adobe Premiere for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    