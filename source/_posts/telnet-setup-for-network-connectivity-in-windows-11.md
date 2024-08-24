---
title: Telnet Setup for Network Connectivity in Windows 11
date: 2024-08-23T07:08:28.318Z
updated: 2024-08-24T07:08:28.318Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Telnet Setup for Network Connectivity in Windows 11
excerpt: This Article Describes Telnet Setup for Network Connectivity in Windows 11
keywords: Windows Telnet Setup,Telnet Windows 11,Network Telnet Protocol,Connected via Telnet,Windows 11 Networking,Installing Telnet Client,Windows Telnet Configuration
thumbnail: https://thmb.techidaily.com/1945857397ebd75b26ddd988969514bcfe07be7bef56803fb658a77091d094a7.jpg
---

## Telnet Setup for Network Connectivity in Windows 11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-exploring-the-world-of-desktop-capturing-a-sprout-review/"><u>[New] 2024 Approved  Exploring the World of Desktop Capturing - A Sprout Review</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/"><u>[New] 2024 Approved  Ideal Low-Impact Recording Devices for Eco-Conscious Filmmakers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-be-the-best-lifeguard-at-your-friends-tiktok-shores-for-2024/"><u>[Updated] Be the Best Lifeguard at Your Friends’ TikTok Shores for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-executable-and-linker-format-pe/"><u>Demystifying Windows Executable & Linker Format (PE)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-and-fixing-event-viewer-problems/"><u>Diagnosing and Fixing Event Viewer Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-team-tools-without-the-burden/"><u>Efficient Team Tools Without the Burden</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-productivity-optimize-windows-tiling/"><u>Elevate Productivity: Optimize Windows Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-window-11s-camera-app-crash-afc-error-code/"><u>Eliminating Window 11'S Camera APP Crash: AFC Error Code</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embark-on-a-new-language-expedition/"><u>Embark on a New Language Expedition!</u></a></li>
<li><a href="https://driver-download.techidaily.com/essential-steps-for-successfully-refreshing-ati-graphic-cards-drivers-in-windows-os/"><u>Essential Steps for Successfully Refreshing ATI Graphic Cards Drivers in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-reversing-problems-from-a-recent-windows-update/"><u>Expert Advice: Reversing Problems From a Recent Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/file-expertise-accessing-tabs-with-ease-windows-11/"><u>File Expertise: Accessing Tabs with Ease (Windows 11)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/fixing-skype-essential-advice-for-troubled-connections/"><u>Fixing Skype: Essential Advice for Troubled Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-enigma-of-error-0x0000004e-in-win11/"><u>Fixing the Enigma of Error 0X0000004E in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-most-common-anydesk-failures/"><u>Fixing Windows' Most Common AnyDesk Failures</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-oppo-a59-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-11-apples-new-iphone-by-drfone-ios/"><u>How to Unlock Apple iPhone 11, Apples New iPhone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-vivo-y100i-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-in-depth-audio-settings-in-windows-10/"><u>In 2024, In-Depth  Audio Settings in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-ms-stores-premier-choices/"><u>Jumpstart Your PC: MS Store's Premier Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-tips-operating-the-toolbar-in-mspcm-win11/"><u>Key Tips: Operating the Toolbar in MSPCM Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-your-guide-for-windows-users/"><u>Mastering Map Integration: Your Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-11-policy-editor-efficiently/"><u>Navigate Windows 11 Policy Editor Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inaccessible-delete-switch-in-windows-11-pins/"><u>Overcoming Inaccessible Delete Switch in Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-desktop-spaces-optimal-size-in-win11/"><u>Perfecting Desktop Spaces: Optimal Size in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-messenger-magic-on-windows-devices/"><u>Reigniting Messenger Magic on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-non-working-outlook-automated-filters-in-windows/"><u>Restarting Non-Working Outlook Automated Filters in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-brightness-on-windows-volume-controls/"><u>Restore Brightness on Windows' Volume Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-operation-of-ps-windows-version/"><u>Restoring Seamless Operation of PS Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-experience-file-explorer-troubleshooting/"><u>Revitalize Your Experience: File Explorer Troubleshooting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-opening-win-11s-call-center/"><u>Steps for Opening Win 11'S Call Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-overcome-server-stumbled-error-in-windows-11-and-11-store/"><u>Steps to Overcome Server Stumbled Error in Windows 11 & 11 Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-reawakening-guide-navigating-through-windows-8-revival-techniques/"><u>System Reawakening Guide: Navigating Through Windows' 8 Revival Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-approaches-to-overcoming-disabled-errors-in-ps-execution/"><u>Tactical Approaches to Overcoming 'Disabled' Errors in PS Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-rectify-non-specified-values-on-windows-pcs/"><u>Techniques to Rectify Non-Specified Values on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workday-top-9-motivations-to-switch-to-windows-outlook/"><u>Transform Your Workday: Top 9 Motivations to Switch to Windows' Outlook</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-guide-updating-your-intel-hd-graphics-5500-drivers-steps-and-tips/"><u>Ultimate Guide: Updating Your Intel HD Graphics 5500 Drivers - Steps and Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-android-and-pc-simple-synchronization-techniques/"><u>Uniting Android & PC: Simple Synchronization Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-greyed-out-pin-deletion-command-on-pc/"><u>Unlocking Greyed-Out Pin Deletion Command on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-health-5-key-steps-for-device-status-tracking/"><u>Windows 11 Health: 5 Key Steps for Device Status Tracking</u></a></li>
</ul></div>
