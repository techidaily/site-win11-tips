---
title: Guidelines for Removing Windows ~BT Folders Safely
date: 2024-10-22T20:14:50.432Z
updated: 2024-10-26T18:50:36.468Z
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
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094476/7443" target="_top" id="2094476">
  <img src="//a.impactradius-go.com/display-ad/7443-2094476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-smooth-iphone-screen-recording-made-simple-for-2024/"><u>[New] Smooth iPhone Screen Recording Made Simple for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-15-best-sites-to-find-and-download-royalty-free-music-for-youtube-for-2024/"><u>[Updated] 15 Best Sites to Find & Download Royalty-Free Music for YouTube for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-revive-lost-media-icons-on-facebook-users-for-2024/"><u>[Updated] Revive Lost Media Icons on Facebook Users for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-iphone-11-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off iPhone 11 without Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-reversing-frozen-dark-theme-on-computers/"><u>A Guide to Reversing Frozen Dark Theme on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-aspects-of-revamping-your-windows-setup/"><u>Crucial Aspects of Revamping Your Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-unlocking-stuck-battlenet-login/"><u>Expert Guide to Unlocking Stuck Battle.net Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-resetting-windows-11-applications/"><u>Guide to Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-successfully-install-broadcom-bluetooth-drivers-on-pc-with-windows-os-windows-10-8-or-ebx/"><u>How to Successfully Install Broadcom Bluetooth Drivers on PC with Windows OS (Windows 10, 8, or Ebx)</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-easy-ways-to-change-location-on-youtube-tv-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Easy Ways to Change Location on YouTube TV On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigms-of-administrative-control-in-windows-environments/"><u>Shifting Paradigms of Administrative Control in Windows Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-windows-no-internet-issue/"><u>Steps for Overcoming Windows No Internet Issue</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/your-device-pace-youtube-audio-control-guide-for-2024/"><u>Sync Your Device Pace YouTube Audio Control Guide for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-ultimate-chatbot-showdown-gpt-microsoft-bing-ai-google-bard/"><u>The Ultimate Chatbot Showdown: GPT, Microsoft Bing AI, Google Bard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/ultimate-guide-winx-mediatrans-top-choice-for-seamless-photos-and-video-transfer-between-iphone-ipad-and-pc/"><u>Ultimate Guide: WinX MediaTrans - Top Choice for Seamless Photos & Video Transfer Between iPhone, iPad, and PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    