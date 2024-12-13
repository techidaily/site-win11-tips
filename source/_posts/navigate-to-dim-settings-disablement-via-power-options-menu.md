---
title: Navigate to Dim Settings Disablement Via Power Options Menu
date: 2024-12-09T00:24:15.962Z
updated: 2024-12-13T01:54:12.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to Dim Settings Disablement Via Power Options Menu
excerpt: This Article Describes Navigate to Dim Settings Disablement Via Power Options Menu
keywords: Navigate Power Save,Dim Display Disable,Settings Control Panel,Power Options Access,Switch Off Dimming,Control Brightness Levels,Menu Power Change Mode
thumbnail: https://thmb.techidaily.com/829637766daad5158a0e2799ab45977f98c34111cdb4f87264835a3e2bfe371a.jpg
---

## Navigate to Dim Settings Disablement Via Power Options Menu

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-comparing-instagrams-latest-features-reels-vs-stories/"><u>[New] In 2024, Comparing Instagram's Latest Features Reels Vs Stories</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-the-craft-of-engaging-your-viewers-from-the-start/"><u>[Updated] Mastering the Craft of Engaging Your Viewers From The Start</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/5-most-effective-methods-to-unlock-iphone-6s-plus-in-lost-mode-drfone-by-drfone-ios/"><u>5 Most Effective Methods to Unlock iPhone 6s Plus in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme GT Neo 5 SE? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-1011-click-no-open-folders/"><u>Eliminating Windows 10/11 Click No-Open Folders</u></a></li>
<li><a href="https://tech-haven.techidaily.com/harness-the-potential-of-chatgpt-for-remote-freelancing-success-with-these-cups/"><u>Harness the Potential of ChatGPT for Remote Freelancing Success with These Cups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-eliminate-frustrating-windows-bsod-instances/"><u>How to Eliminate Frustrating Windows BSOD Instances</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-vivo-v29-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Vivo V29 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-horizon-zero-dawn-adventure-with-optimal-fps-enhancement-techniques/"><u>Maximize Your Horizon Zero Dawn Adventure with Optimal FPS Enhancement Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-disarm-windows-security-alarms/"><u>Quick Fixes to Disarm Windows Security Alarms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-and-validating-windows-11-with-activation-methods/"><u>Securing and Validating Windows 11 with Activation Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-file-save-location-mistakes-in-win-1011/"><u>Solving File Save Location Mistakes in Win 10/11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/strategies-for-improved-video-zoom-during-virtual-gatherings-google-meet/"><u>Strategies for Improved Video Zoom During Virtual Gatherings (Google Meet)</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unbeatable-portable-amplifier-showcases-impressive-clarity-and-range-for-every-type-of-song-a-review-by-zdnet/"><u>Unbeatable Portable Amplifier Showcases Impressive Clarity & Range for Every Type of Song - A Review by ZDNET</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-power-of-productivity-with-these-key-win-11-widgets/"><u>Unleash the Power of Productivity with These Key Win 11 Widgets</u></a></li>
</ul></div>

