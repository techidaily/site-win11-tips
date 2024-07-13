---
title: Addressing Deceptive Virus Notifications on Windows Chrome
date: 2024-07-12T17:54:05.573Z
updated: 2024-07-13T17:54:05.573Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/the-leading-25-icons-setting-social-trends-on-insta/"><u>The Leading 25 Icons Setting Social Trends on Insta</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-google-pixel-8-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Google Pixel 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-file-explorer-display-options-windows-11/"><u>How to Control File Explorer Display Options (Windows 11)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-perfect-your-story-a-roundup-of-best-editing-apps/"><u>In 2024, Perfect Your Story  A Roundup of Best Editing Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boost-your-snapshots-proper-use-of-zoom-in-snapchat-for-2024/"><u>Boost Your Snapshots  Proper Use of Zoom in Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-detailed-steps-to-using-azure-speech-recognition-for-2024/"><u>[Updated] Detailed Steps to Using Azure Speech Recognition for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nine-must-have-android-apps-for-windows-users/"><u>Nine Must-Have Android Apps for Windows Users</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-boost-engagement-by-refreshing-your-tiktok-profile/"><u>[New] 2024 Approved  Boost Engagement by Refreshing Your TikTok Profile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prevent-non-scrollability-of-ranges-in-excel-windows/"><u>Prevent Non-Scrollability of Ranges in Excel, Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-ultimate-playlist-to-share-on-fb-stories-for-2024/"><u>[Updated] The Ultimate Playlist to Share on FB Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-steam-cloud-connection-problems/"><u>Correcting Steam Cloud Connection Problems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-fast-track-to-facebooks-latest-viewing-history-2e23/"><u>[Updated] In 2024, Fast Track to Facebook’s Latest Viewing History (2E23)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-approach-to-editing-windows-registry-with-command-prompt/"><u>Stepwise Approach to Editing Windows Registry with Command Prompt</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-internal-windows-error-during-remote-desktop-use/"><u>How to Handle Internal Windows Error During Remote Desktop Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-faded-screen-settings-in-uefi/"><u>Restoring Faded Screen Settings in UEFI</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-your-earning-game-with-youtube-monetization-strategies-for-2024/"><u>Elevating Your Earning Game with YouTube Monetization Strategies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-desktop-icon-update-process-on-windows/"><u>Simplifying Desktop Icon Update Process on Windows</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-motorola-moto-g13-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Motorola Moto G13 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-correct-xbox-mic-issues-in-os/"><u>Guidelines to Correct Xbox Mic Issues in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/severing-the-ties-unlink-onedrive-from-your-msid-on-windows/"><u>Severing the Ties: Unlink OneDrive From Your MSID on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-audio-subtitle-symphony-streamlining-prime-viewing-in-windows-11/"><u>Decoding Audio-Subtitle Symphony: Streamlining Prime Viewing in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-chromes-system-time-a-fix-guide-windows/"><u>Realigning Chrome's System Time: A Fix Guide (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-swiftly-and-permanently-discard-a-partition-on-windows-pc/"><u>How to Swiftly and Permanently Discard a Partition on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reverse-winerror-exit-point-failure/"><u>Steps to Reverse WinError Exit Point Failure</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-boosting-earning-potential-on-youtube-shorts/"><u>[New] In 2024, Boosting Earning Potential on YouTube Shorts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-instructions-for-installing-chrome-on-windows-11/"><u>Stepwise Instructions for Installing Chrome on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-on-windows-11-updates/"><u>Solving Error 0X80246007 on Windows 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/click-without-the-rush-learn-to-deactivate-mouse-acceleration-windows-style/"><u>Click Without the Rush: Learn to Deactivate Mouse Acceleration Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-adjust-windows-activity-lock/"><u>How to Adjust Windows Activity Lock</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-amplify-engagement-broadcasting-from-twitch-to-facebook-for-2024/"><u>[New] Amplify Engagement  Broadcasting From Twitch to Facebook for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-level-windows-photos-shortcut-guide/"><u>Pro-Level Windows Photos Shortcut Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-approach-to-bypassing-no-permission-on-pc/"><u>Step-by-Step Approach to Bypassing 'No Permission' On PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-se-2022-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone SE (2022) Lock Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mobile-filming-tools-for-tourists/"><u>Mobile Filming Tools for Tourists</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-join-the-giggle-roll-and-tearful-talks-on-instagram-memes-for-2024/"><u>[New] Join the Giggle-Roll and Tearful Talks on Instagram Memes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stuck-keys-alert-restoring-order-in-windows/"><u>Stuck Keys Alert: Restoring Order in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-7-plus-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 7 Plus without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-personalized-secure-locks-for-windows-11/"><u>Designing Personalized Secure Locks for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-footage-excellence-with-these-best-apps-for-windows-11/"><u>Enhance Footage Excellence with These Best Apps for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-device-hang-on-windows-11-zerodxgieror/"><u>Overcoming the Device Hang on Windows 11 (ZeroDXGIEror)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rectifying-device-is-unreachable-error-in-windows/"><u>Mastering the Art of Rectifying Device Is Unreachable Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-access-mastering-network-drives-in-win11/"><u>Seamless File Access: Mastering Network Drives in Win11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-the-ultimate-list-of-video-brightness-editors-online-desktop-and-mobile-for-2024/"><u>New The Ultimate List of Video Brightness Editors Online, Desktop, and Mobile for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expert-advice-for-embedding-youtube-playlists-with-ease/"><u>[Updated] Expert Advice for Embedding YouTube Playlists with Ease</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-capture-kings-top-15-windows-tools/"><u>In 2024, Capture Kings  Top 15 Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-installation-and-usage-of-ms-store-themes/"><u>Navigate With Style: Installation and Usage of MS Store Themes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-indoor-android-games-you-can-play-without-a-network/"><u>[Updated] In 2024, Indoor Android Games You Can Play Without a Network</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-error-code-0xc0000001-on-windows-11-or-11/"><u>How to Fix Error Code 0Xc0000001 on Windows 11 or 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-fatal-error-c0000022-in-windows/"><u>How to Fix the Fatal Error C0000022 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-display-at-operating-system-kickoff/"><u>Resolving Non-Display at Operating System Kickoff</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-efficiency-guide/"><u>Mastering Windows 11: Efficiency Guide</u></a></li>
</ul></div>
