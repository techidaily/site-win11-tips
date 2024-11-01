---
title: Fixing Media Errors on Windows Platform
date: 2024-10-29T17:31:21.993Z
updated: 2024-11-01T18:31:21.716Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Media Errors on Windows Platform
excerpt: This Article Describes Fixing Media Errors on Windows Platform
keywords: Windows Media Fix Guide,WinMediaError Resolution,Windows Media Correction,Media Errors in Windows,Windows Repair Media,Tackle Media Issues WIN,WIN Error Media Solution
thumbnail: https://thmb.techidaily.com/cf1ae4b3cdb5debdafe3b02949517a45048f6142dd7f5f842e985181e8a620c0.jpg
---

## Fixing Media Errors on Windows Platform

 Windows Media Player is old software, but many users still utilize it for playing music and video. However, some WMP users have reported a “server execution failed” error message pops up when they try to play media files in Windows Media Player. Consequently, users can’t listen to music or watch videos in Windows Media Player.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Try Restarting the Windows Media Player Process

 Some WMP users have confirmed that ending the Windows Media Player process in Task Manager can fix the “Server execution failed” error. That’s a very simple potential resolution that amounts to little more than restarting the software, albeit via Task Manager. You can end the Windows Media Player process in Task Manager like this:

1. Open Task Manager by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** key combination for launching that utility.
2. Click **Processes** to view that tab if it doesn’t open with Task Manager.
3. Select the **Windows Media Player** process in Task Manager.  
![The Processes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-process-tab.jpg)
4. Press the **End task** button to terminate the selected WMP process.
5. Then exit Task Manager and open Windows Media Player to see if the error persists.

## 2\. Run the Video Playback Troubleshooter

 Windows 11 and 10 both include a Video Playback troubleshooter that might be useful for resolving the “Server execution failed” error. That’s a troubleshooter for resolving video playback issues, and some users have said it helped them fix this issue. These are the steps for running the Video Playback troubleshooting tool:

1. First, [bring up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) the quick way by holding the **Windows** logo key and pressing **I**.
2. Then select **System** and the **Troubleshoot** navigation option included within that tab.
3. Click **Other trouble-shooters** to proceed to a list of troubleshooting utilities.
4. Open the Video Playback troubleshooter by clicking its **Run** option.  
![The Run button for the Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-video-playback-troubleshooter.jpg)
5. Select **I want to continue** **with this troubleshooter** in Video Playback.  
![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/video-playback-troubleshooter.jpg)
6. Apply any possible fixes the Video Playback troubleshooter offers.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To utilize the same Video Playback troubleshooter in Windows 10, select the Update & Security settings category. Then you can reach the Video Playback repair utility by selecting **Troubleshoo**t > **Additional troubleshooters**. Select Video Playback and click **Run the troubleshooter**.

## 3\. Register DLL Files

 Registering the jscript and vbscript DLL files is a widely confirmed fix for the “Server execution failed” error. You can register those files by executing a couple of simple regsvr commands like this:

1. [Open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=In%20the%20Run%20dialog%20box,Command%20Prompt%20with%20administrative%20privileges.) to utilize that app with elevated privileges.
2. Then input this regsvr command and hit **Enter**: regsvr32 jscript.dll  
![The regsvr32 jscript.dll](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsvr32-command.jpg)
3. Click **OK** on RegSvr32 confirmation box.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Next, execute this command to register the VBScript file: regsvr32 vbscript.dll  
![The regsvr32 vbscript.dll command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsver32-vbscript-command.jpg)
5. Then select **OK** again.
6. Go to your Start menu and select **Restart** from there.

## 4\. Disable the Windows Media Player Network Sharing Service

 Windows Media Player Network Sharing is a service required for sharing WMP libraries via the UPnP protocol. That’s not a service needed for playing media files on one PC, and some WMP users have fixed the “Server execution failed” error by disabling that service. This is how you can disable that service:

1. Click on the taskbar’s magnifying glass icon or search box.
2. Enter a **services** keyword to find the app that matches that search phrase.
3. Run Services by clicking that app within your search results.
4. Double-click **Windows Media Player Network Sharing** to access that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-window2.jpg)
5. Select the **Disabled** option on the **Startup** menu.  
![The Disabled option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-disabled-option.jpg)
6. Click **Stop** just below the **Startup type** menu.
7. Select **Apply** \> **OK** to save settings and exit the Windows Media Player Network Sharing Service Properties window.

