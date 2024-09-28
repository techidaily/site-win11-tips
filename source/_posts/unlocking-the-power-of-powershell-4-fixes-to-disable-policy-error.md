---
title: "Unlocking the Power of PowerShell: 4 Fixes to Disable Policy Error"
date: 2024-09-24T16:54:43.623Z
updated: 2024-09-28T18:01:29.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking the Power of PowerShell: 4 Fixes to Disable Policy Error"
excerpt: "This Article Describes Unlocking the Power of PowerShell: 4 Fixes to Disable Policy Error"
keywords: Disabling Policy Errors PS,PowerShell Control FIX,Enhance PowerShell Usage,PowerShell Policy Management,Mastering PSScriptRun,Resolving PS Errors Ease,Optimize Script Execution PS
thumbnail: https://thmb.techidaily.com/d24f731fb7d4e16e9e3dad20fbd83add26d8b00ef3415c454c76fbd282fafbfc.jpg
---

## Unlocking the Power of PowerShell: 4 Fixes to Disable Policy Error

 You’re running some commands on PowerShell and suddenly see an error message that reads, “PowerShell cannot be loaded because running scripts is disabled on this system.”

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run PowerShell in Administrator Mode

 Are you currently running PowerShell without proper administrative rights? If so, then perhaps that’s where the issue lies.

 So, let’s explore the steps you should apply to run the tool in administrator mode:

1. Press **Win + X** to open the Quick Access menu.
2. Select the **Windows PowerShell (Admin)** option.

![Selecting the Windows PowerShell (Admin) option on the Quick Access Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/selecting-the-windows-powershell-admin-option-on-the-quick-access-menu.jpg)

 And if that doesn’t help, check out [the various ways to open Windows PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/). But you should only focus on the methods that show you how to run the tool with administrative privileges.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2105882/7443" target="_top" id="2105882">
  <img src="//a.impactradius-go.com/display-ad/7443-2105882" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105882/7443" style="position:absolute;visibility:hidden;" border="0" />
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

 The Local Group Policy Editor (LGPE) also makes it easy for you to change the execution policy. In fact, this tool can also help you configure various system settings or troubleshoot tons of PC issues.

 Remember, the main aim is to change the execution policy such that you’ll be able to run your PowerShell scrips without a hassle. And by so doing, you’ll get rid of the “running scripts is disabled” error on PowerShell.

 Here’s how to change the execution policy in the LGPE:

1. Type **Edit group policy** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various ways to open the LGPE](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows PowerShell**.
3. Double-click on the **Turn on Script Execution** option.

![Clicking the Turn on Script Execution option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clicking-the-turn-on-script-execution-option.jpg)

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check the **Enabled** box. From there, click the **Execution Policy** drop-down menu and select **Allow local scripts and remote signed scripts**. This option is similar to the "RemoteSigned" option that we discovered earlier.

 If you want to run all scripts without restrictions, pick the **Allow all scripts** option from the "Execution Policy" drop-down menu.

 From there, click **Apply** and then click **OK** to save these changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 If the value is missing, create it through these steps:

1. Right-click on a blank space on the right-hand side.
2. Select **New > DWORD (32-bit) Value**.
3. Name the value as **ExecutionPolicy** and press **Enter**.

 Double-click on the **ExecutionPolicy** value. Next, type **RemoteSigned** in the "Value data" section. This will allow PowerShell to execute local and signed scripts.

 Alternatively, type **ByPass** in the "Value data" section. This will allow PowerShell to execute any script without limitations.

 After entering your preferred value in the "Value data" section, press **OK** to save the changes. Finally, close the Registry Editor and then restart your device.

## Run Your PowerShell Scripts Without Any Restrictions

 It can be quite frustrating when you suddenly can’t execute certain commands on Windows PowerShell. But if you come across the “scripts is disabled” error, the solutions we’ve covered should help.

 Now, does PowerShell often give you other issues? Well, there are more solutions that can help you out.

 Wondering what causes this issue and how you can resolve it? We’ll take you through the easy methods that can help you tackle this issue once and for all.

 Let’s dive in!

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-rhythm-ringtone-converting-tamil-music-into-phone-chimes/"><u>2024 Approved Rhythm Ringtone Converting Tamil Music Into Phone Chimes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/altering-default-cmd-settings-with-ease/"><u>Altering Default CMD Settings with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/digital-expression-unleashed-crafting-metaverse-memes/"><u>Digital Expression Unleashed Crafting Metaverse Memes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-handling-widget-notifications-win-11-style/"><u>Efficiently Handling Widget Notifications Win 11 Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-the-crash-of-windows-update-error-x712/"><u>Fixing the Crash of Windows Update Error X712</u></a></li>
<li><a href="https://driver-download.techidaily.com/guide-to-fixing-hp-beats-headphones-sound-issues-in-windows-1187/"><u>Guide to Fixing HP Beats Headphones Sound Issues in Windows 11/8/7</u></a></li>
<li><a href="https://extra-support.techidaily.com/inside-out-essential-vr-dictionary-words-for-2024/"><u>Inside Out Essential VR Dictionary Words for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/modifier-sans-frais-transformer-vos-images-jpeg-en-jpg-a-laide-de-movavi-online/"><u>Modifier Sans Frais : Transformer Vos Images JPEG en JPG À L'aide De Movavi Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-comics-an-intuitive-approach-for-win11-users/"><u>Navigating Comics: An Intuitive Approach for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-lost-default-windows-11-power-settings/"><u>Reinstating Lost Default Windows 11 Power Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-microsoft-store-blockage-issue-on-win11/"><u>Resolving Microsoft Store Blockage Issue on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategies-for-correcting-severe-browser-js-problem-in-discord/"><u>Strategies for Correcting Severe Browser JS Problem in Discord</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-top-10-screenshot-tools-of-2021-for-2024/"><u>The Top 10 Screenshot Tools of 2021 for 2024</u></a></li>
<li><a href="https://solve-helper.techidaily.com/top-rated-macavchd-video-converter-free-software-guide-and-downloads/"><u>Top Rated MacAVCHD Video Converter: Free Software Guide & Downloads</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unleashing-the-power-of-dji-robomaster-s1-a-fun-filled-tank-drone-with-interactive-battles-and-learning-opportunities/"><u>Unleashing the Power of DJI RoboMaster S1 – A Fun-Filled Tank Drone with Interactive Battles and Learning Opportunities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-secrets-efficient-qr-codes-on-windows-systems/"><u>Unlocking Secrets: Efficient QR Codes on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-11s-secure-testing-solution-enabling-and-configuring-sandbox/"><u>Win 11'S Secure Testing Solution: Enabling and Configuring Sandbox</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    