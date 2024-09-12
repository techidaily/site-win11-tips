---
title: "Overriding Blocked Script Policies: Four Fixes for PS Load Failure"
date: 2024-09-11T01:20:44.898Z
updated: 2024-09-12T01:20:44.898Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overriding Blocked Script Policies: Four Fixes for PS Load Failure"
excerpt: "This Article Describes Overriding Blocked Script Policies: Four Fixes for PS Load Failure"
keywords: Override Blocked Scripts,PS Loading Issue Fix,JS Policy Bypass,Script Execution Error,Webpage Compatibility,Coding Workaround PS,Script Failure Resolution
thumbnail: https://thmb.techidaily.com/0ac17e49979c72a050b377ffc6f63723ef10196944c0e4d0e8d090140eaead92.jpg
---

## Overriding Blocked Script Policies: Four Fixes for PS Load Failure

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

## 2\. Change the Execution Policy in PowerShell

 In some instances, changing the execution policy could help. But before we explore the solutions, let’s first take you through what the execution policy is and how it works.

### What Is the Execution Policy, and How Does It Work?

 The execution policy is a security feature that controls the way you run PowerShell scripts on your device. It simply determines which types of scripts can be run and which ones should be avoided. The best part is that you can configure this policy to your liking.

 Here are the options you can pick from when configuring the execution policy:

* **Restricted**: This policy prohibits you from running any PowerShell script.
* **Unrestricted**: Allows you to run any script but shows you a warning message when you run suspicious scripts.
* **RemoteSigned**: This policy requires a digital signature when you run the scripts that you downloaded online. However, it doesn’t require a signature for local scripts.
* **ByPass**: This allows you to run any script without any restrictions. Unlike the "Unrestricted" policy, the "ByPass" policy won’t show you any warning messages when you run suspicious scripts. So, always apply this policy only when running legit scripts.
* **AllSigned**: This policy only runs scripts that are signed by a trusted publisher.

 Now, if you use PowerShell regularly, then you might want to change the execution policy from time to time. However, some execution policies might display error messages when you run your PowerShell scripts.

 For example, enabling the “Restricted,” “AllSigned,” or “RemoteSigned” policies might lead to error messages like the "running scripts is disabled" error.

 To resolve the problem, you'd simply have to change the execution policy to “Unrestricted” or “ByPass.” But that’s not all; you'd also need to decide how the policy should be implemented. For example, do you want to apply the policy for all users or just for your current PowerShell session?

 Let's explore all the additional [PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) you’ll have to add when changing the execution policy:

* **CurrentUser**: This policy will only be applied to all the PowerShell sessions of the person who has currently logged in on the device.
* **LocalMachine**: Applies to all the users that have an account on the device. This policy can only be configured by local users that have administrative privileges.
* **Process**: Only applies on the current PowerShell session. This means you’ll have to execute the policy again if you start a new session.
* **MachinePolicy**: This policy applies to all the users who have an account on your device. However, it can only be configured by network administrators who have appropriate permissions. But it's often possible for local administrators to configure this execution policy using the Local Group Policy Editor.
* **UserPolicy**: Applies to all PowerShell sessions and the scripts executed by a particular user.

 Now that everything is clear, let’s explore how you can execute the relevant policies to tackle the "PowerShell cannot load" issue.

### How to Change the Execution Policy to "Unrestricted"

 The best way to tackle the issue at hand is to change the execution policy to "unrestricted." But before that, you need to check how each execution policy is configured.

 Here are the steps for checking how the execution policies are configured:

1. Press **Win + X** to open the Quick Access Menu.
2. Select **Windows PowerShell (Admin)** from the options.
3. Type the following command and press **Enter**:

`Get-ExecutionPolicy -List`

