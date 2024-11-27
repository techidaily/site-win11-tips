---
title: "Customizing Text Entry Interface: Add WordPad Command Keys to Window's Menu"
date: 2024-11-24T17:56:33.110Z
updated: 2024-11-27T17:36:22.649Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing Text Entry Interface: Add WordPad Command Keys to Window's Menu"
excerpt: "This Article Describes Customizing Text Entry Interface: Add WordPad Command Keys to Window's Menu"
keywords: Window's Menu Customization,WordPad Key Integration,UI Text Input Enhancement,Windows Menu Accessibility,Add-On Command Functionality,Interface Text Editing Tools,Personalized Keyboard Controls
thumbnail: https://thmb.techidaily.com/86eaf732ac0282547acec52c64c3976ebfde5c25b2b266f861ae95d9b96270a9.jpg
---

## Customizing Text Entry Interface: Add WordPad Command Keys to Window's Menu

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-knowledge.techidaily.com/updated-samsung-bd-j5900-review-2023-update/"><u>[Updated] Samsung BD-J5900 Review - 2023 Update</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-steps-to-acquire-free-picture-frame-videos/"><u>[Updated] Steps to Acquire Free Picture Frame Videos</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-power-of-creativity-magix-video-pro-x-demystified/"><u>2024 Approved The Power of Creativity Magix Video Pro X Demystified</u></a></li>
<li><a href="https://win-able.techidaily.com/collaborative-endeavors-reach-new-heights-with-the-official-release-of-it-takes-two/"><u>Collaborative Endeavors Reach New Heights with the Official Release of 'It Takes Two'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-strategies-for-retrieving-nvidias-missing-settings/"><u>Comprehensive Strategies for Retrieving NVIDIA's Missing Settings</u></a></li>
<li><a href="https://tech-revival.techidaily.com/create-mesmerizing-graphics-discover-8-inspiring-dall-e-3-text-prompts/"><u>Create Mesmerizing Graphics: Discover 8 Inspiring DALL-E 3 Text Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-common-blue-screen-errors-vmware-win11-edition/"><u>Fixing Common Blue Screen Errors: VMware, Win11 Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-harnessing-tech-acquiring-fb-status-video-content/"><u>In 2024, Harnessing Tech Acquiring FB Status Video Content</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-the-world-of-youtube-editing-using-finalcut-pro-for-2024/"><u>Navigating the World of YouTube Editing Using FinalCut Pro for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-limited-usb-controller-space-on-pcs/"><u>Resolving Limited USB Controller Space on PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/speaking-volumes-how-mondly-became-the-leading-app/"><u>Speaking Volumes: How Mondly Became the Leading App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tools-to-enhance-your-desktop-writing-skills-windows/"><u>Top Tools to Enhance Your Desktop Writing Skills (Windows)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/troubleshooting-guide-for-when-your-ps4-fails-to-play-dvds-understanding-and-fixing-common-issues/"><u>Troubleshooting Guide for When Your PS4 Fails to Play DVDs – Understanding & Fixing Common Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-mechanics-of-law-filters-on-windows-os/"><u>Understanding the Mechanics of LAW Filters on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-invisible-wired-connections-windows-guide/"><u>Unmasking Invisible Wired Connections: Windows Guide</u></a></li>
</ul></div>

