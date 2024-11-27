---
title: Straighten Up Windows 11 Designs
date: 2024-11-23T17:09:31.330Z
updated: 2024-11-27T17:08:46.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Straighten Up Windows 11 Designs
excerpt: This Article Describes Straighten Up Windows 11 Designs
keywords: Windows 11 Aesthetics,New UI Layout,Clean Windows Interface,Windows Theme Redesign,Modern Window GUI,Sleek Windows Update,Enhanced Window Style
thumbnail: https://thmb.techidaily.com/1a9ff9a0df36e63422a5b90ac24e55bb1f02f4633cff516b42a4d7954e71a5e9.jpg
---

## Straighten Up Windows 11 Designs

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-crafting-professionally-recorded-audio-via-audacity/"><u>[New] Crafting Professionally Recorded Audio via Audacity</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-skype-to-mp3-capturing-calls-at-no-charge/"><u>[Updated] 2024 Approved Skype to MP3 Capturing Calls at No Charge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-win11-and-macos-key-benefits/"><u>Comparing Win11 & MacOS: Key Benefits</u></a></li>
<li><a href="https://article-helps.techidaily.com/elite-gimbal-solutions-youtube-creators-stabilizing-allies-for-2024/"><u>Elite Gimbal Solutions YouTube Creators' Stabilizing Allies for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Stop Life360 from Tracking You On Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/navigating-the-landscape-of-firefox-picture-in-picture/"><u>Navigating the Landscape of Firefox Picture-in-Picture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-wsl-performance-after-win-11-update/"><u>Restoring WSL Performance After Win 11 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revive-your-microsoft-store-login-experience/"><u>Revive Your Microsoft Store Login Experience</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/samsung-galaxy-fit-assessment-ideal-gadget-for-fitness-enthusiasts/"><u>Samsung Galaxy Fit Assessment - Ideal Gadget for Fitness Enthusiasts</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-and-resolving-driver-problems-on-your-lg-monitor-for-windows-users-versions-10-7-81/"><u>Troubleshooting and Resolving Driver Problems on Your LG Monitor for Windows Users (Versions 10, 7, 8.1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-intel-unison-wont-work-in-win11-solutions-included/"><u>Troubleshooting: Intel Unison Won't Work in Win11, Solutions Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-entertainment-free-win-compatible-players-reviewed/"><u>Unlock Entertainment: Free Win-Compatible Players Reviewed</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-15-pro-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>Unlocking Apple iPhone 15 Pro Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    