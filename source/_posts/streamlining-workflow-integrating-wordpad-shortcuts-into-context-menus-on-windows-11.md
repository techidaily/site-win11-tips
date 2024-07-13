---
title: "Streamlining Workflow: Integrating WordPad Shortcuts Into Context Menus on Windows 11"
date: 2024-07-12T17:25:02.531Z
updated: 2024-07-13T17:25:02.531Z
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
<li><a href="https://win11-tips.techidaily.com/enhance-control-running-task-manager-with-admin-rights-in-win11/"><u>Enhance Control: Running Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/10-ultimate-immersive-vr-video-hits/"><u>10 Ultimate Immersive VR Video Hits</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-cutting-confinement-with-comedy-best-facebook-incarceration-laughs-of-today/"><u>2024 Approved  Cutting Confinement with Comedy  Best Facebook Incarceration Laughs of Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-audacity-error-code-9999-in-windows-1110/"><u>How to Fix the Audacity Error Code 9999 in Windows 11/10</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-videopad-video-editor-buying-guide-top-features-and-pricing/"><u>2024 Approved Videopad Video Editor Buying Guide Top Features and Pricing</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-how-to-delete-messages-on-discord-in-bulk/"><u>2024 Approved  How to Delete Messages On Discord In Bulk</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-your-program-visibility-win11-style/"><u>Fine-Tuning Your Program Visibility: Win11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-censored-windows-11-theme-options-with-registry/"><u>Unveiling Censored Windows 11 Theme Options with Registry</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-itel-s23plus-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Itel S23+ Back to Operation | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-transform-your-gopro-footage-quick-and-easy-video-editing-on-macbook/"><u>Updated Transform Your GoPro Footage Quick and Easy Video Editing on MacBook</u></a></li>
<li><a href="https://fox-direct.techidaily.com/5-best-sd-card-for-gopro-cameras-hero-87-included/"><u>5 Best SD Card for GoPro Cameras - Hero 8/7 Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-access-to-hardware-spaces-via-win-1011-disks/"><u>Efficient Access to Hardware Spaces via Win 10/11 Disks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-dissecting-social-media-giants-tiktok-meets-snap/"><u>2024 Approved  Dissecting Social Media Giants  TikTok Meets Snap</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-a-compelling-movie-mini-epic-for-2024/"><u>Crafting a Compelling Movie Mini-Epic for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unlocking-cross-media-sharing-power-twitterfacebook/"><u>In 2024, Unlocking Cross-Media Sharing Power (Twitter/Facebook)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-unlimited-chuckles-craftsmanship-no-monetary-requirement/"><u>In 2024, Unlimited Chuckles Craftsmanship  No Monetary Requirement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-pro-efficient-docx-to-pdf-conversion-made-simple/"><u>Win 11 Pro: Efficient DOCX to PDF Conversion Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-strategies-eradicate-wow-error-132-in-1011/"><u>Winning Strategies: Eradicate WoW Error 132 in 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-terminal-and-powershell-identifying-what-sets-them-aside/"><u>Windows Terminal and PowerShell: Identifying What Sets Them Aside</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719371847315-fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-practices-for-converting-webp-to-jpg-format-for-2024/"><u>Best Practices for Converting WebP to JPG Format for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-8-plus-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone 8 Plus</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-5-best-slow-motion-cameras/"><u>[New] 5 Best Slow Motion Cameras</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-meme-magnate-monetization-pewdiepies-payday/"><u>2024 Approved  Meme Magnate Monetization  PewDiePie’s Payday</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workarounds-for-static-energy-controls-on-windows-11/"><u>Workarounds for Static Energy Controls on Windows 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-inside-look-the-best-youtube-makeup-artists-of-today/"><u>[New] Inside Look  The Best YouTube Makeup Artists of Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battery-friendly-tips-minimize-windows-11-apps-impact/"><u>Battery-Friendly Tips: Minimize Windows 11 Apps' Impact</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-disk-potential-masterful-techniques-in-w10w11/"><u>Unlocking Disk Potential: Masterful Techniques in W10/W11</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-motorola-moto-g34-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-segmentviewer-study-notes-for-2024/"><u>[Updated] SegmentViewer Study Notes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-file-path-of-your-current-wallpaper/"><u>Discover the File Path of Your Current Wallpaper</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-top-rated-video-luminance-adjustment-apps/"><u>New In 2024, Top-Rated Video Luminance Adjustment Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-macos-usability-through-windows-apps/"><u>Boosting macOS Usability Through Windows Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-cutting-edge-image-vault-websites/"><u>[Updated] Cutting-Edge Image Vault Websites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-update-processes-windows-os-explored/"><u>Dissecting Update Processes: Windows OS Explored</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-superior-lineup-elite-webcam-mounts/"><u>2024 Approved  Superior Lineup  Elite Webcam Mounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-in-win10win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 in Win10/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-bypass-chatbot-assistance-in-win-11-key-gen/"><u>Why Bypass Chatbot Assistance in Win 11 Key Gen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-do-you-nullify-windows-hello-in-win11/"><u>How Do You Nullify Windows Hello in Win11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-an-educational-ambiance-for-windows/"><u>Creating an Educational Ambiance for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-win11-written-in-devhomes-script/"><u>Deciphering Win11' Written in DevHome's Script</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-wacatacbml-signature-and-defense-for-windows-users/"><u>Exploring the Depths of Wacatac.B!ml: Signature & Defense for Windows Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-high-ranking-mac-tools-to-replace-standard-bandicam/"><u>[New] High-Ranking Mac Tools to Replace Standard Bandicam</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-google-frp-by-drfone-android/"><u>Full Guide to Bypass Google FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-steam-goals-a-complete-walkthrough/"><u>Clearing Steam Goals: A Complete Walkthrough</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-admin-denial-in-cmd-window-on-windows-10/"><u>Fixing Admin Denial in CMD Window on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-top-windows-platforms-for-ndsswitch-players/"><u>Cutting Edge: Top Windows Platforms for NDS/Switch Players</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-best-10-crazy-cool-examples-of-ar-video/"><u>In 2024, Best 10 Crazy-Cool Examples of AR Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-window-glass-idleness-exploration/"><u>Fundamentals of Window Glass Idleness Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-steam-downloads-for-windows-users/"><u>Turbo-Charging Steam Downloads for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-system-performance-via-alomware-settings-utility/"><u>Enhance System Performance via AlomWare Settings Utility</u></a></li>
</ul></div>
