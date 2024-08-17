---
title: How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
date: 2024-08-16T01:36:27.406Z
updated: 2024-08-17T01:36:27.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
excerpt: This Article Describes How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows
keywords: Fix Outlook Error Windows,Resolve Outlook Error,Outlook Crash Fix,MSOffice Glitch Solve,Microsoft Office Error,Windows Mail Issue,Outlook Troubleshooting Guide
thumbnail: https://thmb.techidaily.com/27b127c31cd1d4c4e3c7e2e3da33ec44af88b4b625ba034a78a3512eb4d83268.jpg
---

## How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

 Once removed, click the **New** option under the **Email** tab and set up your account again.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-secure-your-webcam-with-these-10-tips-for-2024/"><u>[New] Secure Your Webcam with These 10 Tips for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-whispered-words-web-hidden-voice-recorders-for-smartphones-for-2024/"><u>[New] Whispered Words Web  Hidden Voice Recorders for Smartphones for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-5-best-igtv-editor-apps-for-improved-layouts/"><u>[Updated] 5 Best IGTV Editor Apps for Improved Layouts</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-bifrost-betrayal-gods-at-war-for-2024/"><u>[Updated] Bifrost Betrayal  Gods at War for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-quick-tips-for-editing-igtv-content-to-stand-out/"><u>[Updated] In 2024, Quick Tips for Editing IGTV Content to Stand Out</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-internal-recording-feature-screen-capture-for-huaweis-mate-and-p-series-phones-for-2024/"><u>[Updated] Internal Recording Feature  Screen Capture for Huawei's Mate & P Series Phones for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-shaky-to-steady-selecting-an-ideal-camera-gimbals-for-uavs/"><u>2024 Approved  From Shaky to Steady  Selecting an Ideal Camera Gimbals for UAVs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-reel-motivation-a-curated-list-of-top-10-film-titles/"><u>2024 Approved  Reel Motivation  A Curated List of Top 10 Film Titles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-and-utilizing-widgets-in-windows-11/"><u>Accessing and Utilizing Widgets in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-oculus-quest-2-as-a-windows-vr-device/"><u>Adapting Oculus Quest 2 as a Windows VR Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-desktop-icon-chaos-in-windows/"><u>Avoid Desktop Icon Chaos in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-windows-experience-our-criteria-for-best-free-drivers/"><u>Boost Your Windows Experience: Our Criteria for Best Free Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-boot-routine-secrets/"><u>Breaking Down Windows Boot Routine Secrets</u></a></li>
<li><a href="https://extra-information.techidaily.com/closing-credits-collection-free-to-subscription-choices-for-2024/"><u>Closing Credits Collection  Free to Subscription Choices for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/effective-techniques-to-forcibly-end-non-responding-windows-applications/"><u>Effective Techniques to Forcibly End Non-Responding Windows Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-java-vm-not-found-issue-on-windows-devices/"><u>Fixing Java VM Not Found Issue on Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-loading-device-drivers-on-windows-11/"><u>Fixing Non-Loading Device Drivers on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-responsive-spotify-app-on-windows-11-pcs/"><u>Fixing Non-Responsive Spotify App on Windows 11 PCs</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-motorola-g24-power-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/view-media-mastering-the-art-of-selecting-a-cms-for-2024/"><u>Grandview Media  Mastering the Art of Selecting a CMS for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/highlights-of-excellence-top-15-unboxing-youtubers-for-the-year-2024/"><u>Highlights of Excellence  Top 15 Unboxing Youtubers for the Year, 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-itel-p55-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Itel P55 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-deal-with-imminent-license-expiry-on-your-pc/"><u>How to Deal with Imminent License Expiry on Your PC</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-itel-p55plus-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-on-apple-iphone-11-pro-max-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out On Apple iPhone 11 Pro Max How to Bypass?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-rotating-iphone-photos-for-perfect-angles/"><u>In 2024, Rotating iPhone Photos for Perfect Angles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-ultimate-guide-to-mp4-from-instagram-advanced-2-step-processes/"><u>In 2024, Ultimate Guide to MP4 From Instagram  Advanced 2-Step Processes</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-vectors-decoded-for-newbies-diverse-forms-and-tool-options/"><u>In 2024, Vectors Decoded for Newbies  Diverse Forms and Tool Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/is-your-machine-prepared-to-run-newest-windows-os/"><u>Is Your Machine Prepared to Run Newest Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-video-drivers-errors/"><u>Mastering the Art of Fixing Video Drivers Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterpiece-ahead-initiating-mspaint-windows-11-style/"><u>Masterpiece Ahead: Initiating MSPaint, Windows 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-visibility-unveiling-windows-11s-system-tray-and-hidden-items/"><u>Maximizing Visibility: Unveiling Windows 11'S System Tray & Hidden Items</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-shift-whats-updated-in-windows-11/"><u>Navigating the Shift: What's Updated in Windows 11?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unreachable-issues-fixing-mb-service-disconnect-in-windows-11/"><u>Overcoming Unreachable Issues: Fixing MB Service Disconnect in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/photographys-top-10-digital-notebooks-for-smartphones/"><u>Photography's Top 10 Digital Notebooks for Smartphones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-fixed-bluetooth-pairing-error-in-win-os/"><u>Quick Guide to Fixed: Bluetooth Pairing Error in Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-tips-ignoring-license-expires-messages-in-win11/"><u>Quick Tips: Ignoring ‘License Expires’ Messages in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinvigorating-computers-top-8-windows-tricks/"><u>Reinvigorating Computers: Top 8 Windows Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-non-scrolling-issue-in-microsoft-excel-pc/"><u>Resolve Non-Scrolling Issue in Microsoft Excel PC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-gpu-malfunction-alert-nvidia/"><u>Resolved: GPU Malfunction Alert (NVIDIA)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restarting-the-windows-indexer-a-quick-guide/"><u>Restarting the Windows Indexer: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-workflow-why-the-latest-windows-outlook-matters/"><u>Revolutionize Your Workflow: Why the Latest Windows' Outlook Matters</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/sharp-sight-and-spectrum-diving-into-the-z32x-display/"><u>Sharp Sight and Spectrum  Diving Into the Z32X Display</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-turning-onoff-secure-boot-in-virtualbox/"><u>Step-by-Step Guide: Turning On/Off Secure Boot in VirtualBox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-starting-spotify-by-default/"><u>Stop Windows From Starting Spotify by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-performance-replacing-aged-technology/"><u>Streamlining Windows Performance: Replacing Aged Technology</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/tecno-phantom-v-flip-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Tecno Phantom V Flip ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-dolby-atmos-installation-in-windows/"><u>The Essential Checklist for Dolby Atmos Installation in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-workday-woes-into-productivity-peaks-using-windows-11s-tools/"><u>Transform Workday Woes Into Productivity Peaks Using Windows 11'S Tools</u></a></li>
</ul></div>
