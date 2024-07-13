---
title: Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard
date: 2024-07-12T16:37:22.251Z
updated: 2024-07-13T16:37:22.251Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard
excerpt: This Article Describes Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard
keywords: Win 11 Protection,Defender AppGuard Boost,Browse Securely Win 11,Enhance Win 11 Security,MS Defender for Win 11,Optimize Win 11 Safety,Guarded Browsing Win 11
thumbnail: https://thmb.techidaily.com/3d0b2d16ee1d6e6a1474c3b5739a00253bf279f4294e6c37548bb9b82e10821e.jpg
---

## Elevate Your Browsing Experience in Win 11 by Enabling MS Defender Application Guard

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're [having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
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

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

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

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

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

1. Open Windows PowerShell with admin access. If you need help, see our guide on [how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

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
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/understanding-the-duration-required-for-language-mastery/"><u>Understanding the Duration Required for Language Mastery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-reactivate-googles-nearby-share-app/"><u>Essential Tips to Reactivate Google's Nearby Share App</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-precision-displays-the-finest-screen-options-for-editors-2024/"><u>[New] Precision Displays - The Finest Screen Options For Editors, 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-word-clarity-with-windows-11-help/"><u>Expedite Word Clarity with Windows 11 Help</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-youtube-video-aspect-ratios-the-pros-and-cons-of-each-option/"><u>New 2024 Approved YouTube Video Aspect Ratios The Pros and Cons of Each Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/spotlight-on-7-irksome-windows-11-aesthetics/"><u>Spotlight on 7 Irksome Windows 11 Aesthetics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-update-issue-error-code-0x80073712/"><u>Resolving Windows Update Issue: Error Code 0X80073712</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-efficient-windows-menu-for-software-alerts/"><u>Crafting an Efficient Windows Menu for Software Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-access-control-constructing-your-windows-personal-pins/"><u>Cutting-Edge Access Control: Constructing Your Windows Personal Pins</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-essential-guide-incorporating-music-and-effects-into-your-videos-for-2024/"><u>New Essential Guide Incorporating Music and Effects Into Your Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-rectifying-error-0x80300024-in-winxp/"><u>Steps for Rectifying Error 0X80300024 in WinXP</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-no-budget-no-problem-top-10-free-video-editing-software-for-chromebook/"><u>New In 2024, No Budget? No Problem! Top 10 Free Video Editing Software for Chromebook</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-boost-your-budget-a-straightforward-triple-step-method-to-monitor-youtube-revenue/"><u>[Updated] Boost Your Budget  A Straightforward Triple-Step Method to Monitor YouTube Revenue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-windows-aggressive-contrast-mode/"><u>Silence Windows' Aggressive Contrast Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resuscitating-silent-windows-headset-mic/"><u>Resuscitating Silent Windows Headset Mic</u></a></li>
<li><a href="https://win11-tips.techidaily.com/standardizing-your-windows-system-backups/"><u>Standardizing Your Windows System Backups</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-editing-tasks-with-powertoys-text-tools/"><u>Simplify Editing Tasks with PowerToys' Text Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/documentation-skills-snapping-windows-uac-prompts/"><u>Documentation Skills: Snapping Windows UAC Prompts</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-mkv-video-on-xiaomi-redmi-note-12r-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Issues playing MKV video on Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://audio-editing.techidaily.com/youtubes-ultimate-playlist-of-irresistible-sounds/"><u>YouTubes Ultimate Playlist of Irresistible Sounds</u></a></li>
<li><a href="https://change-location.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-memory-limitation-indicators-on-windowsvmware-systems/"><u>Correcting Memory Limitation Indicators on Windows/VMware Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-for-clearing-false-device-error-on-pcs/"><u>Expert Guide for Clearing False Device Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-hello-for-secure-user-access/"><u>Enabling Windows Hello for Secure User Access</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unlocking-the-power-of-igtv-from-novice-to-pro/"><u>2024 Approved  Unlocking the Power of IGTV  From Novice to Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-nvidia-configurations-on-windows-os/"><u>How to Recover NVIDIA Configurations on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-linux-with-windows-tools/"><u>Enhancing Linux with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-11-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-disable-virtual-machine-feature-in-windows-11/"><u>Instructions: Disable Virtual Machine Feature in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-8-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 8 to other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locating-and-opening-system32-windows-11/"><u>Locating and Opening System32 (Windows 11)</u></a></li>
</ul></div>
