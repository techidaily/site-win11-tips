---
title: How to Master Windows Blue Screen Troubleshooting
date: 2024-07-12T17:26:36.126Z
updated: 2024-07-13T17:26:36.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Master Windows Blue Screen Troubleshooting
excerpt: This Article Describes How to Master Windows Blue Screen Troubleshooting
keywords: BSCT Fix Guide,WinBlueTroubleshoot,BlueScreenRepair,WindowsErrorSolver,ErrorLogWindows,BSOD Solutions,SystemRecoveryWin
thumbnail: https://thmb.techidaily.com/48eff568c35933b40401a65faa40dbe7bb6a58eb499e343dac1cbda32fedf601.jpg
---

## How to Master Windows Blue Screen Troubleshooting

 Windows operating system is far from perfect and encounters errors frequently. While Microsoft releases updates to fix widespread errors, some errors require a different tweaking approach to fix them. However, whenever you see an error code, the first idea is to note it down and search for it online.

 But do you know you can look up error codes in Windows 11? Microsoft offers an error lookup tool using which you can check for any error that pops up on your Windows PC. Without further ado, let's explore this wonderful tool and learn how to check error codes with it.

## What Is the Microsoft Error Lookup Tool?

 Microsoft Error Lookup tool does exactly what it sounds like. You can look up system error codes using this tool to get an idea of what the error code is really about. However, this is a command-line tool, so you need to use Command Prompt to run it. Microsoft is yet to release a GUI version of this tool, which could make searching for error codes for non-tech-savvy users convenient.

 Using a simple command, you can search and learn more about the nature of the error code. Microsoft Error Lookup tool is only available for Windows OS versions 8.1 and above. So, if you are still using Windows 7, searching the web remains your only option.

## How to Download and Run Microsoft Error Lookup Tool

 Microsoft Error Lookup is a lightweight command-line tool. You don’t need a copious amount of system resources to run it on your system. Here’s how to download and set up the tool on your system:

### 1\. Downloading and Renaming the Tool

 Repeat the following steps to download and install the Microsoft Error Lookup tool:

