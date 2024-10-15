---
title: How To Adjust Text Emphasis and Search Highlights
date: 2024-10-08T23:07:28.876Z
updated: 2024-10-15T02:21:56.620Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Adjust Text Emphasis and Search Highlights
excerpt: This Article Describes How To Adjust Text Emphasis and Search Highlights
keywords: Text Highlighting Guide,Emphasize Text Tips,Search Highlighting Hacks,Text Emphasis Adjustment,Text Formatting Basics,Text Styling Techniques,Highlight Keywords Efficiently
thumbnail: https://thmb.techidaily.com/69f3067d39675d6781ab4c7e0458c920b25824edab0f0d8186f7e1accf89f14a.jpg
---

## How To Adjust Text Emphasis and Search Highlights

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
<a href="https://aligracehair.sjv.io/c/5597632/1925484/19272" target="_top" id="1925484">
  <img src="//a.impactradius-go.com/display-ad/19272-1925484" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925484/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-the-ultimate-guide-to-t5s-action-footage/"><u>[New] The Ultimate Guide to T5's Action Footage</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-is-there-a-superior-cameras-marketplace/"><u>[Updated] In 2024, Is There a Superior Cameras Marketplace?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-the-power-of-easy-video-editing-in-photos-and-windows-11-for-2024/"><u>Explore the Power of Easy Video Editing in Photos & Windows 11 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-inactive-windows-key-in-os-11/"><u>Fixing Inactive Windows Key in OS 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/flac-aviflacmovavi/"><u>FLAC格式自動化 - AVI到FLAC無成本轉換解決方案：Movavi</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-correctly-address-the-d3dx924dll-missing-system-error/"><u>How to Correctly Address the d3dx9_24.dll Missing System Error</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-14-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-external-devices-with-file-manager/"><u>Integrating External Devices with File Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-your-network-address-with-cli-win-os/"><u>Locate Your Network Address with CLI, Win OS</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/screen-to-air-assessing-obs-and-twitch-studios-features/"><u>Screen to Air Assessing OBS and Twitch Studio's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-corrupted-file-error-code-0x80070570-on-windows-11/"><u>Strategies to Overcome Corrupted File (Error Code 0X80070570) on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-audio-experience-using-windows-11s-mixer/"><u>Streamline Your Audio Experience Using Windows 11'S Mixer</u></a></li>
</ul></div>

