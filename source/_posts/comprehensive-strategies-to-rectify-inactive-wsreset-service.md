---
title: Comprehensive Strategies to Rectify Inactive WSReset Service
date: 2024-12-02T20:15:09.899Z
updated: 2024-12-07T00:24:47.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensive Strategies to Rectify Inactive WSReset Service
excerpt: This Article Describes Comprehensive Strategies to Rectify Inactive WSReset Service
keywords: Fixing WSReset,Reactivate Reset Service,WSReset Troubleshooting,Reset Service Restart,Inactive WSReset Remediation,Reactivation of Reset Services,Overcoming WSReset Lockout
thumbnail: https://thmb.techidaily.com/79c7e594da2bcc4e0b5a712ad425c9a3c9c769d4308cac3ac9d4efb24f911715.jpg
---

## Comprehensive Strategies to Rectify Inactive WSReset Service

 WSReset.exe is an essential command line tool delivered with Windows to perform various tasks and troubleshoot issues. It resets the Windows application store and clears cache issues that may result in slow performance or errors.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Run Windows Store Apps Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-windows-store-apps-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As the troubleshooter scans, it detects and fixes any existing issues. Once that's done, restart your computer again and try running WSReset.exe again.

 If you use Windows 10 version, the process will be slightly different. Press **Win + R**, type **ms-settings:troubleshoot**, and hit Enter. In the Settings menu, click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters**.

![Windows Additional Troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Windows-Additional-Troubleshooters.jpg)

 Select **Windows Store Apps** from the list and click **Run the troubleshooter**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. If the UAC pop-up appears, click **Yes** to continue.
8. When the Registry Editor opens, navigate to the following registry key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Appx\AppxAllUserStore`  
 You can also paste this path into the Registry Editor's address bar and press Enter. This will direct you to the AppxAllUserStore registry key.
9. In the **AppxAllUserStore** key, find the **SID** you copied earlier.  
![Clear the Microsoft Store Cache via the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/clear-the-microsoft-store-cache-via-the-registry.jpg)
10. Right-click on it and select **Delete**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

11. If a confirmation pop-up appears, click **Yes**. This will clear the Microsoft Store cache.
12. Close the Registry Editor and restart your PC.

 Now, open the Command Prompt window with administrative privileges again and run WSReset.exe to see if it works properly. If so, you have successfully cleared the Microsoft Store cache via the registry.

## 6\. Reinstall the Microsoft Store

 Sometimes Windows Store files are corrupted or damaged. This may require you to [reinstall the Microsoft Store app](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/). The process replaces corrupted or missing files and prevents WSReset.exe from malfunctioning.

## 7\. Try Some Generic Fixes

 There are also some general solutions that work in various scenarios. These include [running a malware scan on your system](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) or [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and switching to it.

 If you're still encountering WSReset.exe errors, [restart your Windows computer](https://www.makeuseof.com/windows-restart-methods/). It refreshes your computer's memory and cleans out temporary files or settings.

 You could also [run System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) to fix errors and replace corrupt files. If none of the above-mentioned steps work, [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/) and restore your computer to an earlier point when it was working fine.

## Resolving the WSReset.exe Issue on Windows

 Today WSReset.exe is a well-known tool among Windows users. Despite being simple, this can be tricky to troubleshoot if it fails to reset or clear the Windows Store. Hopefully, it's just a system glitch, and you can fix the problem using the suggestions provided in this article.

 However, if you encounter problems with WSReset.exe or receive frequent errors, your computer may have an underlying issue that needs to be addressed. This article offers guidance on troubleshooting and fixing WSReset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/updated-fueling-audience-interaction-crafting-intriguing-fb-giving-announcements/"><u>[Updated] Fueling Audience Interaction Crafting Intriguing FB Giving Announcements</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-ultimate-guide-incorporating-informative-commentary-in-youtube-videos-for-2024/"><u>[Updated] The Ultimate Guide Incorporating Informative Commentary in YouTube Videos for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-secrets-to-effortless-iphone-photo-sorting-and-synchronizing-with-icloud/"><u>2024 Approved The Secrets to Effortless iPhone Photo Sorting & Synchronizing with iCloud</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-video-resizing-tools-of-2023-ultimate-guide-to-adjusting-video-quality-on-your-computer-and-web/"><u>Best Video Resizing Tools of 2023: Ultimate Guide to Adjusting Video Quality on Your Computer & Web</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-games-reimagined-utilizing-retroarchs-shaders-effectively/"><u>Classic Games Reimagined: Utilizing RetroArch's Shaders Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-visual-performance-the-ultimate-vram-boosters/"><u>Elevating Visual Performance: The Ultimate VRAM Boosters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-system-features-on-windows-11-devices/"><u>Fine-Tuning System Features on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/highlighting-key-features-windows-11-feb-update/"><u>Highlighting Key Features: Windows 11, FEB Update</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-from-motorola-moto-e13-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Motorola Moto E13 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-razer-synapse-not-detecting-razer-devices-in-windows-10-and-11/"><u>How to Fix Razer Synapse Not Detecting Razer Devices in Windows 10 & 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/how-to-minimize-insurance-scams-and-surpass-client-satisfaction/"><u>How to Minimize Insurance Scams & Surpass Client Satisfaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-approaches-to-solve-elevation-prompt-issues-on-winos/"><u>Masterful Approaches to Solve Elevation Prompt Issues on WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-os-setup-a-guide-to-installing-win11-in-vmware-17/"><u>Optimizing OS Setup: A Guide to Installing Win11 in VMWare 17</u></a></li>
<li><a href="https://blog-min.techidaily.com/passos-detalhados-para-modificar-a-funcao-de-zoom-na-plataforma-movavi/"><u>Passos Detalhados Para Modificar a Função De Zoom Na Plataforma Movavi</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-10t-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Realme 10T 5G Users</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/why-does-my-photo-booth-videos-keep-freezing-in-2024/"><u>Why Does My Photo Booth Videos Keep Freezing, In 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    