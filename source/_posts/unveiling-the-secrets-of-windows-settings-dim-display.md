---
title: "Unveiling the Secrets of Windows Settings: 'Dim Display'"
date: 2024-06-25T16:31:40.328Z
updated: 2024-06-26T16:31:40.328Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Secrets of Windows Settings: 'Dim Display'"
excerpt: "This Article Describes Unveiling the Secrets of Windows Settings: 'Dim Display'"
keywords: Dim Windows View,Windows Display Tips,Low Contrast Mode,Adjust Windows Brightness,Reduce Screen Glare,Optimize Windows UI,Custom Dark Theme Settings
thumbnail: https://thmb.techidaily.com/0b81880445efb7746c34685a24a5e53155bfff0ac907d2d7a06d83968e5eaef1.jpg
---

## Unveiling the Secrets of Windows Settings: 'Dim Display'

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

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
<li><a href="https://win11-tips.techidaily.com/the-path-to-reinstating-default-windows-backups/"><u>The Path to Reinstating Default Windows Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-virtualboxs-usb-failure-message-a-step-by-step-guide-for-windows-users/"><u>Resolving VirtualBox's USB Failure Message: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-isdonedll-complications-quickly/"><u>Solving Windows ISDone.dll Complications Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/experience-the-pinnacle-of-windows-interactivity/"><u>Experience the Pinnacle of Windows Interactivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-cannot-open-files-in-windows-system/"><u>How to Resolve 'Cannot Open' Files in Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-antiquity-embellishing-old-games-with-retroarch-awards/"><u>Upgrade the Antiquity - Embellishing Old Games With Retroarch Awards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/converting-gmail-to-outlook-on-windows-a-step-by-step-guide/"><u>Converting Gmail To Outlook on Windows – A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicate-unintended-mouse-scrolling-with-these-7-tricks/"><u>Eradicate Unintended Mouse Scrolling with These 7 Tricks</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-rotate-resize-and-refine-top-10-online-video-editors/"><u>Updated In 2024, Rotate, Resize, and Refine Top 10 Online Video Editors</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-voice-in-unison-for-the-digital-stage-for-2024/"><u>[Updated] Voice-in-Unison for the Digital Stage for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-how-to-use-speed-ramping-to-create-an-intense-action-footage/"><u>New 2024 Approved How To Use Speed Ramping to Create an Intense Action Footage</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/thriving-on-instagram-vids-blueprint-for-effective-content-strategies/"><u>Thriving on Instagram Vids  Blueprint for Effective Content Strategies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-empower-your-filmmaking-skills-using-phone-cameras-for-recording/"><u>[New] 2024 Approved  Empower Your Filmmaking Skills  Using Phone Cameras for Recording</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-fix-apple-iphone-xr-stuck-on-data-transfer-verified-solution-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Fix Apple iPhone XR Stuck on Data Transfer Verified Solution! | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-tecno-spark-10-pro-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Tecno Spark 10 Pro</u></a></li>
<li><a href="https://audio-editing.techidaily.com/how-to-fade-in-and-fade-out-audio-in-imovie/"><u>How to Fade in and Fade Out Audio in iMovie?</u></a></li>
</ul></div>
