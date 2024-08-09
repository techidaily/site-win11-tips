---
title: "Mastering Windows Power Menus: Suppress Dim Screen"
date: 2024-08-08T11:10:18.793Z
updated: 2024-08-09T11:10:18.793Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows Power Menus: Suppress Dim Screen"
excerpt: "This Article Describes Mastering Windows Power Menus: Suppress Dim Screen"
keywords: WinPowerSuppressScreen,DimScreenControlWin,MasterPowerMenuQuit,ScreenDimSuppressWin,PowerMenuScreenTweak,WindowsAdjustmentTool,ReduceDimmedDisplay
thumbnail: https://thmb.techidaily.com/c40243a18120050792e9b2a35c08e8c187a7242ae42c21363a9149298cc2eac3.jpg
---

## Mastering Windows Power Menus: Suppress Dim Screen

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-affluent-streaming-stars/"><u>[New] 2024 Approved  Affluent Streaming Stars</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-from-live-to-recorded-using-obs-for-games/"><u>[New] 2024 Approved  From Live to Recorded  Using OBS for Games</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-the-essential-guide-to-tracking-igtv-viewership-metrics/"><u>[New] 2024 Approved  The Essential Guide to Tracking IGTV Viewership Metrics</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-brightening-up-your-videography-gopro-fog-free-techniques-for-2024/"><u>[New] Brightening Up Your Videography  GoPro Fog-Free Techniques for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-illuminating-photography-with-dynamic-mosaic-creations/"><u>[New] Illuminating Photography with Dynamic Mosaic Creations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unlock-the-potential-of-your-feed-with-mass-photo-and-video-posting/"><u>[New] In 2024, Unlock the Potential of Your Feed with Mass Photo & Video Posting</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-brilliant-hd-broadcasts-optimizing-videos-on-fb/"><u>[Updated] 2024 Approved  Brilliant HD Broadcasts  Optimizing Videos on FB</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-best-twitter-video-downloaders-how-to-save-twitter-videos/"><u>[Updated] In 2024, Best Twitter Video Downloaders  How to Save Twitter Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-film-for-a-friendly-facebook-feature/"><u>2024 Approved  Film for a Friendly Facebook Feature</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-unleashing-creative-potential-with-pixiz-for-photo-videos/"><u>2024 Approved  Unleashing Creative Potential with Pixiz for Photo Videos</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-xiaomi-redmi-note-13-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Xiaomi Redmi Note 13 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/6-innovative-uses-of-chatgpt-for-enhancing-creative-writing-skills/"><u>6 Innovative Uses of ChatGPT for Enhancing Creative Writing Skills</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/best-top-timelapses-quick-capture-and-edit/"><u>Best Top Timelapses  Quick Capture & Edit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bf-price-war-save-612-on-endless-win10-lifetime-life/"><u>BF Price War: Save $6.12 on Endless Win10 Lifetime Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-infinix-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Infinix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://hardware-help.techidaily.com/gtx-1660-graphics-driver-update-guide-fast-and-simple-steps/"><u>GTX 1660 Graphics Driver Update Guide: Fast & Simple Steps</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-data-from-apple-iphone-11-pro-max-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How To Transfer Data from Apple iPhone 11 Pro Max to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-xiaomi-redmi-a2plus-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Xiaomi Redmi A2+ Phone Now with These Tips</u></a></li>
<li><a href="https://extra-tips.techidaily.com/master-the-craft-powerdirector-2024-complete-guide-and-reviews/"><u>Master the Craft  PowerDirector 2024 Complete Guide & Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-system-with-a-fresh-net-framework-max-156/"><u>Reconciling System with a Fresh .NET Framework (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-steam-network-error-in-windows-11-systems/"><u>Remedying Steam Network Error in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-page-load-failure-on-microsoft-store-windows-app/"><u>Resolving 'Page Load Failure' On Microsoft Store Windows App</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-correct-win10-screen-size/"><u>Restoring Correct Win10 Screen Size</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-gmaps-windows-pc-guide/"><u>Setting Up GMaps: Windows PC Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-screen-splitting-problems-in-win-10/"><u>Solutions for Screen Splitting Problems in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-fixing-windows-11-help-menu-failure/"><u>Steps for Fixing Windows 11 Help Menu Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stops-repeated-edge-icons-on-workspace/"><u>Stops Repeated Edge Icons on Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-c0000005-failure-on-windows-108/"><u>Tackling C0000005 Failure on Windows 10/8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-path-failure-on-pc-operating-systems/"><u>Tackling PATH Failure on PC Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-winning-playbook-strategies-to-eliminate-stutter-in-videos/"><u>The Winning Playbook: Strategies to Eliminate Stutter in Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-synapse-unidentified-razer-peripherals-on-win-11/"><u>Troubleshooting Synapse: Unidentified Razer Peripherals on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vscode-instability-in-windows-11/"><u>Troubleshooting VSCode Instability in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-hp-printer-writes-error-oxc4eb827f/"><u>Unraveling HP Printer' Writes Error OXC4EB827F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-windows-settings-dim-display/"><u>Unveiling the Secrets of Windows Settings: 'Dim Display'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-end-task-control-for-window-management/"><u>Utilizing End Task Control for Window Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
</ul></div>
