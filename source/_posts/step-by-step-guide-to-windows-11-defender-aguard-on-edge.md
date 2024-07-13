---
title: Step-by-Step Guide to Windows 11 Defender Aguard on Edge
date: 2024-07-12T17:30:13.566Z
updated: 2024-07-13T17:30:13.566Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Windows 11 Defender Aguard on Edge
excerpt: This Article Describes Step-by-Step Guide to Windows 11 Defender Aguard on Edge
keywords: Windows 11 Defender Basics,Guarding Edge with WID,Securing PCs,Edge Security Guide,Antivirus on Windows 11,Edge Protection Setup,Learn WID for Edge
thumbnail: https://thmb.techidaily.com/8dc40963abf93641fc12fb3ff0b8fa0a43902050db781f6bcdf9e50e7619aa67.jpg
---

## Step-by-Step Guide to Windows 11 Defender Aguard on Edge

 If you work in an environment that deals with sensitive data, then you must install Microsoft Defender Application Guard for Edge on your Windows computer. It opens Microsoft Edge in an isolated container so that suspicious or potentially harmful files will not be able to access trusted resources.

 In this guide, we will show you different methods to install Microsoft Defender Application Guard for Edge on your Windows 11 PC.

## 1\. How to Install Microsoft Defender Application Guard Using Windows Settings

 Installing Microsoft Defender Application Guard for Edge on your Windows PC is a quick and simple process. You just need to access the Windows Settings app, and then follow a few steps to enable the feature. Here's how to do it:

1. Press**Win + I** on your keyboard to open the Settings app. See our guide if you're [having trouble opening Windows Settings](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/) .
2. On the left, click**Privacy and security** , and then on the right, click**Windows Security** .
3. Under the Protection areas, click**App & browser control** .
4. Then, on the Windows Security page, click the**Install Microsoft Defender Application Guard** link below Isolated browsing.  
![How to Install Microsoft Defender Application Guard Using Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/how-to-install-microsoft-defender-application-guard-using-windows-security.jpg)
5. If you see the UAC prompt on your computer screen, click Yes to confirm your action.
6. Next, check the box next to**Microsoft Defender Application Guard** and click**OK** .  
![Add Microsoft Defender Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-microsoft-defender-application-guard-for-edge.jpg)

 Once you perform the above steps, you must need to restart your computer to finish installing the requested changes. This way you can install the feature on your computer.

 If you have already installed Microsoft Defender Application Guard and want to uninstall it, the process is quite easy. All you need to do is follow the steps mentioned above until you reach the Windows Security page.

![Uninstall Microsoft Defender Application Guard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-defender-application-guard.jpg)

 Then click**Uninstall Microsoft Defender Application Guard** and uncheck the box next to**Microsoft Defender Application Guard** .

## 2\. How to Install Microsoft Defender Application Guard Using the Control Panel

 You can also install Microsoft Defender Application Guard for Edge on your Windows 11 computer using the classic Control Panel. Here's how to do it:

1. Search for**Control Panel** in the Start menu and open it.
2. Select**Programs and Features** from the menu items.
3. From the left pane, click**Turn Windows features on or off** .
4. Tick the box next to**Microsoft Defender Application Guard** and click**OK** .
5. Then restart your computer for the changes to take effect.

 In order to uninstall it, follow the same steps and uncheck the box next to**Microsoft Defender Application Guard** . Then click OK and reboot your computer to save the changes.

## 3\. How to Install Microsoft Defender Application Guard Using Local Group Policy Editor

 Another method to install Microsoft Defender Application Guard is through the Local Group Policy Editor. This method requires some advanced knowledge and might be challenging for some users but don't worry; if you follow the steps, you'll be okay.

 You'll also find that if you're on Windows Home, the below instructions won't work. This is because it's not enabled by default on Home. Fortunately, you can learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before you perform this fix.

 Follow the steps given below to install Microsoft Defender Application Guard using Local Group Policy Editor:

1. Press the**Win + R** shortcut key to launch the Run window.
2. Type**gpedit.msc** in the dialog box and press Enter or click**OK** .
3. In the Local Group Policy Editor window, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Microsoft Defender Application Guard`
4. Now go to the right pane and double-click on the **Turn On Microsoft Defender Application Guard in Managed Mode** policy.  
![Microsoft Defender Application Guard Using Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-defender-application-guard-using-local-group-policy-editor.jpg)
5. This will open a new window, select the**Enabled** checkbox.
6. You can now go to**Options** and change it to**2** or**3** .  
![Turn on Microsoft Defender Application Guard in Managed Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turn-on-microsoft-defender-application-guard-in-managed-mode.jpg)
7. Once done, click**Apply** and then**OK** to save all the changes you have made.

 Now restart your computer and Microsoft Defender Application Guard will be installed on your PC.

## 4\. How to Install Microsoft Defender Application Guard Using Command Prompt

 If you are comfortable with the command prompt, you can also install Microsoft Defender Application Guard using the Command Prompt. Follow the steps here:

1. Right-click on Start and select**Run** from the menu list.
2. In the dialog box, type**cmd** and then press**Ctrl + Shift + Enter** on your keyboard.
3. If UAC prompts, click**Yes** to run the command prompt with admin access.
4. In the elevated command prompt window, type the following command and hit Enter:  
`Dism /online /Enable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`
5. When Command Prompt asks you to restart, type**Y** and hit Enter to complete this operation.

 Once you restart your computer, Microsoft Defender Application Guard will be installed and ready to use. In case you want to uninstall the Application Guard, you can do so by using the same command prompt steps. Just make sure to run the following command instead:

`Dism /online /Disable-Feature /FeatureName:"Windows-Defender-ApplicationGuard"​`

 At this point, you may be asked to restart your computer. To proceed, type**Y** and press Enter. After restarting, you will have successfully installed Microsoft Defender Application Guard on your system.

## 5\. How to Install Microsoft Defender Application Guard Using Windows PowerShell

 Alternatively, you can use Windows PowerShell to install Microsoft Defender Application Guard for Edge on Windows 11\. This is also a command-line process but is different from the Command Prompt application. Follow these steps to install Microsoft Defender Application Guard using Windows PowerShell:

1. Open Windows PowerShell with admin access. If you need help, see our guide on [how to open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Once you're in the PowerShell window, type the following command:  
`Enable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`
3. Now press**Enter** on your keyboard to execute it.
4. When PowerShell asks you to restart your computer, type**Y** and hit Enter.

 Upon restarting the computer, you will have successfully installed Microsoft Defender Application Guard on your system. Now you can make sure that you are browsing in a secure and protected environment.

 If you ever want to uninstall Microsoft Defender Application Guard, you can do so by using the same PowerShell command. Just make sure to use**Disable** \-WindowsOptionalFeature instead of**Enable** . So, this way the command should look like this:

`Disable-WindowsOptionalFeature -Online -FeatureName "Windows-Defender-ApplicationGuard"​`

 Now press Enter on your keyboard to execute the command and restart your system. Once it is done, Microsoft Defender Application Guard will be uninstalled from your PC.

 This is how you can install and uninstall Microsoft Defender Application Guard using Windows PowerShell on Windows 11.

## Get Microsoft Defender Application Guard and Stay Safe

 Microsoft Defender Application Guard uses isolated secure containers to protect your device from malicious files and threats. In the above-described methods, you can follow the installation steps and remain safe while browsing the web.


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
<li><a href="https://facebook-video-recording.techidaily.com/new-8-free-and-online-facebook-link-downloaders-for-2024/"><u>[New] 8 Free And Online Facebook Link Downloaders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidance-on-resolving-windows-software-initiation-flaw-error/"><u>Guidance on Resolving Windows Software Initiation Flaw (Error)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-enhance-your-feed-top-15-instagram-free-safe-following-aids/"><u>[New] In 2024, Enhance Your Feed  Top 15 Instagram Free, Safe Following Aids</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-honor-x9b-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Honor X9b Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-industry-standards-prime-gimbals-for-drones/"><u>In 2024, Industry Standards  Prime Gimbals for Drones</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-infinix-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Infinix</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-constructing-captivating-youtube-music-selections/"><u>[Updated] In 2024, Constructing Captivating YouTube Music Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-1011-permanent-file-disposal-via-custom-trash-bin-setup/"><u>Windows 10/11: Permanent File Disposal via Custom Trash Bin Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/icon-position-correction-made-simple/"><u>Icon Position Correction Made Simple</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-top-10-ultra-quality-tiktok-videos-clear-and-free-download/"><u>[New] In 2024, Top 10  Ultra-Quality TikTok Videos - Clear & Free Download</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-get-organized-timely-social-media-engagement-on-fb-no-cost/"><u>In 2024, Get Organized  Timely Social Media Engagement on FB (No Cost)</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-navigating-the-ins-and-outs-of-aiseesofts-screencast-functionality/"><u>[New] Navigating the Ins and Outs of Aiseesoft's Screencast Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-to-customize-windows-11s-search-via-settings/"><u>5 Ways to Customize Windows 11'S Search via Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instructions-to-bring-back-old-school-search-in-windows-11/"><u>Instructions to Bring Back Old-School Search in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breakthrough-programs-facilitating-switch-from-mac-to-windows/"><u>Breakthrough Programs Facilitating Switch From MAC to WINDOWS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-360-degree-videos-secure-youtube-uploads/"><u>2024 Approved  Mastering 360-Degree Videos  Secure YouTube Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-hacks-for-instantaneous-iis-server-management-entry/"><u>8 Hacks for Instantaneous IIS Server Management Entry</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-broad-overview-delving-into-google-podcasts-application/"><u>In 2024, Broad Overview  Delving Into Google Podcasts Application</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-print-bridge-trouble-shooting-guide/"><u>Windows Print Bridge: Trouble Shooting Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-comparison-dissecting-key-differences-between-local-and-microsoft-logins-in-os/"><u>In-Depth Comparison: Dissecting Key Differences Between Local & Microsoft Logins in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-function-keys-actions-on-windows-1011/"><u>Adjusting Function Keys' Actions on Windows 10/11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/sh-potential-access-premium-sound-effects-for-2024/"><u>Unleash Potential  Access Premium Sound Effects for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/explore-the-best-of-both-worlds-with-these-5-cams/"><u>Explore the Best of Both Worlds with These 5 Cams</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-the-most-effective-win-video-codecs/"><u>Demystifying the Most Effective Win Video Codecs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-different-ways-to-tailor-windows-11-search/"><u>Explore Different Ways to Tailor Windows 11 Search</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-create-a-brand-video-to-make-your-business-shine/"><u>In 2024, Create a Brand Video to Make Your Business Shine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-basics-to-brilliance-elevating-your-windows-experience-via-ms-store/"><u>From Basics to Brilliance: Elevating Your Windows Experience via MS Store</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-your-youtube-presence-filmmaking-with-filmora/"><u>2024 Approved  Elevate Your YouTube Presence  Filmmaking with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719380879608-speedy-outlook-on-windows-heres-how/"><u>Speedy Outlook on Windows? Here's How!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-writing-game-wins-finest-tools/"><u>Elevate Your Writing Game – Win's Finest Tools</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ehind-the-scenes-filmmaking-tips-from-youtube-experts-for-2024/"><u>[New] Behind-the-Scenes Filmmaking Tips From YouTube Experts for 2024</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-hardware-drivers-with-windows-device-manager-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your hardware drivers with Windows Device Manager on Windows 11 & 10 & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxvk-transforming-windows-gaming-experience-for-the-better/"><u>DXVK: Transforming Windows Gaming Experience for the Better</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-mastering-your-media-10-premier-recorder-software-for-2024/"><u>[New] Mastering Your Media  10 Premier Recorder Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-streamline-note-taking-with-win-11-display-rules/"><u>How to Streamline Note-Taking with Win 11 Display Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adding-items-to-windows-11-desktop-menu-hierarchy/"><u>Adding Items to Windows 11 Desktop Menu Hierarchy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-completely-reskin-windows-11-for-a-nostalgic-windows-98-look/"><u>How to Completely Reskin Windows 11 for a Nostalgic Windows 98 Look</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-windows-component-services-interface-quickly/"><u>Accessing Windows' Component Services Interface Quickly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-use-frame-blending-in-premiere-pro/"><u>How to Use Frame Blending in Premiere Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-system-ready-for-windows-11-with-our-top-3-usb-tips/"><u>Get Your System Ready for Windows 11 with Our Top 3 USB Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-immediate-folder-upload-tackling-onedrive-errors/"><u>Mastering Immediate Folder Upload: Tackling OneDrive Errors</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-smart-guide-to-procuring-premium-image-banners/"><u>In 2024, The Smart Guide to Procuring Premium Image Banners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winfixing-comprehensive-steps-for-repairing-windows-filesystem-issues/"><u>Winfixing: Comprehensive Steps for Repairing Windows Filesystem Issues</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-honor-play-40c-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Honor Play 40C Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capturing-every-victory-pro-gaming-tips-for-w11-users-for-2024/"><u>[New] Capturing Every Victory  Pro Gaming Tips for W11 Users for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-to-apple-iphone-6-plus-drfone-by-drfone-ios/"><u>In 2024, How to Mirror PC to Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-guide-to-enhancing-performance-in-your-new-windows-11-setup/"><u>A Quick Guide to Enhancing Performance in Your New Windows 11 Setup</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-illuminate-your-gaming-recordings-avoid-black-screens-with-obs/"><u>[Updated] 2024 Approved  Illuminate Your Gaming Recordings  Avoid Black Screens with OBS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-uncover-and-attend-to-hidden-storage/"><u>How to Uncover and Attend to Hidden Storage?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangling-stacked-icons-on-operating-system-ui/"><u>Disentangling Stacked Icons on Operating System UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-lightweight-browsers-for-chromeoswindowsmacos-ram-and-cpu-wise/"><u>Finding Lightweight Browsers for ChromeOS/Windows/macOS: RAM & CPU-Wise</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-ultimate-guide-to-constructing-mc-neighborhoods/"><u>2024 Approved  The Ultimate Guide to Constructing MC Neighborhoods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-start-wordpad-in-a-windows-desktop/"><u>How to Start WordPad in a Windows Desktop</u></a></li>
</ul></div>
