---
title: Overcoming the Stuck GPSVC Hang in Windows
date: 2024-08-23T07:01:29.458Z
updated: 2024-08-24T07:01:29.458Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Stuck GPSVC Hang in Windows
excerpt: This Article Describes Overcoming the Stuck GPSVC Hang in Windows
keywords: Fixing Windows GPSVC Freeze,Resolve Windows GPSVC Error,Unfreeze GPSVC in Win,Stop GPSVC Hang on PC,Windows GPSVC Stuck Fix,Eliminate GPSVC Hang Windows,Clearing GPSVC Glitches
thumbnail: https://thmb.techidaily.com/7e858d7102e5ef6f6137f0acdeeba112d7b0daf0c9e0dad5ba4b3979a33bb860.jpg
---

## Overcoming the Stuck GPSVC Hang in Windows

 The "Please wait for the GPSVC" loop in Windows is a frustrating issue that can cause the system to get stuck upon a shutdown attempt. This loop is related to the Group Policy Client Service (GPSVC).

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.

## What Does “Please Wait for the GPSVC” Mean?

 The "Please wait for the GPSVC" statement occurs while the system is waiting for the Group Policy Client Service (GPSVC) to complete certain active processes. This service works by managing and applying the group policies in your Windows system.

 The time this service takes to complete the process can depend upon factors such as the complexity of the Group Policy settings, network connectivity, and the performance of the system. While it is generally recommended to avoid interrupting the process till it completes, there are times when this loop can take forever to end.

 This normally happens due to one or more of the following reasons:

* **Group Policy errors**: The Group Policy settings in your computer may have been corrupted, which is preventing the GPSVC process from completing successfully.
* **Third-party software conflicts**: A third-party software or services might be conflicting with the GPSVC process, causing it to get stuck in a loop.
* **System file corruption**: If the essential system files on which the Group Policy or the GPSVC processes depend become corrupted or damaged, it can lead to the system getting stuck in loops, improper shutdowns, disk errors, or malware infections.
* **Malware or viruses**: Malware can also interrupt system processes deliberately. The malware or virus in your system might be attempting to gain control over your system by interfering with GPE.

 It is essential to note that the exact cause of this loop can vary, depending upon different circumstances. However, regardless of what the cause might be, the troubleshooting methods we have listed below are sure to help you fix the issue for good.

## Setting Up Your PC for Troubleshooting

 To start the troubleshooting, you must be able to access your system. This can be done in two ways; you can either [perform a Windows reboot](https://www.makeuseof.com/windows-restart-methods/) to break the loop using the Ctrl + Alt + Delete menu or enter the Safe Mode.

 If you have tried rebooting but the error pops up again, you can boot into the Safe Mode through Windows Recovery Environment.

 This will launch the system with a set of only the necessary drivers and services. Once you are in Safe Mode, you can take further steps to diagnose the issue and fix it.

 Here is how you can do that:

1. Shut down your computer and use the power button to restart.
2. When the computer is loading, use the power button to force shutdown again. You can do this by pressing and holding the power button).
3. Repeat this twice and on the third attempt, Windows will boot into the Recovery Environment automatically.
4. Choose **Troubleshoot** \> **Advanced options**.  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
5. Click on **Startup settings** and select **Restart**.
6. Wait for the computer to restart and then press the 4, 5, or 6 keys to boot into Safe Mode.

 Once you are in Safe Mode, proceed with the solutions we have listed below.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 1\. Restart the Group Policy Client Service

 The GPSVC service itself might be dealing with a temporary glitch or a corruption error that is causing it to malfunction. The easiest way to fix issues with the service is by restarting it.

 Here is how you can do that:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "services.msc" in Run and click **Enter**.
