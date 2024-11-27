---
title: Enhance Disk Space Efficiency with Auto Delete on Windows 11
date: 2024-11-26T16:05:32.178Z
updated: 2024-11-27T17:20:23.087Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhance Disk Space Efficiency with Auto Delete on Windows 11
excerpt: This Article Describes Enhance Disk Space Efficiency with Auto Delete on Windows 11
keywords: Save Disk Space (W11),Auto Delete Feature,Storage Optimization,Windows Space Management,Clear Unused Files (Windows 11),Efficient Data Handling,Reduce Disk Waste (W11)
thumbnail: https://thmb.techidaily.com/0be1e99c17baad20df818e64c74b29c212a06e76be2a092d41b1fc888150e8a5.jpeg
---

## Enhance Disk Space Efficiency with Auto Delete on Windows 11

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Go to **Settings > System > Storage**.
2. Toggle on the **Storage Sense** feature.
3. Then, click **Configure Storage Sense or run it now**.
4. Under **Temporary Files**, set up your desired time frames fore deleting files in the recycle bin and files in your Downloads folder.  
![storage sense in windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/storage-sense-in-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Not all files in the Downloads folder will be deleted after the set time; just those that haven't been opened. This means if you download a file and want to open it later, it will still be deleted after the set time. If you turn this setting on, you should move anything out of the Downloads folder that you intend to keep.

 If you want, you can always turn off the setting by simply disabling the **Storage Sense** button later on.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Deleted Old Files or Folders With the Command Prompt

 Like most things on Windows, you can use the Command Prompt here as well. A replacement for the easy pin-and-point graphical user interface, the Command Prompt works with simple text-based commands to help you perform different admin functions and fix various troubleshooting issues on Windows.

 Here's how you can use it to fix your storage issues via the _ForFiles_ command on Windows:

1. Head to the **Start menu** search bar, type in 'cmd', and run the CMD as an administrator.
2. Now, to delete the files that you haven't modified in 30 days, type in the following command and hit **Enter**:  
`ForFiles /p "C:\path\to\folder"/s /d -30 /c "cmd /c del /q @file"`

 The "C:\\path\\to\\folder" and /d -30 here refer to the folder path from where you want to delete files and the specific time for which you'd like to delete your file. Replace them with the settings that suit you.

![command prompt on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/command-prompt-on-windows.jpg)

 Your files will be removed as quickly as soon as you hit the above commands.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevating-the-end-scene-in-youtube-productions-for-2024/"><u>[New] Elevating the End Scene in YouTube Productions for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-instagram-time-keeper-learning-to-rewind-for-2024/"><u>[New] The Instagram Time Keeper Learning to Rewind for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-youtube-srt-extraction-three-practical-approaches-for-downloading/"><u>[Updated] 2024 Approved YouTube SRT Extraction Three Practical Approaches for Downloading</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-maximize-saving-tiktok-videos-android-and-ios-hacks/"><u>[Updated] In 2024, Maximize Saving TikTok Videos Android & iOS Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fastening-your-purchase-speed-for-ms-store-products/"><u>Fastening Your Purchase Speed for MS Store Products</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reset-the-windows-search-settings-in-windows-11/"><u>How to Reset the Windows Search Settings in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On OnePlus Ace 2V? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/movavis-free-online-video-converter-convert-mov-to-mp4-and-more/"><u>Movavi's Free Online Video Converter: Convert MOV to MP4 & More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-most-popular-task-organizers-on-windows/"><u>Navigating the Most Popular Task Organizers on Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-non-startup-for-urban-planner-pro-2-expert-tips-and-tricks/"><u>Solving Non-Startup for Urban Planner Pro 2: Expert Tips and Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-dealing-with-no-click-space-in-win11/"><u>Strategies for Dealing with No-Click Space in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-recover-from-unresponsive-spotify-win11-errors/"><u>Strategies to Recover From Unresponsive Spotify Win11 Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-path-to-inter-device-unity-android-plus-windows-guide/"><u>The Path to Inter-Device Unity: Android + Windows Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/tips-for-finding-christian-choir-songs-online-and-personalizing-them-for-2024/"><u>Tips for Finding Christian Choir Songs Online & Personalizing Them for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Motorola Moto G 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-outlook-integration-fix-non-sync-issue/"><u>Unlock Windows Outlook Integration: Fix Non-Sync Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-efficient-methods-to-resolve-common-anydesk-errors-in-os/"><u>Unlocking Efficient Methods to Resolve Common AnyDesk Errors in OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    