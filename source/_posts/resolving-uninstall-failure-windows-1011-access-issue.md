---
title: "Resolving Uninstall Failure: Windows 10/11 Access Issue"
date: 2024-07-12T17:30:12.512Z
updated: 2024-07-13T17:30:12.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Uninstall Failure: Windows 10/11 Access Issue"
excerpt: "This Article Describes Resolving Uninstall Failure: Windows 10/11 Access Issue"
keywords: Fix Uninstall Error W10/W11,Windows Uninstall Hang-Up,Resolve Win10 Install Fail,Overcome Win10 Uninstall Issue,Address Win10 Access Problem,Correct Uninstall Fails, W10,Stop Win11/10 Uninstall Blocks
thumbnail: https://thmb.techidaily.com/04f98c03565f60c0b0ad3b1ba3f80966cc746c43e46cf7809dfb5c690e2c4abe.jpg
---

## Resolving Uninstall Failure: Windows 10/11 Access Issue

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  
![The Program Install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-list.jpg)

## 4\. Turn Off User Account Control

 The “You do not have sufficient access to uninstall” error can sometimes arise because User Account Control is set to high. So, try temporarily turning UAC off before uninstalling the affected software. Our guide on [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off UAC.

![The User Account Control settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control.jpg)

## 5\. Set Full Control Permissions for the Software’s Installation Folder

 You might need to fix this error because the full user control permission setting isn’t set for the software installation’s folder. So, check the control permission settings for the software installation folder. This is how you can set full control permission for a folder:

1. Open the folder that contains the installation directory of the affected software.
2. Right-click on the installation folder and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option3.jpg)
3. Click **Edit** on the **Security** tab.
4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.
7. Select **OK** to exit the properties window.
8. Repeat the above instructions for the program’s EXE (application) file.

## 6\. Uninstall the Software With an UninstallString Value

 Some users have resolved this error by uninstalling the affected software packages with their UninstallString values. You can do that by copying and pasting the UninstallString value for a program from the registry into the Command Prompt. These are the steps for uninstalling software with an UninstallString value:

1. Open Windows Search with **Win + S**.
2. Type in **regedit** to find the Registry Editor.
3. Select Registry Editor to launch that app.
4. Next, input this location into Registry Editor’s address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall`
5. Click on the subkeys in the **Uninstall** key to view the **DisplayName** strings for them.

1. Select the key for the software you can’t install by identifying it with the **DisplayName** string.  
![DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/display-name.jpg)
2. Double-click on the key's **UninstallString** string.
3. Copy the text in the **Value data** box by selecting it and pressing **Ctrl** \+ **C**.  
![The Edit String window for the UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window3.jpg)
4. Open Command Prompt as an admin (See [how to open Command Prompt with admin permissions](https://www.makeuseof.com/windows-run-command-prompt-admin/)).
5. Click inside the Command Prompt and press **Ctrl** \+ **V** to paste in the string.  
![An uninstall command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/undostring-command.jpg)
6. Press **Enter** to run the command and remove the software.

 Note that the above registry string is for 64-bit software. To find the strings for 32-bit software, you’ll need to go to this registry path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`

## 7\. Try Uninstalling the Software With a Third-Party Uninstaller Tool

 Third-party uninstaller tools have helped some users fix the “do not have sufficient access to uninstall” error. The [best third-party uninstaller tools](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) are superior to Windows’ Programs and Features applet for removing software. So, try uninstalling the software with a freely available utility like Revo Uninstaller, IObit Uninstaller, or Advanced Uninstaller Pro. This is how you can do that with IObit Uninstaller:

1. Open this [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) download page.
2. Select **Free Download** to save IObit Uninstaller’s setup wizard within a folder.
3. Bring up the directory containing the **iobituninstaller.exe** file.
4. Double-click the **iobituninstaller.exe** file and click **Install** in the setup wizard.
5. Open IObit Uninstaller and select the **All programs** tab.  
![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-iobit-uninstaller-software.jpg)
6. Select the program and click **Uninstall**.
7. Click on the checkbox labeled **Automatically remove residual files**.
8. Select **Uninstall** to remove the software.  
![The Uninstall button in IObit Uninstaller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-button.jpg)

