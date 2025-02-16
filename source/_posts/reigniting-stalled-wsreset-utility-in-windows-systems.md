---
title: Reigniting Stalled WSReset Utility in Windows Systems
date: 2025-02-15T01:50:48.619Z
updated: 2025-02-15T22:12:15.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reigniting Stalled WSReset Utility in Windows Systems
excerpt: This Article Describes Reigniting Stalled WSReset Utility in Windows Systems
keywords: WSReset Fix,Reset Windows,System Reset,Reinvigorate WSReset,Windows Stalled Fix,Revive Windows Systems,Enable Windows Refresh
thumbnail: https://thmb.techidaily.com/3fbb28fdd30ab5cd77a4baca2551c9d92b27e18215ac7c02404eb389cacb68b2.jpg
---

## Reigniting Stalled WSReset Utility in Windows Systems

 WSReset.exe is an essential command line tool delivered with Windows to perform various tasks and troubleshoot issues. It resets the Windows application store and clears cache issues that may result in slow performance or errors.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix WSReset.exe Not Working on Windows

 Before you troubleshoot, let's see what WSReset.exe is used for. The WSReset.exe program resets Windows Store and clears any cache issues that might cause errors. It troubleshoots problems with the Windows Store and applications, including those that are not downloading or launching properly.

 Now let's move on to troubleshooting.

