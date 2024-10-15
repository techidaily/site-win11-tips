---
title: "Comprehensive Guide: Resolving the Requires Elevation Error in Windows 11"
date: 2024-10-13T04:34:31.659Z
updated: 2024-10-15T05:04:56.408Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Comprehensive Guide: Resolving the Requires Elevation Error in Windows 11"
excerpt: "This Article Describes Comprehensive Guide: Resolving the Requires Elevation Error in Windows 11"
keywords: Windows 11 Elevation Fixes,Win11 Elevate Error Guide,Solve Win11 Elevate Issue,Correcting Windows 11 Err,Elevate Windows 11 Tutorial,Fix Requires Elevation Error,Overcome Windows 11 Rise Failure
thumbnail: https://thmb.techidaily.com/762eb58aca659c7ab398016eac456ae67d371642f3000355e426b137b3698ca6.jpg
---

## Comprehensive Guide: Resolving the Requires Elevation Error in Windows 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-master-the-art-of-mac-screen-record-via-shortcuts/"><u>[New] Master the Art of Mac Screen Record via Shortcuts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-spectacular-showdowns-and-excursions-top-10-gaming-treasures-for-2024/"><u>[New] Spectacular Showdowns & Excursions – Top 10 Gaming Treasures for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagrammashup-androidandios-video-tiles/"><u>[Updated] InstagramMashup Android&iOS Video Tiles</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/apple-disburses-refunds-to-eligible-macbook-buyers-under-recent-class-action-agreement-tech-news-from-zdnet/"><u>Apple Disburses Refunds to Eligible MacBook Buyers Under Recent Class Action Agreement - Tech News From ZDNet</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725286017619-dvd-dvd/"><u>DVD再生可能化ガイド - 自宅で安全にDVDリフレッシュ</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-non-functional-copy-paste-in-chromeedgefirefox-windows/"><u>Fixing Non-Functional Copy-Paste in Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Vivo S18? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-snapping-in-depth-guide-to-powertoy-window-layouts/"><u>Master the Art of Snapping: In-Depth Guide to PowerToy Window Layouts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-proxy-configurations-on-windows-11/"><u>Mastering the Art of Proxy Configurations on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/maximizing-the-new-windows-taskbar-design/"><u>Maximizing the New Windows Taskbar Design</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revitalize-your-old-school-gaming-adventures-integrate-trophies-through-retroarch/"><u>Revitalize Your Old-School Gaming Adventures - Integrate Trophies Through Retroarch</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/revolutionizing-marketing-with-interactive-tiktok-content-for-2024/"><u>Revolutionizing Marketing with Interactive TikTok Content for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/seamless-system-updates-implementing-macos-sierra/"><u>Seamless System Updates Implementing macOS Sierra</u></a></li>
<li><a href="https://win11-tips.techidaily.com/speedy-app-engagement-in-modern-window-os/"><u>Speedy App Engagement in Modern Window OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-eliminate-directdraw-faults-on-windows-oses/"><u>Steps to Eliminate DirectDraw Faults on Windows OSes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-ultimate-guide-to-unlocking-your-iphone-se-2022-on-metropcs-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Your iPhone SE (2022) on MetroPCS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unfettered-functions-embrace-tiny11s-power/"><u>Unfettered Functions: Embrace Tiny11's Power</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    