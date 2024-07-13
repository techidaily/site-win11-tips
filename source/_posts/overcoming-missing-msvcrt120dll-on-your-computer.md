---
title: Overcoming Missing Msvcrt120dll on Your Computer
date: 2024-07-12T17:28:50.640Z
updated: 2024-07-13T17:28:50.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Missing Msvcrt120dll on Your Computer
excerpt: This Article Describes Overcoming Missing Msvcrt120dll on Your Computer
keywords: Fix DLL Issue,MSVCrt120dll Remedy,Resolve Missing DLL,Cure System Crash,Address DLL Absence,Correct File Error,Rectify Software Glitch
thumbnail: https://thmb.techidaily.com/2a86960040387567ee8a74265a39e135c9493f594810dac12c910c9d9ffd0bfb.jpg
---

## Overcoming Missing Msvcrt120dll on Your Computer

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
<li><a href="https://youtube-videos.techidaily.com/updated-choreographing-narrative-news-wrappers/"><u>[Updated] Choreographing Narrative News Wrappers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-11-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cc-errors-on-windows-10-a-step-by-step-guide/"><u>Mastering CC Errors on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hdr-power-play-is-sns-the-best-option/"><u>2024 Approved  HDR Power Play  Is SNS the Best Option?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-1011-eliminating-email-app-errors/"><u>Mending Windows 10/11: Eliminating Email App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-robloxs-access-denied-error-403/"><u>How to Eradicate Roblox's Access Denied (Error 403)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fix-for-winerror-xc004f050/"><u>Mastering Fix for WinError Xc004f050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-print-control-in-windows-11-9-ways-short-version-max-48-chars/"><u>Navigating Print Control in Windows 11 (9 Ways) - Short Version (Max 48 Chars)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-top-5-capture-tools-dethroning-bandicam-on-apple-devices/"><u>In 2024, Top 5 Capture Tools Dethroning Bandicam on Apple Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-speed-by-tweaking-msram/"><u>Regain Speed by Tweaking MSRam</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-best-video-editors-with-smart-auto-reframe/"><u>New In 2024, Best Video Editors with Smart Auto-Reframe</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-teenyvid-viewers-assessment-on-screenshots/"><u>[New] TeenyVid Viewer's Assessment on Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80070570-error-in-windows-restoring-damaged-data/"><u>Overcoming 0X80070570 Error in Windows: Restoring Damaged Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-default-energy-management-in-windows-11/"><u>Regaining Default Energy Management in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-with-ease-access-calculator/"><u>Navigating Windows 11 with Ease: Access Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-instant-addition-problems-with-windows-onedrive-a-compreenhensive-guide/"><u>Resolving Instant Addition Problems with Windows OneDrive - A Compreenhensive Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/love-tunes-trove-a-top-10-list-for-heartfelt-proposals-for-2024/"><u>Love Tunes Trove  A Top 10 List for Heartfelt Proposals for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-methods-to-address-windows-activation-failure-code-0x803f700f/"><u>Precise Methods to Address Windows Activation Failure Code 0X803F700f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-decades-old-windows-authentication-error/"><u>Reversing Decades-Old Windows Authentication Error</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-symbiotic-relationship-between-cities-and-ecology/"><u>2024 Approved  The Symbiotic Relationship Between Cities and Ecology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-complexities-of-docker-with-wsl-2/"><u>Navigating the Complexities of Docker with WSL 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-invisible-displays-when-gaming-on-win-os/"><u>Preventing Invisible Displays When Gaming on Win OS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-mac-video-editing-essentials-best-software-options/"><u>Updated In 2024, Mac Video Editing Essentials Best Software Options</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/vlog-verily-tips-and-taboos-in-the-daily-digital-sphere-for-2024/"><u>Vlog Verily  Tips and Taboos in the Daily Digital Sphere for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-what-is-lumetri-color-and-how-do-you-use-it-in-adobe-after-effects-find-out-the-numerous-functions-of-lumetri-panel-and-ways-to-apply-them-to-your-v/"><u>In 2024, What Is Lumetri Color and How Do You Use It in Adobe After Effects? Find Out the Numerous Functions of Lumetri Panel and Ways to Apply Them to Your Video</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-add-and-custom-slack-emoji-wondershare-filmora/"><u>New How to Add and Custom Slack Emoji-Wondershare Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-multi-screen-setup-on-windows-11/"><u>Mastering Multi-Screen Setup on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-suppress-gaming-suggestions-in-windows-11-ui/"><u>How to Suppress Gaming Suggestions in Windows 11 UI</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-seo-success-precision-crafted-video-titles-and-tags-for-2024/"><u>Unlock SEO Success  Precision-Crafted Video Titles and Tags for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-update-audio-drivers-on-windows/"><u>How to Update Audio Drivers on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-swift-typing-techniques-with-powertoys/"><u>Master Swift Typing Techniques with PowerToys</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-panopticon-perspective-analysis/"><u>2024 Approved  Panopticon Perspective Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-printer-connection-failsafes-in-windows/"><u>Overcoming Printer Connection Failsafes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-windows-landscape-incorporate-outlook-preview/"><u>Master the Windows Landscape: Incorporate Outlook Preview</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-unlimited-video-editing-top-10-free-online-editors-with-no-watermark/"><u>In 2024, Unlimited Video Editing Top 10 Free Online Editors with No Watermark</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-updater-problem-code-0x8019/"><u>Overcoming Updater Problem: Code 0X8019</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-android-to-windows-shared-drives/"><u>Navigating Android to Windows Shared Drives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-slow-or-non-responsive-windows-download-area/"><u>Repairing Slow or Non-Responsive Windows Download Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-persistent-enter-network-credentials-message-on-windows/"><u>How to Fix a Persistent Enter Network Credentials Message on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-and-change-the-subnet-mask-in-windows-11/"><u>How to Find and Change the Subnet Mask in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-presentations-physical-form-essential-strategies-for-prints-in-windows/"><u>Mastering Your Presentations' Physical Form: Essential Strategies for Prints in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-frolic-fables-a-vhs-review-of-the-comical-epic/"><u>2024 Approved  'Frolic Fables' - A VHS Review of The Comical Epic</u></a></li>
</ul></div>
