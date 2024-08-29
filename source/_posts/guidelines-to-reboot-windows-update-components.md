---
title: Guidelines to Reboot Windows Update Components
date: 2024-08-28T01:16:55.880Z
updated: 2024-08-29T01:16:55.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Reboot Windows Update Components
excerpt: This Article Describes Guidelines to Reboot Windows Update Components
keywords: Windows Update Guide,Rebooting Updates,Fixing Windows Updates,Updating Windows Procedures,Windows Update Reset,System Restart Tips,Windows Components Overhaul
thumbnail: https://thmb.techidaily.com/23c1e788c86a1fe74b0e576c3c163c7e8cc36d0f77392a611796a9122444764d.jpg
---

## Guidelines to Reboot Windows Update Components

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

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-insta-twist-techniques-manual-flipping-photos-and-videos-for-social-media-success/"><u>[New] In 2024, The Insta Twist Techniques Manual  Flipping Photos and Videos for Social Media Success</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-scan-and-store-your-old-printed-photos/"><u>[Updated] How to Scan and Store Your Old Printed Photos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-gionee-f3-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Gionee F3 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-getting-started-with-itunes-podcasts-on-ios-devices/"><u>2024 Approved  Getting Started with iTunes Podcasts on iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now</u></a></li>
<li><a href="https://fox-info.techidaily.com/comprehensive-guide-to-srgb-and-rgb/"><u>Comprehensive Guide to Srgb & Rgb</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-spotlight-screenshot-preferences-efficiently-in-windows/"><u>Configure Spotlight Screenshot Preferences Efficiently in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-stealth-network-safeguarding-in-windows-settings/"><u>Crafting Stealth Network Safeguarding in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-era-compatibility-using-windows-7-product-key-in-11/"><u>Cross-Era Compatibility: Using Windows 7 Product Key in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-usage-by-microsoft-edges-view2/"><u>Decoding Windows Memory Usage by Microsoft Edge's View2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deployment-guide-for-intel-networking-on-ubuntu/"><u>Deployment Guide for Intel Networking on Ubuntu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/devhomes-blueprint-for-cutting-edge-w11-living/"><u>DevHome's Blueprint for Cutting-Edge W11 Living</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-pcs-appeal-animated-backgrounds-in-windows-11/"><u>Elevate Your PC's Appeal: Animated Backgrounds in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-fixing-authentication-in-windows-os/"><u>Essential Guide to Fixing Authentication in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-ensure-your-surfaces-software-stays-current/"><u>Expert Tips to Ensure Your Surface's Software Stays Current</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unsuccessful-execution-of-high-privileges-tasks/"><u>Fixing Unsuccessful Execution of High Privileges Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-generic-volume-controller-malfunction/"><u>Fixing Windows Generic Volume Controller Malfunction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-save-location-errors-in-windows-pcs/"><u>How to Correct Save Location Errors in Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-frozen-itunes-on-your-windows-system/"><u>How to Tackle Frozen iTunes on Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-hidden-5ghz-networks-in-windows-11-using-7-tips/"><u>How to Uncover Hidden 5GHz Networks in Windows 11 Using 7 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-simultaneous-zip-file-extraction-in-windows/"><u>Master the Art of Simultaneous ZIP File Extraction in Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/masterclass-top-10-recorder-options-on-spotify-for-2024/"><u>Masterclass Top 10 Recorder Options on Spotify for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-clock-screen-protectors-for-windows-users/"><u>Masterful Clock Screen Protectors for Windows Users</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-palworld-login-failures-for-eos-users-discover-these-6-critical-solutions/"><u>Mastering PalWorld Login Failures for EOS Users: Discover These 6 Critical Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-fixes-to-common-windows-11-problems/"><u>Mastering Quick FIXES to Common Windows 11 Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-installation-with-windows-11-fixer/"><u>Mastering Software Installation with Windows 11 Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-empty-directory-claim-in-windows-with-error-0x80070091-resolutions/"><u>Overcome the Empty Directory Claim in Windows with Error 0X80070091 Resolutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-no-projector-found-message-in-windows/"><u>Overcoming No Projector Found Message in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unable-to-link-error-guide-for-nvidia-experience-on-windows-11/"><u>Overcoming Unable to Link Error: Guide for Nvidia Experience on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-update-error-0x80073712/"><u>Quick Fix for Windows Update: Error 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-dealing-with-network-failures-on-windows-11-devices/"><u>Quick Fix: Dealing with Network Failures on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-lost-internet-connection/"><u>Quick Fixes for Lost Internet Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-enabling-restore-and-recovery-tools/"><u>Quick Guide: Enabling Restore & Recovery Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rapid-methods-to-discover-windows-vocabulary/"><u>Rapid Methods to Discover Windows Vocabulary</u></a></li>
<li><a href="https://win11-tips.techidaily.com/returning-your-windows-system-backup-to-start/"><u>Returning Your Windows System Backup to Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-xbox-app-glitches-in-windows/"><u>Revive Your Xbox App Glitches in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-integration-of-files-in-win-11-os/"><u>Seamless Integration of Files in Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-web-browsing-with-win-10s-safeguard/"><u>Securing Web Browsing with Win 10'S SafeGuard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-wi-fi-connectivity-puzzles-clarifying-incomplete-instructions/"><u>Solving Wi-Fi Connectivity Puzzles: Clarifying Incomplete Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-handle-not-handled-interrupt-in-windows-systems/"><u>Steps to Handle Not Handled Interrupt in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-virtual-machines-physical-ram-shortage-issue/"><u>Tackling Virtual Machine's Physical RAM Shortage Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-enhancing-usability-with-narrator/"><u>The Ultimate Guide to Enhancing Usability with Narrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-non-responsive-key-to-control-display-brightness-on-windows-11/"><u>Unblocking Non-Responsive Key to Control Display Brightness on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-privacy-concerns-in-using-chatgpt-technology/"><u>Understanding Privacy Concerns in Using ChatGPT Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninstalling-and-reinstalling-troubled-apps-in-windows/"><u>Uninstalling and Reinstalling Troubled Apps in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-creativity-incorinasive-use-of-luts-in-video-editing/"><u>Unlocking Creativity  Incorinasive Use of LUTs in Video Editing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-your-ip-terminal-window-steps/"><u>Unveiling Your IP: Terminal Window Steps</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-elevate-your-video-storytelling-with-professional-voiceovers-for-2024/"><u>Updated Elevate Your Video Storytelling with Professional Voiceovers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>