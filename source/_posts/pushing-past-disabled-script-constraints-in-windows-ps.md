---
title: Pushing Past Disabled Script Constraints in Windows PS
date: 2025-01-21T19:40:59.579Z
updated: 2025-01-24T22:05:54.051Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Pushing Past Disabled Script Constraints in Windows PS
excerpt: This Article Describes Pushing Past Disabled Script Constraints in Windows PS
keywords: Overcoming PSScriptError,Disabling JS Errors on WinPS,Extend PS Capabilities,Bypassing Script Block Limits,Enhance Windows PowerShell,Eliminate PS Constraints,Improve Script Execution
thumbnail: https://thmb.techidaily.com/b4a905fd890aa115ceaae449b319ec44a08a343a14b9f46ade584251a7832338.jpg
---

## Pushing Past Disabled Script Constraints in Windows PS

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

## 2\. Change the Execution Policy in PowerShell

 In some instances, changing the execution policy could help. But before we explore the solutions, let’s first take you through what the execution policy is and how it works.

### What Is the Execution Policy, and How Does It Work?

 The execution policy is a security feature that controls the way you run PowerShell scripts on your device. It simply determines which types of scripts can be run and which ones should be avoided. The best part is that you can configure this policy to your liking.

 Here are the options you can pick from when configuring the execution policy:

* **Restricted**: This policy prohibits you from running any PowerShell script.
* **Unrestricted**: Allows you to run any script but shows you a warning message when you run suspicious scripts.
* **RemoteSigned**: This policy requires a digital signature when you run the scripts that you downloaded online. However, it doesn’t require a signature for local scripts.
* **ByPass**: This allows you to run any script without any restrictions. Unlike the "Unrestricted" policy, the "ByPass" policy won’t show you any warning messages when you run suspicious scripts. So, always apply this policy only when running legit scripts.
* **AllSigned**: This policy only runs scripts that are signed by a trusted publisher.

 Now, if you use PowerShell regularly, then you might want to change the execution policy from time to time. However, some execution policies might display error messages when you run your PowerShell scripts.

 For example, enabling the “Restricted,” “AllSigned,” or “RemoteSigned” policies might lead to error messages like the "running scripts is disabled" error.

 To resolve the problem, you'd simply have to change the execution policy to “Unrestricted” or “ByPass.” But that’s not all; you'd also need to decide how the policy should be implemented. For example, do you want to apply the policy for all users or just for your current PowerShell session?

 Let's explore all the additional [PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) you’ll have to add when changing the execution policy:

* **CurrentUser**: This policy will only be applied to all the PowerShell sessions of the person who has currently logged in on the device.
* **LocalMachine**: Applies to all the users that have an account on the device. This policy can only be configured by local users that have administrative privileges.
* **Process**: Only applies on the current PowerShell session. This means you’ll have to execute the policy again if you start a new session.
* **MachinePolicy**: This policy applies to all the users who have an account on your device. However, it can only be configured by network administrators who have appropriate permissions. But it's often possible for local administrators to configure this execution policy using the Local Group Policy Editor.
* **UserPolicy**: Applies to all PowerShell sessions and the scripts executed by a particular user.

 Now that everything is clear, let’s explore how you can execute the relevant policies to tackle the "PowerShell cannot load" issue.

### How to Change the Execution Policy to "Unrestricted"

 The best way to tackle the issue at hand is to change the execution policy to "unrestricted." But before that, you need to check how each execution policy is configured.

 Here are the steps for checking how the execution policies are configured:

1. Press **Win + X** to open the Quick Access Menu.
2. Select **Windows PowerShell (Admin)** from the options.
3. Type the following command and press **Enter**:

`Get-ExecutionPolicy -List`

![Displaying the list of execution policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/displaying-the-list-of-execution-policies.jpg)

 This should show you how the execution policies are configured for different users and systems.

 To can change the execution policy to “Unrestricted” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

