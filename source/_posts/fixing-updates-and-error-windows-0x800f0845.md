---
title: "Fixing Updates and Error: Windows 0X800F0845"
date: 2024-06-25T16:25:45.883Z
updated: 2024-06-26T16:25:45.883Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Updates and Error: Windows 0X800F0845"
excerpt: "This Article Describes Fixing Updates and Error: Windows 0X800F0845"
keywords: Windows Update Fault Fix,Error Code 0X800F0845 Solution,XP OS Boot Failure,WinError Code Repair,Bootloader Update Issue,System Error Resolution,OS Reboot Troubleshooting
thumbnail: https://thmb.techidaily.com/ff2e2b344a8396c6bab8264d1025798025a6c7a29bed97ca0ab60000543775d0.jpg
---

## Fixing Updates and Error: Windows 0X800F0845

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the [many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on [CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the [Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://win11-tips.techidaily.com/novices-guide-to-easy-use-of-windows-accessibility/"><u>Novices' Guide to Easy Use of Windows Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-keep-lol-playtime-uninterrupted-in-windows/"><u>Strategies to Keep LoL Playtime Uninterrupted in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-complex-archives-efficiently-handling-multiple-zips-in-one-go/"><u>Decoding Complex Archives: Efficiently Handling Multiple ZIPS in One Go</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-archived-footage-boost-video-quality-using-madvr-on-windows/"><u>Reimagine Archived Footage: Boost Video Quality Using MadVR on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-primes-textual-missteps-on-windows-11-desktops/"><u>Correct Prime's Textual Missteps on Windows 11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-functionality-of-fn-keys-on-modern-pcs-windows-11/"><u>Configuring the Functionality of FN Keys on Modern PCs (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-reliable-clicks-and-movement-on-your-desktop/"><u>Ensuring Reliable Clicks & Movement on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-broken-exe-file-execution-on-pcs/"><u>Fix Broken Exe File Execution on PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-set-up-grid-layout-for-google-meet-participants-viewing/"><u>[New] Set Up Grid Layout for Google Meet Participants' Viewing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-the-ultimate-playbook-of-igtv-mastery-top-10-branding-techniques/"><u>[New] 2024 Approved  The Ultimate Playbook of IGTV Mastery  Top 10 Branding Techniques</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-optimize-your-tiktok-viewing-experience/"><u>[New] 2024 Approved  Optimize Your TikTok Viewing Experience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamlined-strategies-for-powerpoint-recordings-for-2024/"><u>Streamlined Strategies for PowerPoint Recordings for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masterclass-on-premiere-pro-fullscreen-mode-finesse/"><u>2024 Approved  Masterclass on Premiere Pro  Fullscreen Mode Finesse</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-11-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone 11 Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-enhancing-mobile-cinematography-the-top-9-accessories-reviewed/"><u>In 2024, Enhancing Mobile Cinematography - The Top 9 Accessories Reviewed</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/how-to-record-a-tiktok-all-about-tiktok-camera/"><u>How to Record a TikTok  All About TikTok Camera</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-iphone-x-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My iPhone X when Phone is Broken?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-utilizing-top-users-to-increase-visibility/"><u>[New] Utilizing Top Users to Increase Visibility</u></a></li>
</ul></div>
