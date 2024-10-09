---
title: Troubleshooting Grayed-Out Recycle Bin on Win11
date: 2024-10-06T22:50:16.267Z
updated: 2024-10-09T07:42:47.783Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Grayed-Out Recycle Bin on Win11
excerpt: This Article Describes Troubleshooting Grayed-Out Recycle Bin on Win11
keywords: Fix Recycle Bin Text,Grayed Bin Windows11,Win11 Bin Icons,Clear Icon Gray Issue,Restore Recycle Icon,Win11 Troubleshoot Bin,Reset Recycle Icon Windows
thumbnail: https://thmb.techidaily.com/87eef5cf587ac33a0581d68baadab4d33ca4c311a823a65d146f4fbbcbf04745.jpg
---

## Troubleshooting Grayed-Out Recycle Bin on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-identifying-best-free-online-and-web-services-tiktok-to-mp3-converter-list-6/"><u>[New] In 2024, Identifying Best Free Online and Web Services TikTok to MP3 Converter List (6)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-6-fiscal-picks-in-the-4k-projector-market/"><u>[New] Top 6 Fiscal Picks in the 4K Projector Market</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-the-future-of-content-creation-profitability-on-youtube/"><u>[Updated] In 2024, The Future of Content Creation Profitability on YouTube</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125187084-diy-deliciousness-exploring-the-world-of-3d-chocolate-printing-with-cocoapress/"><u>DIY Deliciousness: Exploring the World of 3D Chocolate Printing with CocoaPress</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/global-gaming-revolution-oculus-quests-language-leap-with-mondly/"><u>Global Gaming Revolution: Oculus Quest's Language Leap with Mondly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-integrating-portable-tools-in-windows-11/"><u>Master the Art: Integrating Portable Tools in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/must-have-mac-frame-captures-handbook-limited-to-156-characters/"><u>Must-Have Mac Frame Captures Handbook (Limited to 156 Characters)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-destiny-2-startup-glitch-initialization-error-solutions/"><u>Overcoming Destiny 2 Startup Glitch: Initialization Error Solutions</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-honor-90-by-drfone-android/"><u>Top 10 Password Cracking Tools For Honor 90</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-10-windows-compatible-weather-apps/"><u>Top 10 Windows-Compatible Weather Apps</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unbiased-aeiusny-portable-solar-generator-analysis-ensuring-safety-with-pure-sine-wave-for-critical-health-gear/"><u>Unbiased Aeiusny Portable Solar Generator Analysis: Ensuring Safety with Pure Sine Wave for Critical Health Gear</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-your-next-win-based-game-needs-dxvk-insights-unveiled/"><u>Why Your Next Win-Based Game Needs DXVK – Insights Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-1011-mastering-dolby-atmos-setup/"><u>Win 10/11: Mastering Dolby Atmos Setup</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    