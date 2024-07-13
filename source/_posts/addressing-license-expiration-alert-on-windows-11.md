---
title: Addressing 'License Expiration' Alert on Windows 11
date: 2024-07-12T17:18:58.648Z
updated: 2024-07-13T17:18:58.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing 'License Expiration' Alert on Windows 11
excerpt: This Article Describes Addressing 'License Expiration' Alert on Windows 11
keywords: Windows 11 License Warning,Renewal Alert Windows 11,Expiring Windows 11 License,Windows Upgrade Notification,Update Reminder,Extend Windows 11 Licensing,Windows 11 License Lifespan
thumbnail: https://thmb.techidaily.com/cfb0e1f2c6527b7d4431251ab8890078af21f0bc88406680edc99866453f0d22.jpg
---

## Addressing 'License Expiration' Alert on Windows 11

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.

## Why Does the “Your Windows License Will Expire Soon” Error Appear?

 The "Your Windows license will expire soon" error message can occur due to several factors, and here are the most prevalent ones:

* **Windows license is invalid:** Using an unauthorized or pirated version of Windows is one of the most common reasons why you might encounter this error message.
* **Hardware changes:** Performing hardware changes, such as replacing the motherboard in your system, can also lead to activation errors on Windows.
* **Connectivity issues:** Your computer might fail to connect to the Key Management Service (KMS) server due to network-related issues, resulting in activation errors.
* **Corrupt Activation Token files:** The **Tokens.dat** file contains the activation information for your Windows installation. If this file becomes inaccessible for some reason, you may encounter the “Your Windows license will expire soon” error on Windows.  
![Your Windows License Will Expire Soon Error on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/your-windows-license-will-expire-soon-error-on-windows.jpg)

 Now that you are aware of the common causes of this error, let's now focus on the potential solutions to resolve it.

## 1\. Apply Some Preliminary Fixes

 Before you try any advanced troubleshooting tips, it’s a good idea to start with some basic fixes.

