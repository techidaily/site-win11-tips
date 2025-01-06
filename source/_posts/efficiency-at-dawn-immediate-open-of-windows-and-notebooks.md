---
title: "Efficiency at Dawn: Immediate Open of Windows and Notebooks"
date: 2025-01-01T22:16:14.022Z
updated: 2025-01-05T23:08:59.850Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficiency at Dawn: Immediate Open of Windows and Notebooks"
excerpt: "This Article Describes Efficiency at Dawn: Immediate Open of Windows and Notebooks"
keywords: Dawn Efficiency,Window Early Opener,Notebook On-Time,Quick Start Laptops,Rise with Devices,Fast Unlock Windows,Immediate PC Access
thumbnail: https://thmb.techidaily.com/102ab1b6aae4e1817df5a3836c10cfedb2eea5b3cb906b121a8d1c61752ad28b.jpg
---

## Efficiency at Dawn: Immediate Open of Windows and Notebooks

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-in-2024-sharing-tunes-instagram-copyright-edicts/"><u>[New] In 2024, Sharing Tunes Instagram Copyright Edicts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-lead-the-way-in-igtv-videos-with-best-ever-edits-for-2024/"><u>[Updated] Lead the Way in IGTV Videos with Best-Ever Edits for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-how-to-capture-and-share-your-games-online/"><u>2024 Approved How to Capture and Share Your Games Online</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-streamlined-iphone-snapchat-linkage-for-photographs-and-memories/"><u>2024 Approved Streamlined iPhone-Snapchat Linkage for Photographs & Memories</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-win11s-registry-editor-with-ease/"><u>Configure Win11's Registry Editor with Ease</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-realme-narzo-n55-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Realme Narzo N55 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-infinix-smart-7-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Infinix Smart 7 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-masterful-windows-melodies/"><u>In 2024, Masterful Windows Melodies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-high-contrast-brightness-in-windows/"><u>Lowering High Contrast Brightness in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-videos-from-vivo-v27-pro-by-fonelab-android-recover-video/"><u>Possible solutions to restore deleted videos from Vivo V27 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-code-0x80071a90-a-quick-guide/"><u>Resolving Windows Error Code: 0X80071a90 - A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-git-management-with-github-desktop-for-windows-os/"><u>Seamless Git Management with GitHub Desktop for Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-desktop-with-window-notifications/"><u>Streamlining Your Desktop With Window Notifications</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-offline-speech-to-text-transcription-apps/"><u>Top Offline Speech-to-Text Transcription Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-overcoming-server-notifications-on-apex-legends-(156-chars/"><u>Top Strategies: Overcoming Server Notifications on Apex Legends (<156 Chars)</u></a></li>
</ul></div>

