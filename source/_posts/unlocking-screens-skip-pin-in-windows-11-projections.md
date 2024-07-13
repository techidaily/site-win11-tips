---
title: "Unlocking Screens: Skip PIN in Windows 11 Projections"
date: 2024-07-12T17:33:27.207Z
updated: 2024-07-13T17:33:27.207Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Screens: Skip PIN in Windows 11 Projections"
excerpt: "This Article Describes Unlocking Screens: Skip PIN in Windows 11 Projections"
keywords: Windows PIN-Free Project,Unlock Windows 11 Screen,Bypass Windows Lock,No PIN for Windows Projection,Skip PIN in Windows 11,Free Windows Screen Access,Eliminate Windows Pin Lock
thumbnail: https://thmb.techidaily.com/b2e6162c64c71916b12953aa4e598d6dbab13589e9351dbafbf801be610ecb70.jpg
---

## Unlocking Screens: Skip PIN in Windows 11 Projections

 Windows requires a PIN when projecting your computer onto another screen, such as a projector or a second monitor. Doing so prevents others from accessing your private information or projecting their content onto your computer.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

## 1\. Using Windows Settings

 Windows has a built-in app that allows you to change various settings. You can use this app to turn off the “require PIN for pairing” setting when projecting to your PC. Here’s how to do it:

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left sidebar, select the **System** tab.
3. Scroll down to the **Projecting to this PC** section and click on it.

 On the next page, look for the **Require a PIN for pairing** setting. Click on its drop-down menu, and you’ll see three options:

* **Never:** Never ask for a PIN for pairing when projecting to this PC.
* **First Time:** Require a PIN the first time you’re projecting to this PC.
* **Always:** Always requiring a PIN for pairing when projecting to this PC.

 Choose the **Never** option and exit the Settings window. The settings will be saved automatically, and you won’t need to enter a PIN when projecting your computer onto another display.

 If you don’t see **Require a PIN for pairing** in the **Projecting to this PC** section, the feature is disabled on your computer.

 To enable this feature, click on the **Optional features** link. You can also navigate to **Settings** \> **Apps** \> **Optional features** to access the same page. Doing so will open the optional features window.

![Add the Wireless Display optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-the-wireless-display-optional-feature.jpg)

 Click the **Add an optional feature** button and search for **Wireless Display**. You should see the Wireless Display feature listed in the search results. Check the box next to it and click **Next** \> **Install**.

![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-an-optional-feature.jpg)

 Once the feature is installed, return to the Projecting to this PC section in Settings. You should now see the “require a PIN for pairing” setting. Choose the **Never** option and close the window.