3. In the following window, look for the Group Policy Client service and right-click on it.
4. Choose **Properties** from the context menu.  
![Access the Group Policy Client properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/group-policy-client-properties.jpg)
5. Now, click on the **Stop** button, wait for a few seconds, and click **Start**.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Expand the dropdown for Startup type and choose **Automatic**.
7. Click **Apply** \> **OK** to save the changes.

 You can now exit the Services window and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 2\. Reset the Local Group Policy Settings

![Reset Group Policy using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Reset-Group-Policy-using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As we mentioned earlier, there can be an issue with the Local Group Policy settings. To check if this is the case in your situation, you can reset the Local Group Policy settings. This will restore the configurations to the default state, eliminating any potential conflicts that may have caused the issue.

 However, before you proceed, it is important to note that this will also remove any customizations or modifications you made via GPE.

 If that is not a problem, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "cmd" in Run and press **Ctrl** \+ **Shift** \+ **Enter** keys together.
3. Choose **Yes** in the User Account Control prompt.
4. In Command Prompt, execute the command below:  
`RD /S /Q "%WinDir%\System32\GroupPolicyUsers" && RD /S /Q "%WinDir%\System32\GroupPolicy"`
5. Once the command executes, proceed with the following command:  
`gpupdate.exe /force`
6. Finally, restart your computer and check if the issue is resolved.

## 3\. Modify the GPSVC Registry File

 There is also a chance that the GPSVC registry keys are missing or corrupt, which is preventing the service from functioning properly. Such issues can be fixed by modifying the relevant values as shown below.

 Before proceeding, we recommend that you [create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe. Once that is done, follow these steps to proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below:  
`​​​​​​​​​​​​​​Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Svchost`
5. Right-click on **Svchost** and choose **New** \> **Key**.
6. Name this key as **GPSvcGroup**.
7. Double-click on **GPSvcGroup** and right-click anywhere in the right pane.
8. Choose **New** \> **DWORD (32-bit) Value** and rename this value as **AuthenticationCapabilities**.
9. Double-click on **AuthenticationCapabilities** and select the Base to **Decimal**.
10. Type "12320" in Value data and click **OK**.  
![AuthenticationCapabilities key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/authentican-key.jpg)
11. Now, create another key **CoInitializeSecurityParam** in a similar way.
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
12. Set its base to **Hexadecimal** and type "1" in Value data.  
![CoInitializeSecurityParam key in the Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/coinitializesecurityparam-key.jpg)
13. Click **OK** to save the changes and then restart your PC. Hopefully, upon reboot, you will no longer face the error.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 Apart from these specific fixes, you can also try [performing a system restore](https://www.makeuseof.com/tag/system-restore-factory-reset-work-windows-10/) or scanning the system [using the built-in SFC and DISM Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/). The former will help revert the system to an older, error-free state, while performing a system scan will help fix any corruption errors in the system that might be contributing to the problem.

## GPSVC Loops on Windows, Fixed

 The "Please Wait for the GPSVC" loop doesn't have to be a permanent problem. Hopefully, the solutions above will help you fix this issue for good. If the problem persists, it is always recommended to seek assistance from technical experts or Microsoft support.

 Below, we take a look at the different causes of this problem, followed by the solutions you can try to fix it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-free-and-online-facebook-music-downloaders/"><u>[New] 2024 Approved  Free And Online Facebook Music Downloaders</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dynamic-subscriber-buttons-for-video-creators-filmora-edition/"><u>[New] In 2024, Dynamic Subscriber Buttons for Video Creators - Filmora Edition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-unlocking-the-secrets-to-sharing-videos-on-instagram/"><u>[New] Unlocking the Secrets to Sharing Videos on Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-8-sbt-to-srtr-conversion-tools-pcmac-compatibility/"><u>[Updated] Best 8 SBT to SRTR Conversion Tools - PC/Mac Compatibility</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-the-art-of-vlog-script-creation/"><u>[Updated] Mastering the Art of Vlog Script Creation</u></a></li>
<li><a href="https://facebook.techidaily.com/4-things-to-know-about-metas-new-privacy-policy/"><u>4 Things to Know About Meta's New Privacy Policy</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bringing-down-the-time-barrier-for-fastening-fb-video-content/"><u>Bringing Down the Time Barrier for Fastening FB Video Content</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-productivity-optimize-windows-tiling/"><u>Elevate Productivity: Optimize Windows Tiling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-window-11s-camera-app-crash-afc-error-code/"><u>Eliminating Window 11'S Camera APP Crash: AFC Error Code</u></a></li>
<li><a href="https://fox-access.techidaily.com/essential-metaverse-tools-top-7-devices-for-virtual-readiness/"><u>Essential Metaverse Tools  Top 7 Devices for Virtual Readiness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-advice-reversing-problems-from-a-recent-windows-update/"><u>Expert Advice: Reversing Problems From a Recent Windows Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-enigma-of-error-0x0000004e-in-win11/"><u>Fixing the Enigma of Error 0X0000004E in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-most-common-anydesk-failures/"><u>Fixing Windows' Most Common AnyDesk Failures</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-realme-v30t-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Realme V30T? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-xiaomi-redmi-13c-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Xiaomi Redmi 13C 5G Phone that is Locked?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-samsung-galaxy-xcover-7-phone-by-drfone-android/"><u>How to Unlock a Network Locked Samsung Galaxy XCover 7 Phone?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jumpstart-your-pc-ms-stores-premier-choices/"><u>Jumpstart Your PC: MS Store's Premier Choices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-tips-operating-the-toolbar-in-mspcm-win11/"><u>Key Tips: Operating the Toolbar in MSPCM Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-your-guide-for-windows-users/"><u>Mastering Map Integration: Your Guide for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-windows-11-policy-editor-efficiently/"><u>Navigate Windows 11 Policy Editor Efficiently</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-assignments-the-6-premier-learning-apps-that-students-and-parents-love/"><u>Navigating Assignments: The 6 Premier Learning Apps That Students & Parents Love</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-stay-up-to-date-with-the-latest-movie-trailers-top-ios-apps/"><u>New Stay Up-to-Date with the Latest Movie Trailers Top iOS Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-inaccessible-delete-switch-in-windows-11-pins/"><u>Overcoming Inaccessible Delete Switch in Windows 11 PINs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-brightness-on-windows-volume-controls/"><u>Restore Brightness on Windows' Volume Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-seamless-operation-of-ps-windows-version/"><u>Restoring Seamless Operation of PS Windows Version</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-experience-file-explorer-troubleshooting/"><u>Revitalize Your Experience: File Explorer Troubleshooting</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/shortcut-to-engagement-analyzing-facebooks-video-trends/"><u>Shortcut to Engagement  Analyzing Facebook's Video Trends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-opening-win-11s-call-center/"><u>Steps for Opening Win 11'S Call Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-reawakening-guide-navigating-through-windows-8-revival-techniques/"><u>System Reawakening Guide: Navigating Through Windows' 8 Revival Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactical-approaches-to-overcoming-disabled-errors-in-ps-execution/"><u>Tactical Approaches to Overcoming 'Disabled' Errors in PS Execution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-rectify-non-specified-values-on-windows-pcs/"><u>Techniques to Rectify Non-Specified Values on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workday-top-9-motivations-to-switch-to-windows-outlook/"><u>Transform Your Workday: Top 9 Motivations to Switch to Windows' Outlook</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unboxing-marketing-strategy-for-2024/"><u>Unboxing Marketing Strategy for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-android-and-pc-simple-synchronization-techniques/"><u>Uniting Android & PC: Simple Synchronization Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-greyed-out-pin-deletion-command-on-pc/"><u>Unlocking Greyed-Out Pin Deletion Command on PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-health-5-key-steps-for-device-status-tracking/"><u>Windows 11 Health: 5 Key Steps for Device Status Tracking</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>