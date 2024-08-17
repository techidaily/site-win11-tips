---
title: Unlock Advanced Capabilities with Windows PowerShell Policy Settings
date: 2024-08-16T01:57:35.948Z
updated: 2024-08-17T01:57:35.948Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Advanced Capabilities with Windows PowerShell Policy Settings
excerpt: This Article Describes Unlock Advanced Capabilities with Windows PowerShell Policy Settings
keywords: PowerShell Policies,Policy Management,Admin Controls,Windows Security,Access Restrictions,Command Preferences,Advanced System Config
thumbnail: https://thmb.techidaily.com/6b2ec2941933023600c9882b03f190635c85fa9ba36f059f6adc757c4d4da9ce.jpg
---

## Unlock Advanced Capabilities with Windows PowerShell Policy Settings

 iPowerShell, by default, lets you run commands (cmdlets) via its console. To execute a script, you can create a notepad file with the script code, save it with a .ps1 file extension, and execute it via the PowerShell console. You can also directly paste the script onto the console for execution.

 However, if it’s your first time executing a script via PowerShell, you’ll encounter the "running script is disabled" error. By default, script execution on PowerShell is disabled as a security measure to prevent malicious scripts from running on your system. Here we show you the two ways to enable the scrip execution policy on Windows PowerShell.

## How to Check Your Existing Execution Policy
![Powershell set execution policy undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-undefined.jpg)

 You can use a PowerShell cmdlet to get your current execution policy. Knowing your current execution policy is necessary to know if you need a policy change or not.

To get your current execution policy for the current user:

