---
title: "Mastering Windows 11: Adding WordPad Shortcut Accessibility"
date: 2024-08-16T01:30:35.643Z
updated: 2024-08-17T01:30:35.643Z
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see [how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-step-by-step-craft-your-viral-story-in-online-videos/"><u>[New] Step by Step, Craft Your Viral Story in Online Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-from-twitter-to-snaps-a-guide-to-cross-platform-posting/"><u>[Updated] 2024 Approved  From Twitter to Snaps  A Guide to Cross-Platform Posting</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-mastering-the-art-of-instantaneous-deletion-of-youtube-discussions/"><u>[Updated] 2024 Approved  Mastering the Art of Instantaneous Deletion of YouTube Discussions</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-conversational-courtesies-react-and-engage-on-discord-platforms/"><u>[Updated] Conversational Courtesies  React and Engage on Discord Platforms</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-complete-process-recording-youtube-livestream-on-multiple-platforms-for-2024/"><u>[Updated] The Complete Process  Recording YouTube Livestream on Multiple Platforms for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-uniting-melodies-and-images-with-youtube-music-for-video-projects/"><u>2024 Approved  Uniting Melodies & Images with YouTube Music for Video Projects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-audacity-audio-inconsistency-in-windows-1111/"><u>Correcting Audacity Audio Inconsistency in Windows 11/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-process-of-eliminating-security-record-in-windows/"><u>Decoding the Process of Eliminating Security Record in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-peasy-double-click-android-files-in-win-11/"><u>Easy-Peasy: Double-Click Android Files in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/echoes-of-the-past-utilizing-windows-7-product-key-for-windows-11/"><u>Echoes of the Past: Utilizing Windows 7 Product Key for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-these-2023-microsoft-store-community-choice-winning-apps/"><u>Elevate Your Windows Experience With These 2023 Microsoft Store Community Choice Winning Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-intrusive-credential-prompts-on-windows-11-local-account/"><u>Eliminating Intrusive Credential Prompts on Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-windows-security-bypassing-faulty-pins-easily/"><u>Enhance Windows Security: Bypassing Faulty PINs Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-sticky-notes-dont-get-lost/"><u>Ensuring Sticky Notes Don't Get Lost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-virtualbox-v70-installation-for-windows-11-users/"><u>Essential Guide: VirtualBox v7.0 Installation for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-routes-to-windows-recovery-toolkit/"><u>Essential Routes to Windows Recovery Toolkit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-to-overcome-remote-connection-errors-on-windows/"><u>Fixes to Overcome Remote Connection Errors on Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-detailed-can-chatgpt-answers-be-uncovering-its-length-capacity/"><u>How Detailed Can ChatGPT Answers Be? Uncovering Its Length Capacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-dodge-repeated-network-logon-error-messages-on-windows/"><u>How to Dodge Repeated Network Logon Error Messages on Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-graphicgenius-create-funny-memes/"><u>In 2024, GraphicGenius  Create Funny Memes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-verizon-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How to Unlock Verizon Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-iphone-photography-boosted-by-ios-11-features/"><u>In 2024, IPhone Photography Boosted by iOS 11 Features</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-mastering-the-art-of-digital-recording-for-gotomeet-sessions/"><u>In 2024, Mastering the Art of Digital Recording for GoToMeet Sessions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-composers-handbook-to-instagram-and-music-rights/"><u>In 2024, The Composer's Handbook to Instagram and Music Rights</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-infinix-zero-30-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Infinix Zero 30 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-analysis-of-the-asus-ac68u-fast-safe-and-superior-5g-networking-experience/"><u>In-Depth Analysis of the Asus AC68U - Fast, Safe, and Superior 5G Networking Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-start-your-android-devices-double-clicking-apks-on-win-11/"><u>Jump-Start Your Android Devices: Double-Clicking APKs on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-stalled-excel-workflow-on-windows-devices/"><u>Jumpstart Stalled Excel Workflow on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-saved-gamer-tactics-with-launcher-backups/"><u>Mastering Saved Gamer Tactics with Launcher Backups</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mastering-the-art-of-design-selecting-ideal-dimensions-for-yt-branding/"><u>Mastering the Art of Design  Selecting Ideal Dimensions for YT Branding</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-rebooting-indexed-databases/"><u>Mastering the Art of Rebooting Indexed Databases</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-excessive-load-by-dropbox-app-on-windows-computers/"><u>Mitigating Excessive Load by Dropbox App on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shadows-add-stealthy-menu-in-win11/"><u>Navigating the Shadows: Add Stealthy Menu in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-freeze-crash-and-blackout/"><u>Overcoming Chrome Freeze, Crash, and Blackout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-package-access-issues-on-windows-1110-systems/"><u>Overcoming Package Access Issues on Windows 11/10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-hurdles-of-windows-11s-search-functionality/"><u>Overcoming the Hurdles of Windows 11'S Search Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-overloaded-system-by-controlling-processes/"><u>Resolving Overloaded System by Controlling Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sharpen-performance-the-most-unnecessary-windows-applications/"><u>Sharpen Performance: The Most Unnecessary Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-chrome-blackout-on-a-pc/"><u>Solving Chrome Blackout on a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-enhance-visibility-of-webcam-usage-on-win11/"><u>Steps to Enhance Visibility of Webcam Usage on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-token-misrepresentation-issues/"><u>Strategies for Fixing “Token Misrepresentation” Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-future-of-flirting-improving-dating-strategies-using-chatgpt-technology/"><u>The Future of Flirting: Improving Dating Strategies Using ChatGPT Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-benefits-in-maintaining-your-win-11-notification-signals/"><u>The Hidden Benefits in Maintaining Your Win 11 Notification Signals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-retro-arc-of-gaming-shading-techniques-for-ancient-artifacts/"><u>The Retro Arc of Gaming: Shading Techniques for Ancient Artifacts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-guide-to-fast-clickers/"><u>The Ultimate Windows Guide to Fast Clickers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-imminent-windows-licensing-warning/"><u>Troubleshooting Imminent Windows Licensing Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-exe-files-on-your-pc-no-more-issues/"><u>Unlock EXE Files on Your PC, No More Issues!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-key-beware-the-subtle-dangers-of-discounts/"><u>Windows Key Beware: The Subtle Dangers of Discounts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-renewal-methods-for-driver-replacement-and-update/"><u>Windows Renewal: Methods for Driver Replacement and Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-pairings-4-innovative-windows-webp-viewer-apps/"><u>Winning Pairings: 4 Innovative Windows WebP Viewer Apps</u></a></li>
</ul></div>
