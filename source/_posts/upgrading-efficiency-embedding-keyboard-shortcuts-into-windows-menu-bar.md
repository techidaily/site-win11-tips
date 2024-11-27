---
title: "Upgrading Efficiency: Embedding Keyboard Shortcuts Into Windows Menu Bar"
date: 2024-11-26T16:08:26.864Z
updated: 2024-11-27T17:45:52.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Upgrading Efficiency: Embedding Keyboard Shortcuts Into Windows Menu Bar"
excerpt: "This Article Describes Upgrading Efficiency: Embedding Keyboard Shortcuts Into Windows Menu Bar"
keywords: Windows Shortcut Enhancement,Menu Bar Integration,Efficiency Upgrade Wins,Keyboard Quick Access,Accelerated User Interface,Shortcuts in Windows,UI Optimization Tools
thumbnail: https://thmb.techidaily.com/1acb8c811dd75a749590a9459a8ce73dd17ec95c9b2687aeea798f4dbe27d8a4.jpg
---

## Upgrading Efficiency: Embedding Keyboard Shortcuts Into Windows Menu Bar

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-flashframe-crafter/"><u>[New] 2024 Approved FlashFrame Crafter</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-the-ultimate-roadmap-views-subscribers-and-money-on-youtube/"><u>[New] In 2024, The Ultimate Roadmap Views, Subscribers & Money on Youtube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-volume-tailored-keyboard-shortcuts-win11/"><u>Crafting Volume Tailored Keyboard Shortcuts (Win11)</u></a></li>
<li><a href="https://data-wizards.techidaily.com/demystifying-error-unplayable-videos-explained/"><u>Demystifying Error: Unplayable Videos Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-your-windows-11-ui-ungrouping-tips/"><u>Ease Your Windows 11 UI: Ungrouping Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-command-execution-with-advanced-windows-tool/"><u>Elevate Command Execution with Advanced Windows Tool</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/experience-the-power-of-sound-with-razer-leviathan-v2-a-detailed-review-tech-innovation-hub/"><u>Experience the Power of Sound with Razer Leviathan V2 - A Detailed Review | Tech Innovation Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-defeat-installation-obstacles-a-guide-for-win11-users/"><u>How to Defeat Installation Obstacles: A Guide for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/imessage-integration-on-windows-systems-unveiled/"><u>IMessage Integration on Windows Systems Unveiled</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/launch-your-content-with-free-intros-for-2024/"><u>Launch Your Content with Free Intros for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-control-over-windows-11-context-items/"><u>Regaining Control Over Windows 11 Context Items</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-realme-12-proplus-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Realme 12 Pro+ 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-outlook-schedule-on-windows-pcs/"><u>Tailoring Your Outlook Schedule on Windows PCs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-asus-rog-flow-x13-an-expert-evaluation-of-its-sizable-display-amidst-other-tradeoffs/"><u>The ASUS ROG Flow X13: An Expert Evaluation of Its Sizable Display Amidst Other Tradeoffs</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-mystique-of-a-blue-icon-on-facebook-decoding-its-purpose-and-meaning-for-2024/"><u>The Mystique of a Blue Icon on Facebook Decoding Its Purpose and Meaning for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-boosting-virtual-memory-on-windows-11/"><u>The Ultimate Guide to Boosting Virtual Memory on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-your-windows-app-data-usage/"><u>Unveiling Your Windows App Data Usage</u></a></li>
</ul></div>

