---
title: Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing
date: 2024-09-05T19:36:26.440Z
updated: 2024-09-06T19:36:26.440Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing
excerpt: This Article Describes Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing
keywords: Fixing HyViz Error in WinSandbox,Troubleshooting WinSandbox ZeroError,WinSandbox VM Boot Failure Resolution,Overcoming Sandbox Hypervisor Issue,Solving Windows Sandbox ZeroError,WinSandbox Missing Virtualization Fix,Correcting WinSandbox VMM Errors
thumbnail: https://thmb.techidaily.com/6ac471d87db668dcc4b6f87c6982a3ef4bb37e3fbffe0068ce8a47124a8a8199.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing

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

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out[how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-jumpstarting-instagram-celebrity-status/"><u>[New] 2024 Approved Jumpstarting Instagram Celebrity Status</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-breaking-down-the-three-stages-of-snapchat-calls-and-chats/"><u>[New] In 2024, Breaking Down the Three Stages of Snapchat Calls and Chats</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-mastering-fb-advertising-with-a-focus-on-video-content/"><u>[New] In 2024, Mastering FB Advertising with a Focus on Video Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-secrets-of-the-top-social-media-videos-for-2024/"><u>[New] Secrets of the Top Social Media Videos for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-best-6-social-media-platforms-for-business/"><u>[Updated] 2024 Approved Best 6 Social Media Platforms for Business</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-a-comprehensive-list-of-top-virtual-classrooms-not-inspired-by-udemy-for-2024/"><u>[Updated] A Comprehensive List of Top Virtual Classrooms Not Inspired by Udemy for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-how-to-make-your-instagram-pop-with-sharing-gifs-in-4-easy-steps-for-2024/"><u>[Updated] How to Make Your Instagram Pop with Sharing GIFs in 4 Easy Steps for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-mastering-youtube-video-capture-techniques-for-2024/"><u>[Updated] Mastering YouTube Video Capture Techniques for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-balancing-intense-beats-with-fl-studios-easeful-dimming/"><u>2024 Approved Balancing Intense Beats with FL Studio's Easeful Dimming</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/complete-guide-broadcasting-the-2024-olympic-games-in-real-time/"><u>Complete Guide: Broadcasting the 2024 Olympic Games in Real-Time</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-features-essential-tips-for-windows-11-widgets/"><u>Cutting-Edge Features: Essential Tips for Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-resolving-virtualbox-usb-connectivity-problems/"><u>Deciphering and Resolving VirtualBox USB Connectivity Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-gpo-a-complete-guide-for-users/"><u>Deciphering Windows GPO: A Complete Guide for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismiss-incompatible-prerequisite-message-in-win11/"><u>Dismiss Incompatible Prerequisite Message in Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/error-encountered-heres-why-input-not-supported-messages-appear-on-displays/"><u>Error Encountered? Here's Why 'Input Not Supported' Messages Appear on Displays</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/expert-tips-to-cut-through-false-social-endorsements/"><u>Expert Tips to Cut Through False Social Endorsements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-ipadiphone-picture-upload-error-a-detailed-guide-for-windows-users/"><u>Fixing the iPad/iPhone Picture Upload Error: A Detailed Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-disabling-games-on-windows-11-list/"><u>Guide to Disabling Games on Windows 11 List</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-disable-app-launch-tracking-in-windows/"><u>How to Disable App Launch Tracking in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-disk-management-could-not-start-virtual-disk-service-error/"><u>How to Fix the Windows “Disk Management Could Not Start Virtual Disk Service” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-errors-related-to-printmanagement-in-windows/"><u>How to Resolve Errors Related to 'Printmanagement' In Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-winerror-incorrect-file-backup-settings/"><u>How to Resolve WinError: Incorrect File Backup Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-steps-to-implement-personalized-lock-pattern-on-windows-11/"><u>Innovative Steps to Implement Personalized Lock Pattern on Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/mastering-xbox-ultimate-screen-capture-tips-for-2024/"><u>Mastering Xbox Ultimate Screen Capture Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-incorporating-law-filters-into-windows/"><u>Maximizing Efficiency: Incorporating LAW Filters Into Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodology-for-amending-lost-drive-issue/"><u>Methodology for Amending Lost Drive Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-file-movement-in-windows-via-python-servers/"><u>Navigating File Movement in Windows via Python Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-mouse-trail-on-windows-machines/"><u>Personalizing Your Mouse Trail on Windows Machines</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-oneplus-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on OnePlus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-reading-voice-in-ms-windows-document-editor/"><u>Reactivating Reading Voice in MS Windows Document Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-wlanextexe-low-cpu-drain-techniques/"><u>Reducing WLANEXT.EXE: Low CPU Drain Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstating-reliable-windows-protection-on-win-11/"><u>Reinstating Reliable Windows Protection on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-installer-errors-for-non-compatible-apps/"><u>Resolving Windows Installer Errors for Non-Compatible Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/restoring-iphone-xs-trust-reviving-biometric-lock/"><u>Restoring iPhone X's Trust Reviving Biometric Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-user-interface-master-8-bubble-ui-techniques-for-windows/"><u>Revolutionize Your User Interface: Master 8 Bubble UI Techniques for Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionize-your-writing-with-ai-6-methods-using-chatgpts-creative-potential/"><u>Revolutionize Your Writing with AI: 6 Methods Using ChatGPT's Creative Potential</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rise-above-the-norm-with-these-excellent-win-11-widgets/"><u>Rise Above the Norm with These Excellent Win 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-file-management-activating-windows-controlled-folder-access/"><u>Secure File Management: Activating Window’s Controlled Folder Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sever-onedrive-connection-with-ms-account-on-windows/"><u>Sever OneDrive Connection with MS Account on Windows</u></a></li>
<li><a href="https://fox-links.techidaily.com/smartphone-as-your-gateway-to-immersive-virtual-reality/"><u>Smartphone as Your Gateway to Immersive Virtual Reality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-wins-most-unusual-error-codes/"><u>Solutions for Win's Most Unusual Error Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-rectifying-windows-1110-nvidia-errors/"><u>Step-by-Step: Rectifying Windows 11/10 Nvidia Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-rectifying-path-not-found-error/"><u>Strategies for Rectifying Path Not Found Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-resource-occupied-errors-152-chars/"><u>Strategies to Overcome 'Resource Occupied' Errors (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-rectify-windows-update-x8024a205-mistake/"><u>Strategies to Rectify Windows Update X8024A205 Mistake</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-methods-for-scaling-photos-on-windows-11/"><u>Top 6 Methods for Scaling Photos on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-interference-with-windows-power-control/"><u>Troubleshooting App Interference with Windows Power Control</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-tips-for-a-smooth-halo-3-experience-without-any-pc-interruptions/"><u>Troubleshooting Tips for a Smooth Halo 3 Experience without Any PC Interruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-control-enable-users-and-groups-in-windows-homes/"><u>Unleash Control: Enable Users & Groups in Windows Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-of-win-11-gaming-top-seven-strategies-for-gamers/"><u>Unlock the Secrets of Win 11 Gaming: Top Seven Strategies for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-past-enhance-retro-games-using-retroarchs-tools/"><u>Unlocking the Past: Enhance Retro Games Using RetroArch’s Tools</u></a></li>
</ul></div>
