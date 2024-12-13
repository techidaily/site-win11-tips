---
title: "Window Wise: Stop Rounded Corner Style"
date: 2024-12-06T22:55:48.214Z
updated: 2024-12-12T19:02:46.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Window Wise: Stop Rounded Corner Style"
excerpt: "This Article Describes Window Wise: Stop Rounded Corner Style"
keywords: Square Windows,Anti-Round Window,Rectangular Glass,No Curves in Frames,Straight Edges Design,Traditional Window Styles,Rounded Corners Avoidance
thumbnail: https://thmb.techidaily.com/a2e90f9c59ddfc76d24d52ddf99c58f1453c310ceab2f51cc25530b47d90892e.jpg
---

## Window Wise: Stop Rounded Corner Style

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ree-audio-treasures-to-amplify-youtube-for-2024/"><u>[New] Free Audio Treasures to Amplify YouTube for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-8-most-popular-instagram-after-effects-packs/"><u>[New] In 2024, 8 Most Popular Instagram After Effects Packs</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-the-ultimate-entry-editor-for-diverse-tech-landscape-of-2023/"><u>[New] The Ultimate Entry Editor for Diverse Tech Landscape of 2023</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-securely-store-and-download-linkedin-videos-heres-the-top-6-list/"><u>[Updated] In 2024, Securely Store & Download LinkedIn Videos - Here's the Top 6 List</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-visibility-features-mastering-snapchats-star/"><u>2024 Approved High-Visibility Features Mastering Snapchat's Star</u></a></li>
<li><a href="https://techtrends.techidaily.com/1726219888474-mp4movavi/"><u>動画加工におけるMP4ファイル改良「Movavi」を使った詳しいガイド</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-law-filter-features/"><u>Navigating Through Windows LAW Filter Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-faded-boot-prompts-steps/"><u>Redesigning Faded Boot Prompts: Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-creativity-microsofts-surface-studio-2-insight/"><u>Revamping Creativity: Microsoft's Surface Studio 2 Insight</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-windows-family-safety-solutions-for-malfunctions/"><u>Reviving Your Windows Family Safety: Solutions for Malfunctions</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-vivo-y55s-5g-2023-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Vivo Y55s 5G (2023)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-misused-system-tokens-on-windows/"><u>Tips for Troubleshooting “Misused System Tokens” On Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-infinix-smart-7-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Infinix Smart 7 Phone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    