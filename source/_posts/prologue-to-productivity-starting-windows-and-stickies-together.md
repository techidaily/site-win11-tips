---
title: "Prologue to Productivity: Starting Windows & Stickies Together"
date: 2024-10-31T02:02:13.318Z
updated: 2024-11-06T17:44:17.090Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Prologue to Productivity: Starting Windows & Stickies Together"
excerpt: "This Article Describes Prologue to Productivity: Starting Windows & Stickies Together"
keywords: Prologue to WinProductivity,StickyStartingWindows,ProductiveStickiesUse,WinCombinedApps,EfficiencyPrologue,Windows+StickiesBoost,StartWinTogetherEase
thumbnail: https://thmb.techidaily.com/6dfe7c6db7f80e87ac6b399dc687e52e1d331efd7fce0bd5f581a2c33f337372.jpg
---

## Prologue to Productivity: Starting Windows & Stickies Together

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  

C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.

9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/new-speedy-methods-for-shuffling-youtube-lists-on-devices/"><u>[New] Speedy Methods for Shuffling YouTube Lists on Devices</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-seamless-content-transfer-from-youtubers-to-fb-friends/"><u>[Updated] 2024 Approved Seamless Content Transfer From YouTubers to FB Friends</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-auditory-enhancements-for-pixels-and-playlists-for-2024/"><u>[Updated] Auditory Enhancements for Pixels and Playlists for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-windows-index-adjustment/"><u>Command Center: Windows Index Adjustment</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-motorola-moto-g13-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-transfers-python-server-for-windows-networks/"><u>Mastering File Transfers: Python Server for Windows Networks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-task-mastery-top-5-productivity-boosters-for-windows-11/"><u>Maximize Task Mastery: Top 5 Productivity Boosters for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-smoothly-setting-shortcuts-for-microsoft-store-uwp/"><u>Navigate Smoothly: Setting Shortcuts for Microsoft Store UWP</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/official-nvidia-drivers-now-available-geforce-rtx-3070-ti-for-win-1187-safe-to-download/"><u>Official NVIDIA Drivers Now Available: GeForce RTX 3070 Ti for Win 11/8/7 - Safe to Download!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/openai-unveils-revolutionary-gpt-4-ai-changing-the-rules-of-technology/"><u>OpenAI Unveils Revolutionary GPT-4 AI: Changing the Rules of Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opt-out-of-unwanted-windows-system-updates/"><u>Opt Out of Unwanted Windows System Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-740-resolving-elevation-requirements-in-windows-11/"><u>Overcoming Error 740: Resolving Elevation Requirements in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/privacy-policy-just-updated/"><u>Privacy Policy Just Updated</u></a></li>
<li><a href="https://techtrends.techidaily.com/smartwatch-showdown-discover-the-ideal-fit-between-apple-watch-ultra-and-series-8-with-our-expert-analysis/"><u>Smartwatch Showdown: Discover the Ideal Fit Between Apple Watch Ultra & Series 8 with Our Expert Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timestamp-transformation-top-utilities-for-changing-file-times/"><u>Timestamp Transformation: Top Utilities for Changing File Times</u></a></li>
</ul></div>

