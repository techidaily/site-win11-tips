---
title: "Regaining Control: Reclaiming Microsoft Store on Windows 11"
date: 2024-08-23T07:02:56.828Z
updated: 2024-08-24T07:02:56.828Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regaining Control: Reclaiming Microsoft Store on Windows 11"
excerpt: "This Article Describes Regaining Control: Reclaiming Microsoft Store on Windows 11"
keywords: WinStore Regain Control,Microsoft Store Redemption,W11 Microsoft Reentry,Reviving Windows Shop,Retrieve MS Windows Store,Take Back Windows XPS,Control MS Store on W11
thumbnail: https://thmb.techidaily.com/0a1a7225cf59c67660e5517795e22301d6d92dc2445c6377515e5503eb99dcd0.jpg
---

## Regaining Control: Reclaiming Microsoft Store on Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-video-capturing-warriors-choosing-between-obs-and-fraps/"><u>[New] 2024 Approved  Video Capturing Warriors  Choosing Between OBS and Fraps</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-5-reddit-marketing-tips-that-will-turn-beginners-into-experts/"><u>[New] 5 Reddit Marketing Tips that Will Turn Beginners Into Experts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-galaxy-s8s-ultra-hd-experience-unveiled/"><u>[New] Galaxy S8's Ultra HD Experience Unveiled</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-interlinked-networks-transferring-fb-videos-to-whatsapp/"><u>[New] Interlinked Networks  Transferring FB Videos to WhatsApp</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-propel-your-workflow-final-cut-pros-must-have-tools/"><u>[New] Propel Your Workflow  Final Cut Pro’s Must-Have Tools</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-craft-memes-with-kapwings-design-toolkit/"><u>[Updated] 2024 Approved  Craft Memes with Kapwing's Design Toolkit</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-building-visual-story-arcs/"><u>[Updated] Building Visual Story Arcs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pro-tips-for-power-users-expert-whatsapp-techniques-for-2024/"><u>[Updated] Pro Tips for Power Users  Expert WhatsApp Techniques for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-financial-key-to-boosting-your-videos-reach/"><u>[Updated] The Financial Key to Boosting Your Video's Reach</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-unlock-creative-potential-with-premium-effects-extensions-for-2024/"><u>[Updated] Unlock Creative Potential with Premium Effects Extensions for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-elevate-the-listening-experience-with-garageband-edits/"><u>2024 Approved  Elevate the Listening Experience with GarageBand Edits</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gaming-hub-clashes-with-content-creation-empire-a-detailed-twitchyoutube-comparison/"><u>2024 Approved  Gaming Hub Clashes with Content Creation Empire  A Detailed Twitch/YouTube Comparison</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-unlock-apple-iphone-13-mini-without-passcode-or-face-id-by-drfone-ios/"><u>3 Ways to Unlock Apple iPhone 13 mini without Passcode or Face ID</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-windows-n-releases-tech-enthusiasts-guide/"><u>Comparing Windows N Releases: Tech Enthusiast's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-individualized-win11-screensavers/"><u>Designing Individualized Win11 Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-on-win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-on-fixing-the-failed-to-initiate-lunar-client-issue/"><u>Focusing on Fixing the Failed to Initiate Lunar Client Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-troubleshooting-display-with-windows-drivers/"><u>Guide to Troubleshooting Display with Windows Drivers</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-and-fixing-windows-headset-mic-glitches/"><u>Identifying & Fixing Windows Headset Mic Glitches</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-critical-evaluation-of-ustream-with-equivalents/"><u>In 2024, A Critical Evaluation of Ustream with Equivalents</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-nokia-130-music-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Nokia 130 Music Phone? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-vivo-x90s-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Vivo X90S Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-sketch-spectacular-top-10-bare-essentials-for-mac-illustrators/"><u>In 2024, Sketch Spectacular  Top 10 Bare Essentials for Mac Illustrators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-tactics-to-outwit-windows-sign-in-prompts/"><u>Ingenious Tactics to Outwit Windows Sign-In Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/intense-moment-capture-iphone-burst-mode/"><u>Intense Moment Capture  IPhone Burst Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-pc-troubles-try-our-top-10-tools/"><u>Navigating PC Troubles? Try Our Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/podcast-perfection-on-pc-win-five-no-cost-filters/"><u>Podcast Perfection on PC: Win Five No-Cost Filters</u></a></li>
<li><a href="https://media-tips.techidaily.com/quick-and-easy-guide-to-making-amazing-gifs-for-free-top-20-platforms-explored/"><u>Quick and Easy Guide to Making Amazing GIFs for Free – Top 20 Platforms Explored</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieten-the-high-contrast-in-windows-ui/"><u>Quieten the High Contrast in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-the-looks-like-youre-stranded-from-xbox-app-windows/"><u>Removing the 'Looks Like You're Stranded' From Xbox App Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/six-straightforward-mojang-homes-for-creative-builders-for-2024/"><u>Six Straightforward Mojang Homes for Creative Builders for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-offon-windows-11s-online-scan-feature/"><u>Switching Off/On Windows 11'S Online Scan Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-quick-and-easy-route-to-your-pcs-credential-vault-on-win11/"><u>The Quick and Easy Route to Your PC's Credential Vault on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-for-smooth-captions-essential-tips-on-windows-10/"><u>Troubleshoot for Smooth Captions: Essential Tips on Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-path-related-issues-in-windows-os/"><u>Troubleshooting Path-Related Issues in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-security-settings-for-general-pc-users-in-windows/"><u>Tweaking Security Settings for General PC Users in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undo-customization-reverting-win11-user-permissions/"><u>Undo Customization: Reverting Win11 User Permissions</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-se-2022-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock iPhone SE (2022) With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlocking-the-past-best-educational-historical-content-on-yt-for-2024/"><u>Unlocking the Past  Best Educational Historical Content on YT for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-elevate-your-brand-with-these-11-free-animated-logo-generators/"><u>Updated Elevate Your Brand with These 11 Free Animated Logo Generators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-pagefilesys-in-windows-should-you-delete-it/"><u>What Is Pagefile.sys in Windows? Should You Delete It?</u></a></li>
</ul></div>
