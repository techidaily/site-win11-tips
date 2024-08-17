---
title: "Preventing Data Theft: Controlling Removable Storage on PCs"
date: 2024-08-16T02:28:49.319Z
updated: 2024-08-17T02:28:49.319Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
excerpt: "This Article Describes Preventing Data Theft: Controlling Removable Storage on PCs"
keywords: Data Thievery Prevention,Secure Removable Storage,Control USB Devices,Protect Data Portals,Anti-Data Theft Tactics,Safe Media Handling,Limit External Drives
thumbnail: https://thmb.techidaily.com/c3ecdd732aca091f9e06be3caec567f3fcd17c056bf2dd14982465e8c7b5b6a1.jpg
---

## Preventing Data Theft: Controlling Removable Storage on PCs

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### Using the Local Group Policy Editor
![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
### Using the Registry Editor
![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-creating-popular-jujutsu-kaisen-tiktok-content/"><u>[New] Creating Popular Jujutsu Kaisen TikTok Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-beyond-the-numbers-narrative-the-impact-of-fake-likes/"><u>[New] In 2024, Beyond the Numbers Narrative  The Impact of Fake Likes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-maximize-impact-sharing-youtube-videos-on-social-media-fb/"><u>[New] Maximize Impact  Sharing YouTube Videos on Social Media (FB)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-quick-tips-for-nvidia-screen-capturing/"><u>[New] Quick Tips for NVIDIA Screen Capturing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-learn-how-to-build-youtube-backlinks-for-your-channel/"><u>[Updated] 2024 Approved  Learn How to Build YouTube Backlinks for Your Channel</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-optimizing-team-calls-prepost-meeting-screen-customization/"><u>[Updated] 2024 Approved  Optimizing Team Calls  Pre/Post-Meeting Screen Customization</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtube-income-101-from-ideas-to-earnings-in-action-for-2024/"><u>[Updated] YouTube Income 101  From Ideas to Earnings in Action for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-how-to-for-customizing-windows-11-with-widgets/"><u>A Comprehensive How-To for Customizing Windows 11 with Widgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-network-adapter-error-31-quickly/"><u>Addressing Windows Network Adapter Error 31 Quickly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoidance-and-remediation-for-a-frozen-resource-monitor-app-in-windows-11/"><u>Avoidance and Remediation for a Frozen Resource Monitor App in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ceasing-windows-notification-for-updates/"><u>Ceasing Windows Notification for Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Does Life360 Notify When You Log Out On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-canon-mf4500-driver/"><u>Download Canon MF4500 Driver</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-printer-busy-message-in-win11/"><u>Eliminating Printer Busy Message in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/email-marketing/"><u>Email Marketing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-insights-employing-law-filters-within-windows/"><u>Essential Insights: Employing LAW Filters Within Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-the-haste-of-edges-tabs-in-w11/"><u>Halt the Haste of Edge's Tabs in W11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-examine-excel-data-in-notepad/"><u>How to Examine Excel Data in Notepad</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-13-pro-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-strategies-against-locked-out-windows-pin/"><u>Immediate Strategies Against Locked-Out Windows PIN</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mental-matinee-best-general-knowledge-shows/"><u>In 2024, Mental Matinee  Best General Knowledge Shows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lowering-dropbox-cpu-utilization-on-windows-machines/"><u>Lowering Dropbox CPU Utilization on Windows Machines</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkmodesettingforwindowstexteditor/"><u>MasteringDarkModeSettingForWindowsTextEditor</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/microsoft-screen-recorder-download-and-use-guide/"><u>Microsoft Screen Recorder Download and Use Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-error-0x0000004e-in-windows-devices/"><u>Navigating Error 0X0000004E in Windows Devices</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-transforming-podcast-content-into-high-quality-mp3-audio-a-step-by-step-guide/"><u>New Transforming Podcast Content Into High-Quality MP3 Audio A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-account-security-changing-reset-counter-after-failed-logins/"><u>Optimizing Account Security: Changing Reset Counter After Failed Logins</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/original-tape-review-study-guide/"><u>Original Tape Review Study Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fix-for-ignoring-soon-expiring-licenses-alerts-in-windows/"><u>Quick Fix for Ignoring Soon Expiring Licenses Alerts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-this-pc-cant-run-post-windows-11-setup/"><u>Rectifying 'This PC Can't Run' Post-Windows 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-reactivating-ms-store-apps-in-windows-11/"><u>Regaining Access: Reactivating MS Store Apps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remediation-steps-for-windows-sandboxs-hypervisor-not-found/"><u>Remediation Steps for Windows Sandbox's Hypervisor Not Found</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-internal-errors-quickly-with-windows-rdp-connections/"><u>Resolving Internal Errors Quickly with Windows RDP Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/simplified-pubg-voice-alteration-guide-for-2024/"><u>Simplified PUBG Voice Alteration Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/simplified-speech-to-text-integration-into-visual-content-for-2024/"><u>Simplified Speech-to-Text Integration Into Visual Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-organization-in-windows-11/"><u>Simplifying File Organization in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-cant-get-mail-errors-windows-11-edition/"><u>Strategies to Overcome Can’t Get Mail Errors, Windows 11 Edition</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/top-10-insta-management-gadgets-for-boosting-engagement-for-2024/"><u>Top 10 Insta Management Gadgets for Boosting Engagement for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-8-cross-platform-tools-for-microsoft-enthusiasts/"><u>Top 8 Cross-Platform Tools for Microsoft Enthusiasts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleashing-windows-11-potential-via-powertoys-install/"><u>Unleashing Windows 11 Potential via PowerToys Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-volume-control-fix-guide/"><u>Windows 10/11 Volume Control Fix Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-history-hiccup-quick-fixes-in-3-steps/"><u>Windows History Hiccup - Quick Fixes in 3 Steps</u></a></li>
<li><a href="https://howto.techidaily.com/xiaomi-redmi-12-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Xiaomi Redmi 12 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
</ul></div>
