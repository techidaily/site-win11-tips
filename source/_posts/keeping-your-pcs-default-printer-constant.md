---
title: Keeping Your PC's Default Printer Constant
date: 2025-01-25T17:11:26.669Z
updated: 2025-01-31T19:23:49.019Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you complete the above steps, Windows should not change the default printer on its own.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after completing the above steps, and then use one of [the many ways to set the default printer on your Windows PC](https://www.makeuseof.com/set-default-printer-windows-11/). After that, check if the issue occurs again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Some Generic Windows Fixes

 In most cases, one of the above tips should solve your problem. Nonetheless, if the problem persists, you can try some generic solutions to address it.

* **Remove unused printers:**[Removing or uninstalling printers on Windows](https://www.makeuseof.com/windows-remove-printer/) that are no longer available can help resolve the issue of Windows constantly changing the default printer. While you’re at it, you should also delete any printer-related software to avoid potential conflicts.
* **Scan for malware:** The presence of malware or viruses on your PC can also impact system settings and lead to such irregularities. To check for this possibility, you can [use PowerShell to scan your Windows PC for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or other threats.
* **Install the latest Windows updates:** Windows updates not only bring new features to your PC but can also help resolve various issues like this one. Hence, it’s a good idea to [install any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) if you haven’t already.
* **Create a new user account:** Problems with your current user account can also cause the default printer to keep changing on Windows. This can happen if some of the user account files associated with your account have become corrupted. If that’s the case, your best option is to [create and switch to a new user account on Windows](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-elevate-your-page-a-guide-to-growing-facebook-followers/"><u>[New] In 2024, Elevate Your Page A Guide to Growing Facebook Followers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/tep-by-step-guide-premiere-pro-for-youtube-cutting/"><u>[New] Step-by-Step Guide Premiere Pro for YouTube Cutting</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/7-impactful-reasons-for-multilingual-journey/"><u>7 Impactful Reasons for Multilingual Journey</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-test-drive-of-the-netgear-nighthawk-x10-router-superior-wi-fi-connectivity-at-blazing-speeds/"><u>Comprehensive Test Drive of the Netgear Nighthawk X10 Router: Superior Wi-Fi Connectivity at Blazing Speeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-older-os-practical-steps-beyond-windows-11/"><u>Enhance Older OS: Practical Steps Beyond Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-inadequacies-in-windows-installer-rights/"><u>Eradicating Inadequacies in Windows Installer Rights</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-tier-gaming-live-broadcast-tools/"><u>In 2024, Top-Tier Gaming Live Broadcast Tools</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, Will iSpoofer update On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/limosoft-studio-kit-beginners-luxury-lighting-guide/"><u>LimoSoft Studio Kit: Beginner's Luxury Lighting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-w11-desktop-with-taskbar-pins/"><u>Optimizing W11 Desktop with Taskbar Pins</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-asus-rog-phone-7-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Asus ROG Phone 7 Phone Now with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-non-functional-slack-alerts-on-pcs/"><u>Quick Fixes for Non-Functional Slack Alerts on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-missing-file-thumbnails-in-microsofts-newest-os/"><u>Remedy Missing File Thumbnails in Microsoft's Newest OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-discrepanranks-between-prime-audio-and-subtitle-feedback-on-windows-11/"><u>Resolve Discrepanranks Between Prime Audio & Subtitle Feedback on Windows 11</u></a></li>
</ul></div>

