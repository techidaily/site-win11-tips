---
title: "Script for Setting Up MS Word: Opening Email Attachments Without Edit Options"
date: 2025-01-16T16:45:22.910Z
updated: 2025-01-18T17:03:05.128Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Script for Setting Up MS Word: Opening Email Attachments Without Edit Options"
excerpt: "This Article Describes Script for Setting Up MS Word: Opening Email Attachments Without Edit Options"
keywords: Open Email Attachments,Word Attachment Setup,No Edit Option Word,Microsoft Word Guide,Word Email Functions,Word Attachment Process,Attaching Mail in Word
thumbnail: https://thmb.techidaily.com/e475d95ff83684e67af3ed3b0fb046f03e477b4f885c10acf9d70c8e5fd03d37.jpg
---

## Script for Setting Up MS Word: Opening Email Attachments Without Edit Options

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-exclusive-roundup-best-windows-11-video-recording-options-for-2024/"><u>[New] Exclusive Roundup Best Windows 11 Video Recording Options for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-open-world-wonders-beyond-gtas-empire/"><u>[New] In 2024, Open World Wonders Beyond GTA's Empire</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-ranked-costless-pixel-perfection-aid/"><u>[New] Top-Ranked Costless Pixel Perfection Aid</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ultimate-costless-live-camera-capturer-for-2024/"><u>[New] Ultimate Costless Live Camera Capturer for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fast-track-converting-your-srt-files-to-text-format-today/"><u>[Updated] Fast Track Converting Your SRT Files to Text Format Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-video-quality-chrome-and-youtube-optimization/"><u>Elevating Video Quality: Chrome and YouTube Optimization</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-opens-new-horizons-for-oculus-go-with-root-access-unveiled/"><u>Facebook Opens New Horizons for Oculus Go with Root Access Unveiled</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-exploring-free-screen-capture-software-bandicam-vs-camtasia/"><u>In 2024, Exploring Free Screen Capture Software Bandicam Vs. Camtasia</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-the-role-of-ai-in-microsofts-store/"><u>Inside: The Role of AI in Microsoft's Store</u></a></li>
<li><a href="https://extra-hints.techidaily.com/leading-solutions-transforming-photos-into-videos/"><u>Leading Solutions Transforming Photos Into Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-efficiency-with-concurrent-subfolder-creation-on-windows-pcs/"><u>Maximize Your Efficiency with Concurrent Subfolder Creation on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mkv-mp4-conversion-steps-for-windows-users/"><u>MKV-MP4 Conversion Steps for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-disconnecting-woes-essential-fixes-for-windows-usb-wifi/"><u>Overcome Disconnecting Woes – Essential Fixes for Windows USB Wifi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-share-denial-in-microsoft-os/"><u>Overcome Share Denial in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-for-windows-error-0x80071a90/"><u>Step-by-Step Fix for Windows Error 0X80071A90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-resource-already-in-use-on-windows-pcs-152-chars/"><u>Steps to Address Resource Already In Use on Windows PCs (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-fixing-drivers-that-wont-load-in-win11/"><u>Tips for Fixing Drivers that Won't Load in Win11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-ipad-pro-protectors-2024-comprehensive-reviews-and-ratings-insights-from-tech-gurus-zdnet/"><u>Top-Rated iPad Pro Protectors 2024: Comprehensive Reviews & Ratings - Insights From Tech Gurus | ZDNet</u></a></li>
<li><a href="https://fox-access.techidaily.com/why-does-imovie-enforce-dimensions-for-2024/"><u>Why Does iMovie Enforce Dimensions for 2024</u></a></li>
</ul></div>

