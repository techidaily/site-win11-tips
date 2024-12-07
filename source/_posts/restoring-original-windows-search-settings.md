---
title: Restoring Original Windows Search Settings
date: 2024-12-01T21:58:58.469Z
updated: 2024-12-06T17:21:44.020Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Original Windows Search Settings
excerpt: This Article Describes Restoring Original Windows Search Settings
keywords: Set Windows Defaults,Revert Windows Index,Reset Search Engine,Windows Search Restore,Disable Precache,Uninstall UX Search,Remove Windows Explorer
thumbnail: https://thmb.techidaily.com/01781fffdf7ecc74eaf5b3cf4180716493ded8344db51bb91021cea7376b2f5b.jpg
---

## Restoring Original Windows Search Settings

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.

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
<li><a href="https://extra-tips.techidaily.com/new-core-definitions-of-cyber-storytelling/"><u>[New] Core Definitions of Cyber Storytelling</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-demystifying-trillers-unique-approach-to-video-content/"><u>[New] Demystifying Triller's Unique Approach to Video Content</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-effective-engagement-incorporating-youtube-videos-into-slides/"><u>[Updated] Effective Engagement Incorporating YouTube Videos Into Slides</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-peeling-the-onion-understanding-instagram-story-audiences/"><u>[Updated] Peeling the Onion Understanding Instagram Story Audiences</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-perfect-your-storytelling-with-these-6-reel-apps-for-2024/"><u>[Updated] Perfect Your Storytelling with These 6 Reel Apps for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ng-edge-techniques-in-live-streamed-gaming-for-2024/"><u>Cutting-Edge Techniques in Live-Streamed Gaming for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-activate-defender-application-guard-on-windows-11-edge/"><u>How to Activate Defender Application Guard on Windows 11 Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-your-steam-game-icons-missing-on-windows/"><u>How to Fix Your Steam Game Icons Missing on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-motorola-moto-g23-to-mac-drfone-by-drfone-android/"><u>How to Mirror Motorola Moto G23 to Mac? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-infinix-smart-7-hd-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Infinix Smart 7 HD Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-simple-remedies-for-black-screen-panic/"><u>Master Simple Remedies for Black Screen Panic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-fn-key-alterations-for-windows-1011/"><u>Navigating FN Key Alterations for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-amd-graphics-masterful-configuration-tips-for-windows-games/"><u>Perfecting AMD Graphics: Masterful Configuration Tips for Windows Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-cpu-control-minmax-processor-insights/"><u>Precision in CPU Control: Min/Max Processor Insights</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolved-windows-11-kernel-error-fixes-and-prevention-tips/"><u>Resolved: Windows 11 Kernel Error Fixes and Prevention Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-restarting-the-explorer-on-windows-11os/"><u>Swift Solutions: Restarting the Explorer on Windows 11OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-significance-of-runtime-brokers-for-operating-systems/"><u>The Significance of Runtime Brokers for Operating Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-unseen-viewers-route-navigating-instagram-stories-with-anonymous-viewing/"><u>The Unseen Viewer's Route Navigating Instagram Stories with Anonymous Viewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-visual-performance-a-comprehensive-vram-guide/"><u>Turbocharging Visual Performance - A Comprehensive VRAM Guide</u></a></li>
</ul></div>

