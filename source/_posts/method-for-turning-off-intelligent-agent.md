---
title: Method for Turning Off Intelligent Agent
date: 2024-11-05T14:34:19.923Z
updated: 2024-11-06T22:27:23.281Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Method for Turning Off Intelligent Agent
excerpt: This Article Describes Method for Turning Off Intelligent Agent
keywords: Stop Intelligent Agents Method,Deactivating Smart Agent,Disable AI Agent,Terminate AI Functionality,Cease Auto-Responsive Agents,Turn Off Smart Agents,Halt Autonomous Agents
thumbnail: https://thmb.techidaily.com/0f7cc598462e00e671398d3de2bdb7c71a59af5f2607e912d55b8b85ab2b5c83.jpg
---

## Method for Turning Off Intelligent Agent

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
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-free-aesthetic-essentials-for-youtube-artistry/"><u>[New] 2024 Approved Free Aesthetic Essentials for YouTube Artistry</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-campaign-tactics-for-enhancing-health-awareness/"><u>[New] In 2024, Campaign Tactics for Enhancing Health Awareness</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-little-legends-top-gaming-adventures-in-2024/"><u>[New] Little Legends Top Gaming Adventures, In 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-exclusive-guide-to-the-best-chrome-extensions-for-fb-videos-for-2024/"><u>[Updated] Exclusive Guide to the Best Chrome Extensions for FB Videos for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-clearer-view-deeper-insight-zoom-techniques-in-videoleap/"><u>2024 Approved Clearer View, Deeper Insight Zoom Techniques in Videoleap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-win11-bluescreen-error-with-top-11-remedies/"><u>Conquer the Win11 Bluescreen Error with Top 11 Remedies</u></a></li>
<li><a href="https://tech-revival.techidaily.com/guia-definitiva-para-convertir-tu-musica-en-mp4-con-sonido-impecable-a-partir-de-archivos-mod/"><u>Guía Definitiva Para Convertir Tu Música en MP4 Con Sonido Impecable a Partir De Archivos MOD</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-12-mini-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 12 mini iOS System? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-turn-off-spotify-playback-at-os-boot/"><u>How To Turn Off Spotify Playback at OS Boot</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-coordinating-multiple-channels-on-one-screen/"><u>In 2024, Coordinating Multiple Channels on One Screen</u></a></li>
<li><a href="https://driver-install.techidaily.com/keeping-it-current-how-to-efficiently-install-intel-82579lm-drivers/"><u>Keeping It Current: How to Efficiently Install Intel 82579LM Drivers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-time-discrepancies-in-chrome-windows/"><u>Resolving Time Discrepancies in Chrome (Windows)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-microsoft-error-resolution-on-w11/"><u>Step-by-Step Guide to Microsoft Error Resolution on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-sluggishness-solutions-for-a-swift-windows-11/"><u>Tackling Sluggishness: Solutions for a Swift Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-graphics-performance-in-windows-11-pcs/"><u>Tailor Graphics Performance in Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-reclaiming-absent-pane-windows-6-ways/"><u>Win11 – Reclaiming Absent Pane Windows (6 Ways)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-world-wonders-per-screen-themes-for-multitaskers-on-windows/"><u>Window World Wonders: Per Screen Themes for Multitaskers on Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    