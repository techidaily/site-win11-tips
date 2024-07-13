---
title: Enhancing Windows 10/11'S Trouble-Solving Capabilities
date: 2024-07-12T17:23:22.008Z
updated: 2024-07-13T17:23:22.008Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Windows 10/11'S Trouble-Solving Capabilities
excerpt: This Article Describes Enhancing Windows 10/11'S Trouble-Solving Capabilities
keywords: Win10TroubleshootingTips,FixWin10Issues,ResolveWin10Error,Windows10DiagnoseProblems,ImproveWindows10Repair,TroubleshootWindows11,EnhanceWin11Fixes
thumbnail: https://thmb.techidaily.com/c6507ef1a8c1967e04b9a71ecc3df4d6b245a64121c79bffee638bab85472f90.jpg
---

## Enhancing Windows 10/11'S Trouble-Solving Capabilities

 Users often utilize the pre-installed Windows 11/10 troubleshooters available in Settings to fix update, sound, internet, microphone, video playback, Bluetooth, and UWP app issues. However, sometimes those troubleshooters display messages in their windows that say, “An error occurred while troubleshooting.” Or the message might say, “An error occurred while loading the troubleshooter.”

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.

## 1\. Scan and Repair System Files

 Some users have said the system file and image repair tools helped them fix Windows 11/10 troubleshooting tools not working. System File Checker is the command-line tool for repairing system file corruptions. Deployment Image Servicing and Management is a utility you can run to address issues with the Windows image. Try running both those tools in the Command Prompt, as covered within this [guide for repairing corrupted Windows files](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command4.jpg)

## 2\. Enable or Restart Required Services

 Windows troubleshooters can stop working because required services are disabled or not running. Enabling and starting services like Cryptographic Services, Windows Update, BITS, and Windows Installer is a potential resolution for fixing troubleshooters users confirm to work. Try starting those required services like this:

1. Bring up the service management app with a method in this [guide to opening Services](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click **Cryptographic Services** to bring up a settings window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services.jpg)
3. Click on the **Startup type** drop-down menu and choose the **Automatic** setting if a different option is selected.
4. Next, select the **Start** option for the service to run.  
![The Cryptographic Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cryptographic-services-window.jpg)
5. Click on the **Apply** and **OK** options to set your selected settings.
6. Repeat the previous steps for the Windows Update, Windows Installer, and the Background Intelligent Transfer Service.

 If those services are already running and set to an automatic startup, try restarting them. Right-click the service in the Services window and select a **Restart** option.

## 3\. Flush the DNS Cache and Reset the Winsock Catalog

 Network issues can cause some troubleshooters for which an internet connection is more essential to malfunction. Flushing the DNS cache and resetting the Winsock catalog can address such network issues. This potential fix is especially recommended for fixing the Windows Update troubleshooter. You can flush the DNS cache and reset the Winsock catalog by executing two commands like this:

1. Open the Command Prompt app with elevated privileges. If you’re unsure how to access that app, check out this guide for [opening Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Input and execute this command for flushing the DNS cache:  
`ipconfig /flushdns`  
![The ipconfig /flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ipconfig-flushdns-command.jpg)
3. To reset Winsock, execute this command:  
`netsh winsock reset`  
![The netsch winsock reset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/netsch-winsock-reset-command.jpg)

## 4\. Disable Third-Party Security Software and Firewalls

 Many security software packages incorporate firewalls that can sometimes block Windows troubleshooters from connecting with Microsoft servers. If a third-party security app is on your PC, disable that software’s firewall component to ensure it can’t interfere with Windows troubleshooters. Then try running the troubleshooter with the firewall component disabled.

## 5\. Rename the Catroot2 and SoftwareDistribution Folders

 If you’re having issues with the Windows Update troubleshooter, try applying this potential solution. Users confirm renaming the catroot2 and SoftwareDistribution folders can fix the Windows Update troubleshooter not working. Those are folders that store data for Windows updates. Rename the catroot2 and SoftwareDistribution folders as follows:

1. Launch the Windows Command Prompt app with administrative rights.
2. Input these four separate commands, pressing **Enter** after each, to stop update services:  
`net stop cryptsvc  

net stop wuauserv  

net stop bits  

net stop msiserver`
3. Next, input this command and hit **Return** to rename the SoftwareDistribution folder:  
`ren c:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren command for the SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-softwaredistribution-folder.jpg)
4. Enter this command for renaming the catroot2 folder and press **Return**:  
`ren c:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/rename-catroot2-folder.jpg)
5. Restart services by entering and executing these commands:

`net start cryptsvc  
  
net start wuauserv  
  
net start bits  
  
net start msiserver`

