---
title: Repairing Windows Camera Failure on Photo/Video Saving
date: 2024-06-25T16:16:04.664Z
updated: 2024-06-26T16:16:04.664Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Repairing Windows Camera Failure on Photo/Video Saving
excerpt: This Article Describes Repairing Windows Camera Failure on Photo/Video Saving
keywords: Fix Windows Cam Save Issue,Repair Window's Cameras,Resolve Windows Cam Problems,Enhance Windows Video Recording,Address Photo/Video Failure,Windows Camera Troubleshooting,Correct Windows Cam Errors
thumbnail: https://thmb.techidaily.com/6d87b1c3f35bd086cb57f3daa2bccf1c889bbcea516bdcb3d44c7df48b1c3e3d.jpg
---

## Repairing Windows Camera Failure on Photo/Video Saving

 The Windows Camera app is known for its simplicity and user-friendliness, making it a go-to choice for capturing and preserving memories. However, there are occasions when you encounter problems with the app, like the inability to save photos or videos on your device. This can be particularly frustrating, especially if you intend to share or edit these media files later. Below, we walk you through the steps to resolve issues with the Camera app when it fails to save photos or videos in Windows.

## 1\. Check the Storage Permissions

 If your laptop or computer’s camera doesn’t save photos or videos, we recommend starting your troubleshooting journey by ensuring it has sufficient permissions to store data on your device.

 Here is how you can quickly do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Privacy & security** from the left pane.
3. Head over to the App permissions section and choose **Camera** from the list of options available.
4. Turn the toggle on for **Camera access**. You can now close the Settings app and check if the problem is resolved.  
![Enable the Camera Access in the Privacy and Security Tab of the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/3-enable-the-camera-access-in-the-privacy-and-security-tab-of-the-windows-settings-app.jpg)

 While you are at it, you can also re-add your saved location for storing data and see if that makes a difference.

1. Open the Settings app and navigate to **System** \> **Storage** \> **Where new content is saved**.
2. Expand the dropdown for "New videos and photos will save to:" and pick another location. For instance, if you have a USB device, pick that.  
![Pick a different location to save photos and videos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-a-different-location.jpg)

 Here is an alternate way of changing the location:

1. Open a Run dialog by pressing the **Win** \+ **R** keys together.
2. Type “%APPDATA%\\Microsoft\\Windows\\Libraries” in Run and click **Enter**. This will launch the libraries section of the File Explorer.
3. Right-click on Camera roll and choose **Properties** from the context menu.
4. In the following dialog, click on the **Add** button.  
![Change where the camera will save photos and videos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/change-location-for-camera.jpg)
5. Now, add your new preferred location and choose **Set Default Save Location**.
6. Hit **Apply** \> **OK** to save the changes and check if the issue is resolved.

## 2\. Update the Camera Drivers

 Another reason why your camera app might be acting is because of outdated or corrupt drivers. Such issues can be resolved by updating the drivers using either the Device Manager utility or the Windows Update option.

 Here is how you can update your camera driver using the Device Manager:

1. Press the **Win** \+ **S** keys together to open Windows Search.
2. Type "Device Manager" in the search bar and click **Open**.
3. In the following window, expand the Cameras section and right-click on your camera driver.
4. Choose **Update driver** \> **Search automatically for drivers**.  
![Update the Relevant Camera Driver From Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/4-update-the-relevant-camera-driver-from-windows-device-manager.jpg)
5. The utility will now start scanning for an updated version of your driver in the system. If it finds any, follow the on-screen instructions to install it. If it does not, you can click on **Search for updated drivers on Windows Update** to see if an update is available.

 You can also head over to your manufacturer’s website, download an updated version from there, and then install it manually.

## 3\. Repair the Camera App

 The camera app itself can be dealing with an inconsistency or a corruption error which might be preventing it from saving photos and videos. To check if this is the case in your situation, you can make use of the repair option for the camera available in the Windows Settings app.

 This feature will do the following to help with the problem:

* Scan for any missing or corrupted files and reinstall them
* Check the Windows Registry and app-specific configuration settings to ensure they are correctly configured
* Verify and reconfigure any dependencies critical for the app to function

 Follow these steps to repair the app:

1. Open the Settings app and choose **Apps** from the left pane.
2. Click on **Apps & features**.
3. Head over to the App list section and click on the three dots associated with the Camera app.
4. Choose **Advanced options** from the context menu.
5. In the Reset section, click on the **Repair** button.  
![Repair Camera app from Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Repair-Camera.jpg)
6. Wait for the process to complete. This may take a while, depending upon the complexity of the underlying problems.

 Once the app is successfully repaired, check if the issue is fixed. If the app fails to repair, you should see a “We couldn’t repair this app. Try again in a bit.” In that case, you can try using the System File Checker for a more detailed check of the system, or move to the next method below.

