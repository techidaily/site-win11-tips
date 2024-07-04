---
title: "Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox"
date: 2024-06-25T16:47:44.211Z
updated: 2024-06-26T16:47:44.211Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox"
excerpt: "This Article Describes Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox"
keywords: VirtualBox Secure Boot,Enable Secure Boot Vbox,Disable VirtualSecureBoot,Secure Boot VirtualBox Guide,Turning On Secure Boot VM,Off Secure Boot in Virtual Box,Virtual Machine Secure Boot Control
thumbnail: https://thmb.techidaily.com/3d0c7b28b7640277a83e56148652cb264b53fd3e0f61a09c67b9e7dbbff5f451.jpg
---

## Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-resolving-rdp-errors-in-windows-11/"><u>Essential Tips for Resolving RDP Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11s-mysteries-inside-its-registry-files/"><u>Unraveling Windows 11'S Mysteries: Inside Its Registry Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-network-gaps-win-10-and-11-written-for-telnet-users/"><u>Bridging Network Gaps: Win 10 & 11' Written for Telnet Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wipe-out-unfulfilled-criteria-indication-in-win11/"><u>Wipe Out Unfulfilled Criteria Indication in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-broken-exe-file-execution-on-pcs/"><u>Fix Broken Exe File Execution on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-install-unsupported-windows-packages/"><u>Guidelines to Install Unsupported Windows Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/direct-user-name-changes-for-w11-enthusiasts/"><u>Direct User Name Changes for W11 Enthusiasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-path-to-higher-engagement-essential-shortcuts-for-youtubers-for-2024/"><u>The Path to Higher Engagement  Essential Shortcuts for YouTubers for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-chilly-celebrations-beijings-olympic-ice-showcase-2022/"><u>In 2024, Chilly Celebrations  Beijing's Olympic Ice Showcase, 2022</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-bring-your-stories-alive-techniques-for-animation-in-text/"><u>2024 Approved  Bring Your Stories Alive  Techniques for Animation in Text</u></a></li>
<li><a href="https://fox-blue.techidaily.com/navigating-the-best-iphone-options-for-adding-water-marks-for-2024/"><u>Navigating the Best iPhone Options for Adding Water Marks for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-online-oasis-secure-re-entry-to-social-networks/"><u>[New] 2024 Approved  Online Oasis  Secure Re-Entry to Social Networks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-can-i-recover-corrupted-excel-file-2010-stellar-by-stellar-guide/"><u>How Can I Recover Corrupted Excel File 2010 | Stellar</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-learn-quickly-flipping-video-sequence-android-style/"><u>[New] Learn Quickly  Flipping Video Sequence Android-Style</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-channel-upgrade-the-beginners-roadmap-to-video-mastery/"><u>[New] In 2024, Channel Upgrade  The Beginner's Roadmap to Video Mastery</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713965029623-new-this-article-discusses-what-is-hitfilm-express-how-to-download-install-and-use-it-and-its-key-features-it-further-discusses-its-alternative-for-editing-/"><u>New This Article Discusses What Is Hitfilm Express, How to Download, Install and Use It, and Its Key Features. It Further Discusses Its Alternative for Editing Your Videos and More. Check Out Now for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-editorial-elegance-at-the-end/"><u>[New] Editorial Elegance at the End</u></a></li>
</ul></div>
