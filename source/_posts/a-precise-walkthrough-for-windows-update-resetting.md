---
title: A Precise Walkthrough for Windows Update Resetting
date: 2024-07-03T12:43:33.907Z
updated: 2024-07-04T12:43:33.907Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Precise Walkthrough for Windows Update Resetting
excerpt: This Article Describes A Precise Walkthrough for Windows Update Resetting
keywords: Windows Update Fix,Reset Windows Update,Guide to Updater Reset,Clearing Windows Update,Update Process Re-Initiate,Windows Update Troubleshoot,System Update Recalibration
thumbnail: https://thmb.techidaily.com/14598feaeb4d0e61d08a761998cd6976c067dba5c944d538d367654e5b9adad2.jpg
---

## A Precise Walkthrough for Windows Update Resetting

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
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
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
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
cd /d %windir% system32  
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
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.
6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/re-establishing-backup-routine-for-nvidia-panel-configurations/"><u>Re-Establishing Backup Routine for Nvidia Panel Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathing-life-into-your-inactive-windows-11-wi-fi-hotspot/"><u>Breathing Life Into Your Inactive Windows 11 Wi-Fi Hotspot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-default-silence-camera-activation-in-win11/"><u>Breaking the Default Silence: Camera Activation in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solution-to-windows-os-not-found-error/"><u>Swift Solution to Windows OS 'Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-temporary-file-error-1152-on-windows/"><u>Remedying Temporary File Error 1152 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-repair-code-0xc00ce556-on-windows/"><u>Mastering Error Repair: Code 0xC00CE556 on WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-revolutionize-your-videos-top-10-free-green-screen-apps-for-mobile/"><u>Updated Revolutionize Your Videos Top 10 Free Green Screen Apps for Mobile</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-utilizing-continuous-lights-for-comfortable-filming/"><u>In 2024, Utilizing Continuous Lights for Comfortable Filming</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/where-is-the-best-place-to-catch-dratini-on-realme-c51-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-elite-circle-of-digital-titling-top-5-revealed/"><u>The Elite Circle of Digital Titling  Top 5 Revealed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-easywebcamusage-recordingtipsandtricks/"><u>[New] In 2024, EasyWebCamUsage  RecordingTipsAndTricks</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-leveraging-hashtags-in-twitter-advertising/"><u>[Updated] In 2024, Leveraging Hashtags in Twitter Advertising</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-dissecting-the-power-of-discords-nitro-elite-service-explained-and-acquisition-guide/"><u>[New] Dissecting the Power of Discord's Nitro  Elite Service Explained & Acquisition Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/your-quick-guide-to-google-voice-call-history-for-2024/"><u>Your Quick Guide to Google Voice Call History for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-quick-acting-impression-review/"><u>[Updated] In 2024, Quick Acting Impression Review</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>