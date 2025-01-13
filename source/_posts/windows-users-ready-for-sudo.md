---
title: Windows Users, Ready for Sudo?
date: 2025-01-11T22:49:12.204Z
updated: 2025-01-12T19:22:18.353Z
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

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-innovative-ideas-the-best-12-websites-to-access-no-cost-photographic-treasures/"><u>[New] In 2024, Innovative Ideas The Best 12 Websites to Access No-Cost Photographic Treasures</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-leveraging-alternative-footage-in-filmmaking/"><u>[New] Leveraging Alternative Footage in Filmmaking</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-creating-thriving-giveaways-a-facebook-marketers-blueprint-for-2024/"><u>[Updated] Creating Thriving Giveaways A Facebook Marketer's Blueprint for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-double-your-reach-youtube-and-facebook-cross-promotion/"><u>[Updated] Double Your Reach YouTube & Facebook Cross-Promotion</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-olympic-snowscape-highlights-cross-style-22/"><u>2024 Approved Olympic Snowscape Highlights - Cross Style '22</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-picsnapper-app-testimonials-and-feedback/"><u>2024 Approved PicSnapper App Testimonials & Feedback</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-back-your-connection-top-9-fixes-for-missing-bluetooth-in-windows-11/"><u>Bring Back Your Connection: Top 9 Fixes for Missing Bluetooth in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-ways-to-tackle-windows-rpc-errors-effectively/"><u>Easy Ways to Tackle Windows RPC Errors Effectively</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-impacts-of-ditching-windows-11s-taskbar-chatting-feature/"><u>Exploring Impacts of Ditching Windows 11'S Taskbar Chatting Feature</u></a></li>
<li><a href="https://facebook.techidaily.com/fb-twitter-and-snapchat-key-players-in-jbs-vaccine-campaign/"><u>FB, Twitter & Snapchat: Key Players in JB's Vaccine Campaign</u></a></li>
<li><a href="https://tech-haven.techidaily.com/generating-original-imagery-through-microsofts-copilot-technology-how-to/"><u>Generating Original Imagery Through Microsoft's Copilot Technology - How To</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-and-folder-combination-in-windows-11/"><u>Mastering File & Folder Combination in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-functioning-office-outlook-alerts/"><u>Restoring Functioning Office Outlook Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-blue-screen-0xc0000001-on-pc/"><u>Tackling Blue Screen 0xC0000001 on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tracking-and-tallying-windows-app-sizes/"><u>Tracking and Tallying Windows App Sizes</u></a></li>
<li><a href="https://win-guides.techidaily.com/unveiling-the-hidden-the-standard-position-of-the-windows-registry-explained/"><u>Unveiling the Hidden: The Standard Position of the Windows Registry Explained</u></a></li>
</ul></div>

