---
title: Windows 11 Edge-Less Design Tips
date: 2024-12-05T20:35:42.469Z
updated: 2024-12-06T22:53:46.324Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 11 Edge-Less Design Tips
excerpt: This Article Describes Windows 11 Edge-Less Design Tips
keywords: Windows 11 No Frills,Edge Design Tricks,Lite UI for Win11,Win11 Minimalist Guide,Redesign Win11 Simple,Cut Down Edge Features,Simplify Win11 Interface
thumbnail: https://thmb.techidaily.com/1b75e252ed41838e8d5bba451afdfa23d376fd0390a7d35b413d9e3199913287.jpg
---

## Windows 11 Edge-Less Design Tips

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dive-into-filmmaking-the-role-of-lenses-in-videos/"><u>[New] In 2024, Dive Into Filmmaking The Role of Lenses in Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-optimal-youtube-video-formats-a-comprehensive-guide/"><u>[Updated] 2024 Approved Optimal YouTube Video Formats A Comprehensive Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-quick-and-convenient-video-edits-in-windows-11-photos/"><u>[Updated] 2024 Approved Quick & Convenient Video Edits in Windows 11 Photos</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-formulating-impressive-online-media-introductions-for-2024/"><u>[Updated] Formulating Impressive Online Media Introductions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mystery-of-group-policies-on-windows/"><u>Decoding the Mystery of Group Policies on Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/delicious-diplomacy-global-tiktok-cuisine-for-2024/"><u>Delicious Diplomacy Global TikTok Cuisine for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-file-how-to-handle-mcuicntexe-failure/"><u>Fixing Missing File: How to Handle McUICnt.exe Failure</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-xiaomi-13t-pro-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Xiaomi 13T Pro Phone and Remove Locked Screen</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-canon-s-series-multifunction-printer-driver-software-for-microsoft-windows-systems/"><u>Latest Canon S Series Multifunction Printer Driver Software for Microsoft Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-issues-made-simple/"><u>Navigating Through Windows Issues Made Simple!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-login-failure-duration-in-win-1011/"><u>Personalizing Login Failure Duration in Win 10/11</u></a></li>
<li><a href="https://facebook.techidaily.com/selfie-success-the-complete-guide-on-designing-an-avatar-themed-facebook-cover/"><u>Selfie Success: The Complete Guide on Designing an Avatar-Themed Facebook Cover</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/snag-your-dream-lg-oled-television-for-a-bargain-exclusive-labor-day-offer-with-savings-of-up-to-80-cups-check-out-the-latest-reviews-on-zdnet/"><u>Snag Your Dream LG OLED Television for a Bargain: Exclusive Labor Day Offer with Savings of up to $80 Cups! Check Out the Latest Reviews on ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cleanup-windows-self-deleting-system-guide/"><u>Streamline Cleanup: Windows' Self-Deleting System Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-windows-with-expert-wsl-2-docker-techniques/"><u>Transforming Your Windows with Expert WSL 2 Docker Techniques</u></a></li>
</ul></div>

