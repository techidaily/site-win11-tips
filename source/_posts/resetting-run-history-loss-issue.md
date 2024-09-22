---
title: Resetting Run History Loss Issue
date: 2024-09-21T06:57:49.157Z
updated: 2024-09-21T17:33:02.585Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Run History Loss Issue
excerpt: This Article Describes Resetting Run History Loss Issue
keywords: Fix Run History Loss,Reset Tracking Errors,Clear Run Data Issues,Run History Recovery,Address Running Gaps,Restore Run Logs,Solve Run History Problems
thumbnail: https://thmb.techidaily.com/f8f467b332b89dbb4d8c51eef116fbbce4476e735f93f6027b47c78945bb4e75.jpg
---

## Resetting Run History Loss Issue

 The Run command dialog box in Windows makes it easy to launch apps, access system tools, and perform various other tasks. It also has an auto-complete feature that makes it easy to re-use your commands later. However, the auto-complete feature in the Run tool may not work if it fails to save your command history in the first place.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check Your Privacy Settings

 A common reason why Windows may not save the Run command history is if you have previously blocked it from tracking your app launches. Here’s how you can change that.

1. Press **Win + I** to open the Settings app.
2. Select **Privacy & security** from the left sidebar.
3. Under Windows permissions, click on **General**.
4. Enable the toggle next to **Let Windows improve Start and search results by tracking app launches**.  
![Allow Windows to Track App Launches on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-windows-to-track-app-launches-on-windows.jpg)

 After completing the above steps, try running a few commands via the Run dialog box. Then, check if it is saving your command history and providing auto-complete suggestions.

## 2\. Edit Registry Files

 Is the **Let Windows improve Start and search results by tracking app launches** option grayed out on your PC? If so, you can take help from the Registry Editor to get Windows to save your Run command history.

 As you may already be aware, registry files on your PC store essential settings for Windows and its services. Making incorrect modifications to these files can render your system inoperable. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Click the search icon on the taskbar or press the **Win + S** keyboard shortcut to open the search menu.
2. Type **registry editor** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced**.
5. Locate the **Start\_TrackProgs** entry in the right pane. If you can’t find it, right-click on the **Advanced** key and select **New > DWORD (32-bit) Value**. Rename it to **Start\_TrackProgs**.
6. Double-click the newly created DWORD and enter **1** in the **Value data** field.
7. Click **OK**.  
![Edit Registry DWORD on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-registry-dword-on-windows.jpg)

 Restart your PC after this for the changes to take effect. Following this, the Run command should start saving your history on Windows.

## 3\. Apply Generic Fixes

 If the problem persists even after implementing the above tips, you can try applying some basic fixes to resolve the underlying issue.

* **Restart Your PC:** This may appear rudimentary, but temporary OS-related glitches can sometimes cause such anomalies. If it’s nothing major, [restarting your PC](https://www.makeuseof.com/windows-restart-methods/) should fix any issues with the Run command.
* **Run an SFC Scan:** Such issues can also arise if some of the critical system files on your PC are corrupt. [Running a System File Checker (SFC) scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) can help detect and repair any damaged system files on your PC.
* **Scan for Malware:** It’s possible that your system is infected by malware, which is why the Run command is having trouble saving your history. To rule out this possibility, you can [scan Windows for malware using PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/) or Windows Defender.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the Run Tool to Save Your History on Windows

 It can be inconvenient if the Run command dialog box stops saving your history on Windows. Hopefully, one of the solutions provided above has successfully resolved the issue for you.

 If you feel that the Run utility in Windows lacks advanced features, you can always switch to alternative tools like Run-Command or PowerToys Run.

 If you're encountering a similar problem, don’t fret. Below, we share some quick and useful tips that should get the Run tool to save your history once again.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-premium-choice-top-12-apps-with-no-time-limit-feature/"><u>[Updated] 2024 Approved Premium Choice Top 12 Apps with No Time Limit Feature</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-enhancing-your-digital-presence-fb-video-creation-basics/"><u>[Updated] Enhancing Your Digital Presence FB Video Creation Basics</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-prolong-your-snapstreak-legacy-with-ease-for-2024/"><u>[Updated] Prolong Your Snapstreak Legacy with Ease for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-secure-your-fb-story-views-with-these-5-techniques/"><u>2024 Approved Secure Your FB Story Views with These 5 Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-compatibility-essential-wsl-2-advice-for-pcs/"><u>Conquer Compatibility: Essential WSL 2 Advice for PCs</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-lenovo-ideapad-320-a-masterpiece-in-sleek-beauty-and-versatile-usage-complemented-by-lenovos-signature-keyboard/"><u>Discover the Lenovo IdeaPad 320 - A Masterpiece in Sleek Beauty and Versatile Usage Complemented by Lenovo's Signature Keyboard</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-v30-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Vivo V30 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reinstate-accurate-battery-life-meter-on-pcs-running-win-11/"><u>How to Reinstate Accurate Battery Life Meter on PCs Running Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-photography-in-windows-11-building-impressive-slide-shows-and-fixes/"><u>Mastering the Art of Photography in Windows 11: Building Impressive Slide Shows & Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-device-management-in-system-sleep/"><u>Proactive Device Management in System Sleep</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restore-vanished-5ghz-connection-link-in-windows-11-swiftly/"><u>Restore Vanished 5GHz Connection Link in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slash-clutter-a-fast-way-to-remove-bloatware-in-win11/"><u>Slash Clutter: A Fast Way to Remove Bloatware in Win11</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-nwstoreexe-malfunction-a-step-by-step-guide/"><u>Solving nw_store.exe Malfunction: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-stop-keyboard-use-for-computer-running-windows/"><u>Steps to Stop Keyboard Use for Computer Running Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/tactics-to-determine-igtv-viewership-success-for-2024/"><u>Tactics to Determine IGTV Viewership Success for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/why-does-my-iphones-screen-keep-getting-darker-understanding-10-triggers/"><u>Why Does My iPhone's Screen Keep Getting Darker? Understanding 10 Triggers</u></a></li>
</ul></div>

