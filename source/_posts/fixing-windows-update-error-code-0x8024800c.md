---
title: Fixing Windows Update Error Code 0X8024800C
date: 2024-06-25T16:50:00.901Z
updated: 2024-06-26T16:50:00.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Windows Update Error Code 0X8024800C
excerpt: This Article Describes Fixing Windows Update Error Code 0X8024800C
keywords: WinUpdateErrorCode0x8024800C,FixWindowsUpdateErr,Err0X8024UpdateWin,WindowsUpdateFix0X8024,Solve0X8024WindowsErr,ErrorCode0X8024Win,0X8024WindowsErrorRepair
thumbnail: https://thmb.techidaily.com/b0e0b3709f1348652118c2459af9389796059e0f6579c4e1ae20b05da950739b.jpg
---

## Fixing Windows Update Error Code 0X8024800C

 Windows Update is usually dependable, but errors can cause problems. Error 0x8024800C is one such issue that can make updating your Windows OS difficult. This post will guide you through troubleshooting steps to resolve it. Keep reading to find out how.

## What Causes Windows Update Error 0x8024800C?

 Windows Update error 0x8024800C is usually caused by corrupted or damaged system files in the Windows Update Temporary folder, located at "C:\\Windows\\SoftwareDistribution\\Download."

 You may also experience this error if third-party software conflicts with Windows Update or if your internet connection is down. Here are some possible causes.

1. An incomplete or corrupt download of a Windows Update.
2. Insufficient storage space on the system drive.
3. Outdated Windows Update Components.
4. Issues with your internet connection, such as slow connectivity.
5. Third-party software interferes with Windows Update.

 Having explored the causes, let's now see how to fix this problem.

## 1\. Check Your Internet Connection

 If you aren't able to download Windows updates, check your internet connection first. Chances are that a slow or unstable internet connection is causing this error. To test your connection, try accessing other websites in your browser. If you have a fine internet connection, but it's very slow, you just need to [troubleshoot your network](https://www.makeuseof.com/things-slowing-down-home-wifi-network/).

## 2\. Restart Your Computer and Try Again

 Sometimes, a simple restart can fix minor computer issues. It may also help if you experience system instability or frequently encounter this error. Restarting your computer will refresh the system, clearing out any corrupted data that may have caused this issue. So before proceeding, [restart your computer](https://www.makeuseof.com/windows-restart-methods/) and try updating again.

## 3\. Run the Windows Update Troubleshooter

 Windows has a built-in troubleshooter tool that identifies and resolves common Windows Update problems. Here’s how to use it:

1. Press **Win + R** on your keyboard to open the Run box.
2. Type **ms-settings:** in the text box and click **OK**.
3. From the left sidebar, click the **System** tab.
4. Now move to the right pane and click **Troubleshoot > Other troubleshooters**.  
![Other trouble-shooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-trouble-shooters.jpg)
5. Click the **Run** button next to Windows Update.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-windows-update-troubleshooter.jpg)

 After following the above steps, the troubleshooter will scan your system for errors. When it’s done, the troubleshooter will present you with any solutions it finds. Follow the on-screen instructions and apply any recommendations to fix the problem.

## 4\. Clear the SoftwareDistribution Folder

 The Software Distribution folder is where Windows stores data related to updates. It includes temporary files and download logs. Corrupted or missing system files in this folder can cause the 0x8024800C issue. To fix it, you must delete these files from your system. Here’s how:

 To get started, [open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/). Once you're in an elevated command prompt window, run the following command:

`net stop wuauserv  
net stop bits`

 This will halt the Windows Update service and the Background Intelligent Transfer Service.

 Now use the **Win + E** shortcut key to open File Explorer. Then navigate to the "C:\\Windows\\SoftwareDistribution" folder and delete all its contents. You don't need to delete the folder itself; just the files within it.

![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)

 Once you're done, go back to the Command Prompt and type the following commands:

`net start wuauserv  
net start bits`

 This will restart the Windows Update service and the Background Intelligent Transfer Service. Now try downloading updates for your computer.

## 5\. Disable Third-Party Antivirus Software Temporarily

 If you're experiencing problems updating Windows, your antivirus might be the culprit. These programs can sometimes interfere with Windows Update components, causing errors like 0x8024800C. To be sure, we recommend [disabling your antivirus temporarily](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and checking if this solves the issue.

## 6\. Reset Windows Update Components

 It seems that Windows Update components are corrupted or damaged, leading to this issue. To resolve it, you will have to reset them and fix any broken files.

 To reset Windows Update Components, follow these steps:

1. Click Start and type **Notepad** in the search box.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. If you see a UAC prompt, click **Yes** to confirm.
4. Now in Notepad, copy and paste the following command:  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
5. Click **File** in the menu bar and select **Save As**.
6. In the dialog box that appears, set the Save as type to **All Files**.
7. Name your file **WUReset.bat** and save it on your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-update-components.jpg)
8. Once you have created the file, right-click on it and choose **Run as administrator**.
9. If you see a UAC prompt, click **Yes** to confirm.

 This will reset the Windows Update components and fix the 0x8024800C error. After that, you can try updating Windows again.

