---
title: How to Configure Word to Open Email Attachments Exclusively in Read View
date: 2024-12-09T21:27:50.383Z
updated: 2024-12-12T22:41:19.454Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Configure Word to Open Email Attachments Exclusively in Read View
excerpt: This Article Describes How to Configure Word to Open Email Attachments Exclusively in Read View
keywords: Open Email Read-Only,Manage Word Attachments,Exclusive Read Mode Word,Filtering Emails Words,Word Attachment Settings,Restrict View Attachments,Configure Word Attach View
thumbnail: https://thmb.techidaily.com/0e3820d1cc459c1675907e5894236de62a82183359872714a0c5168c962bf67b.jpg
---

## How to Configure Word to Open Email Attachments Exclusively in Read View

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/updated-decoding-how-to-effectively-swap-photo-genders-online-a-comprehensive-approach/"><u>[Updated] Decoding How to Effectively Swap Photo Genders Online A Comprehensive Approach</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-mastery-in-simulating-chrono-displacement/"><u>[Updated] In 2024, Mastery in Simulating Chrono-Displacement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-ts-movavi/"><u>網路上自由下載 MKV 版的 TS文件 - 使用 Movavi 解析器</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wavwma-wavwma/"><u>無限免費移動WAV到WMA: 維威麥 Wav轉成Wma格式</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conversione-libera-tra-bmp-e-gif-il-perfetto-solutore-on-line-di-movavi/"><u>Conversione Libera Tra BMP E GIF: Il Perfetto Solutore On-Line Di Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-your-wav-files-without-cost-seamless-audio-editing-by-movavi/"><u>Convert Your WAV Files Without Cost: Seamless Audio Editing by Movavi</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-photos-from-meizu-21-by-fonelab-android-recover-photos/"><u>Easy steps to recover deleted photos from Meizu 21.</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/enjoy-three-months-free-on-tidal-after-your-next-djeqsean-dex-3-order/"><u>Enjoy Three Months Free on Tidal After Your Next DJeqsean DEX 3 Order!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722988539536-fortnite-sign-in-issues-resolved-fast-and-simple-fixes/"><u>Fortnite Sign-In Issues Resolved: Fast & Simple Fixes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/free-online-converter-transform-webp-images-into-jpeg-format-with-ease/"><u>Free Online Converter: Transform WebP Images Into JPEG Format with Ease</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y100-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/latest-fixes-for-phasmophobia-technical-problems-stay-updated-gaming-success/"><u>Latest Fixes for Phasmophobia Technical Problems - Stay Updated Gaming Success</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-create-unforgettable-lip-sync-videos-with-these-5-top-rated-apps/"><u>New Create Unforgettable Lip Sync Videos with These 5 Top-Rated Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-cost-web-tool-for-mp3-format-switching-by-movavis-easy-snd-to-mp3-solution/"><u>No-Cost Web Tool for MP3 Format Switching by Movavi's Easy SND to MP3 Solution</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-ultimate-guide-to-converting-youtubes-into-vivid-gifs-no-save/"><u>The Ultimate Guide to Converting YouTubes Into Vivid GIFs (No Save)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trasforma-video-aac-a-mp4-senza-costi-usando-il-servizio-di-conversione-online-movavi/"><u>Trasforma Video AAC a MP4 Senza Costi Usando Il Servizio Di Conversione Online Movavi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mod-avi-movavi/"><u>무료 MOD AVI 펑션을 쉽고 사용하기위한 웹 공간 내 스타일리시 도구 - Movavi</u></a></li>
</ul></div>

