---
title: "Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11"
date: 2024-12-09T22:44:23.650Z
updated: 2024-12-12T16:05:49.220Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11"
excerpt: "This Article Describes Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11"
keywords: Secure Browsing,Defender APG Windows,Edge Browser Security,Protect Win 11,Microsoft APG Setup,Privacy-Focused Browser,Advanced Threat Protection
thumbnail: https://thmb.techidaily.com/c2d68683c182adeb644872ae9b6efd92813d48ae83b60547183327ca40ae4d54.jpg
---

## Secure Edge Browser: Setting up Microsoft's Defender Application Guard in Win 11

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're[having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on[how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.

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
<li><a href="https://facebook-videos.techidaily.com/new-facebook-video-posting-dilemmnas-which-way-for-2024/"><u>[New] Facebook Video Posting Dilemmnas Which Way for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-unveiling-facebooks-video-ratio-options-and-tweaks/"><u>[New] In 2024, Unveiling Facebook's Video Ratio Options & Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-device-uptime-a-comprehensive-guide-for-windows-11-users/"><u>Dive Into Device Uptime: A Comprehensive Guide for Windows 11 Users</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/efficiently-tackle-challenges-with-photoshop-when-files-wont-open/"><u>Efficiently Tackle Challenges with Photoshop when Files Won't Open</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-software-installation-windows-11s-toolkit/"><u>Enhancing Software Installation: Windows 11’S Toolkit</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-philips-hf3520-wakeup-call-a-balanced-appraisal-of-price-and-performance/"><u>Exploring the Philips HF3520 Wakeup Call: A Balanced Appraisal of Price and Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-game-installations-in-ms-store/"><u>Fixing Failed Game Installations in MS Store</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unlocking-instagrams-potential-successful-post-tactics/"><u>In 2024, Unlocking Instagram's Potential Successful Post Tactics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-photo-size-in-windows-11-with-these-top-6-tips/"><u>Master Your Photo Size in Windows 11 with These Top 6 Tips</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-lower-thirds-mastery-tips-and-tricks-for-fcpx-users/"><u>New 2024 Approved Lower Thirds Mastery Tips and Tricks for FCPX Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-methods-eliminate-windows-11s-search-visibility/"><u>Proven Methods: Eliminate Windows 11'S Search Visibility</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/tech-giants-samsung-google-and-qualcomm-unite-for-groundbreaking-xr-collaboration-before-apple-enters-the-arena-exclusive-insights-zdnet/"><u>Tech Giants Samsung, Google & Qualcomm Unite for Groundbreaking XR Collaboration Before Apple Enters the Arena: Exclusive Insights | ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-audio-recorder-9999-issue-in-windows/"><u>Troubleshooting Audio Recorder 9999 Issue in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncover-and-purge-the-ultimate-windows-10-history-cleanup/"><u>Uncover & Purge: The Ultimate Windows 10 History Cleanup</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-securely-without-screensaver/"><u>Unlock Windows 11 Securely Without Screensaver</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-users-bitter-experiences-counted/"><u>Windows 11: Users' Bitter Experiences Counted</u></a></li>
</ul></div>

