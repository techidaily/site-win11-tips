---
title: 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
date: 2024-07-12T17:58:44.484Z
updated: 2024-07-13T17:58:44.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
excerpt: This Article Describes 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
keywords: Windows Defender Fault,Fixing Defender Issues,WinDefend Unavailability,Disable Security Errors,Threat Engine Restoration,Protect From Virus Glitch,Resolve WinDefend Failure
thumbnail: https://thmb.techidaily.com/d4a369170dd24048d49b11ae6cda29b689bc2d38aadd635d4ed1887b04b3b67e.jpg
---

## 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the [Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the [different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses [how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some [best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.


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
<li><a href="https://win11-tips.techidaily.com/9-simple-steps-to-fix-server-not-found-error-on-windows-pcs-in-apex-legends-(156-chars/"><u>9 Simple Steps to Fix 'Server Not Found' Error on Windows PCs in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-directories-to-w11s-right-click-menu-steps/"><u>Adding Directories to W11's Right-Click Menu Steps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-cutting-through-chatter-effective-discord-responses/"><u>2024 Approved  Cutting Through Chatter  Effective Discord Responses</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-studio-sessions-best-practices-15-youtube-production-guides-for-musicians/"><u>The Studio Sessions  Best Practices - 15 YouTube Production Guides for Musicians</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-new-windows-11-perks-after-version-update/"><u>10 New Windows 11 Perks After Version Update</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-essential-skills-for-harvesting-and-storing-gifs-from-facebooks-feed/"><u>[Updated] 2024 Approved  Essential Skills for Harvesting and Storing GIFs From Facebook's Feed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719244514852-enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719333011753-4-proven-strategies-for-enhancing-window-shot-taking-on-windows-os/"><u>4 Proven Strategies for Enhancing Window Shot Taking on Windows OS.</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-capturing-excellence-the-best-camera-lenses/"><u>[New] Capturing Excellence  The Best Camera Lenses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-file-extraction-failure-fix-for-error-1152-in-win/"><u>Addressing File Extraction Failure: Fix for Error 1152 in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-recently-used-windows-with-ease/"><u>Accessing Recently Used Windows with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-invalid-update-file-signatures-on-winoses/"><u>Addressing Invalid Update File Signatures on WinOSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-id-inaccuracy-in-windows-11/"><u>Addressing System ID Inaccuracy in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719353749292-navigate-compatibility-hurdles-with-easy-to-follow-steps/"><u>Navigate Compatibility Hurdles with Easy-to-Follow Steps.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-fix-strategies-for-your-windows-resolution-dilemmas/"><u>10 Fix Strategies for Your Windows Resolution Dilemmas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-internal-error-during-win10-remote-access/"><u>Addressing Internal Error During Win10 Remote Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-gmaps-installation-on-pc/"><u>A Step-by-Step Approach to GMaps Installation on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719228801666-streamline-help-process-for-windows-snags/"><u>Streamline Help Process for Windows Snags</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-video-to-image-how-to-convert-videos-to-photos/"><u>New In 2024, Video to Image How to Convert Videos to Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719239834039-start-menu-no-more-unwanted-advertisements/"><u>Start Menu, No More Unwanted Advertisements</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-essential-fixes-to-tackle-fb-story-load-failures/"><u>2024 Approved  Essential Fixes to Tackle Fb Story Load Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-failures-when-attempting-to-share-via-experience/"><u>Addressing Failures When Attempting to Share via Experience</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-narzo-60x-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme Narzo 60x 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-overcoming-cannot-find-gpeditmsc/"><u>A Step-by-Step Guide to Overcoming Cannot Find Gpedit.msc</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-best-free-3d-text-psd-files/"><u>[New] Best Free 3D Text PSD Files</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-audacity-guide-cutting-out-unwanted-sounds/"><u>[New] In 2024, Audacity Guide  Cutting Out Unwanted Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-steps-for-efficient-access-to-windows-connections-tool/"><u>10 Key Steps for Efficient Access to Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-app-launch-with-windows-11/"><u>Accelerate Your App Launch with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-gaining-entry-into-windows-11s-application-repository/"><u>A Guide to Gaining Entry Into Windows 11'S Application Repository</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-with-windows-11-at-home/"><u>Addressing Incompatibility with Windows 11 at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-remove-a-saved-wi-fi-network-from-windows-11/"><u>4 Ways to Remove a Saved Wi-Fi Network From Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719350537828-navigating-troubled-waters-help-for-your-windows-woes/"><u>Navigating Troubled Waters: Help for Your Windows Woes!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/uncomplicated-video-logging-tool-w10-for-2024/"><u>Uncomplicated Video Logging Tool  W10 for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-unleashing-your-funny-bone-a-stepwise-guide-to-making-memes-on-9gag/"><u>[New] 2024 Approved  Unleashing Your Funny Bone  A Stepwise Guide to Making Memes on 9GAG</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-how-to-record-your-screen-on-windows-8/"><u>[New] 2024 Approved  How To Record Your Screen On Windows 8</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guide-to-structuring-youtube-content-with-separate-chapters/"><u>[New] 2024 Approved  Guide to Structuring YouTube Content with Separate Chapters</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-top-picks-of-firefox-tools-to-streamline-your-facebook-video-experience-2023/"><u>2024 Approved  Top Picks of Firefox Tools to Streamline Your Facebook Video Experience, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-close-examination-of-9-key-factors-that-advantage-pcs/"><u>A Close Examination of 9 Key Factors That Advantage PCs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-simplifying-slides-with-vimeo-video-integration-tutorial/"><u>2024 Approved  Simplifying Slides with Vimeo Video Integration Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-themed-settings-for-education-on-windows-11/"><u>Activating Themed Settings for Education on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719355808573-how-to-reactivate-and-rescue-non-responsive-printer-feature-via-win-plus-p-in-windows/"><u>How to Reactivate and Rescue Non-Responsive Printer Feature via Win + P in Windows.</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-vr-bikes-to-check-out/"><u>[New] Top VR Bikes to Check Out</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-whatsapp-video-converterkeywords-convert-video-for-whatsapp-6600-video-converter-for-whatsapp-6600-reduce-video-size-for-whatsapp-1600-whatsap/"><u>2024 Approved Whatsapp Video converterKeywords Convert Video for Whatsapp 6600; Video Converter for Whatsapp 6600; Reduce Video Size for Whatsapp 1600; Whatsapp Supported Video Formats 720; Convert Video to Whatsapp Format 590</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-advanced-protection-features-for-win-11s-edge-using-defender-aguard/"><u>Activate Advanced Protection Features for Win 11'S Edge Using Defender Aguard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719367478733-overcome-windows-obstacles-expert-advice-awaits/"><u>Overcome Windows Obstacles: Expert Advice Awaits</u></a></li>
</ul></div>
