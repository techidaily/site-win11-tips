---
title: "Productivity Hack: Instant Open of Windows' Sticky Notes on Login"
date: 2024-07-12T16:43:06.903Z
updated: 2024-07-13T16:43:06.903Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/quick-methods-creating-new-dossiers-in-win11/"><u>Quick Methods: Creating New Dossiers in Win11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-best-5-apple-podcast-services-for-ios-users/"><u>[Updated] 2024 Approved  Best 5 Apple Podcast Services for iOS Users</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-peak-performance-in-live-recording-software/"><u>[Updated] 2024 Approved  Peak Performance in Live Recording Software</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-a-fake-face-online-top-free-tools-and-apps/"><u>New Make a Fake Face Online Top Free Tools and Apps</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-itel-p55-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Itel P55 Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-safety-invest-heavily-in-research-to-develop-advanced-safety-features-that-reduce-potential-risks-associated-with-drone-operations-such-as-collis31/"><u>Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-pushing-boundaries-with-hps-next-gen-4k-display-envy-27/"><u>[New] Pushing Boundaries with HP's Next Gen 4K Display, Envy 27</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-nokia-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Nokia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-screen-space-removing-windows-overscan-effects/"><u>Maximizing Screen Space: Removing Windows Overscan Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-netconfig-a-guide-to-connectivity/"><u>Mastering Window's NetConfig: A Guide to Connectivity</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktok-titans-the-15-who-defy-limits-and-ignite-passion/"><u>TikTok Titans  The 15 Who Defy Limits and Ignite Passion</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-complete-slomo-recording-app-analysis-consumers/"><u>In 2024, Complete SloMo Recording App Analysis Consumers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-these-non-periscope-video-platforms-for-iphones-and-androids/"><u>Explore These  Non-Periscope Video Platforms for iPhones & Androids</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-frames-per-second-for-languid-visuals/"><u>In 2024, Ultimate Frames Per Second for Languid Visuals</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-optimize-tiktok-performance-the-ultimate-toolkit/"><u>[New] 2024 Approved  Optimize TikTok Performance  The Ultimate Toolkit</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-synthetic-cat-chirp-recording/"><u>New In 2024, Synthetic Cat Chirp Recording</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premium-gaming-systems-high-performance-meets-style/"><u>2024 Approved  Premium Gaming Systems  High Performance Meets Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-file-sync-problem-in-windows-environment/"><u>Overcoming Steam File Sync Problem in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-file-failsafe-six-steps-for-correcting-winrar-sums/"><u>Fixing File Failsafe: Six Steps for Correcting WinRAR Sums</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Samsung Galaxy A15 4G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveil-the-ultimate-8-online-places-to-find-free-3d-text-files/"><u>Unveil the Ultimate 8 Online Places to Find FREE 3D Text Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erroneous-wins-protection-messages/"><u>Fixing Erroneous WINS Protection Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-epic-game-launcher-failures-on-windows-os/"><u>Preventing Epic Game Launcher Failures on Windows OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-dissecting-instagrams-per-post-video-quota/"><u>[New] Dissecting Instagram's Per-Post Video Quota</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-windows-users-from-changing-the-date-and-time/"><u>How to Stop Windows Users From Changing the Date and Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-guide-to-easy-use-of-windows-accessibility/"><u>Novices' Guide to Easy Use of Windows Accessibility</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-seamless-entry-into-friends-tiktok-experiences/"><u>[Updated] Seamless Entry Into Friends' TikTok Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-missing-pin-after-win-11-updates/"><u>Guide to Reinstating Missing PIN After Win 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-and-configure-win-11-sandbox/"><u>How to Launch and Configure Win 11 Sandbox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-onedrive-login-failure-x8004dec5-windows-issue/"><u>Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winerror-x8019/"><u>Mitigating WinError: X8019</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-operating-environment-for-device-interfaces/"><u>Optimizing Windows Operating Environment for Device Interfaces</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-motorola-edgeplus-2023-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Motorola Edge+ (2023) Screen | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-default-search-settings/"><u>Optimizing Windows 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-luminance-adjustments-on-your-win11-device/"><u>Leveraging Luminance Adjustments on Your Win11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-obs-studio-not-launching-on-windows/"><u>How to Fix OBS Studio Not Launching on Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quietude-quotient-windowsmac-music-control/"><u>[Updated] Quietude Quotient  Windows/Mac Music Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-windows-11-ms-store-experience/"><u>Reinstating Your Windows 11 MS Store Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-save-photoerror-in-windows-11-os/"><u>How to Correct 'No Save' PhotoError in Windows 11 OS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-visual-wit-iphone-memetic-formats/"><u>[New] In 2024, Visual Wit  IPhone Memetic Formats</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-honor-x9b-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Honor X9b Phone that is Locked?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/capture-and-share-your-games-like-a-pro-with-these-windows-11-tactics-for-2024/"><u>Capture and Share Your Games Like a Pro with These Windows 11 Tactics for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-top-9-fb-scraper-apps-for-films/"><u>[Updated] In 2024, Top 9 FB Scraper Apps for Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notable-nights-of-non-opening-notepad-your-solution-guide-for-windows-users/"><u>Notable Nights of Non-Opening Notepad: Your Solution Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-resolution-glitches/"><u>Overcoming Common Windows Resolution Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-reverse-keyboard-input-on-pcs/"><u>Navigating Reverse Keyboard Input on PCs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-peering-into-popularity-instagram-analytics-for-you/"><u>2024 Approved  Peering Into Popularity  Instagram Analytics for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-access-windows-11-screen-grab-utility/"><u>Mastering Quick Access: Windows 11 Screen Grab Utility</u></a></li>
</ul></div>
