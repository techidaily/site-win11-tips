---
title: Tips for Managing Text Highlighting in Windows 11
date: 2024-10-31T04:27:29.694Z
updated: 2024-11-07T06:50:01.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Managing Text Highlighting in Windows 11
excerpt: This Article Describes Tips for Managing Text Highlighting in Windows 11
keywords: Highlight Management,Windows 11 Tip Guide,Text Color Adjustment,Highlighter Tools,W11 UI Enhancement,Display Settings Fix,Windows 11 Tips
thumbnail: https://thmb.techidaily.com/1b3acf6f92837e9104aa399e6aa268354b94b6b827af6bb095b68b19082ca48f.png
---

## Tips for Managing Text Highlighting in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484951/16446" target="_top" id="1484951">
  <img src="//a.impactradius-go.com/display-ad/16446-1484951" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484951/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-unlocking-screen-record-features-in-hp-computers/"><u>[New] Unlocking Screen Record Features in HP Computers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-speakers-file-extract-and-analysis/"><u>[Updated] 2024 Approved Speaker's File Extract & Analysis</u></a></li>
<li><a href="https://program-issues.techidaily.com/1723012291102-destiny-2s-beyond-light-update-flawlessly-implemented-on-pc-no-more-crashes/"><u>Destiny 2'S Beyond Light Update Flawlessly Implemented on PC - No More Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-win-error-31-and-regain-online-access/"><u>Eliminating WIN Error 31 and Regain Online Access</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-itel-p40plus-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Itel P40+ Fingerprint Lock</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-google-pixel-8-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Google Pixel 8 Face Lock?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-the-innovative-world-of-intova-x/"><u>In 2024, Inside the Innovative World of Intova X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-dual-recording-incorporating-sound-with-windows-11s-snipping-tool-max-156/"><u>Master the Art of Dual Recording: Incorporating Sound with Windows 11’S Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-productivity-pinning-gmail-icons-to-your-windows-taskbar/"><u>Maximizing Productivity: Pinning Gmail Icons to Your Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-live-updates-for-win-11s-task-monitor/"><u>Optimize Live Updates for Win 11'S Task Monitor</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcome-pc-restoration-issues-on-windows-11-an-effective-error-resolution-strategy/"><u>Overcome PC Restoration Issues on Windows 11: An Effective Error Resolution Strategy</u></a></li>
<li><a href="https://network-issues.techidaily.com/streamline-windows-11-high-res-settings/"><u>Streamline Windows 11 High-Res Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/take-command-streamlining-windows-operations-with-hotkeys/"><u>Take Command: Streamlining Windows Operations with Hotkeys</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-pictures-on-oppo-reno-11-pro-5g-without-backup-by-fonelab-android-recover-pictures/"><u>The way to recover deleted pictures on Oppo Reno 11 Pro 5G without backup.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-potential-with-these-non-windows-apps/"><u>Unleash Potential With These Non-Windows Apps</u></a></li>
</ul></div>

