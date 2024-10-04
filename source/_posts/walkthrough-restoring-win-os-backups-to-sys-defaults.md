---
title: "Walkthrough: Restoring Win OS Backups to Sys Defaults"
date: 2024-09-27T23:24:01.741Z
updated: 2024-10-03T17:03:58.141Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Walkthrough: Restoring Win OS Backups to Sys Defaults"
excerpt: "This Article Describes Walkthrough: Restoring Win OS Backups to Sys Defaults"
keywords: Windows Recovery,System Reset Guide,Revert Windows Settings,Backup to Default OS,WinXP Reset Tutorial,Restore Windows Defaults,XP Restoration Steps
thumbnail: https://thmb.techidaily.com/e9711d2ba9e06d496671fabcb5c03dc2cfd9b4b1eb26d7f5f5a9a68662ceb542.jpg
---

## Walkthrough: Restoring Win OS Backups to Sys Defaults

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-clear-facebook-broadcast-laptops-and-phones-included/"><u>[New] 2024 Approved Clear Facebook Broadcast Laptops and Phones Included</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-maximizing-performance-optimize-mov-files-in-win-11/"><u>[New] Maximizing Performance Optimize MOV Files in Win 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-step-by-step-tech-livestream-setup-pcmaclaptop-for-fb-for-2024/"><u>[New] Step-by-Step Tech Livestream Setup (PC/Mac/Laptop) for FB for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-dish-to-screen-your-recipe-video-blueprint-for-2024/"><u>[Updated] Dish to Screen Your Recipe Video Blueprint for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-embrace-tranquility-top-10-stress-free-games/"><u>[Updated] Embrace Tranquility Top 10 Stress-Free Games</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-navigating-zoom-for-seamless-fb-live-broadcasts/"><u>2024 Approved Navigating Zoom for Seamless FB Live Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-wmv-3gp/"><u>立即使用Movavi: 無限制的 WMV 至 3GP 免費線上轉換工具</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726220670341-mp3-movavi/"><u>無料オンラインで音楽ファイルを MP3にアップコンバートする - Movavi</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-practices-8-steps-for-digital-sound-preservation-for-2024/"><u>Best Practices 8 Steps for Digital Sound Preservation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/change-mp4x-to-matroska-mkv-files-for-free-with-movavis-online-tool/"><u>Change MP4X to Matroska (MKV) Files for Free with Movavi's Online Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converti-file-m4a-in-formato-mp3-di-fatto-a-secco-free-on-web/"><u>Converti File .m4a in Formato .mp3 Di Fatto a Secco - Free on Web</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-fitbit-versa-2-a-review-of-its-advanced-fitness-tracking-abilities-and-intelligent-watch-capabilities/"><u>Exploring the Fitbit Versa 2: A Review of Its Advanced Fitness Tracking Abilities & Intelligent Watch Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-convert-aifc-files-to-mp4-format-using-movavi/"><u>Free Online Converter - Convert AIFC Files to MP4 Format Using Movavi</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-top-10-best-gimbals-for-4k-dsrlmirrorless-cameras/"><u>In 2024, Top 10 Best Gimbals for 4K DSRL/Mirrorless Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-mpegmp4/"><u>Movavi로 인사이트: 인터넷축에서 무용화를 위해 MPEG/MP4 비디오 바꾸기 - 비용 효율적, 시작하기 쉽게</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-cost-mp3-encoder-transform-speech-and-ambient-sounds-with-movavis-web-tool/"><u>No-Cost MP3 Encoder: Transform Speech and Ambient Sounds with Movavi's Web Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-i-tuoi-video-conversione-mpeg-in-mp4-senza-costi-grazie-a-movavi-inizia-ora-la-tua-esperienza-gratuita/"><u>Trasforma I Tuoi Video: Conversione MPEG in MP4 Senza Costi Grazie a Movavi - Inizia Ora La Tua Esperienza Gratuita!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-fcpx-essential-adding-a-countdown-timer-in-just-3-clicks/"><u>Updated 2024 Approved FCPX Essential Adding a Countdown Timer in Just 3 Clicks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vrije-onlinelastellen-voor-omzetting-van-wma-naar-mp3-movavi-toolkit/"><u>Vrije Onlinelastellen Voor Omzetting Van WMA Naar MP3 - Movavi Toolkit</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    