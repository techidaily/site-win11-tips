---
title: Removing Copilot From Your Windows Environment
date: 2024-08-16T01:47:01.293Z
updated: 2024-08-17T01:47:01.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Copilot From Your Windows Environment
excerpt: This Article Describes Removing Copilot From Your Windows Environment
keywords: Uninstall Copilot,Remove Copilot,Delete Copilot,Stop Copilot Install,Eliminate AI Helper,Exclude Copilot Windows,Oust Code Assistant
thumbnail: https://thmb.techidaily.com/5255f0c0ac11261d99ef752e1d8ce7d04128bb9f458962890dfc3acd59ac69d0.jpg
---

## Removing Copilot From Your Windows Environment

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-varieties-of-fb-video-screens/"><u>[New] 2024 Approved  Varieties of FB Video Screens</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-unleash-marketing-potential-with-unpacked-plans/"><u>[New] Unleash Marketing Potential with Unpacked Plans</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-legally-convert-youtube-videos-to-mp4-format/"><u>[Updated] 2024 Approved  How to Legally Convert YouTube Videos to MP4 Format</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-gamerecorder-gambit-for-2024/"><u>[Updated] GameRecorder Gambit for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-go-global-with-music-transform-your-spotify-lists-into-youtube-videos-for-2024/"><u>[Updated] Go Global with Music  Transform Your Spotify Lists Into YouTube Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-error-0xca00a009-from-windows-update-logs/"><u>Clearing Error 0xCA00A009 From Windows Update Logs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-0x8007045d-failure-on-microsoft-oses/"><u>Correcting 0X8007045D Failure on Microsoft OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-secure-quick-access-button-in-windows-11-for-hardware-unhook/"><u>Craft Secure, Quick Access Button in Windows 11 for Hardware Unhook</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-your-pcs-intel-processor-gen-through-windows/"><u>Deciphering Your PC's Intel Processor Gen Through Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-resolving-win11-installation-anomalies-quickly/"><u>Decoding and Resolving Win11 Installation Anomalies Quickly</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-realme-narzo-n55-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Realme Narzo N55</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-steps-to-stabilize-screen-flickering-in-windows/"><u>Effective Steps to Stabilize Screen Flickering in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-system-fixes-via-hotkey-configurations-in-w1011/"><u>Efficient System Fixes via Hotkey Configurations in W10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-collaboration-with-these-5-innovative-windows-folder-techniques/"><u>Enhance Collaboration with These 5 Innovative Windows Folder Techniques</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-ios-resources-for-enjoying-psp-games/"><u>Essential iOS Resources for Enjoying PSP Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explaining-and-solving-the-problem-of-missing-windows-drive-letters/"><u>Explaining and Solving The Problem Of Missing Windows Drive Letters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-to-overcome-same-user-account-error-on-pc/"><u>Guidance to Overcome Same-User Account Error on PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-on-apple-watch-or-apple-iphone-12-pro-by-drfone-ios/"><u>How To Bypass Activation Lock On Apple Watch Or Apple iPhone 12 Pro?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-explore-tab-noise-in-windows/"><u>How to Minimize Explore Tab Noise in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-pro-max-to-others-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 Pro Max To Others Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-launchpad-for-novice-gopro-owners-must-have-gear-guide/"><u>In 2024, Launchpad for Novice GoPro Owners - Must-Have Gear Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-out-invaders-effective-windows-access-blockers/"><u>Keeping Out Invaders: Effective Windows Access Blockers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-high-gpu-activity-in-windows-desktop-window/"><u>Managing High GPU Activity in Windows Desktop Window</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-full-hd-classics-proven-scummvm-strategies-for-the-windows-aficionado/"><u>Mastering Full HD Classics: Proven ScummVM Strategies for the Windows Aficionado</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-the-art-of-virtual-board-usage-in-web-conferences-android-apple-and-pc/"><u>Mastering the Art of Virtual Board Usage in Web Conferences  Android, Apple & PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-formatting-essential-disk-error-on-pc/"><u>Navigating the 'Formatting Essential' Disk Error on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimum-virtual-options-tailored-for-windows-11-systems/"><u>Optimum Virtual Options Tailored for Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x80242016-error-in-windows-updates/"><u>Overcoming 0X80242016 Error in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-buffering-issues-on-chrome-and-youtube/"><u>Overcoming Buffering Issues on Chrome & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-package-registration-on-windows-1011/"><u>Overcoming Obstacles in Package Registration on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-tips-the-top-7-windows-activities-that-could-be-risky/"><u>Preventive Tips: The Top 7 Windows Activities That Could Be Risky</u></a></li>
<li><a href="https://howto.techidaily.com/realme-c67-4g-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme C67 4G Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refreshing-your-pc-resetting-windows-11-applications/"><u>Refreshing Your PC: Resetting Windows 11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-wi-fi-harmony-top-solutions-to-cure-non-functioning-usb-on-windows/"><u>Regain Wi-Fi Harmony: Top Solutions to Cure Non-Functioning USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-device-opens-on-audacity-in-windows-os/"><u>Remedying Device Opens on Audacity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sketchmasters-roundup-top-7-drawing-tools-for-windows/"><u>SketchMasters Roundup: Top 7 Drawing Tools for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smooth-launch-into-lotr-world-lol/"><u>Smooth Launch Into LOTR World (LOL)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-cross-language-switching-hotkeys-in-windows-1011/"><u>Speedy Cross-Language Switching: Hotkeys in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-audacity-audio-error-win1011/"><u>Strategies to Overcome Audacity Audio Error (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/time-traveling-computers-into-the-windows-11-era-with-old-tools/"><u>Time Traveling Computers Into the Windows 11 Era with Old Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-preventing-unwanted-command-window-activation/"><u>Tips for Preventing Unwanted Command Window Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transferring-older-pc-tools-from-legacy-systems-to-windows-11/"><u>Transferring Older PC Tools: From Legacy Systems to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-workspace-managing-windows-folders-and-files/"><u>Unified Workspace: Managing Windows Folders & Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-and-phone-link-debate-best-windows-phone-app-evaluation/"><u>Unison & Phone Link Debate: Best Windows Phone App Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-assistive-features-a-quick-guide/"><u>Unlocking Windows' Assistive Features: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-software-to-supercharge-macos-functionality/"><u>Utilizing Windows Software to Supercharge macOS Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-yourphoneexe-necessary-or-not-for-security/"><u>Windows' YourPhone.exe - Necessary or Not for Security?</u></a></li>
</ul></div>
