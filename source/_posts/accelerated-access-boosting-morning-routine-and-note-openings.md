---
title: "Accelerated Access: Boosting Morning Routine & Note Openings"
date: 2024-07-03T12:42:39.985Z
updated: 2024-07-04T12:42:39.985Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerated Access: Boosting Morning Routine & Note Openings"
excerpt: "This Article Describes Accelerated Access: Boosting Morning Routine & Note Openings"
keywords: Fast Morning Start,Quick Note Opener,Accelerate Mornings,Speedy Notebook,Rapid Access Notes,Hastened Routine,Swift Opening Books
thumbnail: https://thmb.techidaily.com/d8fc0a6dc40b2c266ea46ef0e0946f6a6f2bfc24fdd8c197f755ef2d88428204.jpg
---

## Accelerated Access: Boosting Morning Routine & Note Openings

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
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
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
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373411881-navigate-and-solve-frozen-shift-problems/"><u>Navigate and Solve Frozen Shift Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/download-and-install-windows-11-arm-with-a-focus-on-iso-guide/"><u>Download & Install Windows 11 ARM with a Focus on ISO Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-epic-game-launcher-failures-on-windows-os/"><u>Preventing Epic Game Launcher Failures on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-systems-analyzers-for-windows/"><u>Essential Systems Analyzers for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363317332-troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launch-in-pc-no-fee-clone-of-chatgpt-on-windows/"><u>Launch In-PC, No-Fee Clone of ChatGPT on Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-reference-to-non-existent-token-errors-in-win11/"><u>Correcting “Reference to Non-Existent Token” Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-ensuring-reliable-intel-wireless-networks-in-windows/"><u>Techniques: Ensuring Reliable Intel Wireless Networks in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-from-views-to-sales-the-science-of-successful-tiktok-marketing/"><u>[Updated] 2024 Approved  From Views to Sales  The Science of Successful TikTok Marketing</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-review-of-lazlive-live-selling-platform-with-guide/"><u>2024 Approved Review of LazLive Live Selling Platform With Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-image-editing-on-ios-best-tools-to-erase-objects-from-photos/"><u>[Updated] Innovative Image Editing on iOS  Best Tools to Erase Objects From Photos</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-the-engineers-selection-identifying-the-best-5-dynamic-ducking-software-updates-2-market-trends/"><u>Updated 2024 Approved The Engineers Selection Identifying the Best 5 Dynamic Ducking Software Updates (2 Market Trends)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-vivo-s18-pro-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Vivo S18 Pro</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-unleashing-the-full-potential-of-webcams/"><u>[New] In 2024, Unleashing the Full Potential of Webcams</u></a></li>
<li><a href="https://fox-glue.techidaily.com/visionary-blu-ray-systems-for-unparalleled-3d-immersion-for-2024/"><u>Visionary Blu-Ray Systems for Unparalleled 3D Immersion for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/top-strategies-for-in-depth-nba-game-watching/"><u>Top Strategies for In-Depth NBA Game Watching</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-vivo-s18-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Vivo S18 Phone? Unlock It Now</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/navigating-snapchats-call-feature-in-three-steps/"><u>Navigating Snapchat's Call Feature in Three Steps</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>