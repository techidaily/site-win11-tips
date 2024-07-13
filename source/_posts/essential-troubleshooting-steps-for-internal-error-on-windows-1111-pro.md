---
title: Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro
date: 2024-07-12T16:41:40.640Z
updated: 2024-07-13T16:41:40.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro
excerpt: This Article Describes Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro
keywords: Windows Error Fix Guide,Win11 Troubleshooting,Error Handling W11,System Error Solutions,Win11 Error Steps,PC Crash Resolution,Internal Error Diagnosis
thumbnail: https://thmb.techidaily.com/bd8185a9d59d7e33d1cc856ce7e147e5a0c37bc7679792239ca349164c0b304f.jpg
---

## Essential Troubleshooting Steps for Internal Error on Windows 11/11 Pro

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
<li><a href="https://extra-resources.techidaily.com/new-comparing-digital-universes-meta-to-omni/"><u>[New] Comparing Digital Universes  Meta to Omni</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11-blue-screen-recovery-steps/"><u>Mastering Windows 11 Blue Screen Recovery Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-nvidia-control-panel-access-denied-error-in-windows-1110/"><u>How to Fix the NVIDIA Control Panel “Access Denied” Error in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-proxy-detection-corrections/"><u>Mastering Windows Proxy Detection Corrections</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-new-developments-in-facebook-2023-edition/"><u>[Updated] 2024 Approved  New Developments in Facebook - 2023 Edition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-tips-reversed-color-effects-in-pictures/"><u>2024 Approved  Expert Tips  Reversed Color Effects in Pictures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-depths-of-wacatacbml-signature-and-defense-for-windows-users/"><u>Exploring the Depths of Wacatac.B!ml: Signature & Defense for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-post-blue-screen-events-on-windows-7/"><u>Investigating Post-Blue Screen Events on Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-error-code-0xc0000005-on-windows-pc/"><u>How to Fix the Error Code 0Xc0000005 on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-iphone-photo-import-errors-on-computers/"><u>How to Handle iPhone Photo Import Errors on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-store-sign-in-troubles-solutions-await/"><u>Microsoft Store Sign-In Troubles? Solutions Await</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-11-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 11 & 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-boost-your-content-20-premium-tiktok-caption-strategies-for-2024/"><u>[New] Boost Your Content  20 Premium TikTok Caption Strategies for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/from-blurry-edges-to-squared-perfection-the-imovie-guide-for-instagram-videos-for-2024/"><u>From Blurry Edges to Squared Perfection  The iMovie Guide for Instagram Videos for 2024</u></a></li>
<li><a href="https://techidaily.com/solved-bad-and-corrupt-videos-that-wont-play-on-m6-5g-by-stellar-video-repair-mobile-video-repair/"><u>Solved  Bad and Corrupt Videos that won't Play on M6 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-lost-downloads-in-chrome-on-your-windows-pc/"><u>How to Recover Lost Downloads in Chrome, on Your Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fundamentals-of-window-glass-idleness-exploration/"><u>Fundamentals of Window Glass Idleness Exploration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-audacity-error-code-9999-in-windows-1110/"><u>How to Fix the Audacity Error Code 9999 in Windows 11/10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-precision-in-capturing-androids-best-techniques/"><u>[Updated] Precision in Capturing  Android's Best Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-in-win10win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 in Win10/Win11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-echoes-of-clarity-a-comprehensive-tutorial-on-eliminating-background-distractions-in-web-tools/"><u>New Echoes of Clarity A Comprehensive Tutorial on Eliminating Background Distractions in Web Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-automatic-lock-settings/"><u>Mastery over Windows Automatic Lock Settings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-noise-free-audiovisual-links/"><u>In 2024, Navigating Noise-Free Audiovisual Links</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-pathway-to-smart-youtube-frames-free-methods-inside/"><u>In 2024, The Pathway to Smart YouTube Frames (Free Methods Inside!)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-admin-denial-in-cmd-window-on-windows-10/"><u>Fixing Admin Denial in CMD Window on Windows 10</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-vlog-versus-channels-choosing-between-obs-and-twitch-for-2024/"><u>[Updated] Vlog Versus Channels  Choosing Between OBS & Twitch for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-do-you-nullify-windows-hello-in-win11/"><u>How Do You Nullify Windows Hello in Win11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-system-performance-via-alomware-settings-utility/"><u>Enhance System Performance via AlomWare Settings Utility</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-optimizing-obs-studio-5-editing-game-changers/"><u>[New] 2024 Approved  Optimizing OBS Studio  5 Editing Game Changers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unraveling-top-6-your-guide-to-free-and-favored-shorts-downloaders/"><u>Unraveling Top 6  Your Guide to Free & Favored Shorts Downloaders</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-mastering-unlocking-your-personalized-tiktok-hashtag/"><u>[New] 2024 Approved  Mastering  Unlocking Your Personalized TikTok Hashtag</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-dark-theme-in-windows-calculator/"><u>Implementing Dark Theme in Windows Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fine-tuning-your-program-visibility-win11-style/"><u>Fine-Tuning Your Program Visibility: Win11 Style</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-top-12-uninterrupted-capture-software/"><u>In 2024, Top 12 Uninterrupted Capture Software</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-navigating-the-changing-landscape-of-instagram-stories/"><u>[Updated] In 2024, Navigating the Changing Landscape of Instagram Stories</u></a></li>
</ul></div>
