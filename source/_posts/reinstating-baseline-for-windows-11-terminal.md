---
title: Reinstating Baseline for Windows 11 Terminal
date: 2024-09-11T01:20:49.637Z
updated: 2024-09-12T01:20:49.637Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Baseline for Windows 11 Terminal
excerpt: This Article Describes Reinstating Baseline for Windows 11 Terminal
keywords: Win11 Terminal Baseline,Windows 11 Baseline,Reviving Windows Terminal,Windows 11 Update,Enhancing Terminal Settings,Reinstalling Windows 11,Windows Terminal Standard
thumbnail: https://thmb.techidaily.com/84a193c7dfe30d1711082c3e2e61ae28fba386e229daa9e6bb79214392acb3f8.jpg
---

## Reinstating Baseline for Windows 11 Terminal

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.





<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114263/17093" target="_top" id="2114263">
  <img src="//a.impactradius-go.com/display-ad/17093-2114263" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114263/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .




<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our[beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115931/19272" target="_top" id="2115931">
  <img src="//a.impactradius-go.com/display-ad/19272-2115931" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-unveiling-effective-techniques-for-setting-up-and-gauging-fbs-instream-ads/"><u>[New] In 2024, Unveiling Effective Techniques for Setting Up and Gauging FB's Instream Ads</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-obs-studio-wizards-top-5-secrets-to-unmatched-quality/"><u>[New] OBS Studio Wizards Top 5 Secrets to Unmatched Quality</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-premium-audio-visual-leading-blu-ray-devices-for-2024/"><u>[New] Premium Audio, Visual Leading Blu-Ray Devices for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-investment-in-top-tier-hdr-cameras-a-buyers-guide/"><u>[Updated] In 2024, Investment in Top-Tier HDR Cameras A Buyer's Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-professional-streaming-made-simple-in-obs-studio-android-edition/"><u>[Updated] In 2024, Professional Streaming Made Simple in OBS Studio, Android Edition</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-view-count-best-yt-thumbnail-sizes/"><u>[Updated] Maximize View Count Best YT Thumbnail Sizes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-shielding-imagery-best-practices-for-instagram-photowatermarking-for-2024/"><u>[Updated] Shielding Imagery Best Practices for Instagram Photowatermarking for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-10-best-no-cost-live-streaming-tools-android-and-iphone-guide/"><u>2024 Approved 10 Best No-Cost Live Streaming Tools Android & iPhone Guide</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-oneplus-ace-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on OnePlus Ace 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/animationpros-complete-guide-24-for-2024/"><u>AnimationPros Complete Guide '24 for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/chrome-troubles-eradicate-errnamenotresolved-with-this-easy-method/"><u>Chrome Troubles? Eradicate 'ERR_NAME_NOT_RESOLVED' With This Easy Method!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-smudges-quick-windows-11-remedies-for-distorted-displays/"><u>Decoding Smudges: Quick Windows 11 Remedies for Distorted Displays</u></a></li>
<li><a href="https://extra-hints.techidaily.com/decorate-your-snaps-iphoneandroids-best-10-sticker-enhancing-apps/"><u>Decorate Your Snaps IPhone/Android's Best 10 Sticker-Enhancing Apps</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-samsung-galaxy-a15-5g-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://extra-information.techidaily.com/echo-generator-blueprint/"><u>Echo Generator Blueprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-on-picking-the-right-nvidia-driver-type/"><u>Expert Tips on Picking the Right Nvidia Driver Type</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-samsung-galaxy-s23plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/from-code-to-compassion-ai-in-windows-tomorrow/"><u>From Code to Compassion: AI in Windows Tomorrow</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-common-rainmeter-issues-on-windows/"><u>How to Fix Common Rainmeter Issues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-microsoft-store-error-code-0x80131500/"><u>How to Fix the Microsoft Store Error Code 0X80131500</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reveal-taskbar-behind-maximized-window-titles/"><u>How to Reveal Taskbar Behind Maximized Window Titles</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-v29-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo V29</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-filching-frames-from-films-for-windows-10-photos-collection/"><u>In 2024, Filching Frames From Films for Windows 10 Photos Collection</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-how-to-leverage-different-gadgets-recording-and-saving-youtube-livestayere/"><u>In 2024, How To Leverage Different Gadgets Recording and Saving YouTube Livestayere</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-next-gen-webcams-a-deep-dive-into-live-videography-gear/"><u>In 2024, Next-Gen WebCams A Deep Dive Into Live Videography Gear</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-total-clarification-googles-podcast-application-simplified/"><u>In 2024, Total Clarification Google's Podcast Application Simplified</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/locked-out-of-iphone-x-5-ways-to-get-into-a-locked-iphone-x-drfone-by-drfone-ios/"><u>Locked Out of iPhone X? 5 Ways to get into a Locked iPhone X | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-networks-configure-win11s-dns-client-service/"><u>Mastering Networks: Configure Win11's DNS Client Service</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-credential-management-fix/"><u>Mastering the Art of Credential Management Fix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-missing-file-updates-on-windows-os/"><u>Mastering the Art of Fixing Missing File Updates on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-windows-10-value-with-expert-key-tips/"><u>Maximize Windows 10 Value with Expert Key Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-disruptions-caused-by-windows-update-installations/"><u>Navigating Disruptions Caused by Windows Update Installations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-path-to-windows-assistant-activation/"><u>Navigating the Path to Windows Assistant Activation</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/navigating-the-world-of-electronics-with-toms-hardware-experts/"><u>Navigating the World of Electronics with Tom's Hardware Experts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-pc-query-speed-using-everythingapp/"><u>Optimize PC Query Speed Using EverythingApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-chrome-display-failure/"><u>Overcoming Chrome Display Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/precise-note-taking-apps-the-seven-windows-stars/"><u>Precise Note-Taking Apps: The Seven Windows Stars</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-chromes-sudden-shutdown-a-windows-guide/"><u>Preventing Chrome's Sudden Shutdown: A Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventive-tactics-against-ms-store-on-windows-10/"><u>Preventive Tactics Against MS Store on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-efficient-powertoys-setup-in-win11/"><u>Quick Guide: Efficient PowerToys Setup in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-greyed-out-recycling-tool-in-windows-11/"><u>Reactivating Greyed-Out Recycling Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-photo-capture-failures-in-windows-os/"><u>Resolve Photo Capture Failures in Windows OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/ride-the-viral-wave-mixing-tiktok-flair-into-instagram-reels/"><u>Ride the Viral Wave Mixing TikTok Flair Into Instagram Reels</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-oppo-find-n3-flip-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Oppo Find N3 Flip</u></a></li>
<li><a href="https://extra-hints.techidaily.com/secrets-to-splendid-windows-11-backdrops/"><u>Secrets to Splendid Windows 11 Backdrops</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-y200e-5g-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Y200e 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplify-your-agenda-linking-to-dot-to-ifttt/"><u>Simplify Your Agenda: Linking To-Dot to IFTTT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speeding-up-windows-edge-steps-for-w10-and-w11/"><u>Speeding up Windows Edge: Steps for W10 & W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-regain-smooth-operation-of-asana-on-desktop-computers/"><u>Steps to Regain Smooth Operation of Asana on Desktop Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-restore-your-pcs-renderer-state-in-overwatch-2/"><u>Steps to Restore Your PC's Renderer State in Overwatch 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-overcome-privilege-issues-in-windows-installer-errors/"><u>Strategies to Overcome Privilege Issues in Windows Installer Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tablet-writes-transcribes-find-the-winning-seven-on-pc/"><u>Tablet' Writes, Transcribes: Find the Winning Seven on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-checklist-for-selecting-the-best-windows-pc/"><u>The Essential Checklist for Selecting the Best Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-smart-way-to-ascertain-your-windows-systems-make/"><u>The Smart Way to Ascertain Your Windows System's Make</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-window-bar-timeline-from-85-to-now/"><u>The Window Bar Timeline: From '85 to Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-5-ways-win11-gathers-your-digital-footprint/"><u>Top 5 Ways Win11 Gathers Your Digital Footprint</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-taskbar-utility-adding-directories-to-windows-11-menu/"><u>Transform Taskbar Utility: Adding Directories to Windows 11 Menu</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-unlock-fcp-x-advanced-chroma-keying-techniques-for-video-editors-for-2024/"><u>Updated Unlock FCP X Advanced Chroma Keying Techniques for Video Editors for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-realme-gt-3-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Realme GT 3 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-secure-the-best-encryption-applications-of-the-year-153-chars/"><u>Win Secure: The Best Encryption Applications of the Year (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-s-mode-is-it-right-for-your-pc/"><u>Windows 11 S Mode: Is It Right for Your PC?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-chatgpt-integration-steps/"><u>Windows ChatGPT Integration Steps</u></a></li>
</ul></div>