1. [Open Windows PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Type the following command in the PowerShell console and hit Enter:  
`get-executionpolicy`
3. Since you have encountered an error when executing the script, the return will likely show**Restricted** as your current execution policy.
4. If you need to view the execution policy for all the supported scopes:  
`get-executionpolicy -list`

 You’ll need to change the execution policy to RemoteSigned to run local scripts without the error. You can change the execution policy from the Settings app and PowerShell.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable PowerShell Execution Policy Using the Settings App

 You can change and set the PowerShell execution policy to RemoteSigned using the Settings app. All you have to do is tweak the PowerShell settings in the developers' section to change the execution policy to enable PowerShell script execution.

To change execution policy using Settings:

1. Press**Win + I** to open Se**t** tings.
2. Open the**Privacy & Security** tab in the left pane.
3. Next, click on**For developers.**  
![windows 11 for developers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-for-developers.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
4. Click to expand the**PowerShell** section.
5. Toggle the switch to **change the execution policy to allow local PowerShell scripts to run without signing - Require signing for remote scripts** .  
![enable powershell script execution windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-powershell-script-execution-windows-11-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Once done, open PowerShell, type get**executionpolicy,** and press**Enter** . The execution policy for the current user is now set to**RemoteSigned.**
7. If you need to disable the execution policy, toggle the PowerShell switch and set it to**Off** .

## How to Allow Scripts to Run in PowerShell using PowerShell
![Powershell set execcution policy remotesigned](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/powershell-set-execcution-policy-remotesigned.jpg)

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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Remove Script Execution Policy Using PowerShell
![set-execution-policy-undefined](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-execution-polify-undefined.jpg)

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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/ural-adventures-discovering-the-top-15-instructional-music-videos/"><u>[New] Aural Adventures  Discovering the Top 15 Instructional Music Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-spotifys-1-charting-tunes/"><u>[New] In 2024, Spotify's #1 Charting Tunes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-missing-mfc71udll-in-windows-os/"><u>Addressing Missing Mfc71u.dll in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-stuck-windows-enter-mechanism/"><u>Addressing Stuck Windows 'Enter' Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/bitlock-less-windows-defense-tactics-4-suggestions/"><u>BitLock-Less Windows Defense Tactics: 4 Suggestions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-proficiency-decoding-errors-in-windows-through-advanced-troubleshooting-techniques/"><u>Command Line Proficiency: Decoding Errors in Windows Through Advanced Troubleshooting Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/complete-examination-the-video-show-app/"><u>Complete Examination  The Video Show App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correct-disabled-volume-adjustment-on-windows/"><u>Correct Disabled Volume Adjustment on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/drive-down-compilation-times-with-android-studio-tweaks-on-windows/"><u>Drive Down Compilation Times with Android Studio Tweaks on Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-issue-brightness-settings-unresponsive-on-windows-11/"><u>Fixing the Issue: Brightness Settings Unresponsive on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-more-value-black-friday-offers-at-612-win10/"><u>Get More Value: Black Friday Offers at $6.12 Win10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hacking-the-login-loop-in-windows-1011/"><u>Hacking the Login Loop in Windows 10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-oppo-find-n3-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Oppo Find N3 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-widget-notifications-on-windows-11/"><u>How to Manage Widget Notifications on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-samsung-galaxy-s23-tactical-edition-to-mac-drfone-by-drfone-android/"><u>How to Mirror Samsung Galaxy S23 Tactical Edition to Mac? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-art-of-analytics-understanding-metrics-without-fancy-tools/"><u>In 2024, The Art of Analytics  Understanding Metrics Without Fancy Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-tecno-pova-5-pro-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-file-extraction-failures-in-windows-1110/"><u>Navigating Through File Extraction Failures in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-with-ease-the-windows-11-touchpad-guide/"><u>Navigating with Ease: The Windows 11 Touchpad Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-barriers-how-to-successfully-install-java/"><u>Overcoming Barriers: How to Successfully Install Java</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalize-auto-lock-and-screensaver-interval/"><u>Personalize Auto-Lock & Screensaver Interval</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-window-placement-with-powertoys/"><u>Personalizing Window Placement with PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-google-chrome-from-creating-new-tabs-ownself/"><u>Preventing Google Chrome From Creating New Tabs Ownself</u></a></li>
<li><a href="https://win11-tips.techidaily.com/productive-power-up-with-top-6-windows-apps-for-organizers/"><u>Productive Power-Up with Top 6 Windows Apps for Organizers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/quick-solutions-for-the-windows-80072ee2-updating-glitch/"><u>Quick Solutions for the Windows 80072EE2 Updating Glitch</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reestablishing-credible-power-consumption-forecasts-in-win-11-setup/"><u>Reestablishing Credible Power Consumption Forecasts in Win 11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-your-desktop-layout-with-one-click/"><u>Restoring Your Desktop Layout with One Click</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-printer-speed-in-windows-realm/"><u>Skyrocketing Printer Speed in Windows Realm</u></a></li>
<li><a href="https://fox-that.techidaily.com/step-by-step-solution-for-correcting-camera-zoom-on-whatsapp/"><u>Step-by-Step Solution for Correcting Camera Zoom on WhatsApp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-code-0x0001-problem-in-ge-for-windows/"><u>Steps to Resolve Code 0X0001 Problem in GE for Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-resolving-file-corrupted-error-x70-on-windows-1011/"><u>Swiftly Resolving 'File Corrupted' Error X70 on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-complete-walkthrough-for-finding-windows-keys-losses/"><u>The Complete Walkthrough for Finding Windows Keys Losses</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-smart-shoppers-guide-to-affordable-cloud-space/"><u>The Smart Shopper's Guide to Affordable Cloud Space</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719261998240-unfreeze-windows-update-easy-to-follow-tips/"><u>Unfreeze Windows Update: Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win-users-guide-to-managing-monitor-luminosity/"><u>Win Users Guide to Managing Monitor Luminosity</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-mastery-building-hotkeys-for-repetitive-text-snapping-tasks/"><u>Windows 11 Mastery: Building Hotkeys for Repetitive Text Snapping Tasks</u></a></li>
</ul></div>
