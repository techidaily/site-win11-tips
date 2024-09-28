---
title: Reviving Dormant Recyclebin Icon in Windows 11
date: 2024-09-24T19:19:52.272Z
updated: 2024-09-28T17:22:16.692Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Dormant Recyclebin Icon in Windows 11
excerpt: This Article Describes Reviving Dormant Recyclebin Icon in Windows 11
keywords: Rejuvenate RecycleBin Icon,Revive Waste Bin Symbol,Restore Trash Icons,Reactivate DnD Icon,Enable Bin Recovery,Resurrect Recycling Icon,Bring Back Bin Icon
thumbnail: https://thmb.techidaily.com/9c704c9ab8ca818eb8c547f35c543ea321e006214fab450eba00af5408d5f618.jpg
---

## Reviving Dormant Recyclebin Icon in Windows 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-community-builders-gamer-youtubers-for-2024/"><u>[New] Community Builders Gamer YouTubers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-visionary-designs-for-future-mojave-dwellings/"><u>[New] In 2024, Visionary Designs for Future Mojave Dwellings</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-epicurean-exploration-the-top-15-most-addictive-food-challenges-from-tiktoks-stars/"><u>[Updated] Epicurean Exploration The Top 15 Most Addictive Food Challenges From TikTok's Stars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/11-ways-to-open-system-restore-on-windows-11/"><u>11 Ways to Open System Restore on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-solutions-to-try-if-you-cannot-find-bitlocker-in-windows/"><u>4 Solutions to Try If You Cannot Find BitLocker in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-innovative-windows-tricks-for-program-launching/"><u>6 Innovative Windows Tricks for Program Launching</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-oppo-a56s-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-github-desktop-in-windows-1011/"><u>A Comprehensive Guide to GitHub Desktop in Windows 10/11</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-on-your-iphone-13-mini-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID On Your iPhone 13 mini</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieve-efficient-workflow-multi-screen-settings-in-win11/"><u>Achieve Efficient Workflow: Multi-Screen Settings in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adapting-ancient-windows-to-seniors-needs/"><u>Adapting Ancient Windows to Seniors' Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-sensitivity-on-modern-windows-devices/"><u>Balancing Sensitivity on Modern Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-your-gaming-prowess-mastering-adventure-games-in-high-definition-hd/"><u>Boost Your Gaming Prowess: Mastering Adventure Games in High-Definition HD</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719324521716-elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes.</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-logitech-speakers-driver-pack-for-optimal-performance-on-win-1078/"><u>Essential Logitech Speakers Driver Pack for Optimal Performance on Win 10/7/8</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-diagnose-and-correct-disk-read-errors/"><u>How to Diagnose and Correct Disk Read Errors</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-apple-iphone-14-pro-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to Apple iPhone 14 Pro iCloud Bypass</u></a></li>
<li><a href="https://extra-support.techidaily.com/prospective-videography-gear-ideal-for-future-4k-concert-videos-for-2024/"><u>Prospective Videography Gear Ideal for Future 4K Concert Videos for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/secure-your-precious-moments-leading-apps-for-iphone-photo-recovery/"><u>Secure Your Precious Moments: Leading Apps for iPhone Photo Recovery</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    