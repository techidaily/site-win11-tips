---
title: Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery
date: 2024-07-12T16:55:01.868Z
updated: 2024-07-13T16:55:01.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery
excerpt: This Article Describes Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery
keywords: Storage Strategy Guide,Disk Usage Insights,Windows Command Proficiency,Data Management Skills,Optimizing Storage Space,Filesystem Efficiency,Managing Hard Drive Capacity
thumbnail: https://thmb.techidaily.com/b4646e6c7dd57e63be8305e5fc613622e6d7e19134ef2ba8ba5fe989f296bf0b.png
---

## Becoming a Storage Strategy Expert with Windows' DiskUsage Commands Mastery

 The DiskUsage.exe tool can be used to analyze the contents of any drive or folder on Windows 11\. DiskUsage is accessed from the command line and includes many options for filtering and refining the file data that can be output. In certain situations, this can make it far more useful than GUI tools like Storage Sense.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.

## View Disk Usage of Any Drive or Folder

 The simplest way to use the DiskUsage command line tool is to get an overview of how space is currently used in almost a drive or folder. We have used the tool on Windows 11, but it is also available on Windows 10\.

1. Run the Command Prompt as an admin. If you need help, check out [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. In Command Prompt type **DiskUsage** followed by the path to the drive or folder you want to analyze.
3. For example, to view the disk usage of the Pictures folder, type: **DiskUsage C:\\Users\\UserName\\Pictures**, and press **Enter**.  
![The disk usage command in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-cmd.jpg)
4. To see the SizeOnDisk number in a human-readable format, e.g. KB, MB, or GB, add **/h** to the end of the command.
5. In our example, this looks like **DiskUsage C:\\Users\\UserName\\Pictures /h**.  
![Disk usage date displayed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-data.jpg)

 You can use DiskUsage to analyze any folder in the same way. You can even check internal and external drives, including the C: drive. Bear in mind that analyzing a drive such as C: will spew out a huge list of files and folders in DiskUsage.

 If using DiskUsage.exe seems too complicated, you can easily view how disk space is being used with [Storage Sense](https://www.makeuseof.com/windows-11-storage-sense-guide/).

## List All Files Larger Than a Specified Size

 You can refine the data displayed in DiskUsage based on file size. So if, for example, you only want to include files over 500MB, you can set it to ignore smaller files.

1. To only include files above a specific size, you need to add the minFileSize option to the command.
2. As an example: **DiskUsage /minFileSize=6553600 C:\\Users\\UseName\\Downloads /h**.
3. This will only look for files in Downloads larger than 50MB and then display the disk space those files occupy in that location.
4. The file size number must be entered in bytes, so you might have to convert MB to Byte using an online conversion tool.

 For a more detailed view of large files, including file name as well as size, you can use the **/u** command modifier. This allows you to list a defined number of the largest files in the drive or folder.

1. To do this type: **DiskUsage C:\\Users\\UserName\\Downloads /h /u=15**.
2. The 15 largest files in the Downloads folder will now be listed in Command Prompt.  
![file data listed in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-list.jpg)
3. You can replace the number with any other you want to use. For example, to see the top 5 files taking up space, use **/u=5**.
4. Make sure to include the **/h** option so that the output is in a format that's easy to read.

 After identifying what is taking up the most space, you can use any one of these [methods to delete large files](https://www.makeuseof.com/windows-11-delete-select-files/).

## Additional DiskUsage Command Options

 The DiskUsage tool contains several other useful options that you can use to filter the output. You can filter by filename, display reserved space, or the largest directories within the folder.

 For example, to filter by filename add **/n=installer** to the end of the command to display only files that contain the word installer.

 You can see a complete list of the options by typing **DiskUsage /?** and pressing **Enter**.

![A list of DiskUsage options in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/diskusage-options.jpg)

## Analyze Drive Space With DiskUsage

 Many of the available command line tools are extremely useful for maintaining and managing your Windows PC. And as this guide shows, DiskUsage.exe is a powerful alternative to graphical UI tools such as Storage Sense if you want to really dig down into how your drive space is being used.

 Here's how to start using DiskUsage.exe to view and analyze how the space in your drives is being used.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://easy-unlock-android.techidaily.com/best-honor-x9b-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Honor X9b Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-user-interface-add-psoft-tools-to-windows-11/"><u>Boosting User Interface: Add PSoft Tools to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-check-your-graphics-card-model-on-windows-11/"><u>3 Quick Ways to Check Your Graphics Card Model on Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-a-compre-point-strategies-for-effortless-story-posting/"><u>[Updated] 2024 Approved  A Compre Point  Strategies For Effortless Story Posting</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-rising-to-fame-creating-the-ultimate-facebook-song-video-for-2024/"><u>[Updated] Rising to Fame  Creating the Ultimate Facebook Song Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-windows-camera-problems-with-expert-tips/"><u>Tackle Windows Camera Problems with Expert Tips</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-ace-guide-to-constructing-virtual-classroom-headlines/"><u>[Updated] Ace Guide to Constructing Virtual Classroom Headlines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-laptop-onoff-trick-for-energy-conservation/"><u>Boost Your Laptop: On/Off Trick for Energy Conservation</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-xiaomi-redmi-note-13-5g-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Xiaomi Redmi Note 13 5G? Here is How | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unzipping-challenge-managing-multiple-compressed-files-in-a-snap/"><u>Unzipping Challenge: Managing Multiple Compressed Files in a Snap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-manage-disks-keyways-into-windows-11s-storage-manager/"><u>Swiftly Manage Disks: Keyways Into Windows 11'S Storage Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-photos-apps-generative-erase-is-actually-great/"><u>The Windows Photos App's Generative Erase Is Actually Great</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-eagleeye-hd-recordingtool/"><u>[Updated] In 2024, EagleEye HD RecordingTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blend-in-with-the-background-hide-taskbars-language-bar-win11/"><u>Blend in with the Background: Hide Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-local-user-policies-a-guide-to-windows-11-and-11-systems/"><u>Adjusting Local User Policies: A Guide to Windows 11 & 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719295110946-get-a-free-self-hosted-gptclone-with-gpt4all/"><u>Get a Free, Self-Hosted GPTClone with GPT4All</u></a></li>
<li><a href="https://audio-editing.techidaily.com/extensive-info-on-vimeo-video-aspect-ratio-detailled/"><u>Extensive Info on Vimeo Video - Aspect Ratio Detailled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-to-manipulate-windows-11-sleepwake/"><u>Workarounds to Manipulate Windows 11 Sleep/Wake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-technical-odyssey-embracing-hdr-in-windows-11-environments/"><u>A Technical Odyssey: Embracing HDR in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-multiple-users-ms-logins-on-pc/"><u>Tackling Multiple Users' MS Logins on PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Motorola Edge 40 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-what-sets-ai-hardware-on-a-distinct-path/"><u>Analyzing What Sets AI Hardware on a Distinct Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-cross-device-note-utilization-guide/"><u>Windows 11 Cross-Device Note Utilization Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-navigating-the-best-practices-for-fb-video-advertising/"><u>[New] In 2024, Navigating the Best Practices for FB Video Advertising</u></a></li>
<li><a href="https://win11-tips.techidaily.com/traverse-backward-commanding-windows-11-history/"><u>Traverse Backward: Commanding Windows 11 History</u></a></li>
<li><a href="https://win11-tips.techidaily.com/click-without-the-rush-learn-to-deactivate-mouse-acceleration-windows-style/"><u>Click Without the Rush: Learn to Deactivate Mouse Acceleration Windows Style</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snapchat-wizardry-flipping-your-video-narrative/"><u>In 2024, Snapchat Wizardry  Flipping Your Video Narrative</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-discover-the-best-top-10-free-and-paid-plugins-for-final-cut-pro-x-editors/"><u>New Discover the Best Top 10 Free and Paid Plugins for Final Cut Pro X Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-your-inboxes-connecting-gmail-with-windows-outlook-app/"><u>Uniting Your Inboxes: Connecting Gmail with Windows' Outlook App</u></a></li>
</ul></div>
