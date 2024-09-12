---
title: What Are App Execution Aliases, and How Do You Use Them?
date: 2024-09-11T01:24:45.448Z
updated: 2024-09-12T01:24:45.448Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
excerpt: This Article Describes What Are App Execution Aliases, and How Do You Use Them?
keywords: App Exec ALIAS,SEO Exec ALIAS,Execute Alias Usage,Alias for App SEO,App Performance Optimization,Enhancing App Visibility,Boosting App Engagement
thumbnail: https://thmb.techidaily.com/1ed4f091728645649c840ae907d2be87aba494a53f4cf1942b1dcf1c240fc190.jpg
---

## What Are App Execution Aliases, and How Do You Use Them?

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.





<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118324/7443" target="_top" id="2118324">
  <img src="//a.impactradius-go.com/display-ad/7443-2118324" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118324/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-discovering-and-perfecting-your-individual-style/"><u>[New] 2024 Approved Discovering & Perfecting Your Individual Style</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ecoding-ad-revenue-distribution-in-youtubes-economic-model/"><u>[New] Decoding Ad Revenue Distribution in YouTube's Economic Model</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-quickvision-w11-simple-desktop-capture-tool/"><u>[New] In 2024, QuickVision W11 Simple Desktop Capture Tool</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-innovative-subtitle-edits-rank-the-top-10-programs-for-2024/"><u>[New] Innovative Subtitle Edits – Rank the Top 10 Programs for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-revitalize-disappearing-watch-thumbnail-for-2024/"><u>[New] Revitalize Disappearing Watch Thumbnail for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-image-booster-intense-visual-upgrade/"><u>[New] Ultimate Image Booster Intense Visual Upgrade</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-audio-callback-logger-for-iphone-2024/"><u>[Updated] Audio Callback Logger for iPhone 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-blades-new-vision-in-ultra-high-definition-clarity/"><u>[Updated] Blade's New Vision in Ultra-High Definition Clarity</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-boost-your-income-with-effective-snapchat-ads/"><u>[Updated] Boost Your Income with Effective Snapchat Ads</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-srt-mastery-a-technological-deep-dive-for-media-professionals/"><u>[Updated] SRT Mastery A Technological Deep-Dive for Media Professionals</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-transform-your-macbook-writable-screen-with-these-wallpapers-for-2024/"><u>[Updated] Transform Your MacBook' Writable Screen with These Wallpapers for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-5-quick-hacks-to-sharpen-your-indie-filmmaking-skills/"><u>2024 Approved 5 Quick Hacks to Sharpen Your Indie Filmmaking Skills</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-audiovisual-alteration-apps-that-revolutionize-vtubing-soundscapes/"><u>2024 Approved Audiovisual Alteration Apps that Revolutionize Vtubing Soundscapes</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-steps-to-avoid-automatic-podcast-suggestions-on-spotify/"><u>2024 Approved Steps to Avoid Automatic Podcast Suggestions on Spotify</u></a></li>
