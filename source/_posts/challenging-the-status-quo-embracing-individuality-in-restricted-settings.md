---
title: "Challenging the Status Quo: Embracing Individuality in Restricted Settings"
date: 2024-08-16T01:44:33.132Z
updated: 2024-08-17T01:44:33.132Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Challenging the Status Quo: Embracing Individuality in Restricted Settings"
excerpt: "This Article Describes Challenging the Status Quo: Embracing Individuality in Restricted Settings"
keywords: Challenging Norms,Personal Identity,Breaking Barriers,Nonconformity Now,Self-Expression Freedom,Unique Behaviors,Individual Liberty
thumbnail: https://thmb.techidaily.com/2667ea34d1175640376556500cfb9591d15bfce3d67d6c1590ffd9f57da4dd02.jpg
---

## Challenging the Status Quo: Embracing Individuality in Restricted Settings

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

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
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-examining-the-effectiveness-of-iscreen-recording/"><u>[New] Examining the Effectiveness of iScreen Recording</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-realizing-your-cinematic-dreams-the-art-of-perfect-sound-in-videos/"><u>[New] In 2024, Realizing Your Cinematic Dreams  The Art of Perfect Sound in Videos</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-ultimate-guide-to-tiktoks-most-engaging-rap-songs/"><u>[New] In 2024, The Ultimate Guide to TikTok's Most Engaging Rap Songs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-invisible-vids-on-social-reveal-the-top-12-techniques-to-restore-appearance-in-23/"><u>[New] Invisible Vids on Social? Reveal the Top 12 Techniques to Restore Appearance in '23</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-next-level-gameplay-leading-monitors-for-ps5-with-hdmi-21-features-for-2024/"><u>[New] Next-Level Gameplay  Leading Monitors for PS5 with HDMI 2.1 Features for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-methods-for-restoring-full-display-in-youtube-videos/"><u>[Updated] 2024 Approved  Methods for Restoring Full Display in YouTube Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-enchanting-eloquence-exploring-the-top-8-storytelling-haunts-for-2024/"><u>[Updated] Enchanting Eloquence  Exploring the Top 8 Storytelling Haunts for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-keyword-optimization-for-higher-youtube-viewership/"><u>[Updated] In 2024, Keyword Optimization for Higher YouTube Viewership</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-podcasters-playground-unleashing-full-potential-in-video-and-audio-recording-on-zoom/"><u>[Updated] In 2024, Podcaster's Playground  Unleashing Full Potential in Video and Audio Recording on Zoom</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-splitscreen-designer/"><u>[Updated] SplitScreen Designer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-steps-to-ensure-obs-captures-sound-effectively/"><u>2024 Approved  Steps to Ensure OBS Captures Sound Effectively</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-realme-10t-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Realme 10T 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-disabled-lock-screen-timeout-windows/"><u>Addressing Disabled Lock Screen Timeout Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-the-screen-nintendos-next-step/"><u>Beyond the Screen - Nintendo's Next Step?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/browsing-bygone-tales-in-the-facebook-universe-with-devices/"><u>Browsing Bygone Tales in the Facebook Universe with Devices</u></a></li>
<li><a href="https://app-tips.techidaily.com/1723620191401-comprehensive-evaluation-of-picplaypost-revolutionizing-digital-content-with-advanced-editing-features-for-videos-collages-and-more/"><u>Comprehensive Evaluation of PicPlayPost: Revolutionizing Digital Content with Advanced Editing Features for Videos, Collages, and More!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crucial-cross-platform-tools-windows-meets-android/"><u>Crucial Cross-Platform Tools: Windows Meets Android</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-fixes-for-your-intel-video-driver-glitches-on-windows-11-8-and-7/"><u>Easy Fixes for Your Intel Video Driver Glitches on Windows 11, 8 and 7!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-code-0x0000004e-on-windows-os/"><u>Eliminating Code 0X0000004E on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-non-crashy-windows-user-experience/"><u>Ensure Non-Crashy Windows User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-microsoft-store-fault-code-0x80072efd/"><u>Eradicating Microsoft Store Fault Code 0X80072EFD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-onedrive-symbol-from-windows-11-filesystem/"><u>Eradicating the OneDrive Symbol From Windows 11 Filesystem</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-youtube-playback-speed-delays-in-chrome/"><u>Fixing YouTube Playback Speed Delays in Chrome</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-lava-storm-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Lava Storm 5G Devices | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/free-video-editing-software-round-up-choose-from-7-options-for-2024/"><u>Free Video Editing Software Round-Up  Choose From 7 Options for 2024</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-xiaomi-14-pro-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-obs-studio-not-launching-on-windows/"><u>How to Fix OBS Studio Not Launching on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-moto-g84-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Moto G84 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-windows-users-from-changing-the-date-and-time/"><u>How to Stop Windows Users From Changing the Date and Time</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-boosting-webcam-quality-with-ease-and-precision/"><u>In 2024, Boosting WebCam Quality with Ease and Precision</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-crafting-memorable-tweets-video-integration/"><u>In 2024, Crafting Memorable Tweets  Video Integration</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-itel-a70-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Itel A70? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/learn-the-process-of-capturing-your-watched-youtube-content-without-spending/"><u>Learn the Process of Capturing Your Watched YouTube Content Without Spending</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-luminance-adjustments-on-your-win11-device/"><u>Leveraging Luminance Adjustments on Your Win11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-netconfig-a-guide-to-connectivity/"><u>Mastering Window's NetConfig: A Guide to Connectivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-default-search-settings/"><u>Optimizing Windows 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-operating-environment-for-device-interfaces/"><u>Optimizing Windows Operating Environment for Device Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-resolution-glitches/"><u>Overcoming Common Windows Resolution Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-file-sync-problem-in-windows-environment/"><u>Overcoming Steam File Sync Problem in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-epic-game-launcher-failures-on-windows-os/"><u>Preventing Epic Game Launcher Failures on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-safety-invest-heavily-in-research-to-develop-advanced-safety-features-that-reduce-potential-risks-associated-with-drone-operations-such-as-collis31/"><u>Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-onedrive-login-failure-x8004dec5-windows-issue/"><u>Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-your-muted-windows-start-button-icon/"><u>Resurrecting Your Muted Windows Start Button Icon</u></a></li>
<li><a href="https://sound-issues.techidaily.com/reviving-sound-solutions-for-a-non-responsive-voice-mic/"><u>Reviving Sound: Solutions for a Non-Responsive Voice Mic</u></a></li>
<li><a href="https://techidaily.com/solutions-to-restore-deleted-files-from-itel-p55-5g-by-fonelab-android-recover-data/"><u>Solutions to restore deleted files from Itel P55 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-current-windows-pass-error-in-win11win11/"><u>Solving Current Windows Pass Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-organized-with-automatic-files-deletion-in-win11/"><u>Stay Organized with Automatic Files Deletion in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-creating-self-extracting-fx-in-win11/"><u>Step-by-Step: Creating Self-Extracting FX in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-spontaneous-activation-of-file-explorer/"><u>Stopping Spontaneous Activation of File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-halt-moving-of-apps-within-the-windows-ui/"><u>Techniques to Halt Moving of Apps Within the Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-banishing-the-persistent-pink-error-on-windows/"><u>The Ultimate Guide to Banishing the Persistent Pink Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-stopping-unwanted-disk-filling/"><u>The Ultimate Guide to Stopping Unwanted Disk Filling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-soundcard-irq-errors-on-pc/"><u>Troubleshooting Soundcard IRQ Errors on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-windows-headset-microphone-blockage/"><u>Unblocking Windows Headset Microphone Blockage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-role-of-windows-print-management-interface/"><u>Understanding the Role of Windows Print Management Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-the-power-of-hyper-v-in-windows-11-homes-with-this-guide/"><u>Unleash the Power of Hyper-V in Windows 11 Homes with This Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unseen-approaches-to-bypass-online-educational-content-for-2024/"><u>Unseen Approaches to Bypass Online Educational Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/whats-the-difference-between-the-c-drive-and-the-d-drive/"><u>What's the Difference Between the C: Drive and the D: Drive?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719334227097-windows-transcends-platforms-iphoneipadmacpc-compatibility-announced/"><u>Windows Transcends Platforms: IPhone/iPad/Mac/PC Compatibility Announced!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-password-safety-tools-for-windows-11-users/"><u>Winning Password Safety Tools for Windows 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-impact-on-linux-desktop-usage/"><u>WSL's Impact on Linux Desktop Usage</u></a></li>
</ul></div>
