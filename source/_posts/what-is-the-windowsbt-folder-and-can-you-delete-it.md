---
title: What Is the $Windows.~BT Folder, and Can You Delete It?
date: 2024-10-28T17:05:30.437Z
updated: 2024-11-01T17:27:06.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Is the $Windows.~BT Folder, and Can You Delete It?
excerpt: This Article Describes What Is the $Windows.~BT Folder, and Can You Delete It?
keywords: Windows BT Folder Insight,Deleting Windows Batch Files,Understanding Windows Batch,Windows .BAT File Structure,How to Remove Windows Scripts,Exploring Windows Batch Path,Identifying Windows Batch Folders
thumbnail: https://thmb.techidaily.com/42db5c6877cc90dcf8ab2d1fd7012cdb680249e89327096af45fe59619012883.jpg
---

## What Is the $Windows.~BT Folder, and Can You Delete It?

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
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tech-recovery.techidaily.com/discover-8-effective-people-finder-search-engines-online/"><u>Discover 8 Effective People-Finder Search Engines Online</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discovering-scenes-with-canons-g9x-mark-ii/"><u>Discovering Scenes with Canon's G9X Mark II</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-sticky-notes-dont-get-lost/"><u>Ensuring Sticky Notes Don't Get Lost</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-oneplus-12r-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On OnePlus 12R Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-grow-picture-dimensions-maintain-fidelity/"><u>In 2024, Grow Picture Dimensions, Maintain Fidelity</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-jokecrafters-log-in-to-make-a-difference/"><u>In 2024, JokeCrafters Log In to Make a Difference</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-lenovo-driver-packs-free-download-and-installation-guide-for-windows-10/"><u>Latest Lenovo Driver Packs: Free Download & Installation Guide for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-overloaded-system-by-controlling-processes/"><u>Resolving Overloaded System by Controlling Processes</u></a></li>
<li><a href="https://fox-direct.techidaily.com/sci-fis-virtual-quest-the-best-movies-to-discover-alien-universes-for-2024/"><u>Sci-Fi's Virtual Quest The Best Movies to Discover Alien Universes for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/stepwise-decrease-in-mix-dynamics/"><u>Stepwise Decrease in Mix Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-retro-arc-of-gaming-shading-techniques-for-ancient-artifacts/"><u>The Retro Arc of Gaming: Shading Techniques for Ancient Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-guide-to-fast-clickers/"><u>The Ultimate Windows Guide to Fast Clickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues!</u></a></li>
</ul></div>

