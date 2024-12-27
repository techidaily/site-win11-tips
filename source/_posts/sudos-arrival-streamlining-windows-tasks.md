---
title: "Sudo's Arrival: Streamlining Windows Tasks"
date: 2024-12-23T21:02:48.816Z
updated: 2024-12-27T17:30:19.379Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Sudo's Arrival: Streamlining Windows Tasks"
excerpt: "This Article Describes Sudo's Arrival: Streamlining Windows Tasks"
keywords: Sudo in Windows,Windows Task Automation,Efficient Windows Tasks,Simplify Windows Commands,Powerful Shell Script,Enhanced Command Line,Streamlined Windows Operations
thumbnail: https://thmb.techidaily.com/8cc7746fe0672e4725ddd5d1492632738fafd136f8e04394f483f1432a572415.png
---

## Sudo's Arrival: Streamlining Windows Tasks

### Key Takeaways

* The sudo command on Windows lets you run commands with elevated privileges.
* Microsoft is introducing sudo in Windows 11 to make using the command line more convenient.
* Enable sudo via Settings, the Command Prompt, or PowerShell.

 If you're a fan of tweaking your Windows setup, you often need to run "elevated" or Administrator-level commands. You're probably used to doing this by running a Command Prompt as administrator, but it's about to get a lot easier with sudo on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Does the sudo Command Do?

 Despite the general focus on configuring everything through the Settings apps and easy-to-use configuration wizards on Windows, every once in a while, you still need to type in commands. Many of these won't work with your standard user account. Instead, you need to run them as an administrator. Requiring administrator permissions is still a relatively new concept in Windows, but it was prevalent for far longer in older operating systems.

 It was so prevalent that operating system developers thought about a solution to the problem decades ago. Unix installations had, and still do have, a `su` command, which means "switch user." This would allow you to switch accounts to any other user, but could also let you run as the administrator, or superuser, account of the system by default.

 This solution worked, but logging in as the administrator to run one command seemed like overkill. As a solution, developers created the sudo command, which means either "switch user and do," or "superuser do," depending on various opinions. Long story short, the sudo command lets you easily run one command with elevated privileges—we've covered [the differences between su and sudo](http://www.makeuseof.com/sudo-vs-su/) if you're curious.

 This means that the sudo command is roughly equivalent to right-clicking on the Command Prompt app, selecting **Run as administrator**, and running a command, like `do_something`. With the help of the sudo command, you don't need to worry about remembering to run the Command Prompt as administrator. Instead, simply type `sudo do_something`, and the command will work in exactly the same way.

## Which Windows Versions Can Run the sudo Command?

 Microsoft is adding the sudo command to Windows 11, and considering that support for Windows 10 is winding down, we don't expect to see the command coming there anytime soon. At the time of writing, the sudo command is only available for Windows Insider participants (builds 26045 and later), specifically those on the Developer and [Windows Canary channels](https://www.makeuseof.com/what-is-windows-insider-canary-channel/).

 Unlike some features that Microsoft tests in these versions, it seems fairly likely that sudo is going to arrive on the operating system soon.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the sudo Command on Windows

 If the sudo command isn't yet available for your version of Windows, you'll need to [sign up for Windows Insider](https://www.makeuseof.com/windows-11-insider-program-join/). This is a simple process, but be warned: the Developer and Canary options can be unstable, so don't use them on a PC you're not willing to lose data on.

 Once you're running a version of Windows that has the sudo command available, enabling it is a simple process. Open the **Settings** app, then select **System** on the left and **For developers** from the main area of the window.

 Here, scroll down and enable the checkbox that reads **Enable sudo**.

![Enabling sudo on Window in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-window-in-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Enable sudo via the Command Prompt

 If you're more command-line oriented, you can also enable sudo via the Commmand Prompt. Somewhat ironically, this requires you to run an elevated CMD window. Press the **Windows** key, type "command," then right-click on **Command Prompt** (or **PowerShell**) and select **Run as administrator**.

 In this prompt, run the following command:

`sudo config --enable enable`

![Enabling sudo on Windows via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/enabling-sudo-on-windows-via-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use the sudo Command on Windows

 After you've enabled the sudo command on Windows, it's simple to use. Simply prepend the `sudo` command to any command you'd typically need to run as an administrator, then accept the prompts that follow.

 An example from Microsoft uses the `netstat` command:

`sudo netstat -ab  
`

![Running a command on Windows via sudo](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/03/running-a-command-on-windows-via-sudo.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-boosting-snapchat-vibes-with-smart-editing-tricks/"><u>[New] In 2024, Boosting Snapchat Vibes with Smart Editing Tricks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-unlock-the-secrets-of-slow-motion-expert-advice-using-photo-apps-and-websites/"><u>[New] In 2024, Unlock the Secrets of Slow Motion Expert Advice Using Photo Apps & Websites</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-expert-tips-for-automated-google-meet-timings/"><u>[Updated] 2024 Approved Expert Tips for Automated Google Meet Timings</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhance-your-coding-workflow-essential-tips-to-pair-chatgpt-with-visual-studio-code/"><u>Enhance Your Coding Workflow: Essential Tips to Pair ChatGPT with Visual Studio Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-windows-11s-package-control-using-wingetui/"><u>Enhancing Windows 11'S Package Control Using WingetUI</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhancing-your-social-media-footprint-upload-success-tips-for-stories-for-2024/"><u>Enhancing Your Social Media Footprint Upload Success Tips for Stories for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Nokia 130 Music | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-correct-lsassexe-not-found-error-on-pc/"><u>How to Correct 'lsass.exe' Not Found Error on PC</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-get-verified-on-instagram-6-tips-to-grow-followers-for-2024/"><u>How to Get Verified on Instagram 6 Tips to Grow Followers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-the-problem-when-your-logitech-mouse-scroll-isnt-working/"><u>How to Solve the Problem When Your Logitech Mouse Scroll Isn't Working</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-y200e-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Vivo Y200e 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-your-onedrive-without-an-online-connection/"><u>Navigate Your OneDrive Without an Online Connection</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-install-guide-adding-portable-menu-items-on-w11/"><u>Quick Install Guide: Adding Portable Menu Items on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-find-and-restore-lost-pin-in-win-11-update-fallout/"><u>Steps to Find and Restore Lost PIN in Win 11 Update Fallout</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-for-restoring-file-download-capabilities-within-google-chrome-windows/"><u>Tips for Restoring File Download Capabilities Within Google Chrome, Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-high-cpu-use-by-windows-extender/"><u>Unraveling High CPU Use by Windows Extender</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-back-your-search-power-tips-to-troubleshoot-windows-11s-search-issues/"><u>Winning Back Your Search Power: Tips to Troubleshoot Windows 11'S Search Issues</u></a></li>
</ul></div>

