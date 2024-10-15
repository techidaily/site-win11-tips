---
title: How to Locate & Manage Windows Batch Files
date: 2024-10-10T02:25:20.242Z
updated: 2024-10-14T19:22:34.852Z
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
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-optimize-your-content-youtube-seo-techniques-and-gadgets/"><u>[New] 2024 Approved Optimize Your Content YouTube SEO Techniques and Gadgets</u></a></li>
<li><a href="https://youtube-data.techidaily.com/mplifying-engagement-with-leading-youtube-ranks-top-8-apps-for-2024/"><u>[New] Amplifying Engagement with Leading YouTube Ranks Top 8 Apps for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-guide-for-text-superimposition-on-video-using-windows-photos/"><u>[Updated] Step-by-Step Guide for Text Superimposition on Video Using Windows Photos</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-craft-professional-episodes-a-comprehensive-guide-to-editing-in-garageband/"><u>2024 Approved Craft Professional Episodes A Comprehensive Guide to Editing in GarageBand</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/establish-a-home-friendly-low-cost-windows-simulation/"><u>Establish a Home-Friendly, Low-Cost Windows Simulation</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-from-your-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password From your iPhone 13 Pro Max</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/regulatory-guidelines-youtube-video-recording/"><u>Regulatory Guidelines YouTube Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-mandatory-requirements-problem-on-win11win11/"><u>Remedying Mandatory Requirements Problem on Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverse-engineering-steams-unauthorized-file-access/"><u>Reverse Engineering Steam's Unauthorized File Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-windows-11s-disappeared-symbols/"><u>Reviving Windows 11'S Disappeared Symbols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-disk-differentiation-hddssd-checks-in-windows/"><u>Streamlining Disk Differentiation: HDD/SSD Checks in Windows</u></a></li>
</ul></div>

