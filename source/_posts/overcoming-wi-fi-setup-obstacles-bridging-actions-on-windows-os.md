---
title: "Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS"
date: 2024-08-28T01:18:28.829Z
updated: 2024-08-29T01:18:28.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS"
excerpt: "This Article Describes Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS"
keywords: Wi-Fi Setup Guide,Overcome Connection Issues,Windows Network Fix,Troubleshoot Wi-Fi,Optimize Windows Connectivity,Fixing OS Internet Problems,Resolve Wi-Fi on PCs
thumbnail: https://thmb.techidaily.com/ce2b50426ded5a960fb87586d9bc144c1e1a55defefae42789a30b646b9173fc.jpeg
---

## Overcoming Wi-Fi Setup Obstacles: Bridging Actions on Windows OS

 The "Action needed" prompt for Wi-Fi in Windows pops up when users try to connect to a Wi-Fi network on their devices and can occur with both new and old/trusted networks.

 Below, we discuss the common causes of this problem alongside the troubleshooting methods you can try to fix this issue once and for all.

## 1\. Disable the NCSI Probe From Windows Registry

 In most cases, the "Action Needed" prompt appears when there are corporate Wi-Fi networks with multiple endpoints available. This prompt is associated with the Network Connectivity Status Indicator (NCSI) feature, which verifies the network connection and internet access.

 Occasionally, the NCSI feature may mistakenly trigger this prompt while performing network connectivity checks, even if the network is functioning properly.

 To fix this problem, you can manually disable the NCSI Active probe via Windows Registry. However, before you proceed, we recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Choose **Yes** in the User Account Control prompt.
4. Inside the Registry Editor, navigate to the location below:  
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet
5. Move to the right pane and right-click on the **EnableActiveProbing** value.  
![EnableActiveProbing key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-active-probing-key.jpg)

1. Type 0 in the text field for Value data and click **OK**.
2. Now, navigate to the following location:  
HKLM\Software\Policies\Microsoft\Windows\NetworkConnectivityStatusIndicator
3. Move to the right side and right-click on an empty space.
4. Choose **New** \> **DWORD (32-bit) Value** and rename it as **NoActiveProbe**.  
![NoActiveProbe key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/no-active-probe.jpg)
5. Double-click on this newly created value and change its value data to 1\.
6. Now, create another value the same way and name it as DisablePassivePolling.
7. Double-click on **DisablePassivePolling** and change its value data to 1 as well.  
![DisablePassivePolling key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disable-passive-polling.jpg)
8. Click **OK** to save the changes and exit the Registry Editor.
9. Finally, restart your computer and upon reboot, check if the problem is resolved.

## 2\. Disable the NCSI Probe From GPE

 If using the Windows Registry did not work, you can also make the same changes using the Group Policy Editor.

 Follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "gpedit.msc" in Run and click **Enter**.
3. Choose **Yes** in the User Account Control prompt.
4. In the Group Policy Editor, navigate to the location below:  
​​​​​​​​​​​​​​Computer Configuration\Administrative Templates\System
5. Select **Internet Communication Management** \> **Internet Communication Settings** and click on **Turn off Windows Network Connectivity Status Indicator active tests**.  
![Network connectivity test policy in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/network-connectivity-test-policy.jpg)
6. Checkmark the box with **Enabled** and click **Apply** \> **OK** to save the changes.
7. Next, head over to the following location:  
​​​​​​​​​​​​​​Computer Configuration\Administrative Templates\Network
8. Select **Network Connectivity Status Indicator** \> **Specify passive polling**.  
![Specify passive polling policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/specify-passive-polling-policy.jpg)
9. Choose **Enabled** and click **Apply** \> **OK** to save the changes.
10. Close the Group Policy Editor and restart your computer.

 Hopefully, upon reboot, the issue will no longer appear.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Internet Connection Troubleshooter

 If the scenarios we have discussed above do not apply to you, you might also be facing the problem because of a temporary glitch in the system. In this case, you can run the internet connection troubleshooter. This is a built-in utility that scans your system for underlying related issues. If a problem is identified, it will either fix it for you or suggest a solution that you can apply automatically.

 Here is how you can run it:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Click on **System** and choose **Troubleshoot**.
3. Choose **Other troubleshooters**.
4. You should now be able to see a list of troubleshooters offered by Windows. Locate the Internet connection troubleshooter and click on the **Run** button for it.  
![Internet Connection Troubleshooter in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/internet-connection-troubleshooter.jpg)
5. Wait for the troubleshooter to complete its scan and once done, check if a problem is identified. If it is, click on the **Apply this fix** option. You can also apply a solution manually.
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In case the troubleshooter fails to identify the culprit, click on **Close the troubleshooter** option and move to the next method below.

## 4\. Disable Fast Startup

 You might also be facing the issue if the fast startup feature is interfering with network-related processes in Windows. If this feature is enabled on your computer, disabling it might help fix the underlying error as this will allow the system to completely shut down, which can help in refreshing network settings and resolving any network-related issues.

 Here is how you can proceed:

1. Open Run by pressing the **Win** \+ **R** keys together.
2. Type "control" and click **Enter**.
3. In the Control Panel, expand the **View by** section and choose **Large icons**.
4. Click on **Power Options** from the list and select **Choose what the power buttons do**.  
![Choose what the power button does option of Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/choose-what-the-power-button-does.jpg)
5. Choose **Change settings that are currently unavailable** and navigate to the Shutdown settings option.
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Uncheck the box associated with **Turn on fast startup (recommended)**.  
![Disable Fast Startup on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-fast-startup-on-windows.jpg)
7. Click on the **Save changes** button and exit Control Panel. Check if the issue is now resolved.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Try These Additional Generic Fixes

 If the specific fixes we have listed above have not worked for you, there are some additional fixes related to the network errors in Windows that you can try.

 These include updating the network drivers, re-enabling your wireless network adapter, installing the latest system updates, and resetting the network configurations on your computer. Our guide on[how to fix common Windows network errors](https://www.makeuseof.com/not-connected-any-networks-error-windows/) discusses all of these in detail, so you can head over there for step-by-step instructions.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## Fixing Network Connections in Windows Made Easy

 Network-related issues in Windows can be annoying, especially if they are preventing you from establishing a stable connection. Hopefully, the steps listed above will help you fix the "Action needed" problem for good.

 If you ever need to undo the changes that you made in the Registry Editor or GPE to fix this issue, simply re-enable the respective keys and policies by visiting the locations we have mentioned above in this guide. You can also contact the official Microsoft support team if the error appears even after you have tried all the solutions.

 Below, we discuss the common causes of this problem alongside the troubleshooting methods you can try to fix this issue once and for all.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-in-depth-examination-hero4-black-innovation-for-2024/"><u>[New] In-Depth Examination  Hero4 Black Innovation for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-small-companys-guide-to-the-safest-online-chat-services/"><u>[New] Small Company's Guide to the Safest Online Chat Services</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-cost-effective-options-top-10-free-high-quality-desktop-recorders-for-2024/"><u>[Updated] Cost-Effective Options  Top 10 Free, High-Quality Desktop Recorders for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-pursuit-of-visual-excellence-10-essential-iphone-composition-techniques-for-2024/"><u>[Updated] Pursuit of Visual Excellence  10 Essential iPhone Composition Techniques for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-airborne-mass-movers-selecting-the-best-drones/"><u>2024 Approved  Airborne Mass Movers  Selecting the Best Drones</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-seamless-music-integration-transform-your-favorite-tunes-into-youtube-content/"><u>2024 Approved  Seamless Music Integration  Transform Your Favorite Tunes Into YouTube Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-windows-n-releases-tech-enthusiasts-guide/"><u>Comparing Windows N Releases: Tech Enthusiast's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-individualized-win11-screensavers/"><u>Designing Individualized Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/differences-highlighted-microsoft-and-local-account-divergences-on-pc/"><u>Differences Highlighted: Microsoft and Local Account Divergences on PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-guide-to-installing-epson-xp-245-drivers-on-your-pc-with-windows-7-8-or-10/"><u>Easy Guide to Installing Epson XP-245 Drivers on Your PC with Windows 7, 8 or 10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/elite-5-digital-media-screenshots/"><u>Elite 5 Digital Media Screenshots</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/final-version-dragon-ball-z-kakarot-with-all-prior-glitches-corrected/"><u>Final Version Dragon Ball Z: Kakarot with All Prior Glitches Corrected</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-on-win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-on-fixing-the-failed-to-initiate-lunar-client-issue/"><u>Focusing on Fixing the Failed to Initiate Lunar Client Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-troubleshooting-display-with-windows-drivers/"><u>Guide to Troubleshooting Display with Windows Drivers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-13-with-a-mask-on-by-drfone-ios/"><u>How to Unlock iPhone 13 with a Mask On</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-fixing-windows-headset-mic-glitches/"><u>Identifying & Fixing Windows Headset Mic Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-tactics-to-outwit-windows-sign-in-prompts/"><u>Ingenious Tactics to Outwit Windows Sign-In Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locate-windows-picture-cache-point/"><u>Locate Window’s Picture Cache Point</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-conflict-multiple-ms-logins/"><u>Mastering Device Conflict: Multiple MS Logins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-pc-troubles-try-our-top-10-tools/"><u>Navigating PC Troubles? Try Our Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-low-valorant-download-rate-woes-in-windows/"><u>Overcoming Low Valorant Download Rate Woes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/podcast-perfection-on-pc-win-five-no-cost-filters/"><u>Podcast Perfection on PC: Win Five No-Cost Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieten-the-high-contrast-in-windows-ui/"><u>Quieten the High Contrast in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-looks-like-youre-stranded-from-xbox-app-windows/"><u>Removing the 'Looks Like You're Stranded' From Xbox App Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-offon-windows-11s-online-scan-feature/"><u>Switching Off/On Windows 11'S Online Scan Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-vivo-t2-pro-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Vivo T2 Pro 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-easy-route-to-your-pcs-credential-vault-on-win11/"><u>The Quick and Easy Route to Your PC's Credential Vault on Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-ultimate-guide-to-unlocking-your-iphone-xs-max-on-metropcs-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Your iPhone XS Max on MetroPCS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-for-smooth-captions-essential-tips-on-windows-10/"><u>Troubleshoot for Smooth Captions: Essential Tips on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-path-related-issues-in-windows-os/"><u>Troubleshooting Path-Related Issues in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-security-settings-for-general-pc-users-in-windows/"><u>Tweaking Security Settings for General PC Users in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undo-customization-reverting-win11-user-permissions/"><u>Undo Customization: Reverting Win11 User Permissions</u></a></li>
<li><a href="https://fox-http.techidaily.com/unlocking-skypes-full-capacity-with-effective-zoom-methods/"><u>Unlocking Skype's Full Capacity with Effective Zoom Methods</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlocking-the-secrets-of-macos-15-sequoia-projected-launch-timeline-enhanced-tools-and-breaking-information/"><u>Unlocking the Secrets of MacOS 15 'Sequoia': Projected Launch Timeline, Enhanced Tools & Breaking Information</u></a></li>
<li><a href="https://hardware-help.techidaily.com/usb-30-driver-software-get-latest-version-for-windows-10-free/"><u>USB 3.0 Driver Software: Get Latest Version for Windows 10 Free</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-in-windows-should-you-delete-it/"><u>What Is Pagefile.sys in Windows? Should You Delete It?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>