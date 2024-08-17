---
title: A Guide to Reversing Frozen Dark Theme on Computers
date: 2024-08-16T01:43:19.866Z
updated: 2024-08-17T01:43:19.866Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Guide to Reversing Frozen Dark Theme on Computers
excerpt: This Article Describes A Guide to Reversing Frozen Dark Theme on Computers
keywords: Fix Frozen Dark Theme,Restore Screen Color,Change Computer Theme,Reset Windows Theme,Adjust Display Settings,Revert Theming,Dark Mode Reset
thumbnail: https://thmb.techidaily.com/43e39de2530caaef8af78f1650abc11434992b40c432e7b5caac8bd0f3cdf48f.png
---

## A Guide to Reversing Frozen Dark Theme on Computers

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-revel-in-the-rhythm-of-rising-text/"><u>[New] 2024 Approved  Revel in the Rhythm of Rising Text</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-visual-prowess-meets-audio-excellence-top-5-hd-webcams/"><u>[New] 2024 Approved  Visual Prowess Meets Audio Excellence - Top 5 HD Webcams</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-a-comprehensible-guide-to-screen-recording-on-the-mi-11/"><u>[New] In 2024, A Comprehensible Guide to Screen Recording on the Mi 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-uniting-platforms-post-videos-across-twitter-and-tumblr/"><u>[New] In 2024, Uniting Platforms  Post Videos Across Twitter & Tumblr</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-art-of-retention-capturing-gifs-from-social-media-for-2024/"><u>[New] The Art of Retention  Capturing GIFs From Social Media for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-perfecting-pics-with-practicality-top-5-pc-snipping-tools/"><u>[Updated] In 2024, Perfecting Pics with Practicality - Top 5 PC Snipping Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-lightened-transition-tactics/"><u>[Updated] Lightened Transition Tactics</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-best-vhs-80s-effects-to-use-in-video-editing/"><u>2024 Approved  Best VHS 80S Effects to Use in Video Editing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-intova-edge-x-action-camera-review/"><u>2024 Approved  Intova Edge X Action Camera Review</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-messages-from-apple-iphone-15-pro-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Messages from Apple iPhone 15 Pro to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/analyzing-the-differences-between-samsungs-s10plus-and-s20-models-a-comprehensive-guide/"><u>Analyzing the Differences Between Samsung's S10+ and S20 Models: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-updater-setback-error-0x800f080a-on-windows-systems/"><u>Bypassing Updater Setback Error 0X800F080A on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cant-scroll-in-microsoft-excel-for-windows-try-these-fixes/"><u>Can't Scroll in Microsoft Excel for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/confusion-in-xbox-app-gaming-placement/"><u>Confusion in Xbox App Gaming Placement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-phone-media-saving-problems/"><u>Eliminating Windows Phone Media Saving Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-performance-skyrocketing-vram-in-win1011-systems/"><u>Enhance Performance: Skyrocketing VRAM in Win10/11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erratic-read-only-file-behavior-on-win11/"><u>Fixing Erratic Read-Only File Behavior on Win11</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-x100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo X100 | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-samsung-galaxy-s23-ultra-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Samsung Galaxy S23 Ultra Phone | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/hell-let-loose-pc-compatibility-optimized-ensuring-smooth-gaming-experience/"><u>Hell Let Loose PC Compatibility Optimized: Ensuring Smooth Gaming Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Realme 11 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-grayed-out-secure-boot-in-the-bios-on-windows/"><u>How to Fix a Grayed-Out Secure Boot in the BIOS on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-6-to-windows-10-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 6 to Windows 10? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-windows-printer-revival/"><u>Immediate Windows Printer Revival</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-xiaomi-13-ultra-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Xiaomi 13 Ultra Devices | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-leveraging-video-features-annotations-and-cards/"><u>In 2024, Leveraging Video Features  Annotations & Cards</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-multitask-views-how-to-control-picture-in-picture-on-iphones/"><u>In 2024, Mastering Multitask Views  How to Control Picture in Picture on iPhones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mend-the-minutes-windows-system-synchronized/"><u>Mend the Minutes: Windows System Synchronized</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-get-the-job-done-fast-qui/"><u>New 2024 Approved Get the Job Done Fast Qui</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-address-retrieve-settings-error-on-winx/"><u>Quick Steps to Address Retrieve Settings Error on WinX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/santas-digital-deliveries-via-microsoft-marketplace/"><u>Santa's Digital Deliveries via Microsoft Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-sharing-not-working-in-microsoft-teams-for-windows-try-these-fixes/"><u>Screen Sharing Not Working in Microsoft Teams for Windows? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-enable-photo-viewer-window/"><u>Step-by-Step: Enable Photo Viewer Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-solutions-to-fixed-windows-itunes-applications/"><u>Swift Solutions to Fixed Windows iTunes Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-avoid-dark-screen-while-playing-winos-titles/"><u>Tips to Avoid Dark Screen While Playing WINOS Titles</u></a></li>
<li><a href="https://screen-recording.techidaily.com/transform-slideshow-into-video-for-2024/"><u>Transform Slideshow Into Video for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-remedying-full-screen-troubles-in-sonic-games/"><u>Understanding and Remedying Full-Screen Troubles in Sonic Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11s-gpo-settings-quickly/"><u>Unlocking Windows 11'S GPO Settings Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-0x80072af9-failure/"><u>Unraveling the Mystery of 0X80072AF9 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-to-do-if-microsoft-outlook-only-opens-in-safe-mode-on-windows/"><u>What to Do if Microsoft Outlook Only Opens in Safe Mode on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/where-are-windows-photo-repositories/"><u>Where Are Window's Photo Repositories?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-deleted-content-8-tactics/"><u>Winning Back Your Deleted Content: 8 Tactics</u></a></li>
</ul></div>
