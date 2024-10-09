---
title: Techniques for Disabling Voice AI on Win11
date: 2024-10-07T19:17:02.627Z
updated: 2024-10-08T17:47:42.210Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Disabling Voice AI on Win11
excerpt: This Article Describes Techniques for Disabling Voice AI on Win11
keywords: Win11 Voice Disable,VOIP Tech Disabling,AI Speech Block Win11,Windows Stop AI Talk,Silence Win11 AI,Tech Halt Voice Win,Disable Win11 Voice AI
thumbnail: https://thmb.techidaily.com/2f5a7138163b464da142425b5cd4fc9ef8759bb9361cd872c71016b4ccd5a432.jpg
---

## Techniques for Disabling Voice AI on Win11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-beneath-the-wave-expert-strategies-for-filming-with-gopro-below-water/"><u>[Updated] 2024 Approved Beneath the Wave Expert Strategies for Filming with GoPro Below Water</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-stepwise-approach-transform-fish-voices-on-pcs/"><u>[Updated] Stepwise Approach Transform Fish Voices on PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/accelerate-your-downloads-on-origin-with-these-essential-tricks-for-faster-internet-speeds/"><u>Accelerate Your Downloads on Origin with These Essential Tricks for Faster Internet Speeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clean-slate-clearing-windows-11-activity-record/"><u>Clean Slate: Clearing Windows 11 Activity Record</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-on-time-spent-error-0x800736cc-in-windows-update/"><u>Cutting Down on Time Spent: Error 0X800736CC in Windows Update</u></a></li>
<li><a href="https://fox-glue.techidaily.com/editing-essentials-embark-on-your-lunapic-adventure-for-2024/"><u>Editing Essentials Embark on Your LunaPic Adventure for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/elite-gaming-experience-decoded-the-xbox-ones-best-controller-reviewed/"><u>Elite Gaming Experience Decoded: The Xbox One's Best Controller Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-command-line-experience-make-terminal-first/"><u>Enhance Command Line Experience: Make Terminal First</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/exploring-the-top-features-of-an-exceptional-iphone-case-with-a-tactile-keyboard-more-than-meets-the-eye/"><u>Exploring the Top Features of an Exceptional iPhone Case with a Tactile Keyboard - More than Meets the Eye!</u></a></li>
<li><a href="https://fox-that.techidaily.com/fix-an-unresponsive-standby-mode-a-step-by-step-guide-for-iphone-users/"><u>Fix an Unresponsive Standby Mode: A Step-by-Step Guide for iPhone Users</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-oneplus-nord-ce-3-5g-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass OnePlus Nord CE 3 5G FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-for-recovering-lost-settings-from-nvidia-control-center/"><u>Methods for Recovering Lost Settings From NVidia Control Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-10-store-errors-a-quick-guide/"><u>Tackling Windows 10 Store Errors: A Quick Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-guide-to-cam-cover-selection-for-2024/"><u>The Ultimate Guide to Cam Cover Selection for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-github-desktop-efficiently-on-windows-11-pro/"><u>Utilizing GitHub Desktop Efficiently on Windows 11 Pro</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    