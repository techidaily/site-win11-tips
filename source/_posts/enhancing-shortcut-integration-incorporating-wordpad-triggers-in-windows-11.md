---
title: "Enhancing Shortcut Integration: Incorporating WordPad Triggers in Windows 11"
date: 2024-10-16T02:38:31.549Z
updated: 2024-10-20T19:29:21.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Shortcut Integration: Incorporating WordPad Triggers in Windows 11"
excerpt: "This Article Describes Enhancing Shortcut Integration: Incorporating WordPad Triggers in Windows 11"
keywords: Shortcut Enhancement,Wordpad Triggering,Windows 11 Integration,Quick Access in W11,Efficient File Management,Task Automation via Keyboard,Advanced WordPad Functions
thumbnail: https://thmb.techidaily.com/ffa6265ad1a6a848473605e7aedcfa3ec46ffbe39326ff49e8d4fafd11fa0e00.jpg
---

## Enhancing Shortcut Integration: Incorporating WordPad Triggers in Windows 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/asic-to-breakthrough-content-crafting-the-top-10-simplest-youtube-projects/"><u>[New] Basic to Breakthrough Content Crafting the Top 10 Simplest YouTube Projects</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-crafting-compelling-compositions-with-magix-fruity-loops/"><u>[New] Crafting Compelling Compositions with Magix Fruity Loops</u></a></li>
<li><a href="https://vp-tips.techidaily.com/1-detaillierte-tech-specs-von-winxvideo-ai-offizielles-handbuch/"><u>1. Detaillierte Tech-Specs Von WinXVideo AI - Offizielles Handbuch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/obs-studio-windowsmac/"><u>如何使用OBS Studio Windows/Mac版本：深入學習最新評論及教程，以便即時下載</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-poco-f5-5g-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Poco F5 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/come-riprodurre-file-avi-su-windows-11-una-guida-completa/"><u>Come Riprodurre File AVI Su Windows 11: Una Guida Completa</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/dissecting-status-bts-features-pricey-but-worth-it/"><u>Dissecting Status BT's Features: Pricey but Worth It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/facile-et-gratuit-convertissez-vos-fichiers-gif-en-mp4-a-laide-de-movavi-online/"><u>Facile Et Gratuit : Convertissez Vos Fichiers GIF en MP4 À L'aide De Movavi Online</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-motorola-razr-40-ultra-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Motorola Razr 40 Ultra</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723007433973-how-to-repair-a-malfunctioning-logitech-c920-webcam-solutions-inside/"><u>How to Repair a Malfunctioning Logitech C920 Webcam - Solutions Inside</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-nubia-red-magic-8s-pro-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Nubia Red Magic 8S Pro? Look No Further | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-software-influencer-review-and-recommendations-top-picks/"><u>Movavi Software: Influencer Review & Recommendations - Top Picks!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/os-melhores-12-aplicativos-gratis-para-desenho-fotografico-em-mosaico-para-pc-movavi/"><u>Os Melhores 12 Aplicativos Grátis Para Desenho Fotográfico Em Mosaico Para PC - Movavi</u></a></li>
</ul></div>

