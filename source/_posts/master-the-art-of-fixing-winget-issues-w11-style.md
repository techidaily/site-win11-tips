---
title: Master the Art of Fixing Winget Issues W11 Style
date: 2024-09-05T19:32:42.257Z
updated: 2024-09-06T19:32:42.257Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master the Art of Fixing Winget Issues W11 Style
excerpt: This Article Describes Master the Art of Fixing Winget Issues W11 Style
keywords: Wingset Troubleshooting Guide,W11 Wingset Solutions,Fix Wingset W11 Errors,Winget W11 Repair Tips,Mastering Wingset Fixes,W11 Wingset Recovery Steps,Effective W11 Wingset Fix
thumbnail: https://thmb.techidaily.com/e4680a85088d1a2f44c589b1c74f41a831760d9eaf6ae422f8b959a2a9262d12.jpg
---

## Master the Art of Fixing Winget Issues W11 Style

 Winget is a command-line tool that can download and install app packages from MS Store and the apps listed in its repository. It saves a lot of time that would be otherwise wasted in searching the Microsoft Store or the web for a particular app, downloading it, and then manually installing it.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reasons Why Winget Stops Working on Windows

 Here are the following reasons why Winget is not working on your Windows PC:

1. You are running an outdated version of the App Installer.
2. Winget servers are down, or you don’t have an active internet connection.
3. The app execution alias is not configured or inactive for Winget.
4. App Installer failed to add the PATH environment variable automatically while installing.

 Now, you know the reasons behind Winget not working issue. Try out these eight methods to resolve the issue and use your favorite package manager again.

## 1\. Close and Reopen Winget in the Terminal App

 Before moving on to advanced fixes, completely close the Command Prompt or PowerShell instance you are running on the PC. You can use the Task Manager to stop an unresponsive instance of either of these command-line tools.

 After that, open Command Prompt or PowerShell with administrator privileges on your system. Type Winget and press the **Enter** key to check if Winget works now.