## 4\. Check Your Antivirus and Firewall Settings

 Are you using a third-party security program on your Windows device? If so, there is a good chance that the security program is interfering with the operation of the Camera app, preventing it from saving the data.

 To determine if this is true, you can [disable your antivirus program temporarily](https://www.makeuseof.com/cant-enable-windows-firewall/). If you are using the security features offered by Windows, you can [turn off Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) for some time and retry saving your photos and videos.

 It is, however, important to note that disabling these programs can make your computer vulnerable to risks, so we recommend turning them back on immediately once you are done.

## 5\. Reset or Reinstall the Camera App

 Finally, if the steps listed above have not worked, you can try resetting or reinstalling the camera app as the last resort.

 Resetting the app is a less drastic measure that will restore the camera app's settings to their default values. If this does not fix the problem, you can proceed with a reinstallation, which will essentially remove the existing app from your system.

 You can then download and install a fresh copy from the Microsoft Store (or from another trusted source). It will fix any issues with the previous installation that may be causing the problem.

 To reset the app, open the **Advanced options** menu for the Camera app as we described above. Click on the **Reset** button and follow the on-screen instructions to proceed. To uninstall, launch the Powershell utility as an administrator and execute the following command:

`get-appxpackage *Microsoft.WindowsCamera* | remove-appxpackage`

 Once the command executes, launch Microsoft Store and install the Camera app again.

## Capture and Save Your Moments Again on Windows

 A malfunctioning Camera app that can't save your photos or videos can be a real inconvenience, but it is not impossible to fix. Hopefully, the methods above will help you restore your Camera app's functionality and continue capturing life's moments with confidence. To prevent this issue from occurring in the future, it is best to keep your camera drivers up-to-date at all times.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/turning-the-tide-restoring-daylight-from-dark-theme/"><u>Turning the Tide: Restoring Daylight From Dark Theme</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-optimal-adventure-play-winning-hd-games-on-pc-with-scummvm/"><u>A Guide to Optimal Adventure Play: Winning HD Games on PC with ScummVM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-no-powershell-found-on-your-windows-device/"><u>Remedies for No PowerShell Found on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-data-protection-turning-on-controlled-folder-access/"><u>Ensuring Data Protection: Turning on Controlled Folder Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-visual-assurance-verify-windows-equipment-before-calling/"><u>Audio Visual Assurance: Verify Windows Equipment Before Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-desktop-icon-chaos-in-windows/"><u>Avoid Desktop Icon Chaos in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-to-hyper-v-enablement-in-win11/"><u>Essential Guide to Hyper-V Enablement in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/multi-monitor-mastery-personalized-pixelation-per-system-screen/"><u>Multi-Monitor Mastery: Personalized Pixelation per System Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/audio-upgrade-in-a-flash-streamlining-windows-driver-updates/"><u>Audio Upgrade in a Flash: Streamlining Windows Driver Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-fixing-unexpected-system-call-failures-on-win1011/"><u>Guide: Fixing Unexpected System Call Failures on Win10/11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-optical-opinions-ranking-the-best-camera-lenses-1-10-2024-edition/"><u>[New] Optical Opinions  Ranking the Best Camera Lenses #1-10, 2024 Edition</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-10-masterpieces-in-job-market-insight/"><u>In 2024, 10 Masterpieces in Job Market Insight</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-simplified-approach-to-preserving-video-calls/"><u>[New] Simplified Approach to Preserving Video Calls</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>What Legendaries Are In Pokemon Platinum On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/how-to-ride-on-others-tiktok-waves-as-a-guest-for-2024/"><u>How to Ride on Others' TikTok Waves as a Guest for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-unearthing-the-echoes-from-whistling-sounds/"><u>Updated Unearthing the Echoes From Whistling Sounds</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-make-your-discord-conversation-stand-out-with-style/"><u>[New] In 2024, Make Your Discord Conversation Stand Out with Style</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-honor-90-lite-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Honor 90 Lite Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-blending-music-into-your-ig-visuals-for-2024/"><u>The Art of Blending Music Into Your IG Visuals for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-mastering-fcpx-the-ultimate-guide-to-xml-files/"><u>In 2024, Mastering FCPX The Ultimate Guide to XML Files</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>