---
title: "Improving Text Accessibility: Incorporating WordPad Triggers in Windows 11"
date: 2024-11-24T17:13:17.222Z
updated: 2024-11-27T17:03:13.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Improving Text Accessibility: Incorporating WordPad Triggers in Windows 11"
excerpt: "This Article Describes Improving Text Accessibility: Incorporating WordPad Triggers in Windows 11"
keywords: Windows Text Acessibility,WordPad Enhancement,Windows 11 Readability,Triggered Accessibility Features,Text Editing Access,Inclusive Windows Tools,WordPad Usage Guide
thumbnail: https://thmb.techidaily.com/19639e4ac05cfca12a97f4159ad1c138d0c42ce69fcff51c42722b7ff4015400.jpg
---

## Improving Text Accessibility: Incorporating WordPad Triggers in Windows 11

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/ocial-media-magic-viral-trends-in-youtube-hashing/"><u>[New] Social Media Magic Viral Trends in YouTube Hashing</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-unlocking-the-secrets-quickly-change-your-characters-vocal-tone-pubg-for-2024/"><u>[Updated] Unlocking the Secrets Quickly Change Your Character's Vocal Tone (PUBG) for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-why-are-status-emojis-blue-understanding-fbs-visual-language/"><u>[Updated] Why Are Status Emojis Blue? Understanding FB's Visual Language</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-the-0x800704cf-error-on-windows-devices/"><u>Eliminating the 0X800704CF Error on Windows Devices</u></a></li>
<li><a href="https://win-able.techidaily.com/essential-fixes-for-the-latest-modern-warfare-launch-failures-on-personal-computers/"><u>Essential Fixes for the Latest Modern Warfare Launch Failures on Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-fundamental-techniques-to-rectify-login-conflicts-on-windows-11/"><u>Five Fundamental Techniques to Rectify Login Conflicts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-losing-windows-11-taskbar-chat-affect-you/"><u>How Does Losing Windows 11 Taskbar Chat Affect You?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-overcome-windows-memory-not-recorded-problems/"><u>How to Overcome Windows Memory Not Recorded Problems</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/interactive-guide-to-microsofts-cutting-edge-surface-and-surface-pro-pcs-now-with-smart-copilotplus-features-for-elevated-computing-experience/"><u>Interactive Guide to Microsoft's Cutting-Edge Surface & Surface Pro PCs Now With Smart Copilot+ Features for Elevated Computing Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-missing-sections-of-navigation-view/"><u>Remedying Missing Sections of Navigation View</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-solutions-for-overcoming-the-steam-disk-write-failed-issue/"><u>Simple Solutions for Overcoming the 'Steam Disk Write Failed' Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-avoid-high-cpu-load-during-gameplay-on-pc/"><u>Strategies to Avoid High CPU Load During Gameplay on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-enhance-f-keys-performance-in-windows-11/"><u>Tweak: Enhance F-Keys' Performance in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-ai-how-machines-grasp-human-sentiments/"><u>Unveiling AI: How Machines Grasp Human Sentiments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-update-and-its-companion-service/"><u>Unveiling Windows Update and Its Companion Service</u></a></li>
<li><a href="https://review-topics.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Vivo Y27s | Dr.fone</u></a></li>
</ul></div>