## 2\. Check if the Winget Servers Are Down

 Winget is an online tool that needs a robust internet connection to search for a package in various repositories and then download and install them. If the Winget servers are down or inactive, it won’t be able to fetch results from repositories. So, check if Winget servers are down using [DownDetector](https://redirect.viglink.com/?format=go&jsonp=vglnk%5F168667664973511&key=eac202ea7a96cf485281d6c4ffa2069e&libId=liuggg0i0103es17000ULlmtlntd&loc=https%3A%2F%2Fwww.makeuseof.com%2Fhow-to-fix-0x8004def5-onedrive-error-code-windows-11%2F&ccpaConsent=1---&v=1&opt=true&optExText=false&out=https%3A%2F%2Fdowndetector.com%2F&ref=https%3A%2F%2Fwww.makeuseof.com%2Fauthor%2Fabhishekkumar-mishra%2F&title=9%20Ways%20to%20Fix%20the%200x8004def5%20OneDrive%20Error%20Code%20on%20Windows%2011&txt=DownDetector) or a similar website.

 You can also check if your Windows PC can connect to the internet. Simply open a web browser and access a website or run a web-based app to confirm internet connectivity. If the servers are down, you will have to wait until they come up live again to use Winget.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Perform a Complete System Shutdown

 Windows uses Fast Startup to hibernate kernel-level processes and if any of these glitch, they remain in that state after your power on the system. So, perform a complete shutdown to close and relaunch all the core services and then try to run Winget. Here’s how to do it:

1. Press **Win + R** to open the Run dialog box. Type **cmd** and press **Ctrl + Shift + Enter** keys to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Now, type the following command and press the Enter key: **shutdown /s /f /t 0**  
![Completely Shutdown your PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/completely-shutdown-your-pc.jpg)
3. Your system will shut down. It will take longer than a usual shutdown because Windows will close everything.
<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Power on your system and try to run Winget using the Terminal app to check if it works now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115942/19272" target="_top" id="2115942">
  <img src="//a.impactradius-go.com/display-ad/19272-2115942" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115942/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Update App Installer

 Winget is a part of Windows 10 and 11 now and is shipped to PCs using the App Installer application. If you haven’t updated the App Installer in a while, you can face issues in running Winget and managing packages. Winget is included only in version 1.11.11451 or higher of the App Installer. If you have a version older than that, you cannot use Winget from the terminal.

![Update App Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-app-installer.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 So, open Microsoft Store and check the library section for any pending updates for the App Installer. Manually search and install the update and check if Winget works now.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Enable the App Execution Alias

 If the App Execution Alias for Winget is disabled, it won’t work when you try accessing Winget from the terminal. So, you must enable it in the app settings. Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User** menu. Click on the **Settings** app.
2. Navigate to the left-hand side menu and click on the **Apps** option.
3. Now, click on the **Advanced app settings** option. Then click on the **App execution aliases** option.
4. Locate the **Windows Package Manager Client** option. Check the toggle next to it. If it is disabled, click on it to **enable** the app execution alias for the app.  
![Enable the App Execution Alias-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-the-app-execution-alias-1.jpg)
5. Close the Settings app.

## 6\. Manually Add the Path Environment Variable

 Ae wrongly configured Winget path can also produce errors. So, you must manually add the correct path in Environment Variables using the Advanced System Properties window. Repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **sysdm.cpl ,3** in the text box and press the **Enter** key to open **Advanced System Properties**.
2. Click on the **Environment Variables** button. Click on the **Path** entry and then click on the **Edit** button.
3. Now, click on the New button and paste the following path: **%UserProfile%\\AppData\\Local\\Microsoft\\WindowsApps**  
![Manually Add the Path Environment Variable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manually-add-the-path-environment-variable.jpg)
4. Click on the **OK** button. Restart your PC.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Open the Terminal app and check if Winget works or not.

## 7\. Re-register Winget Using PowerShell

 If Winget isn’t working on your PC, you can re-register it using PowerShell. Since it is a part of the App Installer which is a system app, it is possible to re-register it. Repeat the following steps:

1. Press **Win + R** to open the Run dialog box. Type **PowerShell** and press the **Ctrl + Shift + Enter** keys at once.
2. The PowerShell window will launch with admin rights. Paste the following code and press the **Enter** key to execute it:  
`Add-AppxPackage -DisableDevelopmentMode -Register "C:\Program Files\WindowsApps\Microsoft.Winget.Source_2021.718.1322.843_neutral__8wekyb3d8bbwe\AppXManifest.xml" -Verbose`
3. You won’t see any confirmation message after the command executes successfully. Close the PowerShell window and restart your PC.  
![Re-register Winget Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/re-register-winget-using-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Try Some Generic Windows Fixes

 If none of the methods work for you, try our generic fixes like SFC and DISM scans that find and fix the system file corruption and service Windows Image components. You must [run the SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) first and allow it to find and replace the corrupt system files, if any. After that, [run the DISM scan](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) in online mode.

 After running these scans, you can use System Restore to revert the PC to a point in time when everything worked fine. Lastly, you can perform a complete system reset. You can choose the Keep my files option to preserve all your files while [factory resetting Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/).

## Make Winget Functional Again

 Winget is a fantastic package manager that helps you control and manage app packages from the terminal. Ensure robust internet connectivity and check if the app execution alias is active for Winget. Manually reconfigure the PATH for Winget and re-register the App Installer using PowerShell. If you want a GUI version of Winget, you can try Winstall which helps you batch-install apps.

 But some users report that Winget is not working on their PC. They face a "The system cannot execute the specified program" and cannot run any commands, This post will discuss multiple methods to resolve the issue and restore Winget to its working state. Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-elevate-your-content-selecting-top-thumbnail-fonts/"><u>[New] 2024 Approved Elevate Your Content Selecting Top Thumbnail Fonts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-behind-the-curtains-a-guide-to-youtubes-hidden-videos/"><u>[New] Behind the Curtains A Guide to YouTube’s Hidden Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-6-networks-transforming-how-firms-connect-and-engage/"><u>[New] Top 6 Networks Transforming How Firms Connect and Engage</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-transform-your-photos-with-instagrams-latest-filters-2023-techniques/"><u>[New] Transform Your Photos with Instagram's Latest Filters (2023 Techniques)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-seamless-viewing-of-time-honored-facebook-stories-for-2024/"><u>[Updated] Seamless Viewing of Time-Honored Facebook Stories for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-clearing-imagery-the-canva-method-for-clean-bounds/"><u>2024 Approved Clearing Imagery The Canva Method for Clean Bounds</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-illumination-innovations-advanced-lighting-in-video-making/"><u>2024 Approved Illumination Innovations Advanced Lighting in Video Making</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-nokia-c22-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Nokia C22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-widget-development-strategies-for-windows-11-upgrades/"><u>Cutting-Edge Widget Development: Strategies for Windows 11 Upgrades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-correcting-windows-error-code-0xc00000f/"><u>Decoding and Correcting Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dial-back-to-digital-delight-playing-vintage-pc-games/"><u>Dial Back to Digital Delight: Playing Vintage PC Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-your-dormant-data-windows-storage-visualization-tactics/"><u>Discover Your Dormant Data: Windows Storage Visualization Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diving-deep-into-bsod-memory-information/"><u>Diving Deep Into BSOD Memory Information</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ng-elegance-into-news-summations-for-2024/"><u>Editing Elegance Into News Summations for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effective-guide-installing-latest-amd-drivers-for-windows-versions/"><u>Effective Guide: Installing Latest AMD Drivers for Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-isdonedll-failures-instantly/"><u>Eliminating Windows ISDone.dll Failures Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-disparity-to-consistency-unifying-windows-pcs-with-aoemi/"><u>From Disparity to Consistency: Unifying Windows PCs With AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-familiar-with-your-mouse-guide-to-windows-11-propets/"><u>Get Familiar with Your Mouse: Guide to Windows 11 Propets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/google-play-setup-a-comprehensible-path/"><u>Google Play Setup: A Comprehensible Path</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-13-pro-max-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-world-of-warcrafts-fatal-exception-error-132-in-windows-1011/"><u>How to Fix World of Warcraft’s Fatal Exception Error 132 in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solve-the-0x80071a90-windows-problem/"><u>How to Solve the 0X80071a90 Windows Problem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-square-windows-11-edges/"><u>How to Square Windows 11 Edges</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-v-purse-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Honor V Purse PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Honor X50 GT? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/infusing-vintage-directx-software-with-modern-dxvk-features/"><u>Infusing Vintage DirectX Software with Modern DXVK Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/internet-inequity-fix-your-windows-slowdown-now/"><u>Internet Inequity: Fix Your Windows Slowdown Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-device-awareness-in-power-mode-slumber/"><u>Leveraging Device Awareness in Power Mode Slumber</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-taskbar-date-and-time-settings-for-windows-11/"><u>Mastering Taskbar Date & Time Settings for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-whisper-converting-speech-to-text-on-windows/"><u>Mastering Whisper: Converting Speech to Text on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-anomaly-zero-error-correction-guide/"><u>Microsoft Store Anomaly: Zero-Error Correction Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-peeky-tabs-strategies-for-edge-on-w11/"><u>No Peeky Tabs: Strategies for Edge on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-file-error-on-windows-11/"><u>Overcoming Missing File Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-to-the-next-level-with-collective-folder-formation/"><u>Propel Productivity to the Next Level with Collective Folder Formation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-with-a-non-responsive-printer-in-os/"><u>Reconciling With a Non-Responsive Printer in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-file-images-in-windows-11-the-how-to-guide/"><u>Reinstating File Images in Windows 11 – The How-To Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-invalid-profile-warning-on-pc-win1011-advice/"><u>Remedying 'Invalid Profile' Warning on PC: Win10/11 Advice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-grayed-out-secure-boot-on-windows-bios-settings/"><u>Restoring Grayed-Out Secure Boot on Windows BIOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-sound-output-on-non-responsive-windows/"><u>Restoring Sound Output on Non-Responsive Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-the-driver-verifier-application-on-windows-11/"><u>Starting the Driver Verifier Application on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resetting-validity-of-user-profiles-on-win11-oses/"><u>Steps for Resetting Validity of User Profiles on Win11 OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-non-identified-wireless-networks-in-win11/"><u>Strategies to Recover Non-Identified Wireless Networks in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switch-off-windows-record-of-launches/"><u>Switch Off Windows Record of Launches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-digital-preservation-backing-up-your-epic-games-data/"><u>The Art of Digital Preservation: Backing Up Your Epic Games Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-enhance-saving-capabilities-in-nvidia-control-center/"><u>Tips to Enhance Saving Capabilities in Nvidia Control Center</u></a></li>
<li><a href="https://discover-guides.techidaily.com/top-10-substitutes-for-handbrake-effortless-dvd-and-video-conversion-tools/"><u>Top 10 Substitutes for HandBrake: Effortless DVD & Video Conversion Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-application-switching-aids-mac-to-windows-migration-made-easy/"><u>Top 5 Application Switching Aids: Mac-to-Windows Migration Made Easy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-failed-ms-pc-manager-install-on-windows/"><u>Troubleshoot: Failed MS PC Manager Install on Windows?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-unleash-your-creativity-top-rated-online-animation-software-for-video-making/"><u>Updated 2024 Approved Unleash Your Creativity Top-Rated Online Animation Software for Video Making</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-with-dolby-atmos-audio/"><u>Upgrade Your Windows 11 with Dolby Atmos Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wake-up-rituals-for-keyboard-and-mouse-in-1011-environments/"><u>Wake-Up Rituals for Keyboard & Mouse in 10/11 Environments</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>