---
title: Effective Strategies to Control External Hard Drive Usage
date: 2024-08-16T01:46:34.482Z
updated: 2024-08-17T01:46:34.482Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Strategies to Control External Hard Drive Usage
excerpt: This Article Describes Effective Strategies to Control External Hard Drive Usage
keywords: HDD Usage Management,Data Storage Limits,Backup Plans Optimization,External Drive Efficiency,HDD Control Techniques,Data Transfer Limitation,Usage Time Allocation
thumbnail: https://thmb.techidaily.com/b1dd0483f32a09412f335f94508f9f7301d5aa196fe907bac96fdd29e9d8162d.png
---

## Effective Strategies to Control External Hard Drive Usage

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
### Using the Local Group Policy Editor
![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

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
### Using the Registry Editor
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-embracing-4k-clarity-the-q500-journey-reviewed/"><u>[New] In 2024, Embracing 4K Clarity  The Q500 Journey Reviewed</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-sprint-to-quicker-vimeo-streams/"><u>[New] Sprint to Quicker Vimeo Streams</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-elevate-engagement-with-these-10-igtv-branding-techniques/"><u>[Updated] 2024 Approved  Elevate Engagement with These 10 IGTV Branding Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-select-selections-exciting-cardboard-friendly-virtual-reality-titles/"><u>[Updated] Select Selections  Exciting Cardboard-Friendly Virtual Reality Titles</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-steps-to-engage-in-a-virtual-meeting-via-devices-google-for-2024/"><u>[Updated] Steps to Engage in a Virtual Meeting via Devices (Google) for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-transforming-discord-chats-into-lasting-memories/"><u>[Updated] Transforming Discord Chats Into Lasting Memories</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-samsung-galaxy-m34-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Samsung Galaxy M34 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-repairing-windows-error-0x80040610-in-outlook/"><u>Comprehensive Guide: Repairing Windows Error 0X80040610 in Outlook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-meaning-and-solution-of-winerror-0x80071a90/"><u>Decoding the Meaning & Solution of WinError 0X80071a90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-automated-software-fixes-windows-way/"><u>Delving Into Automated Software Fixes: Windows Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/desk-dilemmas-taming-the-pink-and-purple-on-your-screen/"><u>Desk Dilemmas: Taming the Pink & Purple on Your Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-superuser-in-terminal-a-step-by-step-guide/"><u>Enabling Superuser in Terminal: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-using-outlook-preview-in-windows-11/"><u>Essential Tips for Using Outlook Preview in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-making-windows-menus-less-obvious/"><u>Expert Tips: Making Windows Menus Less Obvious</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/face-off-frenzy-legendary-sj6-versus-yis-prodigy-4k-for-2024/"><u>Face-Off Frenzy  Legendary SJ6 Versus Yi's Prodigy 4K for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-absence-of-files-notification-on-win-11/"><u>Fixing Absence of Files Notification on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-responsive-volume-control-on-win-1011-pc/"><u>Fixing Responsive Volume Control on Win 10/11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-to-know-wintoys-your-intuitive-guide-to-an-underutilized-tool-in-windows/"><u>Getting to Know WinToys: Your Intuitive Guide to an Underutilized Tool in Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-100-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor 100 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-ccleaner-not-working-on-windows-10-and-11/"><u>How to Fix CCleaner Not Working on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-generate-a-group-policy-report-with-the-gpresult-command/"><u>How to Generate a Group Policy Report With the GPResult Command</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-view-and-clear-the-windows-11-activity-history/"><u>How to View and Clear the Windows 11 Activity History</u></a></li>
<li><a href="https://driver-install.techidaily.com/hyperx-audio-device-drivers-easy-updates-made-simple/"><u>HyperX Audio Device Drivers: Easy Updates Made Simple</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-affordable-pc-screen-grabber-selection-list/"><u>In 2024, Affordable PC Screen Grabber Selection List</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-mobile-video-editing-mastery-top-10-vlog-apps/"><u>In 2024, Mobile Video Editing Mastery Top 10 Vlog Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-windows-artistry-with-these-7-distinguished-drawing-tools/"><u>Masterful Windows Artistry with These 7 Distinguished Drawing Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/msstore-dilemma-resolving-windows-error-code-0x0-in-3-steps/"><u>MsStore Dilemma - Resolving Windows Error Code 0X0 in 3 Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mute-functionality-disabling-windows-11-tasks/"><u>Mute Functionality: Disabling Windows 11 Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-teams-screen-failures/"><u>Overcoming Teams Screen Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/power-saving-perplexities-the-tale-of-windows-standby/"><u>Power Saving Perplexities: The Tale of Windows' Standby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconnecting-disconnected-network-via-windows-settings/"><u>Reconnecting Disconnected Network via Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unconnect-error-for-windows-nvidia-applications/"><u>Removing Unconnect Error for Windows' Nvidia Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-the-0x80072746-email-failure-on-windows-pc/"><u>Resolving the 0X80072746 Email Failure on Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-disconnected-remote-resources-on-your-pc/"><u>Reviving Disconnected Remote Resources on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/selecting-and-styling-terminal-image/"><u>Selecting and Styling Terminal Image</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shed-light-on-dark-windows-11-desktops-tips-inside/"><u>Shed Light on Dark Windows 11 Desktops - Tips Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-amd-graphics-drivers-update-for-windows-11-pcs/"><u>Step-by-Step AMD Graphics Drivers Update for Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-and-fix-crashed-epic-games-launcher-window/"><u>Stop & Fix Crashed Epic Games Launcher Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-seven-pocket-friendly-tools-to-increase-windows-volume/"><u>Top Seven Pocket-Friendly Tools to Increase Windows Volume</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-sniptools-unresponsive-commands/"><u>Troubleshooting SnipTool's Unresponsive Commands</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unleash-high-performance-a-thorough-evaluation-of-the-netgear-nighthawk-rax120s-superior-speed-capabilities/"><u>Unleash High Performance: A Thorough Evaluation of the Netgear Nighthawk RAX120's Superior Speed Capabilities</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/unveiling-obs-screen-recorder-functionality-deeply/"><u>Unveiling OBS Screen Recorder Functionality Deeply</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-best-windows-photo-organizers-listed-here/"><u>Unveiling the Best Windows Photo Organizers Listed Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-ancient-pcs-for-modern-operations-using-windows-to-go-and-rufus/"><u>Upgrading Ancient PCs for Modern Operations: Using Windows To Go and Rufus</u></a></li>
</ul></div>
