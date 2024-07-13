---
title: Addressing Insufficient RAM Issues on Windows/VmWare Platforms
date: 2024-07-12T17:46:01.634Z
updated: 2024-07-13T17:46:01.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Insufficient RAM Issues on Windows/VmWare Platforms
excerpt: This Article Describes Addressing Insufficient RAM Issues on Windows/VmWare Platforms
keywords: WinRAM Solutions,VmWare Memory Woes,Low RAM Fix Guide,Optimize VM Memory,Address Insufficient RAM,Windows Virtual RAM,RAM Efficiency Tips
thumbnail: https://thmb.techidaily.com/89e14fb11e9e592fbd5c568e89cdfa2567dfefcd7e2cc4ffd1db69453f4dcbe5.jpg
---

## Addressing Insufficient RAM Issues on Windows/VmWare Platforms

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out [how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.
5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.
7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about [uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on [how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the [VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the [VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-flashing-display-issues-on-windows-11/"><u>Quick Fix for Flashing Display Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-errors-a-guide-to-fs-repair-in-win11/"><u>Mending Errors: A Guide to FS Repair in Win11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-delicious-diplomacy-popular-food-recipes-from-nations/"><u>2024 Approved  Delicious Diplomacy  Popular Food Recipes From Nations</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-crafting-engaging-visuals-after-effects-best-10-text-plans/"><u>In 2024, Crafting Engaging Visuals  After Effect's Best 10 Text Plans</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-8-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 8 without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-win-11-gameplay-unveiling-the-ultimate-seven-steps/"><u>Boosting Win 11 Gameplay: Unveiling the Ultimate Seven Steps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-samsung-galaxy-m34s-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Samsung Galaxy M34s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deactivated-rulesets-in-outlookwindows/"><u>Troubleshooting Deactivated Rulesets in Outlook/Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-complete-guide-to-enthralling-boomers-on-snapchat/"><u>In 2024, The Complete Guide to Enthralling Boomers on Snapchat</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-the-graphic-problem-in-overwatch/"><u>Overcoming the Graphic Problem in Overwatch</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-honor-magic-5-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Honor Magic 5 FRP</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/5-best-auto-music-mixer-for-mac/"><u>5 Best Auto Music Mixer for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-save-big-top-6-inexpensive-action-cams-under-100-deals/"><u>2024 Approved  Save Big  Top 6 Inexpensive Action Cams Under $100 Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-clearer-journey-the-art-of-annotating-folders-on-windows-11/"><u>A Clearer Journey: The Art of Annotating Folders on Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-iphone-11-pro-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from iPhone 11 Pro</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-step-by-step-guide-to-storyboard-for-2024/"><u>Updated Step-by-Step Guide to Storyboard for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-one-off-to-firm-follower-an-ethical-approach-for-2024/"><u>[New] From One-Off to Firm Follower  An Ethical Approach for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-untapped-potential-to-augment-your-youtube-audience/"><u>2024 Approved  Unveiling Untapped Potential to Augment Your Youtube Audience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/ultimate-guide-to-mp4-from-instagram-advanced-2-step-processes/"><u>Ultimate Guide to MP4 From Instagram  Advanced 2-Step Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-change-easily-altering-nat-settings-in-win1110/"><u>Navigating the Change: Easily Altering NAT Settings in Win11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-bypass-windows-admin-installation-restriction-error/"><u>Steps to Bypass Windows 'Admin Installation Restriction' Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-backup-with-windows-11/"><u>Streamlining File Backup with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-0x00000001-barrier-in-game-access/"><u>Overcoming the 0X00000001 Barrier in Game Access</u></a></li>
<li><a href="https://extra-information.techidaily.com/under-200-cameras-with-action-potential-at-your-fingertips/"><u>Under $200 Cameras with Action Potential at Your Fingertips</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/2024-approved-top-5-udemy-subtitle-translation-tools-for-seamless-auto-translations/"><u>2024 Approved Top 5 Udemy Subtitle Translation Tools for Seamless Auto Translations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-folder-multiplication-on-windows-devices/"><u>Unlocking the Potential of Folder Multiplication on Windows Devices</u></a></li>
<li><a href="https://network-issues.techidaily.com/eliminating-c1900101-during-the-process-of-win11-setup/"><u>Eliminating C1900101 During the Process of Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-noisy-keys-regaining-control-over-sound-on-your-pc/"><u>Tame Noisy Keys: Regaining Control Over Sound on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-windows-11-shutdown-procedure-for-active-operations/"><u>Tweak Windows 11 Shutdown Procedure for Active Operations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-steam-network-via-dns-cleanup/"><u>Streamlining Your Steam Network via DNS Cleanup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-trigger-startup-success-for-windows-index-service/"><u>Strategies to Trigger Startup Success for Windows Index Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-save-locations-windows-xp78-errors/"><u>Overcoming Save Locations: Windows XP/7/8 Errors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-your-input-cannot-be-opened-error-in-windows-vlc/"><u>Rectify 'Your Input Cannot Be Opened' Error in Windows, VLC</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-tapping-into-community-spirit-a-guide-to-thriving-fb-gifting-campaigns/"><u>[New] Tapping Into Community Spirit  A Guide to Thriving FB Gifting Campaigns</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-mastering-vimeo-uploads-with-imovie-videos/"><u>[New] In 2024, Mastering Vimeo Uploads with iMovie Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quiet-quandaries-winning-back-volume-from-vexed-keyboard/"><u>Quiet Quandaries: Winning Back Volume From Vexed Keyboard</u></a></li>
<li><a href="https://fox-links.techidaily.com/framing-character-arcs-on-screen-for-2024/"><u>Framing Character Arcs on Screen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-solution-for-fixing-error-code-0x80073d26/"><u>The Ultimate Solution for Fixing Error Code: 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-steps-to-navigate-windows-system-restore-functions/"><u>Simplified Steps to Navigate Windows' System Restore Functions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-bluescreen-mastery-through-11-fixes/"><u>Unraveling Windows 11 Bluescreen: Mastery Through 11 Fixes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-youtube-video-dimension-standards/"><u>[Updated] In 2024, YouTube Video Dimension Standards</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-effortless-transition-in-windows-terminals-attention-mode/"><u>Quick Fix: Effortless Transition in Windows Terminal’s Attention Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-pink-screens-in-windows-systems/"><u>Quick Fixes for Pink Screens in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-memory-use-on-win-11-os/"><u>Revamping Memory Use on Win 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-online-gaming-prevent-lol-disconnections-in-windows/"><u>Secure Online Gaming: Prevent LoL Disconnections in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-analyzing-the-roi-of-sns-hdr-pro-vs-other-hdr-tools/"><u>[Updated] Analyzing the ROI of SNS HDR Pro Vs. Other HDR Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-with-windows-11-safe-boot-tips/"><u>Troubleshoot With Windows 11 Safe Boot Tips</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-essential-list-15-books-shining-on-tiktoks-literary-scene/"><u>2024 Approved  Essential List  15 Books Shining on TikTok's Literary Scene</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strikes-winning-warfare-without-lag-in-star-wars-bf2/"><u>Swift Strikes: Winning Warfare Without Lag in Star Wars BF2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-5-drone-friendly-vr-experiences/"><u>Top 5 Drone-Friendly VR Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-defenders-0x80004004-issue/"><u>Breaking Down Windows Defender's 0X80004004 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-beginners-roadmap-to-google-maps-on-pc/"><u>The Beginner's Roadmap to Google Maps on PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-new-horizons-in-health-and-wellness-facebook-campaigns/"><u>[New] Exploring New Horizons in Health & Wellness Facebook Campaigns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-basics-to-blockbusters-building-an-audience-on-gaming-channels/"><u>[New] In 2024, From Basics to Blockbusters  Building an Audience on Gaming Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workspace-win-11s-finest-productivity-tools/"><u>Transform Your Workspace: Win 11'S Finest Productivity Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/spectre-3-clash-mirage-4-enters-the-fray-for-2024/"><u>Spectre 3 Clash  Mirage 4 Enters the Fray for 2024</u></a></li>
</ul></div>
