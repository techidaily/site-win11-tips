---
title: Addressing Deceptive Virus Notifications on Windows Chrome
date: 2024-07-03T12:45:52.058Z
updated: 2024-07-04T12:45:52.058Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Deceptive Virus Notifications on Windows Chrome
excerpt: This Article Describes Addressing Deceptive Virus Notifications on Windows Chrome
keywords: WinChromeVirusAlerts,DeceptiveVirusNotify,SafeWindowsChecking,ChromeFraudWarnings,VirusAlertDeception,SecureWinBrowserTips,ChromeFalseAlarmGuide
thumbnail: https://thmb.techidaily.com/13464bbf7702e727674e34228111122f1f619fb5b014ebf3cf5f5ddd4c2dec0d.jpg
---

## Addressing Deceptive Virus Notifications on Windows Chrome

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
<li><a href="https://win11-tips.techidaily.com/quick-boot-options-modifying-windows-11s-startup-delay/"><u>Quick Boot Options: Modifying Windows 11'S Startup Delay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-dark-displays-during-win-games/"><u>Troubleshooting Dark Displays During Win Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-quickly-enable-or-disable-bing-chat-ai-in-windows-11-taskbar-search/"><u>How to Quickly Enable or Disable Bing Chat AI in Windows 11 Taskbar Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-file-management-engage-filters-with-checkbox-on-win11/"><u>Enhance File Management: Engage Filters with Checkbox on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-fixing-windows-error-code-0xc00000f-instantly/"><u>Guidelines to Fixing Windows Error Code 0Xc00000f Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-11-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-halt-automatic-windows-11-reboots/"><u>How to Halt Automatic Windows 11 Reboots</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-nubia-red-magic-8s-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-top-rated-free-online-video-editing-platforms/"><u>2024 Approved Top-Rated Free Online Video Editing Platforms</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-elevate-your-tiktok-experience-instant-download-savvy-for-2024/"><u>[Updated] Elevate Your TikTok Experience  Instant Download Savvy for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-masterclass-in-length-management-youtube-vids/"><u>2024 Approved  Masterclass in Length Management  YouTube Vids</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-solve-audio-absence-in-twitch-style-tweets-for-2024/"><u>[New] Solve Audio Absence in Twitch-Style Tweets for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-the-realm-of-time-lapses-gopro-hero-10-in-action/"><u>In 2024, Navigating the Realm of Time Lapses  GoPro Hero 10 in Action</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unravel-the-complexities-of-setting-up-a-hp-printer-for-novices/"><u>Unravel the Complexities of Setting Up a HP Printer for Novices</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-discover-the-top-8-studio-tools-for-producers-on-mac-and-windows-systems/"><u>2024 Approved Discover the Top 8 Studio Tools for Producers on Mac and Windows Systems</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-stop-motion-made-easy-the-best-online-tools-free-and-paid/"><u>2024 Approved Stop Motion Made Easy The Best Online Tools Free & Paid</u></a></li>
</ul></div>
