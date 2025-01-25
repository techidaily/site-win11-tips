---
title: Boost Performance by Rebooting Windows 11 RAM
date: 2025-01-22T16:49:14.272Z
updated: 2025-01-24T23:24:21.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost Performance by Rebooting Windows 11 RAM
excerpt: This Article Describes Boost Performance by Rebooting Windows 11 RAM
keywords: Boost PC Speed,Win11 RAM Optimize,System Reboot Benefits,RAM Enhancement Tips,Windows 11 Performance,Recharge Computer,RAM Performance Boost
thumbnail: https://thmb.techidaily.com/c5a835a587cbde63390ec7ae0f646f52f65cc154a66fb89768e9cd878c5a4c7b.jpg
---

## Boost Performance by Rebooting Windows 11 RAM

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-hero-vs-hero-a-technological-comparison/"><u>[Updated] 2024 Approved Hero Vs Hero A Technological Comparison</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-comprehensive-guide-to-youtube-content-moderation-rules-for-2024/"><u>[Updated] Comprehensive Guide to YouTube Content Moderation Rules for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtube-thumbnail-101-phones-edition/"><u>[Updated] YouTube Thumbnail 101 Phones Edition</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-how-to-satirize-a-guide-to-parody-production/"><u>2024 Approved How to Satirize A Guide to Parody Production</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-file-management-in-windows-guide-max-156/"><u>Efficient File Management in Windows Guide (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-invisible-scrolldown-in-winworlds/"><u>Halt Invisible Scrolldown in Winworlds</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-realme-c53-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Realme C53 to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-adobe-photoshop-not-working-on-windows/"><u>How to Fix Adobe Photoshop Not Working on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/join-forces-and-leap-to-victory-in-dying-light-a-riveting-review-of-its-co-op-parkour-and-survival-challenges/"><u>Join Forces and Leap to Victory in Dying Light: A Riveting Review of Its Co-Op, Parkour, & Survival Challenges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-revive-disconnected-windows-printers/"><u>Methods To Revive Disconnected Windows Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pixel-perfect-protection-sneaky-storage-solutions-on-windows-11/"><u>Pixel Perfect Protection: Sneaky Storage Solutions on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-cpu-overuse-a-guide-to-managing-tiworkerexe-usage/"><u>Reducing CPU Overuse: A Guide to Managing TiWorker.exe Usage</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-mastery-of-cloud-gaming-with-your-xbox-game-pass-ultimate/"><u>Step-by-Step Mastery of Cloud Gaming with Your Xbox Game Pass Ultimate</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-y17s-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Vivo Y17s Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/youtube-titanics-1-8-vids-of-note/"><u>YouTube Titanics #1-#8 Vids of Note</u></a></li>
</ul></div>

