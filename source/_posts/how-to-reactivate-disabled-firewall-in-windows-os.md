---
title: How to Reactivate Disabled Firewall in Windows OS
date: 2024-08-28T01:18:59.288Z
updated: 2024-08-29T01:18:59.288Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reactivate Disabled Firewall in Windows OS
excerpt: This Article Describes How to Reactivate Disabled Firewall in Windows OS
keywords: Reactivate Firewall Windows,Restart Security Feature,Unblock Windows Firewall,Enable Firewall Settings,Reset Firewall Functions,Revive OS Firewall Service,Turn On Windows Firewall
thumbnail: https://thmb.techidaily.com/ccf2cd6688a4adcaeda8d922b0b91ea561ec3cf2936a8b4a71d20d4455d103fb.jpg
---

## How to Reactivate Disabled Firewall in Windows OS

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-the-art-of-mixing-on-youtube-music/"><u>[New] 2024 Approved  The Art of Mixing on YouTube Music</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastering-full-circle-clips-iphone-filming-tips/"><u>[New] In 2024, Mastering Full-Circle Clips  IPhone Filming Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlock-the-best-top-9-gamers-hubs/"><u>[New] Unlock the Best  Top 9 Gamers' Hubs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagrams-latest-trends-for-successful-influencer-journeys-for-2024/"><u>[Updated] Instagram's Latest Trends for Successful Influencer Journeys for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-crafting-captivating-animations-creating-gifs-from-your-favorite-youtube-videos/"><u>2024 Approved  Crafting Captivating Animations  Creating GIFs From Your Favorite YouTube Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamline-your-images-in-canva-without-clutter/"><u>2024 Approved  Streamline Your Images in Canva Without Clutter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/compre-written-remedy-for-windows-0x0000004e/"><u>Compre Written Remedy for Windows' 0X0000004E</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-effective-windows-ping-usage/"><u>Comprehensive Guide to Effective Windows Ping Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-delving-details-how-to-hide-windows-11-admin-login-qanda/"><u>Disabling Delving Details: How to Hide Windows 11 Admin Login Q&A</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxgidll-reemerge-easy-fixes-for-windows-11-users/"><u>Dxgi.dll Reemerge: Easy Fixes for Windows 11 Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/enhancing-browser-use-with-chromes-picture-in-picture-feature/"><u>Enhancing Browser Use with Chrome's Picture In Picture Feature</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722892287552-expert-advice-on-maintaining-a-reliable-skype-connection-top-10-tips/"><u>Expert Advice on Maintaining a Reliable Skype Connection – Top 10 Tips!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fast-track-integration-of-bing-chat-in-win-11-search-field/"><u>Fast-Track Integration of Bing Chat in Win 11 Search Field</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-motorola-g54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-on-telnet-in-up-to-date-windows-11/"><u>How to Turn On Telnet in Up-to-Date Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/igniting-windows-11s-secret-bar-queries/"><u>Igniting Windows 11'S Secret Bar Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/least-demanding-web-browsers-for-your-systems-resources-on-windows-macos-chromeos/"><u>Least Demanding Web Browsers for Your System's Resources on Windows, macOS, ChromeOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-family-safety-a-quick-primer/"><u>Microsoft Family Safety: A Quick Primer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefining-tech-trends-artificial-intelligence-and-windows-11/"><u>Redefining Tech Trends: Artificial Intelligence & Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-full-chatgpt-capacity-warning/"><u>Remedy for Full ChatGPT Capacity Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-system-settings-errors-in-win11/"><u>Resolving System Settings Errors in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0xc004f050/"><u>Resolving Windows Update Issue: Error Code 0xC004F050</u></a></li>
<li><a href="https://win11-tips.techidaily.com/synergy-in-action-link-windows-and-android-using-flow/"><u>Synergy in Action: Link Windows & Android Using Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-downloads-problems-in-win11-pc-environments-2/"><u>Taming Downloads Problems in Win11 PC Environments (2)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transition-guide-using-windows-7-key-for-windows-11-activation/"><u>Transition Guide: Using Windows 7 Key for Windows 11 Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-resolving-the-application-start-failed-error-code-xc000003e-on-win11/"><u>Understanding and Resolving The Application Start Failed Error Code Xc000003e on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-unrelated-edgers-in-tasker/"><u>Understanding Unrelated Edgers in Tasker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-disabling-the-gpsvc-loop/"><u>Unlocking Windows: Disabling the GPSVC Loop</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-asus-bluetooth-adapter-with-our-step-by-step-installation-guide/"><u>Update Your ASUS Bluetooth Adapter with Our Step-by-Step Installation Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>