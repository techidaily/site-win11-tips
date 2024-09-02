---
title: Improve Computer Efficiency with W11 VM Reset
date: 2024-09-01T05:15:08.429Z
updated: 2024-09-02T05:15:08.429Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Improve Computer Efficiency with W11 VM Reset
excerpt: This Article Describes Improve Computer Efficiency with W11 VM Reset
keywords: VM Reset Tips,Boost PC Performance,Enhance System Speed,Optimize Windows 11,Efficient Computing,Clear Cache Effectively,Upgrade System Efficiency
thumbnail: https://thmb.techidaily.com/259bceb776cdbf3be867bf48c477b3f9885a0b2e906117f4f6cafe9378e4fe6f.jpg
---

## Improve Computer Efficiency with W11 VM Reset

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
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-decoding-podcast-access-a-detailed-iphone-guidebook/"><u>[New] In 2024, Decoding Podcast Access  A Detailed iPhone Guidebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-enhance-your-shorts-appeal-with-personalized-thumbnails/"><u>[New] In 2024, Enhance Your Shorts' Appeal with Personalized Thumbnails</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-sites-like-famebit-where-you-can-find-youtube-sponsorships/"><u>[New] In 2024, Sites Like FameBit Where You Can Find YouTube Sponsorships</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-video-capturing-step-by-step-manual/"><u>[Updated] 2024 Approved  Mastering Video Capturing  Step-by-Step Manual</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-scrutinizing-selfies-on-instagram-validation-necessary/"><u>[Updated] In 2024, Scrutinizing Selfies on Instagram  Validation Necessary?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-the-essentials-comprehensive-editing-tutorial/"><u>[Updated] The Essentials  Comprehensive Editing Tutorial</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-traffic-elevate-rankings-essential-youtube-seo/"><u>Boost Traffic, Elevate Rankings - Essential YouTube SEO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-new-username-assignments-in-windows-11-edition/"><u>Conquering New UserName Assignments in Windows 11 Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-install-failed-disconnect-for-win-11-discord/"><u>Correcting the 'Install Failed' Disconnect for Win 11 Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-hidden-power-of-windows-reliability-and-performance-monitors/"><u>Decoding the Hidden Power of Windows' Reliability & Performance Monitors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/displaying-upload-and-download-speeds-in-windows-10/"><u>Displaying Upload & Download Speeds in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-turning-esd-to-iso-on-windows-instantly/"><u>Efficiency in Action: Turning ESD to ISO on Windows Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-notifications-game-on-windows-11/"><u>Elevate Your Notifications Game on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-driver-failure-error-on-windows-11-pc/"><u>Eliminating Driver Failure Error on Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-productivity-with-customized-keyboard-tricks/"><u>Enhance Productivity with Customized Keyboard Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-solve-windows-0x80070141-connectivity-issues/"><u>Essential Tips to Solve Windows' 0X80070141 Connectivity Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insight-efficiently-identify-hdd-vs-ssd-type-on-windows/"><u>Expert Insight: Efficiently Identify HDD vs SSD Type on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-overcoming-technical-hurdles-in-iphone-xs-facial-detection/"><u>In 2024, Overcoming Technical Hurdles in iPhone X's Facial Detection</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-samsung-galaxy-z-flip-5-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Samsung Galaxy Z Flip 5 Phone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-xiaomi-redmi-note-12-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Xiaomi Redmi Note 12 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-to-the-code-how-to-fix-keystrokes-in-win10/"><u>Key to the Code: How to Fix Keystrokes in Win10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leveraging-iphone-features-for-gif-storage-and-entertainment/"><u>Leveraging iPhone Features for GIF Storage & Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-console-permissions-in-the-microsoft-environment/"><u>Managing Console Permissions in the Microsoft Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-windows-11s-entry-point-for-peak-performance/"><u>Maximizing Windows 11'S Entry Point for Peak Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-should-focus-on-making-windows-11-better-not-just-more-fun/"><u>Microsoft Should Focus on Making Windows 11 Better, Not Just More Fun</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-hurdles-restoring-access-to-notepad/"><u>Navigating Through Windows' Hurdles: Restoring Access to Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-visual-impact-activate-windows-11s-color-management/"><u>Optimize Your Visual Impact - Activate Windows 11'S Color Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-gpu-load-with-proven-wm-fixes-on-windows/"><u>Optimizing GPU Load with Proven WM Fixes on Windows</u></a></li>
<li><a href="https://win-able.techidaily.com/optimizing-system-performance-in-god-of-war-a-guide-on-cutting-down-cpu-usage/"><u>Optimizing System Performance in God of War – A Guide on Cutting Down CPU Usage</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/other-great-video-editing-options-besides-powerdirector-for-android-and-ios/"><u>Other Great Video Editing Options Besides PowerDirector for Android and iOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-frozen-pc-lock-screen-wait-time-issue/"><u>Overcoming Frozen PC Lock Screen Wait Time Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-system-hurdle-windows-c0000022-resolution-guide/"><u>Overcoming System Hurdle: Windows C0000022 Resolution Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-task-manager-halt-on-pcs/"><u>Overcoming Task Manager Halt on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-warnings-about-unverified-application-in-windows-os/"><u>Overcoming Warnings About Unverified Application in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-your-windows-11-control-panel/"><u>Overhauling Your Windows 11 Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-windows-zoom-disruptions-fatal-error-1132/"><u>Preventing Windows Zoom Disruptions - Fatal Error 1132</u></a></li>
<li><a href="https://extra-information.techidaily.com/prime-selection-of-innovative-vr-cycling-games/"><u>Prime Selection of Innovative VR Cycling Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-active-state-for-windows-11-context-menu/"><u>Reinstating Active State for Windows 11 Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-error-code-0xc1900101-in-windows-11-update/"><u>Remedying Error Code 0XC1900101 in Windows 11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-excessive-cpu-consumption-by-vanguards-ums-in-windows/"><u>Resolving Excessive CPU Consumption by Vanguard's UMS in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-notepad-unresponsiveness-in-windows-os/"><u>Resolving Notepad Unresponsiveness in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restart-strategies-for-win11s-frozen-adobe-photoshop/"><u>Restart Strategies for Win11's Frozen Adobe Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-controlled-chromeedge-use-in-enterprise-environments/"><u>Simplifying Controlled Chrome/Edge Use in Enterprise Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steady-your-system-five-approaches-to-resolve-secure-boot-errors/"><u>Steady Your System: Five Approaches to Resolve Secure Boot Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-way-through-fax-cover-customization-in-win11/"><u>Streamlining Your Way Through Fax Cover Customization in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-disarm-frozen-app-block-on-windows/"><u>Techniques to Disarm Frozen App Block on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-pc-performance-monitors-in-windows/"><u>Top 6 PC Performance Monitors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-stuck-on-size-errors-in-win11-discord-with-ease/"><u>Troubleshooting Stuck-On-Size Errors in Win11 Discord with Ease</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-videopad-video-editor-review-should-you-buy-it-for-2024/"><u>Updated The Ultimate Videopad Video Editor Review Should You Buy It for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-the-war-against-failed-chromebook-file-uploads-win-wise/"><u>Win the War Against Failed Chromebook File Uploads, WIN-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-arm-installation-iso-file-journey/"><u>Windows 11 ARM Installation: ISO File Journey</u></a></li>
</ul></div>
