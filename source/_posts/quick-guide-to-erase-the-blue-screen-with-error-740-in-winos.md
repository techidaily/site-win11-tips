---
title: Quick Guide to Erase the Blue Screen with Error 740 in WINOS
date: 2024-10-07T00:10:56.560Z
updated: 2024-10-08T21:42:26.091Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Erase the Blue Screen with Error 740 in WINOS
excerpt: This Article Describes Quick Guide to Erase the Blue Screen with Error 740 in WINOS
keywords: Windows BlueScreen Fix,Error 740 Solution,WinOS Screensaver,BSOD Resolution Guide,OS Error Repair,WINOS Error Remediation,ScreenError Troubleshoot
thumbnail: https://thmb.techidaily.com/1296bc6cf3d8ba602cee83fbaf9d9aae0f41d750526e3d62954932be609de318.jpg
---

## Quick Guide to Erase the Blue Screen with Error 740 in WINOS

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.

6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151889/7443" target="_top" id="2151889">
  <img src="//a.impactradius-go.com/display-ad/7443-2151889" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043661/7443" target="_top" id="2043661">
  <img src="//a.impactradius-go.com/display-ad/7443-2043661" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043661/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-behind-the-scenes-samsungs-s8-and-4k-technology/"><u>[New] 2024 Approved Behind the Scenes Samsung's S8 and 4K Technology</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-comprehensive-approach-to-integrating-whiteboards-in-zoom-sessions/"><u>[New] Comprehensive Approach to Integrating Whiteboards in Zoom Sessions</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-windows-11-gamers-ultimate-playbook-top-5-record-techniques/"><u>[Updated] 2024 Approved Windows 11 Gamers' Ultimate Playbook Top 5 Record Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortlessly-watch-mkv-files-top-3-fixes-for-troublesome-player-errors/"><u>Effortlessly Watch MKV Files: Top 3 Fixes for Troublesome Player Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-managed-users-and-groups-in-win1110-homes/"><u>Enabling Managed Users and Groups in Win11/10 Homes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/from-novice-to-pro-20-adobe-premiere-shortcuts-to-elevate-your-skills/"><u>From Novice to Pro 20 Adobe Premiere Shortcuts to Elevate Your Skills</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-bypass-win11s-alarming-zero-error-alerts/"><u>How to Bypass Win11’s Alarming Zero Error Alerts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-the-workings-of-windows-odbc-tools/"><u>Insight Into the Workings of Windows ODBC Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/live-stream-recorder-companies-for-2024/"><u>Live Stream Recorder Companies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-utorrent-install-issues-on-a-windows-laptop/"><u>Navigating uTorrent Install Issues on a Windows Laptop</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/overcoming-alexa-hiccups-expert-advice-for-reactive-solutions/"><u>Overcoming Alexa Hiccups: Expert Advice for Reactive Solutions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/pioneering-change-a-step-by-step-guide-to-reinventing-your-tiktok-identity-for-2024/"><u>Pioneering Change A Step-by-Step Guide to Reinventing Your TikTok Identity for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/solve-apple-watch-connection-problems-a-guide-to-6-effective-solutions/"><u>Solve Apple Watch Connection Problems: A Guide to 6 Effective Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-your-computers-print-command-conundrum-with-effective-tips/"><u>Solving Your Computer's Print Command Conundrum with Effective Tips.</u></a></li>
</ul></div>

