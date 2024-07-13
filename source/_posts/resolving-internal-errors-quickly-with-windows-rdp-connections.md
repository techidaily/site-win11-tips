---
title: Resolving Internal Errors Quickly with Windows RDP Connections
date: 2024-07-12T16:44:20.295Z
updated: 2024-07-13T16:44:20.295Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Internal Errors Quickly with Windows RDP Connections
excerpt: This Article Describes Resolving Internal Errors Quickly with Windows RDP Connections
keywords: Fix RDP Errors Fast,Windows RDP Troubleshoot,Resolve Remote Desktop Errors,Quick RDP Connection Fixes,Windows RDP Stability,RDP Connectivity Problems,Improve RDP Session Speed
thumbnail: https://thmb.techidaily.com/cf530c2c593b6932cef8db0cdf4cd19063a18ed96567f34da25c1f69a7f2e22f.jpg
---

## Resolving Internal Errors Quickly with Windows RDP Connections

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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-unlock-creative-expression-on-tiktok-through-voice-alteration/"><u>[Updated] In 2024, Unlock Creative Expression on TikTok Through Voice Alteration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-vlc-capture-tool-assessment/"><u>[Updated] VLC Capture Tool Assessment</u></a></li>
<li><a href="https://some-techniques.techidaily.com/game-optimized-screens-for-ps5-xbox-series-x-gamers-for-2024/"><u>Game-Optimized Screens for PS5, Xbox Series X Gamers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-could-not-initiate-jvm-in-windows-environment/"><u>Addressing Could Not Initiate JVM in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363450902-mastering-the-art-of-total-windows-screen-capturing-with-these-4-tips/"><u>Mastering the Art of Total Windows Screen Capturing with These 4 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-easy-ways-to-disable-a-user-account-on-windows-11/"><u>4 Easy Ways to Disable a User Account on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-mastery-accessing-windows-admin-settings/"><u>Achieving Mastery: Accessing Windows Admin Settings</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-turn-your-iphone-images-upside-down-with-precision/"><u>2024 Approved  Turn Your iPhone Images Upside Down with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-secure-windows-options-when-bitlocker-isnt-available/"><u>5 Secure Windows Options when Bitlocker Isn't Available</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-samsung-galaxy-a15-5g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Samsung Galaxy A15 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719285972506-windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-depth-analysis-does-inshot-stand-out-in-editing-software/"><u>[New] In-Depth Analysis  Does InShot Stand Out in Editing Software?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719319213526-essential-tips-for-a-working-winshift/"><u>Essential Tips for a Working WinShift.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-total-screen-capture-mastery-using-snip-and-sketch/"><u>Achieving Total Screen Capture Mastery Using Snip & Sketch.</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-seo-innovation-pivotal-tech-to-elevate-your-vids/"><u>2024 Approved  SEO Innovation  Pivotal Tech to Elevate Your Vids</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-potential-exciting-enhancements-from-w11-22h2-moment/"><u>7 Potential Exciting Enhancements From W11 22H2 Moment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-android-innovations-to-transform-your-windows-11-setup/"><u>6 Android Innovations to Transform Your Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-chromium-installation-in-windows-11/"><u>A Detailed Walkthrough of Chromium Installation in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-v30-lite-5g-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on V30 Lite 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-right-way-to-close-a-long-term-but-unneeded-linkedin-account/"><u>2024 Approved  The Right Way to Close a Long-Term but Unneeded LinkedIn Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-command-line-capers-for-the-tech-whimsical/"><u>5 Command Line Capers for the Tech Whimsical</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-11-easy-to-produce-vlog-projects-at-home/"><u>[Updated] 2024 Approved  11 Easy-to-Produce Vlog Projects at Home</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-errors-caused-by-organization-managed-features-on-windows-11/"><u>Addressing Errors Caused by Organization-Managed Features on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-beginners-basics-of-video-clarity-and-sharpness/"><u>[New] Beginner's Basics of Video Clarity and Sharpness</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-narzo-n53-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Narzo N53</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719347202341-unveiling-the-full-potential-of-windows-snip-and-sketch-capabilities/"><u>Unveiling the Full Potential of Windows' Snip and Sketch Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284325307-chrome-opening-woes-resolved-fast-fixed-for-windows-11-users/"><u>Chrome Opening Woes Resolved: Fast Fixed for Windows 11 Users.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-serenity-windows-sleep-mode-guide/"><u>Achieving Serenity: Windows Sleep Mode Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-empty-display-of-system-startups/"><u>Addressing the Empty Display of System Startups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-surface-laptop-studio-2s-creative-edge/"><u>A Deep Dive Into Surface Laptop Studio 2’S Creative Edge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719363006980-discover-solutions-for-programs-that-dont-work-on-vistawindows-7/"><u>Discover Solutions for Programs that Don't Work on Vista/Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-outlook-preview-via-windows-11-os/"><u>Accessing Outlook Preview via Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-balanced-screen-viewing-a-step-by-step-guide-to-90-degree-rotation/"><u>Achieving Balanced Screen Viewing: A Step-by-Step Guide to 90-Degree Rotation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-towards-improved-security-extending-pins-in-oses/"><u>A Step Towards Improved Security: Extending PINs in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-windows-solid-state-drive-power-of-fresh/"><u>Accelerate Your Windows' Solid State Drive - Power of Fresh</u></a></li>
</ul></div>
