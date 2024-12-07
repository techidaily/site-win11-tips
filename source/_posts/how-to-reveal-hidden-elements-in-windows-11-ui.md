---
title: How to Reveal Hidden Elements in Windows 11 UI
date: 2024-12-02T18:56:25.684Z
updated: 2024-12-07T00:22:41.201Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reveal Hidden Elements in Windows 11 UI
excerpt: This Article Describes How to Reveal Hidden Elements in Windows 11 UI
keywords: Win11 UI Finders,Hidden UI Highlighters,Uncovering WinUI,Show Windows 11 Elements,Discover Windows UI Features,Reveal UX Elements Win11,Expose OS UI Components
thumbnail: https://thmb.techidaily.com/72529af7d2bf02239916cd0ba31d950846919ac8ac9ff5b071dc373f5d27eae7.jpg
---

## How to Reveal Hidden Elements in Windows 11 UI

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harness-youtubes-power-with-these-top-7-affordable-easy-to-use-tag-extractor-tools/"><u>[New] 2024 Approved Harness YouTube's Power with These Top 7 Affordable, Easy-to-Use Tag Extractor Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-depth-look-at-instagrams-video-time-restrictions/"><u>[New] In-Depth Look at Instagram's Video Time Restrictions</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-slow-motion-symphony-a-comprehensive-app-analysis-2024/"><u>[New] Slow Motion Symphony A Comprehensive App Analysis, 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-toggle-picture-in-picture-youtube-viewing-tips-for-ios-users/"><u>[Updated] Toggle Picture In Picture YouTube Viewing Tips for iOS Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-honor-80-pro-straight-screen-edition-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Honor 80 Pro Straight Screen Edition to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-to-revitalize-ailing-windows-programs/"><u>Effective Strategies to Revitalize Ailing Windows Programs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-download-latest-wacom-intuos-graphics-tablet-drivers/"><u>Free Download: Latest Wacom Intuos Graphics Tablet Drivers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-vivo-y100-5g-phone-without-google-account-by-drfone-android/"><u>How to Unlock Vivo Y100 5G Phone without Google Account?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-written-expression-on-a-windows-pc/"><u>Master the Art of Written Expression on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-engage-or-disengage-win-11s-safety-feature/"><u>Steps to Engage or Disengage Win 11’S Safety Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/supercharge-your-day-on-windows-11-with-these-5-tools/"><u>Supercharge Your Day on Windows 11 with These 5 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-commands-and-shortcuts-in-windows-os/"><u>Tailored Commands and Shortcuts in Windows OS</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-buccaneers-guide-key-slang-for-seafaring-characters/"><u>The Buccaneer's Guide: Key Slang for Seafaring Characters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-techniques-opening-up-windows-11-appsfolders/"><u>Unveiling the Techniques: Opening Up Windows 11 AppsFolders</u></a></li>
</ul></div>

