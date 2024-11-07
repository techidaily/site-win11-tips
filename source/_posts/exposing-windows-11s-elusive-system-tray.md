---
title: Exposing Windows 11'S Elusive System Tray
date: 2024-11-06T12:28:25.042Z
updated: 2024-11-07T07:24:38.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exposing Windows 11'S Elusive System Tray
excerpt: This Article Describes Exposing Windows 11'S Elusive System Tray
keywords: Windows 11 Tray Hidden,Tray Icon Missing Win11,System Tray Disappearance W11,Elusive Win11 Tray Icon,Unveiling Win11 Tray Vanish,Find Windows 11 Tray,Restore Win11 System Tray
thumbnail: https://thmb.techidaily.com/d1e396e3c497492ee5cb72e95e743dcb132cd92c3b826346b76ee873a38b74bb.jpg
---

## Exposing Windows 11'S Elusive System Tray

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

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068417/7443" target="_top" id="2068417">
  <img src="//a.impactradius-go.com/display-ad/7443-2068417" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068417/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crafting-charismatic-videos-with-diy-camera-setups/"><u>[New] 2024 Approved Crafting Charismatic Videos with DIY Camera Setups</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-audio-finesse-advanced-editing-strategies-for-podcasters/"><u>[New] The Art of Audio Finesse Advanced Editing Strategies for Podcasters</u></a></li>
<li><a href="https://win-unique.techidaily.com/1-quick-guide-seamlessly-moving-4k-footage-from-iphone-to-laptop/"><u>1. Quick Guide: Seamlessly Moving 4K Footage From iPhone to Laptop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriching-user-interface-the-roadmap-for-future-widgets-in-windows-11/"><u>Enriching User Interface: The Roadmap for Future Widgets in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-mediocre-to-marvelous-an-exhaustive-facetune-analysis-for-2024/"><u>From Mediocre to Marvelous An Exhaustive Facetune Analysis for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-maximum-heat-dispersion-with-id-cooling-fx360-pro-excellent-quality-at-60/"><u>Get Maximum Heat Dispersion with ID-Cooling FX360 Pro - Excellent Quality at $60</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-nvidia-revolutionizes-graphics-management-by-merging-control-panel-and-geforce-experience-into-one-app/"><u>How Nvidia Revolutionizes Graphics Management by Merging Control Panel and GeForce Experience Into One App</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-10-superior-tools-for-fbx-file-recording/"><u>In 2024, 10 Superior Tools for FBX File Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-spotifys-connection-realms-a-win11-guide/"><u>Mastering Spotify's Connection Realms: A Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-lost-razer-devices-with-synapse-in-windows-11/"><u>Reconnecting Lost Razer Devices with Synapse in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-overcoming-missing-items-problem-in-windows-11/"><u>Strategies for Overcoming 'Missing Items' Problem in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/update-your-logitech-g403-with-the-new-drivers-on-windows-pcs/"><u>Update Your Logitech G403 with the New Drivers on Windows PCs</u></a></li>
</ul></div>

