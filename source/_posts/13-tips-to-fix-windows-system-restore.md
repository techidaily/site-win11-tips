---
title: 13 Tips to Fix Windows System Restore
date: 2024-07-12T17:46:44.983Z
updated: 2024-07-13T17:46:44.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 13 Tips to Fix Windows System Restore
excerpt: This Article Describes 13 Tips to Fix Windows System Restore
keywords: Windows Restore Fix Guide,System Repair Tools,Troubleshoot Windows Restore,Restore Points Solution,Fixing System Errors,Windows Recovery Methods,Optimize System Restore
thumbnail: https://thmb.techidaily.com/5d29a63e1845651f830e0124c103033fe9ea8d7a1b11e86673f2ac375d1ce40d.jpeg
---

## 13 Tips to Fix Windows System Restore

 System Restore is one of the most useful Windows features, as it allows you to revert your computer to an earlier state, in case something goes wrong. This can be a lifesaver as long as it works.

 There’s a chance you will figure out that System Restore stopped working only when you need it, which can add an extra layer of frustration to your existing issues. Many different factors can affect its performance, but these pointers should help you get to the root of the problem.

## 1\. Create a System Restore Point Manually

 Your first port of call during System Restore irregularities should be to manually create a System Restore point. While this is unlikely to solve the problem outright, you may well be presented with an error message that makes it easier to diagnose what's wrong.

![Create restore point manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-restore-point-manually-1.jpg)

 To get started, type **Restore Point** into your search bar and click on the result titled **Create a restore point**. Click the button labelled **Create** and choose a name, then wait for the process to complete and see if an error message pops up.

## 2\. Check System Restore is Active on All Volumes

 System Restore may simply not be activated on your computer. This is particularly relevant if you're using more than one drive, or have recently swapped your system storage from one volume to another, as drives can have their protection turned on and off individually.

![Check system restore status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-restore-status-1.jpg)

 Type **Restore Point** into the search bar and click on **Create a Restore Point**. You'll see the Available Drives listed under the Protection Settings subheading, alongside a column telling you whether or not they're protected.

 To change this setting, click on the desired drive to highlight it and then click on **Configure**. A radio toggle will allow you to turn System Restore protection on or off.

 As with almost any other technical issue, turning System Restore off and on again is well worth a try.

## 3\. Disable Antivirus Software

 Using a [reliable piece of antivirus software](https://www.makeuseof.com/windows-11-antivirus-apps/) is a great way to keep your system protected against malware and other undesirable installs, but sometimes this kind of utility can cause problems for other tasks.

 If you're facing difficulties with System Restore, briefly disable your antivirus software early on during your troubleshooting — it may well fix things.

## 4\. Check Your Disk Space Allocation

 Your Restore Points will fail if there isn't enough space allocated for their storage. To see how much space you have assigned to this task, enter **Restore Point** into the search bar and open the entry titled **Create a restore point**.

![Check System Restore disk allocation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restore-disk-allocation-1.jpg)

 Click the Configure button and you'll be able to tweak your **Disk Space Usage**. Try using the slider to increase your allocated space, then create a new Restore Point to see whether it has had the desired effect.

## 5\. Manually Delete Restore Points

 As we’ve mentioned, System Restore will fail to create a new restore point if there’s no available storage space on your computer. However, you can [manually delete older restore points](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) that you no longer need to free up some space for System Restore to work.

## 6\. Confirm Essential Services are Running

 System Restore relies on a few different services to do its job; without them, it can't function. Fortunately, it's very easy to check whether or not they are active by typing **Services** into the search bar and opening the app.

 You'll be presented with a long list of all the services that are loaded onto your computer, but you're just looking for three:

* Microsoft Software Shadow Copy Provider Service
* Task Scheduler
* Volume Shadow Copy

 Make sure the **Name** column is sorted alphabetically, then skim through the list to find these three services. You need to confirm that all of them are **Running** and are set to **Automatic** in the **Startup Type** column.

![Check System Restore services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-restore-services-1.jpg)

## 7\. Run Check Disk via Command Prompt

 Check Disk is a system tool built into Windows that can verify the integrity of a file system, and fix logical errors. To access the utility, in the Start menu search bar, search for **command prompt** and select **Run as administrator**.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1.jpg)

 To run Check Disk, input the following command:

chkdsk /f /r

 You might also want to try the similar System File Checker tool with this command:

sfc /scannow

## 8\. Boot Into Safe Mode

 Problems affecting System Restore can often be traced back to services and drivers from a source other than Microsoft. Safe Mode strips your computer's abilities back to the bare essentials, meaning that those processes won't interfere with your procedure.

 You'll still have to find the culprit if you want to fix the issue permanently, but dropping into Safe Mode can be a useful stopgap if you're in a bind.

![Boot your computer in Safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/safe-mode-1.jpg)

 To boot into Safe Mode, type **msconfig** into the search bar and open **System Configuration**. Head to the **Boot** tab and tick the checkbox marked **Safe boot**, with the radio toggle set to **Minimal**. Then try running System Restore from Safe Mode.

 If this didn't work for you, there are [other methods to boot your computer into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

## 9\. Try Selective Startup

 Selective Startup is a similar tool to Safe Mode, in that it reduces the amount of processes running on your computer to make it easier to diagnose problems. Type **System Configuration** into the search box and open the top result to get started.

![Use selective startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/selective-startup-1.jpg)

 You can check and uncheck the **Load system services** and **Load startup items** boxes to customize how your computer behaves at startup. For more information on using Selective Startup to troubleshoot, refer to Microsoft's guide to the process.