## 8\. Uninstall the Software Within Safe Mode

 Safe mode is Windows troubleshooting mode in which only essential drivers and services run. Uninstalling affected software in that mode might work since it will disable things like UAC that can interfere with the uninstallation process. This guide about [entering Windows safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) covers the different ways you can enter that mode.

 However, the safe mode also disables Windows Installer (MSI). So, you’ll need to tweak the registry to prevent the disabling of Windows Installer before entering safe mode. Edit the registry as follows:

1. Start the Registry Editor as covered in steps one to three of the sixth potential solution.
2. Then input the following registry key address:  
`HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\SafeBoot\Minimal`
3. Click the **Minimal** key with your right mouse button and select **New**.
4. Select **Key** and input **MSIServer** within the text box. If that key already exists, then you need not set up a new key.  
![The New > Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-key-option.jpg)
5. Next, select the **MSIServer** key and double-click its **(Default)** string.
6. Enter **Service** in the **Value data** box and select **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window4.jpg)
7. Then enter safe mode and try uninstalling the affected software.

## Uninstall the Software You Need to Remove on Windows

 Although not guaranteed, there’s a pretty good chance one of the resolutions in this guide will resolve the “do not have sufficient access to uninstall” error on your PC. If not, consider troubleshooting the issue with a third-party PC repair tool.

 A more drastic troubleshooting method, like resetting Windows 11/10 or performing an in-place upgrade, might be required to fix system file and registry issues.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/elevate-profits-via-windows-11-pro-key-offers/"><u>Elevate Profits via Windows 11 Pro Key Offers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-subnet-changes-in-win11/"><u>Navigating Subnet Changes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-to-do-restoring-lost-sync-credentials-effectively/"><u>Microsoft To-Do: Restoring Lost Sync Credentials Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-re-listing-bluetooth-on-windows-pc/"><u>Strategies for Re-Listing Bluetooth on Windows PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-harness-youtubes-power-with-these-top-7-affordable-easy-to-use-tag-extractor-tools/"><u>[New] Harness YouTube's Power with These Top 7 Affordable, Easy-to-Use Tag Extractor Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/pushing-the-limits-of-solid-state-drives-on-windows-with-ssdfresh/"><u>Pushing the Limits of Solid State Drives on Windows with SSDFresh</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-complete-blueprint-for-extracting-fb-graphics-to-your-device-for-2024/"><u>[Updated] The Complete Blueprint for Extracting FB Graphics to Your Device for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-honor-play-8t-by-drfone-android/"><u>In 2024, How to Bypass FRP from Honor Play 8T?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implications-of-removing-windows-11-taskbar-chat-on-your-usage-experience/"><u>Implications of Removing Window's 11 Taskbar Chat on Your Usage Experience</u></a></li>
