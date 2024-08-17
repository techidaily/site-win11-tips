---
title: "Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
date: 2024-08-16T02:12:49.378Z
updated: 2024-08-17T02:12:49.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
excerpt: "This Article Describes Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems"
keywords: Windows Hello Troubleshooting,Fingerprint Lock Issues,Solve Windows Fingerprint Error,Overcome Windows Hello Failures,Fix Windows Fingerprint Login,Unlock Happy Methods,Windows Fingerprint Security Tips
thumbnail: https://thmb.techidaily.com/1a71493edba37cb030611c5a8b9738f6d63a9069f2561431aa2bb888dda851d0.jpg
---

## Unlock Windows Hello: 5 Ways to Tackle Fingerprint Problems

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-adeptly-archive-your-fb-friends-lives-in-seconds/"><u>[New] Adeptly Archive Your Fb Friends' Lives in Seconds</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-discord-profile-video-info-dimensions-codec-time-span-for-2024/"><u>[New] Discord Profile Video Info  Dimensions, Codec, Time Span for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-go-viral-on-youtube-with-impressive-music-reaction-content-for-2024/"><u>[New] How to Go Viral on YouTube with Impressive Music Reaction Content for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-a-comprehensive-walkthrough-for-imovie-and-youtube-collaboration/"><u>[New] In 2024, A Comprehensive Walkthrough for iMovie and YouTube Collaboration</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-excellent-auditory-recording-devices-for-classrooms/"><u>[New] In 2024, Excellent Auditory Recording Devices for Classrooms</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-ultimate-guide-to-recording-gaming-with-fraps-for-2024/"><u>[New] The Ultimate Guide to Recording Gaming with Fraps for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-imagination-to-illustration-ranking-the-best-8-iphone-drawing-software/"><u>[Updated] From Imagination to Illustration  Ranking the Best 8 iPhone Drawing Software</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-best-webinar-title-generator/"><u>2024 Approved  Best Webinar Title Generator</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/acclaimed-creators-superior-insta-hlv-page-builders-for-2024/"><u>Acclaimed Creators  Superior Insta HLV Page Builders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/alter-subnet-configurations-in-windows-11/"><u>Alter Subnet Configurations in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-user-adjustments-to-windows-screensaver/"><u>Avoiding User Adjustments to Windows Screensaver</u></a></li>
<li><a href="https://fox-glue.techidaily.com/break-boundaries-get-free-vob-handling-toolset-pc-and-mac/"><u>Break Boundaries  Get Free VOB Handling Toolset (PC & Mac)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/circumventing-no-alert-settings-for-windows-11-cameras/"><u>Circumventing No-Alert Settings for Windows 11 Cameras</u></a></li>
<li><a href="https://win11-tips.techidaily.com/corrective-measures-for-disabled-lock-screen-timer/"><u>Corrective Measures for Disabled Lock Screen Timer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cpu-generation-inquiry-on-windows-8-efficient-approaches/"><u>CPU Generation Inquiry on Windows – 8 Efficient Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-window-11s-desktop-menu-add-ons/"><u>Customizing Window 11'S Desktop Menu Add-Ons</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-nokia-105-classic-device-sim-by-drfone-android/"><u>Easily Unlock Your Nokia 105 Classic Device SIM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-power-management-on-win-11/"><u>Efficient Power Management on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enable-tone-playback-on-windows-post-hardware-failure/"><u>Enable Tone Playback on Windows Post Hardware Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719311785872-fix-crashing-file-explorer-on-windows-11-now/"><u>Fix Crashing File Explorer on Windows 11 Now!</u></a></li>
<li><a href="https://driver-download.techidaily.com/fix-your-hp-beats-audio-card-issues-on-windows-proven-techniques-for-win-10-8-and-7-systems/"><u>Fix Your HP Beats Audio Card Issues on Windows - Proven Techniques for WIN 10, 8 & 7 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-productivity-the-most-compelling-task-list-software-on-windows-11/"><u>Harnessing Productivity: The Most Compelling Task List Software on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-p55-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel P55 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-unclog-the-windows-vds-startup-process/"><u>How to Unclog the Windows VDS Startup Process</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-basic-to-breakthrough-a-youtube-live-thumbnail-journey/"><u>In 2024, From Basic to Breakthrough  A YouTube Live Thumbnail Journey</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-infinix-smart-7-hd-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Infinix Smart 7 HD Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-vivo-y100t-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Vivo Y100t Phone that is Locked?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-simplified-path-to-perfect-video-clarity/"><u>In 2024, Simplified Path to Perfect Video Clarity</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unleash-creativity-in-snaps-15-innovative-posting-techniques/"><u>In 2024, Unleash Creativity in Snaps  15 Innovative Posting Techniques</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-xs-max-by-drfone-ios/"><u>In 2024, Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone XS Max</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-regain-normal-colors-of-microsoft-shop/"><u>Methods to Regain Normal Colors of Microsoft Shop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/neatness-noted-navigating-a-tidier-windowed-explore/"><u>Neatness Noted: Navigating a Tidier Windowed Explore</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-challenges-of-o365-sync-failures-in-win11/"><u>Overcoming the Challenges of O365 Sync Failures in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-setting-up-windows-outlook-preview/"><u>Quick Guide: Setting Up Windows' Outlook Preview</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-and-reinforcing-win-1011-menu-functionality/"><u>Reactivating and Reinforcing Win 10/11 Menu Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reclaiming-lost-wireless-ties-with-these-10-windows-10-tweaks/"><u>Reclaiming Lost Wireless Ties with These 10 Windows 10 Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-file-lockdowns-access-restoration-on-pcs/"><u>Reversing File Lockdowns: Access Restoration on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/safe-windows-storage-expansion-methods/"><u>Safe Windows Storage Expansion Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-security-by-learning-the-quickest-ways-to-access-credentials-in-win11/"><u>Skyrocket Security by Learning the Quickest Ways to Access Credentials in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-solutions-for-we-encountered-an-error-during-oculus-install/"><u>Step-By Step Solutions for We Encountered an Error During Oculus Install</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-stabilizing-inconsistent-windows-printers/"><u>Steps for Stabilizing Inconsistent Windows Printers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-razer-devices-detection-via-synapse-on-windows/"><u>Steps to Restore Razer Devices Detection via Synapse on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-counteract-internal-error-with-remote-desktop/"><u>Strategies to Counteract Internal Error with Remote Desktop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-systemsettings-issues-on-win11/"><u>Strategies to Overcome SystemSettings Issues on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-windows-photos-apps-generative-erase-is-actually-great/"><u>The Windows Photos App's Generative Erase Is Actually Great</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uniting-your-inboxes-connecting-gmail-with-windows-outlook-app/"><u>Uniting Your Inboxes: Connecting Gmail with Windows' Outlook App</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unlocking-the-meaning-behind-tiktoks-pfp-emoji-for-2024/"><u>Unlocking the Meaning Behind TikTok's PFP Emoji for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-youre-overlooking-with-low-priced-activation-keys/"><u>What You're Overlooking with Low-Priced Activation Keys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-mastering-delete-confirmation-options/"><u>Windows: Mastering Delete Confirmation Options</u></a></li>
</ul></div>
