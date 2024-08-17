---
title: "The Sudo Tool Is Coming to Windows: How and Why to Use It"
date: 2024-08-16T01:39:03.926Z
updated: 2024-08-17T01:39:03.926Z
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

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-a-creators-guide-to-understanding-youtube-policies/"><u>[New] 2024 Approved  A Creator’s Guide to Understanding YouTube Policies</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-how-to-screen-record-on-iphone-in-an-easy-way/"><u>[New] 2024 Approved  How to Screen Record on Iphone in An Easy Way?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-samsung-ubd-k8500-review/"><u>[New] 2024 Approved  Samsung UBD-K8500 Review</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-toggle-off-instagram-tv-feature/"><u>[New] 2024 Approved  Toggle Off Instagram TV Feature</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-quick-and-easy-caption-crafting-for-engaging-fb-video-posts/"><u>[New] In 2024, Quick and Easy Caption Crafting for Engaging FB Video Posts</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-mobile-screening-guide-gogooglemeetrecorder-tips/"><u>[Updated] 2024 Approved  Mobile Screening Guide  GoGoogleMeetRecorder Tips</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-top-tier-hd-screen-recording-technology/"><u>[Updated] In 2024, Top-Tier HD Screen Recording Technology</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-step-by-step-guide-to-elevating-your-channel-brand-growth-in-viewers/"><u>[Updated] Step-by-Step Guide to Elevating Your Channel Brand, Growth in Viewers</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-zenith-workspace-in-depth-studio-overview-2023-edition/"><u>2024 Approved  Zenith Workspace  In-Depth Studio Overview, 2023 Edition</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/5-best-snipping-tools-for-windows/"><u>5 Best Snipping Tools for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/abruptly-quell-windows-11-interruptions/"><u>Abruptly Quell Windows 11 Interruptions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-pruveeo-f5-full-hd-1080p-dashcam-analysis/"><u>Affordable Pruveeo F5 Full HD 1080P Dashcam Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/delving-into-the-restricted-world-of-windows-11/"><u>Delving Into the Restricted World of Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/discovering-direct-conversations-on-snapchat-in-a-click-for-2024/"><u>Discovering Direct Conversations on Snapchat in a Click for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dissecting-update-processes-windows-os-explored/"><u>Dissecting Update Processes: Windows OS Explored</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-updating-and-downloading-for-your-amd-rx-480-graphics-card/"><u>Effortless Updating & Downloading for Your AMD RX 480 Graphics Card</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-control-running-task-manager-with-admin-rights-in-win11/"><u>Enhance Control: Running Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-techniques-to-resolve-error-code-3-on-gl-drivers/"><u>Expert Techniques to Resolve Error Code 3 on GL Drivers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-lava-blaze-pro-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Lava Blaze Pro 5G? Try These Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-handle-iphone-photo-import-errors-on-computers/"><u>How to Handle iPhone Photo Import Errors on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prevent-full-disk-notification-in-windows/"><u>How To Prevent Full Disk Notification in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resurrect-lost-keyboard-erase-functionality/"><u>How to Resurrect Lost Keyboard Erase Functionality</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-14-plus-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone 14 Plus Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-vivo-y27s-phone-by-drfone-android/"><u>How to Unlock a Network Locked Vivo Y27s Phone?</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/implementing-dark-theme-in-windows-calculator/"><u>Implementing Dark Theme in Windows Calculator</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-apple-iphone-8-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on Apple iPhone 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/investigating-post-blue-screen-events-on-windows-7/"><u>Investigating Post-Blue Screen Events on Windows 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/lost-in-5ghz-revive-your-connection-with-these-fixes-for-windows-11/"><u>Lost in 5GHz? Revive Your Connection with These Fixes for Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/mastering-the-art-of-graphics-card-upgrades-what-you-need-to-know/"><u>Mastering the Art of Graphics Card Upgrades - What You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastery-over-windows-automatic-lock-settings/"><u>Mastery over Windows Automatic Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximize-window-11-with-these-6-desirable-android-apps/"><u>Maximize Window 11 With These 6 Desirable Android Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-3-windows-group-policy-approaches/"><u>Navigating 3 Windows Group Policy Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-better-with-terminal-set-as-default/"><u>Navigating Better with Terminal Set as Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-power-settings-fully-charged-notifications-for-win11/"><u>Navigating Power Settings: Fully Charged Notifications for Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-the-command-prompt-landscape-for-admin-tasks/"><u>Navigating the Command Prompt Landscape for Admin Tasks</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-s-most-popular-mkv-clip-editors-for-mac/"><u>New In 2024, S Most Popular MKV Clip Editors for Mac</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-device-reset-failed-in-windows-11/"><u>Overcoming 'Device Reset Failed' In Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-file-access-barriers-with-powershell/"><u>Overcoming File Access Barriers with PowerShell</u></a></li>
<li><a href="https://win11-tips.techidaily.com/perfecting-file-formats-transforming-docx-into-plain-pdf-text-via-windows-11/"><u>Perfecting File Formats: Transforming DOCX Into Plain PDF Text via Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-fixes-utilizing-the-eraser-tool-in-psx-for-2024/"><u>Quick Fixes  Utilizing the Eraser Tool in PSX for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-visuals-applying-microsoft-store-themes-in-windows/"><u>Reimagining Visuals: Applying Microsoft Store Themes in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-unwanted-camera-request-errors-code-0xa00f4243/"><u>Removing Unwanted Camera Request Errors (Code 0xA00F4243)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reviving-unseen-networks-a-win11-guide/"><u>Reviving Unseen Networks: A Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-bypassing-windows-11-sign-in-errors/"><u>Strategies for Bypassing Windows 11 Sign-In Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-to-enable-nvidia-cp-setting-retention-in-win11/"><u>Strategies to Enable Nvidia CP Setting Retention in Win11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/troubleshooting-woes-solving-lords-of-mayhem-computer-freeze-issues/"><u>Troubleshooting Woes: Solving 'Lords of Mayhem' Computer Freeze Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-windows-upgrade-notifications/"><u>Turn Off Windows Upgrade Notifications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/understanding-youtube-shorts-earning-potential-for-2024/"><u>Understanding YouTube Shorts Earning Potential for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/unraveling-instagrams-video-sideways-quandary-for-2024/"><u>Unraveling Instagram's Video Sideways Quandary for 2024</u></a></li>
</ul></div>
