---
title: Guiding You Through Windows 11 Emulation on VMWare 17
date: 2024-09-11T01:20:48.946Z
updated: 2024-09-12T01:20:48.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guiding You Through Windows 11 Emulation on VMWare 17
excerpt: This Article Describes Guiding You Through Windows 11 Emulation on VMWare 17
keywords: Windows 11 VM Emulate,Win11 VMWare Guide,Virtualize Win11,Emulate Windows 11,Win11 on VMware,Win11 VM Emulation,Guided Win11 Virtualization
thumbnail: https://thmb.techidaily.com/a018e8a9f0d428a05e6f8e5f431115fbc243ce5256805ecd4c390c919b578ebe.jpg
---

## Guiding You Through Windows 11 Emulation on VMWare 17

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on[how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
2. A Windows 10 or above operating system with TPM 2.0 and virtualization support.
3. The latest version of VMware Workstation 17 Player must be pre-installed on the host system.
4. Adequate computing resources to run Windows 11 as a virtual machine. The list includes 64 GB disk space, 4 GB RAM, and a dual-core x64 processor.

 Once you have the necessary ISO file and the latest copy of VMware on your system, you can proceed to the virtual machine creation and Windows 11 installation.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Install Windows 11 in VMware Workstation 17 Player

 Firstly, we will create a virtual machine in VMware for Windows 11\. Then, we will install Windows 11 on the virtual machine. Lastly, we will install VMware tools to finish setting up the virtual machine.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### 1\. Create a Windows 11 Virtual Machine

 Here’s how to create a virtual machine for Windows 11 in VMware:

1. Launch VMware Player on your system. On the home page, click on**Create a new virtual machine** option.
2. Select the**I will install the operating system later** radio button and click on the**Next** button.  
![Creating a Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/creating-a-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

1. Click on the**Customize Hardware** button. Under the memory tab, increase the**RAM** allocation to**6 GB** or more to avoid a sluggish Windows 11 experience.
2. Switch to the**Processors** tab and allocate**4 or more cores** to the Windows virtual machine.
3. Next, move to the**New CD/DVD (SATA)** tab, and click on the**Use ISO image file** option located under the**Connection** section.
4. Click on the**Browse** button and select the Windows 11 ISO image file you previously downloaded. Click on the**Open** button.
5. Now, close the Hardware window and click on the**Finish** button to create the new virtual machine.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### 2\. Install Windows 11 on the Virtual Machine

 Repeat the following steps to install Windows 11 on the newly created virtual machine:

1. Navigate to the left-hand side menu and select the Windows 11 virtual machine. Click on the**Play virtual machine** option.
2. Press any keyboard key to boot from the ISO file. Pick the appropriate language and region and click on the**Next** button. Then, click on the**Install now** button.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. In the Windows setup window, click on the**I don’t have a product key** option.
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  




<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
3. Press**Win + E** to[launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.





<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Run Windows 11 on VMware Without Any Registry Hacks

 With TMP emulation, there is no need for registry tweaking to disable secure boot and TPM requirements on Windows 11\. All the features work fine, and you don’t need to switch to another hypervisor program. However, Oracle VirtualBox offers the same TPM virtualization and secure boot features.


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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-perfected-framing-for-fb-videos-implement-letterbox-and-dark-frame/"><u>[New] 2024 Approved Perfected Framing for FB Videos Implement Letterbox & Dark Frame</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-maximize-lenovos-recording-features-now/"><u>[New] Maximize Lenovo's Recording Features Now</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unlock-enhanced-audio-visual-sync-subtitle-addition-to-wmp/"><u>[New] Unlock Enhanced Audio-Visual Sync Subtitle Addition to WMP</u></a></li>
<li><a href="https://facebook.techidaily.com/curating-personalized-social-network-content-on-fb/"><u>Curating Personalized Social Network Content on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-features-essential-tips-for-windows-11-widgets/"><u>Cutting-Edge Features: Essential Tips for Windows 11 Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-windows-gpo-a-complete-guide-for-users/"><u>Deciphering Windows GPO: A Complete Guide for Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismiss-incompatible-prerequisite-message-in-win11/"><u>Dismiss Incompatible Prerequisite Message in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-reacting-to-faulty-windows-11-tools/"><u>Effective Strategies: Reacting to Faulty Windows 11 Tools</u></a></li>
<li><a href="https://program-issues.techidaily.com/get-back-on-air-with-these-7-remedies-for-when-your-twitch-live-stream-fails-to-launch/"><u>Get Back on Air with These 7 Remedies for When Your Twitch Live Stream Fails to Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-disabling-games-on-windows-11-list/"><u>Guide to Disabling Games on Windows 11 List</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-6s-plus-passcode-not-working-by-drfone-ios/"><u>How to Fix iPhone 6s Plus Passcode not Working?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-network-discovery-is-turned-off-error-on-windows/"><u>How to Fix the “Network Discovery Is Turned Off” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-load-windows-drivers-without-verification-obligations/"><u>How to Load Windows Drivers without Verification Obligations</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-samsung-galaxy-s23-fe-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Samsung Galaxy S23 FE Phones</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-realme-c67-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Realme C67 5G Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-microsofts-vcplusplus-release-rationale/"><u>Insight: Microsoft's VC++ Release Rationale</u></a></li>
<li><a href="https://win11-tips.techidaily.com/list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodology-for-amending-lost-drive-issue/"><u>Methodology for Amending Lost Drive Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-file-movement-in-windows-via-python-servers/"><u>Navigating File Movement in Windows via Python Servers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-seven-methods-to-enhance-memory-in-win11/"><u>Overcoming Obstacles: Seven Methods to Enhance Memory in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-your-mouse-trail-on-windows-machines/"><u>Personalizing Your Mouse Trail on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-problematic-chrome-file-uploaddownload-on-windows/"><u>Rectifying Problematic Chrome File Upload/Download on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/seamless-shifts-revitalizing-vhs-graphics-with-computer-magic/"><u>Seamless Shifts Revitalizing VHS Graphics with Computer Magic</u></a></li>
<li><a href="https://win-dash.techidaily.com/simple-steps-install-the-latest-epson-drivers-on-windows-without-a-hitch/"><u>Simple Steps: Install the Latest Epson Drivers on Windows Without a Hitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-wins-most-unusual-error-codes/"><u>Solutions for Win's Most Unusual Error Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-resource-occupied-errors-152-chars/"><u>Strategies to Overcome 'Resource Occupied' Errors (152 Chars)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamline-your-schedule-using-these-4-insights-on-chatgpt/"><u>Streamline Your Schedule Using These 4 Insights on ChatGPT</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-lowdown-on-the-latest-leaks-for-oculus-quest-3-lite-specs-pricing-and-release-schedule-uncovered/"><u>The Lowdown on the Latest Leaks for Oculus Quest 3 Lite – Specs, Pricing, and Release Schedule Uncovered!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-app-interference-with-windows-power-control/"><u>Troubleshooting App Interference with Windows Power Control</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-secrets-of-win-11-gaming-top-seven-strategies-for-gamers/"><u>Unlock the Secrets of Win 11 Gaming: Top Seven Strategies for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-past-enhance-retro-games-using-retroarchs-tools/"><u>Unlocking the Past: Enhance Retro Games Using RetroArch’s Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-the-rog-ally-asuss-steam-deck-competitor/"><u>What Is the ROG Ally, ASUS's Steam Deck Competitor?</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-xiaomi-14-ultra-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Xiaomi 14 Ultra Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>
