---
title: Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows
date: 2024-10-01T17:22:36.649Z
updated: 2024-10-03T16:51:34.786Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows
excerpt: This Article Describes Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows
keywords: OneDrive Sign-In Fix,DEC5 Error Resolution,WinSignInTroubleshoot,OneDrive Credential Issue,Windows OS Cure,Microsoft Account Access,ZeroErrorCorrection
thumbnail: https://thmb.techidaily.com/1621022f15bae9f90515e95f15edd431dd0fad0e7e4a31a614efb85ef8dac6ad.JPG
---

## Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows

 Microsoft's cloud storage service OneDrive simplifies file management on Windows. However, you might experience issues when signing in to OneDrive, like the 0x8004dec5 error. This article will guide you on how to resolve OneDrive sign-in error 0x8004dec5 specifically on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Your Internet Connection

 If you’re having trouble signing in to OneDrive, first [check your internet connection](http://www.makeuseof.com/windows-check-wifi-network-strength/). Slow or spotty internet causes sign-in problems. So, check your connection speed and make sure it’s strong enough for OneDrive. If necessary, reset your router or modem to restore the connection.

 If your internet connection is working, restart your computer and sign in to OneDrive again. This simple step fixes minor errors in the operating system that may cause the sign-in issue.

## 2\. Run the Network Troubleshooter

 If your internet connection is stable, but you’re still having OneDrive sign-in problems, you can run the Internet Connections Troubleshooter. This diagnosis tool scans for network problems and repairs any issues it finds.

 To run the Internet Connection Troubleshooter, follow these steps:

1. Right-click on Start and select **Run** from the menu list.  
![Open Internet Connections](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/open-internet-connections.jpg)
2. In the dialog box, type the following command and click **OK**.  

`msdt.exe -id NetworkDiagnosticsWeb`
3. Click **Advanced** and check **Apply repairs automatically**.  
![Run the Internet Connections troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-the-internet-connections-troubleshooter.jpg)
4. Now click **Next** and follow the on-screen instructions to finish the troubleshooting process.

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once it’s done, sign into OneDrive and see if the error is fixed. If not, try the next solution.

## 3\. Tweak the Registry Editor

 If the problem persists, remove cached Office account identities from the registry. This requires changing a few settings in the Windows registry which is a database of your operating system, so proceed with caution.

 If you’re not sure what you’re doing, have an experienced technician make the changes for you. To avoid damaging your system, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making these changes.

1. Press **Win + R** on your keyboard to open the Run dialog.
2. Type **regedit** in the search box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to proceed.
4. In the Registry Editor window, navigate to the path as follows:  
`HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity`
5. Right-click on the **Identity** folder and select **Delete** from the menu.  
![Delete Identity Folder From Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-identity-folder-from-registry.jpg)
6. Click **Yes** when asked to confirm your action.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Close Registry Editor and restart your computer.

 Now try signing in to OneDrive again. The sign-in error should now be resolved.

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove Cached Credentials Folders

 If you're not comfortable tweaking the registry editor, remove cached Office account identities using Windows Explorer. Here's how to do it.

1. Press **Win + E** to open File Explorer.
2. In the File Explorer window, navigate to the following location:  
`C:\Users\Username\AppData\Local\Microsoft\IdentityCache`
3. Press **Ctrl + A** to select all files and delete them.  
![Clear Identity Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/clear-identity-folder.jpg)
4. Now navigate to this location, and replace **Username** with your own Windows username.:  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`C:\Users\Username\AppData\Local\Microsoft\OneAuth  
`
5. Select all the files here and hit the **Delete** button.

 Once you've removed all cached Office account identities, restart your computer and try signing in to OneDrive again.

## 5\. Unlink and Re-Link Your OneDrive Account

 If you have a valid OneDrive account, but still can’t sign in due to the 0x8004dec5 error code, unlink and relink your account. This will reset the connection and fix the problem.

 To unlink OneDrive, follow these steps.

1. Go to the right side of the taskbar and click on the **OneDrive** icon.
2. Click **Help & Settings** (the gear icon) and select **Settings** from the menu list.
3. In the Settings window, go to the **Account** tab.
4. Under your OneDrive account, click **Unlink this PC**.  
![Unlink OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive.jpg)
5. Click **Unlink account** to confirm your action.  
![Unlink OneDrive Account on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/unlink-onedrive-account-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After unlinking the account, you now need to relink it. To do that, open the OneDrive Settings window again and click **Add an Account**. Enter your OneDrive credentials and sign in to the account.

 When it’s done, close the Settings window. Now open OneDrive and sign in with your new account credentials. The sign-in error should now be resolved.

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset the OneDrive App

 In some cases, resetting the OneDrive application solves the sign-in errors. This restores the app to its default settings and removes any corrupted system files.

 To reset the OneDrive app, follow these steps.

1. Press **Win + X** on your keyboard and select **Installed apps** from the list.
2. In the list of installed apps, scroll down to **OneDrive**.
3. Click the three dots and select the **Advanced options**.
4. Scroll down to the **Reset** section and click on the **Reset** button.  
![Reset OneDrive app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-onedrive-app.jpg)
5. Click **Reset** again to confirm your action.

 After the reset, try signing in to OneDrive and seeing if error 0x8004dec5 is fixed.

## 7\. Get the Latest Windows Updates

 Microsoft releases new patches that improve Windows performance. If your computer didn't receive the latest updates, it may cause OneDrive sign-in errors. To fix this problem, install the pending Windows updates and try signing in to OneDrive again.

 To download and install the latest Windows updates, use these steps.

1. Press **Win + I** on your keyboard to open the Settings window (see our guide on [how to open the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/)).
2. From the left sidebar, click on the **Windows Update** tab.
3. Now click **Check for updates** and wait while Windows checks for available updates.  
![Check for updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/check-for-updates.jpg)
4. If you find new updates, download and install them.

 After performing the above action, restart your computer. Now try signing in to OneDrive and seeing if the error is fixed.

## 8\. Uninstall and Reinstall OneDrive

 If the error persists even after trying the above solutions, it's likely that the OneDrive app is malfunctioning. In that case, reinstall the application. It fixes corrupted files and solves sign-in issues. Here's how to do it.

1. [Open Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/).
2. Set the View by option to **Category**, then click **Programs** \> **Uninstall a program**.
3. Find **OneDrive** in the list of installed programs and click **Uninstall**.  
![Uninstall OneDrive-2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-onedrive-2.jpg)
4. If you get a confirmation prompt, click **Yes**.

 Now follow the instructions to complete the process. After that, [visit Microsoft's official website](https://www.microsoft.com/en-us/microsoft-365/onedrive/download?) to download and install OneDrive.

## Fixing OneDrive's 0x8004dec5 Sign In Error

 Following the steps mentioned above should resolve the 0x8004dec5 OneDrive sign-in error. Corrupt files, outdated Windows versions, or compatibility issues usually cause it. A basic troubleshooting step would be to restart your computer and reset the OneDrive app. If that doesn't fix it, unlink and relink your account, or reinstall OneDrive.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-affordable-mcb-theme-images-for-channels/"><u>[New] In 2024, Affordable MCB Theme Images for Channels</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-eliminating-obstacles-to-successful-srt-premiere-export/"><u>[Updated] Eliminating Obstacles to Successful SRT Premiere Export</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-recording-sims-4-games-professionally/"><u>[Updated] In 2024, Recording Sims 4 Games Professionally</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pairing-podcast-with-picture/"><u>2024 Approved Pairing Podcast with Picture</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-admin-restrictions-from-windows-security-error/"><u>Clearing Admin Restrictions From Windows Security Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodging-the-hurdle-of-microsoft-store-error-0x80072efd-on-windows-devices/"><u>Dodging the Hurdle of Microsoft Store Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-mend-d3dx939dll-gap-on-windows-11/"><u>How to Mend D3DX9_39.dll Gap on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-itel-a60-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Itel A60 | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/installing-official-drivers-for-your-amd-ryzen-processor/"><u>Installing Official Drivers for Your AMD Ryzen Processor</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-preservation-adding-dates-to-photos-with-ease-for-2024/"><u>Precision Preservation Adding Dates to Photos with Ease for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-tricks-navigating-through-winerror-in-oculus-setup-for-ws11ws10/"><u>Proven Tricks: Navigating Through WinError in Oculus Setup for WS11/WS10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-windows-11s-default-touch-interface-positioning/"><u>Redefining Windows 11'S Default Touch Interface Positioning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-windows-error-code-0xc0000001-instances/"><u>Remedy for Windows Error Code 0XC0000001 Instances</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-your-mpow-mic-expert-windows-tweaks-and-solutions-for-common-problems/"><u>Reviving Your MPOW Mic - Expert Windows Tweaks and Solutions for Common Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-desktop-image-save-path-in-windows-11/"><u>Tracking Desktop Image Save-Path in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-common-windows-app-glitches-7-fixes/"><u>Troubleshooting Common Windows App Glitches: 7 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-to-a-responsive-esc-key-in-windows-systems/"><u>Unlock the Secrets to a Responsive Esc Key in Windows Systems</u></a></li>
</ul></div>

