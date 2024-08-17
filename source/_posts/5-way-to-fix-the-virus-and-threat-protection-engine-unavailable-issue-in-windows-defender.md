---
title: 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
date: 2024-08-16T01:09:27.562Z
updated: 2024-08-17T01:09:27.562Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
excerpt: This Article Describes 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender
keywords: Windows Defender Fault,Fixing Defender Issues,WinDefend Unavailability,Disable Security Errors,Threat Engine Restoration,Protect From Virus Glitch,Resolve WinDefend Failure
thumbnail: https://thmb.techidaily.com/d4a369170dd24048d49b11ae6cda29b689bc2d38aadd635d4ed1887b04b3b67e.jpg
---

## 5 Way to Fix the Virus & Threat Protection Engine Unavailable Issue in Windows Defender

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the [Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the [different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Once the command is executed, exit Powershell and check if the issue is resolved.

## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses [how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some [best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.


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
<li><a href="https://facebook-clips.techidaily.com/new-effortless-transformation-of-your-fb-video-content-to-mp3/"><u>[New] Effortless Transformation of Your Fb Video Content to MP3</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-the-essential-8-in-virtual-reality-gaming/"><u>[New] The Essential 8 in Virtual Reality Gaming</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-verdict-on-splitcam-premium-recording-experience-in-2024/"><u>[New] The Verdict on SplitCam - Premium Recording Experience, In 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-streamlining-media-transfer-twitter-content-on-snapchat/"><u>[Updated] 2024 Approved  Streamlining Media Transfer  Twitter Content on Snapchat</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-minimize-mbs-avoid-fb-video-ads-for-2024/"><u>[Updated] Minimize MBs  Avoid FB Video Ads for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-multiplying-joy-sharing-a-pile-of-photos-and-videos-with-instagram-for-2024/"><u>[Updated] Multiplying Joy  Sharing a Pile of Photos & Videos with Instagram for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-secrets-to-finding-excellent-economic-pictures-online/"><u>2024 Approved  Secrets to Finding Excellent, Economic Pictures Online</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-motorola-g24-power-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola G24 Power Unlock Without Password</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-and-tarkov-fix-visual-evasion-guide/"><u>AMD & Tarkov Fix: Visual Evasion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/averting-interruptions-with-solid-connections-in-windows/"><u>Averting Interruptions with Solid Connections in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensible-guide-to-resetting-faulty-google-nearby-share/"><u>Comprehensible Guide to Resetting Faulty Google Nearby Share</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-7-indicative-windows-activities-of-malware/"><u>Deciphering 7 Indicative Windows Activities of Malware</u></a></li>
<li><a href="https://extra-hints.techidaily.com/detailed-guide-to-zoom-youtube-live/"><u>Detailed Guide to Zoom YouTube Live</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easing-into-intel-graphic-upgrades-for-underperforming-pcs/"><u>Easing Into Intel Graphic Upgrades for Underperforming PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pen-performance-tackling-issues-in-windows-tablets/"><u>Enhance Pen Performance: Tackling Issues in Windows Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-addressing-installation-setbacks-in-win11/"><u>Essential Techniques for Addressing Installation Setbacks in Win11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/expert-approved-4k-video-editing-solutions-for-2024/"><u>Expert-Approved 4K Video Editing Solutions for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-controller-detection-issues-on-windows-steam/"><u>Fixing Controller Detection Issues on Windows Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-securely-modify-user-passwords-in-win-11/"><u>Guide to Securely Modify User Passwords in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-image-thumbnail-size-in-windows-11/"><u>How to Change the Image Thumbnail Size in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-12-pro-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 12 Pro Max without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-effortlessly-adjust-your-software-size-with-windows-11-keys/"><u>How to Effortlessly Adjust Your Software Size with Windows 11 Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-failed-to-attach-the-usb-device-error-in-virtualbox-on-windows/"><u>How to Fix the Failed to Attach the USB Device Error in VirtualBox on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-box-buying-bonanza-uncovering-top-1-written-by-instruction-1/"><u>In 2024, Box Buying Bonanza! Uncovering Top 1 Written by Instruction 1</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-the-top-5-resources-for-innovative-text-designs/"><u>In 2024, Explore the Top 5 Resources for Innovative Text Designs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-can-i-unlock-my-iphone-11-after-forgetting-my-pin-code-by-drfone-ios/"><u>In 2024, How Can I Unlock My iPhone 11 After Forgetting my PIN Code?</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-techniques-to-mitigate-vr-disorientation/"><u>In 2024, Techniques to Mitigate VR Disorientation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-your-productivity-in-windows-with-flow-launcher/"><u>Increase Your Productivity in Windows With Flow Launcher</u></a></li>
<li><a href="https://techtrends.techidaily.com/insights-into-ai-development-identifying-the-makers-of-chatgpt-technology/"><u>Insights Into AI Development: Identifying the Makers of ChatGPT Technology</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-oculus-rift-into-a-windows-pc-virtual-reality-setup/"><u>Integrating Oculus Rift Into a Windows PC Virtual Reality Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-advanced-tactics-for-group-policy-optimization/"><u>Leveraging Advanced Tactics for Group Policy Optimization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-efficiency-in-windows-1011-with-top-rated-productivity-tools/"><u>Master Efficiency in Windows 10/11 with Top-Rated Productivity Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-ms-office-widows-1011-setup/"><u>Mastering MS Office WIdows 10/11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-system32-access-on-windows-11/"><u>Mastering System32 Access on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mirrorless-impact-on-professional-video-recording/"><u>Mirrorless Impact on Professional Video Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-operation-failure-error-0x0000011b-in-windows-11/"><u>Mitigating Operation Failure (Error: 0X0000011B) in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/mobile-magic-no-cost-image-transformation-tool/"><u>Mobile Magic  No-Cost Image Transformation Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-dystopia-my-quest-for-self-identity-amidst-app-guard/"><u>Navigating Dystopia: My Quest for Self-Identity Amidst App Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-existent-registry-tool/"><u>Navigating Through Non-Existent Registry Tool</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-top-15-slow-motion-capcut-templates-to-work-with-for-2024/"><u>New Top 15 Slow Motion CapCut Templates to Work With for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-asana-compatibility-hurdles-with-windows/"><u>Overcoming Asana Compatibility Hurdles with Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-pens-tablet-apps-on-the-windows-os/"><u>Perfect Pens' Tablet Apps on the Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/polishing-your-past-redefining-vintage-videos-with-windows-and-madvr/"><u>Polishing Your Past: Redefining Vintage Videos with Windows and MadVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precision-guide-for-heic-to-jpeg-transformation-in-w11/"><u>Precision Guide for Heic to JPEG Transformation in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-historical-directx-titles-through-enhanced-dxvk-performance/"><u>Refreshing Historical DirectX Titles Through Enhanced DXVK Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-limited-administrator-power-from-security-issue/"><u>Removing 'Limited Administrator Power' From Security Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-read-only-settings-for-steam-libraries-on-win-11-pcs/"><u>Removing Read-Only Settings for Steam Libraries on Win 11 PCs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/sci-fi-action-gaming-experience-in-the-outer-worlds-an-engaging-narrative-adventure/"><u>Sci-Fi Action Gaming Experience in 'The Outer Worlds': An Engaging Narrative Adventure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silencing-the-disruptive-noise-irq-tuning-guide/"><u>Silencing the Disruptive Noise: IRQ Tuning Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/streaming-mastery-record-hulu-playback-on-multiple-systems/"><u>Streaming Mastery  Record Hulu Playback on Multiple Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-safety-proven-ways-to-prevent-unauthorized-access/"><u>System Safety: Proven Ways to Prevent Unauthorized Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-way-to-cut-out-unwanted-onedrive-in-explorer/"><u>The Way to Cut Out Unwanted OneDrive in Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-and-techniques-for-resolving-failed-image-import-from-ios-devices/"><u>Tips and Techniques for Resolving Failed Image Import From iOS Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-lava-blaze-2-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Lava Blaze 2 5G Location | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharge-windows-11-eliminate-sluggishness-effectively/"><u>Turbocharge Windows 11: Eliminate Sluggishness Effectively</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/ukrainian-and-russian-how-similar-are-these-two-languages/"><u>Ukrainian and Russian: How Similar Are These Two Languages?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-the-disabled-recycle-icon-on-win11/"><u>Unblocking the Disabled Recycle Icon on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-full-office-capabilities-installing-outlook-preview-on-windows-11/"><u>Unlock Full Office Capabilities: Installing Outlook Preview on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-classic-adventures-in-hd-with-scummvm/"><u>Unlock the Full Potential of Classic Adventures in HD with ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-at-code-top-strategies-for-wsl-2-users/"><u>Winning at Code: Top Strategies for WSL 2 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/xbox-not-working-quick-windows-solution-guide/"><u>Xbox Not Working: Quick Windows Solution Guide</u></a></li>
</ul></div>
