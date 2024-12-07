---
title: "Unveiling the Obscured: System Tray on Win11"
date: 2024-12-01T17:55:16.766Z
updated: 2024-12-06T16:18:13.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unveiling the Obscured: System Tray on Win11"
excerpt: "This Article Describes Unveiling the Obscured: System Tray on Win11"
keywords: Win11 System Tray,Tray Icon Hidden,Win11 GUI Update,Tray Icons Uncovered,Windows Tray Notifications,System Tray Revealed,Notification Area in Win11
thumbnail: https://thmb.techidaily.com/c6048430c1339bc95d70af5b42f06e3231c3552b043c7e6cc92b16fd863d9438.jpg
---

## Unveiling the Obscured: System Tray on Win11

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-angles-the-complete-manual-for-effective-video-turns/"><u>[Updated] Instagram Angles The Complete Manual for Effective Video Turns</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-render-blur-effect-on-digital-snaps-in-ps/"><u>[Updated] Render Blur Effect on Digital Snaps in PS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-easy-path-to-engaging-animation-in-your-videos/"><u>[Updated] The Easy Path to Engaging Animation in Your Videos</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/apples-luxury-listening-gear-airpods-max/"><u>Apple's Luxury Listening Gear: AirPods Max</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-visual-wonders-in-lightrooms-hdr-workflow/"><u>Crafting Visual Wonders in Lightroom's HDR Workflow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desktop-deco-compelling-stick-on-apps-for-windows-enthusiasts/"><u>Desktop Deco: Compelling Stick-On Apps for Windows Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-fixes-rejuvenate-frozen-mouse-contexts-in-windows/"><u>Easy Fixes: Rejuvenate Frozen Mouse Contexts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-overcome-win11-cc-challenges/"><u>Expert Tips to Overcome Win11 CC Challenges</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-nubia-z50-ultra-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Nubia Z50 Ultra</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-unveiling-leading-edge-vr-developers/"><u>In 2024, Unveiling Leading-Edge VR Developers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-depth-look-at-instagrams-video-time-restrictions-for-2024/"><u>In-Depth Look at Instagram's Video Time Restrictions for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/iphone-16-upgrade-apple-enhances-camera-with-cutting-edge-visual-recognition-similar-to-google-lens-tech-news/"><u>IPhone 16 Upgrade: Apple Enhances Camera with Cutting-Edge Visual Recognition Similar to Google Lens – Tech News</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-infinite-treasure-in-dragon-game-tips-and-tricks-for-pc-users/"><u>Master the Art of 'Infinite Treasure' In Dragon Game - Tips & Tricks for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-powershell-script-execution-policy/"><u>Mastering the Art of PowerShell Script Execution Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-play-addressing-fall-guys-errors-on-windows/"><u>Streamlining Play: Addressing Fall Guys Errors on Windows</u></a></li>
</ul></div>

