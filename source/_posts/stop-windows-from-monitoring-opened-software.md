---
title: Stop Windows From Monitoring Opened Software
date: 2024-10-27T19:32:41.155Z
updated: 2024-11-01T17:39:26.653Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Monitoring Opened Software
excerpt: This Article Describes Stop Windows From Monitoring Opened Software
keywords: Stop Software Tracking,Avoid Windows Surveillance,End PC Monitoring,Disable Software Watch,Block Window Tracker,Prevent OS Tracking,Eliminate Windows Spying
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
---

## Stop Windows From Monitoring Opened Software

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144275/7443" target="_top" id="2144275">
  <img src="//a.impactradius-go.com/display-ad/7443-2144275" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144275/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948932/19272" target="_top" id="1948932">
  <img src="//a.impactradius-go.com/display-ad/19272-1948932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/iscover-top-platforms-for-youtube-brand-partnerships-for-2024/"><u>[New] Discover Top Platforms for YouTube Brand Partnerships for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-recommended-sub-to-srt-tools-top-8-guide-reviewed/"><u>[New] Expert Recommended Sub to SRT Tools Top 8 Guide Reviewed</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-uncover-the-best-tablet-titans-for-photo-editing-aficionados-for-2024/"><u>[New] Uncover the Best Tablet Titans for Photo Editing Aficionados for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-the-best-alternatives-for-microsofts-core-apps/"><u>Explore the Best Alternatives for Microsoft's Core Apps</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-driver-software-update-for-windows-to-enhance-your-hp-officejet-pro-4650-printer-functionality/"><u>Free Driver Software Update for Windows to Enhance Your HP Officejet Pro 4650 Printer Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-this-app-will-not-work-on-your-device-error-in-windows/"><u>How to Fix This App Will Not Work on Your Device Error in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/lore-lovers-lab-bestest-bunch/"><u>Lore Lovers Lab – Bestest Bunch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-uninstalled-disk-errors-a-win-11-guide/"><u>Mastering the Art of Fixing 'Uninstalled Disk' Errors: A Win 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-nat-modification-for-enhanced-connectivity/"><u>Mastering the Art of NAT Modification for Enhanced Connectivity</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mastering-video-editing-replacing-audio-tracks-a-comprehensive-guide-part-1/"><u>Mastering Video Editing Replacing Audio Tracks - A Comprehensive Guide (Part 1)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-start-to-changing-your-win11-fax-cover-page-layout/"><u>Quick Start to Changing Your Win11 Fax Cover Page Layout</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-restoring-default-sound-settings-on-windows-tips-from-zdnet/"><u>Step-by-Step Guide: Restoring Default Sound Settings on Windows - Tips From ZDNet</u></a></li>
<li><a href="https://some-tips.techidaily.com/web-page-essentials-unlocking-effective-strategies-for-search-engines/"><u>Web Page Essentials: Unlocking Effective Strategies for Search Engines</u></a></li>
</ul></div>

