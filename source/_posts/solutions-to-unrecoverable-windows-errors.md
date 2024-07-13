---
title: Solutions to Unrecoverable Windows Errors
date: 2024-07-12T16:58:42.497Z
updated: 2024-07-13T16:58:42.497Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solutions to Unrecoverable Windows Errors
excerpt: This Article Describes Solutions to Unrecoverable Windows Errors
keywords: Fixing Windows Crashes,Resolving Critical PC Errors,Troubleshoot Blue Screen Failures,Solve Freezing Windows Issues,Unlock Boot Loop Windows,Address Corrupt System Files,Clear Fatal OS Errors
thumbnail: https://thmb.techidaily.com/d8d6563b1e83446e0eb6eee844ba3f9b3df6929eaff9c17a0488818cf8023092.jpg
---

## Solutions to Unrecoverable Windows Errors

 Have you encountered the error "the application encountered an unrecoverable error" when trying to join a Roblox experience via your web browser, causing your Roblox client to crash? If so, something is wrong that has caused Roblox to crash.

 Among the leading causes of this error can be interference from the browser, running Roblox in a virtual machine, or misconfigured BIOS settings. The error message suggests users share a crash dump with Roblox support to diagnose the issue. Before you do that, perform the below-mentioned checks and fixes first.

## 1\. Apply Some Basic Fixes

 Begin troubleshooting the issue by applying these basic fixes, which may stop Roblox from crashing right away:

* Whitelist Roblox in Windows Defender (See [how to allow apps through Windows Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/)). Also, temporarily turn off third-party antivirus software.
* Turn off any anti-cheat software you use, even those that aren't directly related to Roblox.
* Disable other programs running in parallel with Roblox to ensure the system don't crash due to a lack of resources.
* Run Roblox as administrator to give Roblox a higher priority, which can prevent the game from crashing.

 If none of the above checks resolve the error, apply the remaining fixes.

