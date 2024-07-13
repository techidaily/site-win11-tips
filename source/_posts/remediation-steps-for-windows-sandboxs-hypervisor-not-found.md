---
title: Remediation Steps for Windows Sandbox's Hypervisor Not Found
date: 2024-07-12T16:44:19.240Z
updated: 2024-07-13T16:44:19.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remediation Steps for Windows Sandbox's Hypervisor Not Found
excerpt: This Article Describes Remediation Steps for Windows Sandbox's Hypervisor Not Found
keywords: WinSandbox Fix Guide,Hypervisor Recovery,Sandbox Error Resolution,Virtualization Troubleshooting,Hyper-V Missing Issue,Windows VM Repair Steps,Boot Failure Remediation
thumbnail: https://thmb.techidaily.com/865974c7bb05387b6277d30c79ecdc49aad19ee23c97d33e5069a1776373f52c.jpg
---

## Remediation Steps for Windows Sandbox's Hypervisor Not Found

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS
![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.


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
<li><a href="https://win11-tips.techidaily.com/a-guide-to-the-most-ignored-yet-crucial-windows-11-features/"><u>A Guide to the Most Ignored Yet Crucial Windows 11 Features</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unveiling-the-art-of-quiet-video-capture-methods/"><u>[Updated] Unveiling the Art of Quiet Video Capture Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activation-procedure-for-windows-photo-viewer-in-win11/"><u>Activation Procedure for Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-add-timestamp-on-youtube-video-link-desktop-and-mobile-for-2024/"><u>[Updated] How to Add Timestamp on YouTube Video Link? [Desktop and Mobile] for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719306931208-opening-troubled-chrome-remediation-tips-for-win11-users-here/"><u>Opening Troubled Chrome: Remediation Tips for Win11 Users Here.</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-trouble-with-iphone-15-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>In 2024, Trouble with iPhone 15 Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-access-boosting-morning-routine-and-note-openings/"><u>Accelerated Access: Boosting Morning Routine & Note Openings</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/revolutionize-your-feed-with-these-10-insta-tools/"><u>Revolutionize Your Feed with These 10 Insta-Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719298161302-overcoming-grayed-out-screensaver-in-win-os-top-fixes/"><u>Overcoming Grayed-Out Screensaver in Win OS: Top Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-optimum-ssd-speed-on-windows-via-ssdfresh/"><u>Achieve Optimum SSD Speed on Windows via SSDFresh</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tips-to-tell-if-your-pc-needs-restarting/"><u>5 Tips to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-x-flip-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo X Flip to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-steams-offline-content-servers-problem-in-windows/"><u>Addressing Steam's Offline Content Servers Problem in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/hack-the-airwaves-mastering-a-viral-solo-podcast/"><u>Hack the Airwaves  Mastering a Viral Solo Podcast</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-tricks-to-optimize-live-streaming-of-your-snapchat-content/"><u>[Updated] 2024 Approved  Tricks to Optimize Live Streaming of Your Snapchat Content</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-sites-for-secure-and-quick-download-of-youtube-ringtones/"><u>2024 Approved  Exclusive Sites for Secure & Quick Download of YouTube Ringtones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guidetosettingupdarkinterfaceonwinnotepad/"><u>A GuideToSettingUpDarkInterfaceOnWinNotepad</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284654722-software-environment-setup/"><u>Software Environment Setup:</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-win11-tips-for-optimal-performance/"><u>Master Win11  Tips for Optimal Performance</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlocking-virtual-potential-with-kinemasters-latest-android-release/"><u>[New] Unlocking Virtual Potential with KineMaster's Latest Android Release</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-cutting-edge-top-11-list-of-soundscape-capturers/"><u>[New] 2024 Approved  Cutting-Edge Top 11 List of Soundscape Capturers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-beginners-path-to-mastering-mouse-controls-on-win11/"><u>A Beginner's Path to Mastering Mouse Controls on Win11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-practical-ways-to-resize-video-in-handbrake-for-2024/"><u>Updated Practical Ways to Resize Video in Handbrake for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/keeping-your-creative-content-on-ios-with-ease/"><u>Keeping Your Creative Content on iOS with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-windows-11s-fast-assist-procedure/"><u>Activating Windows 11’S Fast Assist Procedure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-tricks-to-correct-your-pcs-pink-screen-misstep/"><u>5 Tricks to Correct Your PC's Pink Screen Misstep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719370071964-resolve-wwin-plus-p-non-functionality-in-windows-systems/"><u>Resolve WWin + P Non-Functionality in Windows Systems.</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-crafting-clear-sounds-on-mac-an-analysis-of-the-top-5-audio-mixers/"><u>2024 Approved Crafting Clear Sounds on Mac An Analysis of the Top 5 Audio Mixers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-detailed-walkthrough-of-using-system-restore-in-windows-os/"><u>A Detailed Walkthrough of Using System Restore in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-handy-tutorial-to-combat-xfffeeee-in-windows/"><u>A Handy Tutorial to Combat XFFFEEEE in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-merging-youtube-melodies-in-cinematic-pieces/"><u>[New] Merging YouTube Melodies in Cinematic Pieces</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professionals-picks-windows-11-video-creation-apps/"><u>In 2024, Professionals' Picks  Windows 11 Video Creation Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-ways-to-create-a-windows-11-bootable-usb-drive/"><u>3 Ways to Create a Windows 11 Bootable USB Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-sevenfold-approach-to-fix-sync-errors-with-google-drive/"><u>A Sevenfold Approach to Fix Sync Errors with Google Drive</u></a></li>
</ul></div>
