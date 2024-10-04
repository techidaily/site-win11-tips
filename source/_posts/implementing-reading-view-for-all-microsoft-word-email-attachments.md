---
title: Implementing Reading View for All Microsoft Word Email Attachments
date: 2024-09-27T18:54:55.151Z
updated: 2024-10-03T22:41:42.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Implementing Reading View for All Microsoft Word Email Attachments
excerpt: This Article Describes Implementing Reading View for All Microsoft Word Email Attachments
keywords: Word Read Mode,Email Doc View,MS Word Attachment,Doc Accessibility,Open Word Mail,Reading Schema,Email Text Rendering
thumbnail: https://thmb.techidaily.com/a4dc30780e032f6d710992cf5481b7eec2d5a638075023e09360ad01372b41d6.jpg
---

## Implementing Reading View for All Microsoft Word Email Attachments

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
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-can-televising-streaming-services-include-facebook-content/"><u>[New] Can Televising Streaming Services Include Facebook Content?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/mpower-your-video-creation-blending-youtube-and-imovie-for-impressive-results-for-2024/"><u>[New] Empower Your Video Creation Blending YouTube and iMovie for Impressive Results for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-2-methods-to-transform-zoom-sound-ensuring-clarity/"><u>[Updated] Top 2 Methods to Transform Zoom Sound, Ensuring Clarity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-full-features-sony-fdr-x1000-model/"><u>2024 Approved Exploring the Full Features Sony FDR-X1000 Model</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-the-ultimate-list-of-coolest-mc-homes-designed/"><u>2024 Approved The Ultimate List of Coolest MC Homes Designed</u></a></li>
<li><a href="https://tools.techidaily.com/epubor/chirp-converter/"><u>Epubor Chirp Converter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exposing-the-latest-file-usage-on-windows-systems/"><u>Exposing the Latest File Usage on Windows Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/high-res-360-views-gear-vs-lgcam-showdown/"><u>High-Res 360 Views Gear vs LGCam Showdown</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-voice-over-advantage-elevating-video-quality/"><u>In 2024, The Voice-Over Advantage Elevating Video Quality</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-vivo-y55s-5g-2023-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Vivo Y55s 5G (2023) Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lightest-load-web-browsers-for-windows-macos-chromeos-users/"><u>Lightest-Load Web Browsers for Windows, macOS, ChromeOS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-legacy-tech-more-elder-safe-for-families/"><u>Making Legacy Tech More Elder-Safe for Families</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-tool-selection-top-6-windows-usage-measurers/"><u>Masterful Tool Selection: Top 6 Windows Usage Measurers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-world-of-affordable-windows-10-licensing/"><u>Navigating the World of Affordable Windows 10 Licensing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-the-autoplay-in-file-explorer/"><u>Silencing the Autoplay in File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zeroing-out-windows-11-for-a-fresh-start/"><u>Zeroing Out Windows 11 for a Fresh Start</u></a></li>
</ul></div>

