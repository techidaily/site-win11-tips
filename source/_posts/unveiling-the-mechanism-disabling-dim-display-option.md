---
title: "Unveiling the Mechanism: Disabling 'Dim Display' Option"
date: 2024-06-25T16:56:52.698Z
updated: 2024-06-26T16:56:52.698Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Mechanism: Disabling 'Dim Display' Option"
excerpt: "This Article Describes Unveiling the Mechanism: Disabling 'Dim Display' Option"
keywords: Dim Display Offset,Screen Brightness Control,Invisible Mode Switch,Hide Display Disablement,Low Visibility Turn-Off,Glare Reduction Mechanism,Visuals Mute Functionality
thumbnail: https://thmb.techidaily.com/4344716e214d80fc0302240776bca3183fcb221b8492651a99a24a405c1e3fa0.jpg
---

## Unveiling the Mechanism: Disabling 'Dim Display' Option

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
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unbreakable-passwords-top-four-managers-for-the-new-windows-edition/"><u>Unbreakable Passwords: Top Four Managers for the New Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-steps-to-navigate-windows-system-restore-functions/"><u>Simplified Steps to Navigate Windows' System Restore Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-data-sorting-adding-text-to-windows-11-folders/"><u>Simplifying Data Sorting: Adding Text to Windows 11 Folders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/escape-key-blues-effective-fixes-for-a-non-operational-keys/"><u>Escape Key Blues? Effective Fixes for a Non-Operational Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/character-discovery-windows-11-pathway/"><u>Character Discovery: Windows 11 Pathway</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-storage-activating-windows-11s-compression/"><u>Efficient Storage: Activating Windows 11’S Compression</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2023s-largest-threaded-video-compilation-for-2024/"><u>[Updated] 2023'S Largest Threaded Video Compilation for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-v27-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo V27 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-bring-your-movies-to-life-a-comprehensive-guide-to-adding-audio-in-final-cut-pro/"><u>2024 Approved Bring Your Movies to Life A Comprehensive Guide to Adding Audio in Final Cut Pro</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-selecting-the-superior-hexacopters-for-2024/"><u>[Updated] Selecting the Superior HexaCopters for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Realme C55? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-much-money-flows-from-a-million-views-on-youtube-for-2024/"><u>[Updated] How Much Money Flows From A Million Views On YouTube for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-8-best-tools-to-make-animated-photo-easily/"><u>Updated In 2024, 8 Best Tools to Make Animated Photo Easily</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/streamline-your-workflow-macos-screencast-tutorial-for-2024/"><u>Streamline Your Workflow  MacOS Screencast Tutorial for 2024</u></a></li>
</ul></div>
