---
title: "Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11"
date: 2024-06-25T16:54:06.862Z
updated: 2024-06-26T16:54:06.862Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11"
excerpt: "This Article Describes Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11"
keywords: Workflow Streamlining,Wordpad Keyboard Shortcuts,Context Menu Enhancement,Integration Techniques,Windows 11 Efficiency,User Interface Improvement,Productivity Tools Update
thumbnail: https://thmb.techidaily.com/1f7a28a8bb8145eaefcf7bd927fe30950467d63b1317d80297e6274f57adb5a8.jpg
---

## Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see [how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
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
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see [how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

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
<li><a href="https://win11-tips.techidaily.com/winning-over-old-titles-directing-them-to-my-pictures/"><u>Winning Over Old Titles: Directing Them to My Pictures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-pc-storage-identifying-excess-disk-usage-in-windows/"><u>Maximizing PC Storage: Identifying Excess Disk Usage in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-task-scheduler-guide-to-efficient-batch-processing/"><u>The Task Scheduler Guide to Efficient Batch Processing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-server-hiccups-in-ms-store-win-1011/"><u>Navigating Through Server Hiccups in MS Store, Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-preparedness-generate-boot-media-in-three-steps/"><u>Windows 11 Preparedness: Generate Boot Media in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-cyber-game-top-7-techniques-for-uac-safety/"><u>Winning the Cyber Game: Top 7 Techniques for UAC Safety</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assessing-windows-subsystem-for-linux-impact/"><u>Assessing Windows Subsystem for Linux Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-a-move-and-copy-to-folder-context-menu-options-in-windows-11-and-11/"><u>How to Add a Move and Copy to Folder Context Menu Options in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-cannot-continue-error-in-amd-installation/"><u>Overcoming the 'Cannot Continue' Error in AMD Installation</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-organize-your-videos-best-mp4-metadata-taggers-for-pc-and-mac/"><u>New In 2024, Organize Your Videos Best MP4 Metadata Taggers for PC and Mac</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-comprehensive-list-of-the-best-10-low-cost-video-production-schools-on-youtube/"><u>A Comprehensive List of the Best 10 Low-Cost Video Production Schools on YouTube</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-guide-to-unlock-your-nubia-red-magic-8s-pro-by-drfone-android/"><u>Full Guide to Unlock Your Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-simplified-approach-to-embedding-multiple-video-playlists-from-youtube/"><u>2024 Approved  Simplified Approach to Embedding Multiple Video Playlists From YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-cutting-edge-strategies-for-choosing-best-fpv-drone-blades/"><u>[Updated] In 2024, Cutting-Edge Strategies for Choosing Best FPV Drone Blades</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-hop-to-it-wondershare-filmora-easter-sale-get-your-discount-now-for-2024/"><u>New Hop to It! Wondershare Filmora Easter Sale - Get Your Discount Now for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-prestige-choices-top-rated-sites-for-securing-snapalert-music/"><u>[Updated] In 2024, Prestige Choices  Top-Rated Sites for Securing SnapAlert Music</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Vivo V30 Lite 5G? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-haul-videography-unlocked-step-by-step-guide-for-enthusiasts/"><u>In 2024, Haul Videography Unlocked  Step-by-Step Guide for Enthusiasts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/final-cuts-ultimate-10-plug-in-essentials-list-for-2024/"><u>Final Cut's Ultimate 10 Plug-In Essentials List for 2024</u></a></li>
</ul></div>
