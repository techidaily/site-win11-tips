---
title: Troubleshoot Manual Timezone Setting in Microsoft OS
date: 2024-08-16T01:55:31.541Z
updated: 2024-08-17T01:55:31.541Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshoot Manual Timezone Setting in Microsoft OS
excerpt: This Article Describes Troubleshoot Manual Timezone Setting in Microsoft OS
keywords: Windows Timezone Fix Guide,Set Timezone MSOS,Resolve Time Zone Errors,Adjust Timezone in Windows,Correct Timezone in OS,Timezone Correction Steps,Microsoft Timezone Calibration
thumbnail: https://thmb.techidaily.com/b7ac3fecaf39cbf4ad53ade68b5607328fb5fc5fabf85fb01691cb6e94c786a0.jpg
---

## Troubleshoot Manual Timezone Setting in Microsoft OS

 Did you ever experience being in a different time zone while working on your Windows computer? You've checked Windows time settings and noticed that it's not set to your current location. Suddenly, you realize that the time zone is greyed out, and you can’t configure it automatically. What do you do next? There are several scenarios where Windows cannot automatically set the time zone, and here's how to fix them.

## 1\. Restart Your PC

 The first step when troubleshooting any Windows-related issue is to restart the computer. It seems obvious, but it often solves the problem. Rebooting flushes out cached data that could cause time zone problems. It also resets various temporary services that may prevent Windows from automatically setting the time zone.

 To restart your computer, save all your work and close any running applications. After that, open the Start menu and click **Restart**. Once your computer restarts, check if that fixes the issue.

## 2\. Turn on Location Services in the Settings

 If restarting your computer didn't fix the issue, check if location services are enabled. Location services allow Windows to automatically detect the time zone and set it accordingly.

 To verify location services, follow these steps:

1. Press **Win + I** to open the Settings window.
2. From the left navigation panel, click **Privacy & security**.
3. Under the **App permissions** section, select **Location**.
4. Make sure the **Location services** option is enabled. If it's not, switch the toggle to turn it on.  
![Enable Location Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-location-services.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->

 Now restart your computer and check if Windows can set the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Set the Windows Time Service to Automatic

 If the location services are already enabled, but Windows still can't detect the time zone, the problem may be related to the Windows Time Service. This background service keeps your system clock synchronized with time servers.

 Windows won't detect the time zone if the service is not running. To fix this issue, set Windows Time Service to Automatic.

 Here's how to do that:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **services.msc** in the text box and press **Enter**.
3. Scroll down in the Services window and locate the **Windows Time** service.
4. Right-click the service and select **Properties**.
5. In the Properties window, set the **Startup type** to **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
6. Now check the **Service status**. If it reads **Stopped**, click the **Start** button to start the service.
7. Click **Apply** and **OK** to save the changes.

 Once you've done this, restart your PC and check the time zone settings.

## 4\. Tweak the Registry Editor

 If Windows still fails to detect the time zone or the "Set time zone automatically" option is still grayed out, you may need to tweak your registry. This is a more technical solution and requires registry knowledge. If you're not good at registry editing, skip this step or ask a professional for help.

 Follow these steps to make the changes:

 Modifying the registry incorrectly may cause serious problems. Before making any changes, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/).

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **regedit** in the search bar and press **Enter**.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following directory.  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\tzautoupdate`
5. In the right pane, double-click the **Start** (DWORD) value.  
![Modify Registry to change the Set time zone automatically setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modify-registry-to-change-the-set-time-zone-automatically-setting.jpg)
6. When the Edit DWORD Value window pops up, set the Value data to **3** and click **OK**.
7. After doing this, you must change the location setting. To do this, navigate to the following key:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\CapabilityAccessManager\ConsentStore\location`  
 You can also copy and paste the path into the Registry Editor address bar. Now press Enter and this directs you to the Location key.
