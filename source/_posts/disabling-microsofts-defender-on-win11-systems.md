---
title: Disabling Microsoft's Defender on Win11 Systems
date: 2024-08-23T07:01:50.271Z
updated: 2024-08-24T07:01:50.271Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Microsoft's Defender on Win11 Systems
excerpt: This Article Describes Disabling Microsoft's Defender on Win11 Systems
keywords: Disable Windows Defender,Turn Off Defender (Win11),Stop Windows Security (Win11),Deactivate Microsoft Defender,Windows Defender Off (Windows 11),Suppress Win11 Defender,Inhibit Windows 11 Guard
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## Disabling Microsoft's Defender on Win11 Systems

 While firewalls can protect you from malicious online threats, there may be times when it is necessary to disable them for certain tasks or applications. While it's usually not a good idea to disable the firewall for long periods of time, doing so for a few seconds while you troubleshoot a problem is usually safe.

 As such, let's explore how to turn off or disable the Microsoft Defender firewall safely and securely in Windows 11\.

## How Important Is the Microsoft Defender Firewall?

 A firewall acts as a shield against unwanted intrusions and prevents external connections from accessing your system without permission. When disabled, your computer becomes vulnerable, and you should take extra precautions while online.

 To ensure maximum security while disabling your firewall, always make sure that other protective measures such as antivirus programs are running in the background. Once these have been taken care of, you can disable the firewall on your Windows 11 PC. Here's how to do this:

## 1\. How to Disable the Firewall Using Windows Security

 The Windows Security program allows you to disable the firewall in Windows 11\. It is the most straightforward way to disable Microsoft Defender Firewall and you don’t need to have any additional tools or software installed. Here's how:

1. Click on **Start** and search for “Windows Security”.
2. Then select the result from the top of the list.
3. Once you are in Windows Security, click on the **Firewall & network protection** option.
4. Select the **Public network** or **Private network** profile and turn off the firewall for that selection.  
![Disable the Firewall Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-using-windows-security.jpeg)

 The UAC prompt will require you to accept it, so make sure your computer is set up as an admin account. If UAC prompts on the screen, click **Yes** to continue.

 Now that you have completed the above steps, disable the firewall for each network profile using the same procedure.

## 2\. How to Disable the Firewall Through Control Panel

 If you are running an older version of Windows or prefer to use a more traditional method, you can disable your firewall through the Control Panel. This is a bit more technical than using Windows Security but still easy enough to do. Here’s how:

1. Open the Control Panel. If you need help with this, check out [how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/).  
![Disable the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-firewall-through-control-panel.jpeg)
2. In the Control Panel, select **System and Security** and then click **Windows Defender Firewall**.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
3. From the left pane, select **Turn Windows Defender Firewall on or off**.  
![Turn off the Firewall Through Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-through-control-panel.jpeg)
4. Then select **Turn off Windows Defender Firewall (not recommended)** for each network setting.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
5. Click **OK** to save your changes.

## 3\. How to Disable the Firewall Using Command Prompt

 If you are comfortable using the command line, then you can also disable your firewall through the Command Prompt. Here’s how:

 Press **Win + S** on your keyboard to open the Windows search tool. Now type "cmd" in the search field and press **Ctrl + Shift + Enter** on your keyboard. This will open Command Prompt with admin rights.

 Once you are in the Command Prompt, type in the following command and hit **Enter:**

netsh advfirewall set currentprofile state off

 Running the above command will turn off the firewall for the current network profile.

 If you wish to disable the firewall for the domain network profile, copy and paste the following command, and hit **Enter**:

netsh advfirewall set domainprofile state off

 Similarly, you can disable the firewall for the private network profile. To do this, copy and paste the following command and hit **Enter**:

netsh advfirewall set privateprofile state off

 For the public network profile, type the following command in the Command Prompt window and press **Enter**:

