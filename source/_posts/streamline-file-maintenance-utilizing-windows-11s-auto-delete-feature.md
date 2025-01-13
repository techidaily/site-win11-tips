---
title: "Streamline File Maintenance: Utilizing Windows 11’S Auto Delete Feature"
date: 2025-01-08T02:14:59.436Z
updated: 2025-01-12T21:28:12.937Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamline File Maintenance: Utilizing Windows 11’S Auto Delete Feature"
excerpt: "This Article Describes Streamline File Maintenance: Utilizing Windows 11’S Auto Delete Feature"
keywords: W11AutoDeleteFiles,StreamlineFileMaintenance,Win11EasyCleanup,DeletingDocsWindows,FileSystemAutoClear,Windows11Optimize,DeleteFeatureWin11
thumbnail: https://thmb.techidaily.com/8728071c55cb4a9d737d3c276cbce71523d45848bd43ebfc7e5000f0a5d34387.jpg
---

## Streamline File Maintenance: Utilizing Windows 11’S Auto Delete Feature

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-flame-the-fire-enhancing-your-snapstreak-game/"><u>[New] 2024 Approved Flame the Fire Enhancing Your Snapstreak Game</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-defeating-darkness-in-youtube-videos/"><u>[Updated] Defeating Darkness in Youtube Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-instant-access-windows-photos-view/"><u>2024 Approved Instant Access Windows Photos View</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-essence-of-sound-diminishment-a-lumafusion-insight/"><u>2024 Approved The Essence of Sound Diminishment A Lumafusion Insight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-things-you-should-avoid-doing-on-windows-11/"><u>8 Things You Should Avoid Doing on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-archiving-feature/"><u>Activating Windows 11'S Archiving Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activatingdeactivating-windows-key-made-simple/"><u>Activating/Deactivating Windows Key Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-one-way-outlook-issue-in-secure-environments/"><u>Addressing the One-Way Outlook Issue in Secure Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-drivers-for-windows-a-comprehensive-update-guide/"><u>Audio Drivers for Windows: A Comprehensive Update Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-the-worst-javascript-failures-while-using-discord-in-win-oses/"><u>Avoiding the Worst JavaScript Failures While Using Discord in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-pc-speed-with-improved-win11-startups/"><u>Boost PC Speed with Improved Win11 Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-customized-windows-cmd-tricks-and-tips/"><u>Boost Productivity: Customized Windows Cmd Tricks and Tips</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-galaxy-f54-5g-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Galaxy F54 5G</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fast-track-to-apple-vision-pro-discover-unforeseen-swift-delivery/"><u>Fast Track to Apple Vision Pro: Discover Unforeseen Swift Delivery!</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-battleye-setup-issues-how-to-handle-the-infamous-driver-load-error-1450/"><u>Fixing BattlEye Setup Issues: How to Handle the Infamous Driver Load Error (1450)</u></a></li>
<li><a href="https://fox-within.techidaily.com/troubleshooting-audio-issues-how-to-spot-problems-with-your-sound-card-yl-computings-guide/"><u>Troubleshooting Audio Issues: How to Spot Problems with Your Sound Card - YL Computing's Guide</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-10-best-public-domain-image-websites-for-2024/"><u>Updated 10 Best Public Domain Image Websites for 2024</u></a></li>
</ul></div>

