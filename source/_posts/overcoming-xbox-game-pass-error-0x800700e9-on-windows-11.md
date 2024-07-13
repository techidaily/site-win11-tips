---
title: "Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11"
date: 2024-07-12T16:52:29.686Z
updated: 2024-07-13T16:52:29.686Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11"
excerpt: "This Article Describes Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11"
keywords: Fix Xbox Error 0X800700E9,Resolve Xbox Game Pass,Overcome Xbox 11 Errors,Solve Windows Gaming Issues,Xbox on PC Troubleshooting,Win Error 0X800700E9 Solution,Remedy Xbox Game Pass Fault
thumbnail: https://thmb.techidaily.com/1da8846cbd836d9712f7b59a73630f863ec9ad2fa528ea4ddf23335f3fc8b9a6.png
---

## Overcoming Xbox Game Pass Error: 0X800700E9 on Windows 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

## 8\. Reset Your Network
![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://some-skills.techidaily.com/new-applications-of-virtual-reality/"><u>[New] Applications of Virtual Reality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-in-windows-preload-land/"><u>Charting Your Course in Windows Preload Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-remedy-guide-eight-tactics/"><u>Essential Windows Remedy Guide - Eight Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-windows-storage-the-top-free-volume-boosters-list/"><u>Enhance Your Windows Storage: The Top Free Volume Boosters List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-benefits-in-not-muting-wins-11-pushes/"><u>Uncovering the Benefits in Not Muting Wins 11 Pushes</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-vlog-like-a-pro-14-essential-video-editing-software-solutions-for-2024/"><u>Updated Vlog Like a Pro 14 Essential Video Editing Software Solutions for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-giggle-generators-online/"><u>2024 Approved  Giggle Generators Online</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-mastering-sonic-transformation-a-list-of-top-5-audio-alteration-software/"><u>2024 Approved Mastering Sonic Transformation A List of Top 5 Audio Alteration Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-windows-11-faces-a-slow-uptake-from-users/"><u>Why Windows 11 Faces a Slow Uptake From Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-removal-of-win11s-official-store/"><u>Exclusive Removal of Win11's Official Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-share-cant-be-opened-issues-in-geforce/"><u>Eliminating Share Can't Be Opened Issues in GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-power-indicators-full-charges-notify-you-in-win11/"><u>Automating Power Indicators: Full Charges Notify You in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-result-visibility-for-windows-1011s-search/"><u>Enhancing Result Visibility for Windows 10/11'S Search</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-enhancing-your-gaming-experience-incorporating-audio-with-kinemaster/"><u>Updated Enhancing Your Gaming Experience Incorporating Audio with KineMaster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-win11-personalized-volume-shortcuts/"><u>The Essentials of Win11 Personalized Volume Shortcuts</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y100t-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y100t without Losing Data | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-resolving-obs-darkness-during-playbacks/"><u>In 2024, Resolving OBS Darkness During Playbacks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-sims-4-recording-techniques-for-gamers/"><u>[New] Sims 4  Recording Techniques for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unnoticed-slowdown-agents-innocent-looking-apps-for-windows-11/"><u>Unnoticed Slowdown Agents: Innocent-Looking Apps for Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-wmp-for-effortless-audio-conversion/"><u>Navigating WMP for Effortless Audio Conversion</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-from-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 From Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-decoding-the-latest-shifts-in-facebook-landscape/"><u>[Updated] Decoding the Latest Shifts in Facebook Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-workday-woes-into-productivity-peaks-using-windows-11s-tools/"><u>Transform Workday Woes Into Productivity Peaks Using Windows 11'S Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-pcs-visual-fidelity-with-updated-radeon-drivers-windows-edition/"><u>Elevating Your PC's Visual Fidelity with Updated Radeon Drivers, Windows Edition</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-excellence-engineers-select-laptop-choices-for-4k-editing-pros/"><u>[New] Excellence Engineers  Select Laptop Choices for 4K Editing Pros</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-integrating-diverse-iphone-media-formats-together/"><u>2024 Approved  Integrating Diverse iPhone Media Formats Together</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-remove-black-display-on-pc-webcam/"><u>Tips to Remove Black Display on PC Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x80131500-on-microsoft-store/"><u>Disabling Error 0X80131500 on Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-increase-video-volume-and-make-video-sounds-louder-video-volume-booster/"><u>In 2024, Increase Video Volume & Make Video Sounds Louder -Video Volume Booster</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-with-windows-11s-screen-snip-functionality/"><u>Engage with Windows 11'S Screen Snip Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-management-navigating-taskbar-with-windows-hotkeys/"><u>Effortless Management: Navigating Taskbar with Windows Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-performance-insider-tips-on-wintools/"><u>Elevate PC Performance: Insider Tips on WinTools</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-se-2020-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock iPhone SE (2020) Without Passcode Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/become-a-cmd-guru-understand-these-20-crucial-commands/"><u>Become a CMD Guru: Understand These 20 Crucial Commands</u></a></li>
</ul></div>
