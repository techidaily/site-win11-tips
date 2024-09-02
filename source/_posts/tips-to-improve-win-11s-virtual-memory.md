---
title: Tips to Improve Win 11'S Virtual Memory
date: 2024-09-01T05:14:08.638Z
updated: 2024-09-02T05:14:08.638Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Improve Win 11'S Virtual Memory
excerpt: This Article Describes Tips to Improve Win 11'S Virtual Memory
keywords: Win 11 Memory Tips,Virtual Memory Boost,Optimize Win 11 Memory,Enhance Win 11 RAM,Virtual Memory Settings,Improve Win 11 Performance,Increase Virtual Memory Efficiency
thumbnail: https://thmb.techidaily.com/dc0976bf992fc8f3795e090c13f66cb1c6f1455915fe3cbbbf65ceba836d3f9e.jpg
---

## Tips to Improve Win 11'S Virtual Memory

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-live-streaming-showdown-streamlabs-vs-obs-face-off/"><u>[Updated] In 2024, Live Streaming Showdown  Streamlabs Vs. OBS Face-Off</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unearthing-8-youtube-platforms-with-stellar-rapid-rise/"><u>2024 Approved  Unearthing 8 YouTube Platforms with Stellar Rapid Rise</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-samsung-galaxy-f54-5g-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Samsung Galaxy F54 5G Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-poco-c51-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Poco C51? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-center-your-portal-to-windows-printer-administration/"><u>Command Center: Your Portal to Windows Printer Administration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-walkthrough-for-windows-11-arm-iso-install/"><u>Comprehensive Walkthrough for Windows 11 ARM ISO Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-hidden-power-of-windows-reliability-and-performance-monitors/"><u>Decoding the Hidden Power of Windows' Reliability & Performance Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-arp-cache-and-its-clearance-methods-126-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Demystifying Windows ARP Cache and Its Clearance Methods (126 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-upload-and-download-speeds-in-windows-10/"><u>Displaying Upload & Download Speeds in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-solve-windows-0x80070141-connectivity-issues/"><u>Essential Tips to Solve Windows' 0X80070141 Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fixing-the-unusual-c0000005-error-in-windows/"><u>Guide to Fixing the Unusual C0000005 Error in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-gps-location-on-vivo-y100t-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo Y100t Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/image-alchemy-converting-ordinary-into-extraordinary-for-2024/"><u>Image Alchemy  Converting Ordinary Into Extraordinary for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-smart-8-plusfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Smart 8 PlusFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-console-permissions-in-the-microsoft-environment/"><u>Managing Console Permissions in the Microsoft Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-integrating-portable-tools-in-windows-11/"><u>Master the Art: Integrating Portable Tools in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-streamerror-fixes-in-steam-for-windows-users/"><u>Mastering StreamError Fixes in Steam for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11s-entry-point-for-peak-performance/"><u>Maximizing Windows 11'S Entry Point for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-pc-lock-screen-wait-time-issue/"><u>Overcoming Frozen PC Lock Screen Wait Time Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-previously-erased-sleep-mode-profiles/"><u>Reclaiming Previously Erased Sleep Mode Profiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-active-state-for-windows-11-context-menu/"><u>Reinstating Active State for Windows 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-create-file-failed-with-code-32-in-windows-error-30005/"><u>Resolving Create File Failed With Code 32 in Windows Error 30005</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-notepad-unresponsiveness-in-windows-os/"><u>Resolving Notepad Unresponsiveness in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-invalid-network-path/"><u>Resolving Windows Error: Invalid Network Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-strategies-for-win11s-frozen-adobe-photoshop/"><u>Restart Strategies for Win11's Frozen Adobe Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-alternative-windows-pdf-viewer/"><u>Setting Alternative Windows PDF Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-incorrect-file-history-options-in-windows/"><u>Tackling the Incorrect File History Options in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-windows-compatible-weather-apps/"><u>Top 10 Windows-Compatible Weather Apps</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-for-windows-camera-failure-error-0xa00f4292-explained/"><u>Troubleshooting Guide for Windows Camera Failure - Error 0xA00F4292 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-search-bar-glitches-with-11-fixes/"><u>Troubleshooting Window's 11 Search Bar Glitches with 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-free-roving-windows-cursors/"><u>Unraveling the Mystery of Free-Roving Windows Cursors</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-premiere-pro-transition-essentials-top-10-plugins-you-need/"><u>Updated 2024 Approved Premiere Pro Transition Essentials Top 10 Plugins You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-your-next-win-based-game-needs-dxvk-insights-unveiled/"><u>Why Your Next Win-Based Game Needs DXVK – Insights Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-mastering-dolby-atmos-setup/"><u>Win 10/11: Mastering Dolby Atmos Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-world-wisdom-individual-screen-wallpaper-in-win-1011/"><u>Window World Wisdom: Individual Screen Wallpaper in Win 10/11</u></a></li>
</ul></div>
