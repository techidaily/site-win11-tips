---
title: "Mastering Privacy: Remove Login Email in Windows"
date: 2024-08-08T11:09:04.484Z
updated: 2024-08-09T11:09:04.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Privacy: Remove Login Email in Windows"
excerpt: "This Article Describes Mastering Privacy: Remove Login Email in Windows"
keywords: Removing Windows Login,Email Omission WinXP,Enhancing PC Privacy,Secure Computing XP,Opt Out Window Mail,Privacy Settings Windows,Stealthy User Access
thumbnail: https://thmb.techidaily.com/3de06be99a3225bd572539cfd46d39535123115f6244e3ee7a3676c38fda1900.jpg
---

## Mastering Privacy: Remove Login Email in Windows

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/024-approved-speed-tutorial-changing-photos-into-engaging-youtube-thumbnails/"><u>[New] 2024 Approved  Speed Tutorial  Changing Photos Into Engaging YouTube Thumbnails</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-dissecting-the-income-from-a-million-on-youtube-for-2024/"><u>[New] Dissecting the Income From a Million on YouTube for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-bite-sized-video-specialist/"><u>[New] In 2024, Bite-Sized Video Specialist</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-the-ultimate-playbook-for-exceptional-obs-studio-content-for-2024/"><u>[New] The Ultimate Playbook for Exceptional OBS Studio Content for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-master-live-broadcast-setup-using-obs-studio-pc-mac-laptop/"><u>[Updated] 2024 Approved  Master Live Broadcast Setup Using OBS Studio (PC, Mac, Laptop)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-from-pcmac-to-the-feed-how-to-efficiently-upload-videos-to-instagram/"><u>[Updated] In 2024, From PC/Mac to the Feed  How to Efficiently Upload Videos to Instagram</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-step-by-step-guide-to-editing-and-optimizing-instagram-footage-for-2024/"><u>[Updated] Step-by-Step Guide to Editing and Optimizing Instagram Footage for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-enhancing-instagram-video-performance-desktop/"><u>2024 Approved  Enhancing Instagram Video Performance (Desktop)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-infinix-zero-5g-2023-turbo-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Infinix Zero 5G 2023 Turbo Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/6-reasons-why-windows-11-is-better-than-macos/"><u>6 Reasons Why Windows 11 Is Better Than macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-premium-zero-cost-windows-media-tools/"><u>7 Premium Zero-Cost Windows Media Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-locate-elusive-gpeditmsc-on-pc/"><u>7 Ways to Locate Elusive 'Gpedit.msc' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-remedies-to-clear-windows-setup-stuck-on-validation-error/"><u>9 Remedies to Clear Windows Setup Stuck on Validation Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/9-simple-steps-to-fix-server-not-found-error-on-windows-pcs-in-apex-legends-(156-chars/"><u>9 Simple Steps to Fix 'Server Not Found' Error on Windows PCs in Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-breakdown-of-mouse-customization-features-on-win11/"><u>A Complete Breakdown of Mouse Customization Features on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-guide-to-microsoft-project-keyboard-shortcuts/"><u>A Complete Guide to Microsoft Project Keyboard Shortcuts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-complete-step-by-step-plan-msoffice-install-on-win11/"><u>A Complete Step-by-Step Plan: MSOffice Install on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-comprehensible-guide-for-windows-11-spotless-restarts/"><u>A Comprehensible Guide for Windows 11 Spotless Restarts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-quick-walkthrough-to-unveil-ms-paint-windows-11/"><u>A Quick Walkthrough to Unveil MS Paint, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-step-by-step-manual-for-ws11s-software-reset/"><u>A Step-By-Step Manual for WS11's Software Reset</u></a></li>
<li><a href="https://win11-tips.techidaily.com/accessing-a-quake-environment-via-terminals/"><u>Accessing a Quake Environment via Terminals</u></a></li>
<li><a href="https://win11-tips.techidaily.com/actions-to-undo-error-x80780119-on-windows-images/"><u>Actions to Undo Error X80780119 on Windows Images</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-nvidia-panel-errors-win1110-fixes/"><u>Addressing Nvidia Panel Errors: Win11/10 Fixes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-screen-separation-issues/"><u>Addressing Windows Screen Separation Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/automate-file-disposal-in-windows-for-efficiency-gains/"><u>Automate File Disposal in Windows for Efficiency Gains</u></a></li>
<li><a href="https://win11-tips.techidaily.com/baffle-the-shutdown-win11s-hidden-button-guide/"><u>Baffle the Shutdown: Win11's Hidden Button Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beginning-on-time-adjusting-startup-services-for-windows-11/"><u>Beginning on Time: Adjusting Startup Services for Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bestowing-wondrous-widgets-onto-context-menu/"><u>Bestowing Wondrous Widgets Onto Context Menu</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boost-efficiency-with-automatic-file-disposal-in-windows-11/"><u>Boost Efficiency with Automatic File Disposal in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-boot-on-windows-sound-service-efficiency/"><u>Boosting Boot-On Windows Sound Service Efficiency</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boosting-mobile-connectivity-in-windows-11/"><u>Boosting Mobile Connectivity in Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-tactics-capturing-high-quality-sports-streams-online-for-2024/"><u>Essential Tactics  Capturing High-Quality Sports Streams Online for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/highly-recommended-auto-cameras-for-vehicle-tracking-for-2024/"><u>Highly Recommended Auto Cameras for Vehicle Tracking for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-13-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 13 without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-oppo-f23-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Oppo F23 5G</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/is-it-allowable-to-distribute-videos-via-social-networks/"><u>Is It Allowable to Distribute Videos via Social Networks?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-honor-70-lite-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Honor 70 Lite 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-aviation-gadgets-purchase-now-for-2024/"><u>Prime Aviation Gadgets, Purchase Now for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719284654722-software-environment-setup/"><u>Software Environment Setup:</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719356387702-stuck-google-chrome-on-win11-try-these-immediate-actions/"><u>Stuck Google Chrome on Win11? Try These Immediate Actions</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-strategy-guide-to-digital-video-enhancement-for-2024/"><u>The Ultimate Strategy Guide to Digital Video Enhancement for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-idt-audio-drivers-for-windows-7/"><u>Update IDT Audio Drivers for Windows 7</u></a></li>
</ul></div>
