---
title: "Resetting Windows Firewall: Essential Tips"
date: 2024-09-11T01:21:36.680Z
updated: 2024-09-12T01:21:36.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resetting Windows Firewall: Essential Tips"
excerpt: "This Article Describes Resetting Windows Firewall: Essential Tips"
keywords: Reset Windows Firewall,Firewall Tips,Safeguard System,Security Reset,Safe Firewall Settings,Network Protection,Optimize Firewall
thumbnail: https://thmb.techidaily.com/e46847f4d730c4e71d01b69ffbbf4867ec32380919d66b5ed5af5b5df6bd28ce.jpg
---

## Resetting Windows Firewall: Essential Tips

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.





<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://facebook-video-content.techidaily.com/new-enhance-teamwork-and-efficiency-8-must-have-task-apps/"><u>[New] Enhance Teamwork & Efficiency 8 Must-Have Task Apps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-exploring-social-boundaries-sign-up-for-a-facebook-profile-for-2024/"><u>[New] Exploring Social Boundaries Sign Up for a Facebook Profile for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-free-videography-starter-pack-openers-and-more/"><u>[New] Free Videography Starter Pack Openers & More</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-how-to-make-looping-videos-for-instagram-in-2024/"><u>[New] How To Make Looping Videos for Instagram, In 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-buzz-factor-creating-catch-all-content-for-facebook/"><u>[New] The Buzz Factor Creating Catch-All Content for Facebook</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-best-ways-to-captivate-an-audience-on-snapchat/"><u>[Updated] 2024 Approved The Best Ways to Captivate an Audience on Snapchat</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-optimal-recorders-top-10-tools-for-webinars/"><u>[Updated] Optimal Recorders Top 10 Tools for Webinars</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-create-a-youtube-music-playlist-on-web-and-mobile-a-detailed-guidance/"><u>2024 Approved Create a YouTube Music Playlist on Web and Mobile - A Detailed Guidance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/digital-detectives-how-to-legally-track-down-a-persons-phone-number-online/"><u>Digital Detectives: How to Legally Track Down a Person’s Phone Number Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatching-win11-camera-troubles-with-error-code-a00f4289/"><u>Dispatching Win11 Camera Troubles with Error Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-the-red-x-meaning-in-file-organization/"><u>Dissecting the Red “X” Meaning in File Organization</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-samsung-ssd-960-evo-drives-updates-and-software-support-on-windows/"><u>Download & Install Samsung SSD 960 EVO Drives: Updates & Software Support on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-chrome-interruptions-in-windows-os/"><u>Eliminating Chrome Interruptions in Windows OS</u></a></li>
<li><a href="https://win-blog.techidaily.com/enhance-performance-overcome-lagging-and-increase-fps-for-a-smooth-rdr2-gameplay/"><u>Enhance Performance: Overcome Lagging and Increase FPS for a Smooth RDR2 Gameplay</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/evaluating-the-thermopro-tp67-economical-yet-flawed-performance/"><u>Evaluating the ThermoPro TP67 - Economical Yet Flawed Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-creative-wallpapers-for-each-windows-11-monitor/"><u>Explore Creative Wallpapers for Each Windows 11 Monitor</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fix-praey-for-the-gods-stability-issues-and-persistent-crashes-on-windows/"><u>Fix Praey for the Gods Stability Issues & Persistent Crashes on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-required-parts-not-found-error-in-win11/"><u>Guide to Fix Required Parts Not Found Error in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-reset-account-lockout-counter-after-failed-logon-attempts-in-windows-10-and-11/"><u>How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-modify-file-permissions-in-windows/"><u>How to Modify File Permissions in Windows</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-se-2020-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Data from Apple iPhone SE (2020) to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Poco Phone with Broken Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-system-limits-on-pc/"><u>Identifying System Limits on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-fixes-to-stranded-error-on-windows-1011-xbox-app/"><u>Immediate Fixes to 'Stranded' Error on Windows 10/11 Xbox App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-efficient-data-management-techniques/"><u>Implementing Efficient Data Management Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-frequent-wallpaper-alterations-in-windows/"><u>Implementing Frequent Wallpaper Alterations in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-notification-for-full-batteries-on-windows/"><u>Improve Notification for Full Batteries on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-facebook-today-unpacking-the-recent-updates/"><u>In 2024, Facebook Today Unpacking the Recent Updates</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-masterclass-reclaiming-personal-eyes-only-images/"><u>In 2024, Masterclass Reclaiming Personal Eyes-Only Images</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-xiaomi-civi-3-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Xiaomi Civi 3 to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-pcs-performance-spectrum/"><u>In-Depth Analysis of PC's Performance Spectrum</u></a></li>
<li><a href="https://driver-download.techidaily.com/logitech-enhances-gamer-experience-check-out-the-new-extreme-3d-pro-mouse-software-version/"><u>Logitech Enhances Gamer Experience - Check Out the New Extreme 3D Pro Mouse Software Version!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/making-the-most-of-windows-outlook-a-calendar-customization-tutorial/"><u>Making the Most of Windows Outlook - A Calendar Customization Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-installation-package-openness-in-ws11ws10-environments/"><u>Mastering Installation Package Openness in WS11/WS10 Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-handling-breakpoint-error-in-windows/"><u>Mastering the Art of Handling 'Breakpoint Error' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-fix-excel-notation-on-windows-notepad/"><u>Methods to Fix Excel Notation on Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-camera-app-glitch-a00f425d/"><u>Overcoming Windows Camera App Glitch: A00F425D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pivot-point-shifting-your-onedrive-save-destination-on-pc/"><u>Pivot Point: Shifting Your OneDrive Save Destination on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-fading-frames-enhancing-vlc-performance/"><u>Quick Fix for Fading Frames: Enhancing VLC Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-for-wi-fi-management-in-win-11/"><u>Quick Tips for Wi-Fi Management in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivate-dormant-slack-notifications-a-quick-fix-guide-for-win-11/"><u>Reactivate Dormant Slack Notifications: A Quick Fix Guide for Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-the-issue-of-one-channel-playback-with-windows-bluetooth/"><u>Rectifying the Issue of One-Channel Playback with Windows Bluetooth</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-display-driver-anomalies-of-r9-gpu-in-windows-10/"><u>Resolved Display Driver Anomalies of R9 GPU in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-non-appearing-windows-11-sign-ins/"><u>Resolving Non-Appearing Windows 11 Sign-Ins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketch-it-up-your-ultimate-guide-to-the-best-drawing-software-on-win10/"><u>Sketch It Up: Your Ultimate Guide to the Best Drawing Software on Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-save-malfunction-resolve-it-with-ease/"><u>Snip-and-Save Malfunction? Resolve It with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-11s-microsoft-store-error-0x80073cf3/"><u>Solving Windows 11'S Microsoft Store Error 0X80073cf3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-tackle-xbox-game-pass-failures-in-windows/"><u>Strategies to Tackle Xbox Game Pass Failures in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-experience-with-emoji-15-in-windows-11/"><u>Streamline Your Experience with Emoji 15 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthen-your-gpu-ranked-1-6-tools-for-windows-users/"><u>Strengthen Your GPU: Ranked #1-#6 Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-ready-your-pc-with-these-startup-speedups-on-win11/"><u>Swiftly Ready Your PC with These Startup Speedups on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-halting-automatic-bios-entry-after-reboot/"><u>Techniques for Halting Automatic BIOS Entry After Reboot</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-htc-u23-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to HTC U23 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-downloads-for-a-smoother-valorant-experience/"><u>Turbocharge Windows Downloads for a Smoother Valorant Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-everyday-scenes-to-dynamic-windows-wallpaper/"><u>Turn Everyday Scenes to Dynamic Windows Wallpaper</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unlocking-potential-your-guide-to-effective-improvements/"><u>Unlocking Potential Your Guide to Effective Improvements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-printer-networking-hurdles-in-windows/"><u>Unraveling Printer Networking Hurdles in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-fix-eradicating-the-0x80246007-update-hurdle/"><u>Win11 Fix: Eradicating the 0X80246007 Update Hurdle</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-display-issue-no-more/"><u>Windows 11 Display Issue No More</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-stop-default-search-menu-activation/"><u>Windows 11: Stop Default Search Menu Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-file-fixes-erase-temp-files-effortlessly/"><u>Windows File Fixes: Erase Temp Files Effortlessly</u></a></li>
</ul></div>




