---
title: Adjust Word's Settings for Consistent Openness of Email Attachments as Text
date: 2025-01-29T07:15:57.866Z
updated: 2025-02-01T11:09:30.951Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjust Word's Settings for Consistent Openness of Email Attachments as Text
excerpt: This Article Describes Adjust Word's Settings for Consistent Openness of Email Attachments as Text
keywords: Email Open Text Format,Attachment Accessibility,Inline Email Content,Text-Based Email Files,Consistent Email Views,Openness in Emails,Word Attachment Settings
thumbnail: https://thmb.techidaily.com/1f343cc2ca566c6b496acac107d8a3cfc474691f655f34c60ef016476e0a8a74.jpg
---

## Adjust Word's Settings for Consistent Openness of Email Attachments as Text

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-lessons.techidaily.com/new-accelerating-attention-how-to-alter-video-speed-on-stories/"><u>[New] Accelerating Attention How to Alter Video Speed on Stories</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-the-art-of-color-grading-utilizing-luts-in-ae/"><u>[New] The Art of Color Grading Utilizing LUTs in AE</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-apple-excellence-iphones-best-no-cost-image-assemblers-and-layouts/"><u>[Updated] Apple Excellence – iPhone's Best No-Cost Image Assemblers & Layouts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-bitrecorder-analysis-with-other-solutions/"><u>[Updated] In 2024, BitRecorder Analysis with Other Solutions</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-elevate-your-drawings-top-artistic-tools-on-chrome-os/"><u>2024 Approved Elevate Your Drawings Top Artistic Tools on Chrome OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-app-management-through-wingetui-on-windows/"><u>Efficient App Management Through WingetUI on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-win11-editions-home-vs-professional-perks/"><u>Essential Guide to Win11 Editions: Home Vs. Professional Perks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-disk-organizer-not-starting-errors/"><u>Fixing Windows Disk Organizer Not Starting Errors</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-asus-rog-phone-7-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Asus ROG Phone 7 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-rescue-a-stuck-macbook-air-from-its-frozen-state-a-step-by-step-guide/"><u>How to Rescue a Stuck MacBook Air From Its Frozen State: A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-affordable-lg-um7n-49-4k-screen-your-go-to-guide-to-basic-home-entertainment/"><u>In-Depth Analysis of the Affordable LG UM7n 49 4K Screen: Your Go-To Guide to Basic Home Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-secure-boot-the-top-5-fixes-at-your-fingertips/"><u>Mastering Secure Boot: The Top 5 Fixes at Your Fingertips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/mastery-guide-securely-archiving-snapchat-media-on-devices/"><u>Mastery Guide Securely Archiving Snapchat Media on Devices</u></a></li>
</ul></div>

