---
title: "Keep Windows 11 Clean: Enable the Autodelete Functionality"
date: 2024-07-12T16:29:38.960Z
updated: 2024-07-13T16:29:38.960Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Keep Windows 11 Clean: Enable the Autodelete Functionality"
excerpt: "This Article Describes Keep Windows 11 Clean: Enable the Autodelete Functionality"
keywords: Win11 Cleanliness Tips,Enable Delete Feature,Auto-Deletion in Windows 11,Keeping Windows Updated,Deleted Files Removal,Optimize Windows Performance,Automatic File Purge
thumbnail: https://thmb.techidaily.com/bc869d9d43a6e8eaba8010b4b670a5dfb48692bbace90e7ba999d6674c090e3f.jpg
---

## Keep Windows 11 Clean: Enable the Autodelete Functionality

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/regaining-command-over-disabled-menu-functions/"><u>Regaining Command over Disabled Menu Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-yourphoneexe-malware-insights-on-windows-87/"><u>Is YourPhone.exe Malware? Insights on Windows 8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-errors-quickly-with-windows-rdp-connections/"><u>Resolving Internal Errors Quickly with Windows RDP Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/embedding-ical-into-your-windows-system-without-hassle/"><u>Embedding iCal Into Your Windows System without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-dropbox-cpu-utilization-on-windows-machines/"><u>Lowering Dropbox CPU Utilization on Windows Machines</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-facebook-dating-for-your-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-subnet-tweak-for-experienced-users-win11/"><u>Effortless Subnet Tweak for Experienced Users, Win11</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-odins-vengeance-realm-awakens/"><u>In 2024, Odin’s Vengeance  Realm Awakens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-quickcapture-miniapp-windows-10-version/"><u>In 2024, QuickCapture MiniApp - Windows 10 Version</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-exploring-genres-a-collection-of-15-innovative-musician-focused-videos/"><u>[New] 2024 Approved  Exploring Genres  A Collection of 15 Innovative Musician-Focused Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-hidden-options-mastery-of-lost-control-configurations/"><u>Explore Hidden Options: Mastery of Lost Control Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-vegas-pro-not-your-cup-of-tea-explore-these-10-mac-friendly-video-editors/"><u>New In 2024, Vegas Pro Not Your Cup of Tea? Explore These 10 Mac-Friendly Video Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exclusive-guide-to-the-best-fileshare-apps-on-a-windows-laptop/"><u>Exclusive Guide to the Best Fileshare Apps on a Windows Laptop</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/illuminating-ideas-the-basics-of-video-setup/"><u>Illuminating Ideas  The Basics of Video Setup</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-achieving-perfect-time-lapses-with-ios-devices-for-2024/"><u>[New] Achieving Perfect Time-Lapses with iOS Devices for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/envisioning-the-ideal-user-experience-in-windows-11/"><u>Envisioning the Ideal User Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploiting-windows-11s-error-diagnostic-solutions/"><u>Exploiting Windows 11'S Error Diagnostic Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unlock-your-onedrive-on-a-windows-machine/"><u>How To Unlock Your OneDrive on a Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-taskbar-icon-anomalies/"><u>Rectifying Taskbar Icon Anomalies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-terminal-usage-make-it-primary-choice/"><u>Elevate Your Terminal Usage: Make It Primary Choice</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-windows-files-disabling-read-only-status/"><u>Manipulating Windows Files: Disabling Read-Only Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leap-forward-in-windows-video-management-integrate-tdarrs-distributed-capabilities/"><u>Leap Forward in Windows Video Management: Integrate Tdarr's Distributed Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multiple-routes-for-opening-utilities-on-windows-systems/"><u>Multiple Routes for Opening Utilities on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-clear-the-focus-wallpaper-icon-on-windows-11/"><u>How to Clear the Focus Wallpaper Icon on Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-peer-reviewed-best-action-replay-tech/"><u>[New] Peer-Reviewed Best Action Replay Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-step-by-step-filming-and-editing-your-first-reel-on-facebook/"><u>[Updated] 2024 Approved  Step-by-Step  Filming and Editing Your First Reel on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-approaches-to-adjacent-and-distinct-windows-partition-merging/"><u>Cutting-Edge Approaches to Adjacent and Distinct Windows Partition Merging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hazards-of-cheap-windows-key-purchases/"><u>Navigating the Hazards of Cheap Windows Key Purchases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-discord-launch-and-update-check-with-windows-startup/"><u>Preventing Discord Launch and Update Check with Windows Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-apk-deployment-for-win-11-users/"><u>Instant APK Deployment for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-10-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-windows-11-search-top-5-expert-methods/"><u>Optimize Your Windows 11 Search: Top 5 Expert Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-epic-launcher-sign-in-on-pc/"><u>Mastering the Art of Epic Launcher Sign-In on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-nokia-c12-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-precision-photography-snippets-from-videos-on-windows-11/"><u>In 2024, Precision Photography Snippets From Videos on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-account-security-changing-reset-counter-after-failed-logins/"><u>Optimizing Account Security: Changing Reset Counter After Failed Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-honor-90-pro-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Honor 90 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
</ul></div>