![Displaying the list of execution policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/displaying-the-list-of-execution-policies.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137224/26400" target="_top" id="2137224">
  <img src="//a.impactradius-go.com/display-ad/26400-2137224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137224/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 This should show you how the execution policies are configured for different users and systems.

 To can change the execution policy to “Unrestricted” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

![Setting the execution policy on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/setting-the-execution-policy-on-powershell.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 To change the execution policy to “Unrestricted” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope LocalMachine`

 When you finish running the command, close PowerShell and restart your PC to save these changes.





<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




### How to Change the Execution Policy to "ByPass"

 The "ByPass" execution policy will allow you to run any PowerShell script without a hassle. But remember that it might also allow you to run buggy files. So, always configure this execution policy only when running trustworthy PowerShell files.

 To change the execution policy to “ByPass” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope CurrentUser`

 And to change the execution policy to “ByPass” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope LocalMachine`

 When you finish, close PowerShell and then restart your device.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Change the Execution Policy Via the Local Group Policy Editor

![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Change the Execution Policy Using the Registry Editor

![A lady using her Windows PC while sitting on bed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-her-Windows-PC-while-sitting-on-bed.jpg)

 If the other methods didn’t help, then try changing the execution policy using the Registry Editor. However, you need to be careful when editing Registry keys. If you tweak the wrong keys, then you might end up damaging your PC.

 Now, here’s how to change the execution policy via the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell`

 Locate the **ExecutionPolicy** value on the right-hand side.

![Selecting the ExecutionPolicy value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-executionpolicy-value.jpg)

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-a-step-by-step-approach-to-best-youtube-thumbnails-for-2024/"><u>[New] A Step-by-Step Approach to Best YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-8-screen-recording-apps-in-windows-11-revealed/"><u>[New] Top 8 Screen Recording Apps in Windows 11 Revealed</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-your-guide-to-8-best-fb-movies-downloader-selection/"><u>[Updated] 2024 Approved Your Guide to #8 Best FB Movies Downloader Selection</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-installing-tiktok-your-path-to-joyful-macbook-experience-for-2024/"><u>[Updated] Installing TikTok Your Path to Joyful MacBook Experience for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-augmenting-our-perception-an-introduction/"><u>2024 Approved Augmenting Our Perception An Introduction</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamline-your-images-in-canva-without-clutter/"><u>2024 Approved Streamline Your Images in Canva Without Clutter</u></a></li>
<li><a href="https://buynow-info.techidaily.com/anthropics-smart-photo-editor-comprehensive-review-and-user-experience-analysis/"><u>Anthropics Smart Photo Editor: Comprehensive Review & User Experience Analysis</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/changing-instagram-voices-a-step-by-step-guide-for-2024/"><u>Changing Instagram Voices A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/connectivity-made-simple-activating-telnet-in-windows-1011/"><u>Connectivity Made Simple: Activating Telnet in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-options-boot-into-safe-mode-with-6-steps-in-windows-11/"><u>Convenient Options: Boot Into Safe Mode with 6 Steps in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-11s-intricate-data-collection/"><u>Decoding Windows 11'S Intricate Data Collection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dive-into-techniques-preventing-apex-crashes-on-windows-11/"><u>Dive Into Techniques: Preventing Apex Crashes on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-fixes-to-overcome-common-windows-app-errors/"><u>Efficient Fixes to Overcome Common Windows App Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-multitask-management-cascade-windows-with-alt-tab/"><u>Efficient Multitask Management: Cascade Windows with Alt-Tab</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-vintage-films-with-madvr-on-pcs/"><u>Enhancing Vintage Films with MadVR on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-window-monitors-brilliance-with-top-software-for-6-users/"><u>Enhancing Window Monitors' Brilliance with Top Software for 6 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensure-optimal-gaming-performance-with-updated-razer-drivers-for-windows-1187xpvista/"><u>Ensure Optimal Gaming Performance with Updated Razer Drivers for Windows 11/8/7/XP/Vista</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-pc-setup-sticking-gmail-on-the-windows-taskbar/"><u>Essential PC Setup: Sticking Gmail on the Windows Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-system-tools-sfc-chkdsk-and-dissect-wintools-decoded/"><u>Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-silent-speech-problems-for-gamers-playing-on-pc/"><u>Fixing Silent Speech Problems for Gamers Playing on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-unheard-sound-from-devices-on-microsoft-windows/"><u>Fixing Unheard Sound From Devices on Microsoft Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-adjust-admin-managed-chromium-and-microsoft-edge-in-windows/"><u>Guidelines to Adjust Admin-Managed Chromium & Microsoft Edge in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-geforce-now-error-xc0f1103f-in-11/"><u>How to Rectify GeForce Now Error Xc0f1103f in 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-tackle-device-latency-zerodxgierror-in-win11-pcs/"><u>How to Tackle Device Latency ZeroDXGIError in Win11 PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-15-plus-official-method-to-unlock-your-apple-iphone-15-plus-by-drfone-ios/"><u>How To Unlock Apple iPhone 15 Plus Official Method to Unlock Your Apple iPhone 15 Plus</u></a></li>
<li><a href="https://win11-tips.techidaily.com/installing-the-latest-windows-11-arm-via-iso-instructions/"><u>Installing the Latest Windows 11 ARM via ISO Instructions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/judging-the-adequacy-of-windows-11s-visual-extras/"><u>Judging the Adequacy of Windows 11'S Visual Extras</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-your-ghost-hunt-top-solutions-for-phasmophobia-glitches-this-year/"><u>Master Your Ghost Hunt: Top Solutions for Phasmophobia Glitches This Year</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-finesse-your-windows-11-laptops-touch-settings/"><u>Navigate with Finesse: Your Windows 11 Laptop's Touch Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/novices-companion-to-windows-accessibility-features/"><u>Novice's Companion to Windows Accessibility Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-common-winx-update-errors/"><u>Overcoming Common WinX Update Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-high-definition-screen-scale-glitches/"><u>Overcoming High-Definition Screen Scale Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-hurdles-with-windows-1011s-missing-search-output/"><u>Overcoming Hurdles with Windows 10/11'S Missing Search Output</u></a></li>
<li><a href="https://extra-support.techidaily.com/prove-youre-a-pro-lightning-fast-editing-in-windows-11-videos-for-2024/"><u>Prove You're a Pro Lightning-Fast Editing in Windows 11 Videos for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-remedy-for-world-of-warcrafts-fatal-error-132-on-win11/"><u>Quick Remedy for World of Warcraft's Fatal Error 132 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reign-in-windows-stop-unwanted-screen-movement/"><u>Reign In Windows: Stop Unwanted Screen Movement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-old-cursor-color-schemes-tips/"><u>Reviving Old Cursor Color Schemes: Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stealth-meets-practicality-asus-s15-review-analysis/"><u>Stealth Meets Practicality - ASUS S15 Review Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-lower-ntoskrnlexe-usage/"><u>Strategies to Lower Ntoskrnl.exe Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-resolve-disk-usage-errors-in-windows-11-os/"><u>Techniques to Resolve Disk Usage Errors in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-6-best-video-converters-for-windows/"><u>The 6 Best Video Converters for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-pathway-to-efficient-work-implementing-outlook-preview-in-windows-11/"><u>The Pathway to Efficient Work: Implementing Outlook Preview in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-win-11-way-merging-folders-and-files-with-precision/"><u>The Win 11 Way: Merging Folders & Files with Precision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-enhance-slow-execution-of-excel-workbooks-on-windows/"><u>Tips to Enhance Slow Execution of Excel Workbooks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-essential-tips-for-taskbar-users/"><u>Transform Your Workflow: Essential Tips for Taskbar Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-app-setup-utilizing-winstall-in-the-windows-11-landscape/"><u>Transforming App Setup: Utilizing Winstall in the Windows 11 Landscape</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/be-video-magic-comprehensive-editing-for-professionals/"><u>YouTube Video Magic Comprehensive Editing for Professionals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/zero-zoom-full-scroll-mouse-rehabilitation-guide/"><u>Zero Zoom, Full Scroll: Mouse Rehabilitation Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>