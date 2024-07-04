---
title: Stay Organized with Automatic Files Deletion in Win11
date: 2024-06-25T16:45:50.972Z
updated: 2024-06-26T16:45:50.972Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stay Organized with Automatic Files Deletion in Win11
excerpt: This Article Describes Stay Organized with Automatic Files Deletion in Win11
keywords: Win11 File Cleanup,Auto Delete WinFiles,Stay Tidy Windows 11,Organize PC Space Win11,Effortless Deletion Win11,Streamline Files Windows 11,Win11 Automatic Purge
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Stay Organized with Automatic Files Deletion in Win11

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
<li><a href="https://win11-tips.techidaily.com/peering-into-ftdibussys-an-analysis-of-windows-memory-controls/"><u>Peering Into ftdibus.sys: An Analysis of Windows' Memory Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-subsystem-with-5-crucial-techniques/"><u>Enhancing Windows Subsystem with 5 Crucial Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-lan-access-barriers-on-winsminecraft/"><u>Dismantling LAN Access Barriers on WinsMinecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-cleanup-integrating-uninstall-shortcuts-into-wins-interface/"><u>Convenient Cleanup: Integrating Uninstall Shortcuts Into Win's Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-conquering-system-calls-failure-in-windows-11/"><u>Expert Tips for Conquering System Calls Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsofts-apppack-and-msibundle-files-to-enhance-productivity/"><u>Integrating Microsoft's Apppack and MsiBundle Files to Enhance Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-with-hyper-v-on-windows-11/"><u>Jumpstart Your PC with Hyper-V on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-10-filmora-editing-traits-for-fan-loyalty/"><u>[Updated] Top 10 Filmora Editing Traits for Fan Loyalty</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-reviewing-multiple-cameras-are-there-upgrades/"><u>[Updated] In 2024, Reviewing Multiple Cameras  Are There Upgrades?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-search-filters-on-instagram-and-get-more-filters-for-free/"><u>[Updated] How to Search Filters on Instagram and Get More Filters for Free</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-innovative-gb-recorder-for-games-on-fbx/"><u>[New] In 2024, Innovative GB Recorder for Games on FBX</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-nokia-g22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-from-last-minute-to-first-impression-how-to-rewind-video-on-instagram/"><u>[Updated] From Last Minute to First Impression  How to Rewind Video on Instagram</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-mastering-youtube-music-a-step-by-step-audio-download-guide/"><u>2024 Approved Mastering YouTube Music A Step-by-Step Audio Download Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-your-aspects-of-sound-and-sight-in-asmr-recording/"><u>[New] 2024 Approved  Elevate Your Aspects of Sound and Sight in ASMR Recording</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-your-android-footage-with-stunning-time-lapse-videos/"><u>[New] Transform Your Android Footage with Stunning Time-Lapse Videos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>