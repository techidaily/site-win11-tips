---
title: Amplifying RAM with Advanced Virtual Memory Settings
date: 2024-08-08T10:57:52.140Z
updated: 2024-08-09T10:57:52.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Amplifying RAM with Advanced Virtual Memory Settings
excerpt: This Article Describes Amplifying RAM with Advanced Virtual Memory Settings
keywords: Enhance RAM Speed,Boost Virtual Mem,Advanced VM Options,Optimize RAM Usage,RAM Performance Tuning,Elevate Memory Speeds,Improve RAM Management
thumbnail: https://thmb.techidaily.com/f244a4b607ff1304250df827a08b69767edd00f8e4433a759d16a32700c891a6.jpg
---

## Amplifying RAM with Advanced Virtual Memory Settings

 Your computer slowing down isn't a great feeling. Is it overheating? Is the CPU old? Or is it that you've run out of memory?

 Running out of memory affects your system from top to bottom, making regular tasks suddenly feel like walking through treacle.

 If that sounds like your Windows 11 installation, it's time to check out your virtual memory settings to make sure your system can cope with demand. So, here's how you change the virtual memory size on Windows 11, along with a few tips on boosting your system performance.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is Virtual Memory?

 We've [previously explained virtual memory](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) in more detail, but here is an outline to bring you up to speed.

> Your hard drive is where your operating system lives, as well as your photos, music, games, documents, and otherwise. Your RAM stores program-specific data. It is much faster but also more volatile, acting as a working storage area for the programs and files you have open.

> So, what is virtual memory?

> Well, if you use all the RAM available to your system, it will utilize virtual memory—also known as a swap or paging file—to provide a temporary expansion. Your system's virtual memory does this using part of your hard-drive memory to expand your RAM effectively. So, this virtual memory is extremely useful. It allows your system to handle more data for more programs than previously available.

