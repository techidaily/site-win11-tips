---
title: "Convenient Start: Unveiling Sticky Notes at System Launch"
date: 2024-12-09T16:34:24.446Z
updated: 2024-12-12T16:38:27.391Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Convenient Start: Unveiling Sticky Notes at System Launch"
excerpt: "This Article Describes Convenient Start: Unveiling Sticky Notes at System Launch"
keywords: Convenient Start,Sticky Notes Launch,System Launch Tips,Note-Taking Systems,Product Introduction,Easy Access Tools,Launch Day Essentials
thumbnail: https://thmb.techidaily.com/641461279d3ad9059bf4fdcda2c6b1609c3c8007cc281a812d3b0157adab9f77.jpg
---

## Convenient Start: Unveiling Sticky Notes at System Launch

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-effortless-methods-amp-up-your-yt-video-quality/"><u>[New] 2024 Approved Effortless Methods Amp Up Your YT Video Quality</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-what-lies-beneath-instagram-story-perceptions/"><u>[New] In 2024, What Lies Beneath Instagram Story Perceptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-current-windows-password-error-in-win11win11/"><u>Eliminating Current Windows Password Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-your-workflow-quick-access-in-win-11/"><u>Enhance Your Workflow: Quick Access in Win 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-passwords-savers-for-enhanced-windows-11-defense/"><u>Optimal Passwords Savers for Enhanced Windows 11 Defense</u></a></li>
<li><a href="https://win11-tips.techidaily.com/real-time-internet-insights-for-taskbar-users/"><u>Real-Time Internet Insights for Taskbar Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-communication-in-windows-via-headset-mic/"><u>Restoring Communication in Windows via Headset Mic</u></a></li>
<li><a href="https://extra-support.techidaily.com/selecting-soundtracks-perfecting-trailers-atmosphere-for-2024/"><u>Selecting Soundtracks Perfecting Trailers' Atmosphere for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reinstate-saving-mechanism-in-nvidia-gui/"><u>Steps to Reinstate Saving Mechanism in Nvidia GUI</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-synergy-of-ai-elevating-onlyoffice-docspace-capabilities-with-chatgpt/"><u>The Synergy of AI: Elevating ONLYOFFICE DocSpace Capabilities with ChatGPT</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-capturing-screenshots-on-your-desktop-computer/"><u>Ultimate Guide: Capturing Screenshots on Your Desktop Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mysteries-of-windows-11-faults/"><u>Unraveling the Mysteries of Windows 11 Faults</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-samsung-galaxy-z-fold-5-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Samsung Galaxy Z Fold 5 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win-tricks.techidaily.com/wie-man-geloschte-daten-von-externen-laufwerken-nicht-im-papierkorb-speichert/"><u>Wie Man Gelöschte Daten Von Externen Laufwerken Nicht Im Papierkorb Speichert</u></a></li>
</ul></div>

