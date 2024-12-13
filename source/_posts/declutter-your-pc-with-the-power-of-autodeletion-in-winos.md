---
title: Declutter Your PC with the Power of AutoDeletion in WINOS
date: 2024-12-08T00:13:25.172Z
updated: 2024-12-12T19:38:41.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Declutter Your PC with the Power of AutoDeletion in WINOS
excerpt: This Article Describes Declutter Your PC with the Power of AutoDeletion in WINOS
keywords: Win OS Declutter,AutoDelete PC,De-Clutter Software,Delete Duplicates,PC Cleanup Tool,Organize Windows,Digital Detox WINOS
thumbnail: https://thmb.techidaily.com/095ce3d3eacef166f46f59459d5ef71a92a706285f3160a9b70eb170ae6406f1.jpg
---

## Declutter Your PC with the Power of AutoDeletion in WINOS

 For many, a cluttered desktop and downloads folder is just a way of life—no matter how hard you try, they somehow always ends up disorganized. Need to do a bit of digital spring-cleaning? Fortunately, there are lots of ways you can keep your Windows 10 computer decluttered.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Auto-Delete Old Files or Folders Using Storage Settings

 The Settings menu lets you do and manage a lot of stuff on your Windows computer. From updates to tweaking the Windows appearance—you can do almost everything. It's no surprise then that you can also use it for setting up an auto-deletion setting on your Windows. Here's how:

![storage settings on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-settings-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-integrating-social-video-platforms-with-hdtv/"><u>[New] In 2024, Integrating Social Video Platforms with HDTV</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-pursuit-of-excellence-tips-for-shooting-with-hero5-black/"><u>[New] In Pursuit of Excellence Tips for Shooting with Hero5 Black</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-key-to-rising-roi-in-facebooks-animated-advertising-sector-for-2024/"><u>[New] The Key to Rising ROI in Facebook's Animated Advertising Sector for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-motivate-and-master-your-movements-20-top-rated-workout-tracks/"><u>2024 Approved Motivate and Master Your Movements 20 Top-Rated Workout Tracks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-nokia-c32-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Nokia C32 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-fn-key-configurations-for-windows-11-enthusiasts/"><u>Deciphering FN Key Configurations for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-samsung-galaxy-a05s-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Samsung Galaxy A05s FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-windows-ipmac-location-using-powershell/"><u>Efficient Windows IP/MAC Location Using PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-captioning-flaws-in-windows-10-computers/"><u>Eliminating Captioning Flaws in Windows 10 Computers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/essential-guide-to-premium-earbuds-free-from-cables-2024/"><u>Essential Guide to Premium Earbuds, Free From Cables 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-samsung-galaxy-s24mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Samsung Galaxy S24Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-windows-safescreen-unaltered-by-users/"><u>Keeping Windows SafeScreen Unaltered by Users</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-tiny-tinas-wonderlands-the-ultimate-pc-guide-to-a-seamlessly-functional-gameplay/"><u>Mastering Tiny Tina's Wonderlands: The Ultimate Pc Guide to a Seamlessly Functional Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-powertoys-for-efficient-file-locking/"><u>Navigating PowerToys for Efficient File Locking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorate-slow-connectivity-a-guide-to-windows-app-health/"><u>Reinvigorate Slow Connectivity: A Guide to Windows App Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-interrupted-by-exception-errors-on-windows-devices/"><u>Resolving Interrupted by Exception Errors on Windows Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/simple-steps-to-modify-screen-capture-on-macos/"><u>Simple Steps to Modify Screen Capture on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-invalid-tag-in-reparse-point-buffers/"><u>Tackling OneDrive Invalid Tag in Reparse Point Buffers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-benefits-in-maintaining-win-11-pushes/"><u>Unlocking Secrets: Benefits in Maintaining Win 11 Pushes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    