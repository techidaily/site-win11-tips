---
title: Essential Tips for Using PowerShell to Unblock Files
date: 2024-08-16T02:35:20.283Z
updated: 2024-08-17T02:35:20.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips for Using PowerShell to Unblock Files
excerpt: This Article Describes Essential Tips for Using PowerShell to Unblock Files
keywords: PowerShell Blocking Removal,Unlock Files PowerShell,File Unblock Scripts PS,PowerShell Unblock Tools,PowerShell Cleanup Guide,Enable Files PS Command,Remove Restrictions with Powershell
thumbnail: https://thmb.techidaily.com/f93eb5bd46514b847ac07d099dc18d72eab724476fd27a01a5370f94ffa41df8.jpg
---

## Essential Tips for Using PowerShell to Unblock Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-authenticity-checks-on-instagram/"><u>[New] Mastering Authenticity Checks on Instagram</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-masterful-archive-of-twitter-animations-at-your-fingertips/"><u>[Updated] 2024 Approved  Masterful Archive of Twitter Animations at Your Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-express-individuality-with-youtube-backgrounds/"><u>2024 Approved  Express Individuality with YouTube Backgrounds</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-inside-vr-today-innovations-and-insights/"><u>2024 Approved  Inside VR Today  Innovations and Insights</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlock-youtube-broadcast-google-meet-tutorial-steps/"><u>2024 Approved  Unlock YouTube Broadcast  Google Meet Tutorial Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-make-windows-look-like-macos/"><u>5 Ways to Make Windows Look Like macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-new-features-the-moment-4-update-added-to-windows-11/"><u>7 New Features the Moment 4 Update Added to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/a-complete-guide-to-downloading-and-backup-of-instagram-vids-on-pcmacos/"><u>A Complete Guide to Downloading & Backup of Instagram Vids on PC/macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-dimension-in-windows-11-understanding-the-role-of-copilot-key/"><u>A New Dimension in Windows 11: Understanding the Role of Copilot Key</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-preparing-your-pc-before-win-upgrade/"><u>A Step-by-Step Guide to Preparing Your PC Before Win Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-operations-using-windows-task-scheduler/"><u>Accelerate System Operations Using Windows Task Scheduler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-network-configurations-in-win11/"><u>Accessing Network Configurations in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-nighttime-display-in-notepad-windows-11-edition/"><u>Activating Nighttime Display in Notepad Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-service-did-not-respond-issue-in-windows/"><u>Addressing Service Did Not Respond Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-user-permissions-issues-with-organizational-settings-in-windows-11/"><u>Addressing User Permissions Issues with Organizational Settings in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aligning-chrome-and-system-time-windows-sync-tips/"><u>Aligning Chrome and System Time (Windows Sync Tips)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-windows-11-outputs-with-savvy-techniques/"><u>Amplify Windows 11 Outputs with Savvy Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automated-awareness-quick-open-of-windows-and-sticky-notebooks/"><u>Automated Awareness: Quick Open of Windows and Sticky Notebooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-wifi-network-deletion-in-win-11/"><u>Automating Wifi Network Deletion in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-trouble-fixing-corrupted-recycle-bin-on-win1011/"><u>Avoid the Trouble: Fixing Corrupted Recycle Bin on Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327449344-bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-elusive-obs-recording-glitches-on-windows-operating-system/"><u>Beating Elusive OBS Recording Glitches on Windows Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-kept-secrets-eclectic-windows-11-styles/"><u>Best-Kept Secrets: Eclectic Windows 11 Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bitlocker-free-windows-4-effective-security-measures/"><u>BitLocker-Free Windows: 4 Effective Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-code-development-top-wls-2-methods-on-latest-oses/"><u>Boost Your Code Development: Top WLS 2 Methods on Latest OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-system-performance-with-advanced-virtual-memory-management-techniques/"><u>Boosting System Performance with Advanced Virtual Memory Management Techniques</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-c33-2023-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on C33 2023.</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/get-your-passport-featured-with-these-top-10-free-portrait-makers-for-2024/"><u>Get Your Passport Featured with These Top 10 Free Portrait Makers for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-add-divine-chant-to-smartphone-notifications/"><u>In 2024, How to Add Divine Chant to Smartphone Notifications</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nokia-105-classic-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Nokia 105 Classic to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-vivo-y36-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Vivo Y36 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-m6-pro-4g-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on M6 Pro 4G</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-oppo-a78-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Oppo A78 5G Hard Reset | Dr.fone</u></a></li>
</ul></div>
