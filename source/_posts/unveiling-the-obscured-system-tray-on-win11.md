---
title: "Unveiling the Obscured: System Tray on Win11"
date: 2024-11-24T17:00:05.483Z
updated: 2024-11-27T17:18:43.577Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-androids-free-screen-snip-picks-our-best-8-on-display/"><u>[New] 2024 Approved Android's Free Screen Snip Picks – Our Best 8 on Display</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-unpacking-manycams-revolutionary-recording-features-for-2024/"><u>[New] Unpacking ManyCam's Revolutionary Recording Features for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-navigating-video-production-with-captivate-for-2024/"><u>[Updated] Navigating Video Production with Captivate for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/elite-5-screen-grab-for-fb-movies/"><u>Elite 5 Screen Grab for FB Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-keeping-login-details-private-on-pc/"><u>Guide to Keeping Login Details Private on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correctly-open-installation-packages-on-windows-10-11/"><u>How to Correctly Open Installation Packages on Windows 10, 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-professionals-choice-best-drone-gimbals/"><u>In 2024, Professional's Choice Best Drone Gimbals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-in-resolving-common-windows-11-issues/"><u>Precision in Resolving Common WINDOWS 11 Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-to-enhance-windows-11-bar/"><u>Quick Fixes to Enhance Windows 11 Bar</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simplifying-systems-administration-how-red-hat-leverages-artificial-intelligence/"><u>Simplifying Systems Administration: How Red Hat Leverages Artificial Intelligence</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-downloading-and-installing-camera-drivers-for-all-windows-oses/"><u>Step-by-Step Guide to Downloading and Installing Camera Drivers for All Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-vision-behind-microsoft-stores-ai-hub/"><u>The Vision Behind Microsoft Store's AI Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-thermal-regulation-options/"><u>Unlocking Windows Thermal Regulation Options</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/which-is-more-beneficial-learning-german-or-french/"><u>Which Is More Beneficial? Learning German or French</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    