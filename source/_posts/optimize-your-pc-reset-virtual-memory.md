---
title: "Optimize Your PC: Reset Virtual Memory"
date: 2024-08-16T02:12:23.570Z
updated: 2024-08-17T02:12:23.570Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Your PC: Reset Virtual Memory"
excerpt: "This Article Describes Optimize Your PC: Reset Virtual Memory"
keywords: PC Memory Optimization,Virtual Mem Reset Guide,Enhance System Speed,RAM Efficiency Tips,Increase PC Performance,Adjust Virtual RAM,Boost Computer Speed
thumbnail: https://thmb.techidaily.com/e8d9fb9f5398f4a792320d2b13c1a57276ee28fb817fc4d294eae20885dd4758.jpg
---

## Optimize Your PC: Reset Virtual Memory

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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2023-online-facebook-video-to-mp3-converters/"><u>[New] 2023 Online Facebook Video to MP3 Converters</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-how-to-record-iphoneipads-screen/"><u>[New] 2024 Approved  How to Record iPhone/iPad’s Screen</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-differences-between-standard-and-premium-youtube-viewing/"><u>[New] 2024 Approved  The Differences Between Standard and Premium YouTube Viewing</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-cooking-crusaders-youtube-stars-serving-up-deliciousness/"><u>[New] Cooking Crusaders  YouTube Stars Serving Up Deliciousness</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-leading-edge-of-virtual-reality-technology-2023-edition/"><u>[New] The Leading Edge of Virtual Reality Technology - 2023 Edition</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-mastering-the-search-a-guide-to-finding-your-ideal-discord-server/"><u>[Updated] 2024 Approved  Mastering the Search  A Guide to Finding Your Ideal Discord Server</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-future-file-fortresses-top-five-innovations-in-cloud-storage/"><u>[Updated] Future File Fortresses  Top Five Innovations in Cloud Storage</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-how-to-use-io-screen-recorder/"><u>[Updated] In 2024, How to Use IO Screen Recorder</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-integrated-upload-sending-vids-to-twitter-and-tumblr/"><u>[Updated] In 2024, Integrated Upload  Sending Vids to Twitter and Tumblr</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-add-fade-inout-premiere-pro/"><u>2024 Approved  How to Add Fade In/Out Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-windows-11s-compatibility-fixer/"><u>A Step-by-Step Guide to Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-to-life-without-official-windows-xp-7-or-81-support/"><u>Adjusting to Life Without Official Windows XP, 7, or 8.1 Support</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-visual-settings-for-secure-web-experience-in-windows-11/"><u>Advanced Visual Settings for Secure Web Experience in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/amplify-your-computers-storage-here-are-the-best-free-options/"><u>Amplify Your Computer's Storage - Here Are the Best Free Options</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/boost-productivity-and-comfort-with-ergodriven-topo-a-detailed-insight-into-the-anti-fatigue-standing-desk-accessory/"><u>Boost Productivity and Comfort with Ergodriven Topo - A Detailed Insight Into the Anti-Fatigue Standing Desk Accessory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combatting-microsoft-teams-crashes-in-win11-and-win10-pcs/"><u>Combatting Microsoft Teams Crashes in Win11 & Win10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-ways-downloading-setting-up-and-running-msix-extensions-on-windows/"><u>Convenient Ways: Downloading, Setting Up & Running MSIX Extensions on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-on-a-nearby-share-solution-tech-giants-go-head-to-head/"><u>Deciding on a Nearby Share Solution: Tech Giants Go Head-to-Head</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-drive-definitions-c-vs-d-in-os/"><u>Dissecting Drive Definitions: C: Vs D: In OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-linking-devices-a-nearby-share-walkthrough/"><u>Effortlessly Linking Devices: A Nearby Share Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-differences-chkdsk-sfc-and-windows-fixes/"><u>Exploring Differences: CHKDSK, SFC, and Windows' Fixes</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-radeon-r9-360-graphics-driver-for-windows-11-step-by-step-guide-and-free-download/"><u>Get the Newest Radeon R9 360 Graphics Driver for Windows 11 - Step-by-Step Guide & Free Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eradicate-system-call-issues-on-modern-windows/"><u>How to Eradicate System Call Issues on Modern Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-tecno-camon-30-pro-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Tecno Camon 30 Pro 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-harnessing-power-at-no-cost-guide-to-hosting-and-participating-in-gmeet/"><u>In 2024, Harnessing Power at No Cost  Guide to Hosting & Participating in GMeet</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-liveaction-gaming-diary/"><u>In 2024, LiveAction Gaming Diary</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-xiaomi-redmi-k70e-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Xiaomi Redmi K70E? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-tips-for-making-facebook-ad-videos-memorable/"><u>In 2024, Tips for Making Facebook Ad Videos Memorable</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-coexistence-of-ethernet-and-wi-fi-for-enhanced-productivity/"><u>Mastering the Coexistence of Ethernet & Wi-Fi for Enhanced Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-virtual-memory-settings-for-peak-windows-performance/"><u>Navigating Through Virtual Memory Settings for Peak Windows Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-missing-device-camera-in-windows-11/"><u>Steps to Correct Missing Device: Camera in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/superior-windows-solutions-for-multimedia-tasks/"><u>Superior Windows Solutions for Multimedia Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-stronger-case-for-windows-11-over-macos/"><u>The Stronger Case for Windows 11 over MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-high-contrast-setting-in-windows/"><u>Turn Off High Contrast Setting in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uninterrupted-online-journey-the-guide-to-win-net-health/"><u>Uninterrupted Online Journey: The Guide to Win Net Health</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719220019899-unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-taskbar-attachment-techniques/"><u>Windows 11 Taskbar Attachment Techniques</u></a></li>
</ul></div>