<li><a href="https://extra-tips.techidaily.com/amplify-your-iphone-films-with-free-audio-additions-discover-three-ways/"><u>Amplify Your iPhone Films with Free Audio Additions – Discover Three Ways</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-assessment-performance-testing-for-corsairs-cx7er-m-power-unit/"><u>Comprehensive Assessment: Performance Testing for Corsair's CX7er M Power Unit</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-directory-not-empty-mistake-windows-error-x80070091/"><u>Decoding the 'Directory Not Empty' Mistake: Windows Error X80070091</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-restarting-windows-programs-in-1011/"><u>Efficiently Restarting Windows Programs in 10/11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-setup-for-your-linksys-ae1200-router-instant-access-to-the-newest-drivers/"><u>Effortless Setup for Your Linksys AE1200 Router - Instant Access to the Newest Drivers</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/elevate-conversations-the-compelling-case-for-chatgptplus-upgrade/"><u>Elevate Conversations - The Compelling Case for ChatGPT+ Upgrade</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriched-desktop-features-real-time-performance-indicators/"><u>Enriched Desktop Features: Real-Time Performance Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-actions-to-resolve-windowed-games-issue/"><u>Essential Actions to Resolve Windowed Games Issue</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-oppo-find-x6-pro-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Oppo Find X6 Pro Face Lock?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-epson-tm-t88v-printer-software-version-for-windows-pcs-free-download/"><u>Get the Newest EPSON TM-T88v Printer Software Version for Windows PCs - Free Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-high-cpu-usage-from-vanguard-user-mode-service-on-windows/"><u>How to Fix High CPU Usage From Vanguard User-Mode Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-synchronization-glitches-in-monitors/"><u>How to Fix Synchronization Glitches in Monitors</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-apple-iphone-x-activation-lock-by-drfone-ios/"><u>How to Remove Apple iPhone X Activation Lock</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-htc-u23-pro-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track HTC U23 Pro Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-motorola-moto-g13-phone-by-drfone-android/"><u>How to Unlock a Network Locked Motorola Moto G13 Phone?</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-se-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone SE without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-15-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 15 Pro Max Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-and-solutions-for-a-non-responsive-discord-overlay/"><u>Identifying Causes and Solutions for a Non-Responsive Discord Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-low-resource-browsers-for-windows-macos-chromeos-users/"><u>Identifying Low Resource Browsers for Windows, macOS, ChromeOS Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-discontinuing-instant-recording-on-quicktime/"><u>In 2024, Discontinuing Instant Recording on QuickTime</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-oppo-f25-pro-5g-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Oppo F25 Pro 5G</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-joint-ventures-in-content-creation-for-youtube-audiences/"><u>In 2024, Joint Ventures in Content Creation for YouTube Audiences</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-your-creative-potential-an-overview-of-final-cut-pro/"><u>In 2024, Unlock Your Creative Potential An Overview of Final Cut Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrated-file-management-in-powertoys/"><u>Integrated File Management in PowerToys</u></a></li>
<li><a href="https://common-error.techidaily.com/make-your-aoc-screen-function-again-in-win10-step-by-step-guide/"><u>Make Your AOC Screen Function Again in Win10: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-x-solutions-for-windows-mail-mistakes/"><u>Mastering Error X: Solutions for Windows Mail Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-efficiency-in-accessibility-insider-secrets-for-using-narrator-shortcuts/"><u>Maximizing Efficiency in Accessibility: Insider Secrets for Using Narrator Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-system-restore-in-windows-11-a-comprehensive-guide/"><u>Navigating System Restore in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/nifty-folding-tricks-in-windows-11-for-beginners/"><u>Nifty Folding Tricks in Windows 11 for Beginners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-performance-tracking-improving-system-tray-usage-reports/"><u>Optimize Performance Tracking: Improving System Tray Usage Reports</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-bluetooth-pairing-issues-on-windows-11/"><u>Overcoming Bluetooth Pairing Issues on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-installation-hurdles-in-windows-11/"><u>Overcoming Steam Installation Hurdles in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-window-error-terminate-denied-issue/"><u>Overcoming the Window Error: Terminate Denied Issue</u></a></li>
<li><a href="https://win11.techidaily.com/procedure-opening-driver-verifier-for-fault-analysis/"><u>Procedure: Opening Driver Verifier for Fault Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prologue-to-productivity-starting-windows-and-stickies-together/"><u>Prologue to Productivity: Starting Windows & Stickies Together</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-tackling-windows-steam-playback-problems/"><u>Quick Guide: Tackling Windows Steam Playback Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/razers-remedy-guide-quick-reset-for-windows-1011/"><u>Razer's Remedy Guide: Quick Reset for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-to-resolve-screen-size-settings-issues-on-pcs/"><u>Remedies to Resolve Screen Size Settings Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-jvm-setup-issue-on-microsoft-os/"><u>Resolving JVM Setup Issue on Microsoft OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-accessible-nvidia-display-settings/"><u>Restoring Accessible Nvidia Display Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-file-transfer-speed-on-microsoft-platforms/"><u>Skyrocket Your File Transfer Speed on Microsoft Platforms</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solve-oculus-air-link-woes-expert-tips-for-a-smooth-windows-setup/"><u>Solve Oculus Air Link Woes: Expert Tips for a Smooth Windows Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-and-kali-linux-combo/"><u>Step-by-Step Guide to Windows & Kali Linux Combo</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-rectify-invalid-user-alert-in-w11-oses/"><u>Steps to Rectify Invalid User Alert in W11 OSes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/streamlining-assistance-chatgpts-integration-with-whatsapp/"><u>Streamlining Assistance: ChatGPT's Integration with WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-permanent-delete-on-windows-pcs-with-the-power-of-your-desktop-bin-11/"><u>Streamlining Permanent Delete on Windows PCs with the Power of Your Desktop Bin (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/surpassing-windows-internet-speed-ceiling-with-ease/"><u>Surpassing Windows Internet Speed Ceiling with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-survival-kit-top-13-ways-to-resurrect-windows/"><u>System Survival Kit: Top 13 Ways to Resurrect Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intersection-of-ai-and-windows-11-user-experience/"><u>The Intersection of AI and Windows 11 User Experience</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-10-substitutes-for-chatgpt-enhancing-ai-conversations/"><u>Top 10 Substitutes for ChatGPT: Enhancing AI Conversations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-after-windows-update-installation/"><u>Troubleshooting After Windows Update Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-opening-mailcalendar-app-in-w11/"><u>Troubleshooting Non-Opening Mail/Calendar App in W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-in-windows-via-alomware-features/"><u>Unlock Potential in Windows via AlomWare Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/which-nvidia-driver-suits-you-gameplay-or-studio/"><u>Which Nvidia Driver Suits You? - Gameplay or Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screen-makeover-tailored-wallpapers-per-monitor/"><u>Windows 11 Screen Makeover: Tailored Wallpapers Per Monitor</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-phone-link-enable-or-disable-for-better-security/"><u>Windows Phone Link - Enable or Disable for Better Security?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windowsnotepadlightoffcommand/"><u>WindowsNotepadLightOffCommand</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-control-fixing-flaky-windows-apps/"><u>Winning Back Control: Fixing Flaky Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-with-warmth-fixing-color-conflicts-on-pcs/"><u>Winning with Warmth: Fixing Color Conflicts on PCs</u></a></li>
</ul></div>




