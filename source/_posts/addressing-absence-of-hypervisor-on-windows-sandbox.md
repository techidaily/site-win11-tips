---
title: Addressing Absence of Hypervisor on Windows Sandbox
date: 2024-08-16T01:12:58.813Z
updated: 2024-08-17T01:12:58.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Absence of Hypervisor on Windows Sandbox
excerpt: This Article Describes Addressing Absence of Hypervisor on Windows Sandbox
keywords: Hypervisor Lack in WSandbox,WinOS Hypervisor Missing,Windows Sandbox No VMware,Sandbox without Virtualization,Hypervisor Absence on Windows,Void Hypervisor on WIndows,No Hypervisor on Windows SBox
thumbnail: https://thmb.techidaily.com/e2b01a1128735e3ec5310f2cbee0a0035159bd501806692c9cb150d9959d92bc.jpg
---

## Addressing Absence of Hypervisor on Windows Sandbox

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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-restoring-your-obs-cameras-integrated-functionality/"><u>[New] 2024 Approved  Restoring Your OBS Camera’s Integrated Functionality</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-advanced-color-techniques-incorporating-luts-for-cinematic-flair/"><u>[New] Advanced Color Techniques  Incorporating Luts for Cinematic Flair</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-bridging-twitter-and-fb-with-shared-vids-for-2024/"><u>[New] Bridging Twitter and FB with Shared Vids for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-back-in-the-past-with-snapchats-animation-hacks/"><u>[New] In 2024, Back in the Past with Snapchat's Animation Hacks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-metaverse-mayhem-top-party-games-listed/"><u>[New] Metaverse Mayhem  Top Party Games Listed</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-clearer-picture-remove-borders-and-boost-recording-quality-for-2024/"><u>[New] The Clearer Picture  Remove Borders and Boost Recording Quality for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-from-console-to-community-livestream-your-xbox/"><u>[Updated] 2024 Approved  From Console to Community  Livestream Your Xbox</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-hero5-black-meets-yi-4k-the-ultimate-update-for-action-camera-fans/"><u>[Updated] Hero5 Black Meets Yi 4K - The Ultimate Update for Action Camera Fans</u></a></li>
<li><a href="https://win11-tips.techidaily.com/10-essential-solutions-for-troubleshooting-missing-wireless-connections-in-windows-10/"><u>10 Essential Solutions for Troubleshooting Missing Wireless Connections in Windows 10</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-to-eradicating-d3d11-errors-in-w11-and-w10/"><u>A Step-by-Step Approach to Eradicating D3D11 Errors in W11 & W10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-locked-windows-11-themes-through-registry-expertise/"><u>Accessing Locked Windows 11 Themes Through Registry Expertise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-network-unity-wi-fi-plus-ethernet-integration-in-windows/"><u>Achieving Network Unity: Wi-Fi + Ethernet Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-empty-directory-alert-in-windows-11/"><u>Addressing Empty Directory Alert in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-default-screen-saver-in-windows-11/"><u>Adjusting Default Screen Saver in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-efficient-voice-access-on-windows/"><u>Advanced Tips for Efficient Voice Access on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/android-integration-in-windows-11-for-effective-multitasking/"><u>Android Integration in Windows 11 for Effective Multitasking</u></a></li>
<li><a href="https://win11-tips.techidaily.com/arrow-key-calm-a-guide-for-win-users/"><u>Arrow Key Calm: A Guide for Win Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-inquiries-stealthy-strategies-for-secure-credentials-in-win-11/"><u>Avoiding Inquiries: Stealthy Strategies for Secure Credentials in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banishing-yellow-shade-from-laptop-panels/"><u>Banishing Yellow Shade From Laptop Panels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/battle-bugs-tackling-skyrims-extension-failure/"><u>Battle Bugs: Tackling Skyrim's Extension Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-fit-selecting-vms-that-thrive-on-windows-11-platforms/"><u>Best Fit: Selecting VMs That Thrive On Windows 11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/black-friday-special-612-unlimited-win10-life/"><u>Black Friday Special: $6.12, Unlimited Win10 Life</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-dedicated-video-ram-capacity-on-modern-windows/"><u>Boost Dedicated Video RAM Capacity on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-performance-by-rebooting-windows-11-ram/"><u>Boost Performance by Rebooting Windows 11 RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-by-mastering-task-management-on-a-windows-11-pc/"><u>Boost Productivity by Mastering Task Management on a Windows 11 PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-productivity-harness-windows-smart-launcher-techniques/"><u>Boost Productivity: Harness Windows' Smart Launcher Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-start-menu-efficiency-in-the-world-of-windows-11/"><u>Boost Your Start Menu Efficiency in the World of Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-apps-with-efficient-internet-fixes/"><u>Boost Your Windows Apps with Efficient Internet Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-edges-app-guard-with-enhanced-graphics/"><u>Boosting Edge's App Guard with Enhanced Graphics</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-zte-axon-40-lite-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting ZTE Axon 40 Lite Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-infinix-gt-10-pro-phone-by-drfone-android/"><u>How to Unlock a Network Locked Infinix GT 10 Pro Phone?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6-plus-by-drfone-ios/"><u>How to Unlock iPhone 6 Plus?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-from-your-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID From Your Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-social-media-blend-adding-youtube-content-to-stories/"><u>In 2024, Social Media Blend  Adding YouTube Content to Stories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/influencing-up-a-comprehensive-instagram-growth-strategy-for-2024/"><u>Influencing Up  A Comprehensive Instagram Growth Strategy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-13-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status On Your iPhone 13</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-s24-ultra-video-recovery-recover-deleted-videos-from-samsung-galaxy-s24-ultra-by-fonelab-android-recover-video/"><u>Samsung Galaxy S24 Ultra Video Recovery - Recover Deleted Videos from Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719327147890-secrets-to-perfect-full-screen-snipping-with-windows-toolkit/"><u>Secrets to Perfect Full-Screen Snipping with Windows' Toolkit</u></a></li>
<li><a href="https://buynow-info.techidaily.com/ultimate-guide-to-the-most-innovative-runners-smartwatches/"><u>Ultimate Guide to the Most Innovative Runner's Smartwatches</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-top-free-gif-animators-for-endless-loops/"><u>Updated Top Free GIF Animators for Endless Loops</u></a></li>
</ul></div>
