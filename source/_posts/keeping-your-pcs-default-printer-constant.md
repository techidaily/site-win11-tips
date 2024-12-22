---
title: Keeping Your PC's Default Printer Constant
date: 2024-12-17T04:28:23.507Z
updated: 2024-12-21T17:09:31.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keeping Your PC's Default Printer Constant
excerpt: This Article Describes Keeping Your PC's Default Printer Constant
keywords: Maintain Default Printing,Preserve Default Printer,Keep Current Printer Set,Fixed Default Printer,Stable System Printer,Unchanged PC Printer,Constant Printer Setting
thumbnail: https://thmb.techidaily.com/9a0ccdfbe8da8591524befa7834f5f64eb569a97d027f532be495df3d4cfc012.jpg
---

## Keeping Your PC's Default Printer Constant

 Setting a default printer on Windows saves you the hassle of manually selecting your preferred printer device across various apps and programs. But what if the default printer keeps changing on your Windows 10 or 11 PC?

 Here are some tips that will keep the default printer from changing on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Prevent Windows From Managing Your Default Printer

 If you have allowed Windows to manage your default printer, it may automatically change the printer depending on your current location. If you don't want that, use these steps to prevent Windows from changing the default printer.

1. Open the **Start menu** and click the **gear-shaped icon** to launch the Settings app.
2. Select **Bluetooth & devices** from the left sidebar.
3. Click on **Printers & scanners**.
4. Under the **Printer preferences** section, disable the toggle next to **Let Windows manage my default printer**.
5. Now select the printer you want to set as the default option.
6. Click the **Set as default** button at the top.  
![Stop Windows From Changing the Default Printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stop-windows-from-changing-the-default-printer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you complete the above steps, Windows should not change the default printer on its own.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Edit the Relevant Registry Files

 If the default printer keeps changing even after you disable the **Let Windows manage my default printer** option, you will need to edit the registry files in order to fix the issue.

 Making incorrect changes to registry files can cause irreversible damage to your computer. Hence, it is important to follow the steps carefully and create a backup of all registry files before proceeding. If you need help with that, refer to our guide on how to [back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

 Once you have done that, use these steps to edit the registry files:

1. Press **Win + S** to open the search menu.
2. Type **registry editor** in the search box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows NT > CurrentVersion > Windows**.
5. In the right pane, double-click the **LegacyDefaultPrinterMode** key to edit it.
6. Enter **1** in the **Value data** field and click **OK**.  
![Stop Windows From Changing the Default Printer via Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/stop-windows-from-changing-the-default-printer-via-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps, and then use one of [the many ways to set the default printer on your Windows PC](https://www.makeuseof.com/set-default-printer-windows-11/). After that, check if the issue occurs again.

## 3\. Try Some Generic Windows Fixes

 In most cases, one of the above tips should solve your problem. Nonetheless, if the problem persists, you can try some generic solutions to address it.

* **Remove unused printers:**[Removing or uninstalling printers on Windows](https://www.makeuseof.com/windows-remove-printer/) that are no longer available can help resolve the issue of Windows constantly changing the default printer. While you’re at it, you should also delete any printer-related software to avoid potential conflicts.
* **Scan for malware:** The presence of malware or viruses on your PC can also impact system settings and lead to such irregularities. To check for this possibility, you can [use PowerShell to scan your Windows PC for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or other threats.
* **Install the latest Windows updates:** Windows updates not only bring new features to your PC but can also help resolve various issues like this one. Hence, it’s a good idea to [install any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) if you haven’t already.
* **Create a new user account:** Problems with your current user account can also cause the default printer to keep changing on Windows. This can happen if some of the user account files associated with your account have become corrupted. If that’s the case, your best option is to [create and switch to a new user account on Windows](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Setting the Default Printer Repeatedly on Windows

 It can be frustrating if the default printer on your Windows computer keeps changing without your input. Fortunately, it’s possible to stop that from happening with the solutions mentioned above.

 Here are some tips that will keep the default printer from changing on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-reel-it-in-8-online-utilities-for-creating-and-sharing-instagram-videos/"><u>[New] 2024 Approved Reel It In 8 Online Utilities For Creating & Sharing Instagram Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-the-teleporting-technique-upgrading-phones-for-vr-immersion/"><u>[New] 2024 Approved The Teleporting Technique Upgrading Phones for VR Immersion</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-what-are-the-best-sites-to-download-text-effects-in-2024/"><u>[New] What Are The Best Sites To Download Text Effects, In 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-syncing-your-presence-in-real-time-tiktoks/"><u>[Updated] 2024 Approved Syncing Your Presence in Real-Time TikToks</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-online-tools-for-dynamic-aspect-adjustment/"><u>[Updated] Online Tools for Dynamic Aspect Adjustment</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-oneplus-nord-ce-3-lite-5g-frp-bypass-by-drfone-android/"><u>About OnePlus Nord CE 3 Lite 5G FRP Bypass</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-essential-audio-tools-free-superior-dj-templates-online/"><u>In 2024, Essential Audio Tools Free, Superior DJ Templates Online</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-xiaomi-redmi-a2plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-whats-the-best-youtube-thumbnail-size/"><u>In 2024, What's the Best YouTube Thumbnail Size?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-issues-top-8-strategies/"><u>Navigating Windows Issues: Top 8 Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-unsynced-files-issue/"><u>Overcoming Steam Unsynced Files Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverse-engineering-failed-vm-start-on-pc/"><u>Reverse-Engineering Failed VM Start on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-stalled-or-non-functional-desktop-menus/"><u>Solutions for Stalled or Non-Functional Desktop Menus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-wi-fi-connectivity-issues-in-minecraft-pc/"><u>Solving Wi-Fi Connectivity Issues in Minecraft, PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    