---
title: Stopping Intelligent Assistant Protocol on Windows
date: 2024-07-12T17:45:46.398Z
updated: 2024-07-13T17:45:46.398Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Intelligent Assistant Protocol on Windows
excerpt: This Article Describes Stopping Intelligent Assistant Protocol on Windows
keywords: Stop AI Windows Protocol,Disable Windows Assistant,Cease IntelliAssist Windows,Halt Microsoft Assistant,Block Windows Intelligent Assistance,Quell Windows Assistant Service,Terminate IntelliAide on PC
thumbnail: https://thmb.techidaily.com/eb0b88fc8ea01a6f57ac593062a230bcd4f411a04c405e68f58f5857acd450ec.jpg
---

## Stopping Intelligent Assistant Protocol on Windows

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
<li><a href="https://win11-tips.techidaily.com/how-to-open-programs-with-preset-window-sizes-in-windows-11/"><u>How to Open Programs With Preset Window Sizes in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Vivo V27 Pro? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/harmonizing-audio-and-visuals-in-vimeo-media/"><u>Harmonizing Audio and Visuals in Vimeo Media</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-remove-google-frp-lock-on-motorola-razr-40-by-drfone-android-unlock-remove-google-frp/"><u>Quickly Remove Google FRP Lock on Motorola Razr 40</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-to-utilizing-diskusage-on-windows-systems/"><u>Expert Guide to Utilizing DiskUsage on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-make-your-photos-pop-top-animated-photo-creators/"><u>In 2024, Make Your Photos Pop Top Animated Photo Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-gaming-service-failures-on-pcs-and-laptops/"><u>How To Resolve Gaming Service Failures on PCs and Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-video-cutting-solutions-on-your-windows-11-system/"><u>Masterful Video Cutting Solutions on Your Windows 11 System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-hyper-v-installation-on-w11-home-systems/"><u>Master the Art of Hyper-V Installation on W11 Home Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-xs-max-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>Unlock iPhone XS Max With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-2d-to-spatial-the-evolution-of-cinematic-videos/"><u>[Updated] From 2D to Spatial  The Evolution of Cinematic Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-complete-blueprint-for-effective-lut-usage-in-editing/"><u>2024 Approved  The Complete Blueprint for Effective LUT Usage in Editing</u></a></li>
<li><a href="https://youtube-help.techidaily.com/expert-audio-guide-for-vloggers-for-2024/"><u>Expert Audio Guide for Vloggers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-analysis-creating-and-interpreting-data/"><u>Navigating Windows Analysis: Creating & Interpreting Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-error-0xc0000142-in-win7win8/"><u>Resolving Error 0XC0000142 in Win7/Win8</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unlock-your-screen-androids-premier-free-recorder-tools/"><u>Unlock Your Screen  Android's Premier Free Recorder Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reboot-dns-cache-in-windows-11/"><u>How to Reboot DNS Cache in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/hearnow-podcast-and-speaker-assessment/"><u>HearNow  Podcast and Speaker Assessment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-in-device-coexistence-utilize-dex-for-galaxy-on-pc/"><u>Mastery in Device Coexistence: Utilize DeX for Galaxy on PC</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-elevating-video-clarity-methods-for-eradicating-inaudible-roughness-in-soundtracks-for-2024/"><u>New Elevating Video Clarity Methods for Eradicating Inaudible Roughness in Soundtracks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fix-windows-11-graphics-drivers-reset/"><u>Efficient Fix: Windows 11 Graphics Drivers Reset</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-video-aspects-online/"><u>Mastering Video Aspects Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methodical-approach-to-reviving-frozen-start-button/"><u>Methodical Approach to Reviving Frozen Start Button</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-ram-cache-and-how-to-purge-it/"><u>Decoding Windows RAM Cache and How to Purge It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curtailing-premature-windows-edge-tabs/"><u>Curtailing Premature Windows Edge Tabs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-hard-drives-terrain-a-guide-to-diskusage-in-windows/"><u>Navigating Through Your Hard Drive's Terrain: A Guide to DiskUsage in Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-expert-strategies-for-success-on-ginger-island/"><u>2024 Approved  Expert Strategies for Success on Ginger Island</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cooling-policies-in-microsofts-os-environment/"><u>Navigating Cooling Policies in Microsoft's OS Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quelling-win1011-screen-glitches-with-ease/"><u>Quelling WIN10/11 Screen Glitches with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-task-manager-with-finesse/"><u>Elevating Task Manager with Finesse</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-the-ultimate-cheat-sheet-inserting-vimeo-videos-into-slides-for-2024/"><u>[Updated] The Ultimate Cheat Sheet  Inserting Vimeo Videos Into Slides for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-get-videoleap-on-your-macbook-download-and-installation-tutorial-for-2024/"><u>New Get Videoleap on Your MacBook Download and Installation Tutorial for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/refining-windows-11-for-superior-usability/"><u>Refining Windows 11 for Superior Usability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-fixing-fall-guys-link-failures-windows-wise/"><u>Essential Steps for Fixing Fall Guys Link Failures Windows-Wise</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alternate-routes-to-open-the-latest-windows-apps/"><u>Alternate Routes to Open the Latest Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-windows-11-the-8-most-common-mistakes-for-beginners-to-skip/"><u>Navigating Windows 11: The 8 Most Common Mistakes for Beginners to Skip</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-google-maps-in-your-windows-system/"><u>Harnessing the Power of Google Maps in Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightness-boost-for-windows-11-control-your-pcs-glow/"><u>Brightness Boost for Windows 11: Control Your PC's Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-challenges-a-guide-to-fixing-your-manager-tool-in-windows-11/"><u>Navigating Challenges: A Guide to Fixing Your Manager Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719328086208-calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-geforce-experiences-retrieval-failure-on-windows-11-systems/"><u>Fixing GeForce Experience's Retrieval Failure on Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-microsoft-outlooks-something-went-wrong-error-on-windows/"><u>How to Fix Microsoft Outlook's “Something Went Wrong” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-a-windows-11-recycle-bin-malfunction/"><u>Fixing a Windows 11 Recycle Bin Malfunction</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-window-restoration-after-dark-screens/"><u>Effortless Window Restoration After Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-techniques-for-troubled-windows-11-calendars/"><u>Resetting Techniques for Troubled Windows 11 Calendars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-save-windows-spotlight-pictures-to-use-as-wallpapers-when-you-want/"><u>How to Save Windows Spotlight Pictures to Use as Wallpapers When You Want</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-viewers-to-earners-journey-calculating-necessary-counts/"><u>[New] Viewers to Earner's Journey  Calculating Necessary Counts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-efficiency-into-daily-use-with-win11-icon-additions/"><u>Integrating Efficiency Into Daily Use with Win11 Icon Additions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/jump-from-smartphone-to-desktop-android-gameplay-in-windows-11-with-google/"><u>Jump From Smartphone to Desktop: Android Gameplay in Windows 11 with Google</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-functionality-of-windows-component-services/"><u>Insight Into the Functionality of Windows Component Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-11-command-not-working-issue/"><u>Fixing Windows 11 Command Not Working Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-output-with-windows-streamlined-launcher/"><u>Maximize Output with Windows' Streamlined Launcher</u></a></li>
</ul></div>
