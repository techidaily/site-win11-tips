---
title: "Tailored Windows Trick: Sticky Notes Open-Up With System Boot"
date: 2024-08-16T01:25:44.026Z
updated: 2024-08-17T01:25:44.026Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tailored Windows Trick: Sticky Notes Open-Up With System Boot"
excerpt: "This Article Describes Tailored Windows Trick: Sticky Notes Open-Up With System Boot"
keywords: Tailored Windows Help,Sticky Notes Launcher,Quick Sys Start,Windows Note Opener,Booted Notify Tool,System Boot Trick,Custom Sys Access
thumbnail: https://thmb.techidaily.com/db587631bccc11018e71b0f197be1378b7d1dbbecd5a463368074dbdb88b8238.jpg
---

## Tailored Windows Trick: Sticky Notes Open-Up With System Boot

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
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App ![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-enhancing-video-quality-editing-tips-for-published-content-for-2024/"><u>[New] Enhancing Video Quality  Editing Tips for Published Content for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-strategies-to-solve-obs-fullscreen-breakdowns/"><u>[New] Strategies to Solve OBS Fullscreen Breakdowns</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-twists-that-tell-stories-crafting-captivating-visual-narratives-on-instagram-platforms/"><u>[New] Twists That Tell Stories  Crafting Captivating Visual Narratives on Instagram Platforms</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hype-generating-headline-author/"><u>[Updated] Hype-Generating Headline Author</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-the-ultimate-checklist-for-top-notch-fb-cover-videos/"><u>2024 Approved  The Ultimate Checklist for Top-Notch FB Cover Videos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-top-ios-pro-and-plus-free-film-apps-unveiled/"><u>2024 Approved  Top iOS  Pro & Plus-Free Film Apps - Unveiled</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternatives-when-bitlocker-isnt-available-on-windows/"><u>5 Alternatives When Bitlocker Isn't Available on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tactics-to-prevent-c-drive-from-running-dry-in-windows/"><u>5 Tactics to Prevent C: Drive From Running Dry in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-strategies-to-extend-your-hard-drives-lifespan/"><u>6 Strategies to Extend Your Hard Drive's Lifespan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-microsoft-can-improve-phone-link-on-windows-11/"><u>7 Ways Microsoft Can Improve Phone Link on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-newcomers-path-in-the-world-of-original-diablo/"><u>A Newcomer's Path in the World of Original Diablo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-visual-journey-customizing-your-windows-11-monitor-walls/"><u>A Visual Journey: Customizing Your Windows 11 Monitor Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-tasks-with-efficient-cmd-commands-top-20/"><u>Accelerate Tasks with Efficient CMD Commands (Top 20)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-system-best-practices-for-dns-setup-in-windows-11/"><u>Accelerate Your System: Best Practices for DNS Setup in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-dns-performance-via-reset/"><u>Achieving Optimal DNS Performance via Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/action-plan-conquering-error-0x800700e1-in-windows-11-systems/"><u>Action Plan: Conquering Error 0X800700E1 in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activate-quick-fix-support-windows-11-procedure/"><u>Activate Quick Fix Support: Windows 11 Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-subsystem-for-linux-wsl-steps/"><u>Activating Windows Subsystem for Linux (WSL) Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-networked-resources-in-explorers-sidebar/"><u>Adding Networked Resources in Explorer's Sidebar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incompatibility-with-windows-11-at-home/"><u>Addressing Incompatibility with Windows 11 at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-how-to-open-excel-files-in-notepad-correctly/"><u>Addressing: How to Open Excel Files in Notepad Correctly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-dpi-settings-for-optimal-display-performance/"><u>Adjust DPI Settings for Optimal Display Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjust-window-placement-for-windows-users/"><u>Adjust Window Placement for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-real-time-performance-of-win-11-task-manager/"><u>Adjusting Real-Time Performance of Win 11 Task Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-strategies-in-group-policy-with-gpresult/"><u>Advanced Strategies in Group Policy with GPResult</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-techniques-to-eliminate-stale-dns-entries/"><u>Advanced Techniques to Eliminate Stale DNS Entries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-entering-windows-terminal-admin-mode-ready/"><u>Automate Entering Windows Terminal, Admin Mode Ready</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-disruptions-with-top-fixes-for-file-explorer-glitches-on-win11/"><u>Avoid Disruptions with Top Fixes for File Explorer Glitches on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-game-interruption-preventing-frequent-ps4-controller-drop-outs-in-windows/"><u>Avoid Game Interruption: Preventing Frequent PS4 Controller Drop-Outs in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-avenue-windows-11-disabling-tactics/"><u>Avoidance Avenue: Windows 11 Disabling Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-a-step-by-step-guide-to-the-taskbars-search-bar-in-windows-11/"><u>Boost Efficiency: A Step-By-Step Guide to the Taskbar’s Search Bar in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-essential-wsl-2-approaches-for-win-users/"><u>Boost Performance: Essential WSL 2 Approaches for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-efficiency-integrating-new-folders-into-windows-11-menu/"><u>Boosting Efficiency: Integrating New Folders Into Windows 11 Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-speed-the-best-windows-mouse-drivers/"><u>Boosting Speed: The Best Windows Mouse Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719296840588-end-of-year-sale-windows-10-starting-at-an-insanely-low-612/"><u>End of Year Sale: Windows 10, Starting at an Insanely Low $6.12!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-itel-a70-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Itel A70 Phone When You Forget the Password</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-poco-c55-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Poco C55</u></a></li>
<li><a href="https://buynow-info.techidaily.com/navigating-through-comfort-and-clarity-the-ultimate-guide-to-the-rotibox-bluetooth-headset-hat/"><u>Navigating Through Comfort and Clarity: The Ultimate Guide to the Rotibox Bluetooth Headset Hat</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-star-studded-us-kids-choice-awards-present-nickwatch-the-newest-tech-for-youngsters/"><u>The Star-Studded U.S. Kids' Choice Awards Present NickWatch: The Newest Tech for Youngsters</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-tier-functionality-at-an-accessible-price-the-in-depth-review-of-apples-new-ipad-air-4-and-how-it-stacks-up-to-the-pro-series/"><u>Top-Tier Functionality at an Accessible Price: The In-Depth Review of Apple's New iPad Air 4 and How It Stacks Up to the Pro Series</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ultimate-guide-to-top-hd-video-recorders-for-2024/"><u>Ultimate Guide to Top HD Video Recorders for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unleash-potential-with-these-essential-editing-tips-for-beginners-for-2024/"><u>Unleash Potential with These Essential Editing Tips for Beginners for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719323547365-unlock-the-future-affordable-windows-11-for-keys-fan-enthusiasts-on-black-friday/"><u>Unlock the Future: Affordable Windows 11 for Keys Fan Enthusiasts on Black Friday</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-wondering-how-to-replace-sky-in-after-effects-learn-how-for-2024/"><u>Updated Wondering How to Replace Sky in After Effects? Learn How for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-note-12-4g-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi Note 12 4G Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
</ul></div>
