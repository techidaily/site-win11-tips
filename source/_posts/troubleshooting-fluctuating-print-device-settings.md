---
title: Troubleshooting Fluctuating Print Device Settings
date: 2024-11-21T16:34:12.605Z
updated: 2024-11-27T17:36:06.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Fluctuating Print Device Settings
excerpt: This Article Describes Troubleshooting Fluctuating Print Device Settings
keywords: Printer Setting Fixes,Print Adjustment Trouble,Devices Set Configurations,Stable Print Device Parameters,Resolving Printer Issues,Modify Print Settings Smoothly,Fixed Fluctuating Printers
thumbnail: https://thmb.techidaily.com/a4224fc73a6465f58bae54c290236f5e5e431174596ef739d111ede45824dcdd.png
---

## Troubleshooting Fluctuating Print Device Settings

 Setting a default printer on Windows saves you the hassle of manually selecting your preferred printer device across various apps and programs. But what if the default printer keeps changing on your Windows 10 or 11 PC?

 Here are some tips that will keep the default printer from changing on your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you complete the above steps, Windows should not change the default printer on its own.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Restart your PC after completing the above steps, and then use one of [the many ways to set the default printer on your Windows PC](https://www.makeuseof.com/set-default-printer-windows-11/). After that, check if the issue occurs again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Some Generic Windows Fixes

 In most cases, one of the above tips should solve your problem. Nonetheless, if the problem persists, you can try some generic solutions to address it.

* **Remove unused printers:**[Removing or uninstalling printers on Windows](https://www.makeuseof.com/windows-remove-printer/) that are no longer available can help resolve the issue of Windows constantly changing the default printer. While you’re at it, you should also delete any printer-related software to avoid potential conflicts.
* **Scan for malware:** The presence of malware or viruses on your PC can also impact system settings and lead to such irregularities. To check for this possibility, you can [use PowerShell to scan your Windows PC for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or other threats.
* **Install the latest Windows updates:** Windows updates not only bring new features to your PC but can also help resolve various issues like this one. Hence, it’s a good idea to [install any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) if you haven’t already.
* **Create a new user account:** Problems with your current user account can also cause the default printer to keep changing on Windows. This can happen if some of the user account files associated with your account have become corrupted. If that’s the case, your best option is to [create and switch to a new user account on Windows](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stop Setting the Default Printer Repeatedly on Windows

 It can be frustrating if the default printer on your Windows computer keeps changing without your input. Fortunately, it’s possible to stop that from happening with the solutions mentioned above.

 Here are some tips that will keep the default printer from changing on your PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unraveling-the-purpose-of-facebooks-blue-messenger-emblem/"><u>[New] 2024 Approved Unraveling the Purpose of Facebook's Blue Messenger Emblem</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-apex-chart-seeker-monitor-most-viewed-videos-for-2024/"><u>[New] Apex Chart Seeker Monitor Most Viewed Videos for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-capturing-the-thrill-hero5-black-against-hero4-silver/"><u>[Updated] 2024 Approved Capturing the Thrill Hero5 Black Against Hero4 Silver</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-logitechs-full-blown-4k-webcam-complete-reveal-and-evaluation/"><u>[Updated] 2024 Approved Logitech's Full-Blown 4K Webcam - Complete Reveal & Evaluation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-master-your-download-installation-and-usage-of-ez-grabber/"><u>[Updated] In 2024, Master Your Download Installation and Usage of EZ Grabber</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-learn-to-turn-your-photos-into-their-opposites/"><u>[Updated] Learn to Turn Your Photos Into Their Opposites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-remedy-error-30005-in-windows/"><u>Comprehensive Guide to Remedy Error 30005 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-applications-that-say-install-net-framework-on-pcs/"><u>Correcting Applications that Say Install .NET Framework on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-error-0x0000004e-on-windows-11-pc/"><u>Disabling Error 0X0000004E on Windows 11 PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-our-handpicked-selection-of-heartwarming-family-flicks-on-amazon-prime-video-july-edition/"><u>Explore Our Handpicked Selection of Heartwarming Family Flicks on Amazon Prime Video - July Edition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-high-quality-methodology-stitching-gopro-sequences-in-virtual-reality-films/"><u>In 2024, High-Quality Methodology Stitching GoPro Sequences in Virtual Reality Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-compatibility-issues-with-easy-fixed-steps/"><u>Overcome Compatibility Issues with Easy Fixed Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-workflow-icon-insertion-into-win11s-context-menu/"><u>Streamlining Workflow: Icon Insertion Into Win11's Context Menu</u></a></li>
</ul></div>

