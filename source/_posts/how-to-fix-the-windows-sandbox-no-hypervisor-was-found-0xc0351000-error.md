---
title: How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
date: 2024-07-12T17:41:08.636Z
updated: 2024-07-13T17:41:08.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
excerpt: This Article Describes How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error
keywords: Windows Sandbox Error 0XC0351000,Fixing Windows Sandbox Hypervisor Missing,Resolve Windows Sandbox No Hypervisor,Windows Sandbox ZeroError,Troubleshoot Windows Sandbox Failure,Windows Sandbox Hyperlink Issue,Curing 0XC0351000 Error in Sandbox
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## How to Fix the Windows Sandbox No Hypervisor Was Found 0XC0351000 Error

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
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-for-placing-program-shortcuts-on-desktop/"><u>Efficient Strategies for Placing Program Shortcuts on Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-leading-winners-for-windows/"><u>Boost Performance: Leading Winners for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-network-access-on-windows-10-and-11-through-telnet/"><u>Boosting Network Access on Windows 10 & 11 Through Telnet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-narrative-voice-with-windows-11-tools/"><u>Crafting Narrative Voice with Windows 11 Tools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-viral-video-quarterly-watch-for-2024/"><u>[New] Viral Video Quarterly Watch for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-photo-perfection-highest-rated-phone-tripods/"><u>In 2024, Photo Perfection  Highest Rated Phone Tripods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-xbox-game-pass-error-code-0x00000001-on-windows-os/"><u>Troubleshooting Xbox Game Pass Error Code 0X00000001 on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-frozen-windows-update-pause/"><u>Eliminate Frozen Windows Update Pause</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-start-screen-links-in-win11s-options/"><u>Adjusting Start Screen Links in Win11's Options</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-rediscover-classics-at-your-fingertits-pick-from-the-ultimate-5-gb-emulator-list-on-pc/"><u>[New] 2024 Approved  Rediscover Classics at Your Fingertits  Pick From The Ultimate 5 GB Emulator List on PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-itel-s23-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Itel S23 FRP Without Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choose-freedom-for-windows-chatai-freedomgpt/"><u>Choose Freedom for Windows ChatAI: FreedomGPT</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-forging-a-massive-online-following-on-facebook/"><u>[Updated] 2024 Approved  Forging a Massive Online Following on Facebook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-cameras-unsuccessful-save-attempts/"><u>Decoding Windows Camera's Unsuccessful Save Attempts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-outlooks-failing-notification-system-a-user-friendly-approach/"><u>Troubleshooting Outlook's Failing Notification System: A User-Friendly Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/update-with-ease-a-guide-for-surface-computer-owners/"><u>Update with Ease: A Guide for Surface Computer Owners</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-realme-narzo-60-pro-5g-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Realme Narzo 60 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/creating-a-safe-digital-playground-windows-11-controls/"><u>Creating a Safe Digital Playground: Windows 11 Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciding-the-best-drive-for-your-xbox-games/"><u>Deciding the Best Drive for Your Xbox Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-data-safety-embedding-secure-passwords-into-files/"><u>Elevate Data Safety: Embedding Secure Passwords Into Files</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-realme-c67-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-vpn-connections-failed-on-windows/"><u>Troubleshooting VPN Connections Failed on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-icon-order-in-windows/"><u>Tips for Restoring Icon Order in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-redmi-note-12-pro-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi Redmi Note 12 Pro 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-battery-life-awareness-charge-notification-tips-for-windows-11/"><u>Enhancing Battery Life Awareness: Charge Notification Tips for Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/elevate-your-social-strategy-with-these-top-8-apps-phones-included/"><u>Elevate Your Social Strategy with These Top 8 Apps, Phones Included</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ways-to-streamline-win11s-print-management-max-52-chars/"><u>Ways to Streamline Win11’s Print Management (Max 52 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-premier-6-task-tracking-tools-for-windows-users/"><u>Unveiling The Premier 6 Task-Tracking Tools for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-innovative-methods-to-improve-your-windows-update-process/"><u>7 Innovative Methods to Improve Your Windows Update Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cloak-the-ctrl-secure-settings-in-win-1011/"><u>Cloak the CTRL - Secure Settings in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-discord-install-problems-on-windows-11/"><u>Bypassing Discord Install Problems on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-and-mending-internal-error-with-windows-11s-rdp/"><u>Avoiding and Mending Internal Error with Windows 11'S RDP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-design-mastering-windows-11s-theme-customization/"><u>Dive Into Design: Mastering Windows 11'S Theme Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-next-chapter-begins-with-moment-22h2s-features/"><u>Windows 11'S Next Chapter Begins With Moment #22H2's Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11s-shortcut-for-seamless-sticky-note-entry/"><u>Win11's Shortcut for Seamless Sticky Note Entry</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/start-streaming-on-youtube-with-an-introductory-obs-course-for-2024/"><u>Start Streaming on Youtube with an Introductory OBS Course for 2024</u></a></li>
</ul></div>