## 1\. Run WSReset.exe as an Administrator

 WSReset.exe requires administrative privileges to run properly. If you're not running it as an administrator, it may fail to reset the Windows Store cache.

 To resolve this issue, [ensure you're using a Windows admin account](https://www.makeuseof.com/check-windows-account-admin-rights/), then try running WSReset.exe again.

## 2\. Run the Windows Store App Troubleshooter

 This problem also appears due to corrupt system files or Windows Store application issues. To fix these issues, Windows offers an embedded troubleshooter that identifies and resolves problems with the Store app.

 To run the troubleshooter, use the steps below.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. Select **System** from the left sidebar.
3. In the right pane, click **Troubleshoot > Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. On the troubleshooter page, scroll down to **Windows Store Apps** and click **Run**.  

![Run Windows Store Apps Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-store-apps-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As the troubleshooter scans, it detects and fixes any existing issues. Once that's done, restart your computer again and try running WSReset.exe again.

 If you use Windows 10 version, the process will be slightly different. Press **Win + R**, type **ms-settings:troubleshoot**, and hit Enter. In the Settings menu, click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters**.

![Windows Additional Troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Windows-Additional-Troubleshooters.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Select **Windows Store Apps** from the list and click **Run the troubleshooter**.

## 3\. Repair and Reset Windows Store

 If WSReset.exe is still not working, chances are the Windows Store app might be corrupted or not functioning correctly. In that case, try [repairing and resetting the Windows Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/). This will restore the application to its default settings and often solves errors

## 4\. Remove the Latest Windows Updates

 Although Microsoft releases regular Windows updates to improve overall system performance, sometimes these updates cause problems instead. WSReset.exe not working is one such issue related to a recent Windows update.

 Therefore, if you’ve recently applied any updates and are now facing issues with WSReset.exe, remove the update and see if this resolves the issue.

1. Press **Win + S** on your keyboard to open the search box.
2. Type **Control Panel** in the search box and select it from the results list.
3. Then navigate to **Programs** \> **Programs and Features** \> **Uninstall a program**.
4. From the left sidebar, select **View installed updates**. This will open the Settings window with the list of applied Windows updates.
5. Now look for the recent update and click **Uninstall** next to it.  
![Uninstall Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-windows-updates.jpg)
6. Click **Uninstall** again when prompted.

 Follow the onscreen instructions and restart your computer when it's done.

## 5\. Clear the Microsoft Store Cache via the Registry

 If you're still having issues with WSReset.exe, clear the Microsoft Store cache via the registry. This wipes out temporary files, settings, or preferences that may cause this issue.

 It is a complex process for those unfamiliar with registry changes, as incorrect settings could cause major problems. However, if done correctly, this flushes the cache and solves WSReset.exe errors. To avoid data loss, back up your registry and be cautious when modifying it.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **cmd** in the text field and press **Ctrl + Shift + Enter**. This will open the Command Prompt window with administrative privileges.
3. If the UAC prompt appears, select **Yes** to continue.
4. In the Command Prompt window, type the following command and press Enter:  
`wmic useraccount get name,sid`
5. Running this command will list all user accounts on your computer. Find the SID of your user account and copy it.  
![List all user account via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/list-all-user-account-via-command-prompt.jpg)
6. Next, open the Registry Editor. For this, click on **Start** \> type **regedit** in the search box, then select it from the results list.

7. If the UAC pop-up appears, click **Yes** to continue.
8. When the Registry Editor opens, navigate to the following registry key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Appx\AppxAllUserStore`  
 You can also paste this path into the Registry Editor's address bar and press Enter. This will direct you to the AppxAllUserStore registry key.
9. In the **AppxAllUserStore** key, find the **SID** you copied earlier.  
![Clear the Microsoft Store Cache via the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/clear-the-microsoft-store-cache-via-the-registry.jpg)
10. Right-click on it and select **Delete**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. If a confirmation pop-up appears, click **Yes**. This will clear the Microsoft Store cache.
12. Close the Registry Editor and restart your PC.

 Now, open the Command Prompt window with administrative privileges again and run WSReset.exe to see if it works properly. If so, you have successfully cleared the Microsoft Store cache via the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reinstall the Microsoft Store

 Sometimes Windows Store files are corrupted or damaged. This may require you to [reinstall the Microsoft Store app](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/). The process replaces corrupted or missing files and prevents WSReset.exe from malfunctioning.

## 7\. Try Some Generic Fixes

 There are also some general solutions that work in various scenarios. These include [running a malware scan on your system](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) or [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and switching to it.

 If you're still encountering WSReset.exe errors, [restart your Windows computer](https://www.makeuseof.com/windows-restart-methods/). It refreshes your computer's memory and cleans out temporary files or settings.

 You could also [run System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to fix errors and replace corrupt files. If none of the above-mentioned steps work, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/) and restore your computer to an earlier point when it was working fine.

## Resolving the WSReset.exe Issue on Windows

 Today WSReset.exe is a well-known tool among Windows users. Despite being simple, this can be tricky to troubleshoot if it fails to reset or clear the Windows Store. Hopefully, it's just a system glitch, and you can fix the problem using the suggestions provided in this article.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-navigating-the-mobile-landscape-start-your-entrepreneurial-or-personal-youtube-channel/"><u>[New] 2024 Approved Navigating the Mobile Landscape Start Your Entrepreneurial or Personal YouTube Channel</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-the-art-of-audio-visual-storytelling-with-iphone/"><u>[New] In 2024, The Art of Audio-Visual Storytelling with iPhone</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-the-artisan-writes-crafting-hdr-magic-with-iphone/"><u>[New] In 2024, The Artisan’ Writes Crafting HDR Magic with iPhone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-key-elements-to-successful-mobile-app-design/"><u>[Updated] 2024 Approved Key Elements to Successful Mobile App Design</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-emerald-error-in-nba-2k21-effective-fixes-explored/"><u>Beat the Emerald Error in NBA 2K21: Effective Fixes Explored</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-xiaomi-civi-3-disney-100th-anniversary-edition-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Xiaomi Civi 3 Disney 100th Anniversary Edition Phone Pattern Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-microsoft-excel-a-step-by-step-guide-to-utilizing-the-filter-feature/"><u>Mastering Microsoft Excel: A Step-by-Step Guide to Utilizing the Filter Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-your-spreadsheet-techniques-to-change-series-names-in-excel/"><u>Mastering Your Spreadsheet: Techniques to Change Series Names in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-data-presentation-with-effective-spell-check-functions-in-excel/"><u>Perfect Your Data Presentation with Effective Spell Check Functions in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/printing-excel-sheets-made-easy-how-to-show-gridlines-with-rowcolumn-labels/"><u>Printing Excel Sheets Made Easy - How to Show Gridlines with Row/Column Labels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-data-with-ease-mastering-pivot-table-updates-in-ms-excel/"><u>Revamp Your Data with Ease - Mastering Pivot Table Updates in MS Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simple-steps-mastering-the-selection-of-cell-ranges-in-microsoft-excel/"><u>Simple Steps: Mastering the Selection of Cell Ranges in Microsoft Excel</u></a></li>
<li><a href="https://fox-http.techidaily.com/starting-an-online-platform-for-consumer-goods-reviews/"><u>Starting an Online Platform for Consumer Goods Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-adding-and-utilizing-microsoft-office-extensions/"><u>Step-by-Step Guide: Adding & Utilizing Microsoft Office Extensions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-crafting-personalized-excel-templates/"><u>Step-by-Step Guide: Crafting Personalized Excel Templates</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-raspberry-pi-hats-of-2024-the-ultimate-guide-to-project-expansion-boards/"><u>Top Raspberry Pi HATs of 2024 - The Ultimate Guide to Project Expansion Boards</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/troubleshooting-how-to-fix-the-error-when-installing-your-graphics-card-driver-tips-from-yl-computing/"><u>Troubleshooting: How to Fix the 'Error' When Installing Your Graphics Card Driver - Tips From YL Computing</u></a></li>
</ul></div>