netsh advfirewall set publicprofile state off

 Alternatively, you can disable the Defender Firewall for all network profiles, such as domain, private, and public, with just one command. To do this, copy and paste the below command and hit **Enter**:

netsh advfirewall set allprofiles state off

 In this way, you can disable the firewall according to your selected network profiles.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Turn Off the Firewall via PowerShell

 Windows PowerShell is an important tool that can be used to manage many aspects of the Windows operating system. You can also use it to disable the Microsoft Defender Firewall.

 To do this, open a PowerShell window as an administrator and run the following commands:

![Turn Off the Firewall Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False

 After running the above command, the firewall will be disabled for all network profiles simultaneously.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 5\. How to Turn Off the Firewall Using Group Policy Editor

 The Group Policy Editor is a powerful system resource that can be used to manage different settings on all Windows computers. With this tool, you can disable your firewall, but it only works with Windows Professional and Enterprise. If you are using Windows Home Edition, you need to [activate the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) in order to access it.

 To disable firewall settings using the Local group policy editor, follow these steps:

1. Right-click on Start and select **Run** from the menu list.
2. Type **gpedit.msc** in the dialog box and click **OK** or press Enter on your keyboard.
3. Inside the Group Policy Editor window, navigate to the following:  
Computer Configuration > Administrative Templates > Network > Network Connections > Windows Defender Firewall > Standard Profile
4. On the right side of the window, double-click the policy called **Windows Defender Firewall: Protect all network connections**.  
![Turn Off the Firewall Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-group-policy-editor.jpg)
5. Next, choose **Disabled** from the dialog box that appears.
6. When you're done making your changes, click **Apply** \> **OK**.
7. For the changes to take effect, restart your computer after completing the above steps.

## 6\. How to Turn Off the Firewall Using Registry Editor

 Windows also has a method for disabling the firewall that involves editing the registry. It is an advanced feature that should only be used by experienced computer users, as incorrect usage can cause serious damage to your computer.

 When using the Registry Editor, it is important not to modify any other settings than those related directly to the firewall. Making unwanted changes could potentially lead to instability within your system, including a decrease in performance or even the complete failure of your operating system. If you're ready to use this method, make sure you [back up your Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point on Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/) first.

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Once you're in, navigate to the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\WindowsFirewall\StandardProfile
3. Right-click StandardProfile and select **New > DWORD (32-bit) Value**.
4. Specify **EnableFirewall** as the key name.
5. Double-click it and enter **0** in the Value data field.  
![Turn Off the Firewall Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-off-the-firewall-using-registry-editor.jpg)
6. Once you have made the changes, click **OK**.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 When you have completed all the steps above, close the Registry Editor and restart your computer.

## Disable the Firewall With Ease on Windows

 You may want to disable the firewall for testing, developing applications, or playing online games. However, disabling the firewall can have risks, and you should always exercise caution. In case you need to do it, this guide explains multiple ways to do it, such as via Windows Security, Control Panel, Command Prompt, and more.


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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-chaptered-videos-on-vimeo-a-comprehensible-guide/"><u>[New] 2024 Approved  Chaptered Videos on Vimeo  A Comprehensible Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-a-guide-to-outstanding-hdr-cameras/"><u>[New] A Guide to Outstanding HDR Cameras</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-the-art-of-polishing-and-personalizing-drone-videos/"><u>[Updated] 2024 Approved  The Art of Polishing and Personalizing Drone Videos</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-blending-beats-with-video-footage-on-vimeo-platform/"><u>[Updated] Blending Beats with Video Footage on Vimeo Platform</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-investigating-whether-sns-hdr-offers-superior-ux/"><u>[Updated] Investigating Whether SNS HDR Offers Superior UX</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-infusing-creative-edge-in-your-youtube-trailer-production/"><u>2024 Approved  Infusing Creative Edge in Your YouTube Trailer Production</u></a></li>
<li><a href="https://article-tips.techidaily.com/avoiding-career-pitfalls-in-graphic-artistry-for-2024/"><u>Avoiding Career Pitfalls in Graphic Artistry for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convert-cr2-files-into-compatible-windows-based-jpeg-images/"><u>Convert CR2 Files Into Compatible Windows-Based JPEG Images</u></a></li>
<li><a href="https://win-answers.techidaily.com/darkest-dungeon-2-stability-problems-how-to-stop-your-game-from-crashing-on-windowsmac/"><u>Darkest Dungeon #2 Stability Problems - How to Stop Your Game From Crashing on Windows/Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disarming-webcam-error-code-a00f4289-in-windows-11-panorama/"><u>Disarming Webcam Error Code A00F4289 in Windows 11 Panorama</u></a></li>
<li><a href="https://screen-recording.techidaily.com/guide-to-skype-call-audio-and-video-capture-windowsos-x-for-2024/"><u>Guide to Skype Call Audio & Video Capture Windows/OS X for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-full-potential-of-windows-11s-auto-hdr/"><u>Harnessing the Full Potential of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-gpt-4-all-operate-an-in-depth-analysis/"><u>How Does GPT-4 All Operate? An In-Depth Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-address-overwatch-2-device-rendering-issue/"><u>How to Address Overwatch 2 Device Rendering Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-batch-rename-files-with-powertoys-powerrename/"><u>How to Batch-Rename Files With Powertoys PowerRename</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-motorola-edge-2023-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Motorola Edge 2023 to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-basic-guide-to-modify-clown-voiceprint-in-windoze-pc/"><u>In 2024, Basic Guide to Modify Clown Voiceprint in Windoze PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-vivo-y27-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Vivo Y27 5G? Try These Fixes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-redmi-k70-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi Redmi K70 Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intercepting-wacatacbml-attacks-securing-windows-against-malware-invasion/"><u>Intercepting Wacatac.B!ml Attacks: Securing Windows Against Malware Invasion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-edges-steady-presence-in-windows-11/"><u>Managing Edge's Steady Presence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-office-error-0x80041015-on-windows/"><u>Mastering the Art of Fixing Office Error: 0X80041015 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-old-logon-phrase-glitch-in-windows/"><u>Mending “Old Logon Phrase Glitch in Windows”</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-dll-loss-mfc71u-on-windows-systems/"><u>Overcoming DLL Loss: Mfc71u on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-sticky-menu-issues-in-windows-11/"><u>Overcoming Sticky Menu Issues in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-deactivated-temperature-control-on-winos/"><u>Overhauling Deactivated Temperature Control on WinOS</u></a></li>
<li><a href="https://article-files.techidaily.com/perfect-accompaniments-for-your-sj4000-journey-for-2024/"><u>Perfect Accompaniments for Your SJ4000 Journey for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-complexity-access-to-windows-printer-administration-console/"><u>Simplifying Complexity: Access to Windows Printer Administration Console</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-seamless-access-to-windows-11s-app-compendium/"><u>Strategies for Seamless Access to Windows 11'S App Compendium</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-installation-with-microsofts-windows-cab-format/"><u>Streamlining File Installation with Microsoft's Windows CAB Format</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-avoid-keyboard-triggers-without-intent/"><u>Techniques to Avoid Keyboard Triggers without Intent</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-resource-for-hardware-enthusiasts-toms-informative-reviews/"><u>The Ultimate Resource for Hardware Enthusiasts: Tom's Informative Reviews</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-eliminate-xbox-game-pass-error-0x00000001/"><u>Troubleshooting Windows 11: Eliminate Xbox Game Pass Error 0X00000001</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-rdp-connectivity-woes/"><u>Understanding and Resolving RDP Connectivity Woes</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-accessing-and-deleting-your-usage-logs/"><u>Windows 11: Accessing & Deleting Your Usage Logs</u></a></li>
</ul></div>
