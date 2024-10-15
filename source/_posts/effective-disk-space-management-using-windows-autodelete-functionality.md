---
title: Effective Disk Space Management Using Windows' AutoDelete Functionality
date: 2024-10-08T11:58:34.064Z
updated: 2024-10-14T16:48:30.121Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Disk Space Management Using Windows' AutoDelete Functionality
excerpt: This Article Describes Effective Disk Space Management Using Windows' AutoDelete Functionality
keywords: WinDiskSpaceAutoDelete,ManageDiskSpaceWin,DeleteFilesAutoWin,OptimizeWindowsDisk,AutoFileCleanupWin,DiskFreezeWithAutoDel,WindowsSaveDiskSpace
thumbnail: https://thmb.techidaily.com/58e5d972b07e7d47a47d775672521bb7b4d26dbdad2027a1e368bc81a0dd6f11.jpg
---

## Effective Disk Space Management Using Windows' AutoDelete Functionality

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
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-from-trip-diary-to-hype-inducing-haul-the-editors-playbook/"><u>[New] 2024 Approved From Trip Diary to Hype-Inducing Haul The Editor's Playbook</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-a-bite-into-tiktoks-most-engaging-dishes/"><u>2024 Approved A Bite Into TikTok's Most Engaging Dishes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/te-video-impact-proven-youtube-seo-methods-for-2024/"><u>Elevate Video Impact Proven YouTube SEO Methods for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-limitless-windows-chatai-with-freedomgpt/"><u>Explore the Limitless Windows ChatAI: With FreedomGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-zero-to-art-starting-up-ms-paint-in-win11/"><u>From Zero to Art: Starting up MS Paint in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-repair-windows-11-assistance-tool/"><u>Guide to Repair Windows 11 Assistance Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-tweaking-your-digital-environment-windows-11-default-actions/"><u>Guide to Tweaking Your Digital Environment: Windows 11 Default Actions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-your-pcs-aware-elements-during-sleep/"><u>Guiding Your PC's Aware Elements During Sleep</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/how-to-upgrade-to-macos-catalina/"><u>How to Upgrade to macOS Catalina</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-honor-100-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Honor 100 Location by Number | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-optimized-introduction-video-tips-the-best-16-to-increase-views/"><u>In 2024, Optimized Introduction Video Tips The Best 16 to Increase Views</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-stuck-windows-updates-with-these-tips/"><u>Navigate Through Stuck Windows Updates with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-greyed-out-erase-feature-in-windows-11-settings/"><u>Overcoming Greyed Out Erase Feature in Windows 11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-req-issue-in-windows-11/"><u>Overcoming Windows Login Req Issue in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-unresponsive-game-server-connections-in-windows-via-steam/"><u>Resolving Unresponsive Game Server Connections in Windows via Steam</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/secure-ios-information-rescue-tool-effortless-data-revival-at-hand/"><u>Secure iOS Information Rescue Tool: Effortless Data Revival at Hand</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-honor-magic5-ultimate-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Honor Magic5 Ultimate IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unwrapping-ustreams-offerings-and-competitors/"><u>Unwrapping Ustream's Offerings and Competitors</u></a></li>
</ul></div>

