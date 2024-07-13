---
title: Simplifying File Management with Windows' AutoDelete Feature
date: 2024-07-12T16:37:58.900Z
updated: 2024-07-13T16:37:58.900Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplifying File Management with Windows' AutoDelete Feature
excerpt: This Article Describes Simplifying File Management with Windows' AutoDelete Feature
keywords: AutoDelete Files,WINDOWS AutoDeletion,File Management Toolkit,Simplified File Handling,Deleted Files Removal,Streamline Windows File,Efficient File Management
thumbnail: https://thmb.techidaily.com/a27b3a3de27d6b4c9a23aaf5bc90c6e51b30c3f5343bae186756d50b06815cf1.jpg
---

## Simplifying File Management with Windows' AutoDelete Feature

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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-the-ultimate-list-of-sandbox-treasures/"><u>[Updated] 2024 Approved  The Ultimate List of Sandbox Treasures</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-index-of-digital-imagery-collections-for-2024/"><u>Premier Index of Digital Imagery Collections for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-top-5-eco-conscious-filmmaking-advances/"><u>[New] 2024 Approved  Top 5 Eco-Conscious Filmmaking Advances</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/professional-youtubers-guide-studio-vs-next-generation-beta/"><u>Professional YouTuber's Guide  Studio Vs. Next Generation Beta</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719202889022-efficient-tips-for-resolving-common-windows-problems/"><u>Efficient Tips for Resolving Common Windows Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-s-mode-imply-in-windows-11-upgrade/"><u>What Does 'S Mode' Imply in Windows 11 Upgrade?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-command-routes-for-fast-diagnostic-center-entry/"><u>10 Command Routes for Fast Diagnostic Center Entry</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-pro-max-passcode-screen-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 Pro Max Passcode Screen?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719203477260-how-to-unfreeze-google-chrome-in-windows-11-fastly-find-out-now/"><u>How to Unfreeze Google Chrome in Windows 11 Fastly? Find Out Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-dilemma-obs-not-opening-on-windows/"><u>Resolving the Dilemma: OBS Not Opening on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-bandicam-in-focus-the-updated-guide-users/"><u>2024 Approved  Bandicam in Focus  The Updated Guide Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-the-great-debate-continues-is-bandicam-or-camtasia-better/"><u>[Updated] 2024 Approved  The Great Debate Continues  Is Bandicam or Camtasia Better?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-setting-up-google-maps-on-windows-pcs/"><u>Navigating the Path: Setting up Google Maps on Windows PCs</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-stream-like-a-pro-optimizing-your-360-youtube-broadcasts/"><u>[New] 2024 Approved  Stream Like a Pro  Optimizing Your 360° Youtube Broadcasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-ways-to-simplify-network-connection-configurations-in-winos/"><u>10 Ways to Simplify Network Connection Configurations in WinOS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-art-of-transcribing-top-4-tactics-for-fb-chat-recordings/"><u>[Updated] In 2024, The Art of Transcribing  Top 4 Tactics for FB Chat Recordings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-fixes-for-fbm-not-working-here/"><u>10 Essential Fixes for FBM Not Working Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-non-detectable-wi-fi-in-win11/"><u>The Ultimate Guide to Fixing Non-Detectable Wi-Fi in Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10plus-strategies-for-system-settings-entry/"><u>10+ Strategies for System Settings Entry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steer-clear-of-stuck-arrows-in-windows/"><u>Steer Clear of Stuck Arrows in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-skyrocketing-influence-growth-in-youtube-audience/"><u>In 2024, Skyrocketing Influence  Growth in YouTube Audience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/12-superfluous-windows-tools-you-can-live-without/"><u>12 Superfluous Windows Tools You Can Live Without</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-power-enable-the-outlook-preview-app/"><u>Unlock Windows' Power: Enable the Outlook Preview App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-key-strategies-for-managing-windows-connections-tool/"><u>10 Key Strategies for Managing Window's Connections Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-using-windows-file-browsing-in-place-of-ls/"><u>Expert Tips for Using Windows File Browsing in Place of LS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-straightforward-steps-to-engage-repair-tool/"><u>10 Straightforward Steps to Engage Repair Tool</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-halt-autoplay-youtube-recommendations-for-2024/"><u>[New] Halt Autoplay YouTube Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-tips-to-help-you-fix-the-windows-11-blue-screen-error/"><u>11 Tips to Help You Fix the Windows 11 Blue Screen Error</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-moto-g14-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Moto G14.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-workspace-windows-11-widget-techniques/"><u>Revamp Your Workspace: Windows 11 Widget Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-background-removal-in-photo-editing-tools/"><u>Mastering Background Removal in Photo Editing Tools</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-oppo-find-x7-ultra-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Oppo Find X7 Ultra Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719205412582-shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719192555427-environment-variables-configuration/"><u>Environment Variables Configuration:</u></a></li>
</ul></div>
