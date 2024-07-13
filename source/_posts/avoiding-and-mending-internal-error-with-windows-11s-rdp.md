---
title: Avoiding and Mending Internal Error with Windows 11'S RDP
date: 2024-07-12T16:47:49.252Z
updated: 2024-07-13T16:47:49.252Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoiding and Mending Internal Error with Windows 11'S RDP
excerpt: This Article Describes Avoiding and Mending Internal Error with Windows 11'S RDP
keywords: Win11RDPErrorSolution,RDPWindowsFixTips,Windows11RemoteError,InternalRDPRepairWin,MendRDPWindows11,AvoidRDPErrorsWin11,FixInternalRDPWin11
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Avoiding and Mending Internal Error with Windows 11'S RDP

 Many users utilize the Remote Desktop Connection app included with Windows to connect with remote PCs. However, some users have reported a Remote Desktop Connection error message that says, “An internal error has occurred.” Consequently, they can’t connect to remote PCs with RDC when that error occurs.

 This error means RDC’s Remote Desktop Protocol can’t establish a server connection with the remote PC selected. Does the “internal error has occurred” error message pop up when you try to connect to another computer with Remote Desktop Connection? If it does, this is how you can resolve that RDP issue in Windows 10 and 11.

## 1\. Select the "Allow Remote Connections" Setting

 First, check the basic settings required for remote connections are enabled. The**Allow the remote connection** setting needs to be enabled on the host computer (the remote one you’re trying to connect to). This is how you can select the**Allow remote connection** setting in Windows 10 and 11:

1. Click the search box or button (the magnifying glass icon) that’s on the Windows taskbar.
2. Type**advanced system settings** inside the search box.
3. Select**View advanced system settings** to bring a System Properties window.
4. Click the System Properties window’s**Remote** tab.
5. Enable remote assistance by selecting the**Allow Remote Assistance** checkbox.
6. Select the**Allow Remote connections** **to this computer** radio button if that feature is not enabled.  
![The Allow remote connections option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-tab.jpg)
7. Click**Apply** and**OK** to save the new remote connection settings.

 If you don’t see the**Allow connections only from computers** option, that probably means the Windows platform isn’t a Pro or Enterprise edition. You can only enable remote connections on host computers with Windows Pro and Enterprise. However, you can still connect to host PCs with Windows Home client PCs.

## 2\. Disable Network Layer Authentication

 There’s an **Allow connections only from computers running Remote Desktop with Network Level Authentication** setting just below the**Allow Remote connection** radio button. Selecting that option implements tighter Network Layer Authentication security for remote connections. However, some users confirm that disabling NLA by unticking that checkbox can fix the “internal error has occurred” error. So, deselect that option if you’ve got it selected.

## 3\. Start or Restart the Remote Desktop Connection Service

 Remote Desktop Services is a service needed for connecting to remote PCs. So, it could be the case you need to fix the “internal error has occurred” error because that service isn’t enabled on your PC. This is how you can start the Remote Desktop Services in Windows 11/10:

1. Open the search utility for finding files and apps in Windows 11/10.
2. Enter**Services** within Windows’ search box and select to open that app from there.
3. Double-click**Remote Desktop Services** to access some configuration settings for that service.  
![The Remote Desktop Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/services-window.jpg)
4. If disabled, select**Automatic** on the**Startup** drop-down menu for Remote Desktop Services.
5. Click**Start** (inside the properties window) to run Remote Desktop Services.  
![The Remote Desktop Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-services-service.jpg)
6. Select**Apply** to set the new service options.
7. Then you can exit the window by clicking**OK** or**X** .
8. If Remote Desktop Services is already running, you can try restarting it instead. Right-click**Remote Desktop Services** to view its context menu and select**Restart** from there.

## 4\. Select the "Reconnect if the Connection Is Dropped" Setting

 Some Remote Desktop Connection users have confirmed that selecting a**Reconnect if the connection is dropped** setting in that app can resolve this error. That simple potential resolution is certainly worth a try. You can select that**Reconnect** setting like this:

