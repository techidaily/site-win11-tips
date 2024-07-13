---
title: Addressing Frozen Windows Guard in Windows 11
date: 2024-07-12T17:50:33.790Z
updated: 2024-07-13T17:50:33.790Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Frozen Windows Guard in Windows 11
excerpt: This Article Describes Addressing Frozen Windows Guard in Windows 11
keywords: Freezing Fixes for Win11,Guard Lock in Win11,Thaw Win11 Frostware,Rescue Window XP 11,Defrosting Win11 Guard,Windows 11 Freeze Remedy,Unfreeze Win11 Protection
thumbnail: https://thmb.techidaily.com/33028f93fa14d69bbcfce2acf14136a66954cb281abb62aff639869e465c0177.jpg
---

## Addressing Frozen Windows Guard in Windows 11

 Windows Security is a free and default antivirus program provided by Microsoft to protect your PC from outside threats. However, there are times when the security software might stop working properly, or in some cases, not start at all. And to top off, if you’re also not using a third-party antivirus app, you're basically wide open to a myriad of security attacks.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.

## 1\. Turn on Windows Security

 In rare cases when a PC undergoes a malicious attack one of the first things that the malicious program does is [turn off all the antivirus defenses like Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/). If your PC has undergone such an attack recently, then it might be possible that you're facing the same issue.

 If that's indeed the case then you'll have to manually enable Windows Security on your PC. Follow these steps to continue:

1. Head to the **Start menu** search bar, type in 'security,' and select the best match.
2. From there, click on **Turn on** to enable the **Virus & threat protection** of your PC.
3. A new dialog box will pop up asking you to confirm if you want to go ahead with the changes; click on **Yes** to proceed.

![security at glance menu in windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-security.jpg)

 The Windows Security app will be enabled instantly.

## 2\. Update Windows 11

 How long has it been since you last updated your Windows? If it’s been a while, it might be a good time to brush off the dust from your updates.

 Follow these steps to check for updates on your Windows PC:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match. Alternatively, press **Win + I** together.
2. Scroll down and select **Windows Update**.
3. Now click on **Check for updates** and Windows will start checking for updates on your PC. (If any new updates are available, they’ll be displayed on the **Windows Update** screen.)
4. Finally, click on **Download & install** to get the ball rolling.

![windows update section in the settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/windows-update-1.png)

 When the updates download is complete, give your PC a quick restart and see if the problem with Windows Security persists. If it does, then jump below to the next method.

## 3\. Disable Third-Party Antivirus

 If you have an additional antivirus installed on your PC, it might be a good time to get rid of it.

 Running Windows Security along with third-party antivirus apps has been known to cause many kinds of disruption in Windows computers. So removing the additional antivirus might, in fact, be a fair approach—remove the antivirus and see if it can get everything back to normal.

 To get started, launch the **Settings** again. Go to **Apps > Apps & features**, search for the antivirus, and when you find it, click on options (three dots) and select **Uninstall**.

![apps and features in the apps settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps-and-feature.png)

 The third-party antivirus will be removed. Now restart your Windows 11 and see if the problem with Windows Security persists. It shouldn’t.

## 4\. Reset the Windows Security App

 Removing the third-party antivirus app from your PC should get your Windows Security back to work in most cases. However, in cases where it's not, it might be time to do a complete reset of your Security app.

 Follow these steps to reset the Windows Security app:

1. Go to the **Settings** menu again by pressing the **Windows key + I**.
2. Select **App > Apps & features** and type in ‘security’ in the search menu box.
3. An icon for Windows Security will pop open. From there, click on the **options** (three dots) and select **Advanced options**.
4. Now scroll down to **Reset** section and click on **Reset**.

 You’ll get a confirmation asking if you really want to reset the app, along with your whole app data. Click on **Reset** to go with it.

![reset and repair option in the windows security settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-and-repair.jpg)

 You can also try the **Repair** option if you don't want to reset the app right off. It’s right there above the **Reset** option. As soon you click on **Repair**, the process will begin. When the Repair is complete, it’ll leave a tick option adjacent to **Repair** box.

## 5\. Run an SFC and DISM Scan

 SFC, short for System File Checker, is a Windows utility that can be fallen back upon when some of your Windows files malfunction. In short, it checks for file corruption and then tries to repair it.

 It is accessed through the Command prompt. To get started, go to the **Start menu** search bar, type in ‘command prompt,’ and then launch it as administrator.

 This launches your Command prompt in an elevated mode, something necessary to run the SFC utility.

 In the Command prompt, type the following command and hit **Enter**:

`sfc/ scannow`

 The tool will scan your PC and you should be able to run the Security app by the end.

![execution of sfc scan in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/sfc-scan-in-command-prompt.png)

 If the SFC tool doesn't work, don't fret just yet. Another tool that you can try your luck with is the DISM; it's not the same as SFC, but it works almost similarly. You can check out the [differences between SFC and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) if you'd like to learn more.

 Much like how the SFC tool helps you fix your PC, a DISM scan finds and fixes any issues with your system image that might be causing problems with your PC's functioning.

 Like with SFC scan above, you’ll have to launch the DISM as an administrator as well. Go to the **Start menu,** type in ‘DISM,’ and run it as administrator. When you launch the DISM scan, enter the following command and hit **Enter**:

`DISM /Online /Cleanup-Image /ScanHealth`

![execution of dsim scan in the command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/dsim-scan-command-prompt.png)

 As soon as the command finishes executing, your files would've been scanned and all the corruption issues would most possibly have been resolved.

 When you’re done, [simply restart your PC](https://www.makeuseof.com/windows-restart-methods/) for the changes to take effect, and see if the problem persists.

## 6\. Restart the Windows Security Service

 Windows Security makes use of a host of programs and services for smooth functioning on your PC. One of those handy services is the Windows Security Center service which monitors the security state of the important components of your system.

 So, if your Windows Security app stopped opening, or if it crashed midway, we suggest you restart your Windows Security Center Service right away. To get started, follow the steps below:

1. Press **Win + R** and type "services.msc" and hit the Enter key.
2. Here, scroll down to find and right-click on **Security-Center** and then select **Restart**.

![security services process in the services app on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-app-windows-11.jpg)

 That's it. Follow any other on-screen instructions and wait for the service to reboot of the service. When that's done, restart your PC and the Windows Security service will be fixed by the next boot-up.

## 7\. Reset Your PC

 A panacea for almost all [the common Windows bugs](https://www.makeuseof.com/common-windows-11-problems/), the **Reset Your PC** setting resets your computer and brings it to its initial state. It’s far better than reinstalling the whole Windows, as you can reset your PC while also keeping your personal files and folders intact.

 To get started, follow the steps below:

1. Go to the **Start menu** search bar, type in ‘settings,’ and select the Best match.
2. In the **Settings** menu, click on **System > Recovery**.
3. In the **Recovery options** tab, click on Reset PC.
4. Then select **Keep my files > Local reinstall** and click on **Next**.

![two types of reset options in the reset this pc on windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/reset-this-pc-windows-11.png)

 That’s it. Follow the onscreen instructions ahead and your Windows will be formatted and reinstalled in no time. When your PC restarts, all your settings will be at ground zero again.

 The whole process is fairly straightforward, but if you face any difficulties during the reset, make sure you go through a [complete guide on Windows 10 factory reset](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) and verify if you're making any slip-ups in between the steps.

## Fixing the Issues With Windows Security

 Windows Security is a must-have for Windows health. However, the app can sometimes malfunction and stop working properly. Hopefully, one of the methods laid out above helped you get it working once again.

 But that's not all; There are a ton of ways you can dial up your PC’s security, so make sure you aren’t simply relying only on Windows security for your PC's cyber protection.

 It's therefore crucial that Windows security is working at its best; this will keep your computer security airtight. In this article, we’ve laid down some of the best tricks that will help you fix Windows Security on your Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/ephemeral-approach-to-suspending-windows-11-protection-systems/"><u>Ephemeral Approach to Suspending Windows 11 Protection Systems</u></a></li>
<li><a href="https://extra-support.techidaily.com/best-methods-to-try-for-changing-playback-speed-in-spotify-for-2024/"><u>Best Methods to Try for Changing Playback Speed in Spotify for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/4-things-to-try-when-prime-videos-subtitles-arent-working-on-windows-11/"><u>4 Things to Try When Prime Video's Subtitles Aren't Working on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlock-lunapics-secret-to-stunning-visuals/"><u>Unlock LunaPic's Secret to Stunning Visuals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-of-runtime-brokers-in-computing/"><u>Unraveling the Mystery of Runtime Brokers in Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disentangle-onedrive-and-microsoft-account-on-windows-machine/"><u>Disentangle OneDrive & Microsoft Account on Windows Machine</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-leveraging-fb-instream-ad-techniques-to-boost-engagement/"><u>In 2024, Leveraging FB Instream Ad Techniques to Boost Engagement</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-photoshop-shake-reduction-is-it-really-useful/"><u>[Updated] Photoshop Shake Reduction - Is It Really Useful?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-fix-youtube-video-black-screen-for-2024/"><u>How to Fix YouTube Video Black Screen for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-to-instant-uninstalling-via-windows-shortcuts/"><u>The Guide to Instant Uninstalling via Windows Shortcuts</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-exploring-high-res-videography-with-nikon-j5/"><u>[New] In 2024, Exploring High-Res Videography with Nikon J5</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-best-free-video-calls-featuring-screen-sharing-roundup/"><u>2024 Approved  Best Free Video Calls Featuring Screen Sharing Roundup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-overcapacity-alerts-for-gpt-service/"><u>Counteracting Overcapacity Alerts for GPT Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-hidden-perils-behind-budget-windows-activation-codes/"><u>The Hidden Perils Behind Budget Windows Activation Codes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/explore-top-7-live-streaming-iosandroid-apps-perfect-for-youtube-channel-creators-for-2024/"><u>Explore Top 7 Live Streaming iOS/Android Apps Perfect for YouTube Channel Creators for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-altering-window-icons-distance-on-11plus-windows/"><u>Title: Altering Window Icons' Distance on 11+ Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-5-best-pc-optimization-tools-on-a-windows-pc/"><u>The 5 Best PC Optimization Tools on a Windows PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-improve-chromium-performance-fb-video-streaming/"><u>[Updated] Improve Chromium Performance  FB Video Streaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-the-reset-failure-count-for-incorrect-login-attempts-on-windows-11/"><u>Configuring the Reset Failure Count for Incorrect Login Attempts on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-closer-look-at-ais-individuality-and-innovation/"><u>A Closer Look at AI's Individuality and Innovation</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-oppo-a1-5g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Oppo A1 5G Without PUK Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparative-analysis-understanding-the-variance-between-non-microsoft-and-microsoft-account-in-os/"><u>Comparative Analysis: Understanding the Variance Between Non-Microsoft and Microsoft Account in OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-idea-to-recording-a-comprehensive-guide-to-podcast-scripting-for-2024/"><u>From Idea to Recording  A Comprehensive Guide to Podcast Scripting for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-ultimate-app-review-for-crafting-unique-reels/"><u>2024 Approved  The Ultimate App Review for Crafting Unique Reels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diagnosing-win-pcs-voice-input-problems/"><u>Diagnosing Win PCs' Voice Input Problems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-cross-platform-movie-recording-pc-mac-and-mobile/"><u>[Updated] Cross-Platform Movie Recording  PC, Mac & Mobile</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-popular-rainmeter-problems-in-windows-systems/"><u>Troubleshooting Popular Rainmeter Problems in Windows Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-pausecapture-stop-and-save-live-image-for-2024/"><u>[New] PauseCapture  Stop & Save Live Image for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resize-windows-monitor-in-win-10/"><u>Resize Windows Monitor in WIN 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-try-now-bluetooth-hurdle-on-pcs-and-tablets/"><u>Bypass 'Try Now' Bluetooth Hurdle on PCs & Tablets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-based-audacity-crash-code-9999/"><u>Fixing Windows-Based Audacity Crash Code 9999</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ancient-pc-modern-atlasos/"><u>Ancient PC, Modern AtlasOS</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-from-beginner-to-appreciator-grasping-the-fundamentals-of-jazz/"><u>Updated In 2024, From Beginner to Appreciator Grasping the Fundamentals of Jazz</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-ways-to-fix-the-sorry-there-is-a-problem-with-the-onedrive-servers-error-on-windows/"><u>6 Ways to Fix the “Sorry, There Is a Problem With the OneDrive Servers” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unison-vs-phone-link-for-windows-phone-users-explored/"><u>Unison Vs. Phone Link for Windows Phone Users Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-steam-cloud-syncs-in-win-10/"><u>Fixing Steam Cloud Syncs in Win 10</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-best-instagram-highlights-covers-apps/"><u>[New] In 2024, Best Instagram Highlights Covers Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-wrinkle-free-up-operator-installation/"><u>Windows Wrinkle? Free Up Operator Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-code-0x80070091-empty-directories-unveiled/"><u>Tackling Windows Error Code 0X80070091 - Empty Directories Unveiled</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/iphone-se-2020-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/"><u>iPhone SE (2020) Asking for Passcode after iOS 17/14 Update, What to Do?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/discover-the-best-open-worlds-today/"><u>Discover the Best Open Worlds Today</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-tecno-camon-30-pro-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Tecno Camon 30 Pro 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-tackling-steam-disk-errors/"><u>Understanding and Tackling Steam Disk Errors</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-farming-secrets-stardew-on-ginger-isles/"><u>2024 Approved  Farming Secrets  Stardew on Ginger Isles</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/step-into-popularity-with-these-20-tiktok-moves/"><u>Step Into Popularity with These 20 TikTok Moves</u></a></li>
<li><a href="https://network-issues.techidaily.com/uninterrupted-anthem-playtime/"><u>Uninterrupted Anthem Playtime</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-color-grading-techniques-unraveling-the-mystery-of-luts/"><u>[New] Color Grading Techniques  Unraveling the Mystery of LUTs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-pc-reawakening-top-3-windows-reset-methods/"><u>Efficient PC Reawakening: Top 3 Windows Reset Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/defend-with-confidence-top-4-password-protectors-for-win-11-users/"><u>Defend With Confidence: Top 4 Password Protectors for Win 11 Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/proven-ways-to-record-and-save-ps4-games-for-2024/"><u>Proven Ways to Record and Save PS4 Games for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-storage-activating-windows-11s-compression/"><u>Efficient Storage: Activating Windows 11’S Compression</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-minecraft-pixel-art-a-complete-guide-for-die-hard-fans-for-2024/"><u>Updated Minecraft Pixel Art A Complete Guide for Die-Hard Fans for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-samsung-galaxy-m34-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Samsung Galaxy M34 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-the-battle-against-freezes-in-apex-legends/"><u>Winning the Battle Against Freezes in Apex Legends</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-samsung-galaxy-xcover-6-pro-tactical-edition-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset Samsung Galaxy XCover 6 Pro Tactical Edition Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-tapping-into-youtubes-earnings-how-much-do-you-make-from-adsense-per-kv/"><u>2024 Approved  Tapping Into Youtube's Earnings  How Much Do You Make From AdSense Per KV?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-approach-using-the-netstat-command-in-win11/"><u>A Step-by-Step Approach: Using the Netstat Command in Win11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-a-gastronomic-journey-the-best-of-viral-tiktok-recipes-for-your-next-cooking-expedition/"><u>[New] A Gastronomic Journey  The Best of Viral TikTok Recipes for Your Next Cooking Expedition</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-xiaomi-redmi-note-12-proplus-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Xiaomi Redmi Note 12 Pro+ 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-surface-computer-firmware-update-manual/"><u>The Ultimate Surface Computer Firmware Update Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-identity-under-threat-are-biometrics-safe/"><u>Windows Identity Under Threat: Are Biometrics Safe?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/upgrading-graphic-memory-in-windows-11-systems/"><u>Upgrading Graphic Memory in Windows 11 Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-stretching-out-youtube-video-quality/"><u>2024 Approved  Stretching Out YouTube Video Quality</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-10-secure-online-forums-dedicated-to-meeting-fellow-netizens/"><u>In 2024, 10 Secure Online Forums Dedicated to Meeting Fellow Netizens</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-decipher-the-best-video-tracker-tools-for-high-impact-results/"><u>[New] In 2024, Decipher the Best Video Tracker Tools for High-Impact Results</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/"><u>Workflow Enhancer: Integrating Sticky Notes Into Your Windows Morning Ritual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-directdraw-errors-with-ease-on-new-windows-oses/"><u>Fixing DirectDraw Errors with Ease on New Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-aid-unlocking-essential-assistive-tech/"><u>Windows Aid: Unlocking Essential Assistive Tech</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-charging-windows-printer-performance/"><u>Turbo-Charging WIndows Printer Performance</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-unlocking-instagrams-hidden-filter-tools/"><u>In 2024, Unlocking Instagram's Hidden Filter Tools</u></a></li>
</ul></div>
