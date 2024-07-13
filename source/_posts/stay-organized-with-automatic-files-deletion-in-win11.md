---
title: Stay Organized with Automatic Files Deletion in Win11
date: 2024-07-12T17:15:30.405Z
updated: 2024-07-13T17:15:30.405Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-strategy-to-reactivate-winget-on-w11/"><u>A Step-by-Step Strategy to Reactivate Winget on W11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-beam-your-best-lol-playing-moments-onto-screen-3-ways/"><u>[New] 2024 Approved  Beam Your Best LOL Playing Moments Onto Screen (3 Ways)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-itel-p55t-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Itel P55T</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msvcrt120dll-omission-on-pcs/"><u>Addressing Msvcrt120dll Omission on PCs</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-best-of-the-best-top-ipad-video-editing-software/"><u>2024 Approved The Best of the Best Top iPad Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comparative-look-at-windows-most-utilized-software-tools/"><u>A Comparative Look at Windows' Most Utilized Software Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-the-magic-behind-film-plots/"><u>Unveiling the Magic Behind Film Plots</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tranquil-tracks-easy-volume-diminution-via-garageband/"><u>2024 Approved  Tranquil Tracks  Easy Volume Diminution via Garageband</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-xiaomi-mix-fold-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nokia-c12-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nokia C12 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/flawless-friending-on-instagram-best-free-safe-mobile-aid-iosandroid/"><u>Flawless Friending on Instagram - Best Free, Safe Mobile Aid (iOS/Android)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-num-caps-lock-signifiers-in-win11-systemtray/"><u>Adding Num, Caps Lock Signifiers in Win11 SystemTray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-parameter-loaderror-87/"><u>Addressing Incorrect Parameter LoadError 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-locked-windows-11-themes-through-registry-expertise/"><u>Accessing Locked Windows 11 Themes Through Registry Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-11s-network-settings/"><u>Accessing Windows 11'S Network Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerating-battery-performance-add-custom-alerts-to-windows-11/"><u>Accelerating Battery Performance: Add Custom Alerts to Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-samsung-galaxy-s24-ultra-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Samsung Galaxy S24 Ultra FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-visual-journey-customizing-your-windows-11-monitor-walls/"><u>A Visual Journey: Customizing Your Windows 11 Monitor Walls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-take-when-facing-invalid-name-on-pc/"><u>Actions to Take When Facing Invalid Name on PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploiting-slow-motion-magic-in-phantom/"><u>[New] Exploiting Slow-Motion Magic in Phantom</u></a></li>
<li><a href="https://win11-tips.techidaily.com/address-unsigned-files-issue-for-updated-pcs/"><u>Address 'Unsigned' Files Issue for Updated PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-microsoft-edge-fix-for-w10w11/"><u>Accelerate Your Microsoft Edge: Fix for W10/W11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/effortless-conversion-of-srt-to-subtitles-subc-for-2024/"><u>Effortless Conversion of SRT to Subtitles (SUBC) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-how-to-for-hypertuned-windows-11-homes/"><u>A Detailed How-To for Hypertuned Windows 11 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719289062860-rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-ui-skills-with-windows-11-widgets/"><u>Accelerate Your UI Skills with Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-key-components-not-found-error-in-win11-environment/"><u>Addressing Key Components Not Found Error in Win11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-thoroughly-detailed-guide-to-windows-boot-options/"><u>A Thoroughly Detailed Guide to Windows Boot Options</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-captureconqueror-a-comprehensive-guide-to-screen-recording/"><u>2024 Approved  CaptureConqueror  A Comprehensive Guide to Screen Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-unlocking-windows-11s-credential-vault/"><u>A Comprehensive Guide to Unlocking Windows 11’S Credential Vault</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/1714925143590-new-crafting-masterpieces-on-your-mac-an-in-depth-look-at-the-leading-daws-of-2-written-in-markdown-format-with-each-title-as-a-separate-subheading-heres-ho/"><u>New Crafting Masterpieces on Your Mac An In-Depth Look at the Leading DAWs of 2 Written in Markdown Format, with Each Title as a Separate Subheading. Heres How It Would Look Like for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-sharpen-aesthetic-focus-learning-border-techniques-for-insta-videos/"><u>[Updated] Sharpen Aesthetic Focus  Learning Border Techniques for Insta-Videos</u></a></li>
</ul></div>
