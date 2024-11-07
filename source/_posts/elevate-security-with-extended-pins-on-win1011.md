---
title: Elevate Security with Extended PINs on Win10/11
date: 2024-11-05T12:34:13.745Z
updated: 2024-11-07T01:29:13.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Security with Extended PINs on Win10/11
excerpt: This Article Describes Elevate Security with Extended PINs on Win10/11
keywords: Elevate Win10 Security,Extended PIN Windows 10,Secure Extended Pins,Enhanced Win11 Authentication,Advanced Win10 Safeguards,Strengthen Win10 Security,Protect with Extended Pins
thumbnail: https://thmb.techidaily.com/7677f4cd9df16c6a66672a56bd970deac980e4b074d81c3008e2f891a827245d.jpg
---

## Elevate Security with Extended PINs on Win10/11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.

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

3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-address-incompatible-facebook-videos-on-ios/"><u>[New] Address Incompatible Facebook Videos on iOS</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-step-by-step-guide-to-elevating-video-presence-through-thumbnails/"><u>[Updated] 2024 Approved Step-by-Step Guide to Elevating Video Presence Through Thumbnails</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-art-of-piecing-together-digital-images/"><u>2024 Approved The Art of Piecing Together Digital Images</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-8-digital-collage-crafting-software/"><u>2024 Approved TOP 8 Digital Collage Crafting Software</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtubes-beauty-titans-whos-leading/"><u>2024 Approved YouTube's Beauty Titans Who's Leading ?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-and-contrasting-win11-homes-vs-advanced-professional-editions/"><u>Comparing and Contrasting Win11: Homes Vs. Advanced Professional Editions</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/comprehensive-analysis-of-sea-techs-portable-usb-blu-ray-recorder-a-look-at-its-erratic-effectiveness/"><u>Comprehensive Analysis of Sea Tech's Portable USB Blu-Ray Recorder - A Look at Its Erratic Effectiveness</u></a></li>
<li><a href="https://tech-hub.techidaily.com/expert-advice-curtailing-chatgpts-conversation-logging/"><u>Expert Advice: Curtailing ChatGPT's Conversation Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-crash-overcoming-server-hiccups-on-windows-11/"><u>Fixing Microsoft Store Crash: Overcoming Server Hiccups on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-apple-calendar-on-windows-10-or-11/"><u>How to Use Apple Calendar on Windows 10 or 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-smooth-audio-transitions-2-methods-to-fade-in-and-out-in-fcp/"><u>New In 2024, Smooth Audio Transitions 2 Methods to Fade In and Out in FCP</u></a></li>
<li><a href="https://tech-revival.techidaily.com/new-to-ai-find-your-mentors-in-these-top-9-groups/"><u>New to AI? Find Your Mentors in These Top 9 Groups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-git-commands-with-github-desktop-on-windows-11/"><u>Optimizing Git Commands with GitHub Desktop on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pump-up-windows-pcs-for-seamless-high-performance-transcoding-workflows-by-tdarr/"><u>Pump Up Windows PCs for Seamless, High-Performance Transcoding Workflows by Tdarr</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-erase-the-blue-screen-with-error-740-in-winos/"><u>Quick Guide to Erase the Blue Screen with Error 740 in WINOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-colorful-volume-adjustment-on-windows-10/"><u>Reinstate Colorful Volume Adjustment on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-absent-drive-in-microsoft-os/"><u>Reinstating Absent Drive in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-maintain-an-operational-windows-notepad/"><u>Techniques to Maintain an Operational Windows Notepad</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-oppo-find-x7-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Oppo Find X7 Bypass FRP Tools for PC That Actually Work</u></a></li>
</ul></div>

