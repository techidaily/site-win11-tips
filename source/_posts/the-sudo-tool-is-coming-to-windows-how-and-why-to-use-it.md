---
title: "The Sudo Tool Is Coming to Windows: How and Why to Use It"
date: 2024-07-12T17:29:11.984Z
updated: 2024-07-13T17:29:11.984Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Sudo Tool Is Coming to Windows: How and Why to Use It"
excerpt: "This Article Describes The Sudo Tool Is Coming to Windows: How and Why to Use It"
keywords: Windows Sudo Guide,Using Sudo on Win,Sudo for Windows Users,Implementing Sudo in Windows,Sudo Command Essentials,Installing Sudo Tool,Windows Sudo Adoption
thumbnail: https://thmb.techidaily.com/afda68c97ad8ab431f217d1a649d9d5c1081b7b5e12422de4ab2672dba23567f.jpg
---

## The Sudo Tool Is Coming to Windows: How and Why to Use It

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-photoflex-max-best-windowsmac-picture-editors-for-2024/"><u>[New] PhotoFlex Max  Best Windows/Mac Picture Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-overcoming-uninstall-restrictions-on-win-11/"><u>Troubleshooting: Overcoming Uninstall Restrictions on Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-fixing-non-displaying-searches-in-win-1011-os/"><u>Strategies for Fixing Non-Displaying Searches in Win 10/11 OS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-the-maze-of-igtv-video-downloads-for-2024/"><u>[New] Navigating the Maze of IGTV Video Downloads for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-understanding-its-windows-purpose/"><u>What Is Pagefile.sys? Understanding Its Windows Purpose</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-windows-11-blackout-with-easy-tips-and-tricks/"><u>Bypass Windows 11 Blackout with Easy Tips & Tricks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-keyboard-errors-for-functional-shortcuts-in-windows-11/"><u>Resolve: Keyboard Errors for Functional Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resetting-windows-lockout-count-after-sign-in-failures/"><u>Resetting Windows Lockout Count After Sign-In Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/yourphoneexe-explained-is-it-safe-on-windows-7xp/"><u>YourPhone.exe Explained - Is It Safe on Windows 7/XP?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-15-pro-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>In 2024, Unlock iPhone 15 Pro With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-audio-not-installed-issues-in-windows-os/"><u>Resolving 'Audio Not Installed' Issues in Windows OS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-ios-cropping-enhancing-your-images/"><u>[Updated] The Ultimate Guide to iOS Cropping  Enhancing Your Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-devices-on-the-frontline-top-5-ways-to-confirm-availability/"><u>Windows 11 Devices on the Frontline: Top 5 Ways to Confirm Availability</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-steam-must-be-running-to-play-this-game-error-in-windows-11/"><u>7 Ways to Fix the Steam Must Be Running to Play This Game Error in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-transition-website-to-desktop-compatibility/"><u>Seamless Transition: Website to Desktop Compatibility</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-your-soundscape-best-free-apps-to-download-youtube-songs-on-android/"><u>In 2024, Streamline Your Soundscape  Best Free Apps to Download YouTube Songs on Android</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolve-your-windows-display-hurdles-easily/"><u>Resolve Your Window's Display Hurdles Easily</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-clearview-recorder-xtreme-win10/"><u>[New] 2024 Approved  ClearView Recorder Xtreme (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-entry-point-issues-on-windows-systems/"><u>Bypassing Entry Point Issues on Windows Systems</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-rock-solid-videos-best-free-video-stabilization-tools-for-pc-and-mac/"><u>New 2024 Approved Rock-Solid Videos Best Free Video Stabilization Tools for PC and Mac</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-unveiling-the-leading-tiktok-talent-around-the-globe/"><u>In 2024, Unveiling the Leading TikTok Talent Around the Globe</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-mastering-tiktok-marketing-effective-ad-methods-and-case-studies/"><u>In 2024, Mastering TikTok Marketing  Effective Ad Methods and Case Studies</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-essential-e-steps-your-pathway-from-preparation-to-production-in-a-reviews-channel/"><u>[New] The Essential E-Steps  Your Pathway From Preparation to Production in a Reviews Channel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-ceasing-random-windows-key-activation/"><u>Strategies for Ceasing Random Windows Key Activation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/adjusting-windows-11s-resolution-settings/"><u>Adjusting Windows 11'S Resolution Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-missing-component-alert-in-windows-1011/"><u>Overcoming the Missing Component Alert in Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-free-note-taking-tricks-in-windows-11/"><u>Top Free Note-Taking Tricks in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/lol-gaming-on-air-top-3-recording-methods/"><u>LOL Gaming On Air  Top 3 Recording Methods</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-sudden-screen-loss-during-win-games/"><u>Techniques to Overcome Sudden Screen Loss During WIN Games</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-into-peace-five-tactics-to-overcome-windows-security-failures/"><u>Boot Into Peace: Five Tactics to Overcome Windows Security Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-made-dns-strategies-for-windows-11-enthusiasts/"><u>Tailor-Made DNS Strategies for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-apply-video-filters/"><u>New How to Apply Video Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tricks-to-speed-up-system-restart-with-windows-11/"><u>Tricks to Speed Up System Restart with Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-manipulating-the-windows-11-registry-to-unlock-themes/"><u>The Art of Manipulating the Windows 11 Registry to Unlock Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/space-saving-savvy-master-windows-11s-minimalist-method/"><u>Space-Saving Savvy: Master Windows 11'S Minimalist Method</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-direct-mp3-download-for-fb-video-tracks-for-2024/"><u>[New] Direct MP3 Download for FB Video Tracks for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-windows-updates-on-windows-108/"><u>Regaining Access to Windows Updates on Windows 10/8</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-infinix-by-fonelab-android-recover-photos/"><u>Undelete lost photos from Infinix .</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-augmented-reality-and-vr-navigating-2023s-content-on-android/"><u>In 2024, Augmented Reality & VR  Navigating 2023'S Content on Android</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-5-tips-about-youtube-shorts-to-grow-your-business-for-2024/"><u>New 5 Tips About YouTube Shorts to Grow Your Business for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-maximizing-profits-on-youtube-the-latest-policy/"><u>[Updated] Maximizing Profits on YouTube  The Latest Policy</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-upcoming-license-expiration-error-in-w10w11/"><u>Addressing Upcoming License Expiration Error in W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalizing-your-pcs-dns-with-ease-in-windows-11/"><u>Revitalizing Your PC's DNS with Ease in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accurate-timekeeping-at-your-fingertips-winning-windows-timers/"><u>Accurate Timekeeping at Your Fingertips: Winning Windows Timers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-invalid-network-path/"><u>Overcoming Windows' Invalid Network Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-failed-operations-code-0x0000011b-fixes/"><u>Eliminating 'Failed' Operations: Code 0X0000011B Fixes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-best-bet-aiff-to-mp3-suite-fast-and-easy-high-quality-converting/"><u>Updated In 2024, Best Bet AIFF to MP3 Suite Fast and Easy High-Quality Converting</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719365974672-ten-terminal-tricks-you-can-try-today/"><u>Ten Terminal Tricks You Can Try Today!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-empty-directory-alert-on-windows-11/"><u>Overcoming Empty Directory Alert on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-fix-0x800700e1-on-w10w11/"><u>Steps to Fix 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-crafting-engaging-content-with-added-vocal-dimensions-in-tiktok-videos/"><u>[New] In 2024, Crafting Engaging Content with Added Vocal Dimensions in TikTok Videos</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-iphone-xs-max-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On iPhone XS Max Online</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/elevate-your-nba-experience-with-these-15-tips-for-2024/"><u>Elevate Your NBA Experience with These 15 Tips for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-photo-import-discrepancies-between-ios-and-windows-11/"><u>Remedying Photo Import Discrepancies Between iOS and Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/convenient-cleanup-integrating-uninstall-shortcuts-into-wins-interface/"><u>Convenient Cleanup: Integrating Uninstall Shortcuts Into Win's Interface</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-tailored-guide-to-youtube-trailer-production-with-filmora/"><u>2024 Approved  Tailored Guide to YouTube Trailer Production with Filmora</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-win11-wi-fi-accessibility-with-9-steps/"><u>Securing Win11 Wi-Fi Accessibility with 9 Steps</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-unmatched-virtual-speedway-showdowns-top-5-list/"><u>[Updated] Unmatched Virtual Speedway Showdowns  Top 5 List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-chart-toppers-on-screen-uploading-songs-methodically/"><u>2024 Approved  Chart-Toppers on Screen  Uploading Songs Methodically</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-asus-rog-phone-7-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Asus ROG Phone 7 to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-pc-sound-with-new-windows-audio-drivers/"><u>Streamline Your PC Sound with New Windows Audio Drivers</u></a></li>
<li><a href="https://some-tips.techidaily.com/streamline-your-podcasts-for-apple-podcasts-for-2024/"><u>Streamline Your Podcasts for Apple Podcasts for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/say-goodbye-to-speedy-pointers-curtailing-acceleration-on-windows-11/"><u>Say Goodbye to Speedy Pointers: Curtailing Acceleration on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-step-by-step-walkthrough-of-instagram-story-screening/"><u>[New] Step-by-Step Walkthrough of Instagram Story Screening</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/fusion-of-video-files-for-ios-devices/"><u>Fusion of Video Files for iOS Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-and-streamlining-the-microsoft-store-in-win11/"><u>Unblocking and Streamlining the Microsoft Store in Win11</u></a></li>
</ul></div>
