---
title: "Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
date: 2024-09-29T19:47:14.027Z
updated: 2024-10-03T18:58:50.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
excerpt: "This Article Describes Enhancing Protection: Fixing Defender's Unavailable Threat Detection"
keywords: Threat Detection Improvement,Enhanced Security Features,Protecting From Hidden Threats,Upgraded Defense Mechanisms,Boosting Safety Systems,Advanced Threat Identification,Strengthening Cybersecurity
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Enhancing Protection: Fixing Defender's Unavailable Threat Detection

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 However, before we proceed, we recommend[creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

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

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148129/17093" target="_top" id="2148129">
  <img src="//a.impactradius-go.com/display-ad/17093-2148129" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148129/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the[Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the[different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses[how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some[best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

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
<li><a href="https://article-tips.techidaily.com/updated-livestream-launchpad-duel-go-with-xsplit-or-opt-for-obs/"><u>[Updated] Livestream Launchpad Duel Go with XSplit or Opt for OBS?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-jumping-from-sdr-to-hdr-the-ultimate-transformation-guide/"><u>2024 Approved Jumping From SDR to HDR The Ultimate Transformation Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725290604089-mp3ogg4/"><u>最新技術：MP3から高音質OGGへの圧縮無料変換4つの方法</u></a></li>
<li><a href="https://extra-information.techidaily.com/audio-exploration-the-comprehensible-review-of-pazera/"><u>Audio Exploration The Comprehensible Review of Pazera</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-thrifty-windows-mastery-of-keys-and-savings/"><u>Essential Guide to Thrifty Windows: Mastery of Keys and Savings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-sticky-notes-not-syncing-on-windows-11/"><u>How to Fix Your Sticky Notes Not Syncing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-apps-supporting-mac-users-in-their-windows-journey/"><u>Ideal Apps Supporting Mac Users in Their Windows Journey</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-inside-the-box-logitechs-expertly-designed-4k-pro-webcam/"><u>In 2024, Inside the Box Logitech’s Expertly Designed 4K Pro Webcam</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-snapmaster-z7-pro-excellence-in-picture-magnification/"><u>In 2024, SnapMaster Z7 Pro Excellence in Picture Magnification</u></a></li>
<li><a href="https://extra-support.techidaily.com/instant-anonymity-shield-face-details-for-2024/"><u>Instant Anonymity Shield Face Details for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-motorola-g24-power-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Motorola G24 Power? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-skills-faster-with-these-top-8-study-tips-on-a-windowed-pc/"><u>Sharpen Skills Faster with These Top 8 Study Tips on a Windowed PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-to-overcome-windows-11-unresponsive-typing-error-x80049dd3/"><u>Swift Fixes to Overcome Windows 11 Unresponsive Typing Error - X80049DD3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-reset-strategies-unveiling-windows-8-secrets/"><u>System Reset Strategies: Unveiling Windows' 8 Secrets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-art-of-inserting-descriptive-commentary-in-youtube-videos-for-2024/"><u>The Art of Inserting Descriptive Commentary in YouTube Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-timed-lock-screen-issue-in-windows/"><u>Troubleshooting Non-Timed Lock Screen Issue in Windows</u></a></li>
</ul></div>

