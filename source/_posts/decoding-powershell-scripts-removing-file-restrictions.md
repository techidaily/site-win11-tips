---
title: "Decoding PowerShell Scripts: Removing File Restrictions"
date: 2024-08-23T07:01:58.240Z
updated: 2024-08-24T07:01:58.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding PowerShell Scripts: Removing File Restrictions"
excerpt: "This Article Describes Decoding PowerShell Scripts: Removing File Restrictions"
keywords: PowerShell Script Basics,Remove File Permissions,Bypassing Restrictions,Secure Script Handling,Unlock Files with PS,Enhancing Script Security,Access Control in Powershell
thumbnail: https://thmb.techidaily.com/39056fd18de68ad167dab8918139616b0085a3cc76b52ba12d66889ac85fb462.jpg
---

## Decoding PowerShell Scripts: Removing File Restrictions

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://on-screen-recording.techidaily.com/new-achieving-cost-free-online-educational-streaming-for-2024/"><u>[New] Achieving Cost-Free Online Educational Streaming for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlock-the-potential-of-photography-with-adobe-motion-blur/"><u>[New] Unlock the Potential of Photography with Adobe Motion Blur</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-your-2023-guide-best-applications-for-downloading-lite-facebook-videos-for-2024/"><u>[New] Your 2023 Guide  Best Applications for Downloading Lite Facebook Videos for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-92-chuckle-fest-an-analyzed-goofy-film-vhs/"><u>[Updated] '92 Chuckle Fest'  An Analyzed Goofy Film VHS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-pioneering-techniques-for-cross-social-video-sharing/"><u>[Updated] 2024 Approved  Pioneering Techniques for Cross-Social Video Sharing</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-fixing-glitches-seeing-your-own-face-in-fb-live-for-2024/"><u>[Updated] Fixing Glitches  Seeing Your Own Face in FB Live for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-no-limit-visual-capturer-device/"><u>[Updated] In 2024, No-Limit Visual Capturer Device</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-spark-interest-on-snapchat-15-innovative-strategies/"><u>[Updated] In 2024, Spark Interest on Snapchat  15 Innovative Strategies</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-ultimate-hue-harmonizer-tool/"><u>[Updated] Ultimate Hue Harmonizer Tool</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-directing-viewers-gaze-in-iphone-compositions-through-leading-lines/"><u>2024 Approved  Directing Viewers' Gaze in iPhone Compositions Through Leading Lines</u></a></li>
<li><a href="https://facebook.techidaily.com/activists-cause-chaos-provoke-one-star-reviews-on-social-network/"><u>Activists Cause Chaos: Provoke One-Star Reviews on Social Network</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cost-free-webm-viewing-a-list-of-industry-standouts-for-2024/"><u>Cost-Free WebM Viewing  A List of Industry Standouts for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-update-lenovo-drivers-for-windows-11/"><u>Download Update Lenovo Drivers for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-your-role-fixing-cmd-prompt-issues/"><u>Elevating Your Role: Fixing Cmd Prompt Issues</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elite-yoga-routines-youtubes-leading-fitness-sites-for-2024/"><u>Elite Yoga Routines  YouTube's Leading Fitness Sites for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-fixes-for-elusive-gpeditmsc-on-your-pc/"><u>Essential Fixes for Elusive 'Gpedit.msc' On Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-windows-fs-apps-crowd-picked-winners/"><u>Essential Windows FS Apps: Crowd-Picked Winners</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-maximize-your-use-of-remote-connections-w11/"><u>Expert Tips: Maximize Your Use of Remote Connections W11</u></a></li>
<li><a href="https://fox-info.techidaily.com/exploring-gpt-vs-bert-a-comprehensive-guide-to-their-key-distinctions/"><u>Exploring GPT Vs. BERT: A Comprehensive Guide to Their Key Distinctions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixers-compendium-tackling-active-directory-printer-errors-on-win-1011/"><u>Fixer's Compendium: Tackling Active Directory Printer Errors on WIN 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-nonfunctional-windows-11-wireless-hotspot-issue/"><u>Fixing Nonfunctional Windows 11 Wireless Hotspot Issue</u></a></li>
<li><a href="https://some-techniques.techidaily.com/free-frameworks-for-every-movie-epilogue-you-dream-for-2024/"><u>Free Frameworks for Every Movie Epilogue You Dream for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/halt-spotify-autoplay-behavior-on-windows-pcs/"><u>Halt Spotify Autoplay Behavior on Windows PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Honor X9a? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-a-display-not-turning-on-when-booting-up-windows/"><u>How to Fix a Display Not Turning On When Booting Up Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-use-apple-maps-on-a-windows-pc/"><u>How to Use Apple Maps on a Windows PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/improving-browsers-pasting-feature-across-pcs/"><u>Improving Browsers' Pasting Feature Across PCs</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-vivo-y100-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-asus-rog-phone-7-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Asus ROG Phone 7 FRP Bypass Instantly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-lock-apps-on-samsung-galaxy-f15-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Samsung Galaxy F15 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/incorporating-omnipotent-options-in-windows-11/"><u>Incorporating Omnipotent Options in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-network-key-harmony-5-steps-for-windows-error-resolution/"><u>Mastering Network Key Harmony: 5 Steps for Windows Error Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/one-account-gpo-tailoring-in-the-modern-windows-environment-11-11/"><u>One-Account GPO Tailoring in the Modern Windows Environment (11, 11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-your-cursor-lighting-with-windows-11-tips/"><u>Optimize Your Cursor Lighting with Windows 11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-directive-not-empty-hurdle-insights-to-eradicate-error-0x80070091/"><u>Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfect-your-audio-screen-recordings-using-the-snipping-tool-max-156/"><u>Perfect Your Audio Screen Recordings Using the Snipping Tool (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-remedying-windows-11-package-complications/"><u>Quick Fixes: Remedying Windows 11 Package Complications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/running-windows-11-on-classics-utilizing-windows-to-go-and-rufus-guide/"><u>Running Windows 11 on Classics - Utilizing Windows To Go & Rufus Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-authentication-disabling-questions-on-windows-11-local-account/"><u>Silent Authentication: Disabling Questions on Windows 11 Local Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-excel-display-in-windows-notepad/"><u>Solutions for Excel Display in Windows Notepad</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-unresolvable-value-errors-in-winos/"><u>Solutions for Unresolvable Value Errors in WinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-error-0x80246007-in-windows-update-for-1011-os/"><u>Solving Error 0X80246007 in Windows Update for 10/11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-multilingual-translation-the-power-of-windows-shortcut-hotkeys/"><u>Speedy Multilingual Translation: The Power of Windows Shortcut Hotkeys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-gaps-within-explore-interface-elements/"><u>Tackling Gaps Within Explore Interface Elements</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-6-youtube-outros-made-easy-and-free-guide-for-2024/"><u>Top 6 YouTube Outros Made Easy & FREE (Guide) for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbocharging-yuzus-performance-on-pcs/"><u>Turbocharging Yuzu's Performance on PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->