1. Start the RDC app with a method in our [how-to open Remote Desktop Connection guide](http://www.makeuseof.com/windows-11-open-remote-desktop-connection/) .
2. Click**Show Options** to view RDC’s settings.  
![The Remote Desktop Connections app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-connections.jpg)
3. Select the**Experience** tab.  
![The Experience tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/experience-tab.jpg)
4. Then select the**Reconnect if the connection is dropped** checkbox.
5. Press the**Connect** button.

## 5\. Set an Automatic DNS Server

 If you’ve set a specific DNS server on your PC, change to an automatic DNS server instead. There could be an issue with the DNS server you’ve set. You can set an automatic DNS server like this:

1. Open Run (press the**Win + R** hotkey or see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ) and enter**ncpa.cpl** in that command box.
2. Click**OK** to view the Network Connections applet.
3. Right-click the internet connection to select its**Properties** context menu option.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option-1.jpg)
4. Select**Internet Protocol Version 4** and click**Properties** .
5. Then click**Obtain DNS server automatically** radio button.  
![The Obtain DNS server radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/obtain-dns-server-option.jpg)
6. Also, click**Obtain an IP address automatically** if that option isn’t selected.
7. Select**OK** to confirm the new DNS and IP address settings.

## 6\. Enable the "Require Use of Specific Security Layer" Group Policy Setting

 Group Policy includes a**Require use of specific security layer policy** setting. Enabling an RDP security layer with that policy might fix the “internal error has occurred” error for some users. To do so, set the**Require use of specific security layer** policy setting as follows:

1. Open Local Group Policy Editor with a method in our guide on [how to launch gpedit.msc](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) guide. If you're using Windows Home, be sure to check out [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Next, you’ll need to double-click**Computer Configuration** \>**Administrative Templates** in the Group Policy’s sidebar.
3. Double-click**Windows Components** \>**Remote Desktop Services** \>**Remote Desktop Session Host** in the console tree.
4. Click**Security** to view its policy settings.
5. Double-click the **Require use of specific security layer for remote (RDP) connections** policy.  
![The Security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-policies.jpg)
6. Select the**Enabled** radio button for that policy.
7. Choose**RDP** in the**Security Layer** drop-down menu.  
![The Security Layer RDP option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/rdp-option.jpg)
8. Click**Apply** \>**OK** inside the**Require use of specific security layer** for remote (RDP) connections policy window.
9. Restart Windows and then open the Remote Desktop Connection app to check if that fixes the issue.

## 7\. Turn Off UDP on the Client via Group Policy

 Users have also confirmed they fixed the “internal error has occurred” issue by enabling a**Turn off UDP** **on Client** policy setting. This is how you can enable that policy setting.

1. Start Group Policy Editor and go to this policy setting location:  
`Computer Configuration\Admin Templates\Windows Components\Remote Desktop Services\Remote Desktop Connection Client`
2. Then double-click**Turn off UDP on Client** on the right side of Group Policy Editor.  
![The Security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-policies.jpg)
3. Select that policy’s**Enabled** option.  
![The Turn Off UDP On Client window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-udp-client-window.jpg)
4. Click**Apply** to set the new**Turn off UDP** on Client policy.
5. Select**OK** in the**Turn off UDP on Client** window and exit Group Policy Editor.

## 8\. Disconnect a Domain Account

 Is your PC connected with a domain (work or school) account? If so, that domain account could be causing the remote connection issue. Try disconnecting a domain account like this:

1. Press**Win + I** to open Settings.
2. Then select the**Accounts** tab or category.
3. Click**Access work or school** to view connected domain accounts.  
![Domain account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/access-work-or-school-accounts.jpg)
4. Select**Disconnect** for a domain account.
5. Press your Start menu’s**Restart** button.
6. Then try connecting to the remote computer with RDC again.

