---
title: The Definitive Guide to Configuring Script Policies in PS
date: 2024-06-25T17:03:00.240Z
updated: 2024-06-26T17:03:00.240Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Definitive Guide to Configuring Script Policies in PS
excerpt: This Article Describes The Definitive Guide to Configuring Script Policies in PS
keywords: Policy Configuration PS Guide,Script Settings Guide PS,PS Policy Management Tips,Setting Script Rules PS,Mastering PS Policy Configure,PS Script Policies Expertise,Configuring PS Scripts Definitive
thumbnail: https://thmb.techidaily.com/e12562333e85045ab9221a99e913b83b793150ee785e5f59fee7c9f18bec3976.png
---

## The Definitive Guide to Configuring Script Policies in PS

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy ![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell ![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

 You can use a [PowerShell cmdlet](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) to set the execution policy to RemoteSigned. The command-line interface makes it easy to change execution policy quickly without using the Settings app.

 Also, the Settings app can only enable or disable the RemoteSigned execution policy. Whereas PowerShell lets you set other policies and scopes as well.

To change the execution policy using PowerShell:

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Set-ExecutionPolicy RemoteSigned`
3. If prompted, press**A** to confirm the action. This will set the**RemoteSigned** execution policy for all users. If you want to set the execution policy for the**Current User** only, use the Scope parameter followed by the username.
4. For example, to set the**RemoteSigned** execution policy for**CurrentUser** , use the following command:  
`Set-ExecutionPolicy RemoteSgined -Scope CurrentUser`
5. Replace**CurrentUser** in the above command with other users (Scope) as per your requirement.

## How to Remove Script Execution Policy Using PowerShell ![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

 If you want to disable script execution, set the execution policy to**Undefined** using th**e Set\_ExecutionPolicy** cmdlet. This is a default state and prevents PowerShell from executing any scripts.

To disable script execution using PowerShell:

1. Open PowerShell with elevated permission.
2. Next, type the following command and press enter to disable script execution for all users:  
`Set-ExecutionPolicy undefined`
3. The above command will set the execution policy default (undefined) for all the users. If you want to disable script execution for a specific scope, use the following command:  
`Set-ExecutionPolicy undefined -Scope CurrentUser`
4. The above command will disable script execution for**CurrentUser** .

## Understanding Execution Policies and Scopes

 Simply put, PowerShell’s execution policy is a policy that controls how PowerShell executes config files and scripts. The intended purpose is to prevent users from accidentally running malicious scripts. The seven PowerShell execution policies are **Default, Restricted, RemoteSigned, AllSigned, Unrestricted, Bypass, and Undefined** .

 The below table briefly explains all the PowerShell execution policies:

| Execution Policy | Enforcement                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| Default          | Sets the default execution policy as Restricted on Windows Client and RemoteSigned on Windows Server.          |
| AllSigned        | Allows execution of publisher signed scripts.                                                                  |
| Bypass           | Unrestricted execution of scripts for larger applications.                                                     |
| RemoteSigned     | Allows locally written script execution. Requires digital signatures for scripts downloaded from the internet. |
| Restricted       | Doesn’t allow script execution, but only individual PowerShell commands.                                       |
| Undefined        | Sets execution policy to Restricted for Windows clients and RemoteSigned for Windows Server.                   |
| Unrestricted     | Allow unsigned script execution with a warning for the scripts downloaded from the internet.                   |

### Execution Policy Scope

 You can set execution policy for a particular scope in PowerShell. The five execution policy scopes are**MachinePolicy, UserPolicy, Process, CurrentUser,** and**LocalMachine** .

The below table briefly explains all the execution policy scopes:

| Execution Policy Scope | Enforcement                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------- |
| UserPolicy             | Configured by a Group Policy for the current user.                                       |
| Machine Policy         | Configured by a Group Policy for all the users.                                          |
| CurrenUser             | Configured for the current user and stored in HKEY\_CURRENT\_MACHINE registry subkey.    |
| LocalMachine           | Configured for all users and stored in HKEY\_CURRENT\_MACHINE registry subkey.           |
| Process                | Affects current PowerShell session and automatically deleted when the session is closed. |

## Add or Remove PowerShell Script Execution Policy on Windows

 Script execution on PowerShell is disabled by default for Windows clients and set to RemoteSigned for Windows server. Power users, however, can change execution policies to run local, signed, and unsigned PowerShell scripts.

 Alternatively, you can bypass the PowerShell execution policy by pasting the script into a PowerShell console or ECHO your script into PowerShell standard input. This is useful if you want to execute scripts without changing the execution policy.


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
<li><a href="https://win11-tips.techidaily.com/preventing-persistent-microsoft-edge-shortcuts/"><u>Preventing Persistent Microsoft Edge Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-surprising-alerts-in-windows-security/"><u>Troubleshooting Surprising Alerts in Windows Security</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-file-ordering-with-these-7-photo-apps/"><u>Seamless File Ordering with These 7 Photo Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guide-to-reversing-frozen-dark-theme-on-computers/"><u>A Guide to Reversing Frozen Dark Theme on Computers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-windows-power-management-options/"><u>Exploring Windows' Power Management Options</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-current-windows-pass-error-in-win11win11/"><u>Solving Current Windows Pass Error in Win11/Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-on-iphone-13-mini-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account On iPhone 13 mini</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-virality-voyage-navigating-newsfeeds-with-noteworthy-posts/"><u>2024 Approved  Virality Voyage  Navigating Newsfeeds with Noteworthy Posts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-switching-mac-screenshot-types-easily/"><u>In 2024, Switching Mac Screenshot Types Easily</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-accelerated-photography-browser-for-11-os-users/"><u>In 2024, Accelerated Photography Browser for 11 OS Users</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-navigating-the-world-of-desktop-tiktok-a-step-by-step-guide/"><u>[Updated] In 2024, Navigating the World of Desktop TikTok  A Step-by-Step Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-youtubes-aspect-ratio-landscape-a-complete-tutorial/"><u>2024 Approved  Navigating YouTube's Aspect Ratio Landscape  A Complete Tutorial</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leading-free-art-pages-for-easy-no-cost-illustrations/"><u>2024 Approved  Leading Free Art Pages for Easy, No-Cost Illustrations</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-craft-unique-logos-using-complimentary-stock-graphics/"><u>In 2024, Craft Unique Logos Using Complimentary Stock Graphics</u></a></li>
</ul></div>
