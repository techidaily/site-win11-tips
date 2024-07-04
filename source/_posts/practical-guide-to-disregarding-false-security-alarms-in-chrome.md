---
title: Practical Guide to Disregarding False Security Alarms in Chrome
date: 2024-06-25T16:31:18.434Z
updated: 2024-06-26T16:31:18.434Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Practical Guide to Disregarding False Security Alarms in Chrome
excerpt: This Article Describes Practical Guide to Disregarding False Security Alarms in Chrome
keywords: Ignoring False Alarms Guide,Chrome Alarm Avoidance,Misleading Alarms Tips,Secure Chrome No Fake Alerts,Bypassing Real Security Fakes,Unverified Chromium Warnings,Truthful Chrome Guard
thumbnail: https://thmb.techidaily.com/b58731ef522e71a2b18dd9c60ce59d1b021be466af8c6f07f44a82b94265d7d5.jpg
---

## Practical Guide to Disregarding False Security Alarms in Chrome

 Have you encountered an error that reads "failed - virus detected" when downloading specific files through Chrome? It usually occurs when Chrome or Windows Defender detects a virus in a potentially malicious file you're downloading. As a result, it halts the download process and displays this error message to prevent your computer from getting infected.

 Occasionally, Chrome raises false flags even if you're downloading a safe file from a reputable source. What can you do about this situation? What is the best way to verify that the file is safe? If it's safe, how do you bypass this error message? We will cover everything in this article.

