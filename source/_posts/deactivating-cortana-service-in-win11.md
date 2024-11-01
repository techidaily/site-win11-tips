---
title: Deactivating Cortana Service in Win11
date: 2024-10-26T16:09:53.320Z
updated: 2024-11-01T18:16:45.363Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deactivating Cortana Service in Win11
excerpt: This Article Describes Deactivating Cortana Service in Win11
keywords: Deactivate Cortana Win11,Disable Windows Cortana,Turn Off Cortana,Stop Cortana on Win11,Uninstall Cortana Service,End Windows Cortana,Remove Cortana Service
thumbnail: https://thmb.techidaily.com/4c64599e932018a17c352685488bbe982ee82f5fc1c73b73894ec43a1b1c5c03.jpg
---

## Deactivating Cortana Service in Win11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576477/17382" target="_top" id="1576477">
  <img src="//a.impactradius-go.com/display-ad/17382-1576477" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576477/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/asing-options-choosing-premium-vs-standard-fixtures-and-whether-they-are-integrated-or-retrofit-options-can-alter-costs-for-2024/"><u>__Purchasing Options__ Choosing Premium Vs. Standard Fixtures and Whether They Are Integrated or Retrofit Options Can Alter Costs. For 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-2024-approved-expert-picks-of-top-fee-free-live-streaming-tech-tools-for-everyone/"><u>[New] 2024 Approved Expert Picks of Top, Fee-Free Live Streaming Tech Tools for Everyone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-optimize-video-sharing-preferences-on-youtube/"><u>[New] Optimize Video Sharing Preferences on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-ultimate-ios-guide-to-premier-psp-emulators/"><u>[New] Ultimate iOS Guide to Premier PSP Emulators</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discover-the-best-11-no-fee-name-crafting-for-channels/"><u>[Updated] In 2024, Discover the Best 11 No-Fee Name Crafting for Channels</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-from-silence-to-soundscape-step-by-step-in-audition/"><u>2024 Approved From Silence to Soundscape Step-by-Step in Audition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/concealing-clock-show-dates-on-windows-interface/"><u>Concealing Clock, Show Dates on Windows Interface</u></a></li>
<li><a href="https://extra-information.techidaily.com/free-screen-capture-solutions-top-5-recommendations-for-windows/"><u>Free Screen Capture Solutions – Top 5 Recommendations for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-stuck-fixing-non-installation-of-optional-windows-11-features/"><u>Getting Stuck? Fixing Non-Installation of Optional Windows 11 Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-functionality-of-automatic-voice-feature-on-word/"><u>Regaining Functionality of Automatic Voice Feature on Word</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revolutionize-your-windows-11-routine/"><u>Revolutionize Your Windows 11 Routine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-proxy-setup-on-the-latest-win-11/"><u>Step-by-Step Proxy Setup on the Latest Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-update-and-its-companion-service/"><u>Unveiling Windows Update and Its Companion Service</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    