## 6\. Modify TEMP and TMP Environment Variables

 Troubleshooter issues can also arise when the TEMP and TMP environment variables have been changed from their default values. To address this, set the TMP and TEMP environment variables to default values as follows:

1. Open the file finder by pressing the **Windows key + S** keyboard buttons.
2. Type **advanced system settings** inside the search box.
3. Click **View advanced system settings** to bring up a System Properties window.
4. Press the **Environment Variables** button on the **Advanced** tab.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-button.jpg)
5. Check the **TEMP** and **TMP** values in the System variables box. If they’re not set to **C:\\Windows\\Temp**, proceed with the next few steps to edit their values.  
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/environment-variables-window.jpg)

1. Double-click **TEMP** in the System variables box.
2. Erase the text in the **Variable** **value** box. Then input **%SystemRoot%\\TEMP** inside the **Variable** **value** box.  
![The Edit System Variable window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-system-variable-window.jpg)
3. Click **OK** on the Edit System Variable window.
4. Repeat the previous three steps for the TMP variable.
5. Select **OK** on the Environment Variables window.

## 7\. Enable Troubleshooters in Group Policy Editor

 Local Group Policy Editor includes policy options for disabling the Windows troubleshooters. If you’re a Windows 11/10 Pro or Enterprise user, it could be the case Group Policy has disabled the troubleshooters. That’s especially likely if the error message says troubleshooting is disabled. You can enable troubleshooting in Group Policy Editor like this:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in that utility.
2. Then double-click **Administrative Templates** \> **System** \> **Troubleshooting and Diagnostics** \> **Scripted Diagnostics** to view policy settings for troubleshooting.  
![The Scripted Diagnostic policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scripted-diagnostic-policies.jpg)
3. Double-click the **Troubleshooting: Allow users to access and run Troubleshooting Wizards** policy.
4. Click **Enabled** to re-enable troubleshooters if the policy is disabled.  
![The Troubleshooting: Allow users to access and run Troubleshooting Wizards policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-allow-users-to-access-and-run-troubleshooters.jpg)
5. Press the **Apply** \> **OK** buttons.
6. Repeat the previous three steps for the **Troubleshooting: Allow users to access online troubleshooting content** and **Configure Security Policy for Scripted Diagnostics** policies.

