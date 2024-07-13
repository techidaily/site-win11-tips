---
title: Adapt Window's Sleep Timer to Suit You
date: 2024-07-12T17:57:03.818Z
updated: 2024-07-13T17:57:03.818Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adapt Window's Sleep Timer to Suit You
excerpt: This Article Describes Adapt Window's Sleep Timer to Suit You
keywords: Sleep Timer Adjustment,Customize Sleep Schedule,Optimize Sleep Settings,Tailor Sleep Timing,Personalized Sleep Timer,Align Sleep Cycle,Adaptive Sleep Timer
thumbnail: https://thmb.techidaily.com/4552dd09d3248cdc2d2f0b5a8866485e28d07f676a831c6174ae4d9651da8ef0.jpg
---

## Adapt Window's Sleep Timer to Suit You

 The Windows lock screen usually displays images when you power on your device or wake it from sleep mode. By default, the lock screen will only appear for about a minute, and then your screen will go blank.

 Meanwhile, the screen saver is an image or animation that appears when your PC has been inactive for a while. Just like the lock screen, the screen saver will also appear for about one minute.

 Wondering how you can display the lock screen or screen saver for longer?

 This article will show you the various ways to change the Windows lock screen and screen saver timeout settings.

## 1\. How to Change the Lock Screen Timeout Settings

 Let’s first take a look at how you can configure the Windows 10 lock screen timeout settings.

### Use the Windows System Settings

 The Windows system settings always come in handy in various situations. Let’s check out how you can use them to change the Windows 10 screen lock timeout settings:

1. Press **Win + I** to open the system settings.
2. Select the **Personalization** option from the menu items.
3. Click the **Lock screen** option on the left-hand side pane.
4. Scroll down on the right-hand side and select the **Screen timeout settings** option.
5. Click the **On battery power** drop-down menu on the right-hand side pane and select your preferred option.

![Using Windows System Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-Windows-System-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 Apply the same settings for the **When plugged** in option on the right-hand side pane. From there, close the **system settings** and restart your device to save these changes.

### Use the Edit Plan Settings (via the Control Panel)

 The Control Panel is a reliable Windows tool that helps you configure various system settings. We’ll show you how you can use it to configure the screen saver timeout settings.

 In this case, we’ll use the Control Panel to navigate to the Edit Plan settings.

 Here are the steps you need to follow:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**.
2. Click the **View by** drop-down menu and select **Small icons**.
3. Select **Power Options** from the menu items.
4. Click the **Change plan settings** option on the right-hand side.
5. Locate the **Turn off the display** option. From there, select your preferred options on the **On battery** and **When plugged in** drop-down menus.
6. Finally, click the **Save changes** button.

![Using the Edit Plan Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Edit-Plan-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

### Use the Advanced Power Options (via the Control Panel)

 You can also use the Control Panel's advanced power settings to configure the lock screen timeout settings.

 Simply follow these steps:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Control Panel** and then press **OK**.
3. Select **Power Options** from the menu items.
4. Click **Change plan settings**. From there, select the **Change advanced power settings** option on the next screen.
5. Scroll down and click the **Display** option. Next, click the **Turn off display after** option.
6. Select the **On battery** option, and then configure the lock screen timeout settings using the **arrow buttons**. From there, apply the same settings for the **Plugged in** option.

![Using the Advanced Power Options to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Advanced-Power-Options-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 When you're done, click **Apply** and then click **OK**. Finally, close the **Control Panel** and then restart your device to save these changes.

### Use the Command Prompt

 The Command Prompt is a reliable tool that can help you [troubleshoot various Windows system issues](https://www.makeuseof.com/how-to-troubleshoot-faulty-windows-pc/). Interestingly, this tool can also help you configure the settings on your device.

 Here’s how to configure the Windows lock screen timeout settings [using the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/):

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Next, type the following commands—one at a time—and press **Enter** in each case:

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOIDLE 60

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 60

 The "**60**" in the command indicates the duration (seconds) in which the lock screen will be displayed. If you want to increase the lock screen duration, apply the previous steps and change "**60**" to a different value of your choice.

 When you finish, type the following command and press **Enter**:

powercfg.exe /SETACTIVE SCHEME_CURRENT

 Finally, restart your PC to save these changes.

## How to Change the Screen Saver Timeout Settings

 Now, let's explore how you can change the screen saver timeout settings.

### Use the System Settings

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Here's how to change the duration of the screen saver using the system settings:

1. Press **Win + I** to open the system settings.
2. Type **screen saver** in the Settings search bar and select the **Change screen saver** option.

 Bear in mind that you can change the screen saver timeout settings only if the screen saver is enabled. If the screen saver is currently disabled, click the **Screen saver** drop-down menu and select your preferred image.

![Enabling the screensaver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Enabling-the-screensaver-option.jpg)

 From there, follow these steps to configure the screen saver timeout settings:

1. Navigate to the **Wait** option on the Screen Saver Settings window.
2. Click the **arrow buttons** to select the screen saver duration (in minutes).

![Using the System Settings to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-System-Settings-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 Finally, press **Apply** and then press **OK** to save these changes.

### Use the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is an incredible tool that makes it easy for you to configure various system settings. Now, here's how you can use this tool to configure the screen saver timeout settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates> Control Panel > Personalization**.
4. Double-click the **Screen saver timeout** option on the right-hand side.

![Using the LGPE to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-LGPE-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 In the next window, select the **Enabled** option. From there, use the **arrow buttons** next to the **Seconds** box to select the duration of the screen saver.

 Press **Apply**, press **OK**, and then close the **LGPE**. Finally, restart your device to save these changes.

 If you want to disable the screen saver settings, here are the steps you need to follow:

1. Navigate to the **Personalization** option on the LGPE as per the previous steps.
2. Double-click the **Screen saver timeout** option and select either the **Disabled** or the **Not Configured** option.
3. Finally, press **Apply**, press **OK**, and then close the **LGPE**.

 Still looking for more tips on how to increase screen time on your laptop? We've got one more solution for you!

### Use the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor can help you tweak the screen-saver timeout settings with ease. But it's quite a sensitive tool, so you should consider [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed.

 Now, here's how to configure the screen-saver timeout settings with the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **OK** to open the Registry Editor.
3. Copy-paste the following command into the address bar:

HKEY_USERS\.DEFAULT\Control Panel\Desktop

 Locate the **ScreenSaveTimeOut** option on the right-hand side.

 If the key is missing, right-click on a blank space on the right and select **New > DWORD (32-bit) Value**. From there, rename the value as **ScreenSaveTimeOut** and press **Enter**.

 Next, double-click the **ScreenSaveTimeOut** value.

![Clicking the "ScreenSaveTimeOut" value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-screensavetimeout-value.jpg)

 Now, type the screen saver timeout duration (in seconds) in the **Value data** box. The default option is usually **900** seconds (15 minutes), but you can enter your desired value. Finally, click **OK** and then restart your device to save these changes.

## Tweak Your Lock Screen Timeout Settings Without a Hassle

 Wondering how to increase laptop screen time? Or do you want to lock your PC and ensure that it doesn’t fully go into sleep mode?

 Try increasing the lock screen and screen saver timeout settings using the solutions we’ve covered. From there, you can explore other cool things, such as how to automatically lock your Windows 11 PC when you’re away.


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
<li><a href="https://win11-tips.techidaily.com/old-vs-new-why-users-favor-windows-10-over-11/"><u>Old vs New: Why Users Favor Windows 10 Over 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stops-repeated-edge-icons-on-workspace/"><u>Stops Repeated Edge Icons on Workspace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-upgrade-to-windows-11-22h2-on-unsupported-hardware/"><u>How to Upgrade to Windows 11 22H2 on Unsupported Hardware</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-mastering-the-self-play-feature-in-facebook-videos-for-2024/"><u>[New] Mastering the Self-Play Feature in Facebook Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-s18-pro-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Vivo S18 Pro</u></a></li>
<li><a href="https://fox-http.techidaily.com/basics-of-evolving-media-and-graphics-for-2024/"><u>Basics of Evolving Media and Graphics for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-1-choice-easy-online-video-text-conversion/"><u>2024 Approved  1 Choice  Easy Online Video Text Conversion</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-itel-a70-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Itel A70? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-screen-splitting-problems-in-win-10/"><u>Solutions for Screen Splitting Problems in Win 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectify-corner-design-in-win11/"><u>Rectify Corner Design in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-fixes-for-nvidia-gl-driver-issue-3-on-win11/"><u>Expert Fixes for NVIDIA GL Driver Issue #3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-file-sharing-using-dropboxgoogle-drive-from-windows-paths/"><u>Streamlining File Sharing: Using Dropbox/Google Drive From Windows Paths</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-hidden-paths-of-window-menus-on-pc/"><u>Navigating the Hidden Paths of Window Menus on PC</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-from-written-to-spoken-effective-text-to-mp3-conversion-methods/"><u>In 2024, From Written to Spoken Effective Text-to-MP3 Conversion Methods</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/spikes-in-subscribers-implementing-top-12-video-promotion-techniques-for-2024/"><u>Spikes in Subscribers  Implementing Top 12 Video Promotion Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-guide-to-implementing-bluescreenview-strategies/"><u>Detailed Guide to Implementing BlueScreenView Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/practical-guide-to-disregarding-false-security-alarms-in-chrome/"><u>Practical Guide to Disregarding False Security Alarms in Chrome</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-hot-tips-for-business-indispensable-items-you-cant-afford-to-miss/"><u>[New] In 2024, Hot Tips for Business  Indispensable Items You Can't Afford To Miss</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reconciling-system-with-a-fresh-net-framework-max-156/"><u>Reconciling System with a Fresh .NET Framework (Max 156)</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-achieving-professional-bokeh-on-mobile-phones-for-2024/"><u>[Updated] Achieving Professional Bokeh on Mobile Phones for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-file-access-failures-in-microsoft-office-outlook/"><u>Correcting File Access Failures in Microsoft Office Outlook</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-6s-without-passcode-4-easy-methods-by-drfone-ios/"><u>How To Unlock Apple iPhone 6s Without Passcode? 4 Easy Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-scheduling-in-windows-11-calendar/"><u>Streamlining Scheduling in Windows 11 Calendar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-pc-speed-for-swift-steam-content-delivery/"><u>Enhance PC Speed for Swift Steam Content Delivery</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-steam-network-error-in-windows-11-systems/"><u>Remedying Steam Network Error in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-error-code-0xc00000f-strategies-for-success/"><u>Mastery over Windows Error Code 0Xc00000f: Strategies for Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-absence-of-tab-functionality-in-os-x/"><u>Navigating the Absence of Tab Functionality in OS X</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-yuzu-fps-on-pc-systems/"><u>Enhancing Yuzu FPS on PC Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-ahead-with-windows-11-integrating-outlook-preview/"><u>Get Ahead with Windows 11: Integrating Outlook Preview</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/frenzied-funhouse-a-guide-to-wildest-tiktok-games-for-2024/"><u>Frenzied Funhouse  A Guide to Wildest TikTok Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gain-full-system-access-through-cmd-elevation/"><u>Gain Full System Access Through CMD Elevation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-high-resolution-drone-flights-a-mi-examination/"><u>In 2024, High-Resolution Drone Flights  A MI Examination</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-page-load-failure-on-microsoft-store-windows-app/"><u>Resolving 'Page Load Failure' On Microsoft Store Windows App</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-ending-invisible-gaming-captures-in-software/"><u>In 2024, Ending Invisible Gaming Captures in Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-way-a-guide-to-mapping-drives-on-windows-11/"><u>Navigate Your Way: A Guide to Mapping Drives on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/transformative-tales-a-compendium-of-the-best-inspirational-movies/"><u>Transformative Tales  A Compendium of the Best Inspirational Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-personalized-lock-patterns-on-windows-11/"><u>Mastering Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-windows-11-error-code-22-lockout/"><u>Steps to Rectify Windows 11 Error Code 22 Lockout</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/the-best-ai-video-makers-from-photos-to-create-captivating-videos-with-pictures/"><u>The Best AI Video Makers From Photos to Create Captivating Videos with Pictures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-flush-the-steam-dns-cache-on-windows/"><u>How to Flush the Steam DNS Cache on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dismantling-barriers-to-running-powershell-scripts-in-windows/"><u>Dismantling Barriers to Running PowerShell Scripts in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-and-fixing-system-call-error-on-windows-11/"><u>Preventing and Fixing System Call Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-guide-remedying-directdraw-disruptions-in-win1011/"><u>Expert Guide: Remedying DirectDraw Disruptions in Win10/11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unlocking-igtvs-potential-5-ways-to-surge-follower-count/"><u>[Updated] In 2024, Unlocking IGTV's Potential  5 Ways to Surge Follower Count</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-find-the-detailed-guide-for-using-a-picture-ratio-calculator-to-determine-the-best-video-aspect-ratio-also-learn-how-to-find-and-adjus/"><u>Updated 2024 Approved Find the Detailed Guide for Using a Picture Ratio Calculator to Determine the Best Video Aspect Ratio. Also, Learn How to Find and Adjust the Right Size of Images</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-producing-square-videos-in-imovie-for-instagram/"><u>[New] 2024 Approved  Step-by-Step  Producing Square Videos in iMovie for Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-the-complexities-of-onedrive-errors/"><u>Navigating Through the Complexities of OneDrive Errors</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-content-creators-den/"><u>[New] 2024 Approved  Content Creator's Den</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-up-gmaps-windows-pc-guide/"><u>Setting Up GMaps: Windows PC Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-fixing-windows-11-help-menu-failure/"><u>Steps for Fixing Windows 11 Help Menu Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-black-windows-display-with-ease/"><u>Navigate Black Windows Display with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-invisible-wi-fi-on-windows/"><u>Master the Art of Invisible Wi-Fi on Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-13-pro-max-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 13 Pro Max with IMEI Code?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-unrecoverable-windows-errors/"><u>Solutions to Unrecoverable Windows Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-loop-of-0xf0831-error-in-win11-os/"><u>Breaking the Loop of 0XF0831 Error in Win11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-the-lock-screen-and-screen-saver-timeout-settings-on-windows/"><u>How to Change the Lock Screen and Screen Saver Timeout Settings on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-changing-proxies-on-windows-11/"><u>Step-by-Step: Changing Proxies on Windows 11</u></a></li>
</ul></div>
