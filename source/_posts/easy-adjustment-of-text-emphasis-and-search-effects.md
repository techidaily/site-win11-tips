---
title: Easy Adjustment of Text Emphasis and Search Effects
date: 2024-10-05T23:54:37.931Z
updated: 2024-10-09T04:00:53.597Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Adjustment of Text Emphasis and Search Effects
excerpt: This Article Describes Easy Adjustment of Text Emphasis and Search Effects
keywords: Text Emphasis Adjust,Search Effects Tweak,Font Weight Change,Italics Control,Bold Text Shift,Highlight Options,Underline Modifier
thumbnail: https://thmb.techidaily.com/ab712e6369c11731fb797565c1d31f34a50ed98f4e3e4e20f2e0bcfb8f432b00.jpg
---

## Easy Adjustment of Text Emphasis and Search Effects

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-altering-mac-screenshot-format-on-the-fly-for-2024/"><u>[New] Altering Mac Screenshot Format on the Fly for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-capturing-vistas-with-the-high-end-z32x-monitor-for-2024/"><u>[New] Capturing Vistas with the High-End Z32X Monitor for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-refining-your-digital-footprint-editing-the-look-back-feature-for-2024/"><u>[Updated] Refining Your Digital Footprint Editing the Look Back Feature for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-snapshot-excellence-the-finest-software-on-market/"><u>[Updated] Snapshot Excellence The Finest Software on Market</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-file-formats-in-ms-office-suite-powerpoint-2016-word-and-excel/"><u>Adjusting Default File Formats in MS Office Suite (PowerPoint 2016, Word & Excel)</u></a></li>
<li><a href="https://fox-info.techidaily.com/enhancing-flight-experience-selecting-premium-fpv-drone-propellers-for-2024/"><u>Enhancing Flight Experience Selecting Premium FPV Drone Propellers for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Life360 from Tracking You On Realme GT Neo 5? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-se-2020-keeps-asking-for-outlook-password-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone SE (2020) Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-top-tier-emulators-for-gba-games-on-android/"><u>In 2024, Top-Tier Emulators for GBA Games on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/soon-your-photo-collection-can-be-easily-organized-in-microsoft-excel-for-windows-upcoming-import-functionality-revealed/"><u>Soon, Your Photo Collection Can Be Easily Organized in Microsoft Excel for Windows – Upcoming Import Functionality Revealed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-computing-the-mean-value-using-microsoft-excel/"><u>Step-by-Step Guide: Computing the Mean Value Using Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-creating-an-elegant-bubble-chart-with-microsoft-excel/"><u>Step-by-Step Guide: Creating an Elegant Bubble Chart with Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-eliminating-smart-tags-from-microsoft-excel-workbooks/"><u>Step-by-Step Guide: Eliminating Smart Tags From Microsoft Excel Workbooks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-modifying-and-customizing-cell-edges-in-microsoft-excel/"><u>Step-by-Step Guide: Modifying and Customizing Cell Edges in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-modifying-excel-gridline-colors-easily/"><u>Step-by-Step Guide: Modifying Excel Gridline Colors Easily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-charts-on-excel-sheets-tips-and-tricks/"><u>The Ultimate Guide to Fixing Charts on Excel Sheets – Tips and Tricks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    