1. Launch a web browser on your system and visit the [Microsoft Error Lookup Tool download page](https://www.microsoft.com/en-us/download/details.aspx?id=100432) .
2. Scroll down and click on the Download button. It will take a few seconds for the download to complete.
3. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the Microsoft Error Lookup Tool executable file download location.
4. Since it is a command-line tool, you will have to run it by typing its full name. The default download name is**Err\_6.4.5** which will be trouble to remember and type correctly every time in the Command Prompt. So, we will rename it to something easier like**Err** .
5. Right-click on the Microsoft Error Lookup tool executable file and select**Show more options** .  
![Renaming Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/renaming-microsoft-error-lookup-tool.jpg)
6. Then, click on the**Rename** option from the context menu. Type**Err** and press the enter key to rename the tool.

### 2\. Placing the Tool in a Convenient Location

 You can only run the Microsoft Error Lookup Tool from the command line. If you place it in a deeply nested path like a folder inside a directory, you will have to navigate to that directory from the command line every time. So, you must move the tool to an accessible location first.

Here’s how to do it:

1. Press**Win + E** to open File Explorer and navigate to the Microsoft Error Lookup Tool download location. Now, press**Ctrl + C** to copy the file.
2. Go to the C drive and paste the tool. Grant permissions to place the tool in C drive.  
![Placing Microsoft Error Lookup Tool in C drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/placing-microsoft-error-lookup-tool-in-c-drive.jpg)
3. Now, press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** in the text box and press enter key.
4. In the Command Prompt window, type the following command and press the enter key:**cd C:\\** .
5. Now, you will be in the parent directory. Type**Err** and press enter.  
![Running Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-microsoft-error-lookup-tool.jpg)
6. Microsoft Error Lookup Tool will run and display the format to look up error codes along with other available parameters. Don’t close the tool yet.

## How to Check Error Codes Using Microsoft Error Lookup Tool

 Now, you have the Microsoft Error Lookup Tool up and running on your system. All you need to do is run appropriate commands to view information about error codes. Here’s how:

1. In the same Command Prompt window, you must type**\[Tool name\] \[error code\]** and press the enter key.
2. Suppose you want to look up the error code 0x80070490 using the tool. So, the correct command will be:**Err 0x80070490** .  
![Checking an Error Code in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-an-error-code-in-microsoft-error-lookup-tool.jpg)
3. Press the enter key and the tool will display all the matching information it has about the error code. It will include the exact error string and a sentence describing the meaning. Often, it will also try to make suggestions to fix the error.

 An error code can have multiple meanings and the error lookup tool will list all of them. You can use this information to narrow down your search and try to fix the issue.

## How to Export the Output of Microsoft Error Code Tool

 The tools can output multiple matches for an error code and that information becomes difficult to scroll in the Command Prompt window. But we can export the results of the error code lookup to a text file on your system.

Repeat the following steps:

1. Press**Win + S** and type CMD. Click on the**Run as administrator** option.
2. Now, type the following command to navigate to the error lookup tool location:**cd C:\\**
3. The syntax for copying the error code lookup results is:**Err \[Error code\] > \[Path of text file\]** .
4. So, your final command will become:**Err 0x80070490 > D:\\error.txt** .  
![Exporting Error Code Lookup results in Microsoft Error Lookup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-microsoft-error-lookup-tool.jpg)
5. It will export the results to the text file named error on D drive. If the file doesn’t exist, the tool will create it with the same name. However, it won’t display any search result in the Command Prompt and just display the number of matches found.  
![Exporting Error Code Lookup results in a text file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/exporting-error-code-lookup-results-in-a-text-file.jpg)

 Now, open the file, and you can read the entire list of error code results and begin troubleshooting.

## Can the Microsoft Error Lookup Tool Display Information About All Error Codes?

 Microsoft updates the tool to the latest version in 2019\. Since then, it hasn’t received an update. So, as newer builds or a [new version of Windows](https://www.makeuseof.com/windows-12-improve-upon-windows-11/) comes out, the tool may fail to produce results for a specific error code. But the chances of that are very slim. Moreover, it contains information only about Windows and some other Microsoft error codes. Don’t expect it to display information about errors you face inside a third-party application or program.

 So, you can use the error lookup tool without any worries and patiently wait for Microsoft to release a new build. You can check for the latest available build by visiting the official download page of the Microsoft Error Lookup Tool. Or, you can try a bunch of third-party options like Winerr or Error Lookup Tool for a more presentable error code lookup and troubleshooting experience.

## Lookup Error Details With Ease

 Microsoft Error Lookup Tool is a free tool that you can easily run on your system. Surely, you won’t get a very descriptive troubleshooting guide with it. But you will still be able to find the issue and error string related to it, and even a suggestion, if the tool has one.


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
<li><a href="https://ai-video-tools.techidaily.com/1714163748501-new-the-ultimate-list-10-vegas-pro-alternatives-for-mac-users-free-and-paid/"><u>New The Ultimate List 10 Vegas Pro Alternatives for Mac Users (Free & Paid)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mobile-app-positions-in-windows-ui/"><u>Mastery Over Mobile App Positions in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-win11-to-new-subnets-easily/"><u>Shifting Win11 to New Subnets Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responsive-spotify-app-on-windows-11-pcs/"><u>Fixing Non-Responsive Spotify App on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-cursor-visibility-on-win-11-a-guide/"><u>Maximizing Cursor Visibility on Win 11: A Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-loading-device-drivers-on-windows-11/"><u>Fixing Non-Loading Device Drivers on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/maximize-profits-the-top-13-no-experience-reddit-hacks/"><u>Maximize Profits  The Top 13 No-Experience Reddit Hacks</u></a></li>
<li><a href="https://fix-guide.techidaily.com/stuck-at-android-system-recovery-of-htc-u23-pro-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of HTC U23 Pro ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-java-vm-not-found-issue-on-windows-devices/"><u>Fixing Java VM Not Found Issue on Windows Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-tiktok-visuals-101-mastering-camera-techniques-and-filmora-styles/"><u>[New] In 2024, TikTok Visuals 101  Mastering Camera Techniques & Filmora Styles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-solidify-the-save-feature-on-nvidias-windows-control-center/"><u>How to Solidify the Save Feature on NVidia's Windows Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-steams-domain-name-system-on-windows-systems/"><u>Purging Steam's Domain Name System on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resume-windows-netflix-playback/"><u>Strategies to Resume Windows Netflix Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-ignoring-license-expires-messages-in-win11/"><u>Quick Tips: Ignoring ‘License Expires’ Messages in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-non-scrolling-issue-in-microsoft-excel-pc/"><u>Resolve Non-Scrolling Issue in Microsoft Excel PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-disconnected-pc-from-wireless-lan/"><u>Steps to Fix Disconnected PC From Wireless LAN</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Realme GT 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-windows-11-default-applications/"><u>Step-by-Step: Changing Windows 11 Default Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-machine-prepared-to-run-newest-windows-os/"><u>Is Your Machine Prepared to Run Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-your-machine-windows-11s-bloatware-hack/"><u>Rejuvenate Your Machine: Windows 11'S Bloatware Hack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-video-drivers-errors/"><u>Mastering the Art of Fixing Video Drivers Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-context-menu-quick-uninstall-in-win-1110/"><u>Mastering Context Menu: Quick Uninstall in Win 11/10</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shift-whats-updated-in-windows-11/"><u>Navigating the Shift: What's Updated in Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-windows-11-licensing-expiration/"><u>Overcoming the Challenges of Windows 11 Licensing Expiration</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-from-tiktok-to-twitter-a-2023-blueprint-for-2024/"><u>[New] From TikTok to Twitter  A 2023 Blueprint for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/creating-chuckles-with-simple-images/"><u>Creating Chuckles with Simple Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deal-with-imminent-license-expiry-on-your-pc/"><u>How to Deal with Imminent License Expiry on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-win-workflow-selecting-the-best-productivity-tools-for-windows-11/"><u>Pro-Win Workflow: Selecting the Best Productivity Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-badge-indicators-on-taskbars/"><u>Restoring Badge Indicators on Taskbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-access-the-fastest-way-to-snipping-tool-win-11/"><u>Instant Access: The Fastest Way to Snipping Tool Win 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-optimal-design-options-for-windows-users-no-cost-or-charged/"><u>[New] Optimal Design Options for Windows Users - No Cost or Charged</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unlock-vertical-video-potential-top-editing-apps-for-mobile-for-2024/"><u>Unlock Vertical Video Potential Top Editing Apps for Mobile for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-outlooks-non-synchronization-in-windows-os/"><u>How to Rectify Outlook's Non-Synchronization in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fixed-bluetooth-pairing-error-in-win-os/"><u>Quick Guide to Fixed: Bluetooth Pairing Error in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-tips-for-leveraging-the-power-of-windows-11-calendar/"><u>Pro Tips for Leveraging the Power of Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-computers-top-8-windows-tricks/"><u>Reinvigorating Computers: Top 8 Windows Tricks</u></a></li>
</ul></div>
