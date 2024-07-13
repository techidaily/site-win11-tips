---
title: "Windows Watchlist: Spot the Red Flags in These 7 Tasks"
date: 2024-07-12T17:36:38.770Z
updated: 2024-07-13T17:36:38.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Watchlist: Spot the Red Flags in These 7 Tasks"
excerpt: "This Article Describes Windows Watchlist: Spot the Red Flags in These 7 Tasks"
keywords: Red Flag Tasks Windows,Watchlist Windows Tips,Identify Risks Windows,Spotting Security Vulnerabilities,Windows Task Alerts,Detecting Threats in Windows,Recognizing Unsafe Windows Actions
thumbnail: https://thmb.techidaily.com/c4e970c61c745a22a93f179d1f650cdbb34448ec2a9158efa033c2403816542e.jpg
---

## Windows Watchlist: Spot the Red Flags in These 7 Tasks

 Processes are an unavoidable part of Windows, and it is not unusual to see dozens or hundreds of them in Task Manager. Each process is a program or part of a program that is running. Unfortunately, malware creators know this and are known to hide malicious software behind the names of legitimate processes.

 Here are some of the most commonly hijacked or duplicated processes, along with where they should be located and how to spot a malicious version.

## 1\. Svchost.exe

 The Service Host, or svchost.exe, is a shared-service process. It allows various other Windows services to share processes. This helps to reduce resource usage, making the system more efficient. You will almost certainly see more than one instance of Svchost.exe in Task Manager, but this is normal. If one or more of these files are compromised by malware, you may notice a distinct reduction in performance.

![the svchost process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/svchost-process.jpg)

 The legitimate Svchost files should be found in**C:\\Windows\\System32** . If you suspect it has been hijacked, check**C:\\Windows\\Temp** . If you see svchost.exe here, it could be a malicious file. Scan the file with your antivirus software, and quarantine it if necessary.

## 2\. Explorer.exe

 Explorer.exe is responsible for the graphical shell. Without it, you would have no Taskbar, Start Menu, File Manager, or even the Desktop. Therefore, it is an essential part of Windows and cannot be disabled.

 Several viruses can use the Explorer.exe filename to hide behind, including trojan.w32.ZAPCHAST. The legitimate file will be in**C:\\Windows** . If you find it in**System32** , you should definitely check it with your antivirus software.

## 3\. Winlogon.exe

 The Winlogon.exe process is an essential part of the Windows OS. It handles things like loading the user profile during login and locking the computer when the screensaver runs. Unfortunately, because it handles security elements, Windows Logon and the winlogon.exe process are common targets for threats.

 Several Trojan viruses, including Vundo, can be hidden within or disguised as winlogon.exe. The usual location of the Winlogon.exe file is**C:\\Windows\\System32** . If you find it in**C:\\Windows\\WinSecurity** , it could be malicious. One good indication that the process has been hijacked is unusually high memory use.

 Viruses and malware don't just hide behind Windows processes. Here are some [other ways malware can go undetected and hide on your computer](https://www.makeuseof.com/can-malware-go-undetected-how-viruses-hide-from-you/) .

## 4\. Csrss.exe

 The Client/Server Run-Time Subsystem, or Csrss.exe, is an essential Windows process. Although it is not as widely used in modern Windows versions, it is still required by the system and cannot be disabled.

![The csrss process file in folder location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/csrss-process.jpg)

 The Nimda.E virus has been known to mimic the Csrss.exe process, although that is not the only potential threat. The legitimate file should be located in the**System32** or**SysWOW64** folders. Right-click on the Csrss.exe process in Task Manager and choose**Open File Location** . If it is located anywhere else, it is likely to be a malicious file.

## 5\. Lsass.exe

 lsass.exe is an essential process responsible for the security policy on Windows. It verifies the login name and password, among other security procedures. It is unlikely that the process will be hijacked. If it isn't running correctly, you will usually be automatically logged out of your computer. But viruses are known to use the filename to hide.

 Look for the Lsass.exe file in**C:\\Windows\\System32** . This is the only place you should find it. If you see it in another location, such as**C:\\Windows\\system** or**C:\\Program Files** , act with suspicion and scan the file with your antivirus.