## 2\. Use the Microsoft Store App Until the Issue Is Resolved
![Roblox Microsoft Store App Listing on Windows](https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roblox-microsoft-store-app-listing-on-windows.jpg)

 Roblox users have reported that the error under discussion only affects those who attempt to join Roblox experiences from the web, not Roblox's Microsoft Store app. Because of this, if you have encountered a crash when joining an experience through the Roblox website, download Roblox's app from the [Microsoft Store](https://apps.microsoft.com/store/detail/roblox/9NBLGGGZM6WM) and join the experience through it.

 Until the issue isn't fixed, continue using the Microsoft Store app to play Roblox experiences.

## 3\. Don't Run Roblox on a Virtual Machine

 Roblox doesn't permit playing Roblox experiences on a virtual machine, as a Roblox staff member reported on [Roblox's developer forum](https://devforum.roblox.com/t/the-application-encountered-an-unrecoverable-error/2419033/2). When someone attempts to access Roblox experiences this way, Hyperion abruptly crashes the process.

![An open laptop sitting on a windowsill with a residential view in the background.](https://thmb.techidaily.com/4a4364521475bc98d43a49b1c82e26ef445f3c795924721c63fb3c06810bfd5f.jpg)

 Do you also want to run Roblox Player on a virtual machine, but the client crashes? If so, that could be the cause of the error. Close the virtual machine and run Roblox by installing the client on your OS; hopefully, nothing will go wrong this way.

 If you don't use a virtual machine and still get the **"the application encountered an unrecoverable error"** error, virtualization could be enabled in the BIOS settings.

## 4\. Disable Virtualization From the BIOS

 Virtualization allows Windows users to emulate another operating system, such as Linux. Having this feature enabled on Windows can cause the Roblox client to crash, and Roblox staff members recommend turning it off through the BIOS. Therefore, you should ensure it's disabled and disable it if necessary.

 Turning off virtualization and accessing BIOS varies from manufacturer to manufacturer. Here's how you can turn off virtualization on a Dell device:

1. Turn off your Windows PC and then turn it back on.
2. Press **F2** when the Dell logo appears on your screen; this will boot your device into BIOS.
3. Go to **Advanced > Virtualization** or **Virtualization Support > Virtualization**.
4. Click on **Intel Virtualization Technology (VT)** and uncheck the box beside **Enable** **Intel Virtualization Technology (VT)**.  
![Disable Intel Virtualization Technology Option in the BIOS Settings of a Dell Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disable-intel-virtualization-in-bios-settings-of-a-dell-laptop.jpeg)
5. Click on **Intel VT for Direct I/O** and uncheck the box beside **Enable** **Intel VT for Direct I/O**.  
![Disable Intel VT for Direct IO in BIOS Settings of a Dell Device](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disable-intel-vt-for-direct-io-in-bios-settings-of-a-dell-device.jpeg)

 If you're using a device from another manufacturer, visit its official website for steps on disabling virtualization.

## 5\. Check for Browser Interference

 If virtualization wasn't already enabled, and you don't use any virtual machines, check for browser interference and ensure that's not causing the error.

 To confirm this, switch to a different browser and run Roblox experiences there. If you don't get an error in another browser, it's a problem specific to your primary browser. In that case, here're a few things you can do to exclude browser interference:

* [Clear the cache and cookies in Chrome](https://www.makeuseof.com/how-to-clear-cookies-cache-in-chrome/), [Firefox](https://www.makeuseof.com/clear-cache-firefox/), [Edge](https://www.makeuseof.com/how-to-clear-microsoft-edge-cache-browsing-data/), or any other browser you use.
* Disable or remove all your extensions to ensure they don't interfere with the process. Refer to our guide on [how to disable or permanently remove the extensions on different browsers](https://www.makeuseof.com/tag/how-to-clean-up-your-browser-extensions-the-easy-way/) for instructions.

 However, if you get an error on other browsers also, browser interference is likely not a cause. In that case, keep applying the remaining fixes.

## 6\. Delete the Temporary Roblox Files

 The corruption of cache files can also cause the error under discussion. To make sure the outdated temporary files do not cause the problem, follow these steps to delete them:

1. Press **Win + R**.
2. Type **"%localappdata%"** and press **Enter**.
3. Navigate to the **Temp** folder.
4. Right-click on the **Roblox** folder and click **Delete**.  
![Delete Roblox Temporary Folder in the Windows Temp Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-roblox-temporary-folder-in-the-windows-temp-folder.jpg)

## 7\. Report the Problem to the Roblox Support Team

 If none of the above fixes resolve the issue, you should follow the instructions in the error message: get a crash dump, and send it to Roblox. Follow these steps to do that:

1. Create a JSON file at the following location:  
`%LOCALAPPDATA%\Roblox\Versions<your-current-client-version-here>\ClientSettings\ClientAppSettings.json`  
 (If subfolders aren't already there, create them)  
![Create and Save a JSON File in the Roblox App Data Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/creating-and-saving-a-json-file-in-the-roblox-app-data-folder.jpg)
2. Open the newly created file, add the following text, and save it:  
`{"DFIntWriteFullDmpPercent": 100}`
3. Run Roblox and let it crash.
4. Post a bug report by following the instructions on the [Roblox website](https://devforum.roblox.com/t/how-to-post-a-bug-report/24388).
5. Attach crash dump files and log files to the bug report from one of the following locations:  
`%UserProfile%\AppData\Local\Roblox\logs  
%UserProfile%\AppData\Local\Roblox\logs\crashes`

## 8\. Reinstall the Roblox Client

 If the Roblox installation gets corrupt, it can also crash and present the **"the application encountered an unrecoverable error"** error. To ensure that's not the case, uninstall the previous installation and reinstall Roblox from scratch. If you do not know how to do this, refer to our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

 Once the Roblox client has been uninstalled, navigate to the **C:\\Users\\<your username>\\AppData\\Local** and delete the Roblox folders. Then, go to Roblox's official website and reinstall the Roblox client. You should avoid downloading the Roblox client from third-party sources since unsigned third-party applications are prone to causing issues.

## Don't Let Roblox Crash on Windows

 Seeing Roblox crash and display annoying errors can be a bit unsettling. You should now better understand what causes the error in question. Also, applying the basic fixes discussed above will resolve the problem. Report the issue to Roblox support if nothing works. They will diagnose the issue for you and help you resolve it.

 Like the abovementioned error, Roblox can also crash with many other errors. There is no need to worry if you encounter them, as all of them are easy to fix.

 Among the leading causes of this error can be interference from the browser, running Roblox in a virtual machine, or misconfigured BIOS settings. The error message suggests users share a crash dump with Roblox support to diagnose the issue. Before you do that, perform the below-mentioned checks and fixes first.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/focusing-gpo-application-one-user-approach-for-windows-1111/"><u>Focusing GPO Application: One-User Approach for Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-obsolete-directx-applications-using-dxvk/"><u>Overhauling Obsolete DirectX Applications Using DXVK</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-decode-and-clear-windows-10s-activity-archive/"><u>How to Decode and Clear Windows 10'S Activity Archive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-win-11-taskbar/"><u>Mastering Time Display on Win 11 Taskbar</u></a></li>
<li><a href="https://extra-hints.techidaily.com/hdmi-display-showdown-the-creme-de-la-creme-monitors/"><u>HDMI Display Showdown  The Crème De La Crème Monitors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-make-instagram-slow-motion-video-for-2024/"><u>[Updated] How to Make Instagram Slow Motion Video for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-leading-10-lenses-revolutionizing-photography/"><u>In 2024, Leading 10 Lenses Revolutionizing Photography</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-flawed-windows-safety-features-in-win-11/"><u>Fixing Flawed Windows Safety Features in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-constant-windows-printer-selection/"><u>Guidelines for Constant Windows Printer Selection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-re-entry-to-your-shared-windows-spot/"><u>Seamless Re-Entry to Your Shared Windows Spot</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-voice-purging-protocols-the-six-key-steps-to-a-vocally-cleansed-audio-track-via-adobe-audition/"><u>2024 Approved Voice Purging Protocols The Six Key Steps to a Vocally Cleansed Audio Track via Adobe Audition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-potential-of-diskusage-for-in-depth-drive-space-examination/"><u>Harnessing the Potential of DiskUsage for In-Depth Drive Space Examination</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-remove-button-for-windows-11-pins/"><u>Reinstating Absent 'Remove' Button for Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-the-windows-11-taskbar-teams-chat-removal-will-impact-you/"><u>How the Windows 11 Taskbar Teams Chat Removal Will Impact You</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-best-applications-for-crafting-dynamic-video-entrances/"><u>2024 Approved  Best Applications for Crafting Dynamic Video Entrances</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-creating-engaging-gaming-broadcasts-using-ai-faces/"><u>[Updated] Creating Engaging Gaming Broadcasts Using AI Faces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-touchpad-gestures-not-working-in-windows/"><u>How to Fix Touchpad Gestures Not Working in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackling-wow-glitch-519-successfully/"><u>Tackling WoW Glitch #519 Successfully</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails/"><u>Elevate Your Digital Footprint  Crafting Compelling Shorts Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-ensure-seamless-windows-notepad-functioning/"><u>Steps to Ensure Seamless Windows Notepad Functioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reignite-the-gaming-revolution-integrate-trophies-and-awards-using-retroarch/"><u>Reignite the Gaming Revolution - Integrate Trophies and Awards Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-recover-non-operational-windows-apps/"><u>Steps to Recover Non-Operational Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-windows-11-calculator-activation/"><u>Steps for Windows 11 Calculator Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-grammarly-a-dead-service-on-your-desktop/"><u>Reactivating Grammarly, a Dead Service on Your Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-ai-enhance-windows-11-usability/"><u>How Does AI Enhance Windows 11 Usability?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-themes-for-enhanced-terminal-views/"><u>Innovative Themes for Enhanced Terminal Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-security-running-as-administrator/"><u>Navigating Windows Security: Running As Administrator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-non-active-vss-service-states/"><u>Restoring Non-Active VSS Service States</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-fixing-media-creators-error-0x8007043c/"><u>Methods for Fixing Media Creator's Error 0X8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microphone-blackout-during-powerpoint-video-recording/"><u>Fixing Microphone Blackout During PowerPoint Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stabilizing-dwarf-fortress-on-win/"><u>Solutions for Stabilizing Dwarf Fortress on Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-pc-manager-on-windows-11-a-quick-guide/"><u>Setting Up PC Manager on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-for-local-sam-service-error-on-computers/"><u>Fix for Local SAM Service Error on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-lowering-windows-acoustic-amplifiers/"><u>Guide to Lowering Windows Acoustic Amplifiers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-how-to-make-looping-videos-for-instagram/"><u>[Updated] How To Make Looping Videos for Instagram?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-windows-hosts-overuse-a-guide/"><u>Reducing Windows Host's Overuse: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-directx-setup-couldnt-download-the-file-error-on-windows/"><u>How to Fix the “DirectX Setup Couldn’t Download the File” Error on Windows</u></a></li>
</ul></div>
