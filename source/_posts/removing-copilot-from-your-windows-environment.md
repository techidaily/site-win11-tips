---
title: Removing Copilot From Your Windows Environment
date: 2024-07-12T17:20:39.840Z
updated: 2024-07-13T17:20:39.840Z
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

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

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

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

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
<li><a href="https://win11-tips.techidaily.com/fixing-dll-not-loading-error-in-windows-steam-client/"><u>Fixing Dll Not Loading Error in Windows Steam Client</u></a></li>
<li><a href="https://some-techniques.techidaily.com/figma-mastery-techniques-to-eliminate-disruptive-backdrops-for-2024/"><u>Figma Mastery  Techniques to Eliminate Disruptive Backdrops for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosted-efficiency-expert-tips-for-optimizing-bar-use/"><u>Boosted Efficiency: Expert Tips for Optimizing Bar Use</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-professional-gopro-footage-in-3-simple-steps/"><u>2024 Approved  Professional Gopro Footage in 3 Simple Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-the-amd-installer-crash-in-windows/"><u>Quick Fixes for the AMD Installer Crash in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-instagram-mastery-for-phones-choose-from-the-top-8-timers/"><u>[Updated] In 2024, Instagram Mastery for Phones - Choose From The Top 8 Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-disable-virtual-machine-feature-in-windows-11/"><u>Instructions: Disable Virtual Machine Feature in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719336383556-mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-vivo-v27-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Vivo V27 Device</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-vivo-y02t-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Vivo Y02T Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-nvidia-configurations-on-windows-os/"><u>How to Recover NVIDIA Configurations on Windows OS</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-complete-process-of-audio-integration-into-quicktime-video-files/"><u>New 2024 Approved The Complete Process of Audio Integration Into QuickTime Video Files</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-unleashing-your-creative-potential-with-siri-on-tiktok-apps/"><u>[New] In 2024, Unleashing Your Creative Potential with Siri on TikTok Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/speedy-sketching-techniques-for-fortnite-tiles-for-2024/"><u>Speedy Sketching Techniques for Fortnite Tiles for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-transform-your-skype-speech-patterns-with-these-5-must-have-voice-change-tools/"><u>New In 2024, Transform Your Skype Speech Patterns with These 5 Must-Have Voice Change Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-device-tracking-with-windows-live-tiles/"><u>Mastering Device Tracking with Windows Live Tiles</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-this-article-talks-in-detail-about-how-to-export-imovie-video-from-iphone-mac-etc-it-also-covers-the-process-of-using-imovie-alternative-to-edit-videos-/"><u>New This Article Talks in Detail About How to Export iMovie Video From iPhone, Mac, Etc. It Also Covers the Process of Using iMovie Alternative to Edit Videos on Mac. Check Out Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-an-efficient-windows-menu-for-software-alerts/"><u>Crafting an Efficient Windows Menu for Software Alerts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/winning-game-recording-guide-for-w11-users-for-2024/"><u>Winning Game Recording Guide for W11 Users for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/documentation-skills-snapping-windows-uac-prompts/"><u>Documentation Skills: Snapping Windows UAC Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-resource-tracking-efficiency-via-windows-interfaces/"><u>Upgrade Resource Tracking Efficiency via Window's Interfaces</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-vivo-s17e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/crafting-compelling-podcast-cliffhangers-for-2024/"><u>Crafting Compelling Podcast Cliffhangers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-audio-device-isolation-explained/"><u>Windows Audio Device Isolation Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-error-unsigned-update-files-fix-guide/"><u>Windows Error: Unsigned Update Files; Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-memory-limitation-indicators-on-windowsvmware-systems/"><u>Correcting Memory Limitation Indicators on Windows/VMware Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-missing-msvcrt120dll-on-your-computer/"><u>Overcoming Missing Msvcrt120dll on Your Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimalist-workstations-with-windows-os/"><u>Minimalist Workstations with Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-for-clearing-false-device-error-on-pcs/"><u>Expert Guide for Clearing False Device Error on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/locating-and-opening-system32-windows-11/"><u>Locating and Opening System32 (Windows 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrade-browser-security-with-trusted-site-listing/"><u>Upgrade Browser Security with Trusted Site Listing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-elevate-taskmanager-with-a-new-cli-tab-windows-11/"><u>How to Elevate TaskManager with a New CLI Tab (Windows 11)</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-vivo-t2-pro-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Vivo T2 Pro 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quickly-manipulate-text-illumination-in-windows-11/"><u>Quickly Manipulate Text Illumination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-newbies-guide-to-easier-access/"><u>Windows Newbies' Guide to Easier Access</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-windows-11s-revamped-widget-interface/"><u>Implementing Windows 11'S Revamped Widget Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-linux-with-windows-tools/"><u>Enhancing Linux with Windows Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-trends-and-techniques-for-skyrocketing-youtube-views/"><u>2024 Approved  Trends and Techniques for Skyrocketing YouTube Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-mass-rename-with-powertoys/"><u>Automate Mass Rename with PowerToys</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-expert-tips-for-youtube-short-pitfall-prevention/"><u>[New] 2024 Approved  Expert Tips for YouTube Short Pitfall Prevention</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-edge-access-control-constructing-your-windows-personal-pins/"><u>Cutting-Edge Access Control: Constructing Your Windows Personal Pins</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-recovery-mode-on-apple-iphone-xs-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-from-virtual-anonymity-to-facebook-fame-how-to-expand-your-audience/"><u>[New] From Virtual Anonymity to Facebook Fame  How to Expand Your Audience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-audacitys-error-while-opening-sound-device-issue-in-windows-11-and-11/"><u>How to Fix Audacity’s “Error While Opening Sound Device” Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-system-file-verification-with-sfc/"><u>How to Start System File Verification with SFC</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-iphone-15-pro-max-drfone-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-hello-for-secure-user-access/"><u>Enabling Windows Hello for Secure User Access</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-6-platforms-revolutionizing-business-social-interaction/"><u>2024 Approved  Top 6 Platforms Revolutionizing Business-Social Interaction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-to-reactivate-googles-nearby-share-app/"><u>Essential Tips to Reactivate Google's Nearby Share App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expedite-word-clarity-with-windows-11-help/"><u>Expedite Word Clarity with Windows 11 Help</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-exploring-the-creme-de-la-creme-instas-influential-elite-for-2024/"><u>[New] Exploring the Crème De La Crème  Insta's Influential Elite for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-essential-fixes-conquer-the-windows-update-hurdles/"><u>7 Essential Fixes: Conquer the Windows Update Hurdles</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circuit-breakers-fixes-to-power-up-your-photoshop/"><u>Circuit Breakers: Fixes to Power Up Your PhotoShop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-updater-error-code-0xca00a009/"><u>Addressing Windows Updater Error Code: 0XCA00A009</u></a></li>
</ul></div>
