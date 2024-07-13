---
title: The Complete Walkthrough for Finding Windows Keys Losses
date: 2024-07-12T17:37:34.988Z
updated: 2024-07-13T17:37:34.988Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Complete Walkthrough for Finding Windows Keys Losses
excerpt: This Article Describes The Complete Walkthrough for Finding Windows Keys Losses
keywords: Lost Windows Key Repair Guide,Reverse Windows Product Code Hacking,Restore Missing Windows ID,Troubleshoot Forgotten Windows Logo,Recover Lost Windows Registry,Unlock Deactivated Windows Account,Solve Keyboard No Signal Error
thumbnail: https://thmb.techidaily.com/669bc1413d235f8908afbf69f357ad5578fda1c3066e7cdb610eb41a93c8a8ff.jpeg
---

## The Complete Walkthrough for Finding Windows Keys Losses

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt
![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell
![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key
![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  
![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/windows-audio-test-failure-immediate-action-plan/"><u>Windows Audio Test Failure: Immediate Action Plan</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-arp-cache-how-to-empty-it/"><u>Decoding Windows ARP Cache: How to Empty It?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tips-for-seamlessly-screening-instagram-stories-for-2024/"><u>[New] Tips for Seamlessly Screening Instagram Stories for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-on-windows-11-sound-settings-navigation/"><u>A Quick Walkthrough on Windows 11 Sound Settings Navigation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-visuals-applying-microsoft-store-themes-in-windows/"><u>Reimagining Visuals: Applying Microsoft Store Themes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-causes-behind-usb-attachment-failure-in-virtualbox/"><u>Unraveling the Causes Behind 'USB Attachment Failure' In VirtualBox</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-locate-lively-youtube-conversations/"><u>In 2024, Locate Lively YouTube Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-windows-11-account-settings-center/"><u>Finding Windows 11 Account Settings Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-9-analytical-points-showcasing-pcs-edge-over-macs/"><u>Top 9 Analytical Points Showcasing PC's Edge Over Macs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dxgidll-missing-heres-how-win11-can-help/"><u>Dxgi.dll Missing? Here's How Win11 Can Help</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-poco-x5-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Poco X5 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-microsofts-apppack-and-msibundle-files-to-enhance-productivity/"><u>Integrating Microsoft's Apppack and MsiBundle Files to Enhance Productivity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/image-editing-strategies-remove-unwanted-areas/"><u>Image Editing Strategies: Remove Unwanted Areas</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-secure-command-line-user-permissions-on-pc/"><u>Steps to Secure Command Line User Permissions on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/"><u>How to Thrive in Free Championship Football Simulator</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-unlock-full-potential-of-your-zoom-sessions-with-obs/"><u>[Updated] In 2024, Unlock Full Potential of Your Zoom Sessions With OBS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-blocked-paths-in-windows-update/"><u>Clearing Up Blocked Paths in Windows Update</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-ultimate-compilation-of-advanced-mp3-reduction-software/"><u>Updated 2024 Approved The Ultimate Compilation of Advanced MP3 Reduction Software</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Itel Phone with Broken Screen</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-free-audio-transmutation-exploring-six-efficient-ways-to-convert-video-to-sound/"><u>Updated In 2024, Free Audio Transmutation Exploring Six Efficient Ways to Convert Video to Sound</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-deciphering-no-snaps-possible-blocking-for-2024/"><u>[Updated] Deciphering No Snaps, Possible Blocking for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-efficient-coding-solutions-with-microsofts-companion/"><u>Crafting Efficient Coding Solutions with Microsoft's Companion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-automate-microsoft-to-do-with-ifttt/"><u>How to Automate Microsoft To Do With IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-keyboard-wizardry-with-windows-tools/"><u>Speedy Keyboard Wizardry with Windows Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stop-unintentional-hotkey-engagements-on-pc/"><u>Stop Unintentional Hotkey Engagements on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerated-unzipping-of-multiple-files-using-windows-tools/"><u>Accelerated Unzipping of Multiple Files Using Windows Tools</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-find-out-how-to-add-subtitles-in-the-vlc-media-player-on-your-windows-and-mac-system-with-quick-and-simple-instructions/"><u>Updated Find Out How to Add Subtitles in the VLC Media Player on Your Windows and Mac System with Quick and Simple Instructions</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-leap-into-editing-speedy-windows-photoshop-hacks/"><u>[Updated] Leap Into Editing  Speedy Windows Photoshop Hacks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-operation-failed-0x0000011b-errors/"><u>Troubleshooting Operation Failed: 0X0000011B Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-cmd-mastery-the-20-most-important-commands/"><u>Dive Into CMD Mastery: The 20 Most Important Commands</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-windows-movie-maker-alternatives-6-best-video-editing-software/"><u>In 2024, Windows Movie Maker Alternatives 6 Best Video Editing Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-problems-active-status-of-your-win11-license/"><u>Solving Problems: Active Status of Your Win11 License</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cortana-ends-new-windows-aid-emerges/"><u>Cortana Ends, New Windows Aid Emerges</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-windows-upgrade-failures-and-errors/"><u>How to Resolve Windows Upgrade Failures and Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-enable-nvidia-cp-setting-retention-in-win11/"><u>Strategies to Enable Nvidia CP Setting Retention in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-setup-virtualboxs-security-features-secure-boot-and-tpm/"><u>How to Setup VirtualBox's Security Features: Secure Boot & TPM</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-advanced-techniques-for-perfecting-your-voice-with-morphvox-for-2024/"><u>[New] Advanced Techniques for Perfecting Your Voice with MorphVOX for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/harmonizing-your-footage-with-optimal-aspect-ratios-for-2024/"><u>Harmonizing Your Footage With Optimal Aspect Ratios for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-11-resolving-webcam-error-code-a00f4289/"><u>Troubleshooting Windows 11: Resolving Webcam Error Code A00F4289</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-achieving-studio-quality-with-audacity/"><u>In 2024, Achieving Studio Quality with Audacity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/veiled-functionality-for-context-tools-on-pcs/"><u>Veiled Functionality for Context Tools on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-secrets-of-windows-odbc-settings-panel/"><u>Deciphering the Secrets of Windows' ODBC Settings Panel</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-how-to-edit-the-length-of-a-video-on-youtube/"><u>[New] How to Edit the Length of a Video on YouTube</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-top-quality-fb-pic-and-movie-creator-no-cost/"><u>[Updated] In 2024, Top Quality FB Pic & Movie Creator (No Cost)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-the-integration-of-apple-maps-on-pcs/"><u>Deciphering the Integration of Apple Maps on PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expand-your-video-editing-toolkit-beyond-inshot/"><u>In 2024, Expand Your Video Editing Toolkit Beyond Inshot</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-bypassing-windows-11-sign-in-errors/"><u>Strategies for Bypassing Windows 11 Sign-In Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-windows-0x8007007e-error-code/"><u>How to Fix the Windows 0X8007007E Error Code</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-infinix-note-30i-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Infinix Note 30i Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vcplusplus-redistribution-purpose-explored/"><u>VC++ Redistribution Purpose Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplified-guide-airpods-and-windows-compatibility/"><u>Simplified Guide: AirPods & Windows Compatibility</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-tecno-pova-5-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Tecno Pova 5 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-control-windows-11-shutdown-with-open-filestasks/"><u>How to Control Windows 11 Shutdown with Open Files/Tasks</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-top-12-solutions-to-decipher-and-display-hidden-video-posts-on-fb-for-2024/"><u>[Updated] Top 12 Solutions to Decipher and Display Hidden Video Posts on FB for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-recover-icon-positions-in-windows-10/"><u>Swiftly Recover Icon Positions in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-domain-services-printer-failures-on-newest-microsoft-os/"><u>Fixing Domain Services Printer Failures on Newest Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-upgrade-notifications/"><u>Turn Off Windows Upgrade Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11-and-the-lost-bluetooth-9-effective-solutions-to-find-your-connection/"><u>Win 11 and the Lost Bluetooth: 9 Effective Solutions to Find Your Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unwanted-camera-request-errors-code-0xa00f4243/"><u>Removing Unwanted Camera Request Errors (Code 0xA00F4243)</u></a></li>
</ul></div>
