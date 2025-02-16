---
title: "Maximizing Efficiency: Adding WordPad Keyboard Triggers in Windows 11'S UI"
date: 2025-02-12T01:22:39.902Z
updated: 2025-02-15T17:01:08.948Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximizing Efficiency: Adding WordPad Keyboard Triggers in Windows 11'S UI"
excerpt: "This Article Describes Maximizing Efficiency: Adding WordPad Keyboard Triggers in Windows 11'S UI"
keywords: Efficient Windows 11 Usage,WordPad Keyboard Triggers,UI Optimization Techniques,Streamline Office Windows 11,Improve Window Interface,Enhancing Keyboard Functions,Productivity in Windows 11
thumbnail: https://thmb.techidaily.com/5101a256be44324944567b3cdefbcb470dad072a31cdc714305925ec88d3af54.jpg
---

## Maximizing Efficiency: Adding WordPad Keyboard Triggers in Windows 11'S UI

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

6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-break-free-top-10-exclusive-web-photo-workstations/"><u>[New] In 2024, Break Free Top 10 Exclusive Web Photo Workstations</u></a></li>
<li><a href="https://some-approaches.techidaily.com/complete-guide-disconnecting-a-printer-from-your-pc-running-on-windows-11-or-10/"><u>Complete Guide: Disconnecting a Printer From Your PC Running on Windows 11 or 10</u></a></li>
<li><a href="https://techtrends.techidaily.com/contents-of-a-standard-nintendo-switch-packaging-setup/"><u>Contents of a Standard Nintendo Switch Packaging Setup</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-biometrics-what-are-these-technologies-all-about/"><u>Decoding Biometrics: What Are These Technologies All About?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-pathway-to-windowsstore-folder/"><u>Decoding the Pathway to WindowsStore Folder</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/high-def-streaming-cameras-for-social-media-giants-for-2024/"><u>High-Def Streaming Cameras for Social Media Giants for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-vivo-s17e-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Vivo S17e To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-concealment-of-wireless-networks-windows-style/"><u>Masterful Concealment of Wireless Networks, Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-java-install-glitches/"><u>Mastering the Art of Fixing Java Install Glitches</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/quick-solutions-resolving-the-80004001-error-on-windows-11-without-hassle/"><u>Quick Solutions: Resolving the 80004001 Error on Windows 11 Without Hassle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-screen-brilliance-overcoming-windows-11-limits/"><u>Reigniting Screen Brilliance: Overcoming Windows 11 Limits</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/restoring-default-sound-configuration-on-windows-a-step-by-step-guide/"><u>Restoring Default Sound Configuration on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrect-your-device-reviving-dead-usb-connections-win/"><u>Resurrect Your Device: Reviving Dead USB Connections Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slowing-down-lifes-exuberance-in-your-windows-environment/"><u>Slowing Down Life's Exuberance in Your Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-install-microsofts-pc-manager/"><u>Steps to Install Microsoft's PC Manager</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/taming-language-through-ai-understanding-bot-content-filters/"><u>Taming Language Through AI: Understanding Bot Content Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-repairing-directionally-inconsistent-headphone-output/"><u>Win10: Repairing Directionally Inconsistent Headphone Output</u></a></li>
</ul></div>

