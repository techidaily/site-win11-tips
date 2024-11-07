---
title: "Customizing Word's Behavior: Opens Email Attachments as Text Only"
date: 2024-11-05T22:16:00.737Z
updated: 2024-11-07T12:33:17.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customizing Word's Behavior: Opens Email Attachments as Text Only"
excerpt: "This Article Describes Customizing Word's Behavior: Opens Email Attachments as Text Only"
keywords: Word Email Filtering,Custom Word Options,Email Attachment View,Open As Text Feature,Attachment Format Change,No Content Display,Word Text-Only Mode
thumbnail: https://thmb.techidaily.com/0444eec17d8a448239a97f10d9e4452f293a188f566a19e1bcefd1ff9d258319.jpg
---

## Customizing Word's Behavior: Opens Email Attachments as Text Only

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

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
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-brilliant-visuals-uncover-the-magic-in-these-7-grades/"><u>[New] In 2024, Brilliant Visuals Uncover the Magic in These 7 Grades</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-master-mac-streaming-with-our-top-5-software-picks/"><u>[Updated] 2024 Approved Master Mac Streaming with Our Top 5 Software Picks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-engaging-audiences-writing-compelling-titles-and-descriptions-for-youtube/"><u>[Updated] In 2024, Engaging Audiences Writing Compelling Titles and Descriptions for YouTube</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unlocking-creative-expression-tips-for-sharing-gifs-on-snapchat-for-2024/"><u>[Updated] Unlocking Creative Expression Tips for Sharing GIFs on Snapchat for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/artistic-anomaly-top-10-unique-affordable-mac-drawers-free/"><u>Artistic Anomaly Top 10 Unique, Affordable Mac Drawers (Free)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-purpose-of-twitter-axes-checkmarks-linus-tech-tips-cyber-attack-expose-and-the-dangers-of-trojan-threats-online/"><u>Decoding the Purpose of Twitter Axes Checkmarks | Linus Tech Tips' Cyber Attack Exposé & The Dangers of Trojan Threats Online</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-y100i-power-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo Y100i Power 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-winstall-for-swift-grouped-app-deployments-on-windows-11/"><u>Harnessing the Power of Winstall for Swift Grouped App Deployments on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-restore-functionality-of-cortana-on-latest-version-windows-11/"><u>How to Restore Functionality of Cortana on Latest Version Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-white-screen-on-microsoft-appstore/"><u>Overcoming White Screen on Microsoft Appstore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-silent-systems-voice-finding-sound-solutions/"><u>Restore Silent System's Voice: Finding Sound Solutions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/save-big-on-apple-airpods-exclusive-40-discount-just-in-time-for-independence-day-shopping-tips-from-zdnet/"><u>Save Big on Apple AirPods: Exclusive $40 Discount Just in Time for Independence Day - Shopping Tips From ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-joy-with-these-best-free-players-win/"><u>Streamline Joy with These Best FREE Players (Win)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-wacatacbmls-deception-in-your-windows-ecosystem/"><u>Unmasking Wacatac.B!ml's Deception in Your Windows Ecosystem</u></a></li>
</ul></div>

