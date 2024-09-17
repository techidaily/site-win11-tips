---
title: Empowering Microphone/Camera Access in Edge Guards
date: 2024-09-09T21:11:26.467Z
updated: 2024-09-16T19:46:39.093Z
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
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-startups-discovering-the-best-15-video-intros/"><u>[Updated] In 2024, Captivating Startups Discovering the Best 15 Video Intros</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-sound-clarity-in-media-paid-vs-free-software-solutions/"><u>[Updated] Sound Clarity in Media - Paid Vs. Free Software Solutions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-unleashing-youtube-talent-the-best-themes-for-channel-growth/"><u>[Updated] Unleashing YouTube Talent The Best Themes for Channel Growth</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-lava-blaze-2-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Lava Blaze 2 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-optimal-efficiency-nircmd-tips-for-mastering-windows-11/"><u>Achieve Optimal Efficiency: NirCmd Tips for Mastering Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-initial-display-of-task-manager-in-windows-11/"><u>Customizing Initial Display of Task Manager in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-samsung-galaxy-a14-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Samsung Galaxy A14 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premiere-pros-finest-tools-free-and-exceptional-quality/"><u>In 2024, Premiere Pro's Finest Tools - Free & Exceptional Quality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installation-guide-to-dolby-atmos-for-pc-users/"><u>Installation Guide to Dolby Atmos for PC Users</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-tecno-spark-10-4g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Tecno Spark 10 4G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-non-functional-microsoft-store-in-windows-11/"><u>Quick Fix for Non-Functional Microsoft Store in Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