## 7\. Perform Some Generic Fixes

 After trying all of the above solutions, you should also try some generic fixes. This includes [running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to repair corrupted system files and running Disk Cleanup to [remove unnecessary junk files](https://www.makeuseof.com/windows-10-remove-junk-files/). You may also want to use the Deployment Image Servicing and Management tool to repair corrupt system images.

 If the problem isn't fixed, you can [try either system restore](https://www.makeuseof.com/windows-11-create-restore-point/) or reinstalling Windows. These options will reset your computer to its original settings, which will most likely resolve any software-related problems. And remember to [back up your Windows data](https://www.makeuseof.com/tag/backup-windows-computer-cloud/) before trying these solutions so you have something to fall back on if something goes wrong.

## Fixing Windows Update Error 0x8024800C

 Having trouble downloading and installing Windows updates? You might be facing Windows Update Error 0x8024800C, which prevents your PC from accessing the latest updates and security patches. Thankfully we have some easy solutions that may help you fix this error code on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/remedying-stalled-amd-driver-in-windows-environment/"><u>Remedying Stalled AMD Driver in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-chrome-clock-error-ahead-or-behind-windows-edition/"><u>Adjusting Chrome Clock Error: Ahead or Behind? (Windows Edition)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-rectifications-quick-tricks-to-prevent-windows-crashes-in-games/"><u>Rapid Rectifications: Quick Tricks to Prevent Windows Crashes in Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-fix-guide-combatting-a-non-active-wsresetexe/"><u>The Ultimate Fix Guide: Combatting a Non-Active WSReset.exe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screenscape-symphony-composing-personalized-displays-in-windows-1011/"><u>Screenscape Symphony: Composing Personalized Displays in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-link-mastery-8-powerful-free-extractor-tools-for-2024/"><u>[Updated] FB Link Mastery  8 Powerful FREE Extractor Tools for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-tecno-spark-10c-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Tecno Spark 10C Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-avi-video-editor-for-windows-8-latest-2023-update-for-seamless-editing/"><u>Updated AVI Video Editor for Windows 8 Latest 2023 Update for Seamless Editing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-full-spectrum-review-exploring-digital-performances-evolution/"><u>[New] In 2024, Full Spectrum Review  Exploring Digital Performance's Evolution</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-from-youtube-to-mp3-how-to-choose-a-safe-and-efficient-converter/"><u>New 2024 Approved From YouTube to MP3 How to Choose a Safe and Efficient Converter</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-everything-from-apple-iphone-6-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Everything from Apple iPhone 6 to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-budget-pc-screen-capture-apps/"><u>In 2024, Budget PC Screen Capture Apps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-gamer-centric-streaming-tool-selection/"><u>In 2024, Gamer-Centric Streaming Tool Selection</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>