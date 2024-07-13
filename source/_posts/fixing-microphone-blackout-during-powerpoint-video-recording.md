---
title: Fixing Microphone Blackout During PowerPoint Video Recording
date: 2024-07-12T17:19:13.056Z
updated: 2024-07-13T17:19:13.056Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Microphone Blackout During PowerPoint Video Recording
excerpt: This Article Describes Fixing Microphone Blackout During PowerPoint Video Recording
keywords: Microphone Recording Issues,No Sound Blackout Fix,PowerPoint Audio Glitch,Clear Voice Feedback,Preventing PPT Blackouts,Remedy Speaker Problems,Audio Consistency Tips
thumbnail: https://thmb.techidaily.com/a44de758792af2fb67431bc0cd10b70e0176e5a8a3e2c53a5711bc4054272247.jpg
---

## Fixing Microphone Blackout During PowerPoint Video Recording

 The screen recording feature in Microsoft PowerPoint can be useful for recording tutorials or training videos on your computer. But what if PowerPoint fails to capture the audio when you record the screen of your Windows computer?

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.

## 1\. Restart PowerPoint

 Temporary issues with PowerPoint can sometimes disrupt its ability to capture audio on your Windows computer. If it’s just a one-off glitch, simply closing and reopening PowerPoint should fix the problem.

 Press **Ctrl + Shift + Esc** to open the Task Manager. In the **Processes** tab, right-click on **Microsoft PowerPoint** and select the **End task** option.

![Close PowerPoint Using Task Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/close-powerpoint-using-task-manager-on-windows.jpg)

 Right-click on the **PowerPoint** shortcut and select **Run as administrator**. After that, try to create a screen recording and see if PowerPoint records the audio this time.

## 2\. Allow Desktop Apps to Use Your Microphone

 Another reason why PowerPoint might fail to record audio is if you have denied desktop apps permission to access your microphone. Here's how you can change that.

1. Press **Win + I** to open the Settings app.
2. Head to **Privacy & security > App permissions > Microphone**.
3. Enable the toggle next to **Let desktop apps access your microphone**.  
![Allow Desktop Apps to Access Microphone on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-desktop-apps-to-access-microphone-on-windows.jpg)

 Once you complete the above steps, all your desktop apps, including PowerPoint, should be able to use your microphone.

## 3\. Check Which Device Is Set as the Default Microphone on Windows

 Are there several audio devices connected to your Windows computer? If so, you need to ensure that you have selected the correct microphone on Windows.

 To view or change the default microphone on Windows, use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **sound settings** in the box and press **Enter**.
