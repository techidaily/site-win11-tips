---
title: Techniques to Switch Off Microsoft's Assistant
date: 2024-06-25T16:23:32.620Z
updated: 2024-06-26T16:23:32.620Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Switch Off Microsoft's Assistant
excerpt: This Article Describes Techniques to Switch Off Microsoft's Assistant
keywords: Disabling Cortana,Turning Off AI,Shutting Down MS Assist,Stop Microsoft Assistant,Silence Cortana,Deactivate AI Helper,Cease Microsoft's Help
thumbnail: https://thmb.techidaily.com/4f252061500e08e9c2f2521977c5b0253a500625454298afd84e9855ed4fbb6b.jpg
---

## Techniques to Switch Off Microsoft's Assistant

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
<li><a href="https://win11-tips.techidaily.com/easy-routines-to-reactivate-window-explorer/"><u>Easy Routines to Reactivate Window Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icloud-on-windows-common-fixes-for-download-problems/"><u>ICloud on Windows: Common Fixes for Download Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-obscured-network-visibility-in-windows/"><u>Curing Obscured Network Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-win1011-recycle-bin-repair-strategies/"><u>Mastering WIN10/11 Recycle Bin Repair Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-your-digital-life-winning-crypto-apps-ranked-150-chars/"><u>Secure Your Digital Life: Winning Crypto Apps Ranked (150 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storage-soaring-speeds-stalling-mp60-model/"><u>Storage Soaring, Speeds Stalling - MP60 Model</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-guide-to-snap-uac-dialogues/"><u>A Step-by-Step Guide to Snap UAC Dialogues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-ensure-complete-ram-usage-by-windows-os/"><u>Strategies to Ensure Complete RAM Usage by Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualize-storage-quickly-integrate-diskanalyzer-into-windows-menu/"><u>Visualize Storage Quickly: Integrate DiskAnalyzer Into Windows Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-common-captioning-hurdles-on-windows-10-devices/"><u>Solving Common Captioning Hurdles on Windows 10 Devices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-tech-savvy-strategies-for-harvesting-and-saving-facebooks-most-trendy-gifs/"><u>[New] In 2024, Tech Savvy Strategies for Harvesting & Saving Facebook's Most Trendy GIFs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-windows-10-video-grabber-ultimate-for-2024/"><u>[Updated] Windows 10 Video Grabber Ultimate for 2024</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-8-best-motion-graphics-online-tools-for-your-inspiration/"><u>New 2024 Approved 8 Best Motion Graphics Online Tools for Your Inspiration</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-convert-facebook-posts-to-mp3-files-for-2024/"><u>[Updated] Convert Facebook Posts to MP3 Files for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-crafting-captivating-thumbnails-a-digital-marketers-guidebook/"><u>[Updated] 2024 Approved  Crafting Captivating Thumbnails  A Digital Marketer's Guidebook</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-lyric-purifier-toolkit-assemble-custom-music-beds/"><u>Updated Lyric Purifier Toolkit Assemble Custom Music Beds</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-earning-novice-navigators-essential-guide-for-2024/"><u>YouTube Earning  Novice Navigator's Essential Guide for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-untold-elements-of-instagram-story-engagement/"><u>[New] In 2024, The Untold Elements of Instagram Story Engagement</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-detailed-steps-to-add-border-to-video-using-premiere-pro/"><u>In 2024, Detailed Steps to Add Border to Video Using Premiere Pro</u></a></li>
<li><a href="https://some-techniques.techidaily.com/harmonizing-your-device-importing-to-inshot-app-for-2024/"><u>Harmonizing Your Device  Importing to InShot App for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>