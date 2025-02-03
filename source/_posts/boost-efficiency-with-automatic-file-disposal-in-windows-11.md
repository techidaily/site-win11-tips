---
title: Boost Efficiency with Automatic File Disposal in Windows 11
date: 2025-01-29T01:11:57.520Z
updated: 2025-01-31T19:17:57.523Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Efficiency with Automatic File Disposal in Windows 11
excerpt: This Article Describes Boost Efficiency with Automatic File Disposal in Windows 11
keywords: AutoFileDispose Windows11,BoostEfficiency W11,FileDisposal SaveTime,EfficientW11 Management,Automatic FileCleanup Win,DiskSpace OptimizeWin11,Streamline Files Windows11
thumbnail: https://thmb.techidaily.com/253a511a8eebe03ad95bca3519e71144f55137cbd051ad18a83009076fc1de06.jpg
---

## Boost Efficiency with Automatic File Disposal in Windows 11

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-sure.techidaily.com/ree-youtube-endings-that-stand-out-ranked/"><u>[New] Free YouTube Endings That Stand Out - Ranked!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-the-art-of-collages-thanks-to-picshot/"><u>[New] Master the Art of Collages, Thanks to Picshot</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-advanced-transitions-techniques-for-audios/"><u>2024 Approved Advanced Transitions Techniques for Audios</u></a></li>
<li><a href="https://sound-issues.techidaily.com/addressing-voice-chat-failures-for-a-seamless-lol-experience/"><u>Addressing Voice Chat Failures for a Seamless LOL Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-power-losses-how-to-schedule-auto-shutdown-on-win11-pcs/"><u>Cutting Power Losses: How to Schedule Auto-Shutdown on Win11 PCs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-fixes-for-overcoming-msvcr80dll-not-found-errors-on-your-pc/"><u>Effective Fixes for Overcoming 'Msvcr80.dll Not Found Errors' On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-up-to-speed-with-quick-copy-paste-in-powertoys/"><u>Get Up to Speed With Quick Copy-Paste in PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-d3dx939dll-missing-error-on-windows-11/"><u>How to Fix the D3DX9_39.dll Missing Error on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-amateurs-to-pros-learning-audio-recording-in-audacity/"><u>In 2024, From Amateurs to Pros Learning Audio Recording in Audacity</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-poco-x5-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP on Poco X5 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-media-errors-in-win11/"><u>Mastering the Art of Fixing Media Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-file-explorer-without-ls-command/"><u>Navigating Windows File Explorer: Without LS Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimized-file-picking-toggle-windows-11-checkboxes/"><u>Optimized File Picking: Toggle Windows 11 Checkboxes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-absence-of-power-elapsed-display-in-windows-11/"><u>Resolving Absence of Power Elapsed Display in Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/h-sync-add-youtube-soundtracks-to-imovie-easily-for-2024/"><u>Smooth Sync Add YouTube Soundtracks to iMovie Easily for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-windows-group-policy-interpretation-3-ways/"><u>The Essential Guide to Windows Group Policy Interpretation (3 Ways)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-disabling-gpu-aided-process-ordering-in-widno/"><u>The Guide to Disabling GPU-Aided Process Ordering in WIDNO</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-synergy-of-business-and-virtual-experience-design-for-2024/"><u>The Synergy of Business and Virtual Experience Design for 2024</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/troubleshooting-a-complete-lack-of-display-at-startup-causes-and-fixes-by-yl-experts-in-computing-and-software-development/"><u>Troubleshooting a Complete Lack of Display at Startup: Causes & Fixes by YL Experts in Computing and Software Development</u></a></li>
</ul></div>

