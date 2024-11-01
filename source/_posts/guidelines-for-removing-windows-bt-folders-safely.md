---
title: Guidelines for Removing Windows ~BT Folders Safely
date: 2024-10-30T19:15:46.455Z
updated: 2024-11-01T18:12:01.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines for Removing Windows ~BT Folders Safely
excerpt: This Article Describes Guidelines for Removing Windows ~BT Folders Safely
keywords: BT Folder Deletion Guide,Safe Windows File Removal,Windows ~BT Extract Removal,Secure File Deletion on PC,Avoiding Data Loss in OSX,Preventing System Errors When Deleting Files,Effective Windows File Management
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## Guidelines for Removing Windows ~BT Folders Safely

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
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1993647">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993647%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/updated-identifying-high-impact-hdr-photography-tools/"><u>[Updated] Identifying High-Impact HDR Photography Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-insta-editing-secrets-mastering-high-resolution-footage-in-fcpx/"><u>[Updated] Insta-Editing Secrets Mastering High-Resolution Footage in FCPX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-selecthighlight-issues-in-pdfs-on-windows-pcs/"><u>Fix Select/Highlight Issues in PDFs on Windows PCs</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/future-homes-with-ai-exploring-apples-vision-of-domestic-robot-companions/"><u>Future Homes with AI: Exploring Apple's Vision of Domestic Robot Companions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-override-microsofts-antivirus-exclusivity-measures/"><u>How to Override Microsoft's Antivirus Exclusivity Measures</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-5-solutions-for-realme-12plus-5g-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Realme 12+ 5G Unlock Without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-a-non-reactive-windows-download-folder/"><u>Methods to Fix a Non-Reactive Windows Download Folder</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-career-milestones-using-gpt-technology/"><u>Navigating Career Milestones Using GPT Technology</u></a></li>
<li><a href="https://extra-skills.techidaily.com/optimal-storage-expansion-for-sony-a7c-for-2024/"><u>Optimal Storage Expansion for Sony A7C for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-windows-device-conflicts-no-more-in-use-name-woes/"><u>Resolve Windows Device Conflicts: No More In-Use Name Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-excel-files-unreadable-in-windows-notepad/"><u>Resolve: Excel Files Unreadable in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-not-enough-resources-for-usb-on-windows/"><u>Resolving “Not Enough Resources” For USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-puzzle-overcoming-a-blank-login-window-on-win1011/"><u>Solving the Puzzle: Overcoming a Blank Login Window on Win10/11</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-webcam-selection-for-podcasting/"><u>Ultimate Webcam Selection for Podcasting</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-fraudgpt-a-comprehensive-guide-on-navigating-its-risks/"><u>Understanding FraudGPT: A Comprehensive Guide on Navigating Its Risks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-protocol-concealing-firewall-areas/"><u>Window’s Security Protocol: Concealing Firewall Areas</u></a></li>
</ul></div>

