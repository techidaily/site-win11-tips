---
title: "Exploring New Horizons: Sudo on Windows Platform"
date: 2024-10-20T17:04:44.774Z
updated: 2024-10-26T21:02:04.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring New Horizons: Sudo on Windows Platform"
excerpt: "This Article Describes Exploring New Horizons: Sudo on Windows Platform"
keywords: Windows Sudo Guide,Windows Sudo Security,Linux Sudo Tips,Sudo Command Explanation,Sudo Access Control,Command Line Power,Sudo Usage Instructions
thumbnail: https://thmb.techidaily.com/c68e5dfe066870e624209e946a88b5eb21db8406cf2fae44c9a446c53d02efdc.jpg
---

## Exploring New Horizons: Sudo on Windows Platform

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-proven-youtube-seo-tricks-boosting-video-reach-and-visibility/"><u>[New] In 2024, Proven YouTube SEO Tricks Boosting Video Reach and Visibility</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-streamlined-coordination-the-best-facebook-timetellers-ranked/"><u>[New] Streamlined Coordination The Best Facebook Timetellers Ranked</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-explaining-video-trims-the-logic-of-trimming/"><u>[Updated] In 2024, Explaining Video Trims The Logic of Trimming</u></a></li>
<li><a href="https://app-tips.techidaily.com/boost-your-efficiency-with-slack-mastering-the-apps-top-features-for-enhanced-workflow-zdnet/"><u>Boost Your Efficiency with Slack: Mastering the App's Top Features for Enhanced Workflow | ZDNet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-troubleshoot-and-repair-shortcuts-win-11-style/"><u>Correct: Troubleshoot and Repair Shortcuts, Win 11 Style</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/creating-effective-fitness-plans-with-safe-guidance/"><u>Creating Effective Fitness Plans with Safe Guidance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-complexities-of-windows-iscsi-initiator/"><u>Decoding the Complexities of Windows iSCSI Initiator</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-zte-blade-a73-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the ZTE Blade A73 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-moves-in-sw-quick-fixed-for-windows-mouse-lag-woes/"><u>Master Moves in SW: Quick Fixed for Windows Mouse Lag Woes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-snapchats-help-options-how-to-get-in-touch-with-their-team/"><u>Navigating Snapchat's Help Options: How to Get in Touch with Their Team</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preserving-calculators-zenith-in-windows-settings/"><u>Preserving Calculator's Zenith in Windows Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speed-up-disabling-windows-11-alerts/"><u>Speed Up Disabling Windows 11 Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-windows-11-writable-state-with-keys/"><u>Unlocking Windows 11' Writable State with Keys</u></a></li>
</ul></div>

