---
title: "Streamlining Shortcut Functionality: Integrating Wordpad Keys with Windows 11 Menu"
date: 2025-03-03T01:22:19.249Z
updated: 2025-03-04T23:54:37.454Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Shortcut Functionality: Integrating Wordpad Keys with Windows 11 Menu"
excerpt: "This Article Describes Streamlining Shortcut Functionality: Integrating Wordpad Keys with Windows 11 Menu"
keywords: Wpd Keyboard Shortcuts,Windows 11 Enhanced Shell,Streamlined User Interface,Integrated Command Accessibility,Navigation Efficiency Boost,Operational Functionality Upgrade,Keys to Menu Correlation
thumbnail: https://thmb.techidaily.com/eb6701eb360daf00501aea3027f5f407ca588034548873224d944d5de49dcde3.jpg
---

## Streamlining Shortcut Functionality: Integrating Wordpad Keys with Windows 11 Menu

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

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-crown-jewels-of-online-watching-youtubes-treasures/"><u>[Updated] 2024 Approved Crown Jewels of Online Watching YouTube's Treasures</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-uncovering-the-secrets-of-effortless-iphone-podcast-downloads/"><u>2024 Approved Uncovering the Secrets of Effortless iPhone Podcast Downloads</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/can-adobe-premiere-pro-handle-av1-video-formats-for-import-and-export-tasks/"><u>Can Adobe Premiere Pro Handle AV1 Video Formats for Import and Export Tasks?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-address-server-stumbled-issues-on-windows-store/"><u>Essential Tips to Address Server Stumbled Issues on Windows Store</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-infinix-hot-40-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Infinix Hot 40 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overriding-no-notify-settings-on-windows-11-cameras/"><u>Overriding No-Notify Settings on Windows 11 Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-process-for-adding-msibundle-files-to-devices-via-store/"><u>Simplified Process for Adding MsiBundle Files to Devices via Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-images-on-pcs-with-these-seven-steps-win11/"><u>Streamline Your Images on PCs with These Seven Steps (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-and-configure-with-ease-control-panel-steps/"><u>Unlock & Configure with Ease: Control Panel Steps</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-the-door-to-tech-careers-with-essential-knowledge-of-these-3-key-programming-languages/"><u>Unlock the Door to Tech Careers with Essential Knowledge of These 3 Key Programming Languages</u></a></li>
</ul></div>

