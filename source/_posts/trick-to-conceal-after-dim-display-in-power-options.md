---
title: Trick to Conceal 'After Dim Display' In Power Options
date: 2025-02-25T20:28:07.053Z
updated: 2025-03-04T22:20:41.066Z
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

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

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
<li><a href="https://facebook-videos.techidaily.com/new-prime-fb-video-snatcher-and-upgrades-for-firefox/"><u>[New] Prime FB Video Snatcher & Upgrades for FireFox</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-how-to-use-picture-in-picture-on-chrome-on-all-platforms/"><u>[Updated] 2024 Approved How to Use Picture in Picture on Chrome on All Platforms</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-swift-playback-in-tiktok-enhancing-performance/"><u>[Updated] Swift Playback in TikTok Enhancing Performance</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-accelerate-conversion-srt-to-text-txt-in-minutes-only/"><u>2024 Approved Accelerate Conversion SRT to Text (TXT) in Minutes Only</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-guide-to-the-nokia-nokia72-how-it-stands-out-among-competitive-devices/"><u>Comprehensive Guide to the Nokia Nokia7.2: How It Stands Out Among Competitive Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/conversion-de-fichiers-au-vers-wav-service-gratuit-en-ligne-avec-movavi/"><u>Conversion De Fichiers Au Vers WAV - Service Gratuit en Ligne Avec Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-strategies-for-tracking-windows-conversations/"><u>Expert Strategies for Tracking Windows Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lexicon-loops-fast-definitions-in-windows-11/"><u>Lexicon Loops: Fast Definitions in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-windows-terminals-focus-mode-engagementdisengagement/"><u>Mastery of Windows Terminal’s Focus Mode Engagement/Disengagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-simple-adding-menu-items-for-your-win11-os/"><u>Quick and Simple: Adding Menu Items for Your Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-unresponsive-email-banners-in-outlook-windows/"><u>Tackling Unresponsive Email Banners in Outlook Windows</u></a></li>
</ul></div>

