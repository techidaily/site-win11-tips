---
title: Prevent Windows From Tracing New Program Starts
date: 2024-12-04T19:24:55.054Z
updated: 2024-12-06T22:22:18.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prevent Windows From Tracing New Program Starts
excerpt: This Article Describes Prevent Windows From Tracing New Program Starts
keywords: Block Program Tracking in Windows,Hide Startup Apps Execution Trace,Disable Windows Logon Events,Stop New Program Alerts on PC,Prevent Windows System Notifications,Secure Program Launch Privacy,Eliminate Program Trigger Messages
thumbnail: https://thmb.techidaily.com/8efb02d1ad78746fe7e04d066e97a30754c0040bd1d393f4b6d528ffbc9df6b1.jpg
---

## Prevent Windows From Tracing New Program Starts

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/updated-step-by-step-livestreaming-to-facebook-from-iphonestablets/"><u>[Updated] Step-by-Step Livestreaming to Facebook From iPhones/Tablets</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-quick-and-easy-how-to-transform-your-mobile-device-into-a-vr-headset/"><u>2024 Approved Quick and Easy How to Transform Your Mobile Device Into a VR Headset</u></a></li>
<li><a href="https://techtrends.techidaily.com/dragon-quest-continuum-arranging-the-how-to-train-your-dragon-movies-for-full-story/"><u>Dragon Quest Continuum: Arranging the How To Train Your Dragon Movies for Full Story</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensure-seamless-connectivity-9-tips-to-unlock-usb-wi-fi-on-pcs/"><u>Ensure Seamless Connectivity: 9 Tips to Unlock USB Wi-Fi on PCs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-enroll-in-chatgpt-plugin-upgrades-now/"><u>How to Enroll in ChatGPT Plugin Upgrades Now!</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723007065050-how-to-stop-frostpunk-crashes-expert-tips-and-solutions-inside/"><u>How To Stop Frostpunk Crashes: Expert Tips and Solutions Inside</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-realme-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-terminal-for-quake-users/"><u>Mastering Windows Terminal for Quake Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-pin-lockouts-effective-methods/"><u>Overcoming Windows PIN Lockouts: Effective Methods</u></a></li>
<li><a href="https://win-news.techidaily.com/premium-angular-admin-framework-now-ui-pro-enhanced-bootstrap-templates-for-developers-created-by-creative-tim/"><u>Premium Angular Admin Framework Now UI PRO: Enhanced Bootstrap Templates for Developers | Created by Creative Tim</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-to-restoring-erratic-windows-software/"><u>Quick Guide to Restoring Erratic Windows Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-gameplay-addressing-windows-boltgun-stutters/"><u>Streamline Your Gameplay: Addressing Window's Boltgun Stutters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-route-for-installing-java-development-kit-on-windows-11/"><u>The Ultimate Route for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-nubia-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Nubia .</u></a></li>
</ul></div>

