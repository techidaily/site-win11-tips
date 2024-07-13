---
title: Effective Strategies to Control External Hard Drive Usage
date: 2024-07-12T17:20:12.911Z
updated: 2024-07-13T17:20:12.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Strategies to Control External Hard Drive Usage
excerpt: This Article Describes Effective Strategies to Control External Hard Drive Usage
keywords: HDD Usage Management,Data Storage Limits,Backup Plans Optimization,External Drive Efficiency,HDD Control Techniques,Data Transfer Limitation,Usage Time Allocation
thumbnail: https://thmb.techidaily.com/b1dd0483f32a09412f335f94508f9f7301d5aa196fe907bac96fdd29e9d8162d.png
---

## Effective Strategies to Control External Hard Drive Usage

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor
![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


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
<li><a href="https://win11-tips.techidaily.com/mastering-windows-netconfig-a-guide-to-connectivity/"><u>Mastering Window's NetConfig: A Guide to Connectivity</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-the-art-of-flawless-instantaneous-iphone-podcast-downloads/"><u>[Updated] Unlocking the Art of Flawless, Instantaneous iPhone Podcast Downloads</u></a></li>
<li><a href="https://driver-install.techidaily.com/maximizing-astro-updating-and-restarting-drivers/"><u>Maximizing Astro: Updating and Restarting Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-file-sync-problem-in-windows-environment/"><u>Overcoming Steam File Sync Problem in Windows Environment</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-top-animation-software-for-gaming-intros-on-pc-and-mac-for-2024/"><u>Updated Top Animation Software for Gaming Intros on PC and Mac for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-oppo-find-x7-ultra-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Oppo Find X7 Ultra Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-inside-instagrams-maximum-video-restriction-policy/"><u>[New] In 2024, Inside Instagram's Maximum Video Restriction Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-file-failsafe-six-steps-for-correcting-winrar-sums/"><u>Fixing File Failsafe: Six Steps for Correcting WinRAR Sums</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-tailoring-video-content-for-igtv-with-horizontal-footage/"><u>[New] 2024 Approved  Tailoring Video Content for IGTV with Horizontal Footage</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-obs-studio-wizards-top-5-secrets-to-unmatched-quality/"><u>[New] In 2024, OBS Studio Wizards  Top 5 Secrets to Unmatched Quality</u></a></li>
<li><a href="https://audio-editing.techidaily.com/top-guide-for-users-seeking-background-noise-removal-in-online-tools/"><u>Top Guide For Users Seeking Background Noise Removal in Online Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quick-guide-initiating-and-managing-android-zoom-calls/"><u>[Updated] Quick Guide  Initiating & Managing Android Zoom Calls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-operating-environment-for-device-interfaces/"><u>Optimizing Windows Operating Environment for Device Interfaces</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamlessly-change-the-dynamic-background-in-windows-os/"><u>Seamlessly Change the Dynamic Background in Windows OS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-why-professionals-choose-final-cut-pro-over-express-for-2024/"><u>New Why Professionals Choose Final Cut Pro Over Express for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/aural-affordability-the-complete-manual-on-free-audio-download-methods/"><u>Aural Affordability The Complete Manual on FREE Audio Download Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-launch-and-configure-win-11-sandbox/"><u>How to Launch and Configure Win 11 Sandbox</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-methods-to-subtly-soften-audible-output-via-lumafusion/"><u>In 2024, Innovative Methods to Subtly Soften Audible Output via Lumafusion</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-what-is-audio-ducking-and-how-to-use-it-in-filmora/"><u>New 2024 Approved What Is Audio Ducking and How to Use It in Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notable-nights-of-non-opening-notepad-your-solution-guide-for-windows-users/"><u>Notable Nights of Non-Opening Notepad: Your Solution Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstating-missing-pin-after-win-11-updates/"><u>Guide to Reinstating Missing PIN After Win 11 Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-obs-studio-not-launching-on-windows/"><u>How to Fix OBS Studio Not Launching on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-onedrive-login-failure-x8004dec5-windows-issue/"><u>Resolving ONEDRIVE Login Failure: X.8004DEC5 Windows Issue</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-champion-video-grabbers-ranked-1-8/"><u>[New] Champion Video Grabbers Ranked 1-8</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/outsmart-automated-views-to-propel-your-channel-for-2024/"><u>Outsmart Automated Views to Propel Your Channel for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-top-voice-ovation-creators-online-and-desktop-recommendations-for-2024/"><u>Updated Top Voice-Ovation Creators Online and Desktop Recommendations for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-quick-access-windows-11-screen-grab-utility/"><u>Mastering Quick Access: Windows 11 Screen Grab Utility</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-classic-film-aesthetics-masterclass-in-video-production/"><u>[New] 2024 Approved  Classic Film Aesthetics  Masterclass in Video Production</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-breaking-into-the-tiktok-livestream-realm/"><u>In 2024, Breaking Into the TikTok Livestream Realm</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-effortless-sound-sourcing-the-top-15-freebie-audiosites-for-2024/"><u>[Updated] Effortless Sound Sourcing  The Top 15 Freebie Audiosites for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-samsung-galaxy-a25-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from Samsung Galaxy A25 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-windows-11s-default-search-settings/"><u>Optimizing Windows 11'S Default Search Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-time-display-on-windows-11-taskbar/"><u>Mastering Time Display on Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-methods-creating-new-dossiers-in-win11/"><u>Quick Methods: Creating New Dossiers in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-epic-game-launcher-failures-on-windows-os/"><u>Preventing Epic Game Launcher Failures on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-winerror-x8019/"><u>Mitigating WinError: X8019</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-samsung-galaxy-a14-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Samsung Galaxy A14 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Xiaomi Redmi Note 12 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rewind-to-richness-a-guide-to-gaming-glory-past/"><u>Rewind to Richness: A Guide to Gaming Glory Past</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-erroneous-wins-protection-messages/"><u>Fixing Erroneous WINS Protection Messages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-windows-resolution-glitches/"><u>Overcoming Common Windows Resolution Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-your-windows-11-ms-store-experience/"><u>Reinstating Your Windows 11 MS Store Experience</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-androids-facetime-essentials-explained/"><u>[Updated] Android's FaceTime Essentials Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-current-windows-pass-error-in-win11win11/"><u>Solving Current Windows Pass Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-pursuit-of-purposeful-downloads-from-windows-store/"><u>In Pursuit of Purposeful Downloads From Windows Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-no-save-photoerror-in-windows-11-os/"><u>How to Correct 'No Save' PhotoError in Windows 11 OS</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-soundless-filmmakers-handbook-techniques-for-removing-audio-from-iphones-for-2024/"><u>Updated The Soundless Filmmakers Handbook Techniques for Removing Audio From iPhones for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oneplus-ace-2-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast OnePlus Ace 2 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unseen-chronicles-5-expertly-crafted-viewer-tools/"><u>[Updated] 2024 Approved  Unseen Chronicles  5 Expertly Crafted Viewer Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-voice-typing-problems-error-code-0x80049dd3-in-windows-11/"><u>Remedying Voice Typing Problems (Error Code: 0X80049DD3) in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prioritize-safety-invest-heavily-in-research-to-develop-advanced-safety-features-that-reduce-potential-risks-associated-with-drone-operations-such-as-collis31/"><u>Prioritize Safety: Invest Heavily in Research to Develop Advanced Safety Features that Reduce Potential Risks Associated with Drone Operations, Such as Collision Avoidance Technology, Redundant System Architectures, and Thorough Pre-Flight Checks.</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-the-ever-changing-era-of-ai-video-translation-a-reality-to-be-fulfilled/"><u>New In 2024, The Ever-Changing Era of AI Video Translation A Reality to Be Fulfilled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-guide-to-easy-use-of-windows-accessibility/"><u>Novices' Guide to Easy Use of Windows Accessibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-screen-space-removing-windows-overscan-effects/"><u>Maximizing Screen Space: Removing Windows Overscan Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-windows-users-from-changing-the-date-and-time/"><u>How to Stop Windows Users From Changing the Date and Time</u></a></li>
<li><a href="https://extra-information.techidaily.com/zero-shaking-zones-how-to-fix-unstable-gopro-videos/"><u>Zero Shaking Zones  How to Fix Unstable GoPro Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/best-emulators-pc-edition-ps1-games-for-2024/"><u>Best Emulators  PC Edition - PS1 Games for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/perfect-your-iphone-photo-mosaic-skills-for-2024/"><u>Perfect Your iPhone Photo Mosaic Skills for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-in-minutes-command-line-steps/"><u>Exploring Windows in Minutes: Command Line Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/leveraging-luminance-adjustments-on-your-win11-device/"><u>Leveraging Luminance Adjustments on Your Win11 Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-reverse-keyboard-input-on-pcs/"><u>Navigating Reverse Keyboard Input on PCs</u></a></li>
</ul></div>
