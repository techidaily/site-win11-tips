---
title: How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
date: 2024-07-12T17:30:40.625Z
updated: 2024-07-13T17:30:40.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
excerpt: This Article Describes How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
keywords: Fix Outlook Error Windows,Resolve Outlook Error,Outlook Crash Fix,MSOffice Glitch Solve,Microsoft Office Error,Windows Mail Issue,Outlook Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/27b127c31cd1d4c4e3c7e2e3da33ec44af88b4b625ba034a78a3512eb4d83268.jpg
---

## How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-videos.techidaily.com/elevate-video-clarity-with-expert-tips-for-youtube-editors/"><u>Elevate Video Clarity with Expert Tips for YouTube Editors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-10-camera-lenses-to-use/"><u>[Updated] Best 10 Camera Lenses to Use</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/converting-your-cellphone-to-a-diy-video-recorder-for-2024/"><u>Converting Your Cellphone to a DIY Video Recorder for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-teamwork-made-simple-the-ultimate-guide-to-8-schedulers/"><u>[Updated] In 2024, Teamwork Made Simple  The Ultimate Guide to 8 Schedulers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359918304-error-handling-strategies/"><u>Error Handling Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-windows-update-error-0x800f080a/"><u>6 Ways to Fix the Windows Update Error 0X800f080a</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719314760975-home-run-your-gptclone-on-windows-free-and-easy-with-gpt4all/"><u>Home-Run Your GPTClone on Windows – Free & Easy with GPT4All</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-and-resolving-msvcr110dll-lack/"><u>Addressing and Resolving MSVCR110.dll Lack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-things-you-should-avoid-doing-on-windows-11/"><u>8 Things You Should Avoid Doing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-improve-your-gaming-experience-on-a-windows-11-pc/"><u>7 Ways to Improve Your Gaming Experience on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-anywhere-unveiling-gaming-data-in-windows/"><u>Access Anywhere: Unveiling Gaming Data in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-global-scripts-windows-font-acquisition-guide/"><u>Accessing Global Scripts: Windows Font Acquisition Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-xiaomi-redmi-12-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/access-denied-reconnecting-to-windows-shared-items/"><u>Access Denied: Reconnecting to Windows Shared Items</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-breaking-down-mp4s-removing-sound-tracks-and-silence/"><u>2024 Approved Breaking Down MP4s Removing Sound Tracks and Silence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719292218138-quicker-downloads-for-battlenet-games-win-pcs-now/"><u>Quicker Downloads for Battle.net Games, Win PCs Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-access-the-startup-folder-in-windows/"><u>5 Ways to Access the Startup Folder in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-enabling-imessage-on-non-ios-devices/"><u>A Deep Dive Into Enabling iMessage on Non-iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-using-dism-on-win11-systems/"><u>A Comprehensive Guide to Using Dism on Win11 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/securing-your-online-presence-off-facebook-activities-exposed/"><u>Securing Your Online Presence  Off-Facebook Activities Exposed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reimagining-editing-processes-the-revolutionary-world-of-magix-video-pro-x/"><u>2024 Approved  Reimagining Editing Processes  The Revolutionary World of Magix Video Pro X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-your-way-through-windows-with-mouseclicklock-techniques/"><u>Ace Your Way Through Windows with MouseClickLock Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719382715644-unlock-potential-of-windows-without-using-the-compatibility-tool/"><u>Unlock Potential of Windows without Using the Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719294305886-ignite-performance-gains-in-winoutlook-today/"><u>Ignite Performance Gains in WinOutlook, Today</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-smart-approach-for-posting-igtv-on-your-story-for-2024/"><u>[New] The Smart Approach for Posting IGTV on Your Story for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-youtube-view-bots-how-to-increase-youtube-views/"><u>[New] 2024 Approved  YouTube View Bots  How to Increase YouTube Views?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-archiving-feature/"><u>Activating Windows 11'S Archiving Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-clickable-items-in-the-latest-os-update/"><u>Addressing Non-Clickable Items in the Latest OS Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-academic-excellence-winning-strategies-for-efficient-windows-learning/"><u>Achieve Academic Excellence: Winning Strategies for Efficient Windows Learning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-winning-strategy-for-moving-software-into-the-future-of-windows-11/"><u>A Winning Strategy for Moving Software Into the Future of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-windows-11-collects-your-data/"><u>5 Ways Windows 11 Collects Your Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-ways-to-fix-there-are-no-startup-items-to-display-in-the-task-manager-error-on-windows/"><u>8 Ways to Fix There Are No Startup Items to Display in the Task Manager Error on Windows</u></a></li>
</ul></div>
