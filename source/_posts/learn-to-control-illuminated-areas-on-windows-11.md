---
title: Learn to Control Illuminated Areas on Windows 11
date: 2024-11-22T16:21:47.398Z
updated: 2024-11-27T16:41:42.333Z
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

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/n-2024-cultivate-creativity-inspiration-driven-video-titles/"><u>[New] In 2024, Cultivate Creativity Inspiration-Driven Video Titles</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-media-showdown-podcasts-vs-youtube-in-the-modern-world/"><u>2024 Approved Media Showdown Podcasts Vs. YouTube in the Modern World</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-honor-x50-gt-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Honor X50 GT via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/bluescreen-in-windows-dxgkrnlsys-issue-fixed/"><u>BlueScreen in Windows - dxgkrnl.sys Issue Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-the-application-couldnt-start-error/"><u>Deciphering and Solving The Application Couldn't Start Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-error-0x80073d26-in-microsoft-store/"><u>Fixing Windows 10/11 Error 0X80073D26 in Microsoft Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-pc-screen-intensity-on-windows-11/"><u>How to Control PC Screen Intensity on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-asus-rog-phone-8-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Asus ROG Phone 8 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-ring-induced-voice-memo-iphone-24/"><u>In 2024, Ring-Induced Voice Memo - iPhone '24</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-reinstalling-nvidia-software/"><u>Resolved: Reinstalling NVIDIA Software</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/thriving-in-the-youtube-landscape-with-data-driven-approach-for-2024/"><u>Thriving in the YouTube Landscape with Data-Driven Approach for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-addressing-disconnected-steam-content-on-home-systems/"><u>Tips for Addressing Disconnected Steam Content on Home Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transitioning-from-quick-access-to-file-explorer-via-onedrive/"><u>Transitioning From Quick Access to File Explorer via OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-resolving-package-registration-errors-in-images/"><u>Troubleshooting Windows 11: Resolving Package Registration Errors in Images</u></a></li>
<li><a href="https://extra-tips.techidaily.com/your-guide-to-masterful-mememaking-on-9gag/"><u>Your Guide to Masterful Mememaking on 9GAG</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    