## 10\. Consult the Event Viewer

 You might be able to find some clues about errors pertaining to System Restore processes by delving into the Event Viewer. Search for the utility and open it up to get started — you'll need to expand the **Windows Logs** folder, then click on **Applications**.

![Check Windows event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/event-viewer-1.jpg)

 Scroll through the results to find anything with **Error** in the **Level** column. Click on an individual event to display its description, and see if that offers up any reason that it might be connected to System Restore. You can do a Google search for any related errors that you find to see what the best course of action is.

## 11\. Check Your Timing

 As simple as it might sound, your System Restore strife might be caused by something as straightforward as your computer being asleep when it's scheduled to create a new image. Your PC won't be able to wake itself up to do the job, unless you have a handy tool called [Restore Point Creator](http://www.downloadcrew.com/article/31634-restore%5Fpoint%5Fcreator).

![Restore Point Creator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restore-point-creator-1.jpg)

 Among a host of other advantages, Restore Point Creator offers users the opportunity to schedule the task for the future, and instruct their system to wake up at that specified time. This option is available by navigating to **System Restore Point Utilities** \> **Schedule creation of System Restore Points** and then checking the box labelled **Wake computer if the system is sleeping**.

 One point to remember is that Restore Point Creator uses Task Scheduler to implement this feature. As such, you'll have to check that your computer is compatible with the tool.

## 12\. Employ a Third-Party Alternative

 If you really can't fix System Restore, you could always try a different solution. This won't help anyone in the midst of a crisis right now, but for those readers that are just setting up their defenses, a backup plan could pay dividends down the line.

 You might also check out these [rescue and restore disks for your Windows System Restore](https://www.makeuseof.com/tag/5-best-rescue-disks-windows-system-restore/).

## 13\. Factory Reset Your Computer

 If none of the above solutions fixed System Restore, and you’re stuck with a system full of bugs and glitches, you should factory reset your computer. This is a bold move, as it will return your PC to the state it was when you bought it.

 Before doing so, make sure to [back up any personal data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) you might need, so long as you’re able to.

## Fixing Windows System Restore

 There are plenty of reasons why System Restore might stop working, so it might be challenging to pin down the exact cause. However, with a bit of patience, the above tips will help you fix the issue so you can load a restore point any time you need it.

 If you want to create restore points faster, you can add the option to the Windows context menu.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-your-w11-browser-by-altering-startup/"><u>Personalize Your W11 Browser by Altering Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-proxy-settings-glitch/"><u>Quick Fix for Windows Proxy Settings Glitch</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-poco-x5-pro-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-winning-strategies-and-hashtags-for-youtubes-best-freefirers/"><u>2024 Approved  Winning Strategies & Hashtags for YouTube's Best FreeFirers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-modifying-windows-files/"><u>Mastering the Art of Modifying Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-virtual-memory-for-performance-gain/"><u>Revamping Virtual Memory for Performance Gain</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-sudden-device-disconnection-dxgi/"><u>Remedy for Sudden Device Disconnection (DXGI)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/exploring-nikon-d850-vs-d7500-features-for-2024/"><u>Exploring Nikon D850 Vs D7500 Features for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transform-your-workflow-harnessing-the-power-of-luts-in-adobe-suite/"><u>[Updated] Transform Your Workflow  Harnessing the Power of LUTs in Adobe Suite</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-crafting-dynamic-speed-up-videos/"><u>2024 Approved  Crafting Dynamic Speed-Up Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-address-failed-lunar-client-startup-errors/"><u>Solutions to Address Failed Lunar Client Startup Errors</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premiere-pro-utilizing-lut-techniques/"><u>In 2024, Premiere Pro  Utilizing LUT Techniques</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insta-twist-techniques-for-tailoring-your-photos-on-the-fly-for-2024/"><u>[New] Insta-Twist Techniques for Tailoring Your Photos on the Fly for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-speed-up-your-storytelling-mastering-time-lapses-in-final-cut-pro/"><u>In 2024, Speed Up Your Storytelling Mastering Time Lapses in Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/speed-up-your-conversions-the-best-youtube-to-mp4-converters-revealed/"><u>Speed Up Your Conversions The Best YouTube to MP4 Converters Revealed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-art-of-flawless-conversion-from-slides-to-videos/"><u>2024 Approved  The Art of Flawless Conversion  From Slides to Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unmasking-invisible-audiences-interactions/"><u>[Updated] Unmasking Invisible Audiences' Interactions</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-say-goodbye-to-black-bars-amazon-prime-video-aspect-ratio-solutions/"><u>2024 Approved Say Goodbye to Black Bars Amazon Prime Video Aspect Ratio Solutions</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/in-2024-best-tool-to-translate-youtube-video-to-arabic/"><u>In 2024, Best Tool to Translate YouTube Video to Arabic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsofts-windows-1111-shop-hurdle/"><u>Overcoming Microsoft's Windows 11/11 Shop Hurdle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-honor-play-8t-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multilingual-mastery-harnessing-the-power-of-hotkey-translations-in-windows-11/"><u>Multilingual Mastery: Harnessing the Power of Hotkey Translations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-lost-steam-gaming-glory-a-how-to-manual/"><u>Reviving Lost Steam Gaming Glory: A How-To Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-overhead-memory-usage-by-malware-detectors/"><u>Reducing Overhead Memory Usage by Malware Detectors</u></a></li>
</ul></div>
