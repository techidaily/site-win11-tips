---
title: Navigating to the Shadowed Elements of Windows 11
date: 2024-11-25T16:58:31.816Z
updated: 2024-11-27T17:24:40.086Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to the Shadowed Elements of Windows 11
excerpt: This Article Describes Navigating to the Shadowed Elements of Windows 11
keywords: W11 SEO Guide,Windows 11 Optimization,Shadowed Features Explained,Win11 Keyword Strategy,Enhancing Win11 SEO,Understanding Windows 11 SEO,Navigate Win11 SEO Tips
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Navigating to the Shadowed Elements of Windows 11

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-choosing-free-video-editing-software-on-iphone-and-ipad/"><u>[Updated] 2024 Approved Choosing Free Video Editing Software on iPhone & iPad</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-a-guide-to-the-best-5-book-tt-examples/"><u>[Updated] A Guide to the Best 5 Book TT Examples</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-pc-ui-with-customizable-weather-icon-addition-in-windows-11-system-tray/"><u>Elevate PC UI with Customizable Weather Icon Addition in Windows 11 System Tray</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-silent-speaker-mistakes-in-windows/"><u>Eliminating Silent Speaker Mistakes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/find-missing-control-panel-options-on-windows-11/"><u>Find Missing Control Panel Options on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/forza-horizon-navigates-2024-top-tricks-to-get-past-startup-problems/"><u>Forza Horizon Navigates 2024: Top Tricks to Get Past Startup Problems</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/gotthard-base-tunnel-switzerland/"><u>Gotthard Base Tunnel, Switzerland</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-fetch-and-implement-the-newest-intel-hd-graphics-card-driver-software/"><u>How to Fetch and Implement the Newest Intel HD Graphics Card Driver Software</u></a></li>
<li><a href="https://fox-direct.techidaily.com/leading-spots-for-stunning-3d-metallic-type-creations-for-2024/"><u>Leading Spots for Stunning 3D Metallic Type Creations for 2024</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/los-reproductores-mas-elegidos-de-formatos-mkv-en-windowsmac-ranking-y-analisis-expertos-para-2020/"><u>Los Reproductores Más Elegidos De Formatos MKV en Windows/Mac: Ranking Y Análisis Expertos Para 2020</u></a></li>
<li><a href="https://youtube-help.techidaily.com/navigating-updated-earnings-policies-for-streamers-for-2024/"><u>Navigating Updated Earnings Policies for Streamers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagine-your-inbox-and-agenda-with-favourite-snaps/"><u>Reimagine Your Inbox & Agenda with Favourite Snaps</u></a></li>
</ul></div>

