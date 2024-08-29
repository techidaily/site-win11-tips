---
title: Troubleshooting Windows Bar Icon Failures
date: 2024-08-28T01:19:37.625Z
updated: 2024-08-29T01:19:37.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows Bar Icon Failures
excerpt: This Article Describes Troubleshooting Windows Bar Icon Failures
keywords: Win Fix Bar Issues,Icon Error Resolution,Windows Icon Trouble,Solve PC Bar Glitch,Rectify Icon Malfunction,Fix System Bar Failure,Unblock Windows Icon
thumbnail: https://thmb.techidaily.com/65e89fa5592e17a634309edf6fa4b1c7a4776f7c9bc581c108157d66f219235d.jpg
---

## Troubleshooting Windows Bar Icon Failures

 Taskbar thumbnail previews usually enable you to see an app window’s content without maximizing it. However, some Windows 11/10 users have posted on help forums about thumbnail previews not working. When taskbar thumbnail previews aren’t working, they don’t appear when users hover their cursors over minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

## 1\. Restart File Explorer’s Process

 The File Explorer process handles the taskbar and many other Windows UI elements. So, restarting that process is a good place to start with troubleshooting this taskbar thumbnail preview issue. Doing so can address File Explorer glitches that could be causing the issue.

 You can restart File Explorer on the **Processes** tab inside Task Manager. Right-click the Windows Explorer process there and select **Restart**. Check out this guide to [restarting File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for further instructions if needed.

![The Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restart-button.jpg)

## 2\. Repair System Files

 It’s usually recommended to try repairing system files whenever a Windows function isn’t working right. In this case, taskbar window previews aren’t working correctly. Running a System File Checker scan might repair corrupted system files causing this issue. Our [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide provides guidelines for utilizing the SFC command-line tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow.jpg)

## 3\. Edit the Taskband and Advanced Registry Keys

 Editing the Taskbar registry key is a widely confirmed solution for fixing taskbar thumbnail previews not working. This potential resolution will fix the **NumThumbnails** DWORD in that key, which might be deleted or incorrectly set. That DWORD sets the maximum number of taskbar thumbnail previews for a single minimized window. This is how you should edit the **Taskband** registry key:

1. Click the magnifying glass or file finder text box on the Windows 11/10 taskbar and input a **regedit** search term.
2. Select the **Registry Editor** search result to access that utility.
3. Go to the **Taskbar** key by inputting this location in the registry address bar:  
`Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Taskband`
4. If you can’t see a **NumThumbnails** DWORD, right-click the **Taskbar** key in Registry Editor’s sidebar and select **New** \> **DWORD**.  
![The New > DWORD option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-dword-options.jpg)
5. Enter **NumThumbnails** inside the DWORD name text box.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
6. Double-click the **NumThumbnails** DWORD.  
![The NumThumbnails DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/numthumbnails-dword.jpg)
7. If that **DWORD** is set at **0**, erase that number and input **10** in the **Value** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/edit-dword-window3.jpg)
8. Click **OK** to set the new **NumThumbnails** value.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
9. Restart Windows 11/10 (or restart File Explorer) for this registry tweak to take effect.

 You might also need to delete a **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** registry key to fix taskbar thumbnail previews not working. To do so, right-click the **DisablePreviewWindow** or **DisablePreviewDesktop** DWORD in the **Advanced** key and select **Delete** \> **Yes**. The registry location of the **Advanced** key is:

`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable the Turn Off Taskbar Thumbnails Policy Setting

 Group Policy Editor includes a policy setting for disabling taskbar thumbnail policies. If you’re a Windows 11/10 Pro or Enterprise user, check that policy to make sure it’s not set to disable taskbar thumbnail previews. You can disable the **Turn off taskbar thumbnails** policy as follows:

1. [Open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window by pressing the **Windows key + R** keyboard shortcut, inputting **gpedit.msc**, and selecting Run’s **OK** option.
2. Double-click **User Configuration** \> **Administrative Templates** \> **Start menu and taskbar** in the navigation sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/local-group-policy-editor.jpg)
3. Next, double-click **Turn off taskbar thumbnails** to access configuration options for that policy.
4. Click the **Disabled** or **Not Configured** option.  
![The Turn off taskbar thumbnail window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-taskbar-window.jpg)
5. Select **Apply** \> **OK** to disable the **Turn off taskbar thumbnails** policy as configured.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

## 5\. Roll Windows Back With a System Restoration Point

 If you have System Restore enabled, that could be a useful troubleshooting tool for fixing taskbar thumbnail previews not working. Restoring Windows to a date when your taskbar window previews worked might undo background changes that caused the issue. However, this will only work if you can select a suitable restore point that predates the issue.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can roll back Windows by following the instructions in this guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/). Applying this potential solution will remove software packages installed after the date of the selected restore point. This will mean some reinstallation of software will probably be necessary after rolling back Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Get Your Taskbar Thumbnail Previews Fixed

 Taskbar thumbnail previews may not be the most essential feature, but many users will undoubtedly miss them when they’re not working. Applying the troubleshooting methods in this guide will usually get the Windows 11/10 taskbar thumbnails working again in most cases. So, give them a try if you can’t view taskbar thumbnail previews for minimized windows.

 This issue often arises when users have multiple windows open for apps. Consequently, users only see text labels for minimized window titles. Does a similar thing happen when you try to view taskbar previews? If so, this is how you can fix taskbar thumbnail previews not working on Windows 11/10 PCs.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-expert-tips-for-adding-audio-to-your-tiktok-creations/"><u>[New] 2024 Approved  Expert Tips for Adding Audio to Your TikTok Creations</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-steps-to-resolve-stuck-obs-camera-feed-for-2024/"><u>[New] Steps to Resolve Stuck OBS Camera Feed for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-streamlining-the-recording-process-in-virtual-gatherings/"><u>[Updated] 2024 Approved  Streamlining the Recording Process in Virtual Gatherings</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-superior-nintendo-switch-hd-recording/"><u>[Updated] 2024 Approved  Superior Nintendo Switch HD Recording</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-expert-insights-choosing-the-best-platforms-for-watching-cricket-live-for-2024/"><u>[Updated] Expert Insights  Choosing the Best Platforms for Watching Cricket LIVE for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-from-casual-to-pro-unpacking-kinemaster-for-android-gamers/"><u>[Updated] From Casual to Pro  Unpacking KineMaster for Android Gamers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-zero-to-hero-crafting-an-authoritative-online-self/"><u>[Updated] In 2024, From Zero to Hero  Crafting an Authoritative Online Self</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-optimal-mac-animation-storer-for-2024/"><u>[Updated] Optimal Mac Animation Storer for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unwrap-these-8-trending-gems-from-youtubes-big-brother-for-2024/"><u>[Updated] Unwrap These 8 Trending Gems From YouTube's Big Brother for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-optimizing-your-podcasts-itunes-placement/"><u>2024 Approved  Optimizing Your Podcast's iTunes Placement</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streamline-your-viewing-experience-how-to-use-floating-window-on-netflix/"><u>2024 Approved  Streamline Your Viewing Experience  How To Use Floating Window on Netflix</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-the-power-of-nikon-d7500/"><u>2024 Approved  Unveiling the Power of Nikon D7500</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-innovation-new-pcs-best-tools-from-msistore/"><u>Accelerated Innovation: New PC's Best Tools From MSIStore</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beyond-imagination-vr-powered-movies/"><u>Beyond Imagination  VR-Powered Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-confusing-blue-screen-issue-error-0x8007007e/"><u>Clearing Up Confusing Blue Screen Issue: Error 0X8007007E</u></a></li>
<li><a href="https://some-guidance.techidaily.com/cookiebot-propulsion-harnessing-next-gen-tech-for-superior-seo-solutions/"><u>Cookiebot Propulsion: Harnessing Next-Gen Tech for Superior SEO Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantle-the-defenses-taking-out-secure-qandas-from-win-11/"><u>Dismantle the Defenses: Taking Out Secure Q&As From Win 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-enhance-the-ultimate-synaptics-touchpad-driver-setup/"><u>Download & Enhance: The Ultimate Synaptics Touchpad Driver Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-workspace-attach-gmail-icon-to-your-windows-edge/"><u>Efficient Workspace: Attach Gmail Icon to Your Window's Edge</u></a></li>
<li><a href="https://win-solutions.techidaily.com/enhancing-stability-solutions-for-continuous-play-of-fall-guys-on-personal-computers/"><u>Enhancing Stability: Solutions for Continuous Play of Fall Guys on Personal Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-the-performance-of-discord-searches-on-windows/"><u>Enhancing the Performance of Discord Searches on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhancing-visual-quests-hunt-for-pristine-pexels-images/"><u>Enhancing Visual Quests  Hunt for Pristine Pexels Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11-with-android-tablet-multi-display/"><u>Enhancing Windows 11 with Android Tablet Multi-Display</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-toms-hardware-a-comprehensive-review/"><u>Exploring Tom's Hardware: A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-group-policies-for-single-accounts-in-latest-windows-versions/"><u>Fine-Tuning Group Policies for Single Accounts in Latest Windows Versions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-your-inkpad-on-windows-a-step-by-step-tutorial/"><u>Fix Your Inkpad on Windows: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-maintain-your-powertoys-setup-during-system-upgrade/"><u>Guide to Maintain Your PowerToys Setup During System Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-error-0x887a0006-on-graphics-issues/"><u>Guide to Rectify Error 0X887A0006 on Graphics Issues</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-google-frp-lock-on-samsung-galaxy-s23-ultra-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Samsung Galaxy S23 Ultra Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-counteract-failed-imports-of-iphone-photos-in-windows-os/"><u>How To Counteract Failed Imports of iPhone Photos in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-active-directory-domain-services-printer-failures-in-win-1011/"><u>How to Tackle Active Directory Domain Services Printer Failures in WIN 10/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-strategies-for-tackling-directdraw-glitches-on-windows-1011/"><u>Key Strategies for Tackling DirectDraw Glitches on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-audio-cds-mp3-conversion-with-imgburn-for-windows-users/"><u>Mastering Audio CDs: MP3 Conversion with ImgBurn for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-10-for-reliable-clipboard-use/"><u>Optimizing Windows 10 for Reliable Clipboard Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-and-easy-qr-code-scanning-on-windows-pcs/"><u>Quick & Easy: QR Code Scanning on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cures-9-ways-to-stop-windows-setup-from-hanging-at-verify/"><u>Quick Cures: 9 Ways To Stop Windows Setup From Hanging at Verify</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-win-tips-for-windows-file-order-max-156/"><u>Quick Win Tips for Windows File Order (Max 156)</u></a></li>
<li><a href="https://common-error.techidaily.com/rapid-chargers-guide-overcoming-non-charging-laptop-batteries/"><u>Rapid Charger's Guide: Overcoming Non-Charging Laptop Batteries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-your-cortana-experience-with-data-export/"><u>Reclaim Your Cortana Experience with Data Export</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-no-built-in-application-for-this-file-in-windows/"><u>Resolving No Built-In Application for This File in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-tab-continuity/"><u>Restoring Seamless Tab Continuity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/revive-your-windows-10-screens-touch-sensitivity-with-these-5-proven-strategies/"><u>Revive Your Windows 10 Screen's Touch Sensitivity with These 5 Proven Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/screen-stickers-top-8-notebook-apps-for-pc/"><u>Screen Stickers: Top 8 Notebook Apps for PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-synergy-controlling-galaxy-via-windows-11-dex/"><u>Seamless Synergy: Controlling Galaxy via Windows 11 DeX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-utorrent-file-transfers-for-windows-users/"><u>Speedy uTorrent File Transfers for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-mend-chromes-sudden-shutdown-on-pc/"><u>Steps to Mend Chrome’s Sudden Shutdown on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-and-modernizing-clipboard-memory-usage-in-windows-11/"><u>Streamlining and Modernizing Clipboard Memory Usage in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-data-exchange-between-dual-windows-using-aoemi/"><u>Streamlining Data Exchange Between Dual Windows Using AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-and-11-glitch-geforce-experience-error/"><u>Tackling Windows 11 & 11 Glitch: GeForce Experience Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-downtines-for-your-w11-gadgets-automated-shutdown-style/"><u>Tailored Downtines for Your W11 Gadgets, Automated Shutdown Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-route-for-entering-your-appshub-on-windows-11/"><u>The Ultimate Route for Entering Your AppsHub on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-7-decisions-your-roadmap-to-the-right-windows-device/"><u>Top 7 Decisions: Your Roadmap to the Right Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-strategies-when-windows-firewall-holds-steady/"><u>Top Strategies When Windows Firewall Holds Steady</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-unnoticed-windows-11-advantages-for-savvy-users/"><u>Top Unnoticed Windows 11 Advantages for Savvy Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-fortification-7-measures-against-illicit-entry/"><u>Windows Fortification: 7 Measures Against Illicit Entry</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>