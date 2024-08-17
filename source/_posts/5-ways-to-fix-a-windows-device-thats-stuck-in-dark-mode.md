---
title: 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
date: 2024-08-16T01:10:02.025Z
updated: 2024-08-17T01:10:02.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
excerpt: This Article Describes 5 Ways to Fix a Windows Device That's Stuck in Dark Mode
keywords: Dark Modes Troubleshoot,Windows Dark Mode Fixes,Resolve Dark Mode Error,Restart Dark Mode Issue,Turn Off Windows Dark Mode,Revert to Light Theme,Fix Stuck Dark Mode Device
thumbnail: https://thmb.techidaily.com/b92970fb02a09749baa6f2838ddd89dd174bd2bb3f33370dc3c96100a7eda776.jpg
---

## 5 Ways to Fix a Windows Device That's Stuck in Dark Mode

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-ultimate-guide-zero-cost-seminar-capture/"><u>[New] 2024 Approved  The Ultimate Guide  Zero-Cost Seminar Capture</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-flair-filled-images-top-10-screenshot-sticker-addons-on-iphonesandroids/"><u>[New] Flair-Filled Images – Top 10 Screenshot Sticker Addons on iPhones/Androids</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-6-cost-free-closers-for-your-youtube-video/"><u>[New] In 2024, 6 Cost-Free Closers for Your YouTube Video</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-effortlessly-fast-forward-focus-in-video-content/"><u>[New] In 2024, Effortlessly Fast-Forward Focus in Video Content</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-pixel-perfection-top-tools-for-preserving-tweets-videos/"><u>[Updated] 2024 Approved  Pixel Perfection  Top Tools for Preserving Tweets' Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-blueprint-to-buzzing-video-success-on-insta/"><u>[Updated] 2024 Approved  The Blueprint to Buzzing Video Success on Insta</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-a-guide-to-instagram-video-brilliance-with-templates/"><u>[Updated] In 2024, A Guide to Instagram Video Brilliance with Templates</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-premier-10-battle-royale-challenges-for-2024/"><u>[Updated] Premier 10 Battle Royale Challenges for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-strategies-for-longer-use-of-gopro-power-source/"><u>[Updated] Strategies for Longer Use of GoPro Power Source</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-your-marketing-journey-begins-here-experience-the-full-spectrum-of-over-50-free-ads/"><u>[Updated] Your Marketing Journey Begins Here - Experience the Full Spectrum of Over 50 FREE Ads!</u></a></li>
<li><a href="https://buynow-help.techidaily.com/comprehensive-withings-move-smartwatch-evaluation-timeless-design-meets-modern-tech/"><u>Comprehensive Withings Move Smartwatch Evaluation – Timeless Design Meets Modern Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curbing-unnecessary-cpu-spikes-tips-and-tricks/"><u>Curbing Unnecessary CPU Spikes: Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-steams-file-lock-error-and-fixes/"><u>Deciphering Steam’s File Lock Error and Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defeat-fixed-menus-in-windows-your-ultimate-guide/"><u>Defeat Fixed Menus in Windows: Your Ultimate Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-enhanced-ui-in-windows-11/"><u>Discovering Enhanced UI in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-ais-influence-on-the-newest-windows-11-landscape/"><u>Dissecting AI's Influence on the Newest Windows 11 Landscape</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradication-of-windows-update-malfunction-error-0x80246007/"><u>Eradication of Windows Update Malfunction: Error 0X80246007</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-tackling-windows-not-found-issue/"><u>Essential Steps: Tackling Windows' Not Found Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exorcising-sound-demons-the-internal-paudio-issue-fix/"><u>Exorcising Sound Demons: The Internal PAudio Issue Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insights-from-docx-to-pdf-mastery-with-windows-11/"><u>Expert Insights: From Docx to PDF Mastery with Windows 11</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-vivo-t2-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-bypass-password-required-alert-on-windows-11/"><u>Guide to Bypass ‘Password Required’ Alert on Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-motorola-edge-40-frp-by-drfone-android/"><u>How Can We Bypass Motorola Edge 40 FRP?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-pagefilesys-affect-your-computers-performance-and-safety/"><u>How Does Pagefile.sys Affect Your Computer’s Performance & Safety?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-realme-narzo-n55-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Realme Narzo N55 Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-package-non-registration-issue-in-windows/"><u>How to Rectify Package Non-Registration Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-10/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 10</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-a-disable-iphone-11-without-itunes-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock a disable iPhone 11 without itunes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-se-2022-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-educational-journey-through-time-with-top-history-yt-channels/"><u>In 2024, Educational Journey Through Time with Top History YT Channels</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-edge-security-feature-defender-application-guard/"><u>Installing Edge Security Feature: Defender Application Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/invoke-smooth-pathways-into-windows-shares/"><u>Invoke Smooth Pathways Into Windows Shares</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-fixes-for-windows-marketplace-error-0x80073cf3/"><u>Mastering Fixes for Windows Marketplace (Error 0X80073CF3)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/mastering-skype-meetings-windowsos-x-record/"><u>Mastering Skype Meetings  Windows/OS X Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-controlling-external-hard-drive-access/"><u>Mastering the Art of Controlling External Hard Drive Access</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/than-just-watch-time-understanding-youtube-views-calculation-for-2024/"><u>More than Just Watch Time  Understanding YouTube Views Calculation for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-the-most-prevalent-chatgpt-mistakes-a-troubleshooting-guide/"><u>Navigating Through the Most Prevalent ChatGPT Mistakes – A Troubleshooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcome-the-stumbling-block-fixing-the-missing-wwinplusprint-on-pc/"><u>Overcome The Stumbling Block: Fixing the Missing WWin+Print on PC.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-try-connecting-bluetooth-failures-on-windows-11-os/"><u>Overcoming 'Try Connecting' Bluetooth Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unsteady-mouse-icon-windows-tips/"><u>Overcoming Unsteady Mouse Icon: Windows Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-realme-gt-5-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Realme GT 5 Phone Now with These Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pinpointing-valid-logins-amidst-failed-attempts-in-windows/"><u>Pinpointing Valid Logins Amidst Failed Attempts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-excessive-memory-consumption-in-antivirus-tools/"><u>Reducing Excessive Memory Consumption in Antivirus Tools</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/resolving-the-disappearance-of-shorts-thumbnails/"><u>Resolving the Disappearance of Shorts Thumbnails</u></a></li>
<li><a href="https://tech-haven.techidaily.com/snapchats-my-ai-6-insightful-benefits-that-go-far-past-being-a-simple-novelty/"><u>Snapchat's My AI: 6 Insightful Benefits That Go Far Past Being a Simple Novelty</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solutions-for-resolving-mfc42dll-file-missing-issues/"><u>Solutions for Resolving 'MFC42.dll' File Missing Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-access-errors-in-windows-a-step-by-step-guide/"><u>Solving Access Errors in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-directx-update-challenges-on-windows/"><u>Solving DirectX Update Challenges on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-odbc-interface/"><u>Step-by-Step Guide to Windows ODBC Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-qr-code-scanners-in-windows-environment/"><u>Step-by-Step: QR Code Scanners in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-network-prompts-comprehensive-steps-in-windows-os/"><u>Streamlining Network Prompts: Comprehensive Steps in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taskmasters-toolkit-best-window-based-productivity-apps-unveiled/"><u>Taskmaster's Toolkit: Best Window-Based Productivity Apps Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-characteristics-setting-ai-devices-apart/"><u>The Characteristics Setting AI Devices Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-navigating-your-way-through-netconfig/"><u>The Essential Guide to Navigating Your Way Through NetConfig</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-digital-canvases-for-your-win10-artistry/"><u>Top 7 Digital Canvases for Your Win10 Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trim-down-your-taskbar-with-windows-11-tweaks/"><u>Trim Down Your Taskbar with Windows 11 Tweaks</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-windows-10-how-to-repair-your-airpods-microphone-issues/"><u>Troubleshooting Windows 10: How to Repair Your AirPods' Microphone Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-utilizing-windows-11s-restore-procedures/"><u>Understanding and Utilizing Windows 11'S Restore Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-package-management-proficiency-wingetui-for-windows-users/"><u>Unlock Package Management Proficiency: WingetUI for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-successful-updates/"><u>Unlocking Windows 11 Successful Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unshackling-windows-11-steps-to-bypass-security-measures/"><u>Unshackling Windows 11: Steps To Bypass Security Measures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-the-past-adding-trophies-and-awards-to-classic-titles-using-retroarch/"><u>Upgrade the Past - Adding Trophies and Awards to Classic Titles Using Retroarch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vintage-vs-modern-atlasos-upgrade/"><u>Vintage VS Modern: AtlasOS Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-does-a-crossed-out-icon-mean-for-your-files/"><u>What Does a Crossed Out Icon Mean for Your Files?</u></a></li>
</ul></div>
