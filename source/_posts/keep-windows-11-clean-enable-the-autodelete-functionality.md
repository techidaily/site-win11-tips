---
title: "Keep Windows 11 Clean: Enable the Autodelete Functionality"
date: 2024-06-25T16:06:13.570Z
updated: 2024-06-26T16:06:13.570Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/screenshare-success-crafting-unique-wallpapers-per-windows-1011-monitor/"><u>Screenshare Success: Crafting Unique Wallpapers per Windows 10/11 Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-windows-horizon-surpassing-11s-achievements/"><u>Next Windows Horizon: Surpassing 11'S Achievements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-invalid-device-label-in-windows-os/"><u>Correcting 'Invalid Device' Label in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gui-diskspace-windows-menu-integration-guide/"><u>Mastering GUI Diskspace: Windows Menu Integration Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-repeatedly-accessing-cmos-settings/"><u>Stop Windows From Repeatedly Accessing CMOS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-how-to-circumvent-secure-boot-mechanism-in-windows-11/"><u>Exposing How To Circumvent Secure Boot Mechanism in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-start-issue-qt-plugin-not-available/"><u>Troubleshooting App Start Issue: Qt Plugin Not Available</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oneplus-11r-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On OnePlus 11R</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-unlock-on-apple-iphone-13-pro-how-to-fix-it-by-drfone-ios/"><u>Apple ID Unlock On Apple iPhone 13 Pro? How to Fix it?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-art-of-video-marketing-11-tips-to-skyrocket-fb-traffic/"><u>[New] The Art of Video Marketing  11 Tips to Skyrocket FB Traffic</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-comprehensive-guidance-transforming-your-discord-chat-with-voxal-sound-modification-techniques-for-2024/"><u>Updated Comprehensive Guidance Transforming Your Discord Chat with Voxal Sound Modification Techniques for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-guide-to-adding-creative-closure-in-vimeo-videos/"><u>[Updated] Guide to Adding Creative Closure in Vimeo Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-enhancing-text-clarity-in-high-quality-obs-output/"><u>[Updated] Enhancing Text Clarity in High Quality OBS Output</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-uniting-networks-sharing-fb-vids-on-whatsapp-chat/"><u>[Updated] 2024 Approved  Uniting Networks  Sharing FB Vids on WhatsApp Chat</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-through-the-best-pc-vr-headset-lineup-of-2023/"><u>In 2024, Navigating Through the Best PC VR Headset Lineup of 2023</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-drafting-an-emotional-tiktok-conclusion/"><u>In 2024, Drafting an Emotional TikTok Conclusion</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-pioneering-a-dual-perspective-3-innovative-techniques-for-viewpoint-based-youtube-reactions/"><u>2024 Approved  Pioneering a Dual Perspective  3 Innovative Techniques for Viewpoint-Based YouTube Reactions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>