---
title: "How to Solve Media Creator Tool Errors: WinError 0X8007043C"
date: 2024-06-25T16:51:01.645Z
updated: 2024-06-26T16:51:01.645Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Solve Media Creator Tool Errors: WinError 0X8007043C"
excerpt: "This Article Describes How to Solve Media Creator Tool Errors: WinError 0X8007043C"
keywords: Media Creator Fix Guide,Resolving WinError 0X8007043c,WinError Error Solution,Media Tool Error Troubleshooting,Handling WinError in Windows,Eliminating WinError Media Errors,Solve WinError 0X8007043C Issue
thumbnail: https://thmb.techidaily.com/a8037b9cb425e19a9ec57f5feba58cc91bfb4e98ab568e20793fc881abc0b40e.jpg
---

## How to Solve Media Creator Tool Errors: WinError 0X8007043C

 The Media Creation Tool lets you upgrade your PC to a new Windows version or create a bootable Windows USB drive. At times, when you try to run the tool, you may encounter the error code 0x8007043C - 0x90017.

 The primary reason for this error is insufficient permission to run the tool or if it has been blocked from running on your PC. You can unblock it from the tool's properties to fix the error. Here is how to fix the Media Creation Tool 0x8007043C - 0x90017 error and perform an upgrade or create a bootable drive.

## 1\. Run the Media Creation Tool as an Administrator

 You can fix permission issues by executing the Media Creation Tool with administrator privileges. By default, the tool does not require administrator rights to run. But you can [manually run Windows apps as an administrator](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) to see if that resolves the error.

To run Media Creation Tool as administrator:

1. Open File Explorer and navigate to where you have saved the**mediacreationtool.exe** file.
2. Right-click on the**Mediacreationtool.exe** file and select**Run as administrator.**  
![run media creation tool as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-media-creation-tool-as-administrator.jpg)
3. Click**Yes** when prompted by UAC. Wait for the tool to launch and check for any improvements.

## 2\. Unblock the Media Creation Tool

 Windows can block suspicious executable files from running to protect your computer. However, it can also block genuine files due to false positives.

 If you have downloaded the Media Creation Tool from the Microsoft website, check if the file is blocked on your PC. If yes, you can unblock the executable file from the Properties dialog. Here’s how to do it.

1. Navigate to the location where the Media Creation Tool is saved.
2. Select and right-click on the tool and select**Properties** .
3. In the**General** tab, locate the**Security** section.
4. Next, check the**Unblock** option.  
![unblock media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/unblock-media-creation-tool.jpg)
5. Click**Apply** , and the security option will disappear.
6. Next, click**OK** to apply the changes.
7. Run the Media Creation Tool again, and it should work without the 0x8007043C - 0x90017 error.

## 3\. Install Any Pending Windows Updates

 If the error occurs during an upgrade, ensure you have installed all the latest updates available for your PC. Often Windows updates consist of performance improvements and bug fixes. Install all the updates to see if that helps you resolve any issues interrupting the upgrade process.

To update your Windows computer:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows update** tab in the left pane.
3. Click on**Check for updates** to find the pending updates.  
![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)
4. If available, click on**Download & Install** and wait for the updates to install. Restart your PC and run the tool again to see if the error is resolved.

## 4\. Run the Windows Update Troubleshooter

 The built-in Windows Update troubleshooter is a great way to fix Windows Update issues on Windows 11\. It will scan the system for issues and try to fix them automatically.

To run the Windows Update Troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .  
![Windows 11 settings troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot.jpg)
3. Next, click on**Other troubleshooters.**  
![Windows-11-settings-troubleshoot-other-troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-troubleshoot-other-troubleshooters.jpg)
4. Under the**Most frequent** section, click the**Run** button for**Windows Update.**  
![windows update troubleshooter run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-run.jpg)
5. The update troubleshooter will initialize diagnostic and scan for issues. If found, it will apply the fix and show a status report. With the Windows Update dialog open, run Media Creation Tool and check if the error is resolved.
6. If not, click**No** in the Windows Update troubleshooter dialog.
7. Next, click on**View detailed** information. Here you can view the issues found and potential issues that were checked.

## 5\. Check for a Third-Party Antivirus Conflict

 Third-party antivirus can be overzealous and block genuine system modifications as malicious. You can disable the security app temporarily to determine if your third-party antivirus is triggering the error.

 Once disabled, relaunch the Media Creation Tool and check if the error persists. If not, check and reconfigure your antivirus settings or switch to one of the [best antivirus solutions on Windows](https://www.makeuseof.com/windows-11-antivirus-apps/) .

## 6\. Run the DISM and System File Checker Tool

 Deployment Image Servicing and Management (DISM) is a command-line tool to repair your Windows 10 and 11 images. It can look for corrupted or missing system files and repair them to fix critical errors on your PC.

 System File Checker utility can help you fix malfunctioning Windows functions. It will scan the system for issues and, if detected, restore the necessary files to fix the problem. You can run the DISM and System File Checker tools in tandem to get the best result. Here’s how to do it.

To run the DISM and System File Checker Tool:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command** **Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command to run the DISM tool:  
DISM.exe /Online /Cleanup-image /Restorehealth
4. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt.jpg)  
 Press**Enter** to execute the command. It may take some time for the process to complete. Once the process reaches 100%, you can run the System File Checker tool.
5. Type the following command and press**Enter** to run the System File Checker utility:  
sfc /scannow
6. The verification can take several minutes. So wait for the verification to reach 100%. The return will indicate if any issue is found and if the tool was able to fix it.
7. Type**exit** and press**Enter** to close the Command Prompt.

## 7\. Use Rufus to Create a Bootable USB Drive

 While Media Creation Tools lets you create a bootable drive, it is not your only option. You can use a popular third-party app, Rufus, to [create a bootable Windows USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/) . You can [download a Windows 11 ISO file](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft servers and then use it to create an installation media using Rufus.

 Rufus is safe to use and offers some customization, such as choosing a partition format. You can also download the ISO file using Rufus.

## 8\. Perform a Repair Reinstall or Clean Install Windows

 Before we do a full clean of Windows, consider performing a repair reinstall. This allows you to perform an in-place upgrade and [reinstall the Windows OS without deleting your files and apps](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) .

 If all else fails, a clean install may be necessary. Make sure to create a backup of your data and then learn [how to clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/) .

## Fixing the Media Creation Tool Error 0x8007043C - 0x90017 Error

 The 0x8007043C - 0x90017 Media Creation Tool error is often due to an insufficient permission issue. You can unblock the utility in the Properties dialog to run the utility without the error. Only in rare instances, you may need to perform a clean install due to system file corruption.


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
<li><a href="https://win11-tips.techidaily.com/how-to-apply-local-group-policies-to-a-specific-user-account-in-windows-10-and-11/"><u>How to Apply Local Group Policies to a Specific User Account in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-with-apple-maps-from-a-pc/"><u>Steering with Apple Maps From a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-operating-systems-state-a-windows-1011-reboot-guide/"><u>Overhauling Your Operating System's State: A Windows 10/11 Reboot Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-deadly-error-0x8007045d-on-windows-pcs/"><u>Eliminating Deadly Error: 0X8007045D on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-file-tracking-the-ultimate-guide-to-copying-windows-11-filesystem-trails-6-methods/"><u>Winning at File Tracking: The Ultimate Guide to Copying Windows 11 Filesystem Trails (6 Methods)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-down-clutter-tackling-large-storage-consumers-in-windows/"><u>Cut Down Clutter: Tackling Large Storage Consumers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-pcs-dns-cache-efficiently/"><u>Revamp Your PC's DNS Cache Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-library-no-sync-error-solution/"><u>Tackling Steam Library: No Sync Error Solution</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-unlocking-crossfade-magic-using-audacity-effectively-for-2024/"><u>[Updated] Unlocking Crossfade Magic  Using Audacity Effectively for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ultimate-windows-11-screen-recorder-guide/"><u>In 2024, Ultimate Windows 11 Screen Recorder Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-list-of-websites-for-text-styling-tools/"><u>In 2024, Expert List of Websites for Text Styling Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-savings-straightforward-and-diversified-methods-unveiled/"><u>[Updated] Instagram Savings  Straightforward & Diversified Methods Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-easy-ways-to-record-steam-gameplay-2023/"><u>2024 Approved  Easy Ways to Record Steam Gameplay 2023</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-free-video-editors-easy-peasy-for-newbies/"><u>New Best Free Video Editors Easy Peasy for Newbies</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-faster-powerpoint-tips-for-quick-video-viewing/"><u>In 2024, Faster PowerPoint  Tips for Quick Video Viewing</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-perfecting-sound-quality-adding-lame-to-your-audacity-setup/"><u>New 2024 Approved Perfecting Sound Quality Adding Lame to Your Audacity Setup</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/learn-how-to-slow-down-time-lapse-videos-on-your-iphone-to-make-detailed-slow-motion-effects-in-your-time-lapse-captures-for-2024/"><u>Learn How to Slow Down Time-Lapse Videos on Your iPhone to Make Detailed Slow-Motion Effects in Your Time-Lapse Captures for 2024</u></a></li>
</ul></div>
