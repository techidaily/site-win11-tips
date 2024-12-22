---
title: How to Configure Word to Open Email Attachments Exclusively in Read View
date: 2024-12-18T00:11:38.291Z
updated: 2024-12-22T01:29:10.447Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-key-techniques-for-capturing-youtube-streaming-content-for-2024/"><u>[New] Key Techniques for Capturing YouTube Streaming Content for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-step-by-step-tech-livestream-setup-pcmaclaptop-for-fb-for-2024/"><u>[New] Step-by-Step Tech Livestream Setup (PC/Mac/Laptop) for FB for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-iphone-tips-achieving-extended-exposure-images/"><u>[Updated] In 2024, IPhone Tips Achieving Extended Exposure Images</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-vivacious-talker-examined-revision-no-8/"><u>[Updated] Vivacious Talker Examined Revision No. 8</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amazon-primes-trending-series-twitters-choice-2023/"><u>Amazon Prime's Trending Series - Twitter's Choice, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-precautionary-measures-on-windows-11-upgrade/"><u>Essential Precautionary Measures on Windows 11 Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exit-the-sharpness-of-windows-high-contrast-mode/"><u>Exit the Sharpness of Windows' High Contrast Mode</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oppo-k11x-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Oppo K11x to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maintaining-calc-spotlight-within-windows/"><u>Maintaining Calc Spotlight Within Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/modifying-internet-preferences-on-win11/"><u>Modifying Internet Preferences on Win11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/by-step-guide-to-integrate-youtube-media-into-gslides/"><u>Step-by-Step Guide to Integrate YouTube Media Into GSlides</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-ultimate-guide-to-creating-free-youtube-outros-1-6-for-2024/"><u>The Ultimate Guide to Creating FREE YouTube Outros #1-6 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transcending-ordinary-how-to-access-divine-settings-on-windows-11/"><u>Transcending Ordinary: How To Access Divine Settings on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-windows-tech-through-artificial-intelligence/"><u>Transforming Windows Tech Through Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-unexpected-wins-alerts/"><u>Understanding and Tackling Unexpected WINS Alerts</u></a></li>
</ul></div>

