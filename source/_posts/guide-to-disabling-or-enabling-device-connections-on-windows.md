---
title: Guide to Disabling or Enabling Device Connections on Windows
date: 2024-10-26T19:21:26.441Z
updated: 2024-11-01T18:10:09.422Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Disabling or Enabling Device Connections on Windows
excerpt: This Article Describes Guide to Disabling or Enabling Device Connections on Windows
keywords: Windows Connect Controls,Disable PC Connection,Enable Devices Windows,Manage Network Links,PC Device Connection Guide,Adjust Windows Connections,Windows Conn Settings Guide
thumbnail: https://thmb.techidaily.com/30c3f68025cf60445ca0af9503de0d05421151fac72dff09f39b3449e1fcd630.jpg
---

## Guide to Disabling or Enabling Device Connections on Windows

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
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

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-complete-razer-kiyo-webcam-overview/"><u>[New] In 2024, Complete Razer Kiyo Webcam Overview</u></a></li>
<li><a href="https://screen-capture.techidaily.com/does-active-presenter-8-outperform-its-rivals/"><u>Does Active Presenter 8 Outperform Its Rivals?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-your-photos-utilizing-luts-in-adobes-image-editor/"><u>Elevate Your Photos Utilizing LUTs in Adobe's Image Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-reboot-loop-into-bios-setup/"><u>Fixing Windows Reboot Loop Into BIOS Setup</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-realme-c53-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Realme C53 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-issues-with-windows-character-map-functionality/"><u>Overcoming Issues with Windows Character Map Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lack-of-hypervisor-in-windows-sandbox-environment/"><u>Resolving Lack of Hypervisor in Windows Sandbox Environment</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-gameplay-disruptions-fixing-life-is-strange-true-colors-crash-issues/"><u>Solving Gameplay Disruptions: Fixing Life Is Strange: True Colors [CRASH] Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remove-hyber-v-from-windows-11-pro/"><u>Steps to Remove Hyber-V From Windows 11 Pro</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-htc-u23-pro-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in HTC U23 Pro for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-fbm-potential-top-fixes-for-pc-users/"><u>Unlocking FBM Potential: Top Fixes for PC Users</u></a></li>
</ul></div>

