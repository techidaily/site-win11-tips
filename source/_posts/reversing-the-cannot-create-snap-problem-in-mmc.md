---
title: Reversing the 'Cannot Create Snap' Problem in MMC
date: 2024-11-26T16:26:37.837Z
updated: 2024-11-27T16:30:45.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing the 'Cannot Create Snap' Problem in MMC
excerpt: This Article Describes Reversing the 'Cannot Create Snap' Problem in MMC
keywords: Fix Snap Error in MMC,Resolve Cannot Create Snap Issue,Eliminate Snap Creation Failure,Counteract MMC Snap Problems,Overcome MMC Snapshot Errors,Address MMC 'Cannot Create',Tackle MMC Snap Creation Issue
thumbnail: https://thmb.techidaily.com/06e4228770e6068ed6a3887b57608ffc3ec670ddf3f56b58d3f796cd0fa916df.jpg
---

## Reversing the 'Cannot Create Snap' Problem in MMC

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-decoding-whatsapps-vocal-messaging-innovation-for-2024/"><u>[New] Decoding WhatsApp's Vocal Messaging Innovation for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-pace-kings-and-queens-of-the-olympics-year-2022/"><u>[New] The Pace Kings & Queens of the Olympics, Year 2022</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-perfecting-pitched-lines-writing-natural-conversations-for-2024/"><u>[Updated] Perfecting Pitched Lines Writing Natural Conversations for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pixel-pizzazz-top-10-screenshot-sticker-enhancers-for-iphonesandroids/"><u>2024 Approved Pixel Pizzazz Top 10 Screenshot Sticker Enhancers for iPhones/Androids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-dark-screens-on-win1011-instantly/"><u>Conquering Dark Screens on Win10/11 Instantly</u></a></li>
<li><a href="https://techidaily.com/is-your-honor-magic5-ultimate-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Honor Magic5 Ultimate working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-biometric-use-for-domains-on-windows-11/"><u>Optimizing Biometric Use for Domains on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-w11-printer-problems-caused-by-ad-ds-errors/"><u>Overcoming W11 Printer Problems Caused by AD DS Errors</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mov-movies-on-xiaomi-redmi-12-is-it-possible-by-aiseesoft-video-converter-play-mov-on-android/"><u>Play MOV movies on Xiaomi Redmi 12, is it possible?</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-issue-unreal-engine-4-glitch-causes-outriders-ue4-madness-error/"><u>Resolved Issue: Unreal Engine 4 Glitch Causes 'Outriders - UE4 Madness' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-file-transfer-capability-to-utorrent-on-win/"><u>Restoring File Transfer Capability to uTorrent on Win</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-the-secrets-of-building-budget-friendly-youtube-ads-for-2024/"><u>Unlock the Secrets of Building Budget-Friendly YouTube Ads for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/visual-storytelling-with-warped-textual-elements-for-2024/"><u>Visual Storytelling with Warped Textual Elements for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    