[When your RAM runs low](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , your system will call upon the paging file to handle some of the extra data. However, as your hard drive or even solid-state drive is much slower than your RAM, system performance will take a hit.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![windows 11 advanced system settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/windows-11-advanced-system-settings-option.jpg)

1. Press**Windows key + I** to open the**Settings** app.
2. Head to**System > About** .
3. Select**Advanced system settings** .
4. Under**Performance** , select**Settings** .
5. Open the**Advanced** tab. Under**Virtual memory** , select**Change** . Here are your Virtual Memory options.
6. If you want to set custom virtual memory settings, you'll have to uncheck the box to**Automatically manage paging file size for all drives** . Once you clear the check box, the Virtual Memory options below will become accessible. Select**Custom Size,** then input your desired virtual memory size and select**OK** .

![windows 11 system properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-system-properties.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![windows 11 performance options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-performance-options.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 virtual memory options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-virtual-memory-options.png)

Close

 Keep in mind the virtual memory management tips in the previous section. It might seem like drastically increasing your paging file is a great idea, but it's almost guaranteed to cause system instability when you least expect it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-advanced-mac-toolkit-screenaudio-recording-feature/"><u>[Updated] Advanced Mac Toolkit  Screen/Audio Recording Feature</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-dive-into-telegram-marketing-a-first-timers-primer-for-2024/"><u>[Updated] Dive Into Telegram Marketing  A First Timer's Primer for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-gif-mastery-your-quick-guide-to-uploads-and-sharing/"><u>[Updated] In 2024, Instagram GIF Mastery  Your Quick Guide to Uploads and Sharing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-revive-your-profile-resetting-2023s-facebook-error/"><u>[Updated] In 2024, Revive Your Profile  Resetting 2023'S Facebook Error</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-quickvid-simplified-w11-screen-capture-software-for-2024/"><u>[Updated] QuickVid  Simplified W11 Screen Capture Software for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-reversing-live-action-on-twitch-a-comprehensive-guide/"><u>[Updated] Reversing Live Action on Twitch  A Comprehensive Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-advanced-steps-in-monitoring-and-archiving-system-sounds/"><u>2024 Approved  Advanced Steps in Monitoring & Archiving System Sounds</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-to-excellence-the-ultimate-powerdirectors-user-manual/"><u>2024 Approved  Step-by-Step to Excellence  The Ultimate PowerDirector's User Manual</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-ultimate-tutorial-on-precise-audioshifting/"><u>2024 Approved  Ultimate Tutorial on Precise Audioshifting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-8-ways-to-iis-explorer/"><u>A Step-by-Step Approach: 8 Ways to IIS Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-movecopy-tasks-to-windows-explorers-context-menu/"><u>Adding Move/Copy Tasks to Windows Explorer's Context Menu</u></a></li>
<li><a href="https://fox-info.techidaily.com/basics-of-weaving-a-narrative-thread/"><u>Basics of Weaving a Narrative Thread</u></a></li>
<li><a href="https://extra-information.techidaily.com/becoming-a-visionary-in-depth-guide-to-hdr-photography/"><u>Becoming a Visionary  In-Depth Guide to HDR Photography</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-solutions-for-huawei-network-unlock-by-drfone-android/"><u>Best Solutions for Huawei Network Unlock</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-activation-lock-from-iphone-11-pro-4-easy-ways-by-drfone-ios/"><u>Bypass Activation Lock From iPhone 11 Pro - 4 Easy Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-through-cortana-history-windows/"><u>Charting Your Course Through Cortana History (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/copilot-disappearance-in-ws11-quick-fixes-guide/"><u>Copilot Disappearance in WS11: Quick Fixes Guide</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/discover-the-top-six-power-of-being-bi-lingual/"><u>Discover the Top Six Power of Being Bi-Lingual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-window-11-search-expertise-with-these-tricks/"><u>Elevate Your Window 11 Search Expertise With These Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-additional-views-in-win-11s-context-menu/"><u>Eliminating Additional Views in Win 11'S Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/empower-your-windows-network-with-python-driven-transfers/"><u>Empower Your Windows Network with Python-Driven Transfers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/exclusive-list-the-most-reliable-10-vimeo-downloader-apps-for-2024/"><u>Exclusive List  The Most Reliable 10 Vimeo Downloader Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-4-strategies-for-mac-address-extraction-in-windows-11/"><u>Exploring 4 Strategies for MAC Address Extraction in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-pros-and-cons-of-signal-vs-whatsapp-privacy-measures/"><u>Exploring the Pros & Cons of Signal Vs. WhatsApp Privacy Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-unopenable-windows-folders-click-doubled-down/"><u>Fixes for Unopenable Windows Folders, Click-Doubled Down</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-blank-monitor-during-windows-launch/"><u>Fixing Blank Monitor During Windows Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-lost-ethernet-connection-fixes/"><u>Guiding You Through Lost Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-conjoin-windows-serial-numbers-and-microsoft-accounting/"><u>How to Conjoin Windows Serial Numbers & MICROSOFT ACCOUNTING</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-camera-app-f429f-hiccup/"><u>How to Rectify Windows 11 Camera App F429F Hiccup</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-zte-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best ZTE Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-detailed-instructions-mastering-the-art-of-uploading-vr-media-to-fb/"><u>In 2024, Detailed Instructions  Mastering the Art of Uploading VR Media to FB</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-xiaomi-14-by-drfone-android/"><u>In 2024, How to Bypass FRP from Xiaomi 14?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-confirm-your-youtube-account-securely/"><u>In 2024, How to Confirm Your YouTube Account Securely?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-interactive-index-for-ig-and-tiktok-connection/"><u>In 2024, The Interactive Index for IG & TikTok Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-sound-control-with-windows-11-volume-tools/"><u>Mastering Sound Control with Windows 11 Volume Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-user-access-regulation-for-everyday-windows-pcs/"><u>Mastering User Access Regulation for Everyday Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hyper-v-setup-process-for-windows-11-home-edition/"><u>Navigating the Hyper-V Setup Process for Windows 11 Home Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-mouse-response-time-on-windows-devices/"><u>Optimizing Mouse Response Time on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800704cf-error-in-win11-marketplace/"><u>Overcoming 0X800704CF Error in Win11 Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-roblox-error-262-instantly/"><u>Overcoming Roblox Error 262 Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/re-engineering-the-taskbar-key-steps-to-better-windows-11-ux/"><u>Re-Engineering the Taskbar: Key Steps to Better Windows 11 UX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-winget-in-windows-11-environments/"><u>Reactivating Winget in Windows 11 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-blocking-self-starting-windows-store/"><u>Strategies for Blocking Self-Starting Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-onedrive-errors-on-windows-effective-fixes/"><u>Tackling OneDrive Errors on Windows: Effective Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tech-tip-how-to-turn-off-nvidia-ui/"><u>Tech Tip: How to Turn Off NVIDIA UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-your-windows-11-defense-enhanced-filter-options-via-context-menu/"><u>Upgrade Your Windows 11 Defense: Enhanced Filter Options via Context Menu</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-modern-standby-gets-a-bad-rap-in-windows/"><u>Why Modern Standby Gets a Bad Rap in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-configurations-restarted-a-triad-of-tips/"><u>Win11 Configurations Restarted: A Triad of Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-a-safe-choice-for-beginners/"><u>Windows 11 S Mode: A Safe Choice for Beginners?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-software-windows-best-photo-arrangers-reviewed/"><u>Winning Software: Windows' Best Photo Arrangers Reviewed</u></a></li>
</ul></div>
