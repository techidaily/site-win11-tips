---
title: Avoid Changing Windows Date & Time Accurately
date: 2024-08-16T01:08:42.547Z
updated: 2024-08-17T01:08:42.547Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Changing Windows Date & Time Accurately
excerpt: This Article Describes Avoid Changing Windows Date & Time Accurately
keywords: TimeSync Avoidance,WindowDateAccuracy,SystemTimeStable,WindowsDateTimeSafety,DateChangePrevention,TimestampSecurity,OSDateTimeIntegrity
thumbnail: https://thmb.techidaily.com/7f4ae1b9b31cac38f7f5bddb79d648495e38c22783ddea3f0c620d5fbd42617b.jpg
---

## Avoid Changing Windows Date & Time Accurately

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-mastering-video-posting-between-twitter-and-tumblr/"><u>[New] 2024 Approved  Mastering Video Posting Between Twitter and Tumblr</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-secret-story-spotters-top-5-app-recommendations/"><u>[New] Secret Story Spotters  Top 5 App Recommendations</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-essential-8-strategies-for-digital-sound-recording/"><u>[Updated] 2024 Approved  Essential 8 Strategies for Digital Sound Recording</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-color-contrast-reimagined-choosing-hdr-for-better-videos/"><u>[Updated] Color Contrast Reimagined  Choosing HDR for Better Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-deciding-audio-platforms-podcasts-or-youtube/"><u>[Updated] Deciding Audio Platforms  Podcasts or YouTube?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-a-practical-approach-to-using-screencastify-for-video-capture/"><u>[Updated] In 2024, A Practical Approach to Using Screencastify for Video Capture</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-real-strategy-behind-instagram-reels/"><u>[Updated] In 2024, The Real Strategy Behind Instagram Reels</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-a-step-by-step-guide-to-your-first-twitter-profile/"><u>2024 Approved  A Step-by-Step Guide to Your First Twitter Profile</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-developing-mastery-in-professional-interview-processes/"><u>2024 Approved  Developing Mastery in Professional Interview Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-and-resolving-win11-installation-anomalies-quickly/"><u>Decoding and Resolving Win11 Installation Anomalies Quickly</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/demystifying-kanji-your-guide-to-japanese-writing/"><u>Demystifying Kanji: Your Guide to Japanese Writing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/device-disconnection-remedy-with-dxgi-error-solution/"><u>Device Disconnection Remedy with DXGI Error Solution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-steps-to-stabilize-screen-flickering-in-windows/"><u>Effective Steps to Stabilize Screen Flickering in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/glitch-free-windows-try-these-10-fixes-first/"><u>Glitch-Free Windows? Try These 10 Fixes First</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-minimize-explore-tab-noise-in-windows/"><u>How to Minimize Explore Tab Noise in Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-dissecting-instagrams-maximum-video-duration-rule/"><u>In 2024, Dissecting Instagram's Maximum Video Duration Rule</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-iphone-14-drfone-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-sony-xperia-5-v-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-proven-strategies-for-device-screening/"><u>In 2024, Proven Strategies for Device Screening</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-x-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone X Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-xiaomi-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Xiaomi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keeping-out-invaders-effective-windows-access-blockers/"><u>Keeping Out Invaders: Effective Windows Access Blockers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mambo-measuring-macaws/"><u>Mambo Measuring Macaws</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-full-hd-classics-proven-scummvm-strategies-for-the-windows-aficionado/"><u>Mastering Full HD Classics: Proven ScummVM Strategies for the Windows Aficionado</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-sudden-screen-darkening-in-windows-gaming/"><u>Mitigating Sudden Screen Darkening in Windows Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimum-virtual-options-tailored-for-windows-11-systems/"><u>Optimum Virtual Options Tailored for Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-buffering-issues-on-chrome-and-youtube/"><u>Overcoming Buffering Issues on Chrome & YouTube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-package-registration-on-windows-1011/"><u>Overcoming Obstacles in Package Registration on Windows 10/11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-wi-fi-harmony-top-solutions-to-cure-non-functioning-usb-on-windows/"><u>Regain Wi-Fi Harmony: Top Solutions to Cure Non-Functioning USB on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-device-opens-on-audacity-in-windows-os/"><u>Remedying Device Opens on Audacity in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/smarter-operating-systems-ais-role-in-windows-revolution/"><u>Smarter Operating Systems: AI's Role in Windows Revolution</u></a></li>
<li><a href="https://win-answers.techidaily.com/solve-your-problems-with-the-best-fixes-for-stray-not-working/"><u>Solve Your Problems with the Best Fixes for Stray Not Working</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-cross-language-switching-hotkeys-in-windows-1011/"><u>Speedy Cross-Language Switching: Hotkeys in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-audacity-audio-error-win1011/"><u>Strategies to Overcome Audacity Audio Error (Win10/11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transferring-older-pc-tools-from-legacy-systems-to-windows-11/"><u>Transferring Older PC Tools: From Legacy Systems to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unified-workspace-managing-windows-folders-and-files/"><u>Unified Workspace: Managing Windows Folders & Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-and-phone-link-debate-best-windows-phone-app-evaluation/"><u>Unison & Phone Link Debate: Best Windows Phone App Evaluation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-assistive-features-a-quick-guide/"><u>Unlocking Windows' Assistive Features: A Quick Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/utilizing-windows-software-to-supercharge-macos-functionality/"><u>Utilizing Windows Software to Supercharge macOS Functionality</u></a></li>
</ul></div>
