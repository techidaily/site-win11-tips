---
title: "Unclutter Your Disk: Guide to Windows 11'S Auto-Deletion Techniques"
date: 2024-10-26T18:08:59.391Z
updated: 2024-11-01T17:00:51.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unclutter Your Disk: Guide to Windows 11'S Auto-Deletion Techniques"
excerpt: "This Article Describes Unclutter Your Disk: Guide to Windows 11'S Auto-Deletion Techniques"
keywords: Disk Cleanup Tips,Windows Deletes Automatically,Manage Disk Space Efficiently,Auto-Delete Techniques Guide,11 Storage Optimization,Unclutter Disk Settings,Windows 11 Cleanup Strategies
thumbnail: https://thmb.techidaily.com/288c4a8a533b0f1094aca3a28c5db0188ea8b5a3c3aca95005c1c84fe62729c2.jpg
---

## Unclutter Your Disk: Guide to Windows 11'S Auto-Deletion Techniques

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
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975816/19272" target="_top" id="1975816">
  <img src="//a.impactradius-go.com/display-ad/19272-1975816" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975816/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094476/7443" target="_top" id="2094476">
  <img src="//a.impactradius-go.com/display-ad/7443-2094476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094476/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-streamline-your-instagram-content-free-mp4-exporters-for-windowsmac-users/"><u>[New] Streamline Your Instagram Content Free MP4 Exporters for Windows/Mac Users</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-finding-the-right-mic-a-guide-for-multifaceted-yt-channels-for-2024/"><u>[Updated] Finding the Right Mic A Guide for Multifaceted YT Channels for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/apple-iphone-xs-icloud-activation-lock-bypass-by-drfone-ios/"><u>Apple iPhone XS iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-top-displayed-calculator-on-pcs/"><u>Ensuring Top-Displayed Calculator on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-edits-for-enhanced-user-control-in-win11/"><u>Essential Edits for Enhanced User Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enable-windows-auditory-service-auto-restart-feature/"><u>How to Enable Windows Auditory Service Auto-Restart Feature</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-samsung-galaxy-m34-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Samsung Galaxy M34 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-a14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Samsung Galaxy A14 4G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-upgrade-for-ancient-computers-running-windows-11-using-to-go-and-rufus/"><u>Instant Upgrade for Ancient Computers: Running Windows 11 Using To Go & Rufus</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ize-content-collaboration-in-youtube-for-increased-engagement/"><u>Optimize Content Collaboration in YouTube for Increased Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-display-in-windows-11/"><u>Overcoming Missing Display in Windows 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/realtek-hd-audio-problem-solved-reconnect-and-restore-your-sound/"><u>Realtek HD Audio Problem Solved: Reconnect and Restore Your Sound</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regular-maintenance-rebuilding-win-icon-cache/"><u>Regular Maintenance: Rebuilding Win Icon Cache</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrieve-your-wingman-copilot-in-ws11s-struggle/"><u>Retrieve Your Wingman (Copilot) In WS11's Struggle</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/mlining-the-process-of-finding-your-own-musical-compilation-on-youtube-for-2024/"><u>Streamlining the Process of Finding Your Own Musical Compilation on Youtube for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-best-bargain-in-big-screens-an-in-depth-review-of-the-tcl-50s425-the-2019s-value-packed-4k-roku-tv/"><u>The Best Bargain in Big Screens - An In-Depth Review of the TCL 50S425, the 2019'S Value-Packed 4K Roku TV</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-captcha-on-steam-for-successful-logins/"><u>Unblocking CAPTCHA on Steam for Successful Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-your-displays-potential-with-these-simple-steps/"><u>Unlock Your Display's Potential with These Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-high-fidelity-audio-dolby-atmos-integration-steps/"><u>Unlocking High-Fidelity Audio: Dolby Atmos Integration Steps</u></a></li>
</ul></div>

