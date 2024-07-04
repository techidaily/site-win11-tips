---
title: Stopping Intelligent Assistant Protocol on Windows
date: 2024-06-25T17:12:00.568Z
updated: 2024-06-26T17:12:00.569Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/remedy-for-camera-not-detected-error-on-win11/"><u>Remedy for “Camera Not Detected” Error on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-dxgierror-with-device-reattachment/"><u>Combat DXGI_ERROR with Device Reattachment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screener-a-step-by-step-customization-guide/"><u>Windows 11 Screener: A Step-by-Step Customization Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-sharpen-your-windows-11-multi-tasking-skills/"><u>Strategies to Sharpen Your Windows 11 Multi-Tasking Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-msresourceappname-text-glitch-win11-fix/"><u>Addressing 'MsResource/AppName Text' Glitch, Win11 Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-your-system-space-essential-windows-extras-for-elimination/"><u>Revamp Your System Space: Essential Windows Extras for Elimination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-adjustments-nine-fixes-to-smooth-out-windows-11-gaming/"><u>Accelerated Adjustments: Nine Fixes to Smooth Out Windows 11 Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/memory-and-cpu-efficiency-in-browsers-a-windowsmacoschromeos-comparison/"><u>Memory and CPU Efficiency in Browsers: A Windows/macOS/ChromeOS Comparison</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284663391-version-compatibility/"><u>Version Compatibility:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-procedure-for-gpu-detection-in-windows-11/"><u>Speedy Procedure for GPU Detection in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-kindred-android-companions-for-nintendoenasportable-gaming-for-2024/"><u>[Updated] Kindred Android Companions for Nintendo'enasportable Gaming for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>How to Change Location on TikTok to See More Content On your Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-decoding-the-essentials-of-your-youtube-tv-experience/"><u>[Updated] 2024 Approved  Decoding the Essentials of Your YouTube TV Experience</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-ditch-adobe-10-free-and-open-source-video-editors-for-linux/"><u>Updated 2024 Approved Ditch Adobe 10 Free and Open-Source Video Editors for Linux</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-comedic-journey-an-evaluation-of-goofy-adventures/"><u>2024 Approved  The Comedic Journey  An Evaluation of 'Goofy Adventures'</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-future-of-android-gaming-its-all-in-kinemaster-review/"><u>[Updated] The Future of Android Gaming? It's All in KineMaster Review</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-complete-manual-of-garageband-audio-sessions/"><u>New The Complete Manual of GarageBand Audio Sessions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/seamlessly-preserve-your-ppt-video-recording-tips/"><u>Seamlessly Preserve Your PPT  Video Recording Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leading-phones-best-gopro-videos-editing-tools/"><u>2024 Approved  Leading Phones' Best GoPro Videos Editing Tools</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-unleash-the-power-of-3d-video-editing-techniques-for-windows-users/"><u>New In 2024, Unleash the Power of 3D Video Editing Techniques for Windows Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>