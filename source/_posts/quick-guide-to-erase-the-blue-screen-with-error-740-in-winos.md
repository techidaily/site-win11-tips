---
title: Quick Guide to Erase the Blue Screen with Error 740 in WINOS
date: 2024-09-26T17:37:33.398Z
updated: 2024-10-03T18:41:53.755Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-8-best-photo-grid-online-makers-to-polish-your-pictures/"><u>[New] 8 Best Photo Grid Online Makers to Polish Your Pictures</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-top-gains-on-social-media-secure-and-scalable-tactics/"><u>[New] The Top Gains on Social Media - Secure & Scalable Tactics</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-top-picks-of-engaging-click-based-pc-gaming/"><u>[New] Top Picks of Engaging Click-Based PC Gaming</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-blogging-basics-for-business-beginnings/"><u>[Updated] In 2024, Blogging Basics for Business Beginnings</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-unlocking-the-secrets-of-advanced-virtualization-for-2024/"><u>[Updated] Unlocking the Secrets of Advanced Virtualization for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-strategies-to-dodge-content-advisory-strikes/"><u>2024 Approved Strategies to Dodge Content Advisory Strikes</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725288792712-10/"><u>子供が愛する映画ベストセレクション：新型コロナ時代に楽しむべき10本！視聴はこちらのリンクから始めよう</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-fix-windows-sandboxs-no-hypervisor-error/"><u>Guide to Fix Windows Sandbox's No Hypervisor Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-get-rid-of-silence-in-google-meet-chat/"><u>How to Get Rid of Silence in Google Meet Chat</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-boosting-productivity-how-to-proficiently-use-a-virtual-whiteboard-in-zoom/"><u>In 2024, Boosting Productivity How to Proficiently Use a Virtual Whiteboard in Zoom</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-lava-yuva-2-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Lava Yuva 2 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-a-failed-windows-discord-update-seamlessly/"><u>Navigating a Failed Windows Discord Update Seamlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-exit-code-1-on-pc-with-minecraft/"><u>Overcoming Exit Code 1 on PC with Minecraft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-windows-error-incorrect-file-history-configurations/"><u>Resolving Windows Error: Incorrect File History Configurations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-connectivity-how-to-fix-network-errors-in-windows-11/"><u>Seamless Connectivity: How to Fix Network Errors in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secure-visual-studio-code-against-windows-11-glitches/"><u>Secure Visual Studio Code Against Windows 11 Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocketing-vm-efficiency-on-windows-with-six-tips/"><u>Skyrocketing VM Efficiency on Windows with Six Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-resolving-the-0x0000011b-error-in-win11/"><u>Troubleshooting: Resolving the 0X0000011B Error in Win11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-transform-your-videos-into-audio-top-ios-and-android-apps-for-2024/"><u>Updated Transform Your Videos Into Audio Top iOS and Android Apps for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    