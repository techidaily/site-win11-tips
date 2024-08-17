---
title: The Ultimate Guide to Automated File Deletion on Windows
date: 2024-08-16T02:44:07.776Z
updated: 2024-08-17T02:44:07.776Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Guide to Automated File Deletion on Windows
excerpt: This Article Describes The Ultimate Guide to Automated File Deletion on Windows
keywords: Windows Delete Guide,AutoFileCleanup Windows,DeletedFiles Removal,Windows Erase Files,FileAutoDelete Win,SafeFileDeletion PC,QuickFilePurge Windows
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## The Ultimate Guide to Automated File Deletion on Windows

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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

## 3\. Use Task Scheduler on Windows

 Task Scheduler is a simple Windows tool that lets you easily automate your repetitive Windows tasks. Just set up the task, and the app will handle whatever you have asked it to do. When it comes to auto-deleting your files or folders, the _ForFiles_ command is what you will need to help you delete your older files or folders.

 Here's how you can automate the deletion:

1. Head to the **Start menu** search bar, type in 'task scheduler', and select the best match.
2. Right-click on **Task Scheduler Library** and select **New Folder**.
3. Put in any name and click on **OK**.
4. Right-click on the recently created folder and select the **Create Task** option.  
![task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
5. In the **Name** box, enter a name for the task.
6. Now, in the **General** tab, under the **Security options** section, select the **Run whether the user is logged on or not** option.
7. Make sure the **Do not store password** checkbox is unselected.
8. Click on the **Triggers** tab and select the **New** button.
9. Select **On a schedule** option using the **Begin the task** setting.  
![new trigger section on task scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-trigger-section-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
10. Under the **Settings** section, set up the timings of the tasks you'd like to run. Finally, click on **OK**.

 Now, head to the **Actions** tab and click on the **New** button. From the **Actions** drop-down menu, select the **Start a program** option.

 In the Program/script box, type in the following command:

`ForFiles`

![new action tab on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-action-tab-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->

 That's it—finalize the changes by clicking **OK** once again, and you will be done in no time. From here forward, your files will be automatically deleted within the specified time. Of course, if you later change your mind you can always reverse this setting by simply deleting the new folder your created in first step (which in our case, will be **New Folder 1**).

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Auto-Deleting Old Files or Folders on a Windows Computer

 Keeping unnecessary files on your computer is seldom useful. They eat up memory space, hamper your PC's performance, and clog the file organization. Setting up auto-delete instructions, with whichever method you prefer, lets you rid your PC of this extra baggage.

 However, we'd add that auto-removing files or folders from your PC is just one part of cleaning up your Windows. There are many other important hacks such as removing unused apps, terminating pointless background processes, and tweaking settings to whatever is most relevant to your situation. So, make sure you follow all the best principles for running your Windows as smoothly as possible.

 You can get rid of Windows 10 bloatware. You can sort your right click menu. You can even declutter your search results. And of course, you can clean up your desktop. If you're looking for a more passive approach, here's how to erase old files on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-discovering-facebooks-quintessential-updates/"><u>[New] 2024 Approved  Discovering Facebook's Quintessential Updates</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-navigating-video-uploads-on-social-platforms/"><u>[New] 2024 Approved  Navigating Video Uploads on Social Platforms</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-masterfb-mp4-hacking-facebook-videos-with-ease-for-2024/"><u>[New] MasterFB-MP4  Hacking Facebook Videos with Ease for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-ace-in-the-halls-boosting-youtube-traffic/"><u>[Updated] 2024 Approved  Ace in the Halls  Boosting YouTube Traffic</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-avoiding-disclosure-in-digital-footage/"><u>[Updated] 2024 Approved  Avoiding Disclosure in Digital Footage</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-building-a-vimeo-portfolio-from-the-ground-up/"><u>[Updated] 2024 Approved  Building a Vimeo Portfolio From the Ground Up</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-become-a-kinemaster-virtuoso-advanced-techniques-and-excellent-alternatives-online/"><u>[Updated] Become a KineMaster Virtuoso  Advanced Techniques & Excellent Alternatives Online</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-cyber-profile-pixelation-crafting-a-playful-look/"><u>[Updated] Cyber-Profile Pixelation  Crafting a Playful Look</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-maximizing-impact-partnering-with-influencers-on-youtube/"><u>[Updated] Maximizing Impact  Partnering with Influencers on YouTube</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-reimagining-creation-in-the-crypto-world-a-guide-to-top-nft-generating-platforms/"><u>[Updated] Reimagining Creation in the Crypto World - A Guide to Top NFT-Generating Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-scripting-journalisms-closing-statements/"><u>[Updated] Scripting Journalism's Closing Statements</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unraveling-the-secrets-of-exceptional-green-screen-filming/"><u>[Updated] Unraveling the Secrets of Exceptional Green Screen Filming</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-advancing-google-meet-sessions-implementing-effects-and-masks/"><u>2024 Approved  Advancing Google Meet Sessions  Implementing Effects & Masks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-keys-to-windows-program-harmony/"><u>4 Keys to Windows Program Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-crucial-windows-apps-making-mac-to-windows-swap-a-breeze/"><u>5 Crucial Windows Apps Making Mac to Windows Swap a Breeze</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-honor-play-40c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-strategies-to-fix-failed-security-codes-from-epic-games-on-windows/"><u>7 Strategies to Fix Failed Security Codes From Epic Games on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-ways-to-fix-the-no-servers-found-error-in-apex-legends-for-windows/"><u>9 Ways to Fix the No Servers Found Error in Apex Legends for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-close-examination-of-9-key-factors-that-advantage-pcs/"><u>A Close Examination of 9 Key Factors That Advantage PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-getting-jdk-rolled-out-in-windows-11-dev-environment/"><u>A Guide to Getting JDK Rolled Out in Windows 11 Dev Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-perfection-in-window-management-via-alomware/"><u>Achieving Perfection in Window Management via AlomWare</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/activate-a-sluggish-gpu-fan-with-ease/"><u>Activate a Sluggish GPU Fan with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-displays-that-wont-ignite-on-new-windows-versions/"><u>Addressing Displays That Won't Ignite On New Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-error-code-zero-x-in-the-mail-application-of-windows/"><u>Addressing Error Code Zero X in the Mail Application of Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-errors-caused-by-organization-managed-features-on-windows-11/"><u>Addressing Errors Caused by Organization-Managed Features on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-high-cpu-usage-dropbox-optimization-in-windows/"><u>Addressing High CPU Usage: Dropbox Optimization in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-microsofts-administrative-default-configurations-in-windows-11/"><u>Addressing Microsoft's Administrative Default Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-shown-pc-monitor-at-startup/"><u>Addressing Non-Shown PC Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-update-disruption-x712-fiasco/"><u>Addressing Windows Update Disruption: X712 Fiasco</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-and-controlling-rgb-on-windows-11-pcs/"><u>Adjusting and Controlling RGB on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-methods-for-bypassing-windows-error-0x80040610-in-office/"><u>Advanced Methods for Bypassing Windows Error 0X80040610 in Office</u></a></li>
<li><a href="https://win11-tips.techidaily.com/aid-in-correcting-windows-media-tool-issue-x8007043c/"><u>Aid in Correcting Windows' Media Tool Issue X.8007043C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-accidental-scrolling-on-your-windows-device/"><u>Avoid Accidental Scrolling on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-frustration-fixing-11s-windows-pin-hiccups/"><u>Avoid Frustration: Fixing 11'S Windows PIN Hiccups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-overlapping-defenses-opt-for-a-singular-antivirus-on-windows/"><u>Avoid Overlapping Defenses: Opt for a Singular Antivirus on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/batch-rename-made-easy-the-powerof-tools-guide/"><u>Batch-Rename Made Easy: The PowerOf Tools Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bid-farewell-to-frustration-solving-your-esc-key-issues/"><u>Bid Farewell to Frustration: Solving Your Esc Key Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-setting-up-shortcuts-for-windows-troubleshooters/"><u>Boost Efficiency: Setting Up Shortcuts for Windows Troubleshooters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-file-management-using-checkbox-for-selections-in-win11/"><u>Boost File Management: Using Checkbox for Selections in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719268444157-eliminate-non-responsive-printer-a-guide-for-wwin-issues-on-pcs/"><u>Eliminate Non-Responsive Printer: A Guide for WWin Issues on PCs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/elite-imagery-journey-maker-kit-for-2024/"><u>Elite Imagery Journey Maker Kit for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/imageslice-cutter-for-2024/"><u>ImageSlice Cutter for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-in-class-top-8-software-turning-subtitles-into-simplified-srt-format/"><u>In 2024, Best in Class  Top 8 Software Turning Subtitles Into Simplified SRT Format</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Life360 from Tracking You On Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-premium-choices-the-best-8-tripods-for-4k-cinematography/"><u>In 2024, Premium Choices  The Best 8 Tripods for 4K Cinematography</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-vivo-t2x-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Vivo T2x 5G FRP Without Computer</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-elevate-your-edits-3-ways-to-use-transitions-in-final-cut-pro/"><u>New In 2024, Elevate Your Edits 3 Ways to Use Transitions in Final Cut Pro</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamlining-content-creation-in-volume-a-detailed-guide-to-using-canva-plus-gpt-3-tools/"><u>Streamlining Content Creation in Volume: A Detailed Guide to Using Canva + GPT-3 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328507288-uncomplicated-start-menus-say-no-to-ads/"><u>Uncomplicated Start Menus - Say No to Ads!</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-10-best-free-websites-to-watch-cartoons-online/"><u>Updated 10 Best Free Websites to Watch Cartoons Online</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Motorola Moto G04? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>