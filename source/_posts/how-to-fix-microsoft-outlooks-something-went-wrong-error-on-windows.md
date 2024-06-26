---
title: How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
date: 2024-06-25T16:58:58.528Z
updated: 2024-06-26T16:58:58.528Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-monitor-during-windows-launch/"><u>Fixing Blank Monitor During Windows Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-troubled-waters-in-windows-mail-app-with-0x800713f/"><u>Navigating Through Troubled Waters in Windows Mail App with 0X800713F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-your-preferred-soft-install-tool-on-win-devices/"><u>Finding Your Preferred Soft Install Tool on Win Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-workflow-dealing-with-external-monitor-lag-in-windows/"><u>Improve Your Workflow: Dealing with External Monitor Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-monitoring-integrating-system-resource-data-in-systray/"><u>Streamline Monitoring: Integrating System Resource Data in SysTray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expertise-in-action-how-to-fix-error-code-0x800700e9-on-your-xbox-game-pass-windows-11-device/"><u>Expertise in Action: How to Fix Error Code 0X800700E9 on Your Xbox Game Pass, Windows 11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-black-screen-phenomenon-in-webcams/"><u>Overcoming Black Screen Phenomenon in Webcams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11s-storyteller-a-step-by-step-guide/"><u>Launching Windows 11'S Storyteller: A Step-by-Step Guide</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-fcpx-problem-solving-essentials-top-tips-and-tricks-for-2024/"><u>Updated FCPX Problem-Solving Essentials Top Tips and Tricks for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-digital-dynamo-unleashing-videoviral-impact/"><u>[Updated] 2024 Approved  Digital Dynamo  Unleashing #VideoViral Impact</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pushing-boundaries-in-visual-storytelling-with-hdr/"><u>[Updated] Pushing Boundaries in Visual Storytelling with HDR</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-the-hype-how-to-hike-your-youtube-horde/"><u>[Updated] Harnessing the Hype  How to Hike Your Youtube Horde</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-the-ultimate-guide-to-invisible-lines-in-virtual-meetings-for-2024/"><u>[New] The Ultimate Guide to Invisible Lines in Virtual Meetings for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-elevate-your-presence-setting-up-an-instagram-company/"><u>2024 Approved  Elevate Your Presence  Setting Up an Instagram Company</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-transform-your-tiktok-profile-with-these-cutting-edge-pfps/"><u>[Updated] 2024 Approved  Transform Your TikTok Profile with These Cutting-Edge PFPs</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-tiletime-effortless-video-mosaics-on-both-oses/"><u>[Updated] 2024 Approved  TileTime  Effortless Video Mosaics on Both OSes</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-free-screen-recorder-for-android/"><u>[New] Free Screen Recorder for Android</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-reveal-and-receive-the-most-exciting-sites-for-buying-mystery-boxes/"><u>2024 Approved  Reveal and Receive  The Most Exciting Sites for Buying Mystery Boxes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>