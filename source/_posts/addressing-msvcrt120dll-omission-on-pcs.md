---
title: Addressing Msvcrt120dll Omission on PCs
date: 2024-07-12T17:56:36.360Z
updated: 2024-07-13T17:56:36.360Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Msvcrt120dll Omission on PCs
excerpt: This Article Describes Addressing Msvcrt120dll Omission on PCs
keywords: MSVCRT120OmitError,WindowsDLLFailure,DLLOmissionIssue,OmissionErrorPC,SystemDLLMissing,PCHardwareDeficit,MissingMsvcrt120
thumbnail: https://thmb.techidaily.com/0825c5cfd1c9f8c60055aa627e174f35756a5c00a4e026b76fba822f7faa2ec3.jpg
---

## Addressing Msvcrt120dll Omission on PCs

 Do you keep getting an error that reads “The program can’t start because MSVCR120.dll is missing from your computer” while opening apps or programs on Windows? This can happen due to a variety of reasons, including a damaged Microsoft Visual C++ Redistributable package, corrupt system files, malware infection, and more.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.

## 1\. Repair the Microsoft Visual C++ Redistributable

 The msvcr120.dll file is a component of the Microsoft Visual C++ 2013 Redistributable package. If there are any issues with this package, it may lead to the msvcr120.dll missing error on Windows. You can try repairing the Microsoft Visual C++ 2013 Redistributable package on your PC to see if that fixes the error. Here are the steps for the same.

1. Click the **magnifying icon** on the taskbar or press the **Win + S** keyboard shortcut to access the search menu.
2. Type **control panel** in the search box and select the first result that appears.
3. Use the drop-down menu in the top right corner to change the view type to **Small icons** or **Large icons**.
4. Click on **Programs and Features**.
5. Locate and select the **Microsoft Visual C++ 2013 Redistributable** package on the list.
6. Click the **Change** option at the top.
7. Hit the **Repair** button and wait for the process to complete.  
![Repair the Microsoft Visual C++ Redistributable on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-the-microsoft-visual-c-redistributable-on-windows.jpg)

## 2\. Reinstall Microsoft Visual C++ Redistributable

 If updating the Visual C++ Redistributable package does not help, you can try reinstalling it on your PC. To do so, use these steps:

