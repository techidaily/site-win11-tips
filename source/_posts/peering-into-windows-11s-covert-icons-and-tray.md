---
title: Peering Into Windows 11'S Covert Icons & Tray
date: 2024-11-26T16:54:31.093Z
updated: 2024-11-27T16:18:48.256Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Peering Into Windows 11'S Covert Icons & Tray
excerpt: This Article Describes Peering Into Windows 11'S Covert Icons & Tray
keywords: Win11CovertIcons,TrayIconTechniques,HiddenWindows11,Windows11Secrets,CovertTrayFeatures,IconsUnderScan,StealthWinTools
thumbnail: https://thmb.techidaily.com/6644f0a2d74892fa3a39d2d46d9f44395a7ca3377bb37001448c4704afb2e518.jpg
---

## Peering Into Windows 11'S Covert Icons & Tray

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-discover-youtubes-free-text-translations-and-downloads/"><u>[New] 2024 Approved Discover YouTube's Free Text Translations & Downloads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-write-on-windows-of-imagery-ios-and-android-leaders/"><u>[Updated] 2024 Approved Write on Windows of Imagery – iOS & Android Leaders</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-elevating-views-amplifying-impact-a-youtube-case-study-for-2024/"><u>[Updated] Elevating Views, Amplifying Impact A Youtube Case Study for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-music-transfer-essentials-keeping-your-playlist-alive/"><u>[Updated] Music Transfer Essentials Keeping Your Playlist Alive</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unveiling-top-rated-video-recorders-for-windows-for-2024/"><u>[Updated] Unveiling Top-Rated Video Recorders for Windows for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-master-pip-feature-while-consuming-youtube-videos-on-iphones/"><u>2024 Approved Master PIP Feature While Consuming YouTube Videos on iPhones</u></a></li>
<li><a href="https://extra-resources.techidaily.com/chromatic-confluence-music-and-photography-online/"><u>Chromatic Confluence Music & Photography Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enablingdisabling-secure-boot-and-tpm-in-virtualbox-for-enhanced-security/"><u>Enabling/Disabling Secure Boot and TPM in VirtualBox for Enhanced Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-the-family-shield-top-5-strategies-to-patch-up-issues/"><u>Fix the Family Shield: Top 5 Strategies to Patch Up Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-package-unopened-problem-on-ws11-10-oses/"><u>How to Fix the 'Package Unopened' Problem on WS11, 10 OSes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-building-a-visual-story-on-facebook-with-slideshows/"><u>In 2024, Building a Visual Story on Facebook with Slideshows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/large-storage-at-a-cost-mp60s-speed-story/"><u>Large Storage at a Cost - MP60's Speed Story</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/master-the-art-of-backup-phones-camera-roll-upload-to-social-apps/"><u>Master the Art of Backup Phone's Camera Roll Upload to Social Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-privilege-needed-redirects-on-windows-machines/"><u>Navigating 'Privilege Needed' Redirects on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-network-ghosting-on-pc/"><u>Overcoming Network Ghosting on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-key-steps-for-controlling-settings-in-windows/"><u>Quick Key Steps for Controlling Settings in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-the-geforce-experience-scanning-woes-on-your-win/"><u>Solve the GeForce Experience Scanning Woes on Your Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-package-unopenable-error-a-step-by-step-guide/"><u>Solving Windows' Package Unopenable Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/top-10-best-gif-speed-changers-for-2024/"><u>Top 10 Best GIF Speed Changers for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    