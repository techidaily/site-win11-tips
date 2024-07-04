---
title: "Mastering Windows 11: Adding WordPad Shortcut Accessibility"
date: 2024-06-25T17:04:36.834Z
updated: 2024-06-26T17:04:36.834Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows 11: Adding WordPad Shortcut Accessibility"
excerpt: "This Article Describes Mastering Windows 11: Adding WordPad Shortcut Accessibility"
keywords: Win11WordpadShortcut,WordPadWinAccess,Win11AddWordpad,WordPadWindows11,Win11TextEditing,AccessibilityWordPad,ShortcutsWin11
thumbnail: https://thmb.techidaily.com/2fabafc66fe8d6c738eceaf2d94bef9969abb79ce6dfc7f79cdd9561a56a5238.jpg
---

## Mastering Windows 11: Adding WordPad Shortcut Accessibility

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
<li><a href="https://win11-tips.techidaily.com/bypassing-the-couldnt-be-written-windows-error/"><u>Bypassing the Couldn’t Be Written Windows Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-chatting-experience-with-10-fixes/"><u>Revitalize Your Chatting Experience with 10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-task-managers-dynamic-speed-in-windows-11/"><u>Boost Task Manager's Dynamic Speed in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-crafting-windows-11-extractable-files/"><u>A Step-by-Step Guide to Crafting Windows 11 Extractable Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-how-you-use-the-mouse-cross-border-efficiency-via-powertoys/"><u>Transforming How You Use the Mouse: Cross-Border Efficiency via PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-windows-11-taskbar-for-optimal-datetime-view/"><u>Tailoring Windows 11 Taskbar for Optimal Date/Time View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-update-processes-context-menu-update-option-for-win11-users/"><u>Streamlining Update Processes: Context Menu Update Option for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-to-your-pcs-health-report-efficiently/"><u>Navigate to Your PC’s Health Report Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-seamless-multilingual-input-adjusting-keyboard-layout-in-windows-11/"><u>Achieve Seamless Multilingual Input: Adjusting Keyboard Layout in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/embracing-the-world-one-post-at-a-time-with-insta-captions-for-2024/"><u>Embracing the World, One Post at a Time with Insta Captions for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-fcpx-title-effects-take-your-videos-to-the-next-level/"><u>In 2024, FCPX Title Effects Take Your Videos to the Next Level</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-poco-f5-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-ultimate-guide-convert-and-save-4k-videos-as-mp4-files-for-2024/"><u>New Ultimate Guide Convert and Save 4K Videos as MP4 Files for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-quickcapture-lite-basic-chromecasting-tool-for-2024/"><u>[Updated] QuickCapture Lite  Basic Chromecasting Tool for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On OnePlus 11R? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/high-definition-adventures-top-7-camcorders-unveiled/"><u>High-Definition Adventures  Top 7 Camcorders Unveiled</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-unveiling-the-magic-of-seamless-sound-integration-in-videos/"><u>[New] 2024 Approved  Unveiling the Magic of Seamless Sound Integration in Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-samsung-galaxy-a54-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Samsung Galaxy A54 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-nubia-red-magic-9-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Nubia Red Magic 9 Pro | Dr.fone</u></a></li>
</ul></div>
