---
title: Eradicating Error X.7007043C in Windows' Media Creator
date: 2024-06-25T16:09:25.513Z
updated: 2024-06-26T16:09:25.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating Error X.7007043C in Windows' Media Creator
excerpt: This Article Describes Eradicating Error X.7007043C in Windows' Media Creator
keywords: Eradicating Error 7007043C,Fixing Media Creator Errors,WinMediaCreator Corrections,Removing Windows Error XYZ,Resolve X.7007043C Issue,Media Creator Troubleshoot,Overcoming Windows 7 Error
thumbnail: https://thmb.techidaily.com/7ad836b78743150f7926162559e15271095acf4f64d610e7943b29ad8777b2c6.jpg
---

## Eradicating Error X.7007043C in Windows' Media Creator

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
<li><a href="https://win11-tips.techidaily.com/streamline-operations-7-easy-tips-for-advanced-windows-11-users/"><u>Streamline Operations: 7 Easy Tips for Advanced Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/iosandroid-sync-with-windows-server-files/"><u>IOS/Android: Sync with Windows Server Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-speedy-pointers-curtailing-acceleration-on-windows-11/"><u>Say Goodbye to Speedy Pointers: Curtailing Acceleration on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solutions-for-we-encountered-an-error-during-oculus-install/"><u>Step-By Step Solutions for We Encountered an Error During Oculus Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-your-lost-dxgidll-with-these-win11-hacks/"><u>Restore Your Lost Dxgi.dll with These Win11 Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-same-account-error-in-multiuser-setup/"><u>Eradicating Same Account Error in Multiuser Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-device-safety-increase-win11-pin-length/"><u>Elevate Your Device Safety: Increase Win11 PIN Length</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-micro-musings-video-characters-and-sounds/"><u>[New] Micro Musings  Video Characters & Sounds</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-elevate-your-online-communication-the-best-skype-voice-changing-technologies/"><u>Updated In 2024, Elevate Your Online Communication The Best Skype Voice Changing Technologies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-prime-selection-of-invisible-android-recorders/"><u>[Updated] In 2024, Prime Selection of Invisible Android Recorders</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-say-goodbye-to-format-issues-the-top-12-audio-converters-for-easy-conversion/"><u>2024 Approved Say Goodbye to Format Issues The Top 12 Audio Converters for Easy Conversion</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-xs-max-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone XS Max Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-how-to-achieve-and-share-your-most-lengthy-instagram-videos/"><u>[Updated] How to Achieve and Share Your Most Lengthy Instagram Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-photosynth-pros-a-quick-snapchat-peek/"><u>[New] 2024 Approved  Photosynth Pros  A Quick Snapchat Peek</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-vivo-s17e-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Vivo S17e by Name | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a24-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A24 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
</ul></div>
