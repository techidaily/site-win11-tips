---
title: Maximizing Disk Space in Windows 10 & 11 by Deleting Obsolete Files
date: 2024-11-21T16:12:32.502Z
updated: 2024-11-27T16:14:42.671Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maximizing Disk Space in Windows 10 & 11 by Deleting Obsolete Files
excerpt: This Article Describes Maximizing Disk Space in Windows 10 & 11 by Deleting Obsolete Files
keywords: WIN Disk Cleanup,File Deletion Tips,Maximize Free Storage,Remove Old Windows Files,Optimize PC Space,Clearing Obsolete Data,Enhance Disk Efficiency
thumbnail: https://thmb.techidaily.com/ca9ebd9e5568d283ff74716c5b52278ddfb01bff412fbb14fb93882fc8d1dc09.jpg
---

## Maximizing Disk Space in Windows 10 & 11 by Deleting Obsolete Files

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-enhancing-films-with-effective-b-roll-usage/"><u>[New] Enhancing Films with Effective B-Roll Usage</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-beyondonecam-testing-are-there-better-options/"><u>[Updated] BeyondOneCam Testing Are There Better Options?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-make-a-youtube-trailer-for-2024/"><u>[Updated] How To Make a YouTube Trailer for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-best-game-video-recording-and-editing-software-for-beginners/"><u>[Updated] In 2024, The Best Game Video Recording and Editing Software for Beginners</u></a></li>
<li><a href="https://solve-news.techidaily.com/1-solutions-pour-le-mac-book-pro-qui-ne-lit-pas-les-dvd/"><u>1. Solutions Pour Le Mac Book Pro Qui Ne Lit Pas Les DVD</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/aperture-advocates-the-top-10-camera-optics-guide/"><u>Aperture Advocates The Top 10 Camera Optics Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-it-admin-access-limited-error-in-winsec/"><u>Disabling IT Admin Access Limited Error in WinSec</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-secret-superiority-of-iphones-unexpected-features-spotlighted/"><u>Discover the Secret Superiority of iPhones - Unexpected Features Spotlighted</u></a></li>
<li><a href="https://win-popular.techidaily.com/how-to-solve-sticky-notes-app-unavailable-issue-on-windows-pcs/"><u>How to Solve 'Sticky Notes' App Unavailable Issue on Windows PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-driver-update-modernizing-old-windows-cards/"><u>Mastering Driver Update: Modernizing Old Windows Cards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-moving-your-onedrive-on-win-11/"><u>Mastering the Art of Moving Your OneDrive on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-photo-spinning-in-w11-os/"><u>Mastering the Art of Photo Spinning in W11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/outdated-systems-alert-windows-781-support-cuts-off-by-microsoft/"><u>Outdated Systems Alert: Windows 7/8.1 Support Cuts Off by Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sticky-notes-management-on-windows-1110/"><u>Sticky Notes Management on Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-windows-runner-error-0x8007000f/"><u>Understanding and Resolving Windows Runner Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-techniques-to-reconstruct-damaged-windows-registry-sections/"><u>Unveiling Techniques to Reconstruct Damaged Windows Registry Sections</u></a></li>
</ul></div>

