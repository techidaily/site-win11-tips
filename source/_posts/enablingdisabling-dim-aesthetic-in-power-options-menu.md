---
title: Enabling/Disabling Dim Aesthetic in Power Options Menu
date: 2024-09-15T19:40:08.112Z
updated: 2024-09-16T23:00:33.509Z
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-passionate-communicator-evaluation-revision-viii/"><u>[New] 2024 Approved Passionate Communicator Evaluation - Revision VIII</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-mastering-the-art-of-affordable-data-storage-cloud-for-2024/"><u>[New] Mastering the Art of Affordable Data Storage (Cloud) for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-video-valedictions-sign-off-strategies-for-online-platforms/"><u>[New] Video Valedictions Sign-Off Strategies for Online Platforms</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-unbeatable-prices-for-top-budget-4k-cameras-(1000-for-2024/"><u>[Updated] Unbeatable Prices for Top Budget 4K Cameras (<$1,000) for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-top-value-hd-cameras-for-extreme-sports-for-2024/"><u>10 Top Value HD Cameras for Extreme Sports for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-role-of-ram-reservation-on-windows/"><u>Demystifying the Role of RAM Reservation on Windows</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-videography-quality-top-7-sound-effects-pick/"><u>Elevate Videography Quality Top 7 Sound Effects Pick</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-sidestep-windows-11-expiration-soon-issue/"><u>How to Sidestep Windows 11 'Expiration Soon' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-utilizing-ms-tools-for-windows-11-issues/"><u>In-Depth Analysis: Utilizing MS Tools for Windows 11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimize-latency-streamlining-windows-vlc-videos/"><u>Minimize Latency: Streamlining Windows VLC Videos</u></a></li>
<li><a href="https://tech-hub.techidaily.com/quick-method-for-changing-dall-e-3s-webp-designs-into-jpg-or-png-files/"><u>Quick Method for Changing DALL-E 3'S WebP Designs Into JPG or PNG Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-and-mending-errors-in-win10win11-secure-software/"><u>Unmasking & Mending Errors in Win10/Win11 Secure Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115944/19272" target="_top" id="2115944">
  <img src="//a.impactradius-go.com/display-ad/19272-2115944" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

