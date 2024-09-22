---
title: Enabling/Disabling Dim Aesthetic in Power Options Menu
date: 2024-09-17T22:46:55.376Z
updated: 2024-09-21T20:10:17.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Dim Aesthetic in Power Options Menu
excerpt: This Article Describes Enabling/Disabling Dim Aesthetic in Power Options Menu
keywords: Turn Off Aesthetic Mode,Disable Brightness Slider,Enable System Display,Power Option Customization,Adjust Screen Appearance,Opt Out Aesthetics Mode,Dim Screenscape Control
thumbnail: https://thmb.techidaily.com/d529ee3f9777395e3e6b4e63c228e25fbb4330a46358a8f92c3ef7608136a4ab.jpg
---

## Enabling/Disabling Dim Aesthetic in Power Options Menu

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
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-perfect-your-videography-skills-with-our-expert-tutorial-series/"><u>[Updated] 2024 Approved Perfect Your Videography Skills with Our Expert Tutorial Series</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-flawless-endgame-in-vr-worlds/"><u>[Updated] Flawless Endgame in VR Worlds</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-unlock-your-youtube-potential-idea-generation-guide-for-2024/"><u>[Updated] Unlock Your YouTube Potential Idea Generation Guide for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-11-brain-boosting-trivia-shows-for-24/"><u>2024 Approved Top 11 Brain-Boosting Trivia Shows for '24</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Asus ROG Phone 8? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-conversion-transforming-vob-files-into-high-quality-m2ts-format-with-ease-movavi/"><u>Free Online Conversion: Transforming VOB Files Into High-Quality M2TS Format with Ease - Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/los-10-mejores-programas-para-crear-mixes-de-musica-una-guia-completa/"><u>Los 10 Mejores Programas Para Crear Mixes De Música: Una Guía Completa</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-cost-web-tool-for-mp3-format-switching-by-movavis-easy-snd-to-mp3-solution/"><u>No-Cost Web Tool for MP3 Format Switching by Movavi's Easy SND to MP3 Solution</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unlock-insights-into-video-popularity-via-rank-trackers-for-2024/"><u>Unlock Insights Into Video Popularity via Rank Trackers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mod-avi-movavi/"><u>무료 MOD AVI 펑션을 쉽고 사용하기위한 웹 공간 내 스타일리시 도구 - Movavi</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