![Setting the execution policy on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/setting-the-execution-policy-on-powershell.jpg)

 To change the execution policy to “Unrestricted” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy Unrestricted -Scope LocalMachine`

 When you finish running the command, close PowerShell and restart your PC to save these changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Change the Execution Policy to "ByPass"

 The "ByPass" execution policy will allow you to run any PowerShell script without a hassle. But remember that it might also allow you to run buggy files. So, always configure this execution policy only when running trustworthy PowerShell files.

 To change the execution policy to “ByPass” for the current active user, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope CurrentUser`

 And to change the execution policy to “ByPass” for all users, type the following command and press **Enter**:

`Set-ExecutionPolicy ByPass -Scope LocalMachine`

 When you finish, close PowerShell and then restart your device.

## 3\. Change the Execution Policy Via the Local Group Policy Editor

![A lady using a Windows PC while holding a cup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-a-Windows-PC-while-holding-a-cup.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)

 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.

## 4\. Change the Execution Policy Using the Registry Editor

![A lady using her Windows PC while sitting on bed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-lady-using-her-Windows-PC-while-sitting-on-bed.jpg)

 If the other methods didn’t help, then try changing the execution policy using the Registry Editor. However, you need to be careful when editing Registry keys. If you tweak the wrong keys, then you might end up damaging your PC.

 Now, here’s how to change the execution policy via the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\PowerShell\1\ShellIds\Microsoft.PowerShell`

 Locate the **ExecutionPolicy** value on the right-hand side.

![Selecting the ExecutionPolicy value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/selecting-the-executionpolicy-value.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-capturing-screenshots-like-a-pro-the-best-recorder-reviews/"><u>[New] Capturing Screenshots Like a Pro The Best Recorder Reviews</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/our-first-step-designing-attractive-videos-on-a-mac-for-2024/"><u>[New] Your First Step Designing Attractive Videos on a Mac for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-light-and-shadow-with-iphone-xs-new-lens-technology/"><u>[Updated] Mastering Light & Shadow with iPhone X's New Lens Technology</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-resolution-duel-comparing-gopro-hero-and-polaroid-cube/"><u>[Updated] Resolution Duel Comparing GoPro Hero and Polaroid Cube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-0x8009030e-in-hyper-v-virtualization-windows/"><u>Correcting Error 0X8009030E in Hyper-V Virtualization Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decorating-taskbar-step-by-step-on-adding-a-weather-indicator-to-windows-11/"><u>Decorating Taskbar: Step-by-Step on Adding a Weather Indicator to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-way-to-turn-onoff-in-hand-typing-windows/"><u>Easy Way to Turn On/Off In-Hand Typing Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-1011-searcher-that-skips-results/"><u>Fixing Windows 10/11 Searcher That Skips Results</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-files-for-samsung-galaxy-f54-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD .mts files for Samsung Galaxy F54 5G? </u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-realme-c67-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Realme C67 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-discover-the-top-30-free-intro-creators-on-youtube/"><u>In 2024, Discover the Top 30 Free Intro Creators on YouTube</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ultimate-racing-game-anthology-the-top-five/"><u>In 2024, Ultimate Racing Game Anthology The Top Five</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-microsofts-world-efficient-commands-at-your-fingertips/"><u>Navigating Microsoft's World: Efficient Commands at Your Fingertips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-no-mistakes-essential-errors-to-evade-in-windows-11/"><u>Navigating No Mistakes: Essential Errors to Evade in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-xp019-error/"><u>Overcoming Windows XP019 Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overhauling-windows-11-terminal-configuration/"><u>Overhauling Windows 11 Terminal Configuration</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-visual-glitches-updating-your-graphics-driver-for-forza-horizon-5/"><u>Solving Visual Glitches: Updating Your Graphics Driver for Forza Horizon 5</u></a></li>
<li><a href="https://win11-tips.techidaily.com/trailblazing-through-windows-10s-past-actions/"><u>Trailblazing Through Windows 10'S Past Actions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveil-the-covert-tracker-steps-to-activate-and-employ-the-secret-sidebar-bar/"><u>Unveil the Covert Tracker: Steps to Activate and Employ the Secret Sidebar Bar</u></a></li>
</ul></div>

