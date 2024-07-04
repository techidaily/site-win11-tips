---
title: "Mastering Screen Quiet: Disable Win11 Folders"
date: 2024-06-25T16:30:23.261Z
updated: 2024-06-26T16:30:23.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Screen Quiet: Disable Win11 Folders"
excerpt: "This Article Describes Mastering Screen Quiet: Disable Win11 Folders"
keywords: Quiet Windows,Turn Off Noise,Silence PC Sounds,Win11 Volume Control,Reduce System Loudness,Mute Win11 Folders,Disable Audible Alerts
thumbnail: https://thmb.techidaily.com/f5fbbf41453d9824bf6879798120e6de2082db27f668f4cb2a72d45c0fe37f64.jpg
---

## Mastering Screen Quiet: Disable Win11 Folders

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://win11-tips.techidaily.com/clear-windows-11-login-issues-without-screen-display/"><u>Clear Windows 11 Login Issues Without Screen Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-control-over-your-pc-in-winos/"><u>Unlock Full Control Over Your PC in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/purging-steams-domain-name-system-on-windows-systems/"><u>Purging Steam's Domain Name System on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/captivating-concepts-a-guide-to-obsidian-visualization/"><u>Captivating Concepts: A Guide to Obsidian Visualization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chilly-cheer-christmas-presents-with-microsofts-marketplace/"><u>Chilly Cheer: Christmas Presents with Microsoft's Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-silent-camera-activation-in-windows-11/"><u>Bypassing Silent Camera Activation in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-complications-caused-by-latest-windows-updates/"><u>Resolving Complications Caused by Latest Windows Updates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-harmonize-length-and-engagement-in-podcasting/"><u>In 2024, Harmonize Length & Engagement in Podcasting</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-practices-for-zoom-engagement-on-win10-systems/"><u>2024 Approved  Best Practices for Zoom Engagement on Win10 Systems</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-winning-ways-top-8-video-capture-applications-for-windows/"><u>[New] 2024 Approved  Winning Ways  Top 8 Video Capture Applications for Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-inside-the-latest-movavi-editor-plus-unveiling-features-of-2024/"><u>[New] Inside The Latest Movavi Editor Plus  Unveiling Features of 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-of-the-best-ultimate-list-of-gopro-casings-for-2024/"><u>Best of the Best  Ultimate List of GoPro Casings for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-samsung-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Samsung</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-comprehensive-guide-to-screenshot-excellence/"><u>[New] The Comprehensive Guide to Screenshot Excellence</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-record-and-relive-iphoneandroid-google-meet-sessions/"><u>2024 Approved  Record and Relive  IPhone/Android Google Meet Sessions</u></a></li>
</ul></div>
