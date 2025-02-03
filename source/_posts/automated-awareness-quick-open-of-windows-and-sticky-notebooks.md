---
title: "Automated Awareness: Quick Open of Windows and Sticky Notebooks"
date: 2025-01-27T03:27:58.565Z
updated: 2025-01-31T16:50:36.248Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Automated Awareness: Quick Open of Windows and Sticky Notebooks"
excerpt: "This Article Describes Automated Awareness: Quick Open of Windows and Sticky Notebooks"
keywords: Quick Window Access,Automatic Notification,Fast Opens Systems,Rapid Window Closure,Enhanced Sticky Notes,Immediate System Response,Faster Notebook Opening
thumbnail: https://thmb.techidaily.com/95c7607cc85834758f594e36f86b8274633568f32ba37267dd79e6e802f121e2.png
---

## Automated Awareness: Quick Open of Windows and Sticky Notebooks

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9wiIVztRIqQ?si=GBgdwQ78k5hbeFDv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-elevate-everyday-narratives-gratuitous-facebook-enhancers/"><u>[New] 2024 Approved Elevate Everyday Narratives Gratuitous Facebook Enhancers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-depth-analysis-of-fb-chat-recording-techniques-for-2024/"><u>[New] In-Depth Analysis of FB Chat Recording Techniques for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevate-your-channel-game-tubebuddy-insights/"><u>[Updated] In 2024, Elevate Your Channel Game - TubeBuddy Insights</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-streamline-content-sharing-a-complete-instagram-video-upload-guide-from-desktop/"><u>[Updated] In 2024, Streamline Content Sharing A Complete Instagram Video Upload Guide From Desktop</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-step-by-step-guide-to-revamping-youtube-inspired-thumbnails-on-twitter-for-2024/"><u>[Updated] Step-by-Step Guide to Revamping YouTube-Inspired Thumbnails on Twitter for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-the-next-gen-discover-8-leading-tablets-pushing-beyond-filmoras-limits/"><u>[Updated] The Next Gen Discover 8 Leading Tablets Pushing Beyond Filmora's Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-microsofts-smartscreen-feature/"><u>Configuring Microsoft's SmartScreen Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-inactive-windows-media-player-sounds/"><u>Dealing with Inactive Windows Media Player Sounds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-problem-of-unreachable-nvidia-cp/"><u>How to Fix the Problem of Unreachable Nvidia CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-day-in-windows-the-top-5-must-use-productivity-tools/"><u>Master Your Day in Windows: The Top 5 Must-Use Productivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-your-fileshare-needs-the-best-tools-for-winpc-users/"><u>Navigating Your Fileshare Needs: The Best Tools for WinPC Users</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-s-best-time-lapse-video-editing-tools-a-comprehensive-review/"><u>New 2024 Approved S Best Time-Lapse Video Editing Tools A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-non-opens-winxps-folder-dilemma-on-double-click/"><u>Overcoming Non-Opens: WinXP's Folder Dilemma on Double-Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-tech-setup-downloading-and-deploying-msix-extensions/"><u>Streamline Your Tech Setup: Downloading & Deploying MSIX Extensions</u></a></li>
<li><a href="https://fox-search.techidaily.com/what-does-it-mean-when-your-laptop-whirs-and-clicks-insights-by-yl-tech-experts/"><u>What Does It Mean When Your Laptop Whirs and Clicks? Insights by YL Tech Experts</u></a></li>
</ul></div>