## Before We Get Started…

 Before implementing the fixes, ensure Chrome is up-to-date. In some cases, outdated Chrome can cause unforeseen issues. Among them could be halting the download for no apparent reason. Therefore, it's imperative to [update Chrome](https://www.makeuseof.com/how-to-update-chrome-firefox-edge-desktop-mobile/#how-to-update-and-view-the-current-version-of-chrome-on-desktop) to rule out this possibility.

 In addition, try closing the browser and restarting it to see if that resolves the problem. You should also [clear your cache and cookies](https://www.makeuseof.com/how-to-clear-cookies-cache-in-chrome/) to ensure they won't interfere with the download process.

## 1\. Ensure the File You're Downloading Is Safe

 Even when downloading a file from a legitimate source, it's imperative to ensure it is safe to download. Follow the below steps to ensure the file is virus-free:

1. Visit [VirusTotal's official website](https://www.virustotal.com/gui/home/url) .
2. Copy the download link of the file you are having trouble downloading.
3. Paste the downloaded link into the**URL** search bar.  
![pasting the downloaded link of the file into the url search bar on the virustotal official website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pasting-the-downloaded-link-of-the-file-into-the-url-search-bar-on-the-virus-totals-official-website.jpg)
4. Press**Enter** to continue.  
![scan results of a file being downloaded checked on the virus totals official website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/scan-results-of-a-file-being-downloaded-checked-on-the-virus-totals-official-website.jpg)

 After the scan is complete, see if it returns a clean result. If the tool detects some viruses, you'd be better off not downloading the file. If the scan comes back clean but you're still getting the error, it's time to try something else

## 2\. Does the Issue Pertain to a Particular File?

 Check if the error occurs only when downloading a specific file. If so, maybe you need to download it from another source.

 Thus, try downloading the same file from another website, preferably an official one, and see if you are successful. If not, or if you continue to experience errors while downloading multiple files, the problem is more widespread.

 Apply the remaining fixes only if you are absolutely certain that the file you are downloading is safe.

## 3\. Disable Any Security Extensions

 Any security extensions you're using, especially virus scanners, might interfere with the download process and force Chrome to stop it midway. It is, therefore, advisable to disable all security extensions on your browser that you think may hinder the download process. Not sure how to go about it? See [how to disable or remove browser extensions](https://www.makeuseof.com/tag/how-to-clean-up-your-browser-extensions-the-easy-way/) in all browsers.

## 4\. Exclude the Downloads Folder From Windows Defender

 By default, Microsoft Defender scans every folder on your computer. As such, it will prevent your download from completing if it detects a virus. By excluding the destination folder where your file is being downloaded, you may get rid of the error.

 Unless you have changed the download location, follow the below steps to exclude the Downloads folder in Windows Defender:

1. In the Windows Search, search for**"Windows Security"** and open the app.
2. In the left-sidebar, click**Virus & threat protection** .
3. In the right-hand pane, click**Manage settings** .  
![Opening Manage Settings Option under Virus and Threat Protection Settings in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-5-Opening-Manage-Settings-Option-under-Virus-and-Threat-Protection-Settings--in-Windows-Security-App.jpg)
4. Under**Exclusions** , click**Add or remove exclusions** .
5. Click on**Add an exclusion** button and select**Folder** .  
![Adding an Exclusion for Downloads Folder in Windows Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-6-Adding-an-Exclusion-for-Downloads-Folder-in-Windows-Security-Settings.jpg)
6. Browse to the**Downloads** folder or any other location you have set as a download location.

 By following the above steps, you will prevent Windows Defender from scanning the files in the Downloads folder, so if Windows Defender is causing the error even when the file you're downloading is safe, you won't encounter it again.

## 5\. Add the File to Windows Defender's Whitelist

 Microsoft's Windows Defender Firewall is notorious for blocking even completely safe files and processes from downloading or running. Therefore, you may need to allow it in Windows Defender exclusively to download the file. Here's how you can do it:

1. In Windows Search (**Win + S**), search for**"Windows Security"** and open it.
2. In the left-sidebar, click**Virus & threat protection** .
3. In the right-hand pane, click on**Protection history** .  
![Checking Protection History under Virus and Threat Protection in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-7-Checking-Protection-History-under-Virus-and-Threat-Protection-in-Windows-Security-App.jpg)
4. Locate and expand the blocked app or file.
5. Expand the**Actions** dropdown menu and click**Allow** .

 This time, you should not encounter any errors when downloading the file. If the problem persists, tweak Chrome's security settings.

## 6\. Temporarily Disable Microsoft Defender Firewall

 Excluding the Downloads folder and adding the file to Microsoft Defender's whitelist should prevent the Windows built-in security scanner from scanning this file and allow it to download successfully. However, if you still encounter the same error, we suggest temporarily disabling the Microsoft Defender firewall.

 If you have never disabled the firewall before, refer to our guide on [how to disable the Microsoft Defender Firewall in Windows 11](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

 Don't forget to turn on Microsoft Defender after downloading the file, as it's the first line of defense against malware and threats your computer faces.

## 7\. Tweak Chrome's Security Settings

 If Chrome still considers your file a threat, you should disable its Safe Browsing feature in its settings. Here are the steps you need to follow:

1. Click on**three vertical dots** in the top-right corner and go to**Settings** .
2. In the left-sidebar, click**Privacy and security** .
3. In the right-hand pane, click**Security** .  
![Go to Security Settings in Chrome](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/tweaking-chromes-security-settings-by-clicking-on-security-option-under-the-privacy-and-security-tab-in-chrome-settings.jpg)
4. Check the circle for**No Protection (not recommended)** .  
![check the ircle for no protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/checking-the-circle-for-no-protection-not-recommended-option-in-chromes-security-settings.jpg)

 You might be able to download files successfully by disabling Safe Browsing, but once you disable it, Chrome's built-in security won't protect you from malware and malicious downloads. Therefore, after downloading your files, be sure to turn Safe Browsing back on again.

## 8\. Tweak the Windows Registry Editor

 Does Windows Defender still block downloading the completely safe file? If so, let's tweak Registry Editor to force antivirus to stop scanning downloaded attachments. You can do that by following the below steps:

1. In Windows Search, type**"Registry Editor"** and open the program.
2. In path explorer, copy and paste the following path:  
HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\
3. Right-click on the**Policies** key, select**New > Key** and name it**"Attachments."**  
![Tweaking Windows Registry Editor by Renaming Newly Created Registry Key under Policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-11-Tweaking-Windows-Registry-Editor-by-Renaming-Newly-Created-Registry-Key-under-Policies.jpg)
4. Right-click on**Attachments** and navigate to**New > DWORD (32-bit) Value** .  
![Creating the DWORD (32-bit) String Value in the Attachments Key in Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-12-Creating-the-DWORD-(32-bit)-String-Value-in-the-Attachments-Key-in-Registry-Editor-App.jpg)
5. Rename the newly created String Value to**ScanWithAntiVirus** .
6. Double-click on**ScanWIthAntiVirus** and enter**"1"** under**Value data** .  
![Changing the Value Data by Double-clicking on Newly Renamed ScanWIthAntiVirus String Value in Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Image-13-Changing-the-Value-Data-by-Double-clicking-on-Newly-Renamed-ScanWIthAntiVirus-String-Value-in-Registry-Editor-App.jpg)
7. Click**OK** .

 Because tweaking Registry Editor can be tricky and harmful, we recommend you ask an expert to perform this fix if you don't know how to edit Registry Editor manually.

## 9\. Run a Malware Scan

 If you still experience the problem under discussion after applying the fixes listed above, you should ensure your device has not been infected, causing it to behave abnormally. It's possible for malware hidden inside your device to prevent Chrome from downloading files. So, you should make sure that's not the case here.

 Run a malware scan to rule out this possibility. While you can use any third-party antivirus software to scan your device for threats, we recommend [running Microsoft Defender's offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) for complete virus removal.

## Get Rid of the "Failed - Virus Detected" Error in Chrome for Windows

 Our guide should have helped you scan your file and bypass the "Failed - Virus detected" error message if it was a false positive. If none of the fixes have worked for you and the error persists, you'd be better off switching browsers. Among the popular choices, Firefox, Edge, and Opera GX are highly regarded.

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
<li><a href="https://win11-tips.techidaily.com/how-to-set-up-custom-hotkeys-for-pasting-pre-defined-text-snippets-in-windows-10-and-11/"><u>How to Set Up Custom Hotkeys for Pasting Pre-Defined Text Snippets in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-network-nirvana-a-guide-to-the-top-6-ways-to-mend-network-hardware-in-windows/"><u>Reclaim Your Network Nirvana: A Guide to the Top 6 Ways to Mend Network Hardware in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-tour-to-windows-easy-entry-point/"><u>A Step-by-Step Tour to Windows Easy Entry Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-obscured-network-visibility-in-windows/"><u>Curing Obscured Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-updating-windows-in-isolation/"><u>The Art of Updating Windows in Isolation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-error-1152-temporary-file-extract-failure/"><u>Tackling 'Error 1152: Temporary File Extract Failure'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-writability-enabledisable-ntfs-compression/"><u>Unlocking Windows 11' Writability: Enable/Disable NTFS Compression</u></a></li>
<li><a href="https://change-location.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-y78plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-novice-to-pro-16-easy-to-use-free-video-editors-for-all-skill-levels/"><u>Updated From Novice to Pro 16 Easy-to-Use Free Video Editors for All Skill Levels</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-top-9-best-online-video-quality-enhancer-for-free/"><u>Updated In 2024, Top 9 Best Online Video Quality Enhancer for FREE</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-efficient-screenshot-and-video-recorder-choice-guide-for-pc-for-2024/"><u>[New] Efficient Screenshot & Video Recorder Choice Guide for PC for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-elevate-online-engagement-unlocking-the-potential-of-voicemod-on-discord/"><u>[New] In 2024, Elevate Online Engagement  Unlocking the Potential of VoiceMod on Discord</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-unearthing-springs-full-potential-for-desktop-recorders/"><u>[Updated] Unearthing Spring's Full Potential for Desktop Recorders</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/shh-9-secrets-of-simple-stock-editing-for-2024/"><u>Shh! 9 Secrets of Simple Stock Editing for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-premier-font-generators-transforming-discord-channels/"><u>[Updated] Premier Font Generators  Transforming Discord Channels</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-craft-funny-memes-via-adobe/"><u>In 2024, Craft Funny Memes via Adobe</u></a></li>
</ul></div>
