---
title: Windows Users, Ready for Sudo?
date: 2024-08-08T11:09:08.393Z
updated: 2024-08-09T11:09:08.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Users, Ready for Sudo?
excerpt: This Article Describes Windows Users, Ready for Sudo?
keywords: Windows Admin Power,Sudo Use Advantage,Linux Command Guide,Privilege Escalation,System User Access,Elevated Command Utility,Secure OS Controls
thumbnail: https://thmb.techidaily.com/8d4f635de6f8288e79a21d2dcf9027cad8747323c88b4f310acedbe966d2fadc.jpg
---

## Windows Users, Ready for Sudo?

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

 This feature may seem a tad unnecessary—and for many people, it is. That said, if you spend your day running command after command on Windows and wish for the simplicity of the sudo command, its addition will make your life easier.

 Microsoft seems committed to its implementation of sudo, even going so far as to release [sudo on GitHub](http://github.com/microsoft/sudo) as open source. If reading this entices you to learn more about what goes on under the hood in Windows, make sure to take a look at our list of [commands every Windows user should know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-snapper-to-maker-wealth-creation-on-snapchat-platforms/"><u>[New] 2024 Approved  From Snapper to Maker  Wealth Creation on Snapchat Platforms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-viral-instagram-videos-essential-tricks-for-attention/"><u>[New] 2024 Approved  Viral Instagram Videos  Essential Tricks for Attention</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-craft-compelling-openers-for-your-podcast-episodes-examples-and-tips/"><u>[New] Craft Compelling Openers for Your Podcast Episodes  Examples & Tips</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hp-envy-27-4k-usb-c-monitor-review/"><u>[New] HP Envy 27 4K USB-C Monitor Review</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-record-and-save-every-sound-on-pc-exclusive-x-recorder/"><u>[New] In 2024, Record & Save Every Sound on PC - Exclusive X-Recorder</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-unravel-enigmas-your-guide-to-elite-escape-spaces/"><u>[New] In 2024, Unravel Enigmas  Your Guide to Elite Escape Spaces</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-windows-screencast-champions-revealed/"><u>[New] Windows Screencast Champions Revealed</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-elevate-your-content-with-jujutsu-kaisen-on-tiktok/"><u>[Updated] 2024 Approved  Elevate Your Content with Jujutsu Kaisen on TikTok</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-resurrect-the-past-the-ultimate-list-of-top-5-ps1-games-for-pc/"><u>[Updated] 2024 Approved  Resurrect the Past  The Ultimate List of Top 5 PS1 Games for PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-idea-to-share-the-process-of-adding-gifs-on-snapchat/"><u>[Updated] From Idea to Share  The Process of Adding Gifs on Snapchat</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-high-ranking-top-5-quick-screen-recorders-for-2024/"><u>[Updated] High Ranking - Top 5 Quick Screen Recorders for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-screen-grab-analysis-a-comparative-look-at-leading-software/"><u>[Updated] In 2024, Screen Grab Analysis  A Comparative Look at Leading Software</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-strategic-evasion-the-best-room-escapes-ranked/"><u>[Updated] Strategic Evasion  The Best Room Escapes Ranked</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-dive-deep-into-youtube-shorts-essentials/"><u>2024 Approved  Dive Deep Into YouTube Shorts Essentials</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-shape-viral-memes-using-adobe/"><u>2024 Approved  Shape Viral Memes Using Adobe</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-top-10-facebook-video-players/"><u>2024 Approved  Top 10 Facebook Video Players</u></a></li>
<li><a href="https://win11-tips.techidaily.com/3-steps-pinpointing-policies-in-windows-environments/"><u>3 Steps: Pinpointing Policies in Windows Environments</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-motorola-moto-g23-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Motorola Moto G23 FRP</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-straightforward-steps-to-find-windows-ram-details/"><u>5 Straightforward Steps to Find Windows RAM Details</u></a></li>
<li><a href="https://win11-tips.techidaily.com/5-ways-windows-11-collects-your-data/"><u>5 Ways Windows 11 Collects Your Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-proactive-steps-to-overcome-no-servers-found-in-apex-legends-(156-chars/"><u>8 Proactive Steps to Overcome 'No Servers Found' In Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-to-deciphering-windows-11s-registry/"><u>A Comprehensive Guide to Deciphering Windows 11'S Registry</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensive-guide-restoring-the-non-responsive-service-control-panel/"><u>A Comprehensive Guide: Restoring the Non-Responsive Service Control Panel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-deep-dive-into-affordable-windows-10-licensing-and-deals/"><u>A Deep Dive Into Affordable Windows 10 Licensing & Deals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-sevenfold-approach-to-fix-sync-errors-with-google-drive/"><u>A Sevenfold Approach to Fix Sync Errors with Google Drive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-workflow-with-auto-moves-the-w11-way/"><u>Accelerate Workflow with Auto-Moves: The W11 Way</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accelerate-your-excel-operations-in-windows-os/"><u>Accelerate Your Excel Operations in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-power-management-hiding-dim-display/"><u>Accessing Power Management: Hiding 'Dim Display'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-printers-under-edge-guard-on-windows-11/"><u>Accessing Printers Under Edge Guard on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/achieving-optimal-configuration-windows-11-and-pc-manager/"><u>Achieving Optimal Configuration: Windows 11 & PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-in-use-files-errors-in-windows-152-chars/"><u>Addressing 'In-Use' Files Errors in Windows (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-absence-of-razers-in-the-synapse-interface-of-win-11/"><u>Addressing Absence of Razers in the Synapse Interface of Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-incorrect-parameter-loaderror-87/"><u>Addressing Incorrect Parameter LoadError 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-non-functional-cutpaste-in-win-11/"><u>Addressing Non-Functional Cut/Paste in Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-the-device-latency-error-x887a0006win11/"><u>Addressing the Device Latency Error X887A0006:Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-vanishing-bluetooth-clients-on-pc/"><u>Addressing Vanishing Bluetooth Clients on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-file-management-techniques-dragging-tabs-in-windows-11/"><u>Advanced File Management Techniques: Dragging Tabs in Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-innovation-the-surprising-usability-of-aliexpresss-77-3d-printer-revealed-by-reviewer/"><u>Affordable Innovation: The Surprising Usability of AliExpress's $77 3D Printer Revealed by Reviewer</u></a></li>
<li><a href="https://youtube-web.techidaily.com/bout-youtube-tv-your-comprehensive-resource-for-2024/"><u>All About YouTube TV  Your Comprehensive Resource for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-windows-11-shutdown-time-when-applications-are-running/"><u>Altering Windows 11 Shutdown Time when Applications Are Running</u></a></li>
<li><a href="https://win11-tips.techidaily.com/are-your-windows-11-desktop-icons-shrinking-heres-how-to-fix-that/"><u>Are Your Windows 11 Desktop Icons Shrinking? Here's How to Fix That</u></a></li>
<li><a href="https://win11-tips.techidaily.com/artistry-made-easy-top-7-windows-11-drawing-apps-reviewed/"><u>Artistry Made Easy: Top 7 Windows 11 Drawing Apps Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/auditory-capture-made-simple-with-microsofts-win-11/"><u>Auditory Capture Made Simple with Microsoft's Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoid-the-tremors-fixing-pointer-instability-in-windows/"><u>Avoid the Tremors: Fixing Pointer Instability in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/avoiding-windows-11s-temptations-top-8-cautions/"><u>Avoiding Windows 11'S Temptations: Top 8 Cautions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/back-to-basics-quick-fixes-in-13-essential-steps-for-systems/"><u>Back-to-Basics: Quick Fixes in 13 Essential Steps for Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-history-welcome-new-hues-on-windows/"><u>Banish History, Welcome New Hues on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/banish-the-deadly-js-error-in-discord-a-quick-guide-for-win-11-users/"><u>Banish the Deadly JS Error in Discord: A Quick Guide for Win 11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/best-browser-practices-optimal-memorycpu-use-on-three-platforms/"><u>Best Browser Practices: Optimal Memory/CPU Use on Three Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-efficiency-key-modifications-to-apply/"><u>Boost Windows 11 Efficiency: Key Modifications to Apply</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-windows-11-protection-with-new-firewall-add-ons-in-the-context-menu/"><u>Boost Windows 11 Protection with New Firewall Add-Ons in the Context Menu</u></a></li>
<li><a href="https://facebook.techidaily.com/break-through-the-competition-with-unique-facebook-reels/"><u>Break Through the Competition with Unique Facebook Reels</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-oppo-a59-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Oppo A59 5G Devices | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-samsung-galaxy-a54-5g-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Samsung Galaxy A54 5G Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-asus-rog-phone-8-pro-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-itel-p55plus-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-realme-11-proplus-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Realme 11 Pro+ Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-style-essentials-download-for-free/"><u>In 2024, YouTube Style Essentials - Download for FREE</u></a></li>
<li><a href="https://tech-haven.techidaily.com/language-logic-loops-le-chat-ai-meets-chatgpt/"><u>Language Logic Loops: Le Chat AI Meets ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719373458449-learn-how-to-resurrect-the-non-functional-win-plus-p-feature-in-windows/"><u>Learn How to Resurrect the Non-Functional Win + P Feature in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/master-list-of-premium-9-multi-platform-video-communication-apps-for-2024/"><u>Master List of Premium 9 Multi-Platform Video Communication Apps for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719276634403-microsoft-to-do-not-sync-here-are-easy-solutions/"><u>Microsoft To-Do Not Sync? Here Are Easy Solutions</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-top-10-video-rotation-tools-for-seamless-playback/"><u>New 2024 Approved Top 10 Video Rotation Tools for Seamless Playback</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-still-to-stunning-how-to-create-stop-motion-videos-on-instagram-for-2024/"><u>New From Still to Stunning How to Create Stop Motion Videos on Instagram for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-get-creative-with-slow-mo-top-video-editing-software-for-filmmakers/"><u>New In 2024, Get Creative with Slow Mo Top Video Editing Software for Filmmakers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719271756856-stop-worrying-fix-the-non-working-esc-key-today/"><u>Stop Worrying, Fix the Non-Working Esc Key Today</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-updated-method-to-bypass-samsung-galaxy-s23-ultra-frp-by-drfone-android/"><u>The Updated Method to Bypass Samsung Galaxy S23 Ultra FRP</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-honor-x7b-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Honor X7b Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>