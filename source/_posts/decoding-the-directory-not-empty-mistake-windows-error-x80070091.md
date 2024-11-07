---
title: "Decoding the 'Directory Not Empty' Mistake: Windows Error X80070091"
date: 2024-11-05T19:38:47.585Z
updated: 2024-11-07T08:04:28.756Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding the 'Directory Not Empty' Mistake: Windows Error X80070091"
excerpt: "This Article Describes Decoding the 'Directory Not Empty' Mistake: Windows Error X80070091"
keywords: Windows Error X8007,Directory Full Error,File Upload Failure,X80070091 Solution,Empty Folder Error,System Access Mistake,Unpacking Files Issue
thumbnail: https://thmb.techidaily.com/637640ea893a93e111b973883d0f05d3166b54a33cafa8864cd2873a58b515ce.png
---

## Decoding the 'Directory Not Empty' Mistake: Windows Error X80070091

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  

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

![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  

![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-10-best-free-photo-collage-apps-for-iphone/"><u>[New] 2024 Approved 10 Best FREE Photo Collage Apps for iPhone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/deal-7-digital-photography-devices-for-high-quality-video-streams/"><u>[New] Ideal 7 Digital Photography Devices for High-Quality Video Streams</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/op-10-ultimate-apps-for-seamless-youtube-to-webm-conversion/"><u>[New] Top 10 Ultimate Apps for Seamless YouTube to WebM Conversion</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-optimize-iphoneandroid-video-quality-in-online-platforms-for-2024/"><u>[Updated] Optimize iPhone/Android Video Quality in Online Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-ultimate-guide-to-monetizing-youtube-content-2024-edition/"><u>[Updated] The Ultimate Guide to Monetizing YouTube Content - 2024 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-a-symbiotic-space-between-android-and-windows-11-desktops/"><u>Crafting a Symbiotic Space Between Android and Windows 11 Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cryptic-control-center-elusive-power-button-on-desktop/"><u>Cryptic Control Center: Elusive Power Button on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-pc-ready-for-win-11-essential-usb-setup-strategies/"><u>Get Your PC Ready for Win 11: Essential USB Setup Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-missing-d3dx939-dll-win11-edition/"><u>How to Rectify Missing D3DX9_39 DLL, Win11 Edition</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/lexar-device-connection-made-easy-swift-installation-for-usb-drivers/"><u>Lexar Device Connection Made Easy: Swift Installation for USB Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-firewall-and-network-settings-visibility/"><u>Navigating Windows Firewall & Network Settings Visibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-unsupported-boots-with-these-5-secure-fixes-for-windows/"><u>Overcome Unsupported Boots with These 5 Secure Fixes for Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/streamlining-the-process-for-free-pictured-frame-files/"><u>Streamlining the Process for Free Pictured Frame Files</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/strengthen-your-icloud-account-with-dual-authentication-steps/"><u>Strengthen Your iCloud Account with Dual Authentication Steps</u></a></li>
<li><a href="https://some-guidance.techidaily.com/twitch-recapture-method-restart-livestreams-for-2024/"><u>Twitch Recapture Method Restart Livestreams for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/ultimate-guide-to-top-6-creative-mojave-dwellings-for-2024/"><u>Ultimate Guide to Top 6 Creative Mojave Dwellings for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-efficient-storage-space-in-windows-11/"><u>Unlock Potential: Efficient Storage Space in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-sticky-notes-access-made-simple/"><u>Windows 11 Sticky Notes Access Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wintech-recovering-lost-command-logs/"><u>WinTech: Recovering Lost Command Logs</u></a></li>
</ul></div>

