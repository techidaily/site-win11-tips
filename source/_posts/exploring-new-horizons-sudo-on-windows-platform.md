---
title: "Exploring New Horizons: Sudo on Windows Platform"
date: 2024-10-16T04:52:30.826Z
updated: 2024-10-21T02:08:12.039Z
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

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-how-much-space-does-a-days-video-take-up/"><u>[New] How Much Space Does a Day's Video Take Up?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-revamping-educational-experiences-through-vr/"><u>[New] Revamping Educational Experiences Through VR</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-dial-down-audio-slowly-and-steadily/"><u>[Updated] Dial Down Audio, Slowly and Steadily</u></a></li>
<li><a href="https://win11-tips.techidaily.com/directory-discovery-3-approaches-on-windows-os/"><u>Directory Discovery: 3 Approaches on Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-on-managing-users-in-the-cli/"><u>Expert Tips on Managing Users in the CLI</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/forty-plus-fluency-unleashing-the-power-of-multilingualism-today/"><u>Forty-Plus Fluency: Unleashing the Power of Multilingualism Today</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-itel-p55plus-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/saving-your-cortana-experiences-step-by-step-guide/"><u>Saving Your Cortana Experiences: Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-overcoming-access-issues-with-voice-typing-feature-in-google-keyboard/"><u>Step-by-Step Guide: Overcoming Access Issues with Voice Typing Feature in Google Keyboard</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-11-rdp-fails-internal-error-resolution/"><u>Tackling Windows 11 RDP Fails: Internal Error Resolution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/title-customize-windows-1011-icons-with-spacing-tweaks/"><u>Title: Customize Windows 10/11 Icons with Spacing Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-frozen-shift-on-windows-pcs/"><u>Unlock Frozen Shift on Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-oppo-find-x6-pro-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Oppo Find X6 Pro Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-through-improvement-not-just-innovation/"><u>Winning Through Improvement, Not Just Innovation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    