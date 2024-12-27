---
title: Trick to Conceal 'After Dim Display' In Power Options
date: 2024-12-26T22:01:09.323Z
updated: 2024-12-27T19:52:27.525Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-digital-rights-unexpected-content-take-downs/"><u>[New] In 2024, Digital Rights Unexpected Content Take-Downs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-traditional-rogues-vs-modern-roguism/"><u>[New] Traditional Rogues Vs. Modern Roguism</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-optimal-room-decorations-for-livestreams/"><u>[Updated] 2024 Approved Optimal Room Decorations for Livestreams</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-revamping-educational-experiences-through-vr/"><u>[Updated] In 2024, Revamping Educational Experiences Through VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-art-of-altering-file-types-on-windows/"><u>Decoding the Art of Altering File Types on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directly-connecting-to-clouds-cdropboxgoogledrive-for-work/"><u>Directly Connecting to Clouds: C:/Dropbox/GoogleDrive for Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-error-x80300024-in-windows-xp-environment/"><u>Fixing Error X80300024 in Windows XP Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-identifying-and-eradicating-vacant-folders-on-pcs/"><u>Guide to Identifying & Eradicating Vacant Folders on PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-motorola-moto-g14-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Motorola Moto G14 Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-joining-the-digital-dialogue-facebook-basics/"><u>In 2024, Joining the Digital Dialogue (Facebook Basics)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-privilege-not-held-error-in-windows-code-0x80070522/"><u>Navigating the Privilege Not Held Error in Windows: Code 0X80070522</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-clarity-top-ten-windows-11-troubleshooting-steps/"><u>Precision in Clarity: Top Ten Windows 11 Troubleshooting Steps</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-dji-phantom-3-pro-drone/"><u>The Ultimate Guide to DJI Phantom 3 Pro Drone</u></a></li>
</ul></div>

