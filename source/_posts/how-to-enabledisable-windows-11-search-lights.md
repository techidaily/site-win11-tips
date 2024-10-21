---
title: How to Enable/Disable Windows 11 Search Lights
date: 2024-10-18T23:39:10.285Z
updated: 2024-10-20T17:35:20.307Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable/Disable Windows 11 Search Lights
excerpt: This Article Describes How to Enable/Disable Windows 11 Search Lights
keywords: Disable Windows Search Light,Enable Windows 11 Search,Windows 11 Dark Mode,Turn Off Windows Notification,Reduce Windows Reflections,Adjust Windows Lights Out,Mute Windows Soundscape
thumbnail: https://thmb.techidaily.com/b0350890102e8bceb542486b6a13817e51d92335c8505179cd1df5114471ab31.jpg
---

## How to Enable/Disable Windows 11 Search Lights

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
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-a-step-by-step-tutorial-to-monetize-product-videography/"><u>[New] 2024 Approved A Step-by-Step Tutorial to Monetize Product Videography</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-essential-inexpensive-vlogging-tools-listed-for-2024/"><u>[New] Essential, Inexpensive Vlogging Tools Listed for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quick-windows-data-evaluation-guide/"><u>[Updated] Quick Windows Data Evaluation Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-maximize-engagement-auto-resized-videos-from-mac-for-instagram/"><u>2024 Approved Maximize Engagement Auto-Resized Videos From Mac for Instagram</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/2024s-top-netgear-routers-ranked-find-your-perfect-home-wifi-solution-today/"><u>2024'S Top Netgear Routers Ranked: Find Your Perfect Home WiFi Solution Today</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-differences-a-comparative-look-at-local-and-microsoft-windows-logins/"><u>Delving Into Differences: A Comparative Look at Local & Microsoft Windows Logins</u></a></li>
<li><a href="https://vp-tips.techidaily.com/dvd-handbrake/"><u>DVD/動画ファイルの変換と圧縮: HandBrakeで高画質を実現します</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ease-your-way-past-windows-exe-opening-blocks/"><u>Ease Your Way Past Windows Exe Opening Blocks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-ram-cache-management-on-windows-os/"><u>Efficient RAM Cache Management on Windows OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-no-detect-logitech-receiver-in-latest-windows/"><u>Fix: No Detect Logitech Receiver in Latest Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-to-access-and-watch-your-movies-with-videots-files-essential-troubleshooting-steps/"><u>How To Access & Watch Your Movies With VIDEO_TS Files - Essential Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/install-unseen-windows-tools-a-practical-how-to/"><u>Install Unseen Windows Tools: A Practical How-To</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-and-rectify-hidden-storage-on-pc/"><u>Locate and Rectify Hidden Storage on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-cure-for-onedrives-0x8004dec5-sign-in-crisis-in-windows/"><u>Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-fixes-for-mute-issues-in-black-ops-cold-war-gameplay-on-your-desktop-computer/"><u>Quick Fixes for Mute Issues in Black Ops Cold War Gameplay on Your Desktop Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-method-deactivate-hyper-v-on-windows-11-os/"><u>Quick Method: Deactivate Hyper-V on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-erratic-behavior-of-windows-event-viewer/"><u>Resolving Erratic Behavior of Windows Event Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-identifying-faulty-hardware-in-windows-1011/"><u>Techniques for Identifying Faulty Hardware in Windows 10/11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-limitations-why-cant-ai-like-chatgpt-detect-self-generated-text/"><u>Understanding the Limitations: Why Can't AI Like ChatGPT Detect Self-Generated Text?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    