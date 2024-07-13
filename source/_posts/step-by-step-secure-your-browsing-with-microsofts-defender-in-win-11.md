---
title: "Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11"
date: 2024-07-12T17:08:11.225Z
updated: 2024-07-13T17:08:11.225Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11"
excerpt: "This Article Describes Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11"
keywords: Browser Safety Windows 11,Defender Security Guide,Protect Win 11 Browsing,Secure Defender Setup,Win 11 Privacy Tips,Antivirus in Win 11,Enhance Browser Security
thumbnail: https://thmb.techidaily.com/936d10b629420455d4c3cd43378416c6e205e5dc73cdd968038b275d13e490d5.png
---

## Step-by-Step: Secure Your Browsing with Microsoft's Defender in Win 11

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
<li><a href="https://blog-min.techidaily.com/how-to-transfer-data-from-iphone-12-mini-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 12 mini To Other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-iphones-unlocked-smart-tips-for-saving-and-playing-gifs/"><u>In 2024, IPhones Unlocked  Smart Tips for Saving & Playing GIFs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Vivo Y78+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-network-issues-demystifying-windows-error-0x800704b3/"><u>Tackling Network Issues - Demystifying Windows' Error: 0X800704B3</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-drag-recover-lost-functionality-fast/"><u>Win11 Drag: Recover Lost Functionality Fast</u></a></li>
<li><a href="https://win11-tips.techidaily.com/timely-changes-essential-windows-programs-for-editing-file-dates/"><u>Timely Changes: Essential Windows Programs for Editing File Dates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-telnet-on-windows-11-systems/"><u>Unlocking Telnet on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/starting-smart-with-windows-hidden-folders/"><u>Starting Smart with Windows' Hidden Folders</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-trim-and-cut-mov-files-without-spending-a-dime/"><u>New In 2024, Trim and Cut MOV Files without Spending a Dime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-windows-store-clearing-error-code-x80072f30/"><u>Troubleshoot Windows Store: Clearing Error Code X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-list-of-apps-facilitating-the-switch-from-macos-to-windows/"><u>The Ultimate List of Apps Facilitating the Switch From MACOS to WINDOWS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-troubleshooting-msvcr120-deficiency-windows-wise/"><u>Tips for Troubleshooting Msvcr120 Deficiency Windows-Wise</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-becoming-a-onestream-pro-tips-and-tricks-from-the-pros/"><u>2024 Approved  Becoming a OneStream Pro  Tips and Tricks From the Pros</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-infinix-hot-40-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-your-iphone-x-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From your iPhone X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-techniques-how-to-utilize-the-background-blur-on-w11-photos/"><u>Streamlined Techniques: How to Utilize the Background Blur on W11 Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-productivity-essential-windows-based-tools-listed/"><u>Revolutionize Productivity: Essential Windows-Based Tools Listed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trimming-down-excessive-cpu-usage-in-windows-hosts/"><u>Trimming Down Excessive CPU Usage in Windows Hosts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-the-art-of-precision-modern-methods-to-automatically-align-sound-and-picture/"><u>2024 Approved The Art of Precision Modern Methods to Automatically Align Sound and Picture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-search-enhancements-in-windows-11-file-explorer/"><u>Visual Search Enhancements in Windows 11 File Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-command-center-for-app-and-browser-authority/"><u>Windows Command Center for App and Browser Authority</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-11-complete-guide-drfone-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 11? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/taming-the-tyranny-of-inconsistent-colors-in-windows/"><u>Taming the Tyranny of Inconsistent Colors in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-overcoming-windows-no-internet-issue/"><u>Steps for Overcoming Windows No Internet Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-audio-issues-with-windows-tone-test/"><u>Resolving Audio Issues with Windows Tone Test</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-method-for-heic-to-jpeg-conversion/"><u>Windows Method for Heic to Jpeg Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-smooth-file-transfers-tips-and-tricks-for-windows-users/"><u>Securing Smooth File Transfers: Tips & Tricks for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-tips-for-a-win11-masterpiece/"><u>Transform Your Desktop: Tips for a Win11 Masterpiece</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-error-0x80131500-on-microsoft-shop/"><u>Unlocking Error #0X80131500 on Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-resurrect-non-responsive-windows-discord-elements/"><u>Tactics to Resurrect Non-Responsive Windows Discord Elements</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-instant-title-insertion-for-your-videos-on-windows-photos/"><u>In 2024, Instant Title Insertion for Your Videos on Windows Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unmasking-your-worldwide-address-through-cmd-windows/"><u>Unmasking Your Worldwide Address Through CMD, Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-silencing-audacity-a-step-by-step-noise-reduction-method/"><u>[New] 2024 Approved  Silencing Audacity  A Step-by-Step Noise Reduction Method</u></a></li>
</ul></div>
