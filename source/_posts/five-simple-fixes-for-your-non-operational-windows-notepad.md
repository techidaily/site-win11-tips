---
title: Five Simple Fixes for Your Non-Operational Windows Notepad
date: 2024-06-25T16:09:29.179Z
updated: 2024-06-26T16:09:29.179Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Five Simple Fixes for Your Non-Operational Windows Notepad
excerpt: This Article Describes Five Simple Fixes for Your Non-Operational Windows Notepad
keywords: Windows Notepad Troubleshoot,Notepad Repair Steps,Fixing Non-Functional Notepad,Notepad Error Resolution,Restart Notepad Tips,Stop Notepad Crash,Quick Notepad FIX Guide
thumbnail: https://thmb.techidaily.com/6d6520e192a843298c5f3fb60d79f701e9d849b7c957109090842f5892749c79.jpg
---

## Five Simple Fixes for Your Non-Operational Windows Notepad

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
<li><a href="https://win11-tips.techidaily.com/eliminating-self-closure-in-windows-os/"><u>Eliminating Self-Closure in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-updater-error-code-0xca00a009/"><u>Addressing Windows Updater Error Code: 0XCA00A009</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-blanking-and-flashing-windows-11-screen/"><u>Stop Blanking and Flashing Windows 11 Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-the-barrier-win-solution-for-epic-games-access/"><u>Bypassing the Barrier: Win Solution for Epic Games Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-strategies-to-eradicate-failed-rpc-in-windows/"><u>Top 5 Strategies to Eradicate Failed RPC in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/wsls-role-in-boosting-linux-desktops/"><u>WSL's Role in Boosting Linux Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-adobe-reader-setup-on-ms-store/"><u>Effortless Adobe Reader Setup on MS Store</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-guide-starting-wordpad-efficiently-on-windows/"><u>Essential Guide: Starting WordPad Efficiently on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfettered-functions-embrace-tiny11s-power/"><u>Unfettered Functions: Embrace Tiny11's Power</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-lsa-errors/"><u>Troubleshooting Windows LSA Errors</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-crafting-standout-content-on-reddit-strategic-guide-available/"><u>[New] Crafting Standout Content on Reddit - Strategic Guide Available</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On Apple iPhone XS Max?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-multitask-media-magic-employing-netflix-picture-in-picture/"><u>In 2024, Multitask Media Magic  Employing Netflix Picture-in-Picture</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-experts-approach-to-inserting-subtitlescc-on-youtube-videos/"><u>2024 Approved  The Expert's Approach to Inserting Subtitles/CC on YouTube Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/smooth-insertion-of-videos-into-your-custom-youtube-shelves-for-2024/"><u>Smooth Insertion of Videos Into Your Custom YouTube Shelves for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-4-effective-methods-fake-gps-location-on-apple-iphone-seipad-drfone-by-drfone-virtual-ios/"><u>In 2024, 4 Effective Methods Fake GPS Location on Apple iPhone SE/iPad | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-giggles-in-a-box-iphone-fun/"><u>[Updated] Giggles in a Box (iPhone Fun)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-cost-free-screen-capture-for-windowsmacos-users-for-2024/"><u>[Updated] Cost-Free Screen Capture for Windows/macOS Users for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unlock-the-hidden-potential-of-windows-11-with-these-tips/"><u>[New] Unlock the Hidden Potential of Windows 11 with These Tips</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
</ul></div>