3. Under the **Input** tab, select your preferred audio device.  
![Select Default Microphone in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-default-microphone-in-windows.jpg)

 Is your microphone not showing up in the Settings app? Apply the necessary [fixes to get Windows to detect your microphone](https://www.makeuseof.com/windows-not-detecting-microphone/).

## 4\. Disable Hardware Graphics Acceleration in PowerPoint

 While enabling the hardware graphics acceleration feature in PowerPoint can improve its performance, the feature may not work seamlessly all the time. When this happens, you are likely to run into all kinds of issues, including issues with the screen recorder.

 According to a post on [Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/all/audio-not-working-on-my-ppt-recording/79c77eae-2f86-4c09-a3d6-5fc4b3d89c58), several users managed to fix this particular issue by disabling the hardware graphics acceleration in PowerPoint. You can also give it a try with these steps:

1. Open PowerPoint on your PC.
2. Click the **File** menu in the top left corner.
3. Select **Options** from the left pane.
4. In the PowerPoint Options window, use the left pane to switch to the **Advanced** tab.
5. Scroll down to the **Display** section.
6. Clear the checkboxes that read **Disable hardware graphics acceleration** and **Disable Slide Show hardware graphics acceleration**.
7. Click **OK** to apply the changes.  
![Disable Hardware Acceleration in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-hardware-acceleration-in-powerpoint.jpg)

 Restart PowerPoint after this for changes to take effect.

## 5\. Run the Windows Recording Audio Troubleshooter

 Windows offers several useful troubleshooters for fixing common issues on your computer. In this case, running the Recording Audio troubleshooter can help. It can automatically detect any issues with PowerPoint's audio recording functionality and fix them.

 To run the Recording Audio troubleshooter:

1. Right-click on the **Start** icon and select **Settings** from the list.
2. Navigate to **System > Troubleshoot > Other troubleshooters**.
3. Click the **Run** button next to **Recording Audio**.  
![Recording Audio Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/recording-audio-troubleshooter-on-windows.jpg)

 Allow the troubleshooter to find and fix any issues, and then check if PowerPoint can record the audio.

## 6\. Restart the Windows Audio Services

 Windows relies on certain audio services to capture and record your audio. Typically, these services start automatically every time you boot your computer.

 However, if one of these services encounters any problems, your apps and programs may fail to record the audio. In most cases, you can fix such issues by simply restarting the audio services on your PC.

 To do so, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the search box and select the first result that appears.
3. In the Services window, locate the **Windows Audio** service. Right-click on it and select **Restart**.
4. Similarly, restart the **Windows Audio Endpoint Builder** service as well.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

 Using the Services app isn't the only way to manage services on Windows. You can also use Task Manager, Command Prompt and PowerShell to [start, stop or restart services on Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/).

## 7\. Start PowerPoint in Safe Mode

 One of your add-ins may be acting up and causing PowerPoint to malfunction. To check for this possibility, you need to open PowerPoint in safe mode. For that, press **Win + R** to open the Run dialog box. Type **PowerPnt /safe** in the text field and press **Enter**.

 After opening PowerPoint in safe mode, try creating a screen recording and see if it records audio as expected. If it does, it means one of your add-ins is causing the problem. To identify the one causing the issue, you will need to disable all of your add-ins and then re-enable them one at a time. Here’s how to do that.

1. In PowerPoint, click the **File** menu in the top left corner.
2. Select **Options** in the left pane.
3. In the PowerPoint Options window, switch to the **Add-ins** tab.
4. Click the drop-down menu next to **Manage** and select **COM Add-ins**.
5. Click the **Go** button.
6. Clear the checkboxes to disable add-ins and then click **OK**.  
![Disable Add-ins in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-add-ins-in-powerpoint.jpg)

 Restart PowerPoint after this, and then enable your add-ins one at a time until the issue occurs again. Once you find the faulty add-in, consider removing it.

## 8\. Update Microsoft PowerPoint

 Such issues can also occur if you are using an outdated version of PowerPoint. To update PowerPoint, navigate to **File > Account**. Click on **Update Options** and select **Update Now**.

![Update PowerPoint on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-powerpoint-on-windows.jpg)

 Wait for Microsoft Office to update PowerPoint, and the issue should not occur after that.

## 9\. Run the Office Repair Tool

 If PowerPoint still won’t record audio while recording the screen on Windows, you can run the Office repair tool as a last resort. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **control panel** in the text box and press **Enter**.
3. Click on **Programs and Features**.
4. Locate the **Microsoft Office suite** on the list. Right-click on it and select **Change**.
5. Select the **Quick Repair** option and hit the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, you can run the Office repair tool again to perform an **Online Repair**. Note that this process may take a little longer to complete, as the tool will attempt a more thorough repair.

## Get PowerPoint to Record Your Audio Again on Windows

 It can be frustrating when PowerPoint stops recording audio on your Windows computer. In any case, one of the above tips should help fix the underlying issue for good.

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/reinvigorate-dull-volume-options-in-disk-management-tool/"><u>Reinvigorate Dull Volume Options in Disk Management Tool</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-aural-clarity-unleashed-secrets-to-high-quality-audio/"><u>In 2024, Aural Clarity Unleashed  Secrets to High-Quality Audio</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-ultimate-guide-to-automatic-volume-reduction-audio-ducking-tips-in-adobe-premiere-pro-on-macos/"><u>New In 2024, The Ultimate Guide to Automatic Volume Reduction Audio Ducking Tips in Adobe Premiere Pro on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-for-no-powershell-found-on-your-windows-device/"><u>Remedies for No PowerShell Found on Your Windows Device</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-1011-zoom-glitch-1132/"><u>Overcoming Windows 10/11 Zoom Glitch 1132</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-effortlessly-bypass-pin-in-windows-11-projections/"><u>Navigate Effortlessly: Bypass PIN in Windows 11 Projections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/security-scare-can-you-trust-your-biometric-lock-on-windows/"><u>Security Scare: Can You Trust Your Biometric Lock on Windows?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsoft-copilot-unveiled-revolutionizing-the-development-process/"><u>Microsoft Copilot Unveiled: Revolutionizing the Development Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-your-downloads-with-these-5-windows-clients/"><u>Maximize Your Downloads with These 5 Windows Clients</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-food-for-the-followers-top-tiktok-cuisine-craze/"><u>2024 Approved  Food for the Followers  Top TikTok Cuisine Craze</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-tackle-non-responsive-function-keys-for-brighness-on-windows-11/"><u>Methods to Tackle Non-Responsive Function Keys for Brighness on Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-pinnacle-6-web-based-auditory-dividers-and-snips/"><u>New 2024 Approved Pinnacle 6 Web-Based Auditory Dividers and Snips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-offline-windows-enhancements/"><u>Navigating Offline Windows Enhancements</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-full-compendium-of-podcast-directory-hubs-for-2024/"><u>Updated Full Compendium of Podcast Directory Hubs for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-fullscreen-glitches-with-ease-on-windows/"><u>Navigate Fullscreen Glitches with Ease on Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-fireside-screen-capture-tools/"><u>[New] In 2024, Fireside Screen Capture Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-vivo-x-flip-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Vivo X Flip Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-reinstate-working-state-of-amd-graphics-suite/"><u>Steps to Reinstate Working State of AMD Graphics Suite</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-tablet-navigation-a-guide-to-windows-11s-taskbar/"><u>Optimizing Tablet Navigation: A Guide to Windows 11'S Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-win11s-shopping-crash-error-x800704cf/"><u>Tackling Win11's Shopping Crash: Error X800704CF</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-steam-disk-write-failures-effectively/"><u>Tackling Windows Steam Disk Write Failures Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-workflow-with-top-3d-painting-shortcuts/"><u>Streamline Your Workflow with Top 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-your-systems-core-settings/"><u>Navigating Through Your System's Core Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-doc-file-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .doc file free</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/recognizing-invisible-social-presence-for-2024/"><u>Recognizing Invisible Social Presence for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-nokia-c22-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Nokia C22? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-ideal-methods-to-archive-playstation-4-gaming-sessions/"><u>[Updated] Ideal Methods to Archive PlayStation 4 Gaming Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-superuser-access-a-step-by-step-guide/"><u>Mastering Superuser Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-vivo-x-flip-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Vivo X Flip Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-geforce-experience-settings-retrieval-issues/"><u>Overcoming GeForce Experience Settings Retrieval Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-itel-p55t-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Itel P55T? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-best-comprehensive-recorder-apps-pcmacos/"><u>2024 Approved  Best Comprehensive Recorder Apps - PC/macOS</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-fixes-for-microsoft-store-crash-code-error-0x80072efd/"><u>Swift Fixes for Microsoft Store Crash Code Error 0X80072EFD</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-enhancing-professionalism-blurring-teambackgrounds-effectively/"><u>[Updated] Enhancing Professionalism  Blurring TeamBackgrounds Effectively</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/exclusive-guide-10-immersive-youtube-vr-films/"><u>Exclusive Guide  10 Immersive YouTube VR Films</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-transparent-taskbars-on-win11/"><u>Mastering the Art of Transparent Taskbars on Win11</u></a></li>
</ul></div>