## 5\. Apply Full Access to Your Local User Folder

 Another possibility is that Windows Media Player can’t access media files in your user folder because of permission changes. Re-establishing full access to your local user folder will resolve such an issue. These are the steps for applying full access to a user folder:

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and go to the following folder path:  
`C:\Users`
2. Right-click your user folder that includes media files and select **Properties**.  
![The Properties context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option.jpg)
3. Select **Security** on the properties window.
4. Click **Advanced** to bring up more security settings.
5. Next, click the **Change** option for the owner.  
![The Advanced Security Settings for Users window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/advanced-security-window.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click **Advanced** \> **Find now** on the Select User or Group window.
2. Then choose your user account from there and click **OK** twice.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/select-user-or-group.jpg)
3. Press **Add** on the Advanced Security Settings window.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click **Select a Principal** to bring up a user group selection window.
5. Select your user account again, as covered in steps six and seven.
6. Click the **Full control** checkbox to select that basic permission setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-full-control-option.jpg)
7. Select **OK** on the Permissions Entry window and others open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Disable Third-Party Startup Items

 Disabling all third-party startup items (apps and services) is called clean booting. The purpose of clean booting is to prevent software conflicts by stopping third-party background programs and services from starting automatically. This troubleshooting method is recommended to check if a third-party app or service conflict with Windows Media Player is causing the “Server execution failed” error on your PC.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-tab-in-msconfig.jpg)

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our guide to [clean-booting Windows](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to apply this potential fix by disabling third-party apps and services with Task Manager and MSConfig. When you’ve done that, you’ll need to restart your PC open for a clean boot to take effect. Then open Windows Media Player and try playing some media files again.

## 7\. Reinstall Windows Media Player

 Reinstalling Windows Media Player is a last resort potential resolution to try if none of the above works for you. However, you can’t reinstall WMP like regular software by uninstalling with Programs and Features and downloading a setup file. Instead, you’ll need to disable and re-enable WMP via Windows Features as follows:

1. Bring up the Windows uninstaller tool with a method within this article about [how to open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/).
2. Then click **Turn Windows features on or off** to bring up a utility for enabling/disabling features.  
![Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/programs-and-features-window.jpg)
3. Double-click Media Features to extend it.
4. Deselect the **Windows Media Player** checkbox and select **Yes**.  
![The Windows Media Player checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-windows-media-player-checkbox.jpg)
5. Click **OK** to disable Windows Media Player.
6. Restart Windows after disabling WMP.
7. Then reopen the Windows Features window.
8. Select the **Windows Media Player** checkbox.
9. Click **OK** to reinstall the software.

## Enjoy Your Music and Videos in Windows Media Player

 Many WMP users have fixed the “Server execution failed” error with the potential solutions outlined in this guide. So, don’t ditch Windows Media Player until you’ve at least tried applying most of those potential fixes. One will probably get the “Server execution failed” WMP error fixed on your Windows PC. Then you can enjoy all the music and videos in your Windows Media Player playlists again.

 Nevertheless, there are still plenty of freely available alternatives to Windows Media Player you can always consider. Software like VLC, 5KPlayer, and KMPlayer are among the best freeware media players for Windows.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-eye-catching-youtube-most-followed-channels/"><u>[Updated] In 2024, Eye-Catching YouTube Most Followed Channels</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-how-to-amplify-in-game-voices-naturally-step-by-step-process-for-free-fire-players/"><u>[Updated] In 2024, How to Amplify In-Game Voices Naturally Step-by-Step Process for Free Fire Players</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-maximizing-viewership-igtv-video-scaling-hacks/"><u>2024 Approved Maximizing Viewership IGTV Video Scaling Hacks</u></a></li>
<li><a href="https://win-able.techidaily.com/1726029536995-dvd/"><u>容易な手順でDVDのコピー複製をコピーガード無しで実行</u></a></li>
<li><a href="https://extra-resources.techidaily.com/amplify-your-youtube-audience-three-livestream-strategies/"><u>Amplify Your YouTube Audience Three Livestream Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-codes-of-user-identities-in-win11/"><u>Deciphering the Codes of User Identities in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-methods-to-diminish-desktop-window-managers-power-use/"><u>Effective Methods to Diminish Desktop Window Manager's Power Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhanced-efficiency-embrace-windows-11-tiny/"><u>Enhanced Efficiency: Embrace Windows 11 Tiny</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-low-volume-complaints-in-wireless-audio-equipment/"><u>Fixing Low-Volume Complaints in Wireless Audio Equipment</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-hp-photosmart-7520-printer-driver-here-download-now/"><u>Get Your HP Photosmart 7520 Printer Driver Here - Download Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-acquainted-with-bluescreenview-a-quick-primer/"><u>Getting Acquainted with BlueScreenView: A Quick Primer</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-iphone-15-plus-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your iPhone 15 Plus on MetroPCS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/motorola-moto-g24-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Moto G24 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-visuals-in-application-guard-for-edge-os/"><u>Optimizing Visuals in Application Guard for Edge OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/precise-methods-for-creating-impactful-client-spots-on-film-for-2024/"><u>Precise Methods for Creating Impactful Client Spots on Film for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-fixes-resolving-issues-with-your-lenovo-fingerprint-sensor/"><u>Quick Fixes: Resolving Issues with Your Lenovo Fingerprint Sensor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-process-for-running-sfc-on-windows-pcs/"><u>Step-by-Step Process for Running SFC on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-updater-0x8024a205-malfunction-on-pcs/"><u>Tackling Updater 0X8024a205 Malfunction on PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    