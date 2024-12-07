---
title: "Pro Startup Routine: Launching Sticky Notes as First App in Windows"
date: 2024-12-03T21:15:53.207Z
updated: 2024-12-06T23:03:52.838Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Pro Startup Routine: Launching Sticky Notes as First App in Windows"
excerpt: "This Article Describes Pro Startup Routine: Launching Sticky Notes as First App in Windows"
keywords: Startup Habits,NoteTakerApp,WindowsFirstApp,ProductivityBoost,QuickStartWin,IdeaToAppDev,LaunchRoutine
thumbnail: https://thmb.techidaily.com/5fe7ecb89bcc6e1487d4d4a1019dead48cda049eb81dcbc464d7190885cdca32.jpg
---

## Pro Startup Routine: Launching Sticky Notes as First App in Windows

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.

9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-co-production-strategies-for-online-content-proliferation/"><u>[New] 2024 Approved Co-Production Strategies for Online Content Proliferation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-create-a-unique-identity-personalize-your-youtube-url-today-for-2024/"><u>[New] Create a Unique Identity Personalize Your YouTube URL Today for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-essential-guide-fetching-twitter-videos-directly-from-mobile/"><u>[Updated] 2024 Approved Essential Guide Fetching Twitter Videos Directly From Mobile</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-ultimate-guide-to-dimming-down-soundtracks-in-premiere-pro/"><u>2024 Approved The Ultimate Guide to Dimming Down Soundtracks in Premiere Pro</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-kingdom-the-path-to-youtube-mastery-for-2024/"><u>Crafting Kingdom The Path to YouTube Mastery for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-applying-dark-theme-to-notepad-windows-11/"><u>Effortless Guide: Applying Dark Theme to Notepad (Windows 11)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-ai-accuracy-six-innovative-approaches-to-reduce-hallucination-in-machine-learning-responses/"><u>Enhancing AI Accuracy: Six Innovative Approaches to Reduce Hallucination in Machine Learning Responses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-load-steamuidll-error-in-steam-for-windows/"><u>How to Fix the “Failed to Load steamui.dll” Error in Steam for Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-sharefake-location-on-whatsapp-for-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Xiaomi Redmi A2+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-steam-error-offline-content-not-available-windows-wise/"><u>Navigating Steam Error: Offline Content Not Available Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-boot-menu-pause-boost-startup-with-windows-11-tweaks/"><u>Revising Boot Menu Pause: Boost Startup with Windows 11 Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-paradigm-quality-over-fun-in-windows-11/"><u>Shifting Paradigm: Quality over Fun in Windows 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/y-transformation-from-pixels-to-polished-youtube-thumbnails-for-2024/"><u>Speedy Transformation From Pixels to Polished YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-connected-eliminating-power-save-for-usbs-in-windows-11/"><u>Stay Connected - Eliminating Power Save for USBs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-error-when-transferring-iphones-pics/"><u>Steps to Solve Error When Transferring iPhones' Pics</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-guide-fixing-non-functional-beyond-the-wire-mics/"><u>Ultimate Guide: Fixing Non-Functional 'Beyond The Wire' Mics</u></a></li>
</ul></div>