## 8\. Utilize the System Restore Tool

 System Restore is a utility that undoes system changes by rolling Windows back to earlier times. This tool might undo some changes that caused the troubleshooter error. A lot depends on whether you can select a restore point that will roll Windows back to a time when you could utilize all troubleshooters without issues.

 Check out this [how to utilize System Restore](https://www.makeuseof.com/use-system-restore-windows/) article for instructions about how you can roll back Windows with that tool. Select a restore point that will roll Windows back to a date when all troubleshooters worked on your PC. The oldest restore point available is your best bet if you’re not sure.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-system-restore-window.jpg)

 Utilizing System Restore comes with this caveat: software installed after a restoration date gets removed. This means you may need to reinstall some lost software after performing a restore. Clicking **Scan for affected programs** in System Restore shows you what software a restore point deleted.

## 9\. Factory Reset Your Windows PC

 If troubleshooters still don’t work after applying all the resolutions above, resetting Windows is the last thing you should try. That might seem drastic for fixing troubleshooters, but reinstalling Windows with a reset will likely resolve deeper system issues that have broken them. This potential resolution will wipe all the software and apps you installed.

 The best way to apply this potential resolution is to utilize the "Reset this PC" tool, as outlined in our article about [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/). Selecting **Keep my files** in that tool will save your user files. Also, keep the **Restore preinstalled apps** option set to **Yes** to retain preinstalled software.

![The Reset this PC window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc.jpg)

## Fix Your Windows Issues With the Troubleshooters Once More

 Although most users can probably live without Windows troubleshooters, there’s no denying their usefulness for fixing computing issues. The potential resolutions above will likely resolve most errors that prevent Windows troubleshooters from initiating their troubleshooting. Then you can utilize the troubleshooters to help you fix Windows 10 or 11 issues again.

 The full error messages and codes can vary slightly and appear after users select to run the troubleshooters. Consequently, the affected Windows troubleshooters don’t work. This is how you can fix troubleshooters not working on Windows 11/10 PCs.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/revealing-the-hidden-search-bar-in-win11s-task-manager/"><u>Revealing the Hidden Search Bar in Win11's Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-choose-and-set-your-favorite-command-prompt/"><u>How to Choose and Set Your Favorite Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/complete-walkthrough-to-grab-youtube-playlists/"><u>Complete Walkthrough to Grab YouTube Playlists</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-undetectable-volume-variations-in-garageband-artistry/"><u>2024 Approved  Undetectable Volume Variations in Garageband Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-top-5-best-free-mpeg-video-splitters/"><u>In 2024, Top 5 Best Free MPEG Video Splitters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swivel-your-snaps-with-these-6-steps-for-windows-11-users/"><u>Swivel Your Snaps with These 6 Steps for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-top-10-best-photo-to-animation-converters-that-give-you-an-advantage-for-2024/"><u>New Top 10 Best Photo to Animation Converters That Give You an Advantage for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-conjoin-windows-serial-numbers-and-microsoft-accounting/"><u>How to Conjoin Windows Serial Numbers & MICROSOFT ACCOUNTING</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-software-windows-best-photo-arrangers-reviewed/"><u>Winning Software: Windows' Best Photo Arrangers Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800704cf-error-in-win11-marketplace/"><u>Overcoming 0X800704CF Error in Win11 Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sound-control-with-windows-11-volume-tools/"><u>Mastering Sound Control with Windows 11 Volume Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-a-safe-choice-for-beginners/"><u>Windows 11 S Mode: A Safe Choice for Beginners?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-safeguarding-your-music-three-recording-approaches/"><u>[New] 2024 Approved  Safeguarding Your Music  Three Recording Approaches</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-venues-for-immersive-media/"><u>2024 Approved  Innovative Venues for Immersive Media</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-running-sfc-on-windows/"><u>Understanding and Running SFC on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-access-regulation-for-everyday-windows-pcs/"><u>Mastering User Access Regulation for Everyday Windows PCs</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-unlock-10-passport-images-at-no-cost-desktopweb/"><u>[Updated] 2024 Approved  Unlock 10 Passport Images at No Cost – Desktop/Web</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-hack-design-your-own-unique-pin-pattern/"><u>Windows 10/11 Hack: Design Your Own Unique Pin Pattern</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-unlock-cinematic-excellence-easy-tips-for-creating-stunning-videos/"><u>Updated Unlock Cinematic Excellence Easy Tips for Creating Stunning Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-winterminals-bg-pic/"><u>Setting WinTerminal's Bg Pic</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-effortless-editing-a-beginners-guide-to-gopro-quik-on-macbook/"><u>2024 Approved Effortless Editing A Beginners Guide to GoPro Quik on MacBook</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-a78-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo A78 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-samsung-galaxy-a54-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Samsung Galaxy A54 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-reno-8t-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo Reno 8T 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-ultimate-dvd-conversion-guide-from-disc-to-digital/"><u>In 2024, The Ultimate DVD Conversion Guide From Disc to Digital</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/do-you-want-to-apply-professional-looking-color-grading-on-your-iphones-photos-and-videos-you-can-use-different-iphone-luts-for-your-pictures-and-videos-for/"><u>Do You Want to Apply Professional-Looking Color Grading on Your iPhones Photos and Videos? You Can Use Different iPhone LUTs for Your Pictures and Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-unrealcefsubprocess-high-cpu-and-ram-usage-on-windows/"><u>How to Fix the UnrealCEFSubprocess High CPU and RAM Usage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-cutting-the-fat-in-windows-11/"><u>The Ultimate Guide to Cutting the Fat in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-steam-library-accessibility-on-win-11-pcs/"><u>Troubleshooting Steam Library Accessibility on Win 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-faulty-troubleshooters-in-windows-os/"><u>Reinvigorating Faulty Troubleshooters in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-configurations-restarted-a-triad-of-tips/"><u>Win11 Configurations Restarted: A Triad of Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-pinterest-pin-square-advice/"><u>2024 Approved  Pinterest Pin Square Advice</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-automate-playlist-retrieval-from-youtube-directly/"><u>[Updated] Automate Playlist Retrieval From YouTube Directly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/momentum-builds-with-windows-11s-upcoming-feature-unveil/"><u>Momentum Builds with Windows 11’S Upcoming Feature Unveil</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-sony-xperia-1-v-drfone-by-drfone-android/"><u>How to Screen Mirroring Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-lost-ethernet-connection-fixes/"><u>Guiding You Through Lost Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-camera-app-f429f-hiccup/"><u>How to Rectify Windows 11 Camera App F429F Hiccup</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-leading-applications-replacing-obs-for-live-sessions-for-2024/"><u>[Updated] Leading Applications Replacing OBS for Live Sessions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fix-mobile-device-errors-fb-vids-not-loading-for-2024/"><u>[Updated] Fix Mobile Device Errors  FB Vids Not Loading for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/skyrocket-views-with-these-proven-youtube-optimization-strategies-for-2024/"><u>Skyrocket Views with These Proven YouTube Optimization Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-windows-multiscreen-woes/"><u>Understanding Windows Multiscreen Woes</u></a></li>
<li><a href="https://vp-tips.techidaily.com/exclusive-software-gamers-streaming-companions/"><u>Exclusive Software  Gamers' Streaming Companions</u></a></li>
</ul></div>
