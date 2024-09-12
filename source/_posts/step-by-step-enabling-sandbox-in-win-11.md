---
title: "Step-by-Step: Enabling Sandbox in Win 11"
date: 2024-09-11T01:24:28.220Z
updated: 2024-09-12T01:24:28.220Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Enabling Sandbox in Win 11"
excerpt: "This Article Describes Step-by-Step: Enabling Sandbox in Win 11"
keywords: Win 11 Sandbox,Enable Windows Sandbox,PC Sandboxing Guide,Win 11 Security Feature,Activate OS Xbox Mode,Secure Sandbox Setup,Sandbox in Windows 11
thumbnail: https://thmb.techidaily.com/ae43e169f6c755c4c2193b461c421a8ddcf3ffe9401c395fee54d3c5c1d37695.jpg
---

## Step-by-Step: Enabling Sandbox in Win 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115941/19272" target="_top" id="2115941">
  <img src="//a.impactradius-go.com/display-ad/19272-2115941" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-the-ultimate-tutorial-for-instagram-story-polls/"><u>[New] 2024 Approved The Ultimate Tutorial for Instagram Story Polls</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-exploring-the-universe-of-gesture-technology/"><u>[New] Exploring the Universe of Gesture Technology</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-instagram-edge-bulk-image-and-video-post-strategies-explored/"><u>[New] In 2024, The Instagram Edge Bulk Image and Video Post Strategies Explored</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-ace-your-videos-essential-editors-for-youtube/"><u>[Updated] Ace Your Videos Essential Editors for YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-essential-free-services-for-designing-impactful-youtube-intros-for-2024/"><u>[Updated] Essential Free Services for Designing Impactful YouTube Intros for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hero-11-and-max-360-comparing-the-bests-in-gopros-world/"><u>2024 Approved Hero 11 and Max 360 Comparing the Bests in GoPro's World</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unraveling-the-metaverse-an-analysis-of-6-complex-instances/"><u>2024 Approved Unraveling the Metaverse An Analysis of 6 Complex Instances</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-infinix-hot-30-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Infinix Hot 30 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/breaking-down-the-features-of-samsungs-recent-phone-launch/"><u>Breaking Down the Features of Samsung's Recent Phone Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-the-windows-fatal-blue-screen-error-0x8007007e/"><u>Clearing Up the Windows Fatal Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-remedying-error-0x8007000d-on-pcs/"><u>Deciphering and Remedying 'Error 0X8007000D' On PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deconstructing-mmc-glitches-resolving-snap-in-crashes/"><u>Deconstructing MMC Glitches: Resolving Snap-In Crashes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-iphone-15-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/discover-the-leading-universal-dvd-players-of-2024-a-comprehensive-review-for-all-regions/"><u>Discover the Leading Universal DVD Players of 2024: A Comprehensive Review for All Regions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-how-copilot-key-upgrades-your-windows-11-experience/"><u>Discovering How Copilot Key Upgrades Your Windows 11 Experience</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-epson-wf-3540-printer-drivers-on-your-pc-with-windows-os/"><u>Download & Install Epson WF-3540 Printer Drivers on Your PC with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-routes-to-activate-windows-11s-calculator/"><u>Efficient Routes to Activate Windows 11'S Calculator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-these-top-7-tips-36/"><u>Elevate Your Windows Experience with These Top 7 Tips (36)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-net-runtime-errors-in-microsoft-os/"><u>Eliminating .NET Runtime Errors in Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-characters-with-windows-11-map-tool/"><u>Explore Characters with Windows 11 Map Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-guide-enhance-windows-bluetooth-device-with-full-sound-features/"><u>Fix Guide: Enhance Windows Bluetooth Device with Full Sound Features</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-bug-detected-now-fixed-by-nvidia-drivers/"><u>Graphics Bug Detected, Now Fixed by NVIDIA Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-add-trusted-sites-on-windows-11/"><u>How to Add Trusted Sites on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-uninstall-wsl-on-windows-11-and-11/"><u>How to Completely Uninstall WSL on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-into-and-out-of-the-windows-terminals-focus-mode/"><u>How to Get Into and Out of the Windows Terminal’s Focus Mode</u></a></li>
<li><a href="https://buynow-info.techidaily.com/hp-zbook-firefly-15-g8-user-analysis-unveiling-the-ultimate-laptop/"><u>HP ZBook Firefly 15 G8 User Analysis: Unveiling the Ultimate Laptop</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-acquisitions-starting-off-with-profitable-youtube-channel-buys/"><u>Ideal Acquisitions Starting Off with Profitable YouTube Channel Buys</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-oneplus-nord-3-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From OnePlus Nord 3 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Vivo Y200e 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-secret-sauce-of-profitable-fb-ads-with-dynamic-animation/"><u>In 2024, The Secret Sauce of Profitable FB Ads with Dynamic Animation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twittervidstowebm-direct-media-conversion/"><u>In 2024, TwitterVidsToWebM Direct Media Conversion</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-windows-11-auditory-setup-a-how-to/"><u>In 2024, Windows 11 Auditory Setup A How-To</u></a></li>
<li><a href="https://win-blog.techidaily.com/level-up-your-gaming-experience-fixing-ping-problems-in-chivalry-2-with-latest-tips-and-tricks/"><u>Level Up Your Gaming Experience: Fixing Ping Problems in Chivalry 2 with Latest Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-package-accessibility-a-step-by-step-windows-solution/"><u>Mastering Package Accessibility: A Step-by-Step Windows Solution</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-in-computing-with-tomhardware/"><u>Navigating the Latest in Computing with TomHardware</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-inactive-wsreset-troubleshooting-steps/"><u>Navigating Through Inactive WSReset Troubleshooting Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/organizing-and-naming-pro-level-windows-approach-max-156/"><u>Organizing & Naming: Pro-Level Windows Approach (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-wi-fi-discovery-issues/"><u>Overcoming Windows 11'S Wi-Fi Discovery Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-based-thx-audio-glitches/"><u>Overcoming Windows-Based THX Audio Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/retrogame-enhancement-via-retroarchs-advanced-shading-features/"><u>RetroGame Enhancement via RetroArch’s Advanced Shading Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-keyboard-use-redefine-functionality-via-fn-keys-on-windows-11/"><u>Revolutionize Keyboard Use: Redefine Functionality via FN Keys on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-user-specific-ms-errors/"><u>Steps to Eliminate User-Specific MS Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stopping-inadvertent-command-triggers-in-operating-system/"><u>Stopping Inadvertent Command Triggers in Operating System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-tips-for-maximizing-wsl-2-in-windows/"><u>Top 5 Tips for Maximizing WSL 2 in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-purpose-of-an-x-symbol-for-your-drives/"><u>Understanding the Purpose of an X Symbol for Your Drives</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unleash-your-potential-skyrocketing-youtube-audience-for-2024/"><u>Unleash Your Potential Skyrocketing YouTube Audience for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-efficiency-mastering-the-toolbar-functionality-on-w11-os/"><u>Unveiling Efficiency: Mastering the Toolbar Functionality on W11 OS</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Infinix Hot 30i | Dr.fone</u></a></li>
</ul></div>




