---
title: Techniques for Synchronized Shutdown of Multiple Windows Apps
date: 2024-08-28T01:16:00.869Z
updated: 2024-08-29T01:16:00.869Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Synchronized Shutdown of Multiple Windows Apps
excerpt: This Article Describes Techniques for Synchronized Shutdown of Multiple Windows Apps
keywords: Window Sync Stop,Multi-App Shutdown,Sync Closing Procedures,Uniform App Shutdown,Coordinated Close Tech,Group Windows Cleanup,Synchronized App Termination
thumbnail: https://thmb.techidaily.com/27b127c31cd1d4c4e3c7e2e3da33ec44af88b4b625ba034a78a3512eb4d83268.jpg
---

## Techniques for Synchronized Shutdown of Multiple Windows Apps

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-in-2024-the-undercover-upsell-simple-image-saving/"><u>[New] In 2024, The Undercover Upsell  Simple Image Saving</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-simplified-guide-fb-video-to-mp3-audio-transformations/"><u>[New] Simplified Guide  FB Video to MP3 Audio Transformations</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-free-image-repository-roundup-top-10-sites-reviewed-for-2024/"><u>[Updated] Free Image Repository Roundup  Top 10 Sites Reviewed for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-mastering-self-portraits-top-techniques-for-youtube-presentations/"><u>[Updated] In 2024, Mastering Self-Portraits  Top Techniques for YouTube Presentations</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-multiplatform-iptv-encoding/"><u>[Updated] In 2024, Multiplatform IPTV Encoding</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-revive-missing-fb-watch-icon-solutions/"><u>2024 Approved  Revive Missing FB Watch Icon - Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/best-15-free-bootable-antiviruses-of-the-year/"><u>Best 15 Free Bootable Antiviruses of the Year</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-google-photos-guide-for-beginners/"><u>Complete Google Photos Guide for Beginners</u></a></li>
<li><a href="https://win-blog.techidaily.com/conquer-the-track-with-roller-champions-your-expert-crossplayer-tips-for-pc-in-202n4/"><u>Conquer the Track with Roller Champions: Your Expert Crossplayer Tips for PC in 202N4</u></a></li>
<li><a href="https://tech-revival.techidaily.com/crafting-nutritious-diet-plans-with-the-help-of-chatgpt/"><u>Crafting Nutritious Diet Plans with the Help of ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-windows-identity-user-name-transformation/"><u>Customizing Your Windows Identity: User Name Transformation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-windows-ipmac-using-powershell-techniques/"><u>Easy Windows IP/MAC: Using PowerShell Techniques</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhanced-efficiency-update-lenovo-w11-drivers-in-windows-11/"><u>Enhanced Efficiency - Update Lenovo W11 Drivers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-disk-space-on-win11-safely-keep-files-intact-max-156-chars/"><u>Enhancing Disk Space on Win11 Safely (Keep Files Intact, Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essentials-of-windows-iscsi-initiator-and-access-methods/"><u>Essentials of Windows iSCSI Initiator and Access Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-access-issues-with-nvidia-cp/"><u>Fixing Windows Access Issues with NVIDIA CP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-rockalldlldll-not-found-or-missing-error-on-windows-pc/"><u>How to Fix Rockalldll.dll Not Found or Missing Error on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-flickering-displays-on-windows-11-systems/"><u>How to Mend Flickering Displays on Windows 11 Systems</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-cinematic-hope-the-top-10-inspirational-films/"><u>In 2024, Cinematic Hope  The Top 10 Inspirational Films</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-discovering-new-ways-to-use-bandicam-a-deep-dive/"><u>In 2024, Discovering New Ways to Use Bandicam – A Deep Dive</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Gionee F3 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-windows-os-on-steam-deck-explained/"><u>Installing Windows OS on Steam Deck Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-11-more-engaging-with-themes/"><u>Make Windows 11 More Engaging with Themes</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-the-tricks-to-launch-dota-2-successfully-bypassing-load-errors/"><u>Master the Tricks to Launch Dota 2 Successfully: Bypassing Load Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-firewall-controls-five-techniques/"><u>Mastering Firewall Controls: Five Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-zero-clutter-windows-auto-delete-feature/"><u>Navigate to Zero Clutter: Windows' Auto-Delete Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-maze-of-system-recovery-for-broken-windows-registry/"><u>Navigating the Maze of System Recovery for Broken Windows Registry</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-vsdc-video-editor-not-on-mac-no-problem-here-are-the-alternatives/"><u>New In 2024, VSDC Video Editor Not on Mac? No Problem! Here Are the Alternatives</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-silencing-soundscape-guiding-you-to-audio-deletion-in-mov-files-for-both-operating-systems/"><u>New Silencing Soundscape Guiding You to Audio Deletion in MOV Files for Both Operating Systems</u></a></li>
<li><a href="https://win-blog.techidaily.com/no-more-interruptions-solving-performance-issues-and-pc-crashing-in-the-witcher-3/"><u>No More Interruptions: Solving Performance Issues & PC Crashing in The Witcher 3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-call-error-in-windows-os/"><u>Overcoming System Call Error in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peeling-back-the-layers-of-windows-11-themes-via-registry/"><u>Peeling Back the Layers of Windows 11 Themes via Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-of-league-of-legends-lol-on-pc/"><u>Restoring Online Status of League of Legends (LoL) on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-windows-viewer-to-original-arrangement/"><u>Reverting Windows Viewer to Original Arrangement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-thought-process-adopting-visually-organized-notetaking-via-obsidian-canvas/"><u>Streamline Your Thought Process: Adopting Visually Organized Notetaking via Obsidian Canvas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-mobile-setup-with-one-click-apks-in-windows-11/"><u>Supercharge Your Mobile Setup with One Click APKs in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-undetected-shutdown-guide-for-win11-users/"><u>The Undetected Shutdown Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-workflow-essential-wins11-god-mode-tips/"><u>Transforming Workflow: Essential Wins11 God Mode Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-nvidia-cp-unresponsiveness-on-win-11/"><u>Troubleshooting Nvidia CP Unresponsiveness on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-lost-render-capabilities-in-overwatch-2-pc/"><u>Unlocking Lost Render Capabilities in Overwatch 2 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-password-reset-lockout-period-change/"><u>Windows 10/11 Password Reset Lockout Period Change</u></a></li>
</ul></div>