## 2\. Using the Group Policy Editor

 Another option is to use the Group Policy Editor. This method requires you to have a Pro or Enterprise Windows version. However, you can [activate the Group Policy Editor in Windows Home Edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Once you’ve done that, follow these steps to turn off the feature:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Group Policy Editor window.
3. From the left sidebar, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Connect​`
4. On the right side of the window, look for **Require pin for pairing** and double-click on it. Doing so will open the policy settings page.  
![Disable the Require pin for pairing policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-require-pin-for-pairing-policy.jpg)
5. Select the **Enabled** radio button and select **Never** from the drop-down menu.  
![Never Require Pin For Pairing in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-require-pin-for-pairing-in-gpe.jpg)
6. Click **Apply** \> **OK** to save the changes.

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

## 3\. Using the Registry Editor

 If you can’t access the Group Policy Editor, you can use the Registry Editor to disable the “Require PIN for Pairing” setting. This method involves editing the Windows registry, so [creating a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding is essential. That way, you can easily restore your computer if anything goes wrong.

 Once you’ve done that, follow these steps to turn off the feature:

1. Press the **Windows** key to open the Start menu.
2. Type **regedit** in the search bar and hit **Enter** to open the Registry Editor.
3. If the User Account Control window prompts, click **Yes** to give the program permission.
4. In the left sidebar, navigate to this path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect`
5. If you don’t see the Connect key at this location, right-click on Windows and select **New > Key**. Name it **Connect** and press **Enter**.
6. Now, right-click on Connect and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **RequirePinForPairing** and press **Enter**. Doing so will create a new DWORD in the registry.
8. Double-click on this newly created value to open its Properties window.  
![Tweak Registry to Disable Require PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/tweak-registry-to-disable-require-pin-for-pairing.jpg)
9. Set the **Value data** to **0** and click **OK** to save the changes.

 Once you've done that, exit the Registry Editor window and restart your computer. After restart, you won't need a PIN when projecting your computer onto another screen.

 To turn the feature back on, follow the same steps but set the **Value data** to **1**. This will enable the required PIN for pairing settings when projecting to a Windows 11 PC​​​​​.

## 4\. Using a REG File

 The fourth and final option is to use a REG file. This method is for those who have little or no experience with the Registry Editor. The REG file contains instructions that edit the Windows registry on your behalf. If you'd rather use this method, here’s what you need to do:

1. Right-click on Start and select **Run** from the menu.
2. Type **Notepad** in the text field and press **Enter**.
3. In the Notepad window, type or copy-paste the following code lines:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000001`
4. Click **File** and select **Save as** from the menu.
5. In the Save As window, click the **Save as type** drop-down menu and select **All files**.
6. Name the file **DisableRequirePin.reg** and select **Desktop** from the left sidebar.  
![Disable the Required PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-required-pin-for-pairing.jpg)
7. Now click **Save** and exit Notepad. You'll find the REG file on your desktop.
8. Double-click on it and select **Yes** when prompted. This will edit the registry on your behalf.

 Once done, restart your computer and the settings will be saved automatically. You won't need to enter a PIN when projecting your PC onto another screen.

 If you ever want to re-enable this feature, repeat the same steps as above and use this code in Notepad:

`<code>Windows Registry Editor Version 5.00  
  
[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000003`

 Save the file with the **EnableRequirePin.reg** filename and double-click on it to edit the registry.

 After that, restart your computer and the setting will be enabled. You'll now need to enter a PIN each time you project the PC onto another screen.

## Project to a Windows 11 PC Without Requiring a PIN

 Projecting your PC onto another display is a useful feature that allows you to mirror or extend your computer screen. Now you know how to do so without needing to enter your PIN every time.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/strategies-to-solve-pin-verification-issues-on-w11w10-pcs/"><u>Strategies to Solve PIN Verification Issues on W11/W10 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-order-in-windows-registry-through-repair-methods/"><u>Restoring Order in Windows Registry Through Repair Methods</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-recorders-unite-compete/"><u>[New] Recorders Unite, Compete</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/instant-media-transformation-enhance-fb-videos-to-hdmp4-on-the-fly/"><u>Instant Media Transformation  Enhance FB Videos to HD/MP4 on the Fly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-future-microsofts-copilot-key-and-windows-11-revolution/"><u>Navigating the Future: Microsoft's Copilot Key and Windows 11 Revolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mobile-file-access-via-windows-server/"><u>Mobile File Access via Windows Server</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-swift-upload-of-sizeable-videos-from-iphone-to-mac-desktop/"><u>[Updated] Swift Upload of Sizeable Videos From iPhone to Mac Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/should-you-block-yourphoneexe-on-home-editions/"><u>Should You Block YourPhone.exe on Home Editions?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-reactivate-the-default-folder-cooking-a-comprehensive-guide/"><u>Methods to Reactivate the Default Folder' Cooking: A Comprehensive Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-instagram-etiquette-ceasing-connections/"><u>[New] In 2024, Instagram Etiquette  Ceasing Connections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-amplify-your-audience-maximizing-youtube-viewership/"><u>[Updated] In 2024, Amplify Your Audience  Maximizing YouTube Viewership</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-usage-chronicles/"><u>Navigating Through Windows 11 Usage Chronicles</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-capture-and-save-your-next-google-meet-with-iphoneandroid/"><u>[New] 2024 Approved  Capture & Save  Your Next Google Meet with iPhone/Android</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-sniff-out-recent-unfollowers-on-instagram/"><u>In 2024, Sniff Out Recent Unfollowers on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-strategies-windows-voice-logging/"><u>Step-by-Step Strategies: Windows Voice Logging</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-basics-to-brilliance-elevating-your-windows-experience-via-ms-store/"><u>From Basics to Brilliance: Elevating Your Windows Experience via MS Store</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-web-portals-finding-perfect-alarm-sounds/"><u>[Updated] Top Web Portals  Finding Perfect Alarm Sounds</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/color-harmony-in-powerdirector-a-beginners-guide-to-clip-color-matching/"><u>Color Harmony in PowerDirector A Beginners Guide to Clip Color Matching</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-disconnection-dxgi-error-guide/"><u>Overcoming Device Disconnection: DXGI Error Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revising-the-start-page-to-a-new-preference-in-win11/"><u>Revising the Start Page to a New Preference in Win11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-halt-real-time-audiovideo-capturing-on-apples-platform/"><u>[Updated] 2024 Approved  Halt Real-Time Audio/Video Capturing on Apple's Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-eradicate-wows-fatal-issue-132-in-win-1011/"><u>Strategies to Eradicate WoW's Fatal Issue #132 in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stabilize-cease-persistent-file-explorer-opens/"><u>Stabilize: Cease Persistent File Explorer Opens</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-voiceover-techniques-for-tiktok-video-amplification/"><u>[Updated] Voiceover Techniques for TikTok Video Amplification</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-cinematic-brilliance-through-masterful-application-of-luts-from-cg-central/"><u>2024 Approved  Cinematic Brilliance Through Masterful Application of Luts From CG Central</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-crafting-a-memorable-tiktok-persona-pfp-insights-for-2024/"><u>[Updated] Crafting a Memorable TikTok Persona  PFP Insights for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-multitasking-enhancing-windows-11-widget-capabilities/"><u>Streamlining Multitasking: Enhancing Windows 11 Widget Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-app-experience-win11-color-automation/"><u>Tailoring Your App Experience: Win11 Color Automation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinventing-win11s-configuration-interface/"><u>Reinventing Win11's Configuration Interface</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-personal-content-management-building-a-structured-watch-later-list/"><u>In 2024, Mastering Personal Content Management  Building a Structured 'Watch Later' List</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-enhancing-visual-presentation-before-and-after-team-calls/"><u>[New] 2024 Approved  Enhancing Visual Presentation Before & After Team Calls</u></a></li>
<li><a href="https://techidaily.com/vivo-y36-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Vivo Y36 Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-windows-from-tracking-your-apps/"><u>Stop Windows From Tracking Your Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-vmware-crashes-a-guide-for-win11-users/"><u>Overcoming VMware Crashes: A Guide for Win11 Users</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-google-pixel-8-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Google Pixel 8 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/crafting-compelling-cinematography-3-novel-approaches-to-weave-sound-into-video-projects-for-2024/"><u>Crafting Compelling Cinematography 3 Novel Approaches to Weave Sound Into Video Projects for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/find-the-most-effective-strategy-to-learn-finnish-online/"><u>Find the Most Effective Strategy to Learn Finnish Online</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-disabled-gpu-settings-on-windows-devices-win1011/"><u>Fixing Disabled GPU Settings on Windows Devices (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-reskin-windows-11-for-a-nostalgic-windows-98-look/"><u>How to Completely Reskin Windows 11 for a Nostalgic Windows 98 Look</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-lava-yuva-2-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Lava Yuva 2.</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-freedomfrexpressor-the-ultimate-2024-audio-extractor-guide/"><u>[Updated] FreedomFreXpressor  The Ultimate 2024 Audio Extractor Guide</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unbeatable-gaming-intro-creations-the-best/"><u>Unbeatable Gaming Intro Creations The Best</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-the-prosperous-path-share-tiktok-via-twitter/"><u>[Updated] 2024 Approved  The Prosperous Path  Share TikTok via Twitter</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-motorola-moto-g24-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Motorola Moto G24</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-guide-on-how-to-remove-apple-id-from-apple-iphone-x-by-drfone-ios/"><u>In 2024, Guide on How To Remove Apple ID From Apple iPhone X</u></a></li>
</ul></div>
