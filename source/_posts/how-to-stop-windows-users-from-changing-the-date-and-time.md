---
title: How to Stop Windows Users From Changing the Date and Time
date: 2024-08-16T01:51:46.124Z
updated: 2024-08-17T01:51:46.124Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Stop Windows Users From Changing the Date and Time
excerpt: This Article Describes How to Stop Windows Users From Changing the Date and Time
keywords: Stopping DST Change on PCs,Prevent Windows Time Modification,Anti-TimeShift in Windows,Block Clock Adjustment WIN,Secure Windows Date Settings,Disable System Time Editing,Protect Windows Timestamps
thumbnail: https://thmb.techidaily.com/46bc9e67353768ac792e1534a64f3c2875130c736cfcb08614e4c3a629de687e.jpg
---

## How to Stop Windows Users From Changing the Date and Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-enhancing-classroom-learning-through-recorders/"><u>[New] 2024 Approved  Enhancing Classroom Learning Through Recorders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-visual-branding-in-small-business-marketing/"><u>[New] Visual Branding in Small Business Marketing</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-top-rated-8-android-tools-for-team-video-calls/"><u>[Updated] 2024 Approved  The Top-Rated 8 Android Tools for Team Video Calls</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-prepare-for-success-essential-trends-in-facebook-ads-24/"><u>[Updated] In 2024, Prepare for Success  Essential Trends in Facebook Ads '24</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-apps-to-increase-the-volume-beyond-100-percent-in-windows/"><u>4 Apps to Increase the Volume Beyond 100 Percent in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ace-win-hardware-testing-with-these-premier-graphics-tools/"><u>Ace Win Hardware Testing with These Premier Graphics Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-file-locks-turn-off-read-only-windows-mode/"><u>Altering File Locks: Turn Off Read-Only Windows Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-digital-snare-spotting-invisible-threats/"><u>Avoid the Digital Snare: Spotting Invisible Threats</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-saved-audio-configurations-winvolume-hacks/"><u>Bring Back Saved Audio Configurations: WinVolume Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/choosing-amongst-windows-n-versions-key-considerations/"><u>Choosing Amongst Windows N Versions: Key Considerations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-compatibility-with-windows-11-explained/"><u>Chrome Compatibility with Windows 11 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-os-synergy-creating-a-linux-vm-inside-windows-using-hyper-v/"><u>Cross-OS Synergy: Creating a Linux VM Inside Windows Using Hyper-V</u></a></li>
<li><a href="https://win11-tips.techidaily.com/curing-wont-start-spotify-on-windows-1011-platforms/"><u>Curing Won't Start Spotify on Windows 10/11 Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-code-effective-techniques-to-neutralize-wacatacbml/"><u>Deciphering the Code: Effective Techniques to Neutralize Wacatac.B!ml</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/discover-the-10-leading-free-video-call-apps-iosandroid-for-2024/"><u>Discover The 10 Leading Free Video Call Apps (iOS/Android) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-performance-new-tech-in-microsoft-teams/"><u>Enhancing Performance: New Tech in Microsoft Teams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-reminders-before-overhauling-your-windows/"><u>Essential Reminders Before Overhauling Your Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-strategies-for-winning-with-the-windows-11-bar/"><u>Essential Strategies for Winning with the Windows 11 Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-commands-learn-the-top-20-cmd-tricks/"><u>Essential Windows Commands: Learn the Top 20 CMD Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-for-installing-programs-despite-windows-admin-blocks/"><u>Guidelines for Installing Programs Despite Windows Admin Blocks</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-much-wealth-can-you-generate-on-youtube-using-cpm/"><u>How Much Wealth Can You Generate on YouTube Using CPM?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-motorola-g54-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Motorola G54 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leverage-larger-thumbnails-for-video-success-for-2024/"><u>Leverage Larger Thumbnails for Video Success for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-privacy-activating-controlled-folder-access-in-windows-11/"><u>Mastering Privacy: Activating Controlled Folder Access in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-onedrive-crashes-effortlessly/"><u>Navigate Through Windows OneDrive Crashes Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/notepad-woes-on-pc-7-steps-to-reopen-the-favorite-text-editor/"><u>Notepad Woes on PC: 7 Steps to Reopen the Favorite Text Editor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rebooting-lost-connectivity-winos-strategies/"><u>Rebooting Lost Connectivity: WinOS Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-and-render-vintage-videos-with-windows-madvr/"><u>Revamp and Render Vintage Videos with Windows MadVR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-the-malfunction-of-windows-delete-operation/"><u>Reversing the Malfunction of Windows Delete Operation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stay-alert-stay-up-the-top-5-ways-to-monitor-win11-uptime/"><u>Stay Alert, Stay Up: The Top 5 Ways to Monitor Win11 Uptime</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swashbucklers-overcome-delayed-gameplay-in-sw-bf2/"><u>Swift Swashbucklers: Overcome Delayed Gameplay in SW BF2</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-mac-toolkit-capturing-netflix-views/"><u>The Ultimate Mac Toolkit  Capturing Netflix Views</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triggering-printer-functionality-within-edge-guard/"><u>Triggering Printer Functionality Within Edge Guard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-preparedness-generate-boot-media-in-three-steps/"><u>Windows 11 Preparedness: Generate Boot Media in Three Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-playnite-integrating-virtual-game-archives/"><u>Winning Playnite: Integrating Virtual Game Archives</u></a></li>
</ul></div>
