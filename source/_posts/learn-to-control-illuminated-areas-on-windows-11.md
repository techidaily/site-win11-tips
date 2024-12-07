---
title: Learn to Control Illuminated Areas on Windows 11
date: 2024-12-03T23:16:13.904Z
updated: 2024-12-06T21:35:41.143Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Learn to Control Illuminated Areas on Windows 11
excerpt: This Article Describes Learn to Control Illuminated Areas on Windows 11
keywords: Window 11 Lighting Control,Illuminated Windows Management,Bright Area Windows Regulation,Windows 11 Adjustable Lights,LED Windows Intelligent Switch,Windows 11 Illumination Guide,Manage Windows Lighting System
thumbnail: https://thmb.techidaily.com/14e8ddcfb81fc424c37a798e2f4fac450a83bd3f6d231984ceb0349e3e717f14.jpg
---

## Learn to Control Illuminated Areas on Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-inside-obs-alternatives-for-professional-streamers/"><u>[New] In 2024, Inside OBS Alternatives for Professional Streamers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-the-finest-selection-of-5-sd-cards-for-hero-gopros/"><u>[New] In 2024, The Finest Selection of 5 SD Cards for Hero GoPros</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-capture-brilliance-essential-lighting-hacks-for-iphone-for-2024/"><u>[Updated] Capture Brilliance Essential Lighting Hacks for IPhone for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-ending-dark-mode-glitches-on-playback/"><u>2024 Approved Ending Dark Mode Glitches on Playback</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-monitors-heres-how-to-swiftly-update-your-display-drivers/"><u>ASUS Monitors? Here’s How to Swiftly Update Your Display Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effortless-driver-updates-and-downloads-for-your-surface-book/"><u>Effortless Driver Updates & Downloads for Your Surface Book!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-task-management-in-windows-11/"><u>Enhancing Task Management in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/flawless-setup-how-to-obtain-and-install-the-hp-laserjet-pro-m402n-driver-for-windows-operating-systems/"><u>Flawless Setup: How to Obtain and Install the HP LaserJet Pro M402n Driver for Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-text-accessibility-incorporating-wordpad-triggers-in-windows-11/"><u>Improving Text Accessibility: Incorporating WordPad Triggers in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-microsoft-store-logins-with-easy-fixes/"><u>Master Microsoft Store Logins with Easy Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-storage-differentiation-distinguishing-hddssd-in-windows/"><u>Mastering Storage Differentiation: Distinguishing HDD/SSD in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/optimize-sound-quality-expert-tips-to-repair-your-obs-mic-troubles-this-year/"><u>Optimize Sound Quality: Expert Tips to Repair Your OBS Mic Troubles This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-revive-a-non-responsive-control-panel/"><u>Strategies to Revive a Non-Responsive Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synergy-of-data-windows-1011-file-management/"><u>Synergy of Data: Windows 10/11 File Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-windows-11-screensaver-preferences/"><u>Tailoring Your Windows 11 Screensaver Preferences</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/voiceover-your-videos-with-ease-top-6-pc-software-for-2024/"><u>Voiceover Your Videos with Ease Top 6 PC Software for 2024</u></a></li>
</ul></div>

