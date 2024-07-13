---
title: Fine-Tuning Non-Admin Account Permissions in Windows
date: 2024-07-12T16:53:13.694Z
updated: 2024-07-13T16:53:13.694Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning Non-Admin Account Permissions in Windows
excerpt: This Article Describes Fine-Tuning Non-Admin Account Permissions in Windows
keywords: Admin Privilege Control,User Access Management,Limited Permission Settings,Security Role Limitation,Windows Non-Admin Rights,Account Access Restriction,Secure User Permissions
thumbnail: https://thmb.techidaily.com/641461279d3ad9059bf4fdcda2c6b1609c3c8007cc281a812d3b0157adab9f77.jpg
---

## Fine-Tuning Non-Admin Account Permissions in Windows

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/a-clearer-journey-the-art-of-annotating-folders-on-windows-11/"><u>A Clearer Journey: The Art of Annotating Folders on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-noisy-keys-regaining-control-over-sound-on-your-pc/"><u>Tame Noisy Keys: Regaining Control Over Sound on Your PC</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-a-statement-10-best-animated-text-generators-for-eye-catching-content/"><u>New Make a Statement 10 Best Animated Text Generators for Eye-Catching Content</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-methods-for-repairing-nonfunctional-itunes-on-windows/"><u>Efficient Methods for Repairing Nonfunctional iTunes on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-samsung-galaxy-f34-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Samsung Galaxy F34 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workspace-win-11s-finest-productivity-tools/"><u>Transform Your Workspace: Win 11'S Finest Productivity Tools</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capturing-contentment-top-streaming-techniques-for-2024/"><u>Capturing Contentment  Top Streaming Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unraveling-the-purpose-behind-a-common-symbol-on-fb-chat/"><u>Unraveling the Purpose Behind a Common Symbol on FB Chat</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-for-quake-via-windows-terminal/"><u>Command Line for Quake via Windows Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/approaches-to-addressing-critical-app-issues/"><u>Approaches to Addressing Critical App Issues</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/best-console-to-pc-conversion-top-5-ps1-emulators-for-2024/"><u>Best Console-to-PC Conversion  Top 5 PS1 Emulators for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-how-to-quickly-craft-perfect-subtitles-and-captions-for-facebook-video-feeds/"><u>2024 Approved  How To Quickly Craft Perfect Subtitles and Captions for Facebook Video Feeds</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-defenders-0x80004004-issue/"><u>Breaking Down Windows Defender's 0X80004004 Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-code-0x887a0006-for-graphics/"><u>Correcting Error Code 0X887A0006 for Graphics</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-x-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>Complete Fixes To Solve Apple iPhone X Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-win-11-gameplay-unveiling-the-ultimate-seven-steps/"><u>Boosting Win 11 Gameplay: Unveiling the Ultimate Seven Steps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-strikingly-successful-nicknames-a-must-have-list-for-disco-channels/"><u>In 2024, Strikingly Successful Nicknames  A Must-Have List for Disco Channels</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-with-windows-11-safe-boot-tips/"><u>Troubleshoot With Windows 11 Safe Boot Tips</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-asus-rog-phone-7-ultimate-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Asus ROG Phone 7 Ultimate to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-index-performance-on-your-pc/"><u>Enhancing Index Performance on Your PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-motorola-g24-power-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Motorola G24 Power Phone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-0x800704cf-from-windows-marketplace/"><u>Eliminating 0X800704CF From Windows Marketplace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/workaround-cease-discord-startup-and-update-checks-in-windows/"><u>Workaround: Cease Discord Startup and Update Checks in Windows</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-global-reach-12-video-live-stream-app/"><u>2024 Approved  Global Reach  12 Video Live Stream App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweak-windows-11-shutdown-procedure-for-active-operations/"><u>Tweak Windows 11 Shutdown Procedure for Active Operations</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-final-cut-pro-for-beginners-rotating-and-flipping-clips-like-a-pro/"><u>In 2024, Final Cut Pro for Beginners Rotating and Flipping Clips Like a Pro</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-steam-network-via-dns-cleanup/"><u>Streamlining Your Steam Network via DNS Cleanup</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-instagrams-music-ip-policies/"><u>[New] 2024 Approved  Instagram's Music IP Policies</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-innovative-ideas-for-fb-slideshow-creations/"><u>[New] In 2024, Innovative Ideas for FB Slideshow Creations</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-begin-webcam-footage-recording-with-vlc/"><u>[Updated] 2024 Approved  Begin Webcam Footage Recording with VLC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/finding-solutions-to-unacceptable-connections-in-windows-os/"><u>Finding Solutions to Unacceptable Connections in Windows OS</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-tecno-pop-7-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Tecno Pop 7 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prime-gpus-for-sharp-4k-image-display/"><u>Prime GPUs for Sharp 4K Image Display</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-unveiling-the-secret-for-instantaneous-deletion-of-youtube-feedbacks/"><u>[Updated] 2024 Approved  Unveiling the Secret for Instantaneous Deletion of Youtube Feedbacks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-guide-from-raw-images-to-high-quality-youtube-thumbnail-art/"><u>Hasty Guide  From Raw Images to High-Quality YouTube Thumbnail Art</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-and-artificial-intelligence-generating-vibrant-ai-graphics-paint-cocreator/"><u>Windows 11 & Artificial Intelligence: Generating Vibrant AI Graphics (Paint Cocreator)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-windows-experience-with-vivetool-innovations/"><u>Elevate Your Windows Experience with ViVeTool Innovations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-11-bluescreen-mastery-through-11-fixes/"><u>Unraveling Windows 11 Bluescreen: Mastery Through 11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-deactivated-rulesets-in-outlookwindows/"><u>Troubleshooting Deactivated Rulesets in Outlook/Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-the-potential-of-folder-multiplication-on-windows-devices/"><u>Unlocking the Potential of Folder Multiplication on Windows Devices</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-inspiration-in-frames-top-20-creative-instagrams/"><u>[New] Inspiration in Frames  Top 20 Creative Instagrams</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-screenscape-high-quality-4k-panels-for-editors/"><u>Elite Screenscape  High-Quality 4K Panels for Editors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-solution-for-fixing-error-code-0x80073d26/"><u>The Ultimate Solution for Fixing Error Code: 0X80073D26</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-beginners-roadmap-to-google-maps-on-pc/"><u>The Beginner's Roadmap to Google Maps on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configure-touch-input-in-windows-enabledisable-steps/"><u>Configure Touch Input in Windows: Enable/Disable Steps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-insights-into-utilizing-dism-for-win11-fixes/"><u>Expert Insights Into Utilizing Dism for Win11 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windows-infamous-blue-screen-issues/"><u>Demystifying Windows' Infamous Blue Screen Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fasten-up-your-pc-launches-mastering-windows-11-quick-start-mode/"><u>Fasten Up Your PC Launches: Mastering Windows 11 Quick Start Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-strikes-winning-warfare-without-lag-in-star-wars-bf2/"><u>Swift Strikes: Winning Warfare Without Lag in Star Wars BF2</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-notes-navigated-steps-for-sound-submissions-to-youtube-for-2024/"><u>[Updated] Notes Navigated  Steps for Sound Submissions to YouTube for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-12plus-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Realme 12+ 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-6-chrome-browser-sound-capture-apps/"><u>Updated Top 6 Chrome Browser Sound Capture Apps</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-quality-sd-card-for-sony-alpha-7s-ii/"><u>2024 Approved  Top-Quality SD Card for Sony Alpha 7S II</u></a></li>
</ul></div>
