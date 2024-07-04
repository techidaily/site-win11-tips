---
title: Restoring Microsoft Store Functionality in Windows 11
date: 2024-06-25T16:30:40.045Z
updated: 2024-06-26T16:30:40.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Microsoft Store Functionality in Windows 11
excerpt: This Article Describes Restoring Microsoft Store Functionality in Windows 11
keywords: Win11 Store Fix,MS Windows Restore,Store OS Repair,Microsoft Store Enable,Win11 Store Recovery,MSCornerStore Function,Windows 11 Store Revive
thumbnail: https://thmb.techidaily.com/f68ad44dfce4596bff961c8c73128e503881dbfbd95e5f1787a78426eec3f375.jpg
---

## Restoring Microsoft Store Functionality in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users ![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users ![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11-tips.techidaily.com/navigating-through-access-denied-save-issues-on-windows/"><u>Navigating Through Access Denied Save Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-action-for-resolving-missing-msconfig-in-windows-1011/"><u>Swift Action for Resolving Missing MSCONFIG in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-batch-script-execution-power/"><u>Elevate Your Batch Script Execution Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ahead-mastering-upcoming-tools-through-vivetool/"><u>Windows Ahead: Mastering Upcoming Tools Through ViVeTool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-your-systems-kickstart-area/"><u>Navigating to Your System's Kickstart Area</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functionality-of-windows-photo-viewer-in-win11/"><u>Restoring Functionality of Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-windows-local-space-management-tips-no-file-removal-max-156-chars/"><u>Innovative Windows Local Space Management Tips (No File Removal) (Max 156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-enterprise-restricted-chromeedge-settings-on-desktop-pcs/"><u>Addressing Enterprise-Restricted Chrome/Edge Settings on Desktop PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-superuser-access-a-step-by-step-guide/"><u>Mastering Superuser Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-streamlining-vimeo-uploads-from-moviemaker-projects/"><u>In 2024, Streamlining Vimeo Uploads From Moviemaker Projects</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-exploring-the-magic-of-ai-selfie-generators/"><u>New 2024 Approved Exploring the Magic of AI Selfie Generators</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-vivo-y100a-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Vivo Y100A FRP Locks</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-speech-recognition-to-mp3-seamless-integration-across-devices-and-oses/"><u>Updated Speech Recognition to MP3 Seamless Integration Across Devices and OSes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ps4-live-recording-made-simple-with-obs-tutorial-for-2024/"><u>[New] PS4 Live Recording Made Simple with OBS Tutorial for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/top-rated-ios-applications-for-emulating-popular-psp-games/"><u>Top-Rated iOS Applications for Emulating Popular PSP Games</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/tips-for-effortless-eradication-of-unwanted-youtube-discussions-for-2024/"><u>Tips for Effortless Eradication of Unwanted YouTube Discussions for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-inside-twitters-most-impactful-videos-of-the-year/"><u>[Updated] In 2024, Inside Twitter's Most Impactful Videos of the Year</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/iphone-ringtones-a-guide-to-personalized-sound-choices-for-2024/"><u>IPhone Ringtones  A Guide to Personalized Sound Choices for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-videocapture-analysis-hub/"><u>[New] In 2024, VideoCapture Analysis Hub</u></a></li>
</ul></div>
