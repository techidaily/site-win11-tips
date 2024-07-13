---
title: Why Windows Users Should Anticipate Sudo
date: 2024-07-12T17:12:38.294Z
updated: 2024-07-13T17:12:38.294Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Why Windows Users Should Anticipate Sudo
excerpt: This Article Describes Why Windows Users Should Anticipate Sudo
keywords: Sudo Security Concerns,Preventing Sudo Abuse,Windows Sudo Risks,Mitigating Sudo Vulnerabilities,Secure Windows Administration,Anticipate Sudo Breaches,Protect Against Sudo Exploits
thumbnail: https://thmb.techidaily.com/fe488ca615edc9308d7ef5f18a2de9eeeab475c2bf30ee9f714175262d3f8617.jpeg
---

## Why Windows Users Should Anticipate Sudo

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
<li><a href="https://win11-tips.techidaily.com/solutions-for-driver-initialization-failure-in-windows-11/"><u>Solutions for Driver Initialization Failure in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-tackling-windows-1011-interrupt-crashes/"><u>Strategies for Tackling Windows 10/11 INTERRUPT Crashes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-xbox-mic-malfunctions-in-windows-os/"><u>Overcoming Xbox Mic Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-guide-to-managing-win11-applications-via-winget/"><u>The Complete Guide to Managing Win11 Applications via Winget</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rejoining-fall-guys-fixing-connectivity-issues-on-pc/"><u>Rejoining Fall Guys: Fixing Connectivity Issues on PC</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-tune-tracker-prodigies-the-finest-song-identification-apps-enhancing-your-android-musical-experience/"><u>2024 Approved Tune Tracker Prodigies The Finest Song Identification Apps Enhancing Your Android Musical Experience</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-the-key-to-captivating-audiences-crafting-fb-slideshows/"><u>In 2024, The Key to Captivating Audiences  Crafting FB Slideshows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-for-expanded-pinned-area-on-windows-11-ui/"><u>Techniques for Expanded Pinned Area on Windows 11 UI</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-9-powerful-methods-to-make-money-on-your-youtube-shorts/"><u>In 2024, 9 Powerful Methods to Make Money on Your YouTube Shorts</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-gif-speed-booster-best-tools-for-web-ios-and-android-for-2024/"><u>New GIF Speed Booster Best Tools for Web, iOS, and Android for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-elevate-video-performance-top-notch-youtube-seo-strategies/"><u>In 2024, Elevate Video Performance  Top-Notch YouTube SEO Strategies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-d3dx939dll-loss-in-windows-11/"><u>Resolving D3DX9_39.dll Loss in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-inadequate-usb-support-on-desktops/"><u>Addressing Inadequate USB Support on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-intel-unison-for-windows-11-calling/"><u>The Ultimate Guide to Intel Unison for Windows 11 Calling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719320946567-list-three-benefits-of-applying-a-cultural-relativist-approach-when-encountering-unfamiliar-customs-or-beliefs/"><u>List Three Benefits of Applying a Cultural Relativist Approach when Encountering Unfamiliar Customs or Beliefs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-checklist-longer-pins-in-windows-11-and-11/"><u>The Ultimate Checklist: Longer PINs in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-for-resolving-user-not-found-issue-windows-1011/"><u>Steps for Resolving 'User Not Found' Issue: Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regain-command-gain-admin-status/"><u>Regain Command - Gain Admin Status</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-display-options-with-these-10-tips/"><u>Unlocking Windows 11 Display Options with These 10 Tips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-unlocking-engagement-best-practices-for-highlight-boost/"><u>[Updated] Unlocking Engagement  Best Practices for Highlight Boost</u></a></li>
<li><a href="https://win11-tips.techidaily.com/storeroom-in-mp60-speed-still-scarce/"><u>Storeroom in MP60, Speed Still Scarce</u></a></li>
<li><a href="https://extra-skills.techidaily.com/speedy-fixes-for-slow-mo-videos-in-a-flash-for-2024/"><u>Speedy Fixes for Slow-Mo Videos in a Flash for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/forging-bonds-strategic-partnerships-with-brands-on-youtube-for-2024/"><u>Forging Bonds  Strategic Partnerships with Brands on YouTube for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-unlocking-the-potential-a-basic-guide-to-using-lexis-sound-laboratory/"><u>Updated 2024 Approved Unlocking the Potential A Basic Guide to Using Lexis Sound Laboratory</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-do-you-want-to-add-subtitles-to-your-mkv-files-easily-this-article-will-introduce-7-simple-ways-through-which-you-can-add-subtitles-to-mkv-on-different-/"><u>New Do You Want to Add Subtitles to Your MKV Files Easily? This Article Will Introduce 7 Simple Ways Through Which You Can Add Subtitles to MKV on Different Devices</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-fixing-live-stream-drops-optimizing-your-obs-settings/"><u>In 2024, Fixing Live Stream Drops  Optimizing Your OBS Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-the-mechanics-of-windows-11s-compatibility-tool/"><u>Uncovering the Mechanics of Windows 11’S Compatibility Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proven-windows-methods-to-identify-system-gadgets/"><u>Proven Windows Methods to Identify System Gadgets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-microsofts-ai-assistive-functions/"><u>Understanding Microsoft's AI Assistive Functions</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-samsung-galaxy-xcover-6-pro-tactical-edition-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Samsung Galaxy XCover 6 Pro Tactical Edition via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-xs-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone XS Max without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-perfect-your-patchwork-on-tiktok/"><u>[Updated] 2024 Approved  Perfect Your Patchwork on TikTok</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beating-the-buzz-mastering-voice-recorder-shortcuts-in-windows-11/"><u>Beating the Buzz: Mastering Voice Recorder Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-non-verified-error-during-windows-file-installation/"><u>Solving the Non-Verified Error During Windows File Installation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-crafting-captivating-igtv-cover-images-thumbnails-for-2024/"><u>[New] Crafting Captivating IGTV Cover Images (Thumbnails) for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-nokia-c12-plus-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Nokia C12 Plus</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-mobile-downloader-the-ultimate-apps-for-video-buffs/"><u>[Updated] In 2024, Free Mobile Downloader  The Ultimate Apps for Video Buffs</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-list-for-google-pixel-tunes/"><u>[New] The Ultimate List for Google Pixel Tunes</u></a></li>
</ul></div>
