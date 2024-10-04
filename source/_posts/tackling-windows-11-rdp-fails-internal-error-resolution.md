---
title: "Tackling Windows 11 RDP Fails: Internal Error Resolution"
date: 2024-10-01T20:09:02.155Z
updated: 2024-10-03T20:29:39.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Windows 11 RDP Fails: Internal Error Resolution"
excerpt: "This Article Describes Tackling Windows 11 RDP Fails: Internal Error Resolution"
keywords: Win11RDPCorrect,FixErrorWin11RDP,RDPResolveFailures,Windows11RDPFixes,Win11RDPTroubleshoot,SolveWin11RDPErrors,UnblockWindowsRDP
thumbnail: https://thmb.techidaily.com/609392eeb7e6d07659b5310d5497d83d3c111a4e7e0b8902513730d25dcd2f24.png
---

## Tackling Windows 11 RDP Fails: Internal Error Resolution

 Many users utilize the Remote Desktop Connection app included with Windows to connect with remote PCs. However, some users have reported a Remote Desktop Connection error message that says, “An internal error has occurred.” Consequently, they can’t connect to remote PCs with RDC when that error occurs.

 This error means RDC’s Remote Desktop Protocol can’t establish a server connection with the remote PC selected. Does the “internal error has occurred” error message pop up when you try to connect to another computer with Remote Desktop Connection? If it does, this is how you can resolve that RDP issue in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Network Layer Authentication

 There’s an **Allow connections only from computers running Remote Desktop with Network Level Authentication** setting just below the**Allow Remote connection** radio button. Selecting that option implements tighter Network Layer Authentication security for remote connections. However, some users confirm that disabling NLA by unticking that checkbox can fix the “internal error has occurred” error. So, deselect that option if you’ve got it selected.

## 3\. Start or Restart the Remote Desktop Connection Service

 Remote Desktop Services is a service needed for connecting to remote PCs. So, it could be the case you need to fix the “internal error has occurred” error because that service isn’t enabled on your PC. This is how you can start the Remote Desktop Services in Windows 11/10:

1. Open the search utility for finding files and apps in Windows 11/10.
2. Enter**Services** within Windows’ search box and select to open that app from there.
3. Double-click**Remote Desktop Services** to access some configuration settings for that service.  
![The Remote Desktop Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/services-window.jpg)
4. If disabled, select**Automatic** on the**Startup** drop-down menu for Remote Desktop Services.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click**Start** (inside the properties window) to run Remote Desktop Services.  
![The Remote Desktop Services Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-services-service.jpg)
6. Select**Apply** to set the new service options.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Then you can exit the window by clicking**OK** or**X** .
8. If Remote Desktop Services is already running, you can try restarting it instead. Right-click**Remote Desktop Services** to view its context menu and select**Restart** from there.

## 4\. Select the "Reconnect if the Connection Is Dropped" Setting

 Some Remote Desktop Connection users have confirmed that selecting a**Reconnect if the connection is dropped** setting in that app can resolve this error. That simple potential resolution is certainly worth a try. You can select that**Reconnect** setting like this:

1. Start the RDC app with a method in our[how-to open Remote Desktop Connection guide](http://www.makeuseof.com/windows-11-open-remote-desktop-connection/) .
2. Click**Show Options** to view RDC’s settings.  
![The Remote Desktop Connections app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/remote-desktop-connections.jpg)
3. Select the**Experience** tab.  
![The Experience tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/experience-tab.jpg)
4. Then select the**Reconnect if the connection is dropped** checkbox.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press the**Connect** button.

## 5\. Set an Automatic DNS Server

 If you’ve set a specific DNS server on your PC, change to an automatic DNS server instead. There could be an issue with the DNS server you’ve set. You can set an automatic DNS server like this:

1. Open Run (press the**Win + R** hotkey or see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ) and enter**ncpa.cpl** in that command box.
2. Click**OK** to view the Network Connections applet.
3. Right-click the internet connection to select its**Properties** context menu option.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/properties-option-1.jpg)
4. Select**Internet Protocol Version 4** and click**Properties** .
5. Then click**Obtain DNS server automatically** radio button.  
![The Obtain DNS server radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/obtain-dns-server-option.jpg)
6. Also, click**Obtain an IP address automatically** if that option isn’t selected.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Select**OK** to confirm the new DNS and IP address settings.

## 6\. Enable the "Require Use of Specific Security Layer" Group Policy Setting

 Group Policy includes a**Require use of specific security layer policy** setting. Enabling an RDP security layer with that policy might fix the “internal error has occurred” error for some users. To do so, set the**Require use of specific security layer** policy setting as follows:

1. Open Local Group Policy Editor with a method in our guide on[how to launch gpedit.msc](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) guide. If you're using Windows Home, be sure to check out[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Next, you’ll need to double-click**Computer Configuration** \>**Administrative Templates** in the Group Policy’s sidebar.
3. Double-click**Windows Components** \>**Remote Desktop Services** \>**Remote Desktop Session Host** in the console tree.
4. Click**Security** to view its policy settings.
5. Double-click the **Require use of specific security layer for remote (RDP) connections** policy.  
![The Security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-policies.jpg)
6. Select the**Enabled** radio button for that policy.
7. Choose**RDP** in the**Security Layer** drop-down menu.  
![The Security Layer RDP option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/rdp-option.jpg)
8. Click**Apply** \>**OK** inside the**Require use of specific security layer** for remote (RDP) connections policy window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Press your Start menu’s**Restart** button.
6. Then try connecting to the remote computer with RDC again.

## 9\. Turn Off Any Active VPNs

 VPNs that route connections to different servers can also cause the “internal error has occurred” issue to arise. If you’re utilizing a VPN, at least try temporarily disabling it. This is how you can turn off a VPN in Settings:

1. Open the Windows Settings app to select**Network & internet** .
2. Click the**VPN** navigation option or tab.  
![The VPN navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/vpn-navigation-option.jpg)
3. Select your VPN’s**Disconnect** option.  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-help.techidaily.com/new-exclusive-mcb-logo-designs-and-templates/"><u>[New] Exclusive MCB Logo Designs and Templates</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-instant-anonymity-shield-face-details/"><u>[Updated] In 2024, Instant Anonymity Shield Face Details</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-holistic-harmony-the-best-online-yoga-channels/"><u>2024 Approved Holistic Harmony - The Best Online Yoga Channels</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722874253484-beat-code-28errors-in-windows-with-these-proven-fixes/"><u>Beat Code ^[[2][8]Errors in Windows with These Proven Fixes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-windows-11-clean-install-tutorial/"><u>Complete Windows 11 Clean Install Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-and-restore-missing-pin-on-windows-11-system/"><u>How To Locate and Restore Missing PIN on Windows 11 System</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1715860430243-in-2024-activating-built-in-recorders-on-mate-and-p-series-phones-mate-1020-p2010/"><u>In 2024, Activating Built-In Recorders on Mate and P Series Phones (Mate 10/20; P20/10).</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-iphone-6s-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From iPhone 6s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-the-system-level-driver-monitor-w11/"><u>Launching the System-Level Driver Monitor W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-non-operational-obs/"><u>Mastering the Art of Restarting Non-Operational OBS</u></a></li>
<li><a href="https://win-answers.techidaily.com/1726029871244-mp3/"><u>MP3への変換ガイド: ニコニコ動画から高音質オーディオ素材取得</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-zerox-error-at-keyboard-input/"><u>Overcoming Windows 11'S Zerox Error at Keyboard Input</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/orm-predicament-choosing-the-right-space/"><u>Platform Predicament Choosing the Right Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/students-new-tech-ally-asus-s15-oled-review-revealed/"><u>Students' New Tech Ally: Asus S15 OLED Review Revealed</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-guide-to-dreame-bot-l10-pro-review-revolutionizing-household-chores-with-lidar-technology/"><u>The Ultimate Guide to Dreame Bot L10 Pro Review - Revolutionizing Household Chores with LiDAR Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-accelerate-your-windows-printer-pace/"><u>Turbo-Accelerate Your WIndows Printer Pace</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-for-tiktok-content-sharing-strategies/"><u>Twitter for TikTok Content Sharing Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-covert-software-on-your-pc/"><u>Uncovering Covert Software on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-you-should-stick-with-windows-over-linux-for-gaming/"><u>Why You Should Stick With Windows Over Linux for Gaming</u></a></li>
</ul></div>