1. Open up any web browser and visit Microsoft’s website to [download the Visual C++ Redistributable packages](https://www.microsoft.com/en-ph/download/details.aspx?id=40784).
2. Select your preferred language using the drop-down menu and click the **Download** button.
3. Tick the **vcredist\_x64.exe** and **vcredist\_x86.exe** checkboxes and click **Next**.  
![Download the Microsoft Visual C++ Redistributable.png](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/download-the-microsoft-visual-c-redistributable-png.jpg)

 Double-click the downloaded setup file and follow the on-screen prompts to finish the installation process. After that, check if the error occurs again.

 If you are using 64-bit Windows, you can install both vcredist\_x64.exe and vcredist\_x86.exe. However, if you have a 32-bit version of Windows, you should only install vcredist\_x86.exe. You can [tell if the Windows version you are using is 32-bit or 64-bit](https://www.makeuseof.com/tag/4-easy-ways-to-know-if-youre-on-a-64-bit-version-of-windows/) by checking the system information.

## 3\. Copy the Msvcr120.dll From Another Computer

 While troubleshooting the msvcr120.dll missing error, you might stumble upon websites that promise to fix the error through a quick download of the DLL file. However, doing so can be risky, as the file may be infected by malware.

 A safer alternative is to manually copy the msvcr120.dll file from another computer and paste it into the appropriate folder on your computer. You can transfer the msvcr120.dll file from another computer [using nearby sharing on WIndows](https://www.makeuseof.com/how-to-use-nearby-sharing-on-windows-11/) or an external storage device.

 Once you get the msvcr120.dll file, you can paste it into the appropriate folder. If you are using the 64-bit version, you should paste it into **Local Disk (C:) > Windows > System32**. For the 32-bit version, you should paste it into **Local Disk (C:) > Windows > SysWOW64**.

![MSVCR120 in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msvcr120-in-file-explorer.jpg)

## 4\. Update or Reinstall the Problematic Program

 If you encounter the msvcr120.dll missing error only when launching a specific app or program, it is likely that the program is unable to access the DLL file. You can try updating the problematic program to its most recent version to see if that helps.

 If the error persists even after that, you can consider removing the program completely and installing it again. We have a detailed guide on [different ways to uninstall software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). You can follow any one of the methods outlined there to uninstall the problematic program. Make sure you [eradicate leftovers from the uninstalled program](https://www.makeuseof.com/windows-remove-leftovers-uninstalled-software/) before reinstalling it on your PC.

## 5\. Re-Register the Msvcr120.dll File

 Re-registering the MSVCR120.dll file on your system refreshes the registration information for the file in the Windows Registry. This can help resolve issues caused by missing or corrupted registry entries that may have led to the error.

 To re-register the msvcr120.dll file on Windows, use these steps:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Type the following command and press **Enter** to unregister the msvcr120.dll file from your system.  
`regsvr32 /u MSVCR120.dll`
4. Paste the following command and press **Enter** to re-register the msvcr120.dll file.  
`regsvr32 MSVCR120.dll`

## 6\. Try Some Generic Fixes to Resolve the Msvcr120.dll Missing Error

 If you are still getting the msvcr120.dll missing error at this point, you can try some of the generic fixes to resolve the error message. Let's go over all of them quickly one by one.

* **Run an SFC Scan:** Problems with your PC's system files can give rise to such errors. [Running the SFC and DISM scans](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) can help you scan your PC for corrupt or damaged system files and repair them.
* **Scan for Malware:** The disappearance of the msvcr120.dll file may be caused by a malware infection. If that seems to be the case, you can [use Microsoft Defender's offline scan to detect and remove any malware](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) from your PC.
* **Update Drivers:** A malfunctioning driver could interfere with your apps and programs and trigger such errors. Hence, it’s a good idea to update the drivers on your PC using a [free driver updater tool](https://www.makeuseof.com/windows-best-free-driver-updaters/).
* **Install Windows Updates:** It’s possible that the error in question is occurring due to a bug within Windows. If that’s the case, [installing pending Windows updates](https://www.makeuseof.com/windows-11-install-updates/) should help fix it.
* **Perform a System Restore:** If the msvcr120.dll missing error has only started appearing recently, you can [use system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state. This will allow you to undo any recent system changes that may have caused the problem.

## Restore the Missing the Msvcr120.dll File on Windows

 The msvcr120.dll missing error can prevent you from using your favorite apps and programs and waste your time. Fortunately, as with most DLL errors, “The program can’t start because MSVCR120.dll is missing from your computer” can be easily resolved if you apply the above-mentioned fixes.

 If none of the troubleshooting tips help, you can consider resetting Windows to its default state as your last option. The good news is that you can reset Windows without losing any of your personal data or files.

 Whatever the cause, fixing the msvcr120.dll missing error on Windows isn’t too difficult. Here are the solutions you need to try.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-realme-11-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-best-mac-capture-software-excluding-traditional-bandicam/"><u>2024 Approved  Best Mac Capture Software Excluding Traditional Bandicam</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-directory-for-acquiring-cat-sound-effects-in-audio-format/"><u>In 2024, Directory for Acquiring Cat Sound Effects in Audio Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-unraveling-breakpoint-failed-in-windows-devices/"><u>Tips for Unraveling Breakpoint Failed in Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-game-pass-access-restoration-in-win-oses/"><u>Mastering Game Pass Access Restoration in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-copy-pasting-predefined-text-with-windows-11-hotkeys/"><u>Streamline Copy-Pasting Predefined Text with Windows 11 Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-access-control-the-powertoys-way/"><u>Mastering Access Control: The PowerToys Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/virtualbox-v70-upgrade-guide-win11-edition-walkthrough/"><u>VirtualBox v7.0 Upgrade Guide – Win11 Edition Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-disabled-volume-snapshots/"><u>Restoring Functionality to Disabled Volume Snapshots</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-step-by-step-saving-tweet-vids-on-androids/"><u>[New] 2024 Approved  Step-By-Step  Saving Tweet Vids on Androids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-solution-to-error-code-0x80070570-rescuing-damaged-files-on-windows-11/"><u>Unlocking Solution to Error Code 0X80070570: Rescuing Damaged Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/terminals-in-win11-undo-changes-and-start-new/"><u>Terminals in Win11: Undo Changes & Start New</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/detailed-steps-to-record-hulu-on-every-os-and-device-type/"><u>Detailed Steps to Record Hulu on Every OS and Device Type</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://network-issues.techidaily.com/tackle-roblox-slowness-at-pc-level/"><u>Tackle Roblox Slowness at PC Level</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-adding-linguistic-accessibility-to-your-igtv-videos/"><u>[New] 2024 Approved  Adding Linguistic Accessibility to Your IGTV Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-normalcy-show-startups-on-task-manager/"><u>Restoring Normalcy: Show Startups on Task Manager</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-game-jams-and-indie-project-highlights/"><u>[Updated] 2024 Approved  Game Jams and Indie Project Highlights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-lock-personal-pattern-creation-tutorial/"><u>Mastering Window's Lock: Personal Pattern Creation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-file-extensions-windows-guide/"><u>Switching File Extensions: Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-non-start-troubles-in-csgo-and-w11/"><u>Tackling Non-Start Troubles in CS:GO & W11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-90-pro-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-insight-into-budget-friendly-design-portals/"><u>[Updated] Exclusive Insight Into Budget-Friendly Design Portals</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-installed-optional-windows-functions-a-7-step-guide/"><u>Fixing Non-Installed Optional Windows Functions: A 7-Step Guide</u></a></li>
<li><a href="https://discord-videos.techidaily.com/no-cost-high-quality-logos-your-free-discord-tool-for-2024/"><u>No-Cost, High-Quality Logos - Your Free Discord Tool for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-draw-on-the-desktop-on-windows-11-and-11/"><u>How to Draw on the Desktop on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-non-responsive-services-on-windows-pcs/"><u>Steps to Rectify Non-Responsive Services on Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/fix-infinix-zero-30-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Infinix Zero 30 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-restart-printers-automatic-service-in-win/"><u>Methods to Restart Printer's Automatic Service in Win</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-funimate-video-mastery-a-comprehensible-guide/"><u>[New] Funimate Video Mastery  A Comprehensible Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synchronizing-camera-use-among-windows-programs/"><u>Synchronizing Camera Use Among Windows Programs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-smoother-video-playback-on-chromebook-and-mobile-devices/"><u>2024 Approved  Smoother Video Playback on Chromebook & Mobile Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-fast-track-to-1000-fans-through-captivating-content/"><u>2024 Approved  Fast-Track To 1,000 Fans Through Captivating Content</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-whats-the-best-aspect-ratio-for-twitter-videos/"><u>Updated In 2024, Whats the Best Aspect Ratio for Twitter Videos?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-system-restore-a-guide-to-rollbacks/"><u>Mastering Windows' System Restore: A Guide to Rollbacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-absent-d3dx939dll-on-windows-11/"><u>Remedying Absent D3DX9_39.dll on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-directory-management-without-renaming-features-in-windows-11/"><u>Mastering Directory Management without Renaming Features in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/best-of-the-best-12-screen-capture-tools-no-end-for-2024/"><u>Best of the Best 12 Screen Capture Tools (No End) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disk-designations-c-and-d-varieties/"><u>Navigating Disk Designations: C and D Varieties</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-to-amd-gpu-software-on-pcs/"><u>Restoring Functionality to AMD GPU Software on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-correcting-ipad-picture-importer-mishaps-in-windows/"><u>Quick Guide: Correcting iPad Picture Importer Mishaps in Windows</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-10-top-tools-to-make-pic-collage-for-windows/"><u>In 2024, 10 Top Tools to Make Pic Collage for Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-iphone-8-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/onedrive-repositioning-in-the-windows-11-environment/"><u>OneDrive Repositioning in the Windows 11 Environment</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-the-complete-wm-maker-playbook-for-youtube-clips-perfection/"><u>[New] 2024 Approved  The Complete WM Maker Playbook for YouTube Clips Perfection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-resolving-microsoft-store-error-on-windows-devices/"><u>Tips for Resolving Microsoft Store Error on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-terminal-to-enter-quake-interface/"><u>Using Terminal to Enter Quake Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/joining-forces-onedrive-and-windows-live-account-sync/"><u>Joining Forces: OneDrive & Windows Live Account Sync</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-upgrade-error-xc004f050-code/"><u>Unblocking Windows Upgrade Error Xc004f050 Code</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/budget-friendly-vlogging-cameras-unveiled-our-picks/"><u>Budget-Friendly Vlogging Cameras Unveiled  Our Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11s-geforce-now-error-xc0f1103f/"><u>Tackling Windows 11'S GeForce Now Error Xc0f1103f</u></a></li>
<li><a href="https://extra-hints.techidaily.com/synchronized-intro-editing-across-all-your-devices-this-year/"><u>Synchronized Intro Editing Across All Your Devices This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-updater-failures-0xca00a009/"><u>Mastering the Art of Fixing Updater Failures #0xCA00A009</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-beginners-obs-techniques-for-youtube-live-streaming/"><u>[Updated] In 2024, Beginner's OBS Techniques for YouTube Live Streaming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-premium-zero-price-point-live-capture-app/"><u>[New] 2024 Approved  Premium Zero-Price Point Live Capture App</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-apples-finest-best-video-editing-software-for-mac/"><u>New In 2024, Apples Finest Best Video Editing Software for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedies-for-non-functional-windows-alt-codes-49-characters/"><u>Quick Remedies for Non-Functional Windows Alt Codes (49 Characters)</u></a></li>
</ul></div>