* **Restart Windows Explorer:** Temporary issues with the Windows Explorer process can sometimes trigger the “Your Windows license will expire soon” error on your PC. If it’s nothing major, you should be able to fix it by simply [restarting the Windows Explorer process](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).
* **Run the SFC Scan:** It’s possible that Microsoft is having trouble authenticating your Windows license due to corrupt or damaged system files. To repair these files, you can try [running the System File Checker (SFC) scan on your PC](https://www.makeuseof.com/system-file-checker-sfc-windows/).
* **Scan for Malware:** Another potential factor contributing to Windows activation issues is malware infection. To address this, you can try [scanning your PC for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Microsoft Defender.

## 2\. Run the Activation Troubleshooter

 Both Windows 10 and 11 offer various troubleshooters for addressing common system issues. In this case, you can take help from the Windows Activation troubleshooter to fix any issues that may have caused the “Your Windows license will expire soon” error on your PC.

 To run the Activation troubleshooter, use these steps:

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Activation**.
3. Click the **Troubleshooter** button.  
![Running the Windows Activation Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/running-the-windows-activation-troubleshooter-1.jpg)

 Wait for the troubleshooter to do its thing, and then check if it resolves the error.

## 3\. Find Your Product Key and Activate Windows

 Another thing you can do to fix this error is to find your product key using the ShowKeyPlus app and then attempt to activate Windows again. Several users on the forums reported fixing the error with this method. You can also give it a go.

1. [Download the ShowKeyPlus app](https://www.microsoft.com/store/productId/9PKVZCPRX9NV) from the Microsoft Store.
2. Open the ShowKeyPlus app using the search menu.
3. Note down the **OEM key** in the **Home** tab.  
![ShowKeyPlus App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/showkeyplus-app-on-windows.jpg)
4. Press **Win + I** to open the Settings app.
5. In the **System** tab, click on **Activation**.
6. Click the **Change** button next to **Change product key**.
7. Enter the **OEM key** noted earlier and click **Next**.
8. Click the **Activate** button to confirm.  
![Update Product Key on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/update-product-key-on-windows.jpg)

## 4\. Activate Windows Using Command Prompt

 If you are unable to activate Windows via the Settings app, you can try to activate it through the Command Prompt. To do so, make sure that your PC is connected to the internet, and then use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **cmd** in the box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type **slmgr /ato** in the console and press Enter.  
![Activate Windows via Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/activate-windows-via-command-prompt.jpg)

 Wait for Command Prompt to validate your product key. You will see a message confirming the outcome of the activation process, whether it was successful or not. If the activation is successful, you should not see the “Your Windows license will expire soon” error after this.

## 5\. Rebuild the Tokens.dat File

 Tokens.dat is a system file related to Windows activation and licensing. If this file somehow gets corrupted, Windows may have trouble verifying the authenticity of your license and trouble you with the “Your Windows license will expire soon” error.

 You can try rebuilding the Tokens.dat file on your PC to see if that fixes the error. Here are the steps for the same.

1. Right-click on the **Start icon** or use the **Win + X** keyboard shortcut to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Type the following commands one by one and press **Enter** after each.  
`net stop sppsvc  
cd %windir%\system32\spp\store\2.0  
ren tokens.dat tokens.bar  
net start sppsvc  
cscript.exe %windir%\system32\slmgr.vbs /rilc`

 Restart your computer after running the above commands and then check if you still get the “Your Windows license will expire soon” error on your PC.

## 6\. Reset the Licensing Status

 In case your Windows license is not genuine, there's a workaround to dismiss the “Your Windows license will expire soon” message. This workaround involves resetting the activation period and [hiding the Activate Windows watermark](https://www.makeuseof.com/tag/remove-activate-windows-10-watermark/) via Command Prompt. Here are the steps you can follow.

1. [Open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **slmgr /rearm** in the console and press **Enter**.
3. Restart your PC after running the command.  
![Reset the Activation Timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-activation-timer.jpg)

 It's worth noting that you can only utilize the above command a few times. Eventually, you will have to obtain a genuine Windows license to eliminate the error message permanently.

## Fixing the “Your Windows License Will Expire Soon” Error on Windows

 Since Microsoft limits access to various personalization and security features on systems with inactivated Windows licenses, it’s vital to troubleshoot errors like the “Your Windows license will expire soon”. One of the above fixes should help you resolve the error message on your Windows computer. However, if nothing works, you can consider reaching out to Microsoft tech support as a last resort.

 Have you encountered the alarming "your Windows license will expire soon" error message on your PC? That usually happens when the Windows license on your PC is expired or deemed invalid. However, if your Windows license is indeed genuine, there might be another issue preventing Microsoft from authenticating it properly.

 In the following sections, we will discuss the common causes behind this error and provide potential solutions to fix it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-huawei-p60-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Huawei P60 Location | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-importance-of-secondary-footage-in-engaging-editors/"><u>[New] The Importance of Secondary Footage in Engaging Editors</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-creative-potential-access-free-sfx/"><u>In 2024, Unlock Creative Potential, Access Free SFX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-solve-0xc0000001-on-windows-os/"><u>Steps to Solve 0XC0000001 on Windows OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-accelerated-adventures-fastest-flash-games-on-devices/"><u>[New] Accelerated Adventures  Fastest Flash Games on Devices</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-lava-yuva-2-pro-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Lava Yuva 2 Pro Location | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-xiaomi-redmi-a2plus-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Xiaomi Redmi A2+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobe-reader-microsoft-store-approach/"><u>Unlocking Adobe Reader: Microsoft Store Approach</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-guide-to-modify-mouses-double-click-speed/"><u>Ultimate Guide to Modify Mouse's Double-Click Speed</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-hide-location-on-apple-iphone-11-pro-and-android-without-others-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, Hide location on Apple iPhone 11 Pro and Android without others knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-high-dpi-screen-resolution-problems-on-pcs/"><u>Tackling High DPI Screen Resolution Problems on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-tips-for-photoshopping-on-windows-11/"><u>Troubleshooting Tips for Photoshopping on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-audiences-on-the-move-tracker-apps/"><u>In 2024, Audiences on the Move Tracker Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-retrospective-on-the-goofy-movie-a-comprehensive-review/"><u>2024 Approved  Retrospective on 'The Goofy Movie'  A Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-power-of-network-configurations-in-windows-os/"><u>Unlock the Power of Network Configurations in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/triumph-over-windows-11-theme-lockdown-a-registry-approach/"><u>Triumph Over Windows 11 Theme Lockdown: A Registry Approach</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-ground-to-sky-expert-and-beginners-guide-to-editing-drones/"><u>In 2024, From Ground to Sky - Expert and Beginner's Guide to Editing Drones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-activate-folder-restrictions-in-windows/"><u>Step-by-Step Guide to Activate Folder Restrictions in Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unleash-your-creativity-the-best-animation-makers-for-beginners-and-pros-for-2024/"><u>New Unleash Your Creativity The Best Animation Makers for Beginners and Pros for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-motorola-g24-power-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Motorola G24 Power Pattern Lock Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safeguard-against-unexpected-scroll-behavior-in-os/"><u>Safeguard Against Unexpected Scroll Behavior in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-windows-11-speed-start-up-enhancement-techniques/"><u>Unleash Windows 11 Speed: Start-Up Enhancement Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-a-stuck-recycle-bin-on-microsofts-latest-os/"><u>Reviving a Stuck Recycle Bin on Microsoft's Latest OS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-is-it-legal-to-screen-record-youtube-videos/"><u>In 2024, Is It Legal to Screen Record YouTube Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesigning-the-user-experience-in-win11-settings/"><u>Redesigning the User Experience in Win11 Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-solutions-at-fingertips-customizing-shortcuts-for-win-11-repairs/"><u>Speedy Solutions at Fingertips: Customizing Shortcuts for Win 11 Repairs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-window-success-with-smart-key-purchasing-tactics/"><u>Unlocking Window Success with Smart Key Purchasing Tactics</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-automating-subtitles-for-social-media-visuals-on-instagram/"><u>In 2024, Automating Subtitles for Social Media Visuals on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-building-meme-foundations/"><u>[Updated] Expert Tips  Building Meme Foundations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-instructions-downloading-and-installing-msixbundle-packages/"><u>Step-by-Step Instructions: Downloading & Installing MSixbundle Packages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-a-frozen-xbox-app-in-windows-10/"><u>Unlocking a Frozen Xbox App in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-steps-to-resolve-onedrive-server-crashes/"><u>Swift Steps to Resolve OneDrive Server Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secret-to-a-cleaner-win11-experience/"><u>Unveiling the Secret to a Cleaner Win11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scrutinizing-the-utility-of-windows-11-interface-components/"><u>Scrutinizing the Utility of Windows 11 Interface Components</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-risks-in-windows-11-service-deactivation/"><u>Understanding Risks in Windows 11 Service Deactivation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regenerating-system-icons-in-windows-os/"><u>Regenerating System Icons in Windows OS</u></a></li>
</ul></div>