## 9\. Turn Off Any Active VPNs

 VPNs that route connections to different servers can also cause the “internal error has occurred” issue to arise. If you’re utilizing a VPN, at least try temporarily disabling it. This is how you can turn off a VPN in Settings:

1. Open the Windows Settings app to select**Network & internet** .
2. Click the**VPN** navigation option or tab.  
![The VPN navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/vpn-navigation-option.jpg)
3. Select your VPN’s**Disconnect** option.  
![Domain account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/access-work-or-school-accounts.jpg)

## Re-establish Remote PC Access on Windows

 Those potential fixes for the “internal error has occurred” issue will probably re-establish remote PC access in most cases. The issue is often caused by RDP security, network, or remote connection setting configurations that many of the above solutions will address. So, those potential resolutions are certainly worth a try.

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
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-comprehensive-guide-top-6-free-tiktok-to-mp3-tools-online/"><u>2024 Approved  Comprehensive Guide  Top 6 FREE TikTok to MP3 Tools Online</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-free-luts-for-obs-how-to-use-them-in-2024/"><u>Updated Free LUTs for OBS How to Use Them, In 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942683526-2024-approved-step-by-step-to-rotate-videos-using-obs/"><u>2024 Approved Step by Step to Rotate Videos Using OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimal-performance-kali-on-windows/"><u>Achieve Optimal Performance: Kali on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-zip-file-errors-a-win-11-remedy-plan/"><u>Overcoming Zip File Errors: A Win 11 Remedy Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-failed-retrieval-error-with-geforce-x/"><u>Quick Fixes for Failed Retrieval Error with GeForce X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realigning-windows-11-troubleshooters-for-optimal-performance/"><u>Realigning Windows 11 Troubleshooters for Optimal Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-steps-to-wipe-your-drives-partitions-in-windows/"><u>4 Easy Steps to Wipe Your Drive's Partitions in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-login-error-compatibility-issue-with-scanner/"><u>Overcoming Windows Login Error: Compatibility Issue with Scanner</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multilingual-mastery-harnessing-the-power-of-hotkey-translations-in-windows-11/"><u>Multilingual Mastery: Harnessing the Power of Hotkey Translations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-windows-proxy-settings-glitch/"><u>Quick Fix for Windows Proxy Settings Glitch</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unveiling-the-12-superior-portable-cams-for-flip-screen-use/"><u>[Updated] Unveiling the 12 Superior Portable Cams for Flip Screen Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-aligning-sticky-notes-in-w11/"><u>Mastering the Art of Aligning Sticky Notes in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-microsofts-windows-1111-shop-hurdle/"><u>Overcoming Microsoft's Windows 11/11 Shop Hurdle</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-ultimate-list-of-online-gaming-intro-designers/"><u>New 2024 Approved The Ultimate List of Online Gaming Intro Designers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-filmless-to-film-rich-digitizing-yesteryears-images-for-2024/"><u>From Filmless to Film-Rich  Digitizing Yesteryears' Images for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-unsetting-personalized-search-on-windows-11-os/"><u>Methods for Unsetting Personalized Search on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-barriers-of-error-80080300-a-guide-to-enhanced-teamwork-on-windows/"><u>Breaking Barriers of Error 80080300: A Guide to Enhanced Teamwork on Windows</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-infinix-hot-40i-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Infinix Hot 40i.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-upgrade-efficiency-over-entertainment/"><u>Windows 11 Upgrade: Efficiency Over Entertainment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-windows-11-the-exciting-features-in-feb-2023-patch/"><u>Inside Windows 11 - The Exciting Features in FEB 2023 Patch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-boot-up-a-guide-to-startup-service-management/"><u>Navigate Through Windows Boot-Up: A Guide to Startup Service Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/examining-the-prospects-why-choose-win11-over-macos/"><u>Examining the Prospects: Why Choose Win11 Over MacOS</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-innovate-and-excel-at-fb-ads-unleash-the-potential-of-no-cost-tools/"><u>[New] Innovate & Excel at FB Ads – Unleash the Potential of No-Cost Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tonal-treasures-the-ultimate-list-of-classical-download-sites/"><u>[New] Tonal Treasures  The Ultimate List of Classical Download Sites</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-be-registered-error-a-windows-photos-guide/"><u>Addressing 'Could Not Be Registered' Error: A Windows Photos Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-combine-mov-files-for-free-5-excellent-options/"><u>New In 2024, Combine MOV Files for Free 5 Excellent Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instantly-power-off-windows-11-when-not-in-use/"><u>Instantly Power Off Windows 11 When Not in Use</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-brainy-broadcasts-top-trivia-video-channels-for-the-year-2024/"><u>[Updated] Brainy Broadcasts  Top Trivia Video Channels for the Year 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-modifying-windows-files/"><u>Mastering the Art of Modifying Windows Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-user-experience-in-windows-11-notepad/"><u>Enhancing User Experience in Windows 11 Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimal-pc-protection-limiting-multiple-antiviruses/"><u>Optimal PC Protection: Limiting Multiple Antiviruses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-background-apps-in-windows-11/"><u>How to Disable Background Apps in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/1713952085614-with-the-datamoshing-effect-the-user-can-damage-the-video-clips-to-offer-a-glitch-effect-the-article-introduces-datamosh-after-effects-its-workability-in-th/"><u>With the Datamoshing Effect, the User Can Damage the Video Clips to Offer a Glitch Effect. The Article Introduces Datamosh After Effects Its Workability in the Industry for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-and-configuring-your-win11-screensavers/"><u>Crafting and Configuring Your Win11 Screensavers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-airborne-mass-movers-selecting-the-best-drones/"><u>2024 Approved  Airborne Mass Movers  Selecting the Best Drones</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-discover-the-best-insta-grid-creators-our-leading-ten-picks-for-2024/"><u>[New] Discover the Best Insta Grid Creators  Our Leading Ten Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-your-w11-browser-by-altering-startup/"><u>Personalize Your W11 Browser by Altering Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-the-uninitialized-drive-message-on-pc/"><u>Dealing with the 'Uninitialized Drive' Message on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortlessly-regain-onedrive-entry-points-in-windows/"><u>Effortlessly Regain OneDrive Entry Points in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-task-runner-error-code-0x8007000f-in-winos/"><u>Mastery over Task Runner Error Code 0X8007000f in WinOS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-design-tools-top-10-vector-graphics-making-and-editing-apps/"><u>Essential Design Tools  Top 10 Vector Graphics Making & Editing Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-revive-device-functionality-in-win11-sleep-mode/"><u>How to Revive Device Functionality in Win11 Sleep Mode?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/expertly-design-your-3d-openers-best-picks-for-2024/"><u>Expertly Design Your 3D Openers  Best Picks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-files-save-path-problem-easy-fix-guide/"><u>Windows Files' Save Path Problem: Easy Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-data-organization-optimize-your-win11-hdd/"><u>Mastering Data Organization: Optimize Your Win11 HDD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-of-user-profile-control-with-cmd/"><u>In-Depth Analysis of User Profile Control with CMD</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-boosting-views-essential-tiktok-trends-to-track/"><u>[Updated] 2024 Approved  Boosting Views  Essential #TikTok Trends to Track</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-gradual-echo-deactivation-in-audacity/"><u>2024 Approved  Exploring Gradual Echo Deactivation in Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://extra-resources.techidaily.com/logic-x-lore-guides-to-creating-crossfading-audio/"><u>Logic X Lore  Guides to Creating Crossfading Audio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-new-cycle-begins-without-maintenance-updates-to-windows-xp781/"><u>A New Cycle Begins Without Maintenance Updates to Windows XP/7/8.1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-strategies-for-overcoming-file-access-barriers-in-windows/"><u>Comprehensive Strategies for Overcoming File Access Barriers in Windows</u></a></li>
</ul></div>
