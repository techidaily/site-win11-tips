---
title: "Productivity Hack: Instant Open of Windows' Sticky Notes on Login"
date: 2024-06-25T16:17:52.442Z
updated: 2024-06-26T16:17:52.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Productivity Hack: Instant Open of Windows' Sticky Notes on Login"
excerpt: "This Article Describes Productivity Hack: Instant Open of Windows' Sticky Notes on Login"
keywords: Quick StickyNotes Access,Fast Login Notetips,Instant Note Opener,Login Window Shortcuts,Rapid StickyTip Entry,Windows Login Hack,Efficient Note Startup
thumbnail: https://thmb.techidaily.com/e24c6a589d856da0a108fb73ed8aea987528294a85122e6caa68a425ef40bc26.jpg
---

## Productivity Hack: Instant Open of Windows' Sticky Notes on Login

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
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
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
<li><a href="https://win11-tips.techidaily.com/achieve-smooth-operator-install-in-windows-realm/"><u>Achieve Smooth Operator Install in Windows Realm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-gpu-load-for-smarter-windows-11-wm-efficiency/"><u>Slash GPU Load for Smarter Windows 11 WM Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fortify-windows-11-security-integrating-firewalls-into-the-menubar-ui/"><u>Fortify Windows 11 Security: Integrating Firewalls Into the Menubar UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-with-top-3d-painting-shortcuts/"><u>Streamline Your Workflow with Top 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-tackle-windows-security-faults-effectively/"><u>Steps to Tackle Windows Security Faults Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winrars-hash-harmony-six-ways-to-ensure-correct-sums/"><u>WinRAR's Hash Harmony: Six Ways to Ensure Correct Sums</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-the-dizzy-spins-fixing-your-wheeling-mouse/"><u>Stop the Dizzy Spins: Fixing Your Wheeling Mouse</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-windows-11-photos-incorporating-filters-and-tunes-for-2024/"><u>Mastering Windows 11 Photos  Incorporating Filters & Tunes for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/build-your-wealth-on-youtube-a-guide-to-creating-content-without-ads-for-2024/"><u>Build Your Wealth on YouTube  A Guide to Creating Content Without Ads for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Nokia 105 Classic? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-easily-animate-your-photos-the-9-best-online-tools/"><u>In 2024, Easily Animate Your Photos The 9 Best Online Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-vivo-y17s-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Vivo Y17s to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/the-evolution-of-youtube-shorts-popularity-metrics/"><u>The Evolution of YouTube Shorts Popularity Metrics</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-epicurean-escapades-crafting-kitchen-films/"><u>[Updated] In 2024, Epicurean Escapades  Crafting Kitchen Films</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>