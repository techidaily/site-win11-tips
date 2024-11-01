---
title: "Optimizing Network Defenses: 5 Key Adjustments"
date: 2024-10-31T18:09:34.794Z
updated: 2024-11-01T16:14:51.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Network Defenses: 5 Key Adjustments"
excerpt: "This Article Describes Optimizing Network Defenses: 5 Key Adjustments"
keywords: NetDefense Optimization,Security Adjustment Guide,Network Guarding Tips,Cyber Safeguard Strategies,Defense Improvement Steps,Secure Network Methods,Protective Defense Tweaks
thumbnail: https://thmb.techidaily.com/f7564240f8faa92ac0e388d789a175a79bd1b95533429025b3702f8272211ea0.jpg
---

## Optimizing Network Defenses: 5 Key Adjustments

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
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

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/1716069293527-new-2024-approved-little-legends-top-gaming-adventures/"><u>[New] 2024 Approved Little Legends Top Gaming Adventures!</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-syncing-images-pc-to-iphone-file-sharing/"><u>[New] 2024 Approved Syncing Images PC-to-iPhone File Sharing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-initiating-your-sporty-online-presence-with-mac/"><u>[New] Initiating Your Sporty Online Presence with Mac</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-boost-channels-to-partner-status-in-under-90-days-start-now-for-2024/"><u>[Updated] Boost Channels to Partner Status in Under 90 Days, Start Now for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-s17-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-key-adjustments-to-reestablish-wi-fi-connectivity-in-windows-10-systems/"><u>5 Key Adjustments to Reestablish Wi-Fi Connectivity in Windows 10 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-repairing-onedrive-on-windows-11/"><u>A Step-by-Step Approach to Repairing OneDrive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-pc-interaction-with-comprehensible-win11-navkeys/"><u>Accelerate PC Interaction with Comprehensible Win11 NavKeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-pc-queries-with-everythingapp/"><u>Accelerate Your PC Queries with EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-high-temperatures-in-windows-11-pcs/"><u>Avoiding High Temperatures in Windows 11 PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-search-of-next-level-video-streaming-alternatives/"><u>In 2024, In Search of Next-Level Video Streaming Alternatives</u></a></li>
<li><a href="https://tech-revival.techidaily.com/movhevc/"><u>MOVファイルとのHEVCコードチェンジ: 効率的なビデオエンコード・デコード手法</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/pioneering-camera-spin-top-professionals-360cameras-of-2023/"><u>Pioneering Camera Spin Top Professionals’ 360°Cameras of 2023</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-pova-5-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Pova 5.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719285972506-windows-error-trouble-with-compatibility-tool-here-are-quick-solutions/"><u>Windows Error: Trouble with Compatibility Tool? Here Are Quick Solutions</u></a></li>
</ul></div>

