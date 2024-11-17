---
title: Tackling OneDrive Issue in W11 - The 9 Fixes Approach
date: 2024-11-12T18:35:39.641Z
updated: 2024-11-17T16:23:04.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling OneDrive Issue in W11 - The 9 Fixes Approach
excerpt: This Article Describes Tackling OneDrive Issue in W11 - The 9 Fixes Approach
keywords: Windows W11 Drive Issues,OneDrive W11 Solutions,Fix OneDrive Errors,W11 OneDrive Problems,Resolve Office Save Issue,Streamline OneDrive Fixes,W11 Office Sync Troubleshooting
thumbnail: https://thmb.techidaily.com/6669b51a644a6e6a471c5e95129c578aa098ea11ffbe838822c268118ff95e70.jpg
---

## Tackling OneDrive Issue in W11 - The 9 Fixes Approach

 Microsoft bundles OneDrive with Windows 11 by default. Despite not being the most popular cloud storage service, it's hard to ignore its 5 GB free cloud storage offer. It's less than Google Drive but still lucrative because it's built into Windows.

 However, some users face the infuriating error code 0x8004def5 whenever they try to launch it. The error code indicates a problem in establishing a connection with OneDrive.

 If you face the same error and cannot log in and access your OneDrive account, don't worry. We will list out multiple methods to restore OneDrive to its working state. Let's begin.

## 1\. Terminate OneDrive and Restart the App

 Before trying out any complex fixes, you must terminate all the active instances of OneDrive. After that, restart it to check if it connects with the server. Here's how:

1. Press**Ctrl + Shift + Esc** to[open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) .
2. Go to the top search bar and type**OneDrive** .
3. Switch to the**Details** tab. Right-click on the**OneDrive.exe** process and select the**End process tree** option from the context menu.
4. A popup window will launch. Click on the**End process tree** option.  
![Terminate OneDrive and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/terminate-onedrive-and-restart.jpg)
5. Open the Start menu and type OneDrive. Click on the**Open** option and check if the error pops up.

## 2\. Check if OneDrive Servers Are Down

 OneDrive stores all your data in a dedicated cloud server maintained by Microsoft. Despite promising 99% uptime, it is common for cloud services like OneDrive to encounter outages. Or the service could be down due to scheduled maintenance.

 You can visit the[Microsoft Service Health page](https://portal.office.com/servicestatus) to check which services are down. Alternatively, you can use third-party websites like[DownDetector](https://downdetector.com/) . That way, you can know if other users also face the same server outage issue. If that's the case, you have to wait until Microsoft resolves the problem and brings up the OneDrive servers again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Completely Shut Down and Reboot Your Computer

 Background services are susceptible to glitches and crashes. If one or more such essential services encounter a glitch, it can impede apps that rely on them. However, Windows 11 enables Fast Startup by default which preserves the state of all system and kernel processes for speeding up boot time.

 Even if you shut down the system, it will not close and restart all processes and services. So, you must perform a complete shutdown. Repeat the following steps to do so:

1. Press**Win + R** to open the Run command box. Type**cmd** and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Now, type the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a complete system shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/perform-a-complete-system-shutdown.jpg)
3. A complete shutdown will take longer than usual. Wait for the system to Restart and boot to the desktop.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Now, launch OneDrive and check if you can access your files.

## 4\. Switch Network Connections

 It is possible that your current ISP, or the network you are connected to, blocks Microsoft's servers. Many users shared they were able to fix the issue when they switched to another network. You can simply create a wireless hotspot from your phone or use USB tethering to share the internet with your Windows computer.

 After that, relaunch the OneDrive app and check if you can access your files on the network. You can also request your ISP to remove the block on your connection to access the OneDrive servers seamlessly in the future.

## 5\. Clear OneDrive Logs

 You can try clearing OneDrive telemetry log files in the app data folder. Here's how to do it:

1. Press**Win + E** to[open the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, type the following path, and replace the "**UserName** " with your PC's username:  
C:\Users\UserName\AppData\Local\Microsoft\OneDrive\setup\logs
3. Press the enter key to navigate to the OneDrive logs folder.
4. Locate the**userTelemetryCache.otc** file and copy it.**Paste** it to any other disk drive on your system.
5. Return to the logs folder and**delete** the**userTelemetryCache.otc** file.  
![Clear OneDrive Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-onedrive-logs.jpg)
6. Close the File Explorer and restart your system.
7. Launch OneDrive and then check if it encounters the same error code.

## 6\. Reset OneDrive

 You can reset some Windows apps by accessing their advanced settings. But OneDrive doesn't have an advanced settings option in the Settings app. So, you need to reset it manually using the command prompt. Here's how:

1. Press**Win + R** to open the Run command box. Type**cmd** and press the Enter key to open a new Terminal window.
2. Type the following command and press the enter key:  
%localappdata%\Microsoft\OneDrive\onedrive.exe /reset
3. Wait for the command to reset OneDrive. You will see the OneDrive window popup informing you that the reset is underway.  
![Reset OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-onedrive-1.jpg)
4. Close the app after you see the "Reset completed" message. Restart your system.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Reinstall OneDrive Using Winget

 If resetting the app didn't work, consider a complete reinstall. It will fix any underlying corruption with the app files and install the latest version on your system. Here's how to do it with the Winget tool:

1. Press**Win + R** to open the Run command box. Type**cmd** in the text box and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Type the**winget list onedrive** command and press the enter key.**Copy** the**ID** of the OneDrive app.
3. Now, run the**winget uninstall** command with the OneDrive app ID. This is what it will look like:**Winget uninstall Microsoft.OneDrive**
4. Wait for winget to remove OneDrive from your system. To confirm the uninstallation, type the following command:**winget list onedrive**
5. You will see that no package named OneDrive is not present on your system.  
![Reinstall OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-1.jpg)

1. Type**cls** to clear the command prompt window.
2. Now, input the following command and press the enter key:**winget install Microsoft.OneDrive**  
![Reinstall OneDrive 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-2.jpg)
3. Wait for the tool to download and install OneDrive on your system. You don't need to interact with the installer.
4. **Close** the command prompt window after seeing the "**Successfully installed** " message.
5. Launch OneDrive. You will have to**sign in** with your account.
6. Check if you can connect and browse your files.

## 8\. Rollback Windows Updates

 New Windows updates can sometimes wreck your system and break app compatibility. If OneDrive runs fine before installing a new update,[roll back the Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) . It could take longer if the update file is too big and not all Windows updates can be undone. After that, restart your system and try running the OneDrive app.

## 9\. Restore or Reset the PC

 If you still face the OneDrive error code, it's time to[perform a System Restore or a Windows Reset](https://www.makeuseof.com/windows-reset-system-restore-difference/) . It will help you revert to an old but working system configuration when OneDrive was working fine. Look for the most recent restore point in the wizard and use that.[Perform a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) only if you don't have any Windows Restore points available.

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

## Make OneDrive Functional Again

 OneDrive can fail to connect with the server for a variety of reasons. Start with basic troubleshooting and check if the OneDrive servers are active. After that, delete the telemetry log files and reset the app. If that has no impact, reinstall the OneDrive app and log in again.

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
<li><a href="https://youtube-data.techidaily.com/ideo-text-synthesizer/"><u>[New] Video Text Synthesizer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-lava-storm-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Lava Storm 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-hardware-tips-and-tricks-from-tomntech-expertise/"><u>Advanced Hardware Tips and Tricks From Tom'nTech Expertise</u></a></li>
<li><a href="https://win-advanced.techidaily.com/amplitude-variation/"><u>Amplitude Variation</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-infinix-smart-8-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Infinix Smart 8 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/declutter-your-notebooks-visual-techniques-in-obsidian/"><u>Declutter Your Notebooks: Visual Techniques in Obsidian</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-unilateral-windows-headset-defects/"><u>Diagnosing Unilateral Windows Headset Defects</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/distinctive-fb-video-aspects/"><u>Distinctive FB Video Aspects</u></a></li>
<li><a href="https://sound-issues.techidaily.com/effective-fixes-for-no-sound-in-nvidia-high-definition-audio-systems/"><u>Effective Fixes for 'No Sound' In Nvidia High Definition Audio Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-file-management-windows-11-guide/"><u>Enhancing File Management: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-security-controls-for-typical-windows-accounts/"><u>Enhancing Security Controls for Typical Windows Accounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-software-interaction-winshortcut-guide/"><u>Enhancing Software Interaction: WinShortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-inserting-secure-passwords-into-texts-win-style/"><u>Expert Tips for Inserting Secure Passwords Into Texts, Win-Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-pinpoint-and-tackle-large-disk-space-users/"><u>How to Pinpoint and Tackle Large Disk Space Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-honor-play-40c-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Honor Play 40C PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/limiting-removable-storage-on-windows-without-compromise/"><u>Limiting Removable Storage on Windows Without Compromise</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726225527798-movavi/"><u>Movaviで効果的な画像タイトル追加ガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/powertoys-made-simple-text-pasting-tips/"><u>PowerToys Made Simple: Text Pasting Tips</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210761795-9781591798590-the-mystery-of-2012/"><u>The Mystery of 2012 | Free Book</u></a></li>
</ul></div>

