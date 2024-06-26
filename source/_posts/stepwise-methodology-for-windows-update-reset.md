---
title: Stepwise Methodology for Windows Update Reset
date: 2024-06-25T16:51:22.998Z
updated: 2024-06-26T16:51:22.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stepwise Methodology for Windows Update Reset
excerpt: This Article Describes Stepwise Methodology for Windows Update Reset
keywords: Windows Update Revert,Windows Reset Guide,Update System Overhaul,PC Restart Protocols,Windows Patch Removal,Security Update Halt,OS Reboot Process
thumbnail: https://thmb.techidaily.com/f66305bee95e2c8cfda71737bc488d60f6c275330b2e729ec458216f465e024e.png
---

## Stepwise Methodology for Windows Update Reset

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
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenge-of-restarting-windows-sound-on-booting/"><u>Overcoming the Challenge of Restarting Windows Sound on Booting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unwanted-camera-request-errors-code-0xa00f4243/"><u>Removing Unwanted Camera Request Errors (Code 0xA00F4243)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fortify-windows-11-security-integrating-firewalls-into-the-menubar-ui/"><u>Fortify Windows 11 Security: Integrating Firewalls Into the Menubar UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-unlocking-stuck-battlenet-login/"><u>Expert Guide to Unlocking Stuck Battle.net Login</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-dissolving-ms-teams-error-80080300-on-win11-platform/"><u>Deciphering and Dissolving MS Teams Error 80080300 on Win11 Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-engage-window-management-feature-in-windows-11-end-task/"><u>How to Engage Window Management Feature in Windows 11 (End Task)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-computing-essential-windows-software-to-banish/"><u>Efficient Computing: Essential Windows Software to Banish</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-lost-connectivity-winos-strategies/"><u>Rebooting Lost Connectivity: WinOS Strategies</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-vivo-y78plus-t1-edition-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Vivo Y78+ (T1) Edition FRP In 3 Different Ways</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-best-gaming-intro-creators-for-windows-and-mac-free-and-paid-options/"><u>2024 Approved Best Gaming Intro Creators for Windows and Mac Free and Paid Options</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-essential-list-of-top-10-audio-editors-for-windows-and-mac-platforms-for-2024/"><u>The Essential List of Top 10 Audio Editors for Windows & Mac Platforms for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-plotting-the-perfect-tiktok-outro-journey-for-2024/"><u>[Updated] Plotting the Perfect TikTok Outro Journey for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/the-best-free-security-camera-programs-2023-reviews-and-ratings-for-2024/"><u>The Best Free Security Camera Programs 2023 Reviews and Ratings for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-vivo-x100-pro-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Vivo X100 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-unveiling-the-secrets-of-showmores-screen-capture-software-for-2024/"><u>[Updated] Unveiling the Secrets of ShowMore’s Screen Capture Software for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-apowersoft-examined-a-full-review-of-its-capabilities/"><u>2024 Approved  Apowersoft Examined  A Full Review of Its Capabilities</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>