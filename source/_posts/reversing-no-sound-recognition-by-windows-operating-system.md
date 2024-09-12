---
title: Reversing No Sound Recognition by Windows Operating System
date: 2024-09-11T01:28:36.721Z
updated: 2024-09-12T01:28:36.721Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing No Sound Recognition by Windows Operating System
excerpt: This Article Describes Reversing No Sound Recognition by Windows Operating System
keywords: Windows NoSound Fix,Recognize Audio Issue,WinOS Sound Troubleshoot,Silent Speakers on WinOS,Restore Sound Functionality,Correcting WIN OS NoAudio,Reverse WinOS Sound Loss
thumbnail: https://thmb.techidaily.com/7f531620a49852bbff7e687b5f3193b68bdfdcb0db935514f90e93325010d261.jpg
---

## Reversing No Sound Recognition by Windows Operating System

 Sometimes, you may notice a red X on the sound icon on the Windows taskbar. If you hover the cursor over it, it shows a no speaker, or headphones are plugged in error. This error can occur due to issues with the audio driver or Windows audio services.

 To fix the error, run the built-in audio troubleshooter that can find and fix common audio issues with the sound device. If not, you can perform an audio driver rollback or manually reinstall the audio driver to restore your system's audio.

 Here are a few troubleshooting steps to help you fix the no speaker or headphones are plugged in error on Windows.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Run the Windows Audio Troubleshooter

 You can troubleshoot sound problems on Windows using the built-in audio troubleshooter. It scans your Windows system for common audio issues and tries to fix them automatically.

To run the troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .
3. Next, click on**Other** **troubleshooters** .  
![Windows 11 troubleshoot other troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-troubleshoot-other-troubleshooter.jpg)
4. Click the**Run** button for**Playing Audio** . It will check your audio service status and prompt you to select your audio device.  




<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)
5. Select your device speaker and click**Next** .
6. Click**NO** ,**Do not open Audio Enhancements** in the**Turn off Sound Effects and Enhancements** dialog.
7. Apply any recommended fixes and check for any improvements.

 If the troubleshooter left a good impression on you, check out our[guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Perform an Audio Device Driver Rollback

 If a Windows or driver update has messed up your audio device, you can perform a driver rollback to reinstall the last known good driver. You can use the Device Manager to[roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 To roll back an audio device driver, follow our guide on[how to roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . You'll likely find your audio drivers in the**Sound, video, and game controllers** section of Device Manager.

## 3\. Add Network Service and Local Services to the Local Administrator Group

 Another way to fix this error is to add**Network service** and**Local Services** to the Local Administrator Group. Network Service and Local Service are predefined accounts part of the service control manager. Adding these accounts to the Local Administrator Group should help you fix the sound problem on your Windows PC.

 Note that Local Users and Groups is not available on the Windows Home edition. Home users, however, can add Network Service and Local Services to the local administrator group using Command Prompt.

 To add Network Service and Local Services to the Local Administrator Group using Local Users and Groups:

1. Press**Win + X** to open the**WinX** **Menu** .
2. Click on**Computer Management.**
3. In**Computer Management** , click on**Local User and Groups.**  
![computer management windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/computer-management-windows-11.jpg)
4. In the right pane, double-click on**Groups** to view all the local accounts.  
![local users and groups administrator properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/local-users-and-groups-administrator-properties.jpg)
5. Select and right-click on the**Administrators** account and select**Properties** .  
![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)

1. Click the**Add** button in the**Administrator Properties** dialog.
2. ![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)
3. Next, type**network service** and click**Check Names** . It should change the object name to**NETWORK SERVICE.**  




<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![add network service local administrator group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group.jpg)
4. Click**OK** to add network service to the local user group.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. In the**Administrator Properties** dialog, you'll see**NT Authority\\Network Service added as the member.**
6. Click the**Add** button again and repeat the steps to add**Local Services** to the group as well.
7. Once done, click**Apply** and**OK** to save the changes.

 If you use the Windows Home edition, you can use Command Prompt to add Local Network and Local Services to the local administrator group. Here's how to do it.

![add network service local administrator group command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group-command-prompt.jpg)

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following to add "local service" to the Local Group Administrator:  
`net localgroup Administrators /add localservice`
4. Next, type the following command to add "network service" to the Local Group Administrator account:  
`net localgroup Administrators /add networkservice`
5. If both the commands are executed successfully, type**exit** and press**Enter** to close Command Prompt.
6. Restart your PC and check if the error is resolved.

## 4\. Uninstall the Audio Device and Driver

 Temporary glitches with the audio device driver can cause this error on Windows. To fix the issue, uninstall the audio device and the associated driver from Device Manager. After the restart, Windows will automatically reinstall the driver to resolve the issue.

To uninstall an audio device:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Device Manager** from the context menu.
3. In Device Manager, expand the**Sound, video, and game controllers** section.
4. Right-click on your audio device, like**Realtek** **Audio** .  
![uninstall audio device device manager 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager-1.jpg)
5. Select**Attempt to remove the driver for this device** option in the**Uninstall Device** dialog.  
![uninstall audio device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager.jpg)
6. Click**Uninstall** to remove the device.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Once uninstalled, restart your PC. Windows will automatically install the necessary drivers for your audio device.

 If the issue persists, manually reinstall the audio device driver from the manufacturer.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Manually Reinstall the Audio Device Driver

 If the automatic reinstall doesn't work, check if your computer manufacturer or the audio device OEM has a stable driver version available. On a laptop, visit your computer manufacturer's website and download the latest audio drivers. On a desktop, you can download the latest drivers for your sound card from the manufacturer's website.

 Alternatively, you can also manually reinstall the existing drivers for your audio device. Check out[how to update Windows, Apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) for more information.

 If the issue persists, change the device installation settings and then reinstall the driver. To change device installation settings:

![device installation settings windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/device-installation-settings-windows.jpg)

1. Press the**Win** key, and type**device installation settings.**
2. Next, click on**Change device installation settings** from the search result.
3. Select the**No (your device might not work as expected)** option in the**Device installation settings** dialog.
4. Click**Save Changes** . Click**Yes** if prompted by**User Account Control.**

 With the automatic driver download disabled, reinstall the existing driver to fix the no audio issue.





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Fixing the "No Speaker or Headphones Are Plugged In" Error

 The error often occurs due to a bad driver update. To fix it, you can perform a rollback or manually reinstall the audio device driver. In addition, try to update the audio device driver from the manufacturer's website.


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
<li><a href="https://article-files.techidaily.com/new-2024-approved-professional-recommendations-superior-voice-modification-tools/"><u>[New] 2024 Approved Professional Recommendations Superior Voice Modification Tools</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-improve-video-clarity-with-simplified-caption-steps/"><u>[New] Improve Video Clarity with Simplified Caption Steps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-automate-your-snapshot-backup-from-snapchat-app/"><u>[New] In 2024, Automate Your Snapshot Backup From Snapchat App</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-compre-cookie-cutter-webinar-logging-a-windows-and-macos-manual/"><u>[New] In 2024, Compre Cookie Cutter Webinar Logging A Windows & macOS Manual</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-quick-guide-saving-screen-share-dialogue/"><u>[New] Quick Guide Saving Screen Share Dialogue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-focus-on-you-not-the-surroundings-blur-techniques-for-google-meet-success/"><u>[Updated] 2024 Approved Focus on You, Not the Surroundings Blur Techniques for Google Meet Success</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-spotify-how-to-halt-default-podcast-additions/"><u>[Updated] Spotify How to Halt Default Podcast Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-file-handling-windows-edition-max-156/"><u>Efficiency in File Handling: Windows Edition (Max 156)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/enhancing-your-instareel-game-with-unbeatable-slow-motion-techniques-for-2024/"><u>Enhancing Your InstaReel Game with Unbeatable Slow Motion Techniques for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-advice-resolving-the-not-launching-error-in-hogwarts-legacy-updated-tips-for-202cu/"><u>Expert Advice: Resolving the 'Not Launching' Error in Hogwarts Legacy (Updated Tips for 202Cu)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-high-cpu-usage-from-vanguard-user-mode-service-on-windows/"><u>How to Fix High CPU Usage From Vanguard User-Mode Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-and-solutions-for-a-non-responsive-discord-overlay/"><u>Identifying Causes and Solutions for a Non-Responsive Discord Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-low-resource-browsers-for-windows-macos-chromeos-users/"><u>Identifying Low Resource Browsers for Windows, macOS, ChromeOS Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-from-idea-to-installment-making-custom-instagram-notifications/"><u>In 2024, From Idea to Installment Making Custom Instagram Notifications</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-and-updating-the-latest-drivers-for-your-brother-mfc-7360n-on-windows-version-11-8-7/"><u>Installing and Updating the Latest Drivers for Your Brother MFC-7360N on Windows (Version 11, 8, 7)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-x-solutions-for-windows-mail-mistakes/"><u>Mastering Error X: Solutions for Windows Mail Mistakes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-powerpoints-voice-recognition-feature-for-2024/"><u>Mastering PowerPoint's Voice Recognition Feature for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-absence-of-monitor-at-startup/"><u>Overcoming Absence of Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-installation-hurdles-in-windows-11/"><u>Overcoming Steam Installation Hurdles in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-0x800700e1/"><u>Overcoming Windows Error 0X800700E1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-to-resolve-screen-size-settings-issues-on-pcs/"><u>Remedies to Resolve Screen Size Settings Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-accessible-nvidia-display-settings/"><u>Restoring Accessible Nvidia Display Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-failed-attempts-office-activation-troubleshooting/"><u>Reversing Failed Attempts: Office Activation Troubleshooting</u></a></li>
<li><a href="https://win-answers.techidaily.com/smooth-sailing-ahead-resolving-euro-truck-simulator-2-pc-disruptions-for-gaming-enthusiasts/"><u>Smooth Sailing Ahead: Resolving Euro Truck Simulator 2 PC Disruptions for Gaming Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-dxgierrordeviceremoved-in-oses/"><u>Steps to Address DXGI_ERROR_DEVICE_REMOVED in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-sandboxs-zero-error-hypervisor-missing/"><u>Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-permanent-delete-on-windows-pcs-with-the-power-of-your-desktop-bin-11/"><u>Streamlining Permanent Delete on Windows PCs with the Power of Your Desktop Bin (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intersection-of-ai-and-windows-11-user-experience/"><u>The Intersection of AI and Windows 11 User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-camouflaging-search-on-11/"><u>The Ultimate Guide to Camouflaging Search on 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshoot-and-solve-your-persistent-minecraft-crash-issues-in-just-6-ways/"><u>Troubleshoot & Solve Your Persistent Minecraft Crash Issues in Just 6 Ways!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-after-windows-update-installation/"><u>Troubleshooting After Windows Update Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-accelerate-your-windows-printer-pace/"><u>Turbo-Accelerate Your WIndows Printer Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-diskspace-analyzer-tool-a-new-feature-for-windows-explorer/"><u>Visual Diskspace Analyzer Tool: A New Feature for Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/which-nvidia-driver-suits-you-gameplay-or-studio/"><u>Which Nvidia Driver Suits You? - Gameplay or Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-you-should-stick-with-windows-over-linux-for-gaming/"><u>Why You Should Stick With Windows Over Linux for Gaming</u></a></li>
</ul></div>




