---
title: "Mastering Windows Power Menus: Suppress Dim Screen"
date: 2025-01-04T03:40:08.643Z
updated: 2025-01-06T02:32:57.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Power Menus: Suppress Dim Screen"
excerpt: "This Article Describes Mastering Windows Power Menus: Suppress Dim Screen"
keywords: WinPowerSuppressScreen,DimScreenControlWin,MasterPowerMenuQuit,ScreenDimSuppressWin,PowerMenuScreenTweak,WindowsAdjustmentTool,ReduceDimmedDisplay
thumbnail: https://thmb.techidaily.com/c40243a18120050792e9b2a35c08e8c187a7242ae42c21363a9149298cc2eac3.jpg
---

## Mastering Windows Power Menus: Suppress Dim Screen

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-constructing-an-inspirational-tiktok-end-screen-for-2024/"><u>[New] Constructing An Inspirational TikTok End Screen for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-essential-tools-for-every-mac-user-free-screen-recorder-guide/"><u>[New] Essential Tools for Every Mac User – Free Screen Recorder Guide</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-craft-movies-on-windows-11-using-the-free-movie-maker-app-for-2024/"><u>[Updated] Craft Movies on Windows 11 Using the Free Movie Maker App for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/bypass-the-stall-essential-tricks-for-skipping-past-forza-horizon-5s-loading-loop/"><u>Bypass the Stall: Essential Tricks for Skipping Past Forza Horizon 5'S Loading Loop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-non-attached-file-program-linkage-on-pcs/"><u>Correcting Non-Attached File Program Linkage on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-the-shrinkage-of-desktop-icons-on-windows-11/"><u>Correcting the Shrinkage of Desktop Icons on Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/honor-the-founding-fathers-with-savings-purchase-a-cutting-edge-macbook-pro-featuring-the-new-m3-pro-for-an-exceptional-200-discount-on-presidents-day-only-37/"><u>Honor the Founding Fathers with Savings: Purchase a Cutting-Edge MacBook Pro Featuring the New M3 Pro for an Exceptional $200 Discount on Presidents' Day Only | Engadget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/offline-tutorials-setting-up-windows-11/"><u>Offline Tutorials: Setting Up Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/professional-secrets-for-superior-snapshots-on-apples-mobile-tech/"><u>Professional Secrets for Superior Snapshots on Apple’s Mobile Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-tasks-with-windows-grasp-20-key-cmd-commands/"><u>Streamline Tasks with Windows: Grasp 20 Key CMD Commands</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-steps-for-when-d3dx940dll-cannot-be-located/"><u>Troubleshooting Steps for When d3dx9_40.dll Cannot Be Located</u></a></li>
</ul></div>

