---
title: Discreet Deletion of Email After Signing In Windows
date: 2024-06-25T16:23:48.468Z
updated: 2024-06-26T16:23:48.468Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Discreet Deletion of Email After Signing In Windows
excerpt: This Article Describes Discreet Deletion of Email After Signing In Windows
keywords: Secure Delete,WinSign-In Mail Removal,Windows Email Purge,Signed In Deletion Service,Stealthy Email Discard,Privacy-Focused Email Cleanup,Silent Email Erase After Login
thumbnail: https://thmb.techidaily.com/b1e13c65cf79c8bfe0a90a1ea55d4cf4b25b6f465fd497be9c6686a8f2877ff5.jpg
---

## Discreet Deletion of Email After Signing In Windows

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://win11-tips.techidaily.com/efficiently-launching-apps-on-windows-11/"><u>Efficiently Launching Apps on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailor-your-pcs-display-lock-settings/"><u>Tailor Your PC's Display Lock Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforcing-the-resilience-of-windows-11-taskbar/"><u>Reinforcing the Resilience of Windows 11 Taskbar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-up-output-the-power-of-flow-launcher-unveiled/"><u>Scaling Up Output: The Power of Flow Launcher Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-overcoming-windows-run-time-errors/"><u>Unraveling the Mystery: Overcoming Windows 'Run-Time Errors'</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reimagining-taskbar-dynamics-top-6-suggestions-for-windows-11-enhancement/"><u>Reimagining Taskbar Dynamics: Top 6 Suggestions for Windows 11 Enhancement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-solution-for-your-windows-photo-app/"><u>A Step-by-Step Solution for Your Windows Photo App</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-change-lockout-duration-after-failed-logon-attempts-in-windows-11-and-11/"><u>How to Change Lockout Duration After Failed Logon Attempts in Windows 11 and 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-browse-images-using-windows-11-explorer/"><u>Efficiently Browse Images Using Windows 11 Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-linkage-airpods-and-windows-harmony/"><u>Master the Linkage: AirPods & Windows Harmony</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-tecno-camon-20-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Tecno Camon 20 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-critical-analysis-the-best-skype-recorders-of-2023-for-2024/"><u>[Updated] Critical Analysis  The Best Skype Recorders of 2023 for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Tecno Phantom V Flip? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-savor-your-day-8-essential-tools-for-instagram-video-management/"><u>2024 Approved  Savor Your Day  8 Essential Tools for Instagram Video Management</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-metaverse-jokes-and-giggles-how-to-craft-your-own-laughter-inducing-memes/"><u>[Updated] Metaverse Jokes & Giggles  How to Craft Your Own Laughter-Inducing Memes</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-photographic-perfection-in-the-palm-of-your-hands-online/"><u>[New] Photographic Perfection in the Palm of Your Hands Online</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-vivo-y28-5g-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-step-by-step-guide-to-crafting-impressive-instagram-loops/"><u>[Updated] In 2024, Step-by-Step Guide to Crafting Impressive Instagram Loops</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-optimizing-video-sequences-blend-modes-application/"><u>2024 Approved  Optimizing Video Sequences  Blend Modes Application</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-ultimate-checklist-how-to-choose-a-video-to-audio-converter-that-works/"><u>The Ultimate Checklist How to Choose a Video to Audio Converter That Works</u></a></li>
</ul></div>
