---
title: Navigating Through Virtual Memory Settings for Peak Windows Performance
date: 2024-06-25T16:23:22.348Z
updated: 2024-06-26T16:23:22.348Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through Virtual Memory Settings for Peak Windows Performance
excerpt: This Article Describes Navigating Through Virtual Memory Settings for Peak Windows Performance
keywords: Virtual Memory Optimization,Windows Performance Tips,Max Out Virtual RAM,Enhance Memory Efficiency,High-Performance Settings,System Speed Upgrade,Improve PC Load Times
thumbnail: https://thmb.techidaily.com/1f2923f64e4d04f1252f20b82bfb98586fbf55cfa582bc360a8483bf8c37d216.jpg
---

## Navigating Through Virtual Memory Settings for Peak Windows Performance

 Your computer slowing down isn't a great feeling. Is it overheating? Is the CPU old? Or is it that you've run out of memory?

 Running out of memory affects your system from top to bottom, making regular tasks suddenly feel like walking through treacle.

 If that sounds like your Windows 11 installation, it's time to check out your virtual memory settings to make sure your system can cope with demand. So, here's how you change the virtual memory size on Windows 11, along with a few tips on boosting your system performance.

## What Is Virtual Memory?

 We've [previously explained virtual memory](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) in more detail, but here is an outline to bring you up to speed.

> Your hard drive is where your operating system lives, as well as your photos, music, games, documents, and otherwise. Your RAM stores program-specific data. It is much faster but also more volatile, acting as a working storage area for the programs and files you have open.

> So, what is virtual memory?

> Well, if you use all the RAM available to your system, it will utilize virtual memory—also known as a swap or paging file—to provide a temporary expansion. Your system's virtual memory does this using part of your hard-drive memory to expand your RAM effectively. So, this virtual memory is extremely useful. It allows your system to handle more data for more programs than previously available.

[When your RAM runs low](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , your system will call upon the paging file to handle some of the extra data. However, as your hard drive or even solid-state drive is much slower than your RAM, system performance will take a hit.

### Windows 11 Is Running Low on Virtual Memory

 Now, the thing is, virtual memory has its own limits. It isn't an infinite well of additional yet slower memory you can call upon. If you begin to run out of virtual memory, Windows 11 will display the following error message:

> Your system is low on virtual memory. Windows is increasing the size of your virtual memory paging file. During this process, memory requests for some applications may be denied. For more information, see help.

 Windows 11 will automatically manage your virtual memory, ensuring that the paging file has enough capacity to handle your system demands. However, you can also manually increase the size of your paging file on Windows 11 if you're comfortable making decisions regarding how much RAM you have installed.

 Windows sets the initial virtual memory paging file equal to the amount of installed RAM. The paging file is a minimum of 1.5 times and a maximum of three times your physical RAM. You can use the following system to calculate your Windows 11 paging file (using a system with 8GB installed as the example), providing you know [how much RAM you have installed](https://www.makeuseof.com/windows-check-installed-ram-available-ram-slots/) .

* **Minimum** : 1024_8_ 1.5=12288 \[1GB RAM x Installed RAM x Minimum\]
* **Maximum** : 1024_8_ 3=24576 \[1GB RAM x Installed RAM x Maximum\]

 Still, both of these values are high.[Microsoft recommends](http://docs.microsoft.com/en-us/windows/client-management/determine-appropriate-page-file-size) "3 × RAM or 4 GB, whichever is larger," which will protect your system from instability when you do use your paging file. However, Windows' automatic paging file management might decide otherwise, so it's typically best to let the operating system figure things out for itself. For example, in the image below, you can see that on my Windows 10 machine with 32GB RAM installed, the paging file is automatically set at just under 7GB.

 Furthermore, remember that these values take up space on your hard drive, as Windows allocates the overall paging file space in case it needs it.

## How to Increase Virtual Memory Size on Windows 11

 If you want to go ahead and manually alter the paging file size on Windows 11 to remove the virtual memory low message, here's how you go about it.

![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

### Install More RAM to Boost Your System Performance

 Increasing your virtual memory size is a temporary fix and isn't one you should rely on long-term. The only way to truly fix your low virtual memory issue [is to install more RAM](https://www.makeuseof.com/how-to-install-ram/) . The reason your system is turning to the paging file to begin with is that additional data is being palmed off.

 The answer is to install more RAM, which in turn will give your whole system a boost as you'll no longer run out of memory and have to use the slower paging file instead. It's easier to install more RAM on a desktop computer than on a laptop, but [upgrading the RAM on a laptop is possible](https://www.makeuseof.com/tag/upgrading-a-laptops-ram-step-by-step-si-x2/) . Unfortunately, if you don't have any more RAM slots, have reached the maximum RAM capacity, or find that your laptop has soldered RAM, you're flat out of luck.

 You can [attempt to free up more RAM](https://www.makeuseof.com/tag/5-ways-clear-memory-increase-ram-windows-computer/) , but ultimately, you're probably going to need a new laptop.

## Increasing the Windows 11 Paging File Size Is a Temporary Fix

 Boosting the paging file size on Windows 11 or any operating system is a temporary fix. If you're butting up against your memory limit frequently and your computer begins to slow to a crawl, there is only one true fix.


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
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-routines-to-reactivate-window-explorer/"><u>Easy Routines to Reactivate Window Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-files-and-folders-win-1011-edition/"><u>Conquering Files and Folders, Win 10/11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-windows-update-obstacles-with-error-code-0x800736cc/"><u>Breaking Through Windows Update Obstacles with Error Code 0X800736CC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-solution-for-fixing-error-code-0x80073d26/"><u>The Ultimate Solution for Fixing Error Code: 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-o365-sync-issues-a-quick-guide-to-fixing-errors/"><u>Win 11 and O365 Sync Issues: A Quick Guide to Fixing Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-command-prompt-not-running-as-administrator-on-windows/"><u>How to Fix Command Prompt Not Running as Administrator on Windows</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/sourav-joshis-financial-journey-charting-a-profitable-course-on-youtube/"><u>Sourav Joshi’s Financial Journey  Charting a Profitable Course on YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-use-google-trends-to-come-up-with-video-ideas/"><u>[New] In 2024, How to Use Google Trends to Come up with Video Ideas?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-elevate-your-online-presence-with-easy-video-sharing-on-fb-for-2024/"><u>[Updated] Elevate Your Online Presence with Easy Video Sharing on FB for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-109-funny-jokes-and-riddles-to-share-online/"><u>[Updated] In 2024, 109 Funny Jokes & Riddles to Share Online</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-top-8-safe-online-collaboration-software-for-businesses/"><u>[New] Top 8 Safe Online Collaboration Software for Businesses</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-experience-the-old-school-games-anywhere-with-best-in-class-pc-gb-emulators-for-2024/"><u>[New] Experience the Old School Games Anywhere with Best-in-Class PC GB Emulators for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-restore-a-bricked-motorola-moto-g23-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Motorola Moto G23 Back to Operation | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-blur-backgrounds-online-top-free-tools-and-websites/"><u>New 2024 Approved Blur Backgrounds Online Top Free Tools and Websites</u></a></li>
</ul></div>