8. Move to the right pane and double-click the **Value** (REG\_SZ) value.  
![Edit Registry to change the location setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/edit-registry-to-change-the-location-setting.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. In the Edit String window, type **Allow** in the **Value data** field and click OK.

 After that, close the Registry Editor and restart your PC. Windows should detect the time zone automatically and set it correctly.

## 5\. Use the Group Policy Editor

 If you're comfortable with registry editing, use the Group Policy Editor instead. However, the tool is only compatible with Windows Pro and Enterprise editions. If you're not a Pro user, [activate the Group Policy for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Right-click on Start and select **Run**.
2. Type **gpedit.msc** in the text field and click **OK**. The Local Group Policy Editor window will open.
3. On the left navigation panel, browse to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Location and Sensors > Windows Location Provider`
4. Go to the right pane and double-click on **Turn off Windows Location Provider**.  
![Turn off Windows Location Provider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/turn-off-windows-location-provider.jpg)
5. In the pop-up window, check the **Not Configured** option.
6. Click **Apply** and **OK** to save the changes.

 Now close the Group Policy Editor and restart your PC. After restarts check if your Windows detects the time zone automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## 6\. Reset the Windows Time Service

 This problem may also occur if the Windows Time Service or time synchronization settings become corrupted. In that case, reset the service to its default settings and see if that helps. Here's how to do it:

1. Click on Start and type **cmd** in the search box.
2. Press **Ctrl + Shift + Enter** on your keyboard simultaneously. This opens the Command Prompt in administrator mode.
3. If the pop-up window appears, click **Yes** to grant permission.
4. In the Command Prompt window, type net **stop w32time** and press **Enter**. Running this command will stop the Windows Time Service.
5. Now, type **w32tm /unregister** in the Command Prompt window and hit **Enter**. This unregisters the service.
6. Next, type **w32tm /register** and press **Enter**. This will re-register the Windows Time Service.
7. After that, type net **start w32time** to restart the Windows Time Service.

 Once done, close the Command Prompt and restart your computer to check if it solves the problem.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Try Some Generic Windows Fixes

 There are also generic fixes you can try:

1. **Run the System File Checker tool:**[running System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) scans for corrupted system files and replaces them if necessary.
2. **Perform a Clean Boot:** If that didn't work, [try a Windows clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This determines if third-party applications interfere with Windows Time Service.
3. **Update Windows:** Finally, [update Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to ensure you have all the latest fixes and security patches.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Windows Can Now Automatically Set the Time Zone

 We hope the article helped you resolve timing issues on your Windows computer. It may occur due to missing or corrupted system files or incorrect time zone settings. Make sure to try these solutions and perform a System Restore if the problem persists.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-infusing-watermarks-in-youtube-content-for-trademarks/"><u>[New] 2024 Approved  Infusing Watermarks in YouTube Content for Trademarks</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-comparing-metaverse-to-multiplemetasa-highlighting-their-variance/"><u>[New] Comparing Metaverse to MultipleMetasa  Highlighting Their Variance</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-art-of-choosing-and-utilizing-cc-license-types/"><u>[New] The Art of Choosing and Utilizing CC License Types</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-whatsapps-voice-communication-system/"><u>[New] Understanding WhatsApp's Voice Communication System</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-chronicle-of-the-years-best-ice-artistry/"><u>[Updated] A Chronicle of the Year's Best Ice Artistry</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-augmenting-your-stardew-experience-with-seven-top-mods/"><u>[Updated] Augmenting Your Stardew Experience with Seven Top Mods</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-precision-techniques-for-high-quality-console-recordings-on-pcs/"><u>[Updated] In 2024, Precision Techniques for High-Quality Console Recordings on PCs</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-standout-soundstage-sagas-and-plots/"><u>[Updated] Standout Soundstage Sagas and Plots</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-10-no-cost-software-for-professional-capture-at-home-for-2024/"><u>[Updated] Top 10 No-Cost Software for Professional Capture at Home for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-live-your-dreams-insights-into-the-panasonic-hx-a1-cam/"><u>2024 Approved  Live Your Dreams  Insights Into the Panasonic HX-A1 Cam</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-ultimate-companion-for-a-seamless-instagram-video-journey/"><u>2024 Approved  The Ultimate Companion for a Seamless Instagram Video Journey</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-who-takes-the-crown-in-action-camera-warfare/"><u>2024 Approved  Who Takes the Crown in Action Camera Warfare?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-efficient-coding-solutions-with-microsofts-companion/"><u>Crafting Efficient Coding Solutions with Microsoft's Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-integration-of-apple-maps-on-pcs/"><u>Deciphering the Integration of Apple Maps on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-secrets-of-windows-odbc-settings-panel/"><u>Deciphering the Secrets of Windows' ODBC Settings Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-arp-cache-how-to-empty-it/"><u>Decoding Windows ARP Cache: How to Empty It?</u></a></li>
<li><a href="https://buynow-help.techidaily.com/exploring-sonys-dual-recording-features-on-hdrcx405/"><u>Exploring Sony's Dual Recording Features on HDRCX405</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-windows-11-account-settings-center/"><u>Finding Windows 11 Account Settings Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-domain-services-printer-failures-on-newest-microsoft-os/"><u>Fixing Domain Services Printer Failures on Newest Microsoft OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-zte-axon-40-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked ZTE Axon 40 Lite? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-0x8007007e-error-code/"><u>How to Fix the Windows 0X8007007E Error Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/"><u>How to Thrive in Free Championship Football Simulator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-xiaomi-redmi-note-12-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Xiaomi Redmi Note 12 5G FRP</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-poco-x6-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Poco X6 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-honored-advisors-elite-iphone-audio-experts/"><u>In 2024, Honored Advisors  Elite iPhone Audio Experts</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-from-your-iphone-7-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock from your iPhone 7 and iPad?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Lava Yuva 3? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-modern-methods-rapidly-turning-srt-into-txt-format/"><u>In 2024, Modern Methods  Rapidly Turning SRT Into TXT Format</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-professional-insights-crafting-youtube-trailers-using-filmora/"><u>In 2024, Professional Insights  Crafting YouTube Trailers Using Filmora</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-top-10-platforms-revolutionizing-how-you-discover-youtube-keywords/"><u>In 2024, Top 10 Platforms Revolutionizing How You Discover YouTube Keywords</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-hp-zbook-firefly-15-g8-assessment-the-epitome-of-portable-power/"><u>In-Depth HP ZBook Firefly 15 G8 Assessment: The Epitome of Portable Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-auto-lock-and-screensaver-configurations/"><u>Mastering Auto-Lock & Screensaver Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-double-click-3-essential-tips/"><u>Mastering Mouse Double-Click: 3 Essential Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-disrupted-windows-thx-spatial-sound/"><u>Mending Disrupted Windows THX Spatial Sound</u></a></li>
<li><a href="https://driver-download.techidaily.com/microsofts-latest-bluetooth-drivers-compatible-with-windows-10-11-8-and-7-download-update-now/"><u>Microsoft's Latest Bluetooth Drivers: Compatible with Windows 10, 11, 8 & 7 – Download Update Now!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-7-steps-to-mend-obs-server-link-error-in-windows/"><u>Navigating 7 Steps to Mend OBS Server Link Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepads-dark-shift-windows-11-guide/"><u>Notepad's Dark Shift: Windows 11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-pc-boost-unearthing-windows-best-eight-restart-strategies/"><u>Quick PC Boost: Unearthing Windows' Best Eight Restart Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-steam-for-seamless-gameplay-on-windows-11-devices/"><u>Realigning Steam for Seamless Gameplay on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-roots-user-permissions-back-to-basics-in-win11/"><u>Restoring Roots: User Permissions Back to Basics in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-your-pc-restarting-windows-11-apps/"><u>Reviving Your PC: Restarting Windows 11 Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipgear-gone-wrong-nine-effective-tips-to-get-it-running-again/"><u>SnipGear Gone Wrong? Nine Effective Tips to Get It Running Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-inactive-windows-file-alignment-service/"><u>Solutions for Inactive Windows File Alignment Service</u></a></li>
<li><a href="https://os-tips.techidaily.com/step-by-step-guide-activating-dual-authentication-on-your-apple-id/"><u>Step-by-Step Guide: Activating Dual-Authentication on Your Apple ID</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-failed-updates-error-0x800f0845/"><u>Steps to Fix Failed Updates - Error 0X800f0845</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategic-service-management-for-optimized-windows-11/"><u>Strategic Service Management for Optimized Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-on-or-off-windows-digital-protection-filter/"><u>Switching on or Off Windows' Digital Protection Filter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-aural-anomaly-fixing-audacity-writes-on-wos/"><u>Tackling the Aural Anomaly: Fixing Audacity' Writes on WOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-financial-frontier-acquiring-high-value-youtubes-for-2024/"><u>The Financial Frontier  Acquiring High-Value Youtubes for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-removing-virtualization-support-on-win11/"><u>Tips for Removing Virtualization Support on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-win-microphone-functionality/"><u>Troubleshoot Win Microphone Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/universal-font-collection-windows-installation-steps/"><u>Universal Font Collection: Windows Installation Steps</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-power-of-the-garmin-venu-your-constant-partner-in-personal-well-being-and-activity-management/"><u>Unveiling the Power of the Garmin Venu: Your Constant Partner in Personal Well-Being & Activity Management</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-2024-approved-best-10-emoji-makers-to-create-your-own-emojis-pconlineandroidiphone/"><u>Updated 2024 Approved Best 10 Emoji Makers to Create Your Own Emojis PC/Online/Android/iPhone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-keyboard-command-center-mastery-of-shortcuts-for-fixed-paste-tasks/"><u>Win11's Keyboard Command Center: Mastery of Shortcuts for Fixed Paste Tasks</u></a></li>
</ul></div>
