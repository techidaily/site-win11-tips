---
title: Reinstating Functional Wastebin Icon in Windows 11
date: 2024-08-08T11:08:39.298Z
updated: 2024-08-09T11:08:39.298Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Functional Wastebin Icon in Windows 11
excerpt: This Article Describes Reinstating Functional Wastebin Icon in Windows 11
keywords: Wastebins Redesign,Bin Icon Update,Windows 11 Icon Fix,Restoring Waste Icon,New Window Icon,11 Bin Icon Revamp,Functional Trash Icon
thumbnail: https://thmb.techidaily.com/8ff604b1994b08eb94688e168989c0566c68ac5579a7ef54ad52cac70e587e21.jpg
---

## Reinstating Functional Wastebin Icon in Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

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
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-awesome-igtv-channels-that-deliver-quality-content/"><u>[New] 2024 Approved  Awesome IGTV Channels That Deliver Quality Content</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-navigating-youtube-submission-a-filmmakers-guide-to-360-video/"><u>[New] 2024 Approved  Navigating YouTube Submission  A Filmmaker's Guide to 360 Video</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-avi-visionary-player-compatible-with-pcmobile/"><u>[New] Avi Visionary Player  Compatible with PC/Mobile</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-boost-your-game-presence-with-free-voice-alteration-tips-for-free-fire/"><u>[New] Boost Your Game Presence with Free Voice Alteration Tips for Free Fire</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-conquer-any-gadget-to-record-your-youtube-live-experience-for-2024/"><u>[New] Conquer Any Gadget to Record Your YouTube Live Experience for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-cutting-the-clutter-stopping-instagram-followers-for-2024/"><u>[New] Cutting the Clutter  Stopping Instagram Followers for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-dynamic-subtitle-artisan/"><u>[New] Dynamic Subtitle Artisan</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-copyright-concern-unscheduled-video-displacement/"><u>[New] In 2024, Copyright Concern  Unscheduled Video Displacement</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-effortless-techniques-for-saving-youtube-videos/"><u>[New] In 2024, Effortless Techniques for Saving YouTube Videos</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-the-development-and-application-of-vr-shopping-for-2024/"><u>[New] The Development and Application of VR Shopping for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-mastering-audio-and-visual-quality-in-youtube-videos/"><u>[Updated] 2024 Approved  Mastering Audio & Visual Quality in YouTube Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-the-pros-way-of-recording-movs-effectively-on-windows-10/"><u>[Updated] 2024 Approved  The Pro's Way of Recording MOVs Effectively on Windows 10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-boosting-traffic-elevating-your-pages-popularity-metric/"><u>[Updated] Boosting Traffic  Elevating Your Page's Popularity Metric</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-essential-guide-to-producing-quality-igtv-on-smartphonesdslrs-for-2024/"><u>[Updated] Essential Guide to Producing Quality IGTV on Smartphones/DSLRs for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-venture-beyond-reality-with-our-top-1-cookies-in-mobile-vr-technology/"><u>[Updated] Venture Beyond Reality with Our Top 1 Cookies in Mobile VR Technology</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-vidextracter-facebook-streams/"><u>[Updated] VidExtracter  Facebook Streams</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/11-ultimate-phantom-4-accessories-to-purchase-for-2024/"><u>11 Ultimate Phantom 4 Accessories to Purchase for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/13-tips-to-fix-windows-system-restore/"><u>13 Tips to Fix Windows System Restore</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-12-live-views-at-your-fingertips/"><u>2024 Approved  Exclusive 12 Live Views at Your Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-quick-ways-to-disable-usb-selective-suspend-in-windows-11/"><u>3 Quick Ways to Disable USB Selective Suspend in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-ways-to-clear-the-microsoft-defender-protection-history-on-windows-10-and-11/"><u>4 Ways to Clear the Microsoft Defender Protection History on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-alternative-protection-strategies-for-missing-bitlocker-in-winoss/"><u>5 Alternative Protection Strategies for Missing Bitlocker in WinOSs</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-honor-play-7t-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Honor Play 7T to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-checksum-error-in-winrar/"><u>6 Ways to Fix the Checksum Error in WinRAR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-easy-tips-for-memo-making-in-windows/"><u>7 Easy Tips for Memo-Making in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-routes-to-rescue-your-stream-with-a-fixed-obs-link-on-windows/"><u>7 Routes to Rescue Your Stream with a Fixed OBS Link on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-slick-techniques-to-launch-iis-manager/"><u>8 Slick Techniques to Launch IIS Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-compre-cookie-cutter-guide-to-revamping-your-pc-with-a-fresh-os/"><u>A Compre Cookie-Cutter Guide to Revamping Your PC with a Fresh OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-tutorial-on-windows-1011s-audio-upgrade/"><u>A Comprehensive Tutorial on Windows 10/11'S Audio Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-precise-walkthrough-for-windows-update-resetting/"><u>A Precise Walkthrough for Windows Update Resetting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-secrets-the-fastest-ways-to-uncover-windows-11s-credential-manager/"><u>Accessing Secrets: The Fastest Ways to Uncover Windows 11'S Credential Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-digital-dreamland-with-windows-pcs/"><u>Achieving Digital Dreamland with Windows PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-windows-11-and-parallels-confluence-in-macos/"><u>Achieving Windows 11 and Parallels Confluence in MacOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-discrepancies-in-disk-based-discord-queries/"><u>Addressing Discrepancies in Disk-Based Discord Queries</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-issues-with-googles-nearby-sharing-on-desktop-pc/"><u>Addressing Issues with Google's Nearby Sharing on Desktop PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-operative-brightness-fn-button-on-windows-11/"><u>Addressing Non-Operative Brightness Fn Button on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-winrars-summation-anomalies-with-six-fixes/"><u>Addressing WinRAR's Summation Anomalies with Six Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-10-and-11s-phishing-protection-settings/"><u>Adjusting Windows 10 & 11'S Phishing Protection Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adopt-a-streamlined-approach-to-input-customization/"><u>Adopt a Streamlined Approach to Input Customization</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-tips-for-docx-to-pdf-conversion-on-modern-windows/"><u>Advanced Tips for Docx-to-PDF Conversion on Modern Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-windows-tactics-for-hardware-id-retrieval/"><u>Advanced Windows Tactics for Hardware ID Retrieval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-generated-windows-keys-unveiling-potential-perils/"><u>AI-Generated Windows Keys: Unveiling Potential Perils</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altwindirstat-strategies-for-effective-disk-space-management/"><u>AltWinDirStat Strategies for Effective Disk Space Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artificial-intelligence-windows-future-trailblazer/"><u>Artificial Intelligence: Windows' Future Trailblazer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/assisting-with-utorrent-download-stalls-in-microsoft-environments/"><u>Assisting with uTorrent Download Stalls in Microsoft Environments</u></a></li>
<li><a href="https://win11-tips.techidaily.com/awaken-your-device-finding-and-fixing-muted-speaker-issues/"><u>Awaken Your Device – Finding & Fixing Muted Speaker Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/balancing-act-keeping-high-vitality-in-check-on-windows/"><u>Balancing Act: Keeping High Vitality in Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-bug-fixing-frequent-apex-legends-crashes-on-windows-11/"><u>Beating the Bug: Fixing Frequent Apex Legends Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-practices-unveiled-supercharge-wsl-2-with-windows-dev-tools/"><u>Best Practices Unveiled: Supercharge WSL 2 with Windows Dev Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beyond-boundaries-artificinas-intelligence-in-windows-11/"><u>Beyond Boundaries: Artificinas Intelligence in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/blueprints-for-crafting-safe-dialog-box-for-hardware-disconnect/"><u>Blueprints for Crafting Safe Dialog Box for Hardware Disconnect</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719278811623-bypassing-chrome-block-strategies-for-w11-users/"><u>Bypassing Chrome Block: Strategies for W11 Users.</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevate-user-interface-with-aesthetic-windows-11-backdrops/"><u>Elevate User Interface with Aesthetic Windows 11 Backdrops</u></a></li>
<li><a href="https://fox-access.techidaily.com/expert-picks-of-top-fee-free-live-streaming-tech-tools-for-everyone/"><u>Expert Picks of Top, Fee-Free Live Streaming Tech Tools for Everyone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-honor-100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Honor 100 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fly-higher-10-must-have-uav-extras-revealed-for-2024/"><u>Fly Higher  10 Must-Have UAV Extras Revealed for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-motorola-moto-g84-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Motorola Moto G84 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-pivot-and-post-mastering-video-orientation/"><u>In 2024, Pivot and Post  Mastering Video Orientation</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-cost-effective-camera-guidebook/"><u>In 2024, The Cost-Effective Camera Guidebook</u></a></li>
<li><a href="https://apple-account.techidaily.com/removing-device-from-apple-id-for-your-iphone-8-by-drfone-ios/"><u>Removing Device From Apple ID For your iPhone 8</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/speed-up-your-storytelling-mastering-time-lapses-in-final-cut-pro-for-2024/"><u>Speed Up Your Storytelling Mastering Time Lapses in Final Cut Pro for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/standing-out-strategies-for-top-users-on-snapchat-for-2024/"><u>Standing Out  Strategies for Top Users on Snapchat for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719266023156-zero-cost-local-gpt-clones-gpt4alls-window-solution/"><u>Zero-Cost Local GPT Clones: GPT4All's Window Solution.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>