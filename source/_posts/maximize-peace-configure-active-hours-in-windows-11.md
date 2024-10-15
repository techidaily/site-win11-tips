---
title: "Maximize Peace: Configure Active Hours in Windows 11"
date: 2024-10-12T02:48:48.989Z
updated: 2024-10-14T23:58:13.735Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Maximize Peace: Configure Active Hours in Windows 11"
excerpt: "This Article Describes Maximize Peace: Configure Active Hours in Windows 11"
keywords: Maximizing Peacetime,Window 11 Schedule,Harmony Windows Settings,Peaceful Windows Use,Quiet Hours Configuring,Calm Windows Timer,Tranquil PC Timings
thumbnail: https://thmb.techidaily.com/70cafb81e97d380bf1f55403cf595cebfeb242757ff19f24408692f694faf166.jpg
---

## Maximize Peace: Configure Active Hours in Windows 11

 Typically, the installation of Windows updates necessitates a system restart, which can cause disruptions during critical work sessions. However, by configuring active hours, you can define the specific times during which you generally use your computer for work. Once you do, Windows will schedule update installations to occur outside of these active hours, ensuring that your work sessions remain uninterrupted.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Set Active Hours Manually via the Settings App

 The Settings app in Windows gives you several options for managing the installation of Windows updates. Here's how you can use it to set active hours on Windows 11\.

1. Press **Win + I** to open the Settings app.
2. Navigate to the **Windows Update** tab using the left sidebar.
3. Select **Advanced options**.
4. Click on **Active hours** to expand it.
5. Use the drop-down menu next to **Adjust active hours** to select **Manually**.
6. In the **Start time** and **End time** fields, specify the hours during which you typically use your device.  
![Set Active Hours Manually via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-settings-app.jpg)

## 2\. How to Set Active Hours Manually Using the Group Policy Editor

 Although the Group Policy Editor on Windows is commonly used to manage advanced system-level settings, you can also use it to set active hours on your computer.

 Note that Group Policy Editor is only available on Professional, Education, and Enterprise editions of Windows. If you use Windows Home, check our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

 Follow these steps to set active hours on Windows using the Group Policy Editor.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end user experience**.
4. Double-click the **Turn off auto-restart for updates during active hours** policy on your right.
5. Select the **Enabled** option.
6. Under **Options**, use the drop-down menus next to **Start** and **End** to specify your active hours.
7. Hit **Apply** followed by **OK**.  
![Set Active Hours Manually via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Set Active Hours Manually With the Registry Editor

 Another method for setting active hours involves tweaking the Windows Registry.

 Although setting active hours via the Registry Editor is a straightforward process, it’s important to be cautious, as incorrect changes made to registry files can render your PC inoperable. If you opt for this method, make sure you either [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + S** to access the search menu.
2. Type **registry editor** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > WindowsUpdate > UX > Settings**.
5. Double-click the **ActiveHoursStart** entry.
6. In the **Value data** field, enter the desired value for the start time of your active hours in a 24-hour format. If you were to set the start time to **9:00 AM**, for instance, you would enter **9** in the text box.
7. Click **OK** to save the value.  
![Set Active Hours Manually via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-registry-editor.jpg)
8. Double-click the **ActiveHoursEnd** entry to set the end time of your active hours in the 24-hour format. For instance, if you want to set the end time to **5:00 PM**, type **17** in the Value data field and click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Exit the Registry Editor window.  
![Set Active Hours Manually via the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-manually-via-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. How to Configure Windows to Set Active Hours Automatically

 You can also configure Windows to set active hours automatically. Doing so will allow Windows to analyze your usage patterns and automatically adjust the active hours accordingly.

 To configure Windows to set active hours automatically:

1. Use one of [the many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Navigate to **Windows Update > Advanced options > Active hours**.
3. Click the drop-down menu next to **Adjust active hours** and select **Automatically**.  
![Set Active Hours Automatically on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-active-hours-automatically-on-windows.jpg)

## Setting Active Hours on Windows Is Easy

 Once you set the active hours using one of the above methods, Windows will avoid initiating automatic restarts for updates during the specified period. As a result, you won’t be interrupted by sudden reboots during your work hours.

 You can set active hours in Windows via the Settings app, the Group Policy Editor, or the Registry Editor. Let’s go through each of these methods in detail.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-buy-youtube-views-everything-you-need-to-know-for-2024/"><u>[Updated] How to Buy YouTube Views - Everything You Need To Know for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-instagram-acceleration-trendsetting-with-likes-and-videos/"><u>[Updated] In 2024, Instagram Acceleration Trendsetting with Likes & Videos</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/clear-cut-content-how-to-minimize-unwanted-elements-in-video/"><u>Clear Cut Content How to Minimize Unwanted Elements in Video</u></a></li>
<li><a href="https://win11-tips.techidaily.com/controlling-visibility-of-clock-on-windows-11-bar/"><u>Controlling Visibility of Clock on Windows 11 Bar</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-asus-rog-strix-xg27acs-qhd-180hz-gaming-display-a-true-game-changer-in-visuals-and-response-times/"><u>Exploring the Asus ROG Strix XG27ACS QHD 180Hz Gaming Display - A True Game Changer in Visuals and Response Times</u></a></li>
<li><a href="https://win11-tips.techidaily.com/make-windows-emailcalendar-pop-infuse-it-with-pics/"><u>Make Windows Email/Calendar Pop: Infuse It With Pics</u></a></li>
<li><a href="https://driver-download.techidaily.com/razer-gaming-drivers-for-all-windows-platforms-windows-10-8-7-xp-and-vista-download-instructions/"><u>Razer Gaming Drivers for All Windows Platforms (Windows 10, 8, 7, XP, and Vista): Download Instructions</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-disabled-radeon-software-on-windows-computers/"><u>Solutions for Disabled Radeon Software on Windows Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-high-energy-spikes-a-guide-for-windows-users/"><u>Taming High Energy Spikes: A Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-techniques-for-an-improved-start-screen-in-windows-11/"><u>Top Techniques for an Improved Start Screen in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/zerogpt-and-peers-are-they-trustworthy-for-accurate-ai-detection-evidence-based-analysis/"><u>ZeroGPT and Peers: Are They Trustworthy for Accurate AI Detection? Evidence-Based Analysis</u></a></li>
</ul></div>

