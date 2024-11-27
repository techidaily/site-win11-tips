---
title: Guide to Programming Microsoft Office Apps For Exclusive Read-Only Display Mode
date: 2024-11-21T17:21:06.730Z
updated: 2024-11-27T16:59:18.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Programming Microsoft Office Apps For Exclusive Read-Only Display Mode
excerpt: This Article Describes Guide to Programming Microsoft Office Apps For Exclusive Read-Only Display Mode
keywords: MS Office Dev Tools,Excel ROD Mode,Word POW Mode,Outlook EXCELORN,Access PLUS Mode,VBA for Read-Only,Programmable READONLY
thumbnail: https://thmb.techidaily.com/279c7ee1ef176fcfbe647ba1dd5b67d647bd153ee16f2665898b8839f297231a.jpg
---

## Guide to Programming Microsoft Office Apps For Exclusive Read-Only Display Mode

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-approaches.techidaily.com/new-unlocking-apples-audio-world-a-download-guide-for-ios-users/"><u>[New] Unlocking Apple's Audio World A Download Guide for iOS Users</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-cheapest-way-designing-successful-youtube-ad-campaigns-for-2024/"><u>[Updated] The Cheapest Way Designing Successful YouTube Ad Campaigns for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-differences-a-comparative-look-at-local-and-microsoft-windows-logins/"><u>Delving Into Differences: A Comparative Look at Local & Microsoft Windows Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-your-way-past-windows-exe-opening-blocks/"><u>Ease Your Way Past Windows Exe Opening Blocks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ram-cache-management-on-windows-os/"><u>Efficient RAM Cache Management on Windows OS</u></a></li>
<li><a href="https://fox-sure.techidaily.com/guru-guru-pemulihan-hdd-cara-mudah-menyimpan-data-dari-harddrive-acer-aspire/"><u>Guru-Guru Pemulihan Hdd | Cara Mudah Menyimpan Data Dari Harddrive Acer Aspire</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Infinix Smart 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-saving-the-best-from-fb-in-high-definition/"><u>In 2024, Saving the Best From FB in High Definition</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-vivo-x-flip-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Vivo X Flip to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/know-your-ai-acronyms-the-must-know-list/"><u>Know Your AI Acronyms: The Must-Know List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-and-rectify-hidden-storage-on-pc/"><u>Locate and Rectify Hidden Storage on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-cure-for-onedrives-0x8004dec5-sign-in-crisis-in-windows/"><u>Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-a-healthy-net-framework-post-fixes-max-156/"><u>Securing a Healthy .NET Framework Post-Fixes (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-optimal-clocktime-saver-software-for-windows/"><u>Unleash Potential - Optimal Clock/Time Saver Software for Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-users-guide-sending-and-receiving-imessages-with-ease/"><u>Windows Users Guide: Sending & Receiving iMessages with Ease</u></a></li>
</ul></div>

