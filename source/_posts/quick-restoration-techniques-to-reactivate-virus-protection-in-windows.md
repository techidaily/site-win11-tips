---
title: Quick Restoration Techniques to Reactivate Virus Protection in Windows
date: 2024-07-12T17:45:33.217Z
updated: 2024-07-13T17:45:33.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Restoration Techniques to Reactivate Virus Protection in Windows
excerpt: This Article Describes Quick Restoration Techniques to Reactivate Virus Protection in Windows
keywords: Virus Protection Activation,Windows Security Reinstatement,Quick System Defense Revive,Rapid Safeguard Restoration,Reset Antivirus on WinOS,Immediate Anti-Malware Reactivate,Swift Malware Shield Regain
thumbnail: https://thmb.techidaily.com/4dbf33f37ff64fa1cd0b3b86eb483d2b61e4dcfaa2f3492f28ea818842097e14.jpg
---

## Quick Restoration Techniques to Reactivate Virus Protection in Windows

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
<li><a href="https://win11-tips.techidaily.com/how-to-manage-windows-applications-without-admin-rights/"><u>How to Manage Windows Applications Without Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-digital-containers-file-prop-techniques/"><u>Navigating Digital Containers: File Prop Techniques</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-marketers-methods-detecting-illusory-engagement-signals-for-2024/"><u>[Updated] Marketers’ Methods  Detecting Illusory Engagement Signals for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-poco-c50-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Poco C50 | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tastebudstribe-leading-foodie-influencers/"><u>TasteBudsTribe  Leading Foodie Influencers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-tailored-approach-boosting-fans-via-page-ranking/"><u>[New] 2024 Approved  Tailored Approach  Boosting Fans via Page Ranking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-closed-folder-issues-in-winxpxo11-on-double-click/"><u>How to Tackle Closed Folder Issues in WinXP/XO11 on Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-the-impact-reducing-unrealcefsubprocess-load-in-windows/"><u>Mitigating the Impact: Reducing UnrealCEFSubprocess Load in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-administrator-access-via-cmd/"><u>Instant Administrator Access via CMD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-directories-a-breeze-with-win11-essentials/"><u>Making Directories a Breeze with Win11 Essentials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-overcome-windows-file-not-found-error/"><u>Methods to Overcome Windows 'File Not Found' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/how-to-retreat-from-macos-sierras-latest-upgrade/"><u>How to Retreat From MacOS Sierra's Latest Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-resolution-of-windows-error-1132-in-zoom/"><u>Master the Resolution of Window's Error 1132 in Zoom</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-the-complete-guide-to-social-media-image-optimization-aspect-ratios-and-more/"><u>2024 Approved The Complete Guide to Social Media Image Optimization Aspect Ratios and More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-build-custom-text-transcription-software-on-windows-with-whisper/"><u>How to Build Custom Text Transcription Software on Windows with Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insiders-look-at-windows-boot-configuration-management/"><u>Insider's Look at Windows Boot Configuration Management</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-streamlining-your-timeline-leading-tools-to-unfollow-tweets/"><u>2024 Approved  Streamlining Your Timeline  Leading Tools to Unfollow Tweets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-through-windows-camera-saving-errors/"><u>Guiding Through Windows Camera Saving Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-find-windows-background-save-spot-in-11/"><u>How to Find Window's Background Save Spot in 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-taking-views-viral-the-ultimate-guide-for-youtube-success/"><u>In 2024, Taking Views Viral  The Ultimate Guide for YouTube Success</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-ultimate-guide-to-negative-time-videos-on-instagram/"><u>The Ultimate Guide to Negative-Time Videos on Instagram</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/miniature-music-menus-actors-in-audio-world-for-2024/"><u>Miniature Music Menus  Actors in Audio World for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-oppo-find-x6-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Oppo Find X6? Fixed | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-vivo-x-fold-2-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Vivo X Fold 2?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-how-to-stabilize-videos-with-google-photos-app-for-free-for-2024/"><u>New How to Stabilize Videos with Google Photos App for Free for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-windows-11-shutdown-time-for-tasks-in-progress/"><u>Modifying Windows 11 Shutdown Time for Tasks in Progress</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-overcoming-d3d11-gpu-hurdles-in-w11w10/"><u>Quick Guide to Overcoming D3D11 GPU Hurdles in W11/W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-security-faults-and-fixes/"><u>Navigating Through Windows Security Faults & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fn-key-techniques-for-efficient-windows-use/"><u>Fn Key Techniques for Efficient Windows Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-wls-techniques-unlocking-the-full-power-of-wsl-2-in-win-oses/"><u>Pro WLS Techniques: Unlocking the Full Power of WSL 2 in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-software-deletion-in-windows-11-115-chars/"><u>Mastering Software Deletion in Windows 11 (115 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-techniques-to-accelerate-steam-downloads-on-windows/"><u>Master Techniques to Accelerate Steam Downloads on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beam-me-up-optimal-webcam-choices-for-podcasts/"><u>In 2024, Beam Me Up  Optimal Webcam Choices for Podcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-disconnects-and-fixes-javascript-issues-in-discord-win-11/"><u>Mastering Disconnects & Fixes: JavaScript Issues in Discord Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-password-policy-update-lockout-value-post-incorrect-attempts/"><u>Modifying Password Policy: Update Lockout Value Post Incorrect Attempts</u></a></li>
</ul></div>
