---
title: Troubleshooting Windows' Inaccessible File Permissions
date: 2024-12-20T06:37:28.275Z
updated: 2024-12-22T06:52:27.537Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows' Inaccessible File Permissions
excerpt: This Article Describes Troubleshooting Windows' Inaccessible File Permissions
keywords: Fix File Access Errors,Unlock Windows Files,Permission Troubleshoot,Resolve Permission Issues,Windows Access Challenges,Secure Inaccessible Files,Rectify Windows Permissions
thumbnail: https://thmb.techidaily.com/0825c5cfd1c9f8c60055aa627e174f35756a5c00a4e026b76fba822f7faa2ec3.jpg
---

## Troubleshooting Windows' Inaccessible File Permissions

 Did you encounter an error message when opening photos on an external hard drive? The message says "It looks like you don't have permission to view this file. Check the permissions and try again." The error implies that Windows Photos or File Explorer is not authorized to access this file.

 In this article, we explain how to fix this error, so you can view your photos again.

## Why Can't You View the File?

 You may encounter this error if your external hard drive is connected to a device without the right permissions settings. Other possible causes include user account control settings which restrict access to external drives, or a corrupted Windows Photos app.

 Now you know what causes this error, let's explore the solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Grant Full Control Permissions

 It looks like the main issue causing this error is that Windows doesn’t have sufficient permissions to access the file. To fix this, you must grant full control permissions to the account or user accessing the file. Here are the steps to follow:

1. Right-click on the folder and choose **Properties**.
2. In the Properties window, go to the **Security** tab.
3. Select the user account or group from the list and click **Edit**.
4. Under the **Permissions** section, check the box next to **Full Control**.  
![Grant Full Control Permissions to an user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/grant-full-control-permissions-to-an-user-account.jpg)
5. Click **Apply** and **OK** to save the changes.

 After making these changes, try viewing the photos again and checking if the error has been resolved.

## 2\. Take Ownership of the Folder

 If granting full control permissions does not work, take ownership of the folder to get more control. Taking ownership means you can manage, access, and delete files within it. Here's how to do it:

1. Right-click on the folder and select **Properties** from the context menu.
2. Switch to the **Security** tab, then click **Advanced** at the bottom.
3. In the Advanced Security Settings window, make sure you're on the **Permissions** tab.
4. Click on **Change** next to **Owner** in the top section.  
![Advanced Security Settings for Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-security-settings-for-folders.jpg)
5. In the dialog box, type **Everyone** and click **Check Names**.  
![Enter the object name to select user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enter-the-object-name-to-select-user.jpg)

1. If it seems correct, click **OK**.
2. Check the box next to **Replace owner on subcontainers and objects**.  
![Take Ownership of the Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/take-ownership-of-the-folder.jpg)
3. Now click Apply. A pop-up appears and asks you to confirm the ownership change.
4. Click **Yes** and wait for the process to finish.
5. Once done, click **OK** and close the window.

 After that, restart your computer and try accessing the folder.

## 3\. Reset the Photos App

 Another way to fix this error is to reset the Photos app. Resetting the app will delete all settings and cached data and restore it to its default state. Here’s how to reset the Photos app:

1. Press **Win + I** to open the Settings menu.
2. From the left pane, click **Apps** \> **Installed apps**.
3. Scroll down to find the **Microsoft Photos** app. You can also use the search bar to find it.  
![Microsoft Photos App in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/microsoft-photos-app-in-settings.jpg)
4. Click on the three dots and select **Advanced options**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Under the **Reset** section, click the **Reset** button.  
![Reset Microsoft Photos App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-microsoft-photos-app.jpg)
6. If a pop-up appears, click **Reset** again to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After that, try to open photos on your external hard drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Disable UAC Temporarily

 You may often find that you don’t have enough permissions to perform specific tasks. In such cases, [disabling UAC](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) may do the trick. So, disable it temporarily and see if it works.

## 5\. Run the Program Compatibility Troubleshooter

 If you're still encountering the error, try [running the Program Compatibility Troubleshooter](http://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/). This tool scans for compatibility issues with installed programs and solves them automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Open Files Without a Problem Again on Windows

 If you have the proper permissions, you should not encounter the "you don’t have permission to view this file” message. However, if you run into this issue, read this guide to resolve it quickly. Make sure you grant all permissions and take ownership of the folder.

 In this article, we explain how to fix this error, so you can view your photos again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-decoding-the-usefulness-what-does-fbs-blue-icon-mean/"><u>[New] In 2024, Decoding the Usefulness What Does FB’s Blue Icon Mean?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-introduction-to-moving-graphics-core-principles/"><u>[New] In 2024, Introduction to Moving Graphics Core Principles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-breakthrough-youtube-success-essential-tips-from-creator-studio-guide/"><u>[Updated] In 2024, Breakthrough YouTube Success Essential Tips From Creator Studio Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-d3d11-compatible-gpu-error-on-win11win10/"><u>Demystifying the D3D11-Compatible GPU Error on Win11/Win10</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-ultimate-5-ai-tool-assisted-prompt-engineering-applications/"><u>Discover the Ultimate 5 AI Tool Assisted Prompt Engineering Applications</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-huawei-nova-y71-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-picture-sequence-architect/"><u>In 2024, Ultimate Picture Sequence Architect</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-tecno-camon-20-premier-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Tecno Camon 20 Premier 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximize-your-blogging-revenue-with-ads-from-buyselladscom/"><u>Maximize Your Blogging Revenue with Ads From buySellAds.com</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-cpu-excesses-windows-resource-monitors-secrets-revealed/"><u>Navigating CPU Excesses: Windows Resource Monitor's Secrets Revealed</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-vintage-vs-modern-ranking-radio-sound-effects/"><u>New 2024 Approved Vintage Vs. Modern Ranking Radio Sound Effects</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaim-control-turn-around-windows-update-dilemmrancies/"><u>Reclaim Control: Turn Around Windows Update Dilemmrancies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rejuvenate-a-stalled-discord-overlay-in-windows/"><u>Steps to Rejuvenate a Stalled Discord Overlay in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-struggle-within-the-shadows-seeking-freedom-in-a-regulated-world/"><u>The Struggle Within the Shadows: Seeking Freedom in a Regulated World</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-3-fixes-to-regain-access-on-win1011s-dark-screens/"><u>Top 3 Fixes to Regain Access on Win10/11's Dark Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-fixing-your-non-functional-corsair-hs60-microphone/"><u>Troubleshooting Tips: Fixing Your Non-Functional Corsair HS60 Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/window-wise-stop-rounded-corner-style/"><u>Window Wise: Stop Rounded Corner Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-a-deep-dive-into-gpo-enforcement-per-user/"><u>Windows 10/11: A Deep Dive Into GPO Enforcement Per User</u></a></li>
</ul></div>

