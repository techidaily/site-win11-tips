---
title: Optimizing USB Security in Modern Operating Systems
date: 2024-08-16T02:36:56.488Z
updated: 2024-08-17T02:36:56.488Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing USB Security in Modern Operating Systems
excerpt: This Article Describes Optimizing USB Security in Modern Operating Systems
keywords: USB Secure OS Optimization,Modern OS USB Safety,USB Security Techniques,Enhancing USB Protection,Data Encryption in USB,Safe USB Implementation,Operating System Security
thumbnail: https://thmb.techidaily.com/40d2bba30d8d7204e00531f0c8ae5a0019fd1a9406955c448a3c7d8503274e5e.jpg
---

## Optimizing USB Security in Modern Operating Systems

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-info.techidaily.com/new-professional-tips-sharpen-and-brighten-your-iphones-hdri-in-adobe-premiere-pro/"><u>[New][Professional Tips] Sharpen and Brighten Your iPhone's HDRI in Adobe Premiere Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-advanced-techniques-for-educators-lecture-capture-on-mac/"><u>[Updated] Advanced Techniques for Educator's Lecture Capture on Mac</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-compelling-narratives-with-b-cut-footage/"><u>[Updated] Crafting Compelling Narratives with B-Cut Footage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/15-secrets-to-discovering-window-settings/"><u>15 Secrets to Discovering Window Settings</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-accelerate-artistry-in-windows-11-photoshop/"><u>2024 Approved  Accelerate Artistry in Windows 11 Photoshop</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-the-essentials-of-uploading-and-broadcasting-old-footage-on-fb/"><u>2024 Approved  The Essentials of Uploading and Broadcasting Old Footage on FB</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-hacks-bypassing-windows-account-verification/"><u>Advanced Hacks: Bypassing Windows Account Verification</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-variances-in-remote-and-in-house-windows-setup/"><u>Analyzing Variances in Remote & In-House Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-fix-java-non-installation-in-windows/"><u>Approaches to Fix Java Non-Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-space-available-for-windows-11-pin-listings/"><u>Boosting Space Available for Windows 11 Pin Listings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-free-from-frozen-windows-pin-locks/"><u>Breaking Free From Frozen Windows PIN Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/data-defense-on-windows-top-rated-encryption-applications-153-chars/"><u>Data Defense on Windows: Top-Rated Encryption Applications (153 Chars)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/deep-dive-into-asus-pa32u-review-excellence-in-professionalism/"><u>Deep Dive Into Asus PA32U Review  Excellence in Professionalism</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directing-win-credits-to-microsoft-logins/"><u>Directing WIN Credits to MICROSOFT LOGINS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-tackling-epic-games-sign-in-on-pc/"><u>Efficiently Tackling Epic Games Sign-In on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-calendar-look-with-outlook-customization-tricks/"><u>Elevate Your Calendar Look with Outlook Customization Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-shutting-down-windows-11-privacy-features/"><u>Guide to Shutting Down Windows 11 Privacy Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-enhance-windows-11-task-manager-with-a-search-tool/"><u>How to Enhance Windows 11 Task Manager with a Search Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-remove-the-system-requirements-not-met-watermark-in-windows-11/"><u>How to Remove the System Requirements Not Met Watermark in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ideal-nvidia-driver-selection-gameplay-or-studio-focus/"><u>Ideal Nvidia Driver Selection - Gameplay or Studio Focus</u></a></li>
<li><a href="https://extra-resources.techidaily.com/immaculatepixels-prograde-background-elimination/"><u>ImmaculatePixels  Prograde Background Elimination</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-here-is-how-asmr-helps-with-sleep-and-best-asmrtist-recommendation/"><u>In 2024, Here Is How ASMR Helps with Sleep & Best ASMRtist Recommendation</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-vivo-v30-lite-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Vivo V30 Lite 5G Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/including-third-party-storage-on-file-explorer/"><u>Including Third-Party Storage on File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intro-to-digital-art-accessing-microsoft-paint-in-windows-11/"><u>Intro to Digital Art: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/introducing-automatic-system-updates-notice-to-windows-11-ui/"><u>Introducing Automatic System Updates Notice to Windows 11 UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/legacy-tech-lifeline-atlasos-revival-plan/"><u>Legacy Tech Lifeline: AtlasOS Revival Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-mouse-thumb-button-clicks-in-windows-11/"><u>Mastering Mouse Thumb Button Clicks in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-fix-of-xbox-error-code-0x800700e9/"><u>Mastering the Fix of Xbox Error Code: 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-notepad-stability/"><u>Mastering Windows Notepad Stability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-interface-clarity-displaying-this-pc-icon/"><u>Optimizing Interface Clarity: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-x0001-error-on-w10w11-systems/"><u>Overcoming GeForce X0001 Error on W10/W11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unknown-disk-error-in-windows/"><u>Overcoming Unknown Disk Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-resolve-old-password-needed-alert/"><u>Quick Guide to Resolve Old Password Needed Alert</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-airpods-and-windows-compatibility/"><u>Simplified Guide: AirPods & Windows Compatibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-problems-active-status-of-your-win11-license/"><u>Solving Problems: Active Status of Your Win11 License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-secure-command-line-user-permissions-on-pc/"><u>Steps to Secure Command Line User Permissions on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unintentional-hotkey-engagements-on-pc/"><u>Stop Unintentional Hotkey Engagements on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-recover-icon-positions-in-windows-10/"><u>Swiftly Recover Icon Positions in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-analytical-points-showcasing-pcs-edge-over-macs/"><u>Top 9 Analytical Points Showcasing PC's Edge Over Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-operation-failed-0x0000011b-errors/"><u>Troubleshooting Operation Failed: 0X0000011B Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-resolving-webcam-error-code-a00f4289/"><u>Troubleshooting Windows 11: Resolving Webcam Error Code A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-fixing-outlook-problems-on-pcs/"><u>Understanding and Fixing Outlook Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-causes-behind-usb-attachment-failure-in-virtualbox/"><u>Unraveling the Causes Behind 'USB Attachment Failure' In VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/using-dialer-in-win-11/"><u>Using Dialer in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veiled-functionality-for-context-tools-on-pcs/"><u>Veiled Functionality for Context Tools on PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-the-lost-bluetooth-9-effective-solutions-to-find-your-connection/"><u>Win 11 and the Lost Bluetooth: 9 Effective Solutions to Find Your Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-test-failure-immediate-action-plan/"><u>Windows Audio Test Failure: Immediate Action Plan</u></a></li>
</ul></div>
