---
title: Guidelines to Make Word Open Email Attachments in Read-Only by Default
date: 2024-09-15T05:53:25.061Z
updated: 2024-09-21T20:56:10.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines to Make Word Open Email Attachments in Read-Only by Default
excerpt: This Article Describes Guidelines to Make Word Open Email Attachments in Read-Only by Default
keywords: Enable Default Read-Only for Emails,Set Attachments Readonly,Prevent Edit Email Content,Secure Email Attachments,Word Open Settings Save as Readonly,Read-Only by Attachment Rule,Default Email Protection Mode
thumbnail: https://thmb.techidaily.com/ab712e6369c11731fb797565c1d31f34a50ed98f4e3e4e20f2e0bcfb8f432b00.jpg
---

## Guidelines to Make Word Open Email Attachments in Read-Only by Default

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.

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
<li><a href="https://discord-videos.techidaily.com/new-quick-win-strategies-for-replying-on-discord-platforms-for-2024/"><u>[New] Quick-Win Strategies for Replying on Discord Platforms for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-top-bargain-video-snippets-grab-youtube-images-without-cost/"><u>[Updated] Top Bargain Video Snippets - Grab YouTube Images Without Cost</u></a></li>
<li><a href="https://os-tips.techidaily.com/apple-maps-failure-guide-understanding-and-solving-downtime-problems/"><u>Apple Maps Failure Guide: Understanding and Solving Downtime Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/descargue-y-convierte-archivos-ogv-a-formatos-wmv-sin-coste-alguno-con-movavi/"><u>Descargue Y Convierte Archivos OGV a Formatos WMV Sin Coste Alguno Con Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/el-mejor-administrador-de-imagenes-para-windows-10-opciones-top-rated/"><u>El Mejor Administrador De Imágenes Para Windows 10: Opciones Top Rated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-essentials-of-mov-and-mp4-video-types-what-sets-them-apart/"><u>Exploring the Essentials of MOV and MP4 Video Types - What Sets Them Apart?</u></a></li>
<li><a href="https://blog-min.techidaily.com/free-converter-change-mov-file-into-flv-format-online-tool-by-movavi/"><u>Free Converter: Change MOV File Into FLV Format - Online Tool by Movavi</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamline-your-soundtrack-exchanging-playlists-seamlessly/"><u>In 2024, Streamline Your Soundtrack Exchanging Playlists Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/kostenloses-online-umwandeln-von-ogg-in-ogv-mit-movavi-media-converter/"><u>Kostenloses Online-Umwandeln Von OGG in OGV Mit Movavi Media Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavis-guide-to-no-cost-wma-to-aiff-file-conversions-on-the-web/"><u>Movavi's Guide to No-Cost WMA to AIFF File Conversions on the Web</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nsvmp3-movavi/"><u>NSV到MP3無成本上線即可 - 以Movavi進行轉換方便多了</u></a></li>
<li><a href="https://win11-tips.techidaily.com/omzetten-van-flv-videofilen-tot-mp4mov-veilige-gratis-online-instellingen/"><u>Omzetten Van FLV Videofilen Tot MP4/MOV: Veilige, Gratis Online Instellingen</u></a></li>
<li><a href="https://article-posts.techidaily.com/platform-dominance-a-comprehensive-twitch-vs-youtube-review/"><u>Platform Dominance A Comprehensive Twitch Vs. YouTube Review</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-console-experience-with-code-magic/"><u>Transform Your Console Experience with Code Magic</u></a></li>
<li><a href="https://driver-download.techidaily.com/try-different-usb-ports-on-your-computer-including-usb-30-and-usb-c-ports-if-available/"><u>Try Different USB Ports on Your Computer, Including USB 3.0 and USB-C Ports if Available</u></a></li>
</ul></div>

