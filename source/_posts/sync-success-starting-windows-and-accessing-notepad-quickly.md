---
title: "Sync Success: Starting Windows and Accessing Notepad Quickly"
date: 2024-08-16T01:49:14.469Z
updated: 2024-08-17T01:49:14.469Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sync Success: Starting Windows and Accessing Notepad Quickly"
excerpt: "This Article Describes Sync Success: Starting Windows and Accessing Notepad Quickly"
keywords: Start Windows Fast,Access Notepad Quick,Sync Devices Easy,Quick Device Connect,Speed Up System Start,Faster App Launch,Simplify Windows Use
thumbnail: https://thmb.techidaily.com/5f1d20c9cdc38cb1d77f47c43dee5a5d477e2ff178ada3de9653ceb21ae65a7a.jpg
---

## Sync Success: Starting Windows and Accessing Notepad Quickly

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-unbeatable-mobilized-game-slowdowns/"><u>[New] In 2024, Unbeatable Mobilized Game Slowdowns</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-unlocking-the-secrets-to-successful-360-streaming-on-fb/"><u>[New] In 2024, Unlocking the Secrets to Successful 360 Streaming on FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-journey-through-ingenious-animated-texts-top-14-snapshots/"><u>[New] Journey Through Ingenious Animated Texts  Top 14 Snapshots</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-delete-or-deactivate-an-instagram-account-permanently/"><u>[Updated] 2024 Approved  How to Delete or Deactivate An Instagram Account Permanently</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-exploring-social-networking-youtube-content-on-fb/"><u>[Updated] In 2024, Exploring Social Networking  YouTube Content on FB</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-to-use-itop-recorder-a-compelling-case/"><u>[Updated] In 2024, To Use ITop Recorder  A Compelling Case?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-master-iphone-screen-recording-in-minutes-for-2024/"><u>[Updated] Master iPhone Screen Recording in Minutes for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-essential-handbook-to-planning-zoom-sessions/"><u>[Updated] The Essential Handbook to Planning Zoom Sessions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-podcasts-on-google-podcasts/"><u>2024 Approved  Best Podcasts on Google Podcasts</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-five-to-fiveteen-tactics-against-oculus-discomfort/"><u>2024 Approved  Five to Fiveteen  Tactics Against Oculus Discomfort</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-small-channels-big-opportunities-an-affiliate-approach/"><u>2024 Approved  Small Channels, Big Opportunities  An Affiliate Approach</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-output-quality-large-scale-creation-via-canva-plus-chatgpt/"><u>Boosting Output Quality: Large-Scale Creation via Canva + ChatGPT</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-tecno-spark-10-4g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Tecno Spark 10 4G is off? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/harnessing-ai-for-dream-job-pursuit/"><u>Harnessing AI for Dream Job Pursuit</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-y78plus-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo Y78+</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Poco C55? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-apple-iphone-14-pro-max-icloud-activation-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing Apple iPhone 14 Pro Max iCloud Activation Lock</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-nokia-c12-plus-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Nokia C12 Plus Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-2024-approved-get-closer-to-the-artistic-marvels-of-ai-portrait-generator/"><u>New 2024 Approved Get Closer to the Artistic Marvels of AI Portrait Generator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-order-in-windows-registry-through-repair-methods/"><u>Restoring Order in Windows Registry Through Repair Methods</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-nokia-c12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-tracking-your-apps/"><u>Stop Windows From Tracking Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-pin-verification-issues-on-w11w10-pcs/"><u>Strategies to Solve PIN Verification Issues on W11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-definitive-guide-to-configuring-script-policies-in-ps/"><u>The Definitive Guide to Configuring Script Policies in PS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-picks-optimal-pomodoro-timers-tailored-for-windows-users/"><u>Top Picks: Optimal Pomodoro Timers Tailored For Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-compatibility-tips-synapse-reinstatement-guide/"><u>Win Compatibility Tips: Synapse Reinstatement Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-memory-makeover-with-triple-tactics/"><u>Windows Memory Makeover with Triple Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-roblox-needs-to-close-windows-errors/"><u>Winning Against Roblox Needs to Close Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-windowed-games-a-list-of-best-fps-trackers-on-pc/"><u>Winning at Windowed Games: A List of Best FPS Trackers on PC</u></a></li>
</ul></div>
