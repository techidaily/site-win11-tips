---
title: "Streamlining Shortcut Functionality: Integrating Wordpad Keys with Windows 11 Menu"
date: 2025-01-30T22:56:59.169Z
updated: 2025-02-01T00:52:04.522Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-the-pinnacle-of-picture-quality-best-players-24/"><u>[New] 2024 Approved The Pinnacle of Picture Quality Best Players '24</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-income-streams-from-google-adsense-to-money-matters/"><u>[Updated] Unlocking Income Streams From Google AdSense to Money Matters</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtube-mastery-starts-here-building-and-monetizing-your-channel/"><u>[Updated] YouTube Mastery Starts Here Building and Monetizing Your Channel</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-discover-top-tier-church-broadcasting-options/"><u>2024 Approved Discover Top-Tier Church Broadcasting Options</u></a></li>
<li><a href="https://ai-voice.techidaily.com/2024-approved-the-best-text-voice-generators-for-all-platforms/"><u>2024 Approved The Best Text Voice Generators for All Platforms</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/battle-for-supremacy-in-a-new-star-wars-game-a-deep-dive-into-squadrons-features-and-gameplay/"><u>Battle for Supremacy in a New Star Wars Game – A Deep Dive Into Squadrons' Features & Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-win11-dns-server-settings-quick-guide/"><u>Configuring Win11 DNS Server Settings Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-method-to-rectify-error-0x800700c6-in-apps/"><u>Detailed Method to Rectify 'Error 0X800700C6' In Apps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/discovering-your-own-original-tagline-in-the-realm-of-tiktok/"><u>Discovering Your Own Original Tagline in the Realm of TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-windows-arp-cache-mechanism-and-deletion/"><u>Dissecting Windows ARP Cache Mechanism and Deletion</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-realme-gt-neo-5-by-fonelab-android-recover-photos/"><u>How To Restore Missing Photos Files from Realme GT Neo 5.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-gpo-searches-in-modern-windows-os/"><u>Mastering GPO Searches in Modern Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-windows-1011s-0x80246007-problem/"><u>Overcoming the Windows 10/11'S 0X80246007 Problem</u></a></li>
<li><a href="https://screen-capture.techidaily.com/pro-moviemakers-manual-for-pc-mac-and-mobile-systems/"><u>Pro Moviemaker's Manual for PC, Mac & Mobile Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-signature-problem-for-windows-updates/"><u>Resolving Signature Problem for Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-7-efficient-study-strategies-on-a-windows-pc/"><u>Unleash Potential: 7 Efficient Study Strategies on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-guide-to-opening-system32-directory/"><u>Win11's Guide to Opening System32 Directory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-a-christmas-makeover-guide/"><u>Windows 11: A Christmas Makeover Guide</u></a></li>
</ul></div>

