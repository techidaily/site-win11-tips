---
title: Unlocking the Concealed Icon Menu of Win11
date: 2024-12-19T21:40:52.970Z
updated: 2024-12-22T03:11:31.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking the Concealed Icon Menu of Win11
excerpt: This Article Describes Unlocking the Concealed Icon Menu of Win11
keywords: Win11 Icon Secrets,Hidden Windows Features,Icon Menus Uncovered,Accessing Win11 Options,Win11 Menu Exploration,Concealed Controls in Win11,Win11 Interface Insights
thumbnail: https://thmb.techidaily.com/0741b6d6b142e6d035036f6df7e304509ca00be9b2a4f404614a92dadcad15cd.jpg
---

## Unlocking the Concealed Icon Menu of Win11

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://network-issues.techidaily.com/fixed-zoom-camera-not-working-2024-guide/"><u>[Fixed] Zoom Camera Not Working 2024 Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-vector-editing-revolution-post-acid-pro-era/"><u>[New] 2024 Approved Vector Editing Revolution Post-ACID Pro Era</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-conveniently-record-your-favorite-streams-top-5-grabber-apps-for-2024/"><u>[New] Conveniently Record Your Favorite Streams Top 5 Grabber Apps for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-10-ways-to-optimize-instagram-highlights-for-your-business/"><u>[Updated] 10 Ways to Optimize Instagram Highlights for Your Business</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-rhythmic-reinvention-the-art-of-voice-in-free-fire/"><u>2024 Approved Rhythmic Reinvention The Art of Voice in Free Fire</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/become-a-reddit-star-detailed-steps-for-share-success/"><u>Become a Reddit Star Detailed Steps for Share Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clear-out-windows-a-guide-to-auto-delete-files-and-folders/"><u>Clear Out Windows: A Guide to Auto-Delete Files and Folders</u></a></li>
<li><a href="https://extra-information.techidaily.com/clear-the-chaos-edit-and-cull-your-bulky-tiktok-collections-for-2024/"><u>Clear the Chaos Edit & Cull Your Bulky TikTok Collections for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-windows-users-fixing-asana-errors/"><u>Essential Tips for Windows Users - Fixing Asana Errors</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/no-drive-letters-in-windows-causes-and-resolutions/"><u>No Drive Letters in Windows: Causes & Resolutions</u></a></li>
<li><a href="https://buynow-info.techidaily.com/optimizing-your-connectivity-inside-look-at-asus-ax6600-mesh-wi-fis-capabilities-and-efficiency/"><u>Optimizing Your Connectivity: Inside Look at Asus AX6600 Mesh Wi-Fi's Capabilities & Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-multi-modal-captures-how-to-use-snipping-tools-audio-feature-max-156/"><u>Perfecting Multi-Modal Captures: How to Use Snipping Tool's Audio Feature (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-self-shutdown-issues-win11-techniques/"><u>Solve Self-Shutdown Issues: Win11 Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-mastering-bluescreenview/"><u>Step-by-Step Guide to Mastering BlueScreenView</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-volume-mixer-a-step-by-step-guide/"><u>Windows 11 Volume Mixer: A Step-by-Step Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    