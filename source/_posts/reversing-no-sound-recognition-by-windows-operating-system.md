---
title: Reversing No Sound Recognition by Windows Operating System
date: 2024-10-25T00:20:06.206Z
updated: 2024-10-26T16:32:29.966Z
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

## 1\. Run the Windows Audio Troubleshooter

 You can troubleshoot sound problems on Windows using the built-in audio troubleshooter. It scans your Windows system for common audio issues and tries to fix them automatically.

To run the troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .
3. Next, click on**Other** **troubleshooters** .  
![Windows 11 troubleshoot other troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-troubleshoot-other-troubleshooter.jpg)
4. Click the**Run** button for**Playing Audio** . It will check your audio service status and prompt you to select your audio device.  

![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)
5. Select your device speaker and click**Next** .
6. Click**NO** ,**Do not open Audio Enhancements** in the**Turn off Sound Effects and Enhancements** dialog.
7. Apply any recommended fixes and check for any improvements.

 If the troubleshooter left a good impression on you, check out our[guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![local users and groups administrator properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/local-users-and-groups-administrator-properties.jpg)
5. Select and right-click on the**Administrators** account and select**Properties** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902324/19272" target="_top" id="1902324">
  <img src="//a.impactradius-go.com/display-ad/19272-1902324" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902324/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click the**Add** button in the**Administrator Properties** dialog.
2. ![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)
3. Next, type**network service** and click**Check Names** . It should change the object name to**NETWORK SERVICE.**  

![add network service local administrator group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group.jpg)
4. Click**OK** to add network service to the local user group.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

7. Once uninstalled, restart your PC. Windows will automatically install the necessary drivers for your audio device.

 If the issue persists, manually reinstall the audio device driver from the manufacturer.

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
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-in-2024-how-to-record-steam-gameplay/"><u>[New] In 2024, How to Record Steam Gameplay</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-from-novice-to-pro-learning-snapseed-essentials-for-2024/"><u>[Updated] From Novice to Pro Learning Snapseed Essentials for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-capture-your-conversations-top-rated-free-and-paid-techniques-windowsmac/"><u>[Updated] In 2024, Capture Your Conversations Top-Rated Free and Paid Techniques (Windows/Mac)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-digital-delights-8-most-watched-movies/"><u>2024 Approved Digital Delights 8 Most Watched Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-the-purpose-of-x-marked-folders-in-windows/"><u>Exploring: The Purpose of X-Marked Folders in Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fixing-lg-monitor-drivers-solutions-for-windows-11-7-and-81-users/"><u>Fixing LG Monitor Drivers: Solutions for Windows 11, 7 & 8.1 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-disabling-auto-start-and-update-searches-by-discord/"><u>Guide to Disabling Auto-Start & Update Searches by Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-software-shortcuts-to-windows-11s-desktop-context-menu/"><u>How to Add Software Shortcuts to Windows 11’S Desktop Context Menu</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-tecno-spark-10-pro-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Tecno Spark 10 Pro Location on Viber | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-error-nvidia-settings-are-unavailable-window/"><u>Overcoming Error: Nvidia Settings Are Unavailable Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-unrequested-search-menu-opens-in-win11/"><u>Stopping Unrequested Search Menu Opens in Win11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/tips-and-tricks-for-an-immersive-tv-experience-during-super-bowl-sunday/"><u>Tips and Tricks for an Immersive TV Experience During Super Bowl Sunday</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-artistic-potential-through-windows-generate-delete/"><u>Unleashing Artistic Potential Through Windows' Generate Delete</u></a></li>
</ul></div>

