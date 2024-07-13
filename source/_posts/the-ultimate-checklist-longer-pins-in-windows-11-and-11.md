---
title: "The Ultimate Checklist: Longer PINs in Windows 11 and 11"
date: 2024-07-12T16:33:00.790Z
updated: 2024-07-13T16:33:00.790Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Checklist: Longer PINs in Windows 11 and 11"
excerpt: "This Article Describes The Ultimate Checklist: Longer PINs in Windows 11 and 11"
keywords: Windows 11 PIN Length,Longer Security Pin,Enhanced PC Pincode,Update Windows Pin Policy,11-Version Pin Strategy,Secure Win11 Login,Extended PIN Support (Win11)
thumbnail: https://thmb.techidaily.com/dbe86f0410f8e9bad5bf3228390b329f698cfe445d25a553d85696ff0b2a85a2.jpg
---

## The Ultimate Checklist: Longer PINs in Windows 11 and 11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-perfect-your-mobile-photography-with-targeted-blurs/"><u>[New] Perfect Your Mobile Photography with Targeted Blurs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-essentials-of-youtube-gaming-livestreaming/"><u>[New] The Essentials of YouTube Gaming Livestreaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-oppo-reno-11-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Oppo Reno 11 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-series-top-tier-webcam-grips/"><u>Ultimate Series  Top-Tier Webcam Grips</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-vivo-y02t-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Vivo Y02T to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/zap-anthem-hiccups-swift-fixes/"><u>Zap Anthem Hiccups: Swift Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-directdraw-errors-with-ease-on-new-windows-oses/"><u>Fixing DirectDraw Errors with Ease on New Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-try-now-bluetooth-hurdle-on-pcs-and-tablets/"><u>Bypass 'Try Now' Bluetooth Hurdle on PCs & Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ephemeral-approach-to-suspending-windows-11-protection-systems/"><u>Ephemeral Approach to Suspending Windows 11 Protection Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-reinstalling-microsofts-mspm/"><u>Master the Art: Reinstalling Microsoft's MSPM</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-efficient-ad-elimination-select-7-android-adblockers/"><u>[Updated] Efficient Ad Elimination  Select 7 Android AdBlockers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keyboard-control-in-action-modifying-software-size-on-windows-11/"><u>Keyboard Control in Action: Modifying Software Size on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-service-setups-for-an-immaculate-windows-11-launch-experience/"><u>Mastering Service Setups for an Immaculate Windows 11 Launch Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-of-inactive-pc-device-engagement/"><u>Mastery of Inactive PC Device Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangle-onedrive-and-microsoft-account-on-windows-machine/"><u>Disentangle OneDrive & Microsoft Account on Windows Machine</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-analysis-understanding-the-variance-between-non-microsoft-and-microsoft-account-in-os/"><u>Comparative Analysis: Understanding the Variance Between Non-Microsoft and Microsoft Account in OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/instant-windows-slide-show-setup-7-essential-steps/"><u>Instant Windows Slide Show Setup: 7 Essential Steps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/revolutionary-wearable-camera-tech/"><u>Revolutionary Wearable Camera Tech</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-s17t-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo S17t without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-investment-tips-from-youtube-experts/"><u>2024 Approved  Top Investment Tips From YouTube Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-reset-failure-count-for-incorrect-login-attempts-on-windows-11/"><u>Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-syncs-in-win-10/"><u>Fixing Steam Cloud Syncs in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-overcapacity-alerts-for-gpt-service/"><u>Counteracting Overcapacity Alerts for GPT Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-things-to-try-when-prime-videos-subtitles-arent-working-on-windows-11/"><u>4 Things to Try When Prime Video's Subtitles Aren't Working on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defend-with-confidence-top-4-password-protectors-for-win-11-users/"><u>Defend With Confidence: Top 4 Password Protectors for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-novice-to-pro-a-tactical-guide-to-snapchat-marketing-for-2024/"><u>[Updated] From Novice to Pro  A Tactical Guide to Snapchat Marketing for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quicklooker-windows-11s-speedy-photo-viewer/"><u>[Updated] QuickLooker  Windows 11'S Speedy Photo Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-storage-activating-windows-11s-compression/"><u>Efficient Storage: Activating Windows 11’S Compression</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-windows-iscsi-initiator-a-beginners-guide/"><u>Navigating the Windows iSCSI Initiator: A Beginner's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-install-microsoft-works-on-windows-11-or-11/"><u>How to Install Microsoft Works on Windows 11 or 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unmatched-subtitle-expertise-top-10-leaders-in-video-caption-manipulation-for-2024/"><u>Unmatched Subtitle Expertise – Top 10 Leaders in Video Caption Manipulation for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-based-audacity-crash-code-9999/"><u>Fixing Windows-Based Audacity Crash Code 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-the-outlook-preview-app-on-windows-10-and-11/"><u>How to Get the Outlook Preview App on Windows 10 and 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/adding-visuals-on-instagram-quickly-for-2024/"><u>Adding Visuals on Instagram Quickly for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-discord-setup-failures-on-windows-1011/"><u>Mastery Over Discord Setup Failures on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-iomap64-system-freezes-and-bsods/"><u>Overcoming Windows IOMap64 System Freezes and BSODs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/find-whistle-sounds-effect/"><u>Find Whistle Sounds Effect</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-no-cost-high-reward-top-10-free-online-video-quality-enhancement-tools/"><u>In 2024, No Cost, High Reward Top 10 Free Online Video Quality Enhancement Tools</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-oppo-reno-11-5g-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Oppo Reno 11 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-aim-for-affluence-enroll-now-in-youtubes-partner-programme/"><u>[Updated] 2024 Approved  Aim for Affluence  Enroll Now in YouTube's Partner Programme</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-mastering-video-transfer-youtube-to-dailymotion-conversion/"><u>[Updated] Mastering Video Transfer  YouTube to Dailymotion Conversion</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-perfecting-sound-quality-adding-lame-to-your-audacity-setup/"><u>Updated 2024 Approved Perfecting Sound Quality Adding Lame to Your Audacity Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-freezes-in-apex-legends/"><u>Winning the Battle Against Freezes in Apex Legends</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-employ-microsofts-copilot-tool-in-windows-ides/"><u>How to Employ Microsoft's Copilot Tool in Windows IDEs</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unified-brands-and-streaming-services-a-new-age-of-marketing-collaboration/"><u>[Updated] Unified Brands & Streaming Services  A New Age of Marketing Collaboration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-pc-reawakening-top-3-windows-reset-methods/"><u>Efficient PC Reawakening: Top 3 Windows Reset Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-ais-individuality-and-innovation/"><u>A Closer Look at AI's Individuality and Innovation</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-real-time-streaming-methods-for-facebook-video-uploads/"><u>[Updated] 2024 Approved  Real-Time Streaming Methods for Facebook Video Uploads</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-constructing-an-elegant-transition-for-decreasing-auditory-intensity/"><u>2024 Approved Constructing an Elegant Transition for Decreasing Auditory Intensity</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-4-ways-for-apple-iphone-xs-max-to-mac-mirroring-drfone-by-drfone-ios/"><u>In 2024, Top 4 Ways for Apple iPhone XS Max to Mac Mirroring | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premier-android-vocal-mixer-app-for-2024/"><u>Premier Android Vocal Mixer App for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ring-youtube-and-dailymotion-notable-contrasts/"><u>Comparing YouTube and Dailymotion  Notable Contrasts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-6-methods-to-mirror-apple-iphone-xs-to-your-windows-pc-drfone-by-drfone-ios/"><u>In 2024, 6 Methods to Mirror Apple iPhone XS to your Windows PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-aid-unlocking-essential-assistive-tech/"><u>Windows Aid: Unlocking Essential Assistive Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ancient-pc-modern-atlasos/"><u>Ancient PC, Modern AtlasOS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-perfecting-your-content-understanding-facebook-video-sizes-and-ratios/"><u>[New] In 2024, Perfecting Your Content  Understanding Facebook Video Sizes and Ratios</u></a></li>
<li><a href="https://techidaily.com/update-hardware-drivers-with-device-manager-on-windows-10-and-7-by-drivereasy-guide/"><u>Update hardware drivers with Device Manager on Windows 10 & 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/network-barricades-implement-these-7-windows-protections/"><u>Network Barricades: Implement These 7 Windows Protections</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-a-compre-written-by-john-doe/"><u>[Updated] A Compre Written By  John Doe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-win-pcs-voice-input-problems/"><u>Diagnosing Win PCs' Voice Input Problems</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-xs-max-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone XS Max to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
</ul></div>
