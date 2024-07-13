---
title: Stifling Windows Restart Requests
date: 2024-07-12T16:41:09.880Z
updated: 2024-07-13T16:41:09.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stifling Windows Restart Requests
excerpt: This Article Describes Stifling Windows Restart Requests
keywords: Windows Restart Blockage,Stop Restart Requests,Prevent Reboot Issues,Disable Windows Refresh,Stifle System Restart,Cease Reboot Prompts,Halt Windows Restarts
thumbnail: https://thmb.techidaily.com/b46b34fd5ad4244a5b3542fda6e0ba281358e5c36628241992e02c966a06886d.jpg
---

## Stifling Windows Restart Requests

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-practical-approach-to-mastering-windows-law-filters/"><u>A Practical Approach to Mastering Windows LAW Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-load-in-win11/"><u>Accelerate System Load in Win11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-unleash-your-inner-star-the-best-of-viral-tiktok-challenges-top-10/"><u>[Updated] In 2024, Unleash Your Inner Star  The Best of Viral TikTok Challenges (Top 10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-misaligned-windows-thx-listening-experience/"><u>Addressing Misaligned Windows THX Listening Experience</u></a></li>
<li><a href="https://extra-tips.techidaily.com/audiophiles-guide-to-immersive-tales/"><u>Audiophile's Guide to Immersive Tales</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-ram-problems-in-windows-systems-using-vmware/"><u>Addressing RAM Problems in Windows Systems Using VMware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719300675775-localize-chatgpt-on-pc-free-and-simple-with-gpt4all/"><u>Localize ChatGPT on PC - Free & Simple With GPT4All</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advanced-editing-for-professional-photographers-time-stamping-tactics/"><u>[Updated] Advanced Editing for Professional Photographers  Time-Stamping Tactics</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-hottest-10-tiktok-filter-trends-to-captivate-viewers-for-2024/"><u>[New] Hottest 10 TikTok Filter Trends to Captivate Viewers for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-refine-image-size-and-shape/"><u>New Refine Image Size and Shape</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-nubia-z50s-promirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Nubia Z50S ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-practical-guide-to-recognizing-and-addressing-uninstalled-disk-issue-win-11-style/"><u>A Practical Guide to Recognizing & Addressing 'Uninstalled Disk' Issue, Win 11 Style</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rethinking-top-movies-7-swap-selections/"><u>In 2024, Rethinking Top Movies - #7 Swap Selections</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cross-cultural-loanwords-in-contemporary-english/"><u>Cross-Cultural Loanwords in Contemporary English</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-organizing-your-w11-space/"><u>A Step by Step Approach to Organizing Your W11 Space</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-mastering-personal-branding-on-tiktok-a-detailed-guide/"><u>[Updated] In 2024, Mastering Personal Branding on TikTok  A Detailed Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disappearing-badge-icons/"><u>Addressing Disappearing Badge Icons</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-plan-for-installing-win11-version-22h2-updater/"><u>A Step-by-Step Plan for Installing WIN11 Version 22H2 Updater</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-stepwise-guide-to-uploading-and-livestreaming-video-recordings/"><u>In 2024, Stepwise Guide to Uploading and Livestreaming Video Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-spooler-service-error-on-windows-systems/"><u>Addressing Spooler Service Error on Windows Systems</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-issue-of-battlenet-not-opening-windows/"><u>Addressing the Issue of Battle.net Not Opening Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-side-by-side-setup-on-windows-os/"><u>Addressing 'Incorrect Side-by-Side Setup' On Windows OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-repeated-text-animation-tutorial/"><u>New Repeated Text Animation Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-another-app-uses-same-speaker-windows-edition/"><u>Addressing Error: Another App Uses Same Speaker, Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simplified-approach-to-windows-odbc-data-management/"><u>A Simplified Approach to Windows ODBC Data Management</u></a></li>
<li><a href="https://extra-tips.techidaily.com/aural-aesthetics-in-whatsapp-statues/"><u>Aural Aesthetics in WhatsApp Statues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-unified-sticky-note-syncing-on-win11/"><u>Addressing Non-Unified Sticky Note Syncing on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operational-windows-keyboard-entry/"><u>Addressing Non-Operational Windows Keyboard Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380036891-dual-virus-defense-think-again-windows-users/"><u>Dual Virus Defense? Think Again, Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/news-narratives-concluding-flourishes-for-2024/"><u>News Narratives' Concluding Flourishes for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-why-professionals-choose-final-cut-pro-over-express/"><u>Updated Why Professionals Choose Final Cut Pro Over Express</u></a></li>
</ul></div>
