---
title: How to Cut Out OneDrive From Your PC's File Explorer Screenshot
date: 2024-07-12T17:03:38.067Z
updated: 2024-07-13T17:03:38.067Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
excerpt: This Article Describes How to Cut Out OneDrive From Your PC's File Explorer Screenshot
keywords: Removing OneDrive From File Explorer,Disable OneDrive in Windows,Exclude OneDrive From Explorer Screenshots,Remove OneDrive Icon From PC Explorer,Screenshot without OneDrive,Screen Capture Excluding OneDrive,Exclude OneDrive when Capturing Files
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## How to Cut Out OneDrive From Your PC's File Explorer Screenshot

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://win11-tips.techidaily.com/stop-blanking-and-flashing-windows-11-screen/"><u>Stop Blanking and Flashing Windows 11 Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/next-gen-teams-meeting-demands-efficiently/"><u>Next-Gen Teams Meeting Demands Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-the-way-you-search-on-windows-11/"><u>Revamp the Way You Search on Windows 11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>How Do I Stop Someone From Tracking My Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-dark-screen-post-update-solution/"><u>Win11 Dark Screen Post-Update Solution</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-beyond-reality-comparing-vr-augmented-and-mixed-tech/"><u>In 2024, Beyond Reality  Comparing VR, Augmented & Mixed Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propelty-keystrokes-on-windows-1011-decrease-lag-quickly/"><u>Propelty Keystrokes on Windows 10/11: Decrease Lag Quickly</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-x90s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-streamlining-with-new-folder-placement/"><u>Step-by-Step Guide to Streamlining with New Folder Placement</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-ranked-techniques-for-capturing-online-sport-spectacles/"><u>[New] Top-Ranked Techniques for Capturing Online Sport Spectacles</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-harnessing-color-grading-power-with-central-luts/"><u>[Updated] Harnessing Color Grading Power with Central Luts</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-exciting-update-filmora-x-compatible-with-arm-architecture/"><u>In 2024, Exciting Update Filmora X Compatible with ARM Architecture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reenergizing-your-dead-wireless-hotspot-in-windows-11/"><u>Reenergizing Your Dead Wireless Hotspot in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-youtube-streams-with-simple-obs-guide-for-2024/"><u>Mastering YouTube Streams with Simple OBS Guide for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-x-fold-2-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Vivo X Fold 2 Location by Number | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-mastering-instagram-adding-borders-to-your-photos/"><u>[New] In 2024, Mastering Instagram  Adding Borders to Your Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforcing-the-resilience-of-windows-11-taskbar/"><u>Reinforcing the Resilience of Windows 11 Taskbar</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unleash-your-favorites-top-youtube-musicians/"><u>2024 Approved  Unleash Your Favorites  Top YouTube Musicians</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-netflix-freeze-in-windows-software/"><u>Overcoming Netflix Freeze in Windows Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-infinix-hot-40i-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Infinix Hot 40i to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-error-code-0x80070570-for-corrupted-items/"><u>Steps to Resolve Windows Error Code 0X80070570 for Corrupted Items</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-code-0x887a0006-device-hang-fixes/"><u>Resolving Error Code 0X887A0006: Device Hang Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/repairing-windows-camera-failure-on-photovideo-saving/"><u>Repairing Windows Camera Failure on Photo/Video Saving</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-default-path-problems-on-windows-1011/"><u>Resolving Default Path Problems on Windows 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-combat-windows-minimizing-glitches/"><u>Strategies to Combat Windows Minimizing Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-windows-installation-privilege-denial-problem/"><u>Solving Windows Installation Privilege Denial Problem</u></a></li>
<li><a href="https://fox-http.techidaily.com/globalscreen-top-ranked-local-and-live-tv-streams-for-2024/"><u>GlobalScreen  Top-Ranked Local & Live TV Streams for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-fatal-glitches-steps-to-fix-error-0x00000001-in-xbox-game-pass-for-windows-11/"><u>Overcoming Fatal Glitches: Steps to Fix Error 0X00000001 in Xbox Game Pass for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snipmagic-disrupted-methods-to-reset-and-revive/"><u>SnipMagic Disrupted? Methods to Reset and Revive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/realign-subtitles-in-prime-video-elevate-your-windows-11-experience/"><u>Realign Subtitles in Prime Video, Elevate Your Windows 11 Experience</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-zooms-auditory-masterclass-fine-tuning-for-impeccable-audio/"><u>[Updated] Zoom's Auditory Masterclass  Fine-Tuning for Impeccable Audio</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-tailor-your-tiktok-voice-a-step-by-step-process/"><u>In 2024, Tailor Your TikTok Voice  A Step-by-Step Process</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-high-quality-youtube-images-download-without-any-cost/"><u>2024 Approved  High-Quality YouTube Images  Download Without Any Cost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reach-top-ssd-efficiency-in-windows-utilize-ssdfresh/"><u>Reach Top SSD Efficiency in Windows, Utilize SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stifling-windows-restart-requests/"><u>Stifling Windows Restart Requests</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-spotify-connections-on-windows-11-devices/"><u>Overcoming Spotify Connections on Windows 11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-your-digital-space-with-win-11-sketching-techniques/"><u>Redefine Your Digital Space with Win 11 Sketching Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-youtube-alternatives-at-a-glance-choosing-the-best-platforms/"><u>[Updated] YouTube Alternatives at a Glance  Choosing the Best Platforms</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-high-fidelity-game-recording-tools/"><u>In 2024, High Fidelity Game Recording Tools</u></a></li>
<li><a href="https://fox-direct.techidaily.com/decisional-balance-for-2024/"><u>Decisional Balance for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-vivo-y100a-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-environment-with-portable-utility-icons/"><u>Streamlining Windows Environment with Portable Utility Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-cannot-link-with-nvidia-in-windows-11/"><u>How to Rectify Cannot Link with NVIDIA in Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/top-6-techniques-amplify-and-adapt-your-zoom-presence-with-hilarious-inflections-in-2024/"><u>Top 6 Techniques Amplify & Adapt Your Zoom Presence with Hilarious Inflections, In 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-turn-off-the-mobile-interface-win-11/"><u>Quick Fix: Turn Off the Mobile Interface (Win 11)</u></a></li>
</ul></div>
