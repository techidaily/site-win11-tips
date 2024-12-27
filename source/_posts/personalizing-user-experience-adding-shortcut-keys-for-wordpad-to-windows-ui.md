---
title: "Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI"
date: 2024-12-20T20:12:55.858Z
updated: 2024-12-27T20:55:26.828Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI"
excerpt: "This Article Describes Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI"
keywords: Personalized UX,Shortcut Keys,Wordpad UI Enhancements,Windows User Experience,Keyboard Customization,Accessibility Features,Efficiency Tools for Windows
thumbnail: https://thmb.techidaily.com/6dd8f57eda55f51f780fa0fbffb1950bf2ad081249b06af69891f71aad7773d2.jpg
---

## Personalizing User Experience: Adding Shortcut Keys for Wordpad to Windows UI

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/udio-alchemy-free-perfectly-crafted-dj-template-videos-for-2024/"><u>[New] Audio Alchemy Free, Perfectly Crafted DJ Template Videos for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-nokia-g310-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Nokia G310 Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dampen-disruptive-desktop-scroll-dynamics/"><u>Dampen Disruptive Desktop Scroll Dynamics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-busy-files-alert-solutions-for-windows-11-users/"><u>Dealing with Busy Files Alert: Solutions for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-quick-boot-mode-to-accelerate-pc-launches-on-windows-11/"><u>Enabling Quick Boot Mode to Accelerate PC Launches on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-timers-swiftly-fix-scheduler-errors/"><u>Enhance Timers: Swiftly Fix Scheduler Errors</u></a></li>
<li><a href="https://driver-download.techidaily.com/eveo-bluetooth-adapter-software-free-download/"><u>EVEO Bluetooth Adapter Software - Free Download</u></a></li>
<li><a href="https://driver-install.techidaily.com/hassle-free-logitech-mouse-driver-update-on-win-7/"><u>Hassle-Free Logitech Mouse Driver Update on Win 7</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-messages-on-infinix-note-30i-by-fonelab-android-recover-messages/"><u>How to restore wiped messages on Infinix Note 30i</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-the-vac-rejected-issue-in-gaming/"><u>How to Sidestep the “VAC Rejected” Issue in Gaming</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-detailed-guide-on-removing-apple-iphone-xr-activation-lock-without-previous-owner-by-drfone-ios/"><u>In 2024, Detailed Guide on Removing Apple iPhone XR Activation Lock without Previous Owner?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-launching-at-optimal-times-a-podcast-guide/"><u>In 2024, Launching at Optimal Times A Podcast Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-docker-in-wsl-2-on-windows-platforms/"><u>Mastering Docker in WSL 2 on Windows Platforms</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solutions-overcome-latency-and-improve-battlefield-5-performance/"><u>Step-by-Step Solutions: Overcome Latency and Improve Battlefield 5 Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-windows-11s-0x800f0922-error/"><u>Strategies to Rectify Windows 11'S 0X800F0922 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-resolving-lunar-client-not-starting-errors/"><u>Techniques for Resolving Lunar Client Not Starting Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-woe-no-more-30-arrow-key-fixes/"><u>Windows Woe No More: 30 Arrow Key Fixes</u></a></li>
</ul></div>

