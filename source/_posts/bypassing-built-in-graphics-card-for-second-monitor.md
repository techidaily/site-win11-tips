---
title: Bypassing Built-In Graphics Card for Second Monitor
date: 2024-07-29T08:13:39.706Z
updated: 2024-07-30T08:13:39.706Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Built-In Graphics Card for Second Monitor
excerpt: This Article Describes Bypassing Built-In Graphics Card for Second Monitor
keywords: Bypass GPU For2Monitors,ExternalGraphicsAdapter,DualDisplaySetup,SecondScreenBypass,Non-NativeGraphics,AlternateMonitorMethod,GraphicsCardOverride
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Bypassing Built-In Graphics Card for Second Monitor

 Your Windows computer probably has integrated graphics, especially if it's a laptop. The problem with this type of GPU, which is built into the motherboard, is that it's usually less powerful than a dedicated GPU. So, if you have a dedicated GPU, which is usually more powerful, it makes sense that you might want it to take over the graphical performance of your computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check If You Have A Dedicated GPU

 Before you disable your integrated GPU (iGPU), you need to verify that your computer has a dedicated GPU installed and that it's working properly. To do that, right-click an empty part of the Taskbar and select **Task Manager**.

![Task Manager Option in the Taskbar Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Task-Manager-Option.jpg)

 In Task Manager, select the **Performance** tab on the left and look at the number of GPUs available for your PC on the right. If there is more than one, then the other one is the dedicated GPU. In our case, **GPU 1** is the dedicated GPU, and if we click on it and scroll to the bottom, we can see that it says **Dedicated GPU Memory** in the rightmost panel.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![the Performace tab of Task Manager with the dedicated GPU selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/performace-tab-of-task-manager-with-gpu-selected-1.jpg)

 After you confirm you have an extra GPU on your computer, you can disable the iGPU.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## How To Turn Off Your Windows Computer’s Integrated Graphics

 You can disable your iGPU in the Device Manager. To do that press **Win + R** to open Windows Run. Type **devmgmt.msc** in the text box and hit the **Enter** key to [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/).

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![Opening device driver with windows run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/opening-device-manager-with-run.png)

 Expand the **Display adapters** section, right-click your integrated GPU, and select **Disable device**.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![disabling an iGPU in Device Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabling-igpu-in-device-manager.jpg)

 In the prompt that appears, confirm you want to disable the iGPU by clicking on **Yes**. That should turn off the integrated graphics on your Windows computer so that the system relies on the dedicated graphics.

## Should You Turn Off Integrated Graphics?

 While dedicated GPUs tend to be more powerful than iGPUs and can boost your computer's graphical performance, that is not always the case.

 So the decision to disable your integrated graphics is dependent on whether you have stronger dedicated graphics, and if you'll be running a lot of graphics-intensive applications, such as games and design software. As we covered in our [integrated vs. dedicated GPU](https://www.makeuseof.com/tag/can-shared-graphics-finally-compete-with-a-dedicated-graphics-card/) guide, dedicated GPUs are ideal for more intense operations.

 On the other hand, if you're not running anything graphics-intensive applications, or you need to reduce power consumption on a laptop, you don't need to disable the iGPU. Also, your Windows system might support switchable graphics, which allows it to decide which GPU to use depending on the application you're running.

 However, this may cause the iGPU to bottleneck the dedicated GPU in some scenarios if they're both running applications and there aren't enough system resources to go around.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Use Your Dedicated Graphics Card When You Need It

 All in all, you're better off using your dedicated graphics card, especially if you are into graphically demanding applications. But if your computer doesn't have a dedicated GPU, disabling integrated graphics is not an option. The decision depends on what you're ultimately trying to achieve on your Windows computer.

 In this guide, we're going to show you how to disable integrated graphics on your Windows computer.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-achieve-cinematic-gaming-with-advanced-steam-recordings/"><u>[New] 2024 Approved  Achieve Cinematic Gaming with Advanced Steam Recordings</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-best-7-high-resolution-dslrs-for-engaging-video-blogs/"><u>[New] 2024 Approved  Best 7 High-Resolution DSLRs for Engaging Video Blogs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-dive-deep-into-the-world-of-creator-studio/"><u>[New] 2024 Approved  Dive Deep Into the World of Creator Studio</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-navigating-novelty-applying-cartoon-lenses-in-snapchat/"><u>[New] 2024 Approved  Navigating Novelty  Applying Cartoon Lenses in Snapchat</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-seamless-transfer-of-social-media-videos-from-twitter-to-whatsapp/"><u>[Updated] 2024 Approved  Seamless Transfer of Social Media Videos From Twitter to WhatsApp</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-streamlining-social-media-top-strategies-for-pc-livestreaming-on-tiktok/"><u>[Updated] In 2024, Streamlining Social Media  Top Strategies for PC Livestreaming on TikTok</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-navigating-the-financial-landscape-for-podcasters/"><u>[Updated] Navigating the Financial Landscape for Podcasters</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unlocking-your-videos-potential-with-smooth-narrative-flows/"><u>[Updated] Unlocking Your Videos' Potential with Smooth Narrative Flows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-vidmessenger-extractor-plus/"><u>2024 Approved  VidMessenger Extractor Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-snap-uac-dialogues/"><u>A Step-by-Step Guide to Snap UAC Dialogues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automating-power-indicators-full-charges-notify-you-in-win11/"><u>Automating Power Indicators: Full Charges Notify You in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-must-haves-alerts-windows-10-and-11-troubleshooting/"><u>Avoiding 'Must-Haves' Alerts: Windows 10 & 11 Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-web-pace-unify-phone-and-laptop-connectivity/"><u>Balancing Web Pace: Unify Phone & Laptop Connectivity</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-apple-iphone-xr-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your Apple iPhone XR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/charting-your-course-in-windows-preload-land/"><u>Charting Your Course in Windows Preload Land</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chocolatey-vs-wm-top-tools-for-windows-software-downloads/"><u>Chocolatey vs WM: Top Tools for Windows Software Downloads</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-prime-sites-to-download-your-got-favorite-tunes/"><u>Discover Prime Sites to Download Your GoT Favorite Tunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/engage-with-windows-11s-screen-snip-functionality/"><u>Engage with Windows 11'S Screen Snip Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-result-visibility-for-windows-1011s-search/"><u>Enhancing Result Visibility for Windows 10/11'S Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-silencing-the-defender-firewall-in-win11/"><u>Guide to Silencing the Defender Firewall in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-secure-your-childrens-online-world-windows-11/"><u>Guidelines to Secure Your Children’s Online World: Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-poco-c65-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Poco C65 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-improve-windows-taskmanager-through-cli-integration/"><u>How to Improve Windows TaskManager Through CLI Integration</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-benq-sw320-review-a-gateway-to-true-high-definition/"><u>In 2024, BenQ SW320 Review  A Gateway to True High Definition</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-15-pro-location-by-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 15 Pro Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nubia-red-magic-9-proplus-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Nubia Red Magic 9 Pro+ to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-your-windows-notes-prominent/"><u>Keeping Your Windows Notes Prominent</u></a></li>
