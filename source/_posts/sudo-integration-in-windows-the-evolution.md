---
title: "Sudo Integration in Windows: The Evolution"
date: 2024-09-09T18:10:42.916Z
updated: 2024-09-16T20:09:10.165Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sudo Integration in Windows: The Evolution"
excerpt: "This Article Describes Sudo Integration in Windows: The Evolution"
keywords: Windows Sudo Integration,Sudo & Windows Evolve,Windows PowerShell Cmdlets,Enhanced Windows Security,Secure Admin Access Windows,Advanced Windows System,Powerful Windows Admin Tools
thumbnail: https://thmb.techidaily.com/ec5c93589cbbf4437a85d01509aad074c0824b7a47a862a6e3798990cfe51fb1.png
---

## Sudo Integration in Windows: The Evolution

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139116/17108" target="_top" id="2139116">
  <img src="//a.impactradius-go.com/display-ad/17108-2139116" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139116/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-beyond-the-lens-innovative-ideas-for-youtube-video-creation/"><u>[Updated] 2024 Approved Beyond the Lens Innovative Ideas for YouTube Video Creation</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-capture-perfection-the-best-live-stream-recorders-ranked/"><u>[Updated] Capture Perfection The Best Live Stream Recorders Ranked</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-expert-tips-for-captivate-based-demos-for-2024/"><u>[Updated] Expert Tips for Captivate-Based Demos for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-y17s-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo Y17s</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/effortless-techniques-for-converting-your-dvds-into-high-quality-avi-files/"><u>Effortless Techniques for Converting Your DVDs Into High-Quality AVI Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-inability-to-open-files-for-writing-in-windows-11/"><u>How to Rectify Inability to Open Files For Writing in Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-xs-max-i-do-get-answers-here-drfone-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone XS Max i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-functionality-legacy-keys-in-windows-narrator/"><u>Maximizing Functionality: Legacy Keys in Windows Narrator</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-launchpad-experience-with-top-techniques-for-windows-11/"><u>Transforming Launchpad Experience with Top Techniques for Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-rogue-company-how-to-prevent-pc-disruptions/"><u>Troubleshooting Rogue Company: How to Prevent PC Disruptions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-finding-lost-enhancement-tab-quick-fix-guide/"><u>Windows 11: Finding Lost Enhancement Tab - Quick Fix Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    