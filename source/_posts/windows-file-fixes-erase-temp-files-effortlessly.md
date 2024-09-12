---
title: "Windows File Fixes: Erase Temp Files Effortlessly"
date: 2024-09-11T01:20:43.412Z
updated: 2024-09-12T01:20:43.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows File Fixes: Erase Temp Files Effortlessly"
excerpt: "This Article Describes Windows File Fixes: Erase Temp Files Effortlessly"
keywords: Windows Temp Fixed,Erase Temp Files,Temp File Cleanup,Windows Temp Delete,Fast File Cleaning,System Temp Clear,Effortless Temp Erase
thumbnail: https://thmb.techidaily.com/5ee746dbc8ada474503544ca04e806e436db5d4104755754e528cce96e41f403.jpg
---

## Windows File Fixes: Erase Temp Files Effortlessly

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135395/19272" target="_top" id="2135395">
  <img src="//a.impactradius-go.com/display-ad/19272-2135395" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135395/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)





<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.





<!-- affiliate ads begin -->
<span id="1982462">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982462%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982462/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-10-essential-cam-shields-for-privacy/"><u>[New] 10 Essential Cam Shields for Privacy</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-bestiary-of-ios-ps2-game-simulators/"><u>[New] Bestiary of iOS PS2 Game Simulators</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-macs-finest-for-gif-saving-the-leading-apps/"><u>[New] Mac's Finest for GIF Saving The Leading Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/1716068661379-updated-2024-approved-top-12-capture-providers-never-stop/"><u>[Updated] 2024 Approved Top 12 Capture Providers, Never Stop!</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-analyzing-time-of-playback-in-a-20mb-film-for-2024/"><u>[Updated] Analyzing Time of Playback in a 20Mb Film for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-tips-and-tricks-how-to-choose-a-winner-amongst-360-degree-cameras/"><u>[Updated] Tips & Tricks How to Choose a Winner Amongst 360-Degree Cameras</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-unlocking-the-full-potential-of-obs-on-mac/"><u>[Updated] Unlocking the Full Potential of OBS on Mac</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-poco-f5-pro-5g-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Poco F5 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/antimalware-resource-hog-turn-it-off-for-better-performance/"><u>Antimalware Resource Hog: Turn It Off for Better Performance</u></a></li>
<li><a href="https://extra-hints.techidaily.com/apply-photo-motion-blur-in-adobe-photoshop-for-2024/"><u>Apply Photo Motion Blur in Adobe Photoshop for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/code-refreshments-vs-big-leap-system-changes/"><u>Code Refreshments Vs. Big-Leap System Changes</u></a></li>
<li><a href="https://article-tips.techidaily.com/comprehensive-insight-into-the-ultra-clear-lg-monitor-for-2024/"><u>Comprehensive Insight Into the Ultra-Clear LG Monitor for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/detailed-tutorial-reactivating-the-dolby-audio-driver-when-encountered-with-errors-in-windows-11/"><u>Detailed Tutorial: Reactivating the Dolby Audio Driver When Encountered with Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disconnecting-guests-from-windows-protocols/"><u>Disconnecting Guests From Windows Protocols</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-efficient-solutions-the-best-10-uses-for-powertoy-features/"><u>Discover Efficient Solutions: The Best 10 Uses for PowerToy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-how-to-modify-window-glow-on-your-pc/"><u>Discover How to Modify Window Glow on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-data-management-linking-onedrive-and-microsoft/"><u>Effortless Data Management: Linking OneDrive and Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-reading-view-as-default-in-word-for-email-attachments/"><u>Enabling Reading View as Default in Word for Email Attachments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-microsofts-smartfilter-in-win11/"><u>Enabling/Disabling Microsoft’s SmartFilter in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-side-by-side-fault-in-windows/"><u>Eradicating Side-by-Side Fault in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-techniques-for-calls-tracking/"><u>Essential Windows Techniques for Calls Tracking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-hidden-5ghz-network-issues-in-windows-11-effectively/"><u>Fix Hidden 5GHz Network Issues in Windows 11 Effectively</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/freelancers-guide-to-mastering-ai-assistantsbing-chat-vs-chatgpt/"><u>Freelancer's Guide to Mastering AI Assistants—Bing Chat Vs. ChatGPT</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-excel-2003-run-time-error-1004-by-stellar-guide/"><u>How to Fix Excel 2003 Run Time Error 1004</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-restore-and-replace-a-lost-d3d9dll-file-effectively/"><u>How to Restore and Replace a Lost d3d9.dll File Effectively</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-vivo-y17s-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Vivo Y17s online without jailbreak</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-itel-a60-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Itel A60 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-full-guide-to-bypass-meizu-21-pro-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Meizu 21 Pro FRP</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pro-photo-and-video-with-gopro-hero5-black-mastery-essentials/"><u>In 2024, Pro Photo & Video with GoPro Hero5 Black Mastery Essentials</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-srt-fundamentals-explored-in-detail-and-clarity/"><u>In 2024, SRT Fundamentals Explored in Detail and Clarity</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-itel-p40plus-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Itel P40+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-approaches-to-using-ping-in-modern-windows-os/"><u>Innovative Approaches to Using Ping in Modern Windows OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/issue-corrected-windows-10-monitor-displays-only-portion-of-windows/"><u>Issue Corrected - Windows 10 Monitor Displays Only Portion of Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-microsofts-mspcm-toolbar-on-w11-os/"><u>Leveraging Microsoft's MSPCM Toolbar on W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsofts-family-safety-landscape/"><u>Navigating Microsoft's Family Safety Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-a-complete-guide-to-folder-resetting-in-win-11/"><u>OneDrive: A Complete Guide to Folder Resetting in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-pc-resources-tackling-high-usage-by-multimedia-tasks/"><u>Optimize PC Resources: Tackling High Usage by Multimedia Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disabled-file-consolidation-feature/"><u>Overcoming Disabled File Consolidation Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-xp-error-code-0xfffffddd/"><u>Overcoming Window's XP Error Code 0xFFFFFDDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-defender-footprint-in-windows-systems/"><u>Overhauling Your Defender Footprint in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommendations-for-setting-a-preferred-cli-window/"><u>Recommendations for Setting a Preferred CLI Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-1011s-defender-record-simple-guide/"><u>Resetting Windows 10/11'S Defender Record - Simple Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-way-to-construct-a-windows-speech-recognition-app-using-autohotkey/"><u>Simple Way to Construct a Window's Speech Recognition App Using AutoHotkey</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-enabling-and-using-hyper-v-on-w11-homes/"><u>Step-by-Step Guide to Enabling and Using Hyper-V on W11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-extending-hard-drive-size-at-zero-cost-in-windows/"><u>Strategies for Extending Hard Drive Size at Zero Cost in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-that-clear-up-common-system-errors/"><u>Strategies that Clear Up Common System Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-win11-mouse-access-for-comfort/"><u>Tailoring Win11 Mouse Access for Comfort</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-reconnect-your-printer-to-pc/"><u>Troubleshooting: Reconnect Your Printer to PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-office-performance-on-windows-with-key-shortcuts/"><u>Turbocharge Office Performance on Windows With Key Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-fixes-for-unreachable-geforce-x-configuration-errors/"><u>Uncovering Fixes for Unreachable GeForce X Configuration Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-clipboard-functionality-within-microsoft-edge-for-app-guard/"><u>Unlocking Clipboard Functionality Within Microsoft Edge for App Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-file-writing-obstructions-in-windows-devices/"><u>Unraveling File Writing Obstructions in Windows Devices</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>Why does the pokemon go battle league not available On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-against-windows-unlock-exe-file-functionality/"><u>Win Against Windows: Unlock EXE File Functionality</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>