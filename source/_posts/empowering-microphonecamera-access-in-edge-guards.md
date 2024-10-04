---
title: Empowering Microphone/Camera Access in Edge Guards
date: 2024-09-27T20:55:35.699Z
updated: 2024-10-04T01:12:04.998Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Empowering Microphone/Camera Access in Edge Guards
excerpt: This Article Describes Empowering Microphone/Camera Access in Edge Guards
keywords: Edge Guard Access,Mic Camera Enhance,Edge Security,Audio-Visual Control,Mobile Device Accessibility,Permission Microphone,Edge Guards Management
thumbnail: https://thmb.techidaily.com/876b4cf01691e6a76beb54576565375ccfec6aaf58375585e8d7cab9fd27ade4.jpg
---

## Empowering Microphone/Camera Access in Edge Guards

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068432/7443" target="_top" id="2068432">
  <img src="//a.impactradius-go.com/display-ad/7443-2068432" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068432/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you[create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see[how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902319/19272" target="_top" id="1902319">
  <img src="//a.impactradius-go.com/display-ad/19272-1902319" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902319/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-discover-how-to-get-sounds-from-twitter-vids/"><u>[New] 2024 Approved Discover How to Get Sounds From Twitter Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-overcoming-virtual-reality-nausea/"><u>[New] 2024 Approved Overcoming Virtual Reality Nausea</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-examining-video-comments-on-youtube-for-2024/"><u>[Updated] Examining Video Comments on YouTube for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/best-no-cost-sms-tools-compatible-with-ios-devices/"><u>Best No-Cost SMS Tools Compatible with iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-error-0xca00a009-from-windows-update-logs/"><u>Clearing Error 0xCA00A009 From Windows Update Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-your-pcs-intel-processor-gen-through-windows/"><u>Deciphering Your PC's Intel Processor Gen Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-fixes-via-hotkey-configurations-in-w1011/"><u>Efficient System Fixes via Hotkey Configurations in W10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-solving-the-problem-of-missing-windows-drive-letters/"><u>Explaining and Solving The Problem Of Missing Windows Drive Letters</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-from-iphone-13-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code From iPhone 13 in the Best Ways</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-15-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone 15 without Apple Account</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-sharestream-downloader-fb-edition/"><u>In 2024, ShareStream Downloader, FB Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-high-gpu-activity-in-windows-desktop-window/"><u>Managing High GPU Activity in Windows Desktop Window</u></a></li>
<li><a href="https://fox-sys.techidaily.com/mastering-the-art-of-screenshots-on-asus-zenphone-devices-zenfone-2-4-5-and/"><u>Mastering the Art of Screenshots on ASUS ZenPhone Devices (Zenfone 2, 4, 5 & 지)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-your-pathway-to-authenticity-with-instagrams-verification-badge/"><u>Mastering Your Pathway to Authenticity with Instagram's Verification Badge</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80242016-error-in-windows-updates/"><u>Overcoming 0X80242016 Error in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-pc-resetting-windows-11-applications/"><u>Refreshing Your PC: Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketchmasters-roundup-top-7-drawing-tools-for-windows/"><u>SketchMasters Roundup: Top 7 Drawing Tools for Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solution-steps-for-restoring-sound-functionality-in-chromecast-devices/"><u>Solution Steps for Restoring Sound Functionality in Chromecast Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-preventing-unwanted-command-window-activation/"><u>Tips for Preventing Unwanted Command Window Activation</u></a></li>
</ul></div>