<li><a href="https://extra-information.techidaily.com/smart-tips-for-creating-time-lapses-on-samsung-devices/"><u>Smart Tips for Creating Time-Lapses on Samsung Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reinstalling-microsoft-store-apps/"><u>Guide to Reinstalling Microsoft Store Apps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-perfecting-content-aesthetics-crafting-personalized-thumbnails/"><u>[Updated] Perfecting Content Aesthetics  Crafting Personalized Thumbnails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-group-policies-in-windows-via-tripartite-lens/"><u>Exploring Group Policies in Windows via Tripartite Lens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-awful-chrome-glitches-on-microsoft-os/"><u>Fixing Awful Chrome Glitches on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-frozen-wastebin-symbol-on-win11/"><u>Reactivating Frozen Wastebin Symbol on Win11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-5-free-video-rotator-apps-for-iphone-users-2023-edition/"><u>New In 2024, Top 5 Free Video Rotator Apps for iPhone Users 2023 Edition</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-swift-transformation-video-aspects-to-mac-standard/"><u>2024 Approved  Swift Transformation  Video Aspects to Mac Standard</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-top-techs-compilation-browsers-with-the-best-snapshot-capabilities/"><u>[Updated] In 2024, Top Tech's Compilation  Browsers with the Best Snapshot Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-recover-faulty-windows-file-organizer/"><u>Methods to Recover Faulty Windows File Organizer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/verifying-microphone-function-on-windows/"><u>Verifying Microphone Function on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-read-aloud-in-office-suite-word/"><u>Fixing Non-Functional Read Aloud in Office Suite (Word)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-how-to-remove-audio-from-mov-files-on-windowsmac-for-2024/"><u>Updated How to Remove Audio From MOV Files on Windows/Mac for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-theme-that-stands-out-crafting-banners-for-gamers/"><u>[New] Theme That Stands Out  Crafting Banners for Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-tips-for-playing-old-championship-manager-on-pc/"><u>Top Tips for Playing Old Championship Manager on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-for-operational-windows-desktop-context-menus/"><u>Tactics for Operational Windows Desktop Context Menus</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/collective-wisdom-on-easeus-products/"><u>Collective Wisdom on EaseUS Products</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-unresponsive-windows-outlook-conditional-rules/"><u>Overcoming Unresponsive Windows Outlook Conditional Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steering-clear-of-low-performance-pitfalls-intel-gpu-resolution/"><u>Steering Clear of Low-Performance Pitfalls: Intel GPU Resolution</u></a></li>
<li><a href="https://facebook.techidaily.com/why-old-school-charm-may-reignite-interest-in-instagram/"><u>Why Old-School Charm May Reignite Interest in Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/teams-upgrade-fast-memory-conscious-solution/"><u>Teams Upgrade: Fast, Memory-Conscious Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-network-drive-management-with-ease-and-security-win11/"><u>Master Network Drive Management with Ease and Security (Win11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-update-failures-strategies-for-error-0x30017/"><u>Overcoming Windows Update Failures: Strategies for Error 0X30017</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-climate-change-mitigation-through-urban-design-innovations/"><u>2024 Approved  Climate Change Mitigation Through Urban Design Innovations</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-xiaomi-redmi-note-12-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Xiaomi Redmi Note 12 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-0x800713f-error-on-windows-11/"><u>Strategies to Eradicate 0X800713F Error on Windows 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/cting-the-financial-lifeblood-of-tseries-via-youtube-engagement-for-2024/"><u>Dissecting the Financial Lifeblood of TSeries via YouTube Engagement for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-ultimate-anonymous-group-communicators/"><u>In 2024, Ultimate Anonymous Group Communicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-invalid-profiles-in-windows-operating-systems/"><u>Steps to Correct Invalid Profiles in Windows Operating Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-and-resolving-issues-with-registry-editor-missing/"><u>Uncovering and Resolving Issues with 'Registry Editor' Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-response-on-windows-discord/"><u>Enhancing Real-Time Response on Windows Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11-discord-install-failure/"><u>Overcoming Windows 11 Discord Install Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-your-digital-experience-with-active-windows-11-notifications/"><u>Maximizing Your Digital Experience with Active Windows 11 Notifications</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-11-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 11 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-onedrive-errors-an-easy-guide/"><u>Overcoming Windows OneDrive Errors: An Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strengthening-game-accessibility-winning-over-ea-errors/"><u>Strengthening Game Accessibility: Winning Over EA Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ignite-old-pcs-with-windows-11-version-22h2/"><u>Ignite Old PCs with Windows 11 Version 22H2</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gourmet-giants-culinary-stars-you-must-subscribe-to/"><u>[Updated] 2024 Approved  Gourmet Giants  Culinary Stars You Must Subscribe To</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-map-integration-in-windows/"><u>Mastering Map Integration in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-installation-issues-with-windows-11-troubleshooter/"><u>Solving Installation Issues with Windows 11 Troubleshooter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedy-for-server-disruptions-and-ms-store-issues-on-windows-11-and-11/"><u>Remedy for Server Disruptions and MS Store Issues on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-desktop-arrangement-including-this-pc-icons/"><u>Efficient Desktop Arrangement: Including 'This PC' Icons</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-nullified-network-visibility-in-windows/"><u>Navigating Through Nullified Network Visibility in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-whispered-wealth-the-silent-online-auction-for-secrecys-treasures-2023/"><u>2024 Approved  Whispered Wealth  The Silent Online Auction for Secrecy's Treasures, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-solution-for-0x80072af9-issue/"><u>Mastering Solution for 0X80072AF9 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tap-out-of-high-contrast-in-windows-environment/"><u>Tap Out of High Contrast in Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silence-missed-specification-alert-on-windows-11/"><u>Silence Missed Specification Alert on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-overview-dji-inspire-1-reviewed/"><u>In 2024, The Ultimate Overview  DJI Inspire 1 Reviewed</u></a></li>
</ul></div>
