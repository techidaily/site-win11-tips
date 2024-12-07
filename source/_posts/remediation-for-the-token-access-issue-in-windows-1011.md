---
title: Remediation for the Token Access Issue in Windows 10/11
date: 2024-12-06T02:07:40.187Z
updated: 2024-12-06T18:46:44.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remediation for the Token Access Issue in Windows 10/11
excerpt: This Article Describes Remediation for the Token Access Issue in Windows 10/11
keywords: Windows Token Fix,Windows Token Solve,Token Access Remedy,10/11 Token Issues,Win10 Token Repair,Win11 Token Fixes,Secure Token Access
thumbnail: https://thmb.techidaily.com/b84b835099bbd2f060100cf1ff53df1a6537fd5a4b5a03be31336b43fbf43c35.jpg
---

## Remediation for the Token Access Issue in Windows 10/11

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/ed-optimal-video-posting-frequency-for-increased-youtube-popularity-for-2024/"><u>[Updated] Optimal Video Posting Frequency for Increased YouTube Popularity for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/analyzing-what-sets-ai-hardware-on-a-distinct-path/"><u>Analyzing What Sets AI Hardware on a Distinct Path</u></a></li>
<li><a href="https://win11-tips.techidaily.com/designing-personalized-secure-locks-for-windows-11/"><u>Designing Personalized Secure Locks for Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722981802051-god-of-war-fps-the-ultimate-action-experience-now-drops-for-your-pc/"><u>God of War FPS: The Ultimate Action Experience Now Drops for Your PC!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-xbox-game-pass-0x00000001-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X00000001 Error in Windows 10 & 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-apple-iphone-se-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From Apple iPhone SE in the Best Ways</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-oppo-find-x7-phone-by-drfone-android/"><u>How to Reset a Locked Oppo Find X7 Phone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-save-the-day-linkinscapes-6-best-apps-for-video-downloading/"><u>In 2024, Save the Day Linkinscape's 6 Best Apps for Video Downloading</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-crypto-insights-using-chatgpt-the-10-prompt-secrets-revealed/"><u>Mastering Crypto Insights Using ChatGPT: The 10 Prompt Secrets Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-winerror-0xc0000005/"><u>Mastering the Art of Fixing WinError 0Xc0000005</u></a></li>
<li><a href="https://tech-revival.techidaily.com/movavijpegweb/"><u>Movaviで簡単JPEGに変更する:無料WEBツール</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-facebook-glitches-and-hurdles-with-ease/"><u>Navigating FaceBook Glitches & Hurdles with Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-launchers-security-failures-on-windows-systems/"><u>Navigating Launcher's Security Failures on Windows Systems</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015617248-quick-and-easy-mic-check-techniques-expert-tips-on-testing-your-microphone/"><u>Quick and Easy Mic Check Techniques - Expert Tips on Testing Your Microphone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-windows-error-1053-unresponsive-service-issue/"><u>Tackling Windows Error 1053: Unresponsive Service Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ultimate-list-of-windows-note-taking-aids/"><u>Ultimate List of Windows Note-Taking Aids</u></a></li>
<li><a href="https://win-webster.techidaily.com/what-is-currently-the-favorite-web-browser-insights-from-zdnet-analytics/"><u>What Is Currently the Favorite Web Browser? - Insights From ZDNet Analytics</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-is-yourphoneexe-phone-link-in-windows-1110-should-you-disable-it/"><u>What Is YourPhone.exe (Phone Link) in Windows 11/10? Should You Disable It?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-editorial-techniques-select-from-the-top-8-video-trimming-titles/"><u>Winning Editorial Techniques: Select From The Top 8 Video Trimming Titles</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    