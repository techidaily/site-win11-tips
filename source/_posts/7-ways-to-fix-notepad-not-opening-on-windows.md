---
title: 7 Ways to Fix Notepad Not Opening on Windows
date: 2024-07-12T17:50:00.654Z
updated: 2024-07-13T17:50:00.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 7 Ways to Fix Notepad Not Opening on Windows
excerpt: This Article Describes 7 Ways to Fix Notepad Not Opening on Windows
keywords: Windows Notepad Issue,Fix Notpad Closed,Launch Notepad Success,Notepad Opens Error,Troubleshoot Notepad,Restart Notepad Fix,Windows Notepad Solution
thumbnail: https://thmb.techidaily.com/a04f09fd3f332adf9ea1d2c4b6687272d88f08a364f88560f34c633d621d6cbc.jpg
---

## 7 Ways to Fix Notepad Not Opening on Windows

 Notepad is a simple text editor app that comes pre-installed on your Windows computer. You can use it to view, create, and edit text files whenever needed. But what if Windows fails to open Notepad and you can’t use it?

 Several factors, ranging from a temporary app glitch to corrupt user account files, can prevent Notepad from opening on Windows. Fortunately, there are some quick fixes you can use to regain access to the Notepad app on Windows.

## 1\. Use Alternative Methods to Open Notepad

 Before you try any advanced solutions, see if you can open Notepad using the Run tool. Press**Win + R** to open the Run dialog box. Type**notepad** in the Open field and press**Enter** .

 If that doesn’t work, try opening Notepad through a command-line tool. Open the search menu to launch**Command Prompt** or**PowerShell** . In the console, type**notepad** and then press**Enter** .

![Open Notepad via Command-Line Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-notepad-via-command-line-tool.jpg)

 You could also ask Cortana to open Notepad. However, if none of these methods work, proceed to the next solution.

## 2\. Set Notepad as the Default Text Editor

 If Notepad is not set as the default text editor app on Windows, your text files may open in a different app. If you don't want that, use these steps to set Notepad as the default text editor app.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Navigate to the**Apps** tab.
3. Select**Default apps** from the right pane.
4. Scroll all the way down to the**Related settings** section.
5. Click**Choose defaults by file type** .
6. Type**.txt** in the search box and click the current default app.
7. Select**Notepad** and click the**Set default** button.  
![Set Notepad as Default Text Editor App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-notepad-as-default-text-editor-app-on-windows.jpg)

Try opening a few text files and see if they open in Notepad.

## 3\. Repair or Reset the Notepad App

 The built-in repair tool on Windows is quite efficient when it comes to fixing minor app-related issues. Microsoft recommends using this tool when an app fails to open or does not work as expected on your Windows computer.

To repair the Notepad app on Windows:

1. Right-click the Start icon or press**Win + X** to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll down or use the search tool to locate**Notepad** on the app list.
4. Click the**three-dot menu icon** next to Notepad and select**Advanced options** .
5. Scroll down to the Reset section and click the**Repair** button.  
![Repair or Reset the Notepad App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/repair-or-reset-the-notepad-app.jpg)

 You should see a checkmark next to the Repair button once the process is complete. Then, try to [open the Notepad app](https://www.makeuseof.com/windows-11-open-notepad/) again.

 If repairing the Notepad app does not make any difference, you can try resetting it. Here are the steps for the same.

1. Press**Win + S** to open the search menu.
2. Type**Notepad** in the search box and select**App settings** .
3. Under the Reset section, click the**Reset** button.

 Windows will reset the Notepad app to its default version, which should resolve any issues with it.

## 4\. Reinstall the Notepad App

 You can also try uninstalling and reinstalling the Notepad app on your computer. To do so, you’ll need to access the [optional features on Windows](https://www.makeuseof.com/tag/windows-10-optional-features-guide/) . Here’s how you can go about it.

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Apps > Optional features** .
3. Click on**Notepad** to expand it.
4. Click the**Uninstall** button.  
![Uninstall Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-notepad-app-on-windows.jpg)
5. Wait for Windows to uninstall Notepad from your computer.
6. Next, click the**View features** button at the top.
7. Type**Notepad** in the search box.
8. Tick the**Notepad (system)** checkbox and click**Next** .
9. Click**Install** .  
![Install Notepad App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/install-notepad-app-on-windows.jpg)

 Wait for Windows to install Notepad on your computer and then try to open it using the search menu.

## 5\. Run the SFC and DISM Scans

 Corrupted system files could also interfere with system processes and prevent Notepad from opening. The System File Checker (SFC) is a built-in utility that can help you repair system files on Windows. It basically scans your system for damaged system files and replaces them with their cached versions.

To run the SFC scan on Windows:

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. When the User Account Control (UAC) prompt appears, select**Yes** to continue.
4. In the console, input the following command and press**Enter** :  
`sfc /scannow`

 Wait for the scan to complete and then enter the following command to run the DISM (or Deployment Image Servicing and Management) scan. It will try to detect and repair any issues with the system image.

`DISM.exe /Online /Cleanup-image /Restorehealth`

![DISM Scan in Windows Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-scan-in-windows-terminal.jpg)

 After the scan is complete, restart your PC and see if you can access Notepad.

## 6\. Perform a Clean Boot

 At times, third-party apps and background services can conflict with Windows processes and cause problems like the one discussed here. One way to verify this possibility is to boot your computer in a clean boot state, where it only runs with essential apps and services.

 If you perform a clean boot and Notepad opens normally, it means that the culprit causing the issue got disabled. If you'd like to learn more about the topic, check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) and follow the steps listed there.

## 7\. Create Another User Account

 If some of the files in your user account have become corrupt, you may have difficulty performing simple tasks like opening an app. If that seems to be the case, your best option is to create and switch to a new user account.

To create a new user account on Windows:

1. Use one of the [many ways to open the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Other users** .
3. Click the**Add account** button.
4. In the Microsoft account window, click **I don't have this person's sign-in information** .  
![Microsoft Account Sign-In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/microsoft-account-sign-in-window.jpg)

 Follow the on-screen prompts to create a new user account. Make sure you give the new account administrative privileges so that you can [move your personal files and data to the new account](https://www.makeuseof.com/windows-10-copy-files-between-user-accounts/) with ease.

 Once you sign in with your newly created account, Notepad should open without problems.

## Start Using Notepad Again

 Hopefully, the solutions provided above have helped, and you’re able to use Notepad again. However, if none of the above solutions work, you can perform a system restore to undo any recent changes that may have caused the problem.


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
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-salvage-dormant-wsreset-service-on-windows/"><u>Steps to Salvage Dormant WSReset Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-chatting-experience-with-10-fixes/"><u>Revitalize Your Chatting Experience with 10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-windows-11-determine-software-harmony/"><u>How Does Windows 11 Determine Software Harmony?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-you-play-mp4-on-huawei-nova-y71-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can you play MP4 on Huawei Nova Y71?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinstate-preview-screens-for-files-troubleshoot-on-win-11/"><u>Reinstate Preview Screens for Files – Troubleshoot on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-in-use-resource-error-in-windows-oses-149-chars/"><u>Overcoming In-Use Resource Error in Windows OSes (149 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-repairing-razer-synapse-fixes-for-modern-oses/"><u>Swift Repairing: Razer Synapse Fixes for Modern OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-speech-detection-with-windows/"><u>Streamlining Speech Detection with Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-the-apple-iphone-14-plus-icloud-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing the Apple iPhone 14 Plus iCloud Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-steam-library-no-sync-error-solution/"><u>Tackling Steam Library: No Sync Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-double-click-with-these-simple-windows-adjustments/"><u>Optimize Your Double-Click with These Simple Windows Adjustments</u></a></li>
<li><a href="https://extra-tips.techidaily.com/share-smiles-and-photos-iphones/"><u>Share Smiles & Photos (iPhones)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-data-transfer-mishaps-with-windows-usb-devices/"><u>Reversing Data Transfer Mishaps with Windows USB Devices</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-resize-flv-video-efficientlywindows-mac-android-iphone-and/"><u>Updated How to Resize FLV Video EfficientlyWindows, Mac, Android, iPhone &</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-for-a-functional-windows-11-search-interface/"><u>Quick Steps for a Functional Windows 11 Search Interface</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-oneplus-12rfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your OnePlus 12RFRP Lock</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-mend-windows-disk-read-problems/"><u>Guide to Mend Windows Disk Read Problems</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-essential-mac-friendly-audio-mixers-the-ultimate-list-of-the-best-5/"><u>Updated In 2024, Essential Mac-Friendly Audio Mixers The Ultimate List of the Best 5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-setup-for-gpt/"><u>Navigating Through Windows Setup for GPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-simple-fixes-for-your-non-operational-windows-notepad/"><u>Five Simple Fixes for Your Non-Operational Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-to-windows-11-home-settings/"><u>Navigating to Windows 11 Home Settings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-vivo-x-fold-2-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Vivo X Fold 2 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-implementing-youtubes-custom-markup-guide/"><u>In 2024, Implementing YouTube's Custom Markup Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-how-to-use-kinemaster-online-and-10-best-online-alternatives/"><u>[New] How To Use KineMaster Online and 10 Best Online Alternatives</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixes-for-failed-security-codes-in-epic-games-launcher-on-windows-pcs/"><u>Fixes for Failed Security Codes in Epic Games Launcher on Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-cant-stop-your-generic-volume-device-error/"><u>How to Fix the “Windows Can’t Stop Your Generic Volume Device” Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/key-mobile-links-android-and-windows-compatible-tools/"><u>Key Mobile Links: Android & Windows Compatible Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-mode-off-how-to-turn-down-windows-11/"><u>Stealth Mode Off: How to Turn Down Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-interface-error-in-windows-os/"><u>Fixing Steam Interface Error in Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-vivo-y27s-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Vivo Y27s</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-winscomrssvdll-issues-during-system-boot/"><u>Steps to Address WinscomrssvDll Issues During System Boot</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlined-approach-automated-password-addition-into-windows-texts/"><u>Streamlined Approach: Automated Password Addition Into Windows Texts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-portals-to-nintendo-switch-gaming/"><u>Essential Windows Portals to Nintendo Switch Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-files-on-windows-using-python-for-network-transfer/"><u>Seamless Files on Windows: Using Python for Network Transfer</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-transform-your-digital-self-updating-status-and-avatars-on-discord/"><u>2024 Approved  Transform Your Digital Self  Updating Status & Avatars on Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-curtail-pc-sound-enhancement-effects/"><u>How To Curtail PC Sound Enhancement Effects</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-binge-watching-to-billions-jake-pauls-video-venture/"><u>[Updated] In 2024, Binge-Watching to Billions  Jake Paul's Video Venture</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-overheat-during-intense-play/"><u>Minimizing Overheat During Intense Play</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-steam-login-lock-ups-with-rust-and-windows/"><u>Navigating Through Steam Login Lock-Ups with Rust & Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-years-top-twitter-treasures-most-engaged-videos/"><u>[Updated] Year's Top Twitter Treasures  Most Engaged Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/peak-performance-selective-software-secrets-for-speedy-wins/"><u>Peak Performance: Selective Software Secrets for Speedy Wins</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrecting-the-lost-top-tips-to-regain-missing-windows-in-11/"><u>Resurrecting the Lost: Top Tips to Regain Missing Windows in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-same-account-error-in-multiuser-setup/"><u>Eradicating Same Account Error in Multiuser Setup</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tricks-to-jumpstart-a-nonfunctional-terminal/"><u>Essential Tricks to Jumpstart a Nonfunctional Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-live-feed-rates-on-task-monitor-win-11/"><u>Improve Live Feed Rates on Task Monitor Win 11</u></a></li>
</ul></div>
