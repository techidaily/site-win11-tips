---
title: Navigate & Optimize PowerShell's Execution Policy Landscape
date: 2024-09-05T19:32:02.899Z
updated: 2024-09-06T19:32:02.899Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate & Optimize PowerShell's Execution Policy Landscape
excerpt: This Article Describes Navigate & Optimize PowerShell's Execution Policy Landscape
keywords: PSExecutionPolicyOptimization,ExecutionPolicyNavigation,PowerShellSecuritySettings,SecureScriptManagement,ScriptPolicyCustomization,EnhancePSExecPolicy,OptimizePowerShellRunTime
thumbnail: https://thmb.techidaily.com/1ce0f809b5f53bee55ecc4e59e4fc7fd703e674d56363d25b6490a7057e74118.jpg
---

## Navigate & Optimize PowerShell's Execution Policy Landscape

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check Your Existing Execution Policy

![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114264/17093" target="_top" id="2114264">
  <img src="//a.impactradius-go.com/display-ad/17093-2114264" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114264/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell

![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You can use a[PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell

![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.


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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-directing-traffic-from-tiktok-to-twitter/"><u>[New] 2024 Approved  Directing Traffic From TikTok to Twitter</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-foremost-frame-openers-identifying-the-most-effective-16-youtube-intros/"><u>[New] 2024 Approved  Foremost Frame Openers  Identifying the Most Effective 16 YouTube Intros</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-examining-obss-recording-features-in-detail/"><u>[New] In 2024, Examining OBS's Recording Features in Detail</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-frame-tools-and-websites-image-editors/"><u>[New] Innovative Frame Tools and Websites Image Editors</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-iphone-video-editing-showdown-cameo-against-filmorago/"><u>[New] IPhone Video Editing Showdown  Cameo Against FilmoraGo</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-role-of-competitive-intelligence-in-effective-market-research/"><u>[New] The Role of Competitive Intelligence in Effective Market Research</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-a-decade-of-digital-disguise-expert-tips-on-snapchat-filters-for-2024/"><u>[Updated] A Decade of Digital Disguise  Expert Tips on Snapchat Filters for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-alpine-adventure-2022s-spectacular-snowboard-cross-olympic-moments/"><u>[Updated] In 2024, Alpine Adventure  2022'S Spectacular Snowboard Cross Olympic Moments</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-blending-beats-and-visuals-a-tutorial-on-youtube-music-addition/"><u>[Updated] In 2024, Blending Beats and Visuals  A Tutorial on YouTube Music Addition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-seamless-igtv-and-fb-sharing-guide/"><u>[Updated] In 2024, Seamless IGTV and FB Sharing Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-tailored-viewing-experience-constructing-a-personalized-watch-later-list/"><u>[Updated] In 2024, Tailored Viewing Experience  Constructing a Personalized 'Watch Later' List</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtubes-flawless-beauty-masterclass-skincare-hairdos-and-cosmetics-for-2024/"><u>[Updated] YouTube's Flawless Beauty Masterclass  Skincare, Hairdos & Cosmetics for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-branding-beyond-words-eye-catching-podcast-graphics/"><u>2024 Approved  Branding Beyond Words  Eye-Catching Podcast Graphics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-0x0-error-essential-fixes-for-win11-users/"><u>Conquer the 0X0 Error: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-e1-for-surface-go-win10/"><u>Correcting Error E1 for Surface Go (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-the-easy-way-to-identify-ram/"><u>Decoding Windows Memory: The Easy Way to Identify RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discovering-hidden-patterns-in-data-usage-through-windows-diskusage-command/"><u>Discovering Hidden Patterns in Data Usage Through Windows' DiskUsage Command</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhancing-audio-quality-on-spotify-quickly-and-safely/"><u>Enhancing Audio Quality on Spotify Quickly & Safely</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-apps-for-modern-computing/"><u>Essential Non-Windows Apps For Modern Computing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/experience-legendary-ps3-gaming-on-your-pc-today-for-2024/"><u>Experience Legendary PS3 Gaming on Your PC Today for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722991326994-fixing-madden-22-stalling-issue-at-launch-proven-methods-to-get-playing-asap/"><u>Fixing Madden 22 Stalling Issue at Launch - Proven Methods to Get Playing ASAP!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-opengl-issue-3-with-nvidia-on-windows-11-os/"><u>Fixing OpenGL Issue #3 with NVIDIA on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-through-the-maze-of-windows-10-crash-modes/"><u>Guide Through the Maze of Windows 10 Crash Modes</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-critical-js-error-affecting-discord-on-modern-windows-devices/"><u>How to Resolve Critical JS Error Affecting Discord on Modern Windows Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-vivo-v30-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Vivo V30 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-best-free-video-watermarking-tools-top-picks/"><u>In 2024, Best Free Video Watermarking Tools Top Picks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-executing-powerful-registry-changes-via-terminal/"><u>In-Depth Analysis: Executing Powerful Registry Changes via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-quick-assistance-on-windows-11/"><u>Initiating Quick Assistance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-vcplusplus-redistributable-needs/"><u>Insight Into VC++ Redistributable Needs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/language-leap-forward-fastest-to-learn-global-languages/"><u>Language Leap Forward: Fastest-to-Learn Global Languages</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-desktop-art-windows-1011-tutorials/"><u>Mastering Desktop Art: Windows 10/11 Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-fix-loaded-lol-screens/"><u>Mastering Windows: Fix Loaded LOL Screens</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/maximizing-twitter-video-quality-full-hd-tips/"><u>Maximizing Twitter Video Quality  Full HD Tips</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-alternatives-to-gopro-quik-for-pc-video-editing-made-easy/"><u>New 2024 Approved Alternatives to GoPro Quik for PC Video Editing Made Easy</u></a></li>
<li><a href="https://ai-video.techidaily.com/new-how-to-translate-audiovideo-content-from-spanish-to-english-and-vice-versa/"><u>New How to Translate Audio/Video Content From Spanish to English and Vice Versa?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-windows-inbuilt-pdf-renderer/"><u>Personalizing Windows' Inbuilt PDF Renderer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-privacy-the-ultimate-windows-encryption-list-152-chars/"><u>Protecting Privacy: The Ultimate Window's Encryption List (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-for-wow-gamers/"><u>Restoring Online Status for WoW Gamers</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-universal-adb-driver-availability-here/"><u>Seamless Universal ADB Driver Availability Here</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-mobility-center-stay-in-full-screen/"><u>Sidestep Mobility Center, Stay In Full Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snapping-into-action-activate-snipping-tool-in-windows-11/"><u>Snapping Into Action: Activate Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-dealing-with-immutable-energy-states-in-windows-11/"><u>Solutions for Dealing with Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-security-for-browsers-trustable-sites-in-windows-11/"><u>Tailored Security for Browsers: Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-excessive-system-update-notifications-in-windows-11/"><u>Tame Excessive System Update Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-fix-errors-with-windows-alt-codes/"><u>Techniques to Fix Errors with Windows ALT Codes</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-unblock-overloaded-gpt-windows-errors/"><u>Tips to Unblock Overloaded GPT Windows Errors</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/transform-your-word-files-into-ebooks-a-step-by-steps-guide-with-calibres-conversion-tool/"><u>Transform Your Word Files Into eBooks: A Step-by-Steps Guide with Calibre's Conversion Tool</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-steps-when-your-squad-microphone-fails/"><u>Troubleshooting Steps: When Your Squad Microphone Fails</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-bar-icon-failures/"><u>Troubleshooting Windows Bar Icon Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-your-pcs-touchpad-response-speed/"><u>Tweaking Your PC's Touchpad Response Speed</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723001571064-ultimate-tricks-for-fluid-gameplay-in-the-ascent-enhance-stutter-free-experience-and-elevate-fps/"><u>Ultimate Tricks for Fluid Gameplay in The Ascent – Enhance Stutter-Free Experience & Elevate FPS!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-code-0x80780119-restore-mishap/"><u>Unraveling Windows' Code 0X80780119 Restore Mishap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-start-button-revived-an-instruction-guide/"><u>Windows Start Button Revived: An Instruction Guide</u></a></li>
</ul></div>