## 6\. Services.exe

 The Services.exe process is responsible for starting and stopping various essential Windows services. Like the other Windows processes in this list, viruses and malware target it because it allows them to hide in plain sight.

 If the file is hijacked, you may notice problems during the startup and shutdown of your PC. Look for the real Services.exe file in the**System32** folder. If it is located anywhere else, such as in**C:\\Windows\\ConnectionStatus** , the file could be a virus.

 The processes mentioned here are essential to the smooth running of Windows. But not all are, and many non-essential [processes can even be closed to help with performance](https://www.makeuseof.com/windows-processes-end-safely-performance/) .

## 7\. Spoolsv.exe

 The Windows Print Spooler Service, or Spoolsv.exe, is an important part of the printing interface. It runs in the background, waiting to manage things like the print queue when required. The process is not dependent on having a printer connected, so you shouldn't be surprised to see it in Task Manager.

![The spooler process in task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/spooler-process.jpg)

 Perhaps because Spoolsv.exe is easily overlooked, a virus can take the name to make itself seem legitimate. The true spools file can be found in**C:\\Windows\\System32** . The fake file will often appear in**C:\\Windows** , or in a user profile folder.

## How Do You Check if a Process Is Legitimate?

 The Task Manager is your friend when looking for suspicious activity. Infected processes will often behave erratically, consuming more CPU power and memory than is usual. But that isn't always the case, so here are some other ways to check a process is legitimate.

 Most of the essential processes listed here should only appear in the System32 folder. You can easily check the location of a suspicious file in the Task Manager. Right-click on the process and select**Open File Location** . Check the path of the folder that opens to ensure the file is in the correct place.

 Another way to tell if a file is legitimate is to check the size. Most of the .exe files of these essential processes will be under 200kb. Right-click on the process name in Task Manager, select**Properties** and look at the size. If it seems unusually large, take a closer look to determine if it is safe.

 You can also [check the certificate of the EXE file](https://www.makeuseof.com/windows-tell-if-exe-file-is-safe/) . An authentic file will have a security certificate issued by Microsoft. If you see anything else, it is likely to be malicious.

 The final thing to do is scan suspect files with an up-to-date antivirus scanner. Quarantine and remove any files that are flagged as infected. Fortunately, modern versions of Windows come with Microsoft Defender built-in, so learn [how to scan a single file or folder with Microsoft Defender](https://www.makeuseof.com/microsoft-defender-scan-file-folder/) to check any suspicious files you find.

## The Windows Processes That Might Be Hiding a Virus

 Part of keeping your Windows PC safe from malware and viruses is knowing where they hide. Sometimes a malicious file will behave oddly, using too much CPU and memory. But not always. So spotting a suspicious file in other ways is a useful skill.


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
<li><a href="https://some-knowledge.techidaily.com/updated-in-depth-cost-analysis-for-new-podcasters/"><u>[Updated] In-Depth Cost Analysis for New Podcasters</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-soundless-videos-the-quintessential-methods-to-ditch-noise-online/"><u>Updated 2024 Approved Soundless Videos The Quintessential Methods to Ditch Noise Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-search-for-program-install-spots-on-pc/"><u>Mastering the Search for Program Install Spots on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exe-and-msi-dissecting-software-package-variations/"><u>EXE and MSI: Dissecting Software Package Variations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recommended-procedures-for-dying-wireless-controller/"><u>Recommended Procedures for Dying Wireless Controller</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-clipchamps-windows-11-install-troubles/"><u>Navigate Through ClipChamp's Windows 11 Install Troubles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-in-the-classroom-best-practices-and-tips-for-educators/"><u>2024 Approved  YouTube in the Classroom  Best Practices and Tips for Educators</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-pick-a-perfect-virtual-reality-device-evaluating-portability-mobile-versus-connected-experience/"><u>In 2024, How to Pick a Perfect Virtual Reality Device  Evaluating Portability (Mobile) Versus Connected Experience</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-from-novice-to-nifty-mastering-snapchats-digital-artistry/"><u>[New] From Novice to Nifty  Mastering Snapchat’s Digital Artistry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/new-ai-feature-on-windows-11-microsofts-taskbar-assistant-revolutionizes-productivity/"><u>New AI Feature on Windows 11: Microsoft's Taskbar Assistant Revolutionizes Productivity</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-bridging-the-gap-between-standard-and-superior-video-quality-techniques/"><u>In 2024, Bridging the Gap Between Standard and Superior Video Quality Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-undetermined-value-messages-on-windows/"><u>Solutions for 'Undetermined' Value Messages on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-managed-users-and-groups-in-win1110-homes/"><u>Enabling Managed Users and Groups in Win11/10 Homes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-folder-management-resetting-critical-components-on-ws11/"><u>Effortless Folder Management: Resetting Critical Components on WS11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-10-most-retweeted-tiktok-sensations/"><u>[New] 10 Most Retweeted TikTok Sensations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fast-tracking-your-creative-spark-with-google-images-art-for-2024/"><u>Fast-Tracking Your Creative Spark with Google Images Art for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unveiling-the-simplicity-accessing-highly-engaged-youtube-reactions/"><u>In 2024, Unveiling the Simplicity  Accessing Highly Engaged YouTube Reactions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-dissecting-the-distinctions-triller-vs-tiktoks-interface-max-156-chars-for-2024/"><u>[New] Dissecting the Distinctions  Triller V/S TikTok's Interface (Max 156 Chars) for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/enhancing-streaming-quality-using-obs-plus-zoom/"><u>Enhancing Streaming Quality Using OBS + Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/instructions-for-resetting-customized-windows-settings/"><u>Instructions for Resetting Customized Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-internal-rdp-problems-on-windows-os/"><u>Eliminating Internal RDP Problems on Windows OS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-comprehensive-guide-to-showmores-efficient-recording-tools/"><u>[New] Comprehensive Guide to ShowMore's Efficient Recording Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improve-your-workflow-dealing-with-external-monitor-lag-in-windows/"><u>Improve Your Workflow: Dealing with External Monitor Lag in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-clear-desktop-instructions-for-windows-recycle-bin-auto-empty/"><u>Master Clear Desktop: Instructions for Windows Recycle Bin Auto-Empty</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-breaking-into-the-world-of-social-broadcasts-and-roku/"><u>In 2024, Breaking Into the World of Social Broadcasts & Roku</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-record-sound-on-mac-5-useful-tips-for-you/"><u>Updated How to Record Sound on Mac? 5 Useful Tips for You</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-books-8-effective-studying-tips-on-windows/"><u>Mastering the Books: 8 Effective Studying Tips on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-free-extension-software-leaders-in-chromebook-video-recording-for-2024/"><u>[Updated] Free Extension Software Leaders in Chromebook Video Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-iomap64-syscall-failures-on-windows-pcs/"><u>Essential Fixes for IOMap64 Syscall Failures on Windows PCs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-master-the-art-of-subtitling-a-brief-blueprint-for-your-fb-video-uploads/"><u>[New] 2024 Approved  Master the Art of Subtitling  A Brief Blueprint for Your FB Video Uploads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-program-harmony-in-os-with-win-pct-wisdom/"><u>Master Program Harmony in OS with Win-PCT Wisdom</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-engineers-choice-selecting-premium-websites-for-advanced-mp3-editing-techniques-for-2024/"><u>The Engineers Choice Selecting Premium Websites for Advanced MP3 Editing Techniques for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-file-operations-in-powershell-and-command-prompt/"><u>Optimizing File Operations in PowerShell & Command Prompt</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-freenoweb-cam-app-assessment-and-comparison-guide/"><u>2024 Approved  FreenoWeb Cam App Assessment & Comparison Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-stop-microsoft-edges-from-popping-up/"><u>How to Stop Microsoft Edges From Popping Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-workings-of-windows-odbc-tools/"><u>Insight Into the Workings of Windows ODBC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-record-windows-uac-notifications/"><u>Quick Steps to Record Windows UAC Notifications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-greyed-out-waste-bin-icon-in-win11/"><u>Restoring Greyed Out Waste Bin Icon in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snip-and-sketch-vs-prtsc-which-screen-capture-wins/"><u>Snip & Sketch Vs. PrtSc: Which Screen Capture Wins?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-how-to-add-audio-to-quicktime-video-files/"><u>New How to Add Audio to QuickTime Video Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-window-11-settings-for-clear-prime-video-texts/"><u>Harmonize Window 11 Settings for Clear Prime Video Texts</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-8-gold-text-wonders-in-the-vast-world-of-3d-sites/"><u>[Updated] Top 8 Gold-Text Wonders in the Vast World of 3D Sites</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-best-funny-fictional-frequencies-for-2024/"><u>The Best Funny Fictional Frequencies for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/1715859704084-2024-approved-capture-share-enjoy/"><u>2024 Approved  Capture, Share, Enjoy!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-administrative-controls-on-windows-defense-measures/"><u>Reversing Administrative Controls on Windows Defense Measures</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-ultimate-guide-top-50plus-inspiring-lyrics-for-tiktok-creators/"><u>[New] The Ultimate Guide  Top 50+ Inspiring Lyrics for TikTok Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-windows-11-with-an-older-windows-7-product-key/"><u>Launching Windows 11 with an Older Windows 7 Product Key</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/proven-strategies-for-device-screening-for-2024/"><u>Proven Strategies for Device Screening for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-win11s-alarming-zero-error-alerts/"><u>How to Bypass Win11’s Alarming Zero Error Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/immediate-actions-for-local-security-not-functioning-warning/"><u>Immediate Actions for 'Local Security Not Functioning' Warning</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-measures-for-eradicating-white-screens-in-win1011/"><u>Efficient Measures for Eradicating White Screens in WIN10/11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-video-structure-a-comprehensive-guide-to-chapter-addition-on-youtube/"><u>Mastering Video Structure  A Comprehensive Guide to Chapter Addition on YouTube</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-action-optimize-your-windows-system-against-high-ums-use/"><u>Efficiency in Action: Optimize Your Windows System Against High UMS Use</u></a></li>
<li><a href="https://win11-tips.techidaily.com/opera-installer-lockdown-try-these-window-tips/"><u>Opera Installer Lockdown? Try These Window Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-utorrent-install-issues-on-a-windows-laptop/"><u>Navigating uTorrent Install Issues on a Windows Laptop</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-precision-and-power-top-5-text-plugins-for-after-effects-creativity-for-2024/"><u>[Updated] Precision and Power  Top 5 Text Plugins for After Effects Creativity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-shortcuts-for-windows-photos-enthusiasts/"><u>Innovative Shortcuts for Windows Photos Enthusiasts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-perfecting-proportions-understanding-youtube-video-sizes/"><u>2024 Approved  Perfecting Proportions  Understanding YouTube Video Sizes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speak-write-and-transform-an-intuitive-guide-to-text-generation-with-windows-whisper/"><u>Speak, Write and Transform: An Intuitive Guide to Text Generation with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-nullify-audio-amplification-in-windows/"><u>Guide to Nullify Audio Amplification in Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-infinix-zero-5g-2023-turbo-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Infinix Zero 5G 2023 Turbo Devices</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-adventure-in-sync-reviewing-the-panasonic-hx-a1-cam/"><u>2024 Approved  Adventure in Sync  Reviewing the Panasonic HX-A1 Cam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-golden-grounds-guided-the-finest-treasure-maps-for-2024/"><u>[Updated] Golden Grounds Guided  The Finest Treasure Maps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips.</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-essential-fcpx-add-ons-top-10-free-and-paid-plugins-you-need-for-2024/"><u>Updated Essential FCPX Add-Ons Top 10 Free and Paid Plugins You Need for 2024</u></a></li>
</ul></div>
