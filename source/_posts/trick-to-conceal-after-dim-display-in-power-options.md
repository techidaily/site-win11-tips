---
title: Trick to Conceal 'After Dim Display' In Power Options
date: 2025-01-25T03:59:51.420Z
updated: 2025-01-31T16:24:24.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
excerpt: This Article Describes Trick to Conceal 'After Dim Display' In Power Options
keywords: Hide After-Dim Screen Option,Power Plan Adjustment Trick,Dim Display Masking Tip,Conceal Extra Views,Screenshop Blackout Method,Oversee Brightness Reduction,Hide Ambient Light Feature
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Trick to Conceal 'After Dim Display' In Power Options

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-fading-out-sound-fl-studio-guide-for-2024/"><u>[New] Fading Out Sound FL Studio Guide for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-discover-the-5-best-android-software-for-ps2-games/"><u>[New] In 2024, Discover the 5 Best Android Software for PS2 Games</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-laptop-touchpad-drivers-for-windows-11-free-download-and-installation-guide/"><u>ASUS Laptop Touchpad Drivers for Windows 11 - Free Download and Installation Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-your-cli-space-making-windows-terminal-default/"><u>Customizing Your CLI Space: Making Windows Terminal Default</u></a></li>
<li><a href="https://win-blog.techidaily.com/effective-solutions-for-resolving-steam-error-code-130/"><u>Effective Solutions for Resolving Steam Error Code 130</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-version-22h2-update-not-appearing/"><u>Fixing Windows 11 Version 22H2 Update Not Appearing</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-samsung-galaxy-s24-ultra-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-fixing-steams-file-permission-blunders-in-win11/"><u>Guidelines for Fixing Steam's File Permission Blunders in Win11</u></a></li>
<li><a href="https://win-forum.techidaily.com/master-the-art-of-file-management-avoid-locked-folders-in-windows-11-for-a-cleaner-drive/"><u>Master the Art of File Management: Avoid-Locked-Folders in Windows 11 for a Cleaner Drive</u></a></li>
<li><a href="https://win-updates.techidaily.com/navigating-microsoft-windows-how-to-access-your-control-panel-from-the-start-menu-with-yl-software-help/"><u>Navigating Microsoft Windows: How to Access Your Control Panel From the Start Menu with YL Software Help</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-disable-script-execution-4-solutions-for-ps-load-failure/"><u>Overcoming Disable Script Execution: 4 Solutions for PS Load Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reawaken-chrome-on-win11-essential-troubleshooting-steps/"><u>Reawaken Chrome on Win11 – Essential Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-steams-captcha-invalid-issue/"><u>Resolving Steam's CAPTCHA Invalid Issue</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175727068-revolutionize-your-silent-pc-experience-with-configurable-cases-and-glowing-fans-by-be-quiet/"><u>Revolutionize Your Silent PC Experience with Configurable Cases & Glowing Fans by Be Quiet!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-file-resolution-6-ultimate-remedies-to-powerpoint-errors/"><u>Speedy File Resolution: 6 Ultimate Remedies to PowerPoint Errors</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-8-chatgpt-triggers-to-combat-online-interruptions-effectively/"><u>Top 8 ChatGPT Triggers to Combat Online Interruptions Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-error-messages-fix-for-user-not-valid-windows-1111/"><u>Unraveling Error Messages: Fix for 'User Not Valid' Windows 11/11</u></a></li>
</ul></div>

