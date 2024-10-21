---
title: "Streamlining Security: Five Alterations to Windows Firewall"
date: 2024-10-19T20:54:47.515Z
updated: 2024-10-20T23:55:26.717Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamlining Security: Five Alterations to Windows Firewall"
excerpt: "This Article Describes Streamlining Security: Five Alterations to Windows Firewall"
keywords: Windows Firewall Update,Secure System Enhancements,Firewall Improvement Guide,Optimized Firewall Settings,Security Protocols Tweaks,Safe Network Adjustments,Efficient Firewall Upgrades
thumbnail: https://thmb.techidaily.com/70a221261e83ff3179ef93192d51afbff1f7257579ffa960f9e7a085032e4b04.png
---

## Streamlining Security: Five Alterations to Windows Firewall

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

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416">
  <img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1972693/19272" target="_top" id="1972693">
  <img src="//a.impactradius-go.com/display-ad/19272-1972693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972693/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-easy-steps-to-rectify-non-sending-or-delayed-videos-in-messenger-chats/"><u>[New] In 2024, Easy Steps to Rectify Non-Sending or Delayed Videos in Messenger Chats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/close-all-a-guide-to-ending-windows-instances-concurrently/"><u>Close All: A Guide to Ending Windows Instances Concurrently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-start-unveiling-sticky-notes-at-system-launch/"><u>Convenient Start: Unveiling Sticky Notes at System Launch</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722973395727-download-and-update-intel-reliable-array-raid-controller-drivers-for-windows-111087/"><u>Download & Update Intel Reliable Array (RAID) Controller Drivers for Windows 11/10/8/7</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-zte-blade-a73-5g-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your ZTE Blade A73 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-overcome-error-0x80072f8f-0x20000/"><u>Expert Tips to Overcome Error 0X80072f8f - 0X20000</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-disconnected-printer-issues-a-step-by-point-guide/"><u>Fixing Disconnected Printer Issues: A Step-By Point Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-request-a-refund-for-digital-xbox-series-xs-purchases/"><u>How to Request a Refund for Digital Xbox Series X|S Purchases</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-the-right-click-experience-for-update-tracking/"><u>Reinventing the Right-Click Experience for Update Tracking</u></a></li>
<li><a href="https://data-wizards.techidaily.com/renewed-phoenix-aid-for-broken-pdfs/"><u>Renewed Phoenix Aid for Broken PDFs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-active-status-to-office-outlook-push-notifications/"><u>Restoring Active Status to Office Outlook Push Notifications</u></a></li>
<li><a href="https://games-able.techidaily.com/spotless-playstation-console-and-controller-tips/"><u>Spotless PlayStation Console and Controller Tips</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-xiaomi-redmi-note-12-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Xiaomi Redmi Note 12 5G Fingerprint Not Working Solutions</u></a></li>
</ul></div>

