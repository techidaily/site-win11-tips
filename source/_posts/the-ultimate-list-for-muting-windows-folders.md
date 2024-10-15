---
title: The Ultimate List for Muting Windows Folders
date: 2024-10-09T04:29:31.030Z
updated: 2024-10-14T16:56:35.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate List for Muting Windows Folders
excerpt: This Article Describes The Ultimate List for Muting Windows Folders
keywords: Mute Windows Folder Alerts,Silence Folder Sounds,Stop Folder Notifications,Quiet Windows Audio Clips,Dial Down Folder Noise,Hush File System Chimes,Mute Windows Sound Files
thumbnail: https://thmb.techidaily.com/1003c2d436af1af88200a4fecafa1c9b55219d7d2c61adc69cde92d0a51179ae.jpg
---

## The Ultimate List for Muting Windows Folders

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461">
  <img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/new-gamers-pathway-to-impeccable-recordings-for-2024/"><u>[New] Gamers' Pathway to Impeccable Recordings for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-transforming-drones-into-cinematic-experiences-with-editing/"><u>[New] In 2024, Transforming Drones Into Cinematic Experiences with Editing</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-unlock-your-content-potential-with-youtubes-movie-maker/"><u>[Updated] In 2024, Unlock Your Content Potential with YouTube's Movie Maker</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-elevating-your-google-meet-engagement-screen-sharing-tips/"><u>2024 Approved Elevating Your Google Meet Engagement Screen Sharing Tips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-harmonic-headstarts-curated-spots-with-the-best-music-picks/"><u>2024 Approved Harmonic Headstarts Curated Spots with the Best Music Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-ai-imagery-via-paint-cocreator-on-win11/"><u>Creating AI Imagery via Paint Cocreator on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-resolving-updater-error-0x80246007-on-w10w11/"><u>Deciphering and Resolving Updater Error 0X80246007 on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-recovery-guide-overcoming-pink-or-purple-windows-glitch/"><u>Desktop Recovery Guide: Overcoming Pink or Purple Windows Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hiding-your-drive-in-the-windows-1110-shadows/"><u>Hiding Your Drive in the Windows 11/10 Shadows</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oppo-find-x6-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Oppo Find X6 phone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-color-adjustment-for-win11-applications/"><u>Mastering Auto-Color Adjustment for Win11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-correctly-interpret-task-managers-cpu-numbers/"><u>Methods to Correctly Interpret Task Manager's CPU Numbers</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-video-file-types-optimized-for-iphones-and-android-devices-by-industry-experts/"><u>Top Video File Types Optimized for iPhones and Android Devices by Industry Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-business-communication-with-intel-unison-in-windows-11/"><u>Transforming Business Communication with Intel Unison in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-creative-shots-with-photoshops-radial-distortion-for-2024/"><u>Unlock Creative Shots with Photoshop's Radial Distortion for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unveiling-googles-latest-creation-an-intimate-look-at-bard-the-cutting-edge-ai-chatbot/"><u>Unveiling Google's Latest Creation: An Intimate Look at Bard, The Cutting-Edge AI Chatbot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-exploration-making-and-investigating-system-reports/"><u>Windows Exploration: Making & Investigating System Reports</u></a></li>
</ul></div>

