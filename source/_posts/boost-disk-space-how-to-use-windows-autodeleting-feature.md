---
title: "Boost Disk Space: How to Use Windows' AutoDeleting Feature"
date: 2025-01-25T10:17:24.150Z
updated: 2025-02-01T13:58:08.861Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Disk Space: How to Use Windows' AutoDeleting Feature"
excerpt: "This Article Describes Boost Disk Space: How to Use Windows' AutoDeleting Feature"
keywords: Save Disk Space (AutoDelete),Deleting Files on Win,Maximize Disk Usage,AutoCleaning Windows,Reduce Storage Need,Clearable Windows Cache,Limit File Size WINDOWS
thumbnail: https://thmb.techidaily.com/b74744220589b6a906ebb663c728844a6da00413ed53ac60e0a2a79854afed11.jpg
---

## Boost Disk Space: How to Use Windows' AutoDeleting Feature

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Similarly, in the **Add arguments** box, type in the following command:

`/p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 In the above command, tweak the _"C:\\path\\to\\folder_" to the path of the folder where your files are and replace "_/d -30_" with actual number you'd like pick. So, your command will become something like this:

`/p "%userprofile%\Users\[Your Username]\Downloads" /s /d -30 /c "cmd /c del /q @file"`

 Click on **OK**. Finally, from the **Settings** tab, check the following checkboxes and then click on **OK**:

* Allow task to be run on demand.
* Run the task as soon as possible after a scheduled start is missed.
* If the task fails, restart every.

![new action setting on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-setting-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-aurora-hdr-vs-standard-imagery-quality-analysis/"><u>[New] 2024 Approved Aurora HDR vs Standard Imagery Quality Analysis</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-groundwork-for-motion-visual-storytelling-for-2024/"><u>[New] Groundwork for Motion Visual Storytelling for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-craft-your-story-with-immersive-youtube-video-editing-tips/"><u>[New] In 2024, Craft Your Story with Immersive YouTube Video Editing Tips</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-zoom-strategy-for-fb-live-success/"><u>[New] The Ultimate Zoom Strategy for FB Live Success</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-3dr-the-path-taken-by-a-lone-printer-explorer/"><u>[Updated] 2024 Approved '3DR' The Path Taken by a Lone Printer Explorer</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-market-victory-through-unwrapped-strategy/"><u>2024 Approved Market Victory Through Unwrapped Strategy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-steam-access-error-on-windows-11/"><u>Clearing Up Steam Access Error on Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/culinary-havoc-unleashed-an-insightful-critique-of-overcooked-2/"><u>Culinary Havoc Unleashed: An Insightful Critique of Overcooked! 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-winmedia-tool-error-0x90017/"><u>Deciphering WinMedia Tool Error: 0X90017</u></a></li>
<li><a href="https://techtrends.techidaily.com/desktop-snapchatting-made-easy-tips-and-tricks-for-using-the-app-on-a-pc/"><u>Desktop Snapchatting Made Easy: Tips and Tricks for Using the App on a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-pc-info-retrieval-with-everythingapp/"><u>Fast PC Info Retrieval with EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-tackle-windows-loading-library-error-87paramerr/"><u>Guidance to Tackle Windows Loading Library Error 87:ParamErr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/handling-loaderror-87-on-windows-libraries-misalignment/"><u>Handling LoadError 87 on Windows Libraries Misalignment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-steam-game-victories/"><u>Refreshing Your Steam Game Victories</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/step-up-your-game-6-proven-tips-for-mastering-portuguese/"><u>Step Up Your Game - 6 Proven Tips for Mastering Portuguese</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-synchronizing-sticky-notes-on-w11/"><u>Troubleshooting Non-Synchronizing Sticky Notes on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-the-archive-of-your-snaps/"><u>Windows: The Archive of Your Snaps</u></a></li>
</ul></div>

