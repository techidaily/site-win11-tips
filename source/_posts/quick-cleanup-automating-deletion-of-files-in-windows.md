---
title: "Quick Cleanup: Automating Deletion of Files in Windows"
date: 2024-07-12T17:40:25.297Z
updated: 2024-07-13T17:40:25.297Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Cleanup: Automating Deletion of Files in Windows"
excerpt: "This Article Describes Quick Cleanup: Automating Deletion of Files in Windows"
keywords: FileDeletionAutomation,WindowsCleanUpScript,QuickFileRemoval,AutoRemoveFilesWin,SpeedyWindowsClear,EfficientFileDelete,FastWindowsCleanup
thumbnail: https://thmb.techidaily.com/8e351a495ce579ab157428c084339d1c33794d9d42c306afbe86c4e9778edcf8.jpg
---

## Quick Cleanup: Automating Deletion of Files in Windows

 We all know how easy it is to delete files and send them to the Recycle Bin. But wouldn't it be great if Windows automatically emptied the bin for us? Fortunately, you can configure your system to do just that.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.

## 1\. How to Automate the Recycle Bin Using the System Settings

 It's easy to configure Windows to empty the recycle bin automatically. All you need to do is open System settings, fiddle with a few things, and you're done.

 However, this feature applies only to the current user account. Other users on the same computer won't have their Recycle Bin emptied automatically until they adjust this setting. In other words, if you're using a shared computer, it won't affect anyone else.

 Here's how to do it:

1. [Open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left panel, select the **System** tab.
3. Scroll down and click on **Storage** on the right-hand side. Here, you will find various computer data storage and management options.  
![Stoage in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stoage-in-system-settings.jpg)
4. Now, you will see a toggle switch under **Storage Sense**. If it's turned off, click to switch it on. This feature enables Windows to delete no longer needed files automatically.  
![Turn on Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/turn-on-storage-sense.jpg)
5. Once Storage Sense is active, click the tiny arrow next to it to expand the options.
6. On the next screen, you'll find an option that says, **Delete files in my recycle bin if they have been there for over**. Click the drop-down menu beside this and select the duration, after which Windows should empty the recycle bin automatically.
7. Select **1 day** if you want Windows to delete these items daily. Or choose another option that suits your needs better.  
![Configure Storage Sense](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/configure-storage-sense.jpg)
8. You can also configure the system to delete downloaded files that haven't been used for several days. To do so, click the **Delete files in my Downloaded folder if they haven't been opened for more than** drop-down menu and select the desired option.

 Once you're done, close the Settings window. Windows will automatically empty your Recycle Bin from now on.

## 2\. How to Automate the Recycle Bin Using the Task Scheduler

 If you want more control over the process, you can use Windows Task Scheduler to empty your Recycle Bin. Here's how:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **taskschd.msc** and hit **Enter** or click **OK**. Doing this [opens the Task Scheduler program](https://www.makeuseof.com/windows-11-open-task-scheduler/).
3. On the left-hand side of the window, select **Task Scheduler Library**.
4. Now, click **Create Basic Task** from the right-hand panel. It will open another window where you can configure your task settings.  
![Create Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-basic-task.jpg)
5. Enter a name for your task (e.g., Empty Recycle Bin) and a brief description if you want. Then, click the **Next** button.

1. The following window will ask you to select the frequency when Windows should empty your Recycle Bin. You can choose Daily, Weekly, Monthly, or One time only. Once you've chosen your preferred frequency, click **Next**.  
![Create a Basic Task](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/create-a-basic-task.jpg)
2. After that, set the start date and time for your task. Also, select **Recur every** to specify the total duration of each cleaning session. Then, click **Next**.  
![Start Date and Time in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-date-and-time-in-task-wizard.jpg)
3. You must specify what action Windows should perform when this task runs. Click on the **Start a program** option and click **Next** again.  
![Start a program in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/start-a-program-in-task-wizard.jpg)
4. In the **Program/script** box, type _**C:\\Windows\\System32\\cmd.exe**_. Then, in the **Add arguments (optional)** field, type the following command:  
/c "echo Y|PowerShell.exe -NoProfile -Command Clear-RecycleBin"  
![Write Program or Script in Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/write-program-or-script-in-task-wizard.jpg)
5. Running this command will delete your Recycle Bin content. Click **Next** to continue.
6. Now, you can review your settings and tick **Open the Properties dialog for this task when I click Finish** if you want to make any changes. When done, hit the **Finish** button.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/finish-task-wizard.jpg)

 Once you're done, close the Task Scheduler window. From now on, Windows will empty your Recycle Bin according to your specified frequency.

