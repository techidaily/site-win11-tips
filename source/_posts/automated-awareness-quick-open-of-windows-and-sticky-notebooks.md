---
title: "Automated Awareness: Quick Open of Windows and Sticky Notebooks"
date: 2024-07-12T17:59:56.797Z
updated: 2024-07-13T17:59:56.798Z
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
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unlock-your-youtube-potential-by-dodging-these-8-typical-mistakes/"><u>2024 Approved  Unlock Your YouTube Potential by Dodging These 8 Typical Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-changing-windows-date-and-time-accurately/"><u>Avoid Changing Windows Date & Time Accurately</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ing-stellar-video-beginnings-with-free-tools-for-2024/"><u>Crafting Stellar Video Beginnings with Free Tools for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-could-not-create-window-mmc-snapshot-issues/"><u>Avoiding 'Could Not Create' Window MMC Snapshot Issues</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-ios-the-ultimate-list-of-ps2-emulators/"><u>[New] IOS  The Ultimate List of PS2 Emulators</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/craft-standout-videos-with-professional-free-banner-samples/"><u>Craft Standout Videos with Professional, Free Banner Samples</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-unbrand-your-videos-remove-filmora-watermark-for-freepaid/"><u>New In 2024, Unbrand Your Videos Remove Filmora Watermark for Free/Paid</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-sync-and-conquer-to-dot-and-ifttt/"><u>Automate, Sync, and Conquer: To-Dot & IFTTT</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-10-must-watch-historical-channels-for-students/"><u>In 2024, 10 Must-Watch Historical Channels for Students</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-task-management-adding-cli-toolbar-in-win11-taskmgr/"><u>Advanced Task Management: Adding CLI Toolbar in Win11 TaskMgr</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-10-video-editing-apps-for-android-devices/"><u>New 2024 Approved Top 10 Video Editing Apps for Android Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-virtualization-turning-on-hyper-v-for-win-11/"><u>Boosting Virtualization: Turning On Hyper-V for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-space-allocation-in-windows-applications/"><u>Assessing Space Allocation in Windows Applications</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/how-to-remove-vocals-from-video-quick-and-easy-sound-improvement-for-2024/"><u>How To Remove Vocals From Video Quick And Easy Sound Improvement for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/archive-your-art-innovative-cost-effective-photo-storage-platforms/"><u>Archive Your Art  Innovative, Cost-Effective Photo Storage Platforms</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-19-secrets-to-free-capture-of-virtual-learning-sessions/"><u>[New] In 2024, 19 Secrets to FREE Capture of Virtual Learning Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-unexpected-shutdowns-in-windows-11-pro/"><u>Avoid Unexpected Shutdowns in Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-errors-secure-your-onedrive-login-on-windows/"><u>Avoiding Errors: Secure Your OneDrive Login on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-sensitivity-on-modern-windows-devices/"><u>Balancing Sensitivity on Modern Windows Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-maximizing-impact-strategies-for-going-viral-on-instagram/"><u>[New] Maximizing Impact  Strategies for Going Viral on Instagram</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-realme-c67-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Realme C67 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-unintended-read-only-file-states-in-windows-11/"><u>Avoiding Unintended Read-Only File States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/asus-zenbook-14-oled-ux3405-review-is-this-the-macbook-of-windows/"><u>ASUS Zenbook 14 OLED (UX3405) Review: Is This the MacBook of Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-cameras-failed-recordings/"><u>Addressing Windows Camera's Failed Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-system-mastering-windows-11-efficiency/"><u>Boost Your System: Mastering Windows 11 Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-windows-utilities-aiding-the-seamless-shift-from-apples-macos/"><u>Best Windows Utilities: Aiding the Seamless Shift From Apple's MACOS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-mastering-multi-platform-skype-group-formation/"><u>[Updated] 2024 Approved  Mastering Multi-Platform Skype Group Formation</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfersync-notes-from-apple-iphone-14-pro-max-to-ipad-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer/Sync Notes from Apple iPhone 14 Pro Max to iPad | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-android-app-integration-on-windows-11-systems/"><u>Best Android App Integration on Windows 11 Systems</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-comprehensive-guide-to-attaching-audios-in-magix-movie-editor-2023/"><u>2024 Approved Comprehensive Guide to Attaching Audios in Magix Movie Editor 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-shutdown-time-when-applications-are-running/"><u>Altering Windows 11 Shutdown Time when Applications Are Running</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-in-depth-look-at-windows-cab-and-its-functionality/"><u>An In-Depth Look at Windows CAB and Its Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blocking-windows-update-messages/"><u>Blocking Windows Update Messages</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-crop-companion-chronicles-ultimate-agrigames-to-bond-with-buddies/"><u>In 2024, Crop Companion Chronicles  Ultimate AgriGames to Bond with Buddies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bluescreenview-unpacked-practical-applications/"><u>BlueScreenView Unpacked: Practical Applications</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-motorola-moto-g84-5g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Motorola Moto G84 5G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2-methods-to-crop-a-video-using-after-effects/"><u>2 Methods to Crop a Video Using After Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-computer-speakers-not-working-how-to-fix-having-no-sound/"><u>Are Your Computer Speakers Not Working? How to Fix Having No Sound</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-samsung-galaxy-m14-5g-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Samsung Galaxy M14 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blackview-minipc-extended-storage-mediocre-execution/"><u>Blackview MiniPC: Extended Storage, Mediocre Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-fun-integrating-games-into-windows-11-through-google-play/"><u>Android Fun: Integrating Games Into Windows 11 Through Google Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-synergy-with-windows-os-paving-a-futuristic-path/"><u>AI Synergy with Windows OS: Paving a Futuristic Path</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-addressing-the-myself-glitch-on-social-media-platforms/"><u>[Updated] In 2024, Addressing the 'Myself' Glitch on Social Media Platforms</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-many-attempts-to-unlock-iphone-xs-max-by-drfone-ios/"><u>In 2024, How Many Attempts To Unlock iPhone XS Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-breaking-disconnections-fall-guys-windows-fixes/"><u>Avoid Game-Breaking Disconnections: Fall Guys Windows Fixes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-unlock-potential-best-practices-for-logitech-webcam-use/"><u>2024 Approved  Unlock Potential  Best Practices for Logitech Webcam Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-the-abrupt-termination-of-wow-error-132-on-win11/"><u>Banishing The Abrupt Termination of WoW (Error 132) on Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>