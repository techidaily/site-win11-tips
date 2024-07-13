---
title: "Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
date: 2024-07-12T16:50:48.575Z
updated: 2024-07-13T16:50:48.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
excerpt: "This Article Describes Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual"
keywords: Workflow Boost,Notebook Routine,Windows Startup,Productivity Tips,Notepad Integration,Morning Habits,Efficiency Improvement
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual

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
<li><a href="https://win11-tips.techidaily.com/1719327449344-bargain-hunters-rejoice-key-lovers-snag-best-prices-for-lifetime-windows-11/"><u>Bargain Hunters Rejoice: Key Lovers Snag Best Prices for Lifetime Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-altering-lockout-frequency-in-windows-11-successor/"><u>A Step-by-Step Guide to Altering Lockout Frequency in Windows 11 Successor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-digital-imagery-to-your-desktop/"><u>Adding Digital Imagery to Your Desktop</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-premium-chrome-modifiers-for-streamlined-vimeo-content/"><u>[New] 2024 Approved  Premium Chrome Modifiers for Streamlined Vimeo Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-ancient-windows-to-seniors-needs/"><u>Adapting Ancient Windows to Seniors' Needs</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-premier-index-affordable-flexible-image-sources/"><u>[New] In 2024, Premier Index  Affordable, Flexible Image Sources</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-indicators-when-a-pc-needs-a-clean-slate/"><u>7 Indicators: When a PC Needs a Clean Slate</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-through-to-windows-11-security-control-screen/"><u>A Step-by-Step Through to Windows 11 Security Control Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-low-memory-alerts-for-vmware-hosts/"><u>Addressing Low Memory Alerts for VmWare Hosts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-undo-error-x80780119-on-windows-images/"><u>Actions to Undo Error X80780119 on Windows Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-mastering-windows-11s-search-functionality/"><u>A Quick Guide to Mastering Windows 11'S Search Functionality</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/best-live-stream-screen-recorders-for-youtube/"><u>Best Live Stream Screen Recorders for YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-understanding-and-using-components-settings/"><u>A Guide to Understanding and Using Components Settings</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-definitive-10-screenshot-boosters-with-stickers-on-iphones-and-androids/"><u>2024 Approved  The Definitive 10 Screenshot Boosters with Stickers on iPhones & Androids</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-trivia-titans-of-the-year-best-general-knowledge-sites/"><u>[Updated] Trivia Titans of the Year - Best General Knowledge Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-fn-key-operations-in-the-latest-windows-os/"><u>Adapting FN Key Operations in the Latest Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-restart-and-shutdown-disruptions-from-windows-faulty-apps/"><u>Addressing Restart and Shutdown Disruptions From Windows Faulty Apps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-directly-sharing-twitter-videos-onto-your-instagram-account-for-2024/"><u>[New] Directly Sharing Twitter Videos Onto Your Instagram Account for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-step-by-step-guide-to-sims-4-gameplay-recording-for-2024/"><u>[New] Step-by-Step Guide to Sims 4 Gameplay Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719359374237-combat-window-settings-malfunctions-now/"><u>Combat Window Settings Malfunctions Now!</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-ranking-the-best-third-place-recording-tools-for-ipad/"><u>[Updated] In 2024, Ranking the Best Third-Place Recording Tools for iPad</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/determining-vertical-or-horizontal-video-posts-on-fb-for-2024/"><u>Determining Vertical or Horizontal Video Posts on FB for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-cutting-edge-mac-cam-apps-a-look-past-bandicam/"><u>2024 Approved  Cutting-Edge Mac Cam Apps  A Look Past Bandicam</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-this-article-youll-find-four-solutions-for-rotating-your-go-pro-videos-the-following-tools-will-be-used-for-this-purpose-for-2024/"><u>In This Article, Youll Find Four Solutions for Rotating Your Go-Pro Videos. The Following Tools Will Be Used for This Purpose for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-data-safety-with-controlled-folder-access-feature/"><u>Activate Data Safety with Controlled Folder Access Feature</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-expert-analysis-the-leading-mac-screenshots-and-recorders-ranked/"><u>[New] 2024 Approved  Expert Analysis  The Leading Mac Screenshots & Recorders Ranked</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/cut-to-perfection-producing-captivating-loop-content-for-instagram/"><u>Cut to Perfection  Producing Captivating Loop Content for Instagram</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastery-over-multiple-tiktok-video-harvest/"><u>2024 Approved  Mastery Over Multiple TikTok Video Harvest</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-apple-iphone-15-pro-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass Apple iPhone 15 Pro Activation Lock</u></a></li>
<li><a href="https://extra-resources.techidaily.com/endless-buffering-solving-photo-booth-freezes/"><u>Endless Buffering  Solving Photo Booth Freezes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-system-operations-using-windows-task-scheduler/"><u>Accelerate System Operations Using Windows Task Scheduler</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-plus-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Plus Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-slowness-in-windows-discord-interface/"><u>Addressing Slowness in Windows Discord Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compreenas-for-conquering-windows-10-bsod-woes/"><u>A Compreenas for Conquering Windows 10 BSOD Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-install-net-now-demands-from-apps/"><u>Addressing Install .NET Now Demands From Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-techniques-for-temporarily-haltin-windows-11-safety/"><u>5 Alternative Techniques for Temporarily Haltin Windows 11 Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-for-enabling-uninstalled-features-in-win10win11/"><u>7 Strategies for Enabling Uninstalled Features in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-remedies-to-clear-windows-setup-stuck-on-validation-error/"><u>9 Remedies to Clear Windows Setup Stuck on Validation Error</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-lost-files-from-poco-x6-by-fonelab-android-recover-data/"><u>How to retrieve lost files from Poco X6?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-iomap64-bsod-with-easy-steps-for-windows-users/"><u>Addressing IOMap64 BSoD with Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-system-restore-five-tactics/"><u>Activating System Restore: Five Tactics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-an-odyssey-through-time-unexplored-worlds-in-classic-books-for-2024/"><u>[New] An Odyssey Through Time  Unexplored Worlds in Classic Books for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pcs-boot-up-with-these-3-ways-in-windows-11/"><u>Accelerate Your PC's Boot-Up with These 3 Ways in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-getting-jdk-rolled-out-in-windows-11-dev-environment/"><u>A Guide to Getting JDK Rolled Out in Windows 11 Dev Environment</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pro-zoom-functionality-tips-for-chromebook-devices/"><u>In 2024, Pro Zoom Functionality Tips for Chromebook Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-through-gopro-and-time-lapse-synergy/"><u>2024 Approved  Navigating Through GoPro and Time-Lapse Synergy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-way-to-fix-the-virus-and-threat-protection-engine-unavailable-issue-in-windows-defender/"><u>5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender</u></a></li>
</ul></div>