## Automate the Recycling Process on Windows

 To keep your computer running smoothly, you must empty your Recycle Bin regularly. However, the process can be tedious and time-consuming. Fortunately, Windows provides some easy ways to automate this task, either through Windows Settings or Task Scheduler.

 Let's look at the different ways to auto-empty the Recycle Bin on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/5-essential-tricks-for-a-better-windows-11-search/"><u>5 Essential Tricks for a Better Windows 11 Search</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-facebook-featured-best-10-music-clips-today/"><u>[New] Facebook Featured  Best 10 Music Clips Today</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-deciphering-the-divergent-aspects-of-youtubes-and-dailymentions/"><u>[New] In 2024, Deciphering the Divergent Aspects of YouTubes & DailyMentions</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-mastering-the-art-of-larger-video-posts-in-instagram/"><u>In 2024, Mastering the Art of Larger Video Posts in Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-symphony-of-sounds-taming-irq-noise/"><u>A Symphony of Sounds: Taming IRQ Noise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-method-for-clean-booting-on-windows-11-systems/"><u>A Step-by-Step Method for Clean Booting on Windows 11 Systems</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/frame-rates-speed-and-wondershare-filmora/"><u>Frame Rates, Speed, and Wondershare Filmora</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-spice-up-your-videos-7-premium-royalty-free-audio-clips/"><u>[New] Spice Up Your Videos  7 Premium, Royalty-Free Audio Clips</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-leading-video-brightness-and-gamma-editors/"><u>New In 2024, Leading Video Brightness and Gamma Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363489312-solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-piceditorpro-assessment-complete-review/"><u>[New] In 2024, PicEditorPro Assessment – Complete Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-proactive-steps-to-overcome-no-servers-found-in-apex-legends-(156-chars/"><u>8 Proactive Steps to Overcome 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6plus-strategies-for-a-superior-windows-11-taskbar-use/"><u>6+ Strategies for a Superior Windows 11 Taskbar Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719366332809-trouble-at-clipcraft-unravel-fixes-today/"><u>Trouble at ClipCraft? Unravel Fixes Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapt-windows-sleep-timer-to-suit-you/"><u>Adapt Window's Sleep Timer to Suit You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-system-called-fails-on-windows-1011/"><u>Addressing System Called Fails on Windows 10/11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/revolutionary-ios-gaming-apples-best-vr-apps-for-2024/"><u>Revolutionary iOS Gaming  Apple's Best VR Apps for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-gamers-manual-to-identifying-top-rated-audio-alteration-devices/"><u>The Gamers Manual to Identifying Top-Rated Audio Alteration Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-polishing-pixels-8-pro-photo-frames-for-images-online/"><u>[New] Polishing Pixels  8 Pro Photo Frames for Images Online</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-epic-virtual-truths-top-30-metaverse-reflections-arvr/"><u>[New] 2024 Approved  Epic Virtual Truths  Top 30 Metaverse Reflections [AR/VR]</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unleash-your-creativity-simple-video-editing-with-microsoft-on-windows/"><u>Updated Unleash Your Creativity Simple Video Editing with Microsoft on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-eradicating-d3d11-errors-in-w11-and-w10/"><u>A Step-by-Step Approach to Eradicating D3D11 Errors in W11 & W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-microsoft-can-improve-phone-link-on-windows-11/"><u>7 Ways Microsoft Can Improve Phone Link on Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-streamline-your-music-library-mp3s-direct-to-youtube-playlist/"><u>In 2024, Streamline Your Music Library  MP3s Direct to YouTube Playlist</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-11-pro-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme 11 Pro Phone and Remove Locked Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-isdonedll-issue-on-w11-and-11x-systems/"><u>Addressing the ISDone.dll Issue on W11 & 11X Systems</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-top-7-animated-gif-text-makers/"><u>New In 2024, Top 7 Animated GIF Text Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-simple-guide-to-adjusting-mask-in-windows-11/"><u>A Simple Guide to Adjusting MASK in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-solution-manual-windows-rainmeter-problems-decoded/"><u>A Comprehensive Solution Manual: Windows Rainmeter Problems Decoded</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-acoustic-link-for-speakers/"><u>2024 Approved  Innovative Acoustic Link for Speakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-folder-and-file-unity-a-windows-exploration/"><u>Achieving Folder & File Unity: A Windows Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-lunar-client-startup-failures-on-windows-systems/"><u>Addressing “Lunar Client Startup Failures” On Windows Systems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-facebooks-recent-views-uncovered-for-you/"><u>2024 Approved  Facebook’s Recent Views Uncovered for You</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-professional-results-for-free-top-4k-video-editing-software-choices/"><u>Updated In 2024, Professional Results for Free Top 4K Video Editing Software Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320814373-reclaim-control-of-freeze-shift-keys/"><u>Reclaim Control of Freeze Shift Keys.</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oppo-f23-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Oppo F23 5G phone? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719357869666-quick-remedies-to-address-compatibility-issues-on-windows-xp/"><u>Quick Remedies to Address Compatibility Issues on Windows XP</u></a></li>
</ul></div>
