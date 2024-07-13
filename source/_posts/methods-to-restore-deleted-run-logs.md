---
title: Methods to Restore Deleted Run Logs
date: 2024-07-12T17:13:09.965Z
updated: 2024-07-13T17:13:09.965Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to Restore Deleted Run Logs
excerpt: This Article Describes Methods to Restore Deleted Run Logs
keywords: Recovering Run Logs,Restoring Deleted Logs,Data Backup for Logs,RunLog Recovery Methods,Resetting System Logs,Log Deletion Fixes,Reinstating Run Records
thumbnail: https://thmb.techidaily.com/c6867ae9c4f4e3df3c9379b15f4163ebd35319a50b7aab7a2fe4029be64b0298.jpg
---

## Methods to Restore Deleted Run Logs

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-failed-speech-recognition-launch-in-windows/"><u>Troubleshooting Failed Speech Recognition Launch in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undetectable-disk-hiding-methods-in-windows-10-and-11/"><u>Undetectable Disk Hiding Methods in Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-infinix-smart-8-hd-easily-by-drfone-android/"><u>How To Unlock a Infinix Smart 8 HD Easily?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-from-grayscale-to-graded-grandeur-color-artistry/"><u>[Updated] From Grayscale to Graded Grandeur  Color Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-microsoft-can-improve-windows-11-widgets/"><u>8 Ways Microsoft Can Improve Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-aggregatorhostexe-on-windows-exploring-its-functionality-and-safety/"><u>What Is AggregatorHost.exe on Windows? Exploring Its Functionality and Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-saved-audio-configurations-winvolume-hacks/"><u>Bring Back Saved Audio Configurations: WinVolume Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-file-locks-turn-off-read-only-windows-mode/"><u>Altering File Locks: Turn Off Read-Only Windows Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-photo-error-on-windows-devices-efficiently/"><u>Troubleshoot Photo Error on Windows Devices Efficiently</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-infinix-note-30-5g-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from Infinix Note 30 5G</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/instagram-video-to-mp3-everything-you-need-to-know-for-2024/"><u>Instagram Video to Mp3 - Everything You Need to Know for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unlock-high-end-screenshot-capabilities-for-free-for-2024/"><u>Unlock High-End Screenshot Capabilities for Free for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-k70-pro-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi K70 Pro Phone without Google Account?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-command-power-in-minutes/"><u>Unlock Full Command Power in Minutes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719220019899-unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-samsungs-photography-toolkit/"><u>In 2024, Exploring Samsung's Photography Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-win-hardware-testing-with-these-premier-graphics-tools/"><u>Ace Win Hardware Testing with These Premier Graphics Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-the-art-of-blurring-parts-in-digital-pictures/"><u>In 2024, Master the Art of Blurring Parts in Digital Pictures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-digital-snare-spotting-invisible-threats/"><u>Avoid the Digital Snare: Spotting Invisible Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-insufficient-access-block-during-uninstalls/"><u>Bypassing Windows' Insufficient Access Block During Uninstalls</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-x50iplus-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor X50i+ Through Google Earth?</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-the-puzzle-of-facebooks-re-branding-plans/"><u>Exploring the Puzzle of Facebook's Re-Branding Plans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-a-ram-cache-and-how-do-you-clear-it-on-windows/"><u>What Is a RAM Cache, and How Do You Clear It on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-apps-to-increase-the-volume-beyond-100-percent-in-windows/"><u>4 Apps to Increase the Volume Beyond 100 Percent in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-your-powershell-scripts/"><u>Unlock the Full Potential of Your PowerShell Scripts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-life-without-official-windows-xp-7-or-81-support/"><u>Adjusting to Life Without Official Windows XP, 7, or 8.1 Support</u></a></li>
</ul></div>
