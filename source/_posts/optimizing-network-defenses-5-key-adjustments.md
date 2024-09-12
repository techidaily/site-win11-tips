---
title: "Optimizing Network Defenses: 5 Key Adjustments"
date: 2024-09-11T01:22:02.765Z
updated: 2024-09-12T01:22:02.765Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimizing Network Defenses: 5 Key Adjustments"
excerpt: "This Article Describes Optimizing Network Defenses: 5 Key Adjustments"
keywords: NetDefense Optimization,Security Adjustment Guide,Network Guarding Tips,Cyber Safeguard Strategies,Defense Improvement Steps,Secure Network Methods,Protective Defense Tweaks
thumbnail: https://thmb.techidaily.com/f7564240f8faa92ac0e388d789a175a79bd1b95533429025b3702f8272211ea0.jpg
---

## Optimizing Network Defenses: 5 Key Adjustments

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134248/18498" target="_top" id="2134248">
  <img src="//a.impactradius-go.com/display-ad/18498-2134248" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134248/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.





<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-framing-fantasy-elite-tips-for-elevating-your-photography/"><u>[New] In 2024, Framing Fantasy Elite Tips for Elevating Your Photography</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-pinnacle-apps-androids-ultimate-cloud-keepsakes/"><u>[New] Pinnacle Apps Android's Ultimate Cloud Keepsakes</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-precise-age-setting-made-simple-tiktoks-guide/"><u>[New] Precise Age Setting Made Simple TikTok's Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/new-the-insiders-handbook-to-whatsapp-hidden-features-for-2024/"><u>[New] The Insider's Handbook to WhatsApp Hidden Features for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-unintended-tiktok-update-how-to-recover/"><u>[New] Unintended TikTok Update – How to Recover?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-capture-unrooted-sounds-in-android-4-methods/"><u>[Updated] 2024 Approved Capture Unrooted Sounds in Android [4 Methods]</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-high-quality-youtube-recording-techniques/"><u>[Updated] High-Quality YouTube Recording Techniques</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-quickly-locating-your-curated-music-compilation-on-youtube/"><u>[Updated] Quickly Locating Your Curated Music Compilation on Youtube</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-honor-80-pro-straight-screen-edition-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/combat-strategy-for-windows-error-code-0x8007045d/"><u>Combat Strategy for Windows' Error Code: 0X8007045D</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-dual-displays-in-windows-11-easy-guide/"><u>Configuring Dual Displays in Windows 11 Easy Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-missing-display-in-boot-sequence/"><u>Diagnosing Missing Display in Boot Sequence</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/easy-romanian-mastery-in-your-pocket/"><u>Easy Romanian: Mastery in Your Pocket</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-multi-monitor-experience-with-top-window-brightness-controls/"><u>Elevating Your Multi-Monitor Experience with Top Window Brightness Controls</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-intrusive-windows-tracking-systems/"><u>Eliminate Intrusive Windows Tracking Systems</u></a></li>
<li><a href="https://buynow-info.techidaily.com/evaluating-the-microsoft-surface-studio-2-is-its-high-cost-worth-it/"><u>Evaluating the Microsoft Surface Studio 2: Is Its High Cost Worth It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/extend-windows-capacity-safely-and-intelligently/"><u>Extend Windows Capacity Safely & Intelligently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fathom-cpu-peaks-understanding-and-adjusting-with-windows-monitor/"><u>Fathom CPU Peaks: Understanding and Adjusting with Windows Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-errors-with-copypaste-feature-on-windows-11/"><u>Fixing Errors with Copy/Paste Feature on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-black-screen-issue-on-cyberpunk-2077-a-comprehensive-guide/"><u>Fixing the Black Screen Issue on Cyberpunk 2077: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-reboot-loop-into-bios-setup/"><u>Fixing Windows Reboot Loop Into BIOS Setup</u></a></li>
<li><a href="https://driver-install.techidaily.com/free-intel-hdgraphics-520-driver-download/"><u>Free Intel HDGraphics 520 Driver Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacks-to-modify-fixed-sleepwake-modes-in-win11/"><u>Hacks to Modify Fixed Sleep/Wake Modes in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-your-hours-regain-windows-rhythm/"><u>Harmonize Your Hours, Regain Windows Rhythm</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-honor-magic-vs-2-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Honor Magic Vs 2 Phones? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-vivo-x-fold-2-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Vivo X Fold 2 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-sign-out-other-users-on-windows-11/"><u>How to Sign Out Other Users on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/howto-use-biometrics-with-windows-11-for-security/"><u>Howto: Use Biometrics with Windows 11 for Security</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-from-twitter-to-gifs-a-cost-saving-how-to-guide/"><u>In 2024, From Twitter to Gifs A Cost-Saving How-To Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-groundhopping-goals-watch-record-and-cut-games-without-spending/"><u>In 2024, Groundhopping Goals Watch, Record & Cut Games Without Spending</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ipad-pro-vs-macbook-pro-showdown-discover-what-sets-them-apart/"><u>IPad Pro vs MacBook Pro Showdown: Discover What Sets Them Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-fixing-winget-issues-w11-style/"><u>Master the Art of Fixing Winget Issues W11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-issues-with-windows-character-map-functionality/"><u>Overcoming Issues with Windows Character Map Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfectly-positioned-win11s-6-image-rotation-methods/"><u>Perfectly Positioned: Win11's 6 Image Rotation Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-terminal-background-image/"><u>Personalizing Terminal Background Image</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-top-7-ways-to-use-windows-11-smartly/"><u>Propel Productivity: Top 7 Ways to Use Windows 11 Smartly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-razers-controller-fixed-in-w10-and-w11/"><u>Resetting Razer's Controller: Fixed in W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lack-of-hypervisor-in-windows-sandbox-environment/"><u>Resolving Lack of Hypervisor in Windows Sandbox Environment</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-driver-integration-surface-pro-4-on-windows/"><u>Seamless Driver Integration: Surface Pro 4 on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-selection-harnessing-checkboxes-in-windows-11/"><u>Simplifying File Selection: Harnessing Checkboxes in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/speedy-fb-uploads-how-to-get-there-fastest-for-2024/"><u>Speedy FB Uploads How to Get There Fastest for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remove-hyber-v-from-windows-11-pro/"><u>Steps to Remove Hyber-V From Windows 11 Pro</u></a></li>
<li><a href="https://fox-access.techidaily.com/superior-psd-text-direction/"><u>Superior PSD Text Direction</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailoring-your-windows-11-experience-enabling-end-task-on-taskbar/"><u>Tailoring Your Windows 11 Experience: Enabling End Task on Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-cortana-dawn-of-four-alternatives-in-windows/"><u>The End of Cortana, Dawn of Four Alternatives in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-labeling-files-in-windows-11/"><u>The Essential Guide to Labeling Files in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-c0000022-crash-in-windows-os/"><u>Troubleshooting C0000022 Crash in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-office-glitch-resetting-errors/"><u>Troubleshooting Windows Office Glitch: Resetting Errors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-xiaomi-redmi-k70-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Xiaomi Redmi K70 FRP Bypass</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/standing-and-proficiently-implementing-cc-copyrights/"><u>Understanding and Proficiently Implementing CC Copyrights</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-fbm-potential-top-fixes-for-pc-users/"><u>Unlocking FBM Potential: Top Fixes for PC Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/websites-halted-by-hardware-7-windows-fixes-for-browsing-blockades/"><u>Websites Halted by Hardware: 7 Windows Fixes for Browsing Blockades</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-ousting-the-focused-wallpaper-symbol/"><u>Windows 11: Ousting the Focused Wallpaper Symbol</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ram-cache-essentials-and-clearance-guide/"><u>Windows RAM Cache Essentials & Clearance Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-system-lifespan-indicator/"><u>Windows System Lifespan Indicator</u></a></li>
<li><a href="https://win11-tips.techidaily.com/your-own-voice-recognition-tool-building-with-ahk-and-whisper-on-windows/"><u>Your Own Voice Recognition Tool: Building with AHK and Whisper on Windows</u></a></li>
</ul></div>




