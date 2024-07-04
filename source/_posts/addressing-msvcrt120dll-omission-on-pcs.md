---
title: Addressing Msvcrt120dll Omission on PCs
date: 2024-07-03T12:48:22.589Z
updated: 2024-07-04T12:48:22.589Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/tackling-wi-fi-troubles-with-ease-filling-out-action-deficiencies/"><u>Tackling Wi-Fi Troubles with Ease: Filling Out Action Deficiencies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-chatting-experience-with-10-fixes/"><u>Revitalize Your Chatting Experience with 10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-your-preferred-soft-install-tool-on-win-devices/"><u>Finding Your Preferred Soft Install Tool on Win Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-elite-windows-apps-for-data-security-149-chars/"><u>7 Elite Windows Apps for Data Security (149 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-shutdownrestart-blockage-due-to-deceptive-apps-in-windows/"><u>Counteracting Shutdown/Restart Blockage Due to Deceptive Apps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mail-troubleshooting-unraveling-the-zero-x-eight-oh-three-one-f-mystery/"><u>Windows Mail Troubleshooting: Unraveling the Zero X Eight Oh Three One F Mystery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-lock-personal-pattern-creation-tutorial/"><u>Mastering Window's Lock: Personal Pattern Creation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-unlocking-windows-11/"><u>Quick Guide: Unlocking Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-tactics-skirting-windows-account-sign-ins/"><u>Avoidance Tactics: Skirting Windows Account Sign-Ins</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-chroma-key-techniques-in-live-broadcasts/"><u>[Updated] Mastering Chroma Key Techniques in Live Broadcasts</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/lighting-the-way-enhancing-your-youtube-videos-with-pro-tips-for-2024/"><u>Lighting the Way  Enhancing Your YouTube Videos with Pro Tips for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-comparative-analysis-of-fb-video-formats/"><u>2024 Approved  Comparative Analysis of FB Video Formats</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-premier-choices-ubuntus-best-recorders/"><u>[Updated] In 2024, Premier Choices  Ubuntu's Best Recorders</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-device-footage-to-youtube-shorts-your-streamlined-approach/"><u>[Updated] From Device Footage to YouTube Shorts - Your Streamlined Approach</u></a></li>
<li><a href="https://extra-tips.techidaily.com/firefox-pip-a-complete-users-manual/"><u>Firefox PIP  A Complete User's Manual</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamlining-your-subtitle-workflow-with-leading-online-tools/"><u>In 2024, Streamlining Your Subtitle Workflow with Leading Online Tools</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/sonic-elevation-in-podcasting-unveiling-11-premier-locations-to-acquire-soundscapes/"><u>Sonic Elevation in Podcasting Unveiling 11 Premier Locations to Acquire Soundscapes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-multimedia-craftsmanship-with-xp-movie-maker/"><u>[Updated] Explore Multimedia Craftsmanship with XP Movie Maker</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>