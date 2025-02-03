---
title: "Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
date: 2025-01-28T18:01:54.709Z
updated: 2025-02-01T03:11:48.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
excerpt: "This Article Describes Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments"
keywords: Word Text Attachment Guide,Avoid Editing Attachments,Text-Only Doc Settings,Word No Edit Attachments,Office Products Preview,Save Original Opened Files,Word Setup for Copy Paste
thumbnail: https://thmb.techidaily.com/07fa8cadb13240ad4114bdffce36c4f17cee86cd9ffa9ec58a8ecda669ea9207.jpg
---

## Avoid Editing: Setup Office Products (Word) for Text Only Opened Attachments

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-techniques-for-capturing-high-quality-movies-on-all-os/"><u>[New] Techniques for Capturing High-Quality Movies on All OS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-expanding-textual-arsenal-in-after-effects/"><u>[Updated] 2024 Approved Expanding Textual Arsenal in After Effects</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-connectivity-aid-fb-stories-saver-pro/"><u>[Updated] In 2024, Connectivity Aid FB Stories Saver Pro</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/55kw5akd44oo44kk44k644gm55s76z2i6yyy55s744gn5re35ywl44gx44gq44ge44gf44kb44gu5luv6i2j/"><u>環境ノイズが画面録画で混入しないための仕草</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>Best Pokemons for PVP Matches in Pokemon Go For Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-unsuccessful-install-of-microsofts-pc-manager/"><u>Fix Unsuccessful Install of Microsoft's PC Manager</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/humble-beginnings-to-sponsored-success-channels-blueprint/"><u>From Humble Beginnings to Sponsored Success Channels' Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-win11-networks-with-effective-dns-setup/"><u>Optimize Win11 Networks with Effective DNS Setup</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-lenovo-g580-driver-updates/"><u>Seamless Lenovo G580 Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-gpos-for-user-accounts-in-the-latest-windows-versions/"><u>Tailoring GPOs for User Accounts in the Latest Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-and-solving-non-sync-problems-in-to-do/"><u>Unraveling and Solving Non-Sync Problems in To Do</u></a></li>
</ul></div>

