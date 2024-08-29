---
title: Navigating to the Shadowed Elements of Windows 11
date: 2024-08-28T01:17:54.483Z
updated: 2024-08-29T01:17:54.483Z
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
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-lightroom-workflow-creating-and-merging-professional-hdr-images/"><u>[New] 2024 Approved  Lightroom Workflow  Creating & Merging Professional HDR Images</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-recording-revelry-capturing-the-thrill-of-sports-games/"><u>[New] In 2024, Recording Revelry  Capturing the Thrill of Sports Games</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-add-a-youtube-video-to-google-slides-for-2024/"><u>[Updated] How to Add a YouTube Video to Google Slides for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-the-ultimate-guide-to-discord-live-broadcasts/"><u>[Updated] In 2024, The Ultimate Guide to Discord Live Broadcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-lunar-luster-online-a-curated-list-of-hdr-sky-images/"><u>[Updated] Lunar Luster Online  A Curated List of HDR Sky Images</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-ios-choice-premium-psp-emulators-ranked-1-5/"><u>2024 Approved  IOS Choice  Premium PSP Emulators Ranked #1-5</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-audio-format-switches-srt-to-ssa-and-more/"><u>2024 Approved  Mastering Audio Format Switches  SRT to SSA & More</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-the-final-verdict-on-vegas-pro-21-a-sports-enthusiasts-review/"><u>2024 Approved  The Final Verdict on Vegas Pro '21 - A Sports Enthusiast's Review</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/beyerdynamic-mmx-30e-pro-headphones-tested-exceptional-sound-with-basic-functionality/"><u>Beyerdynamic MMX 30E Pro Headphones Tested - Exceptional Sound with Basic Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-invisible-button-on-taskview-bar/"><u>Crafting an Invisible Button on TaskView Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-microsofts-conversational-ai/"><u>Disabling Microsoft's Conversational AI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-ultimate-tools-for-international-peak-level-mouse-usage/"><u>Discover the Ultimate Tools for International, Peak-Level Mouse Usage</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-canon-pixma-ip1600-software-suite-for-optimal-performance-with-windows-1087/"><u>Download and Install Canon PIXMA iP1600 Software Suite for Optimal Performance with Windows 10/8/7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-steps-to-windows-ready-website-apps/"><u>Easy Steps to Windows-Ready Website Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-for-creating-slideshow-magic-and-spot-corrections-in-windows-11-photos/"><u>Expert Tips for Creating Slideshow Magic and Spot Corrections in Windows 11 Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-working-taskbar-elements-in-windows/"><u>Fixing Non-Working Taskbar Elements in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-activating-terminals-quake-modes/"><u>Guide to Activating Terminal's Quake Modes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-by-checkra1n-even-on-apple-iphone-12-mini-if-youve-tried-everything-by-drfone-ios/"><u>How To Bypass iCloud By Checkra1n Even On Apple iPhone 12 mini If Youve Tried Everything</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-microsofts-web-browser-in-win11/"><u>How to Remove Microsoft's Web Browser in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-skip-the-onedrive-icon-on-windows-11-file-explorer/"><u>How To Skip the OneDrive Icon on Windows 11 File Explorer</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-extracting-stills-for-windows-11-video-projects/"><u>In 2024, Extracting Stills for Windows 11 Video Projects</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-game-changer-or-gamble-a-2021-review-of-vegas-pros-evolution/"><u>In 2024, Game Changer or Gamble? A 2021 Review of Vegas Pro's Evolution</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-sharing-stories-that-resonate-with-a-digital-audience-yt/"><u>In 2024, Sharing Stories that Resonate with a Digital Audience YT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-smart-color-automation-for-win11-software-suite/"><u>Introducing Smart Color Automation for Win11 Software Suite</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-a2-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo A2 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-repairing-windows-service-not-responding-errors/"><u>Mastering the Art: Repairing Windows Service Not Responding Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-new-wins-setbacks-to-standard-users/"><u>Navigating Through New Wins: Setbacks to Standard Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quicken-keystrokes-with-windows-powertoys/"><u>Quicken Keystrokes with Windows PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resize-windows-11-ui-elements-for-better-visibility/"><u>Resize Windows 11 UI Elements for Better Visibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-audio-glitch-win11s-error-0xc00d36b4/"><u>Solving Audio Glitch: Win11's Error 0XC00D36B4</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-network-errors-in-the-latest-windows-os/"><u>Steps for Overcoming Network Errors in the Latest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-tweaks-lessening-apps-resource-consumption/"><u>System Tweaks: Lessening Apps' Resource Consumption</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-motorola-moto-g23-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Motorola Moto G23 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-role-of-winservicesexe-in-windows-systems/"><u>The Role of Winservices.exe in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-netgear-nighthawk-x6-wi-fi-expansion-unit-a-full-feature-breakdown/"><u>Ultimate Guide to Netgear Nighthawk X6 Wi-Fi Expansion Unit - A Full Feature Breakdown</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-executing-windows-restore-operations/"><u>Understanding and Executing Windows Restore Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-creativity-with-top-video-editors-on-windows-11/"><u>Unleash Creativity with Top Video Editors on Windows 11</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/unveiling-tiktok-to-twitter-conversion-for-2024/"><u>Unveiling TikTok to Twitter Conversion for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-mastering-sound-silence-in-imovie-a-comprehensive-guide/"><u>Updated Mastering Sound Silence in iMovie A Comprehensive Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/vegaspros-new-era-reviewed-2019/"><u>VegasPro's New Era Reviewed (2019)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-back-your-elusive-5ghz-connection-with-these-solutions/"><u>Win Back Your Elusive 5GHz Connection with These Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-quick-keyboard-shortcut-guide/"><u>Windows 11: Quick Keyboard Shortcut Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>