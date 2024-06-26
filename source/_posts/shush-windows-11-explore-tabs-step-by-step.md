---
title: "Shush Windows 11 Explore Tabs: Step-by-Step"
date: 2024-06-25T16:20:45.966Z
updated: 2024-06-26T16:20:45.966Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shush Windows 11 Explore Tabs: Step-by-Step"
excerpt: "This Article Describes Shush Windows 11 Explore Tabs: Step-by-Step"
keywords: Shush Windows 11,Tab Exploration Guide,Steps to Open Tabs,Windows 11 Snooze Mode,Using Windows 11 Shortcuts,Optimize Window Tasks,Efficient Tabs Management
thumbnail: https://thmb.techidaily.com/0e72ae7670739d2aa724a5c1676e3ea5eb7af36bcb7980843f57c620d01dbd2b.jpg
---

## Shush Windows 11 Explore Tabs: Step-by-Step

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
<li><a href="https://win11-tips.techidaily.com/vcplusplus-redistribution-purpose-explored/"><u>VC++ Redistribution Purpose Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-subtle-art-of-windows-11s-user-information-extraction/"><u>The Subtle Art of Windows 11'S User Information Extraction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-upgrade-in-a-flash-streamlining-windows-driver-updates/"><u>Audio Upgrade in a Flash: Streamlining Windows Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-stalled-amd-driver-in-windows-environment/"><u>Remedying Stalled AMD Driver in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-defusing-error-0x80070570-saving-your-damaged-files-in-windows-11/"><u>Deciphering and Defusing Error 0X80070570: Saving Your Damaged Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-console-management-with-admin-rights/"><u>Mastering Windows Console Management with Admin Rights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-application-launch-failure-the-0xc000003e-error-on-windows-11/"><u>Solving Application Launch Failure: The 0XC000003E Error on Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-progressive-array-of-chat-initiators-for-attracting-podcast-audience/"><u>[Updated] 2024 Approved  Progressive Array of Chat-Initiators for Attracting Podcast Audience</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unleash-fun-with-the-top-15-online-anime-websites/"><u>2024 Approved  Unleash Fun with the Top 15 Online Anime Websites</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-monitoring-your-instagram-fan-loss-rate/"><u>[New] Monitoring Your Instagram Fan-Loss Rate</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-avidemux-sound-problems-heres-how-to-fix-them-quickly-for-2024/"><u>New Avidemux Sound Problems? Heres How to Fix Them Quickly for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlock-higher-engagement-the-power-of-precise-timestamping/"><u>2024 Approved  Unlock Higher Engagement  The Power of Precise Timestamping</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-12-best-vlogging-cameras-with-a-flip-screen/"><u>[Updated] In 2024, 12 Best Vlogging Cameras with a Flip Screen</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/dual-angles-debate-vertical-vs-horizontal-fb-videos-for-2024/"><u>Dual Angles Debate  Vertical vs Horizontal FB Videos for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-mastering-mov-to-mpeg-4-conversion-on-win-11/"><u>2024 Approved  Mastering MOV to MPEG-4 Conversion on Win 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-infinix-smart-8-plus-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Infinix Smart 8 Plus Mirror Screen to PC? | Dr.fone</u></a></li>
</ul></div>