<li><a href="https://win11-tips.techidaily.com/manipulating-login-retry-wait-timepost-failed-attempts/"><u>Manipulating Login Retry Wait Timepost-Failed Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-linkage-airpods-and-windows-harmony/"><u>Master the Linkage: AirPods & Windows Harmony</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-mobile-app-positions-in-windows-ui/"><u>Mastery Over Mobile App Positions in Windows UI</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/optimizing-youtube-auditory-experience-for-viewers-for-2024/"><u>Optimizing YouTube Auditory Experience for Viewers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-windows-11-licensing-expiration/"><u>Overcoming the Challenges of Windows 11 Licensing Expiration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vac-rejection-in-steam-windows-gameplay/"><u>Overcoming VAC Rejection in Steam Windows Gameplay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pro-win-workflow-selecting-the-best-productivity-tools-for-windows-11/"><u>Pro-Win Workflow: Selecting the Best Productivity Tools for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejuvenate-your-machine-windows-11s-bloatware-hack/"><u>Rejuvenate Your Machine: Windows 11'S Bloatware Hack</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-badge-indicators-on-taskbars/"><u>Restoring Badge Indicators on Taskbars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-stalled-outlook-alerts-for-new-messages/"><u>Reviving Stalled Outlook Alerts for New Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shifting-win11-to-new-subnets-easily/"><u>Shifting Win11 to New Subnets Easily</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-motorola-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Motorola Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-dealing-with-do-not-have-access-errors/"><u>Strategies for Dealing with 'Do Not Have Access' Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-resume-windows-netflix-playback/"><u>Strategies to Resume Windows Netflix Playback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sync-success-starting-windows-and-accessing-notepad-quickly/"><u>Sync Success: Starting Windows and Accessing Notepad Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-reversion-of-files-to-read-only/"><u>Tackling Win11's Reversion of Files to Read-Only</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-remedy-access-denied-on-windows/"><u>Tactics to Remedy 'Access Denied' On Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-path-to-clear-visible-notes-obsidian/"><u>The Ultimate Path to Clear, Visible Notes: Obsidian</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-budget-friendly-youtube-outro-makers/"><u>Top 6 Budget-Friendly YouTube Outro Makers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turning-the-tide-restoring-daylight-from-dark-theme/"><u>Turning the Tide: Restoring Daylight From Dark Theme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfolding-windows-11s-enigma-insights-into-the-registry/"><u>Unfolding Windows 11'S Enigma: Insights Into the Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-process-of-altering-window-11-admin-identity/"><u>Unveiling the Process of Altering Window 11 Admin Identity</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>