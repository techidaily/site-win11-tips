---
title: Keeping Insider Beta Features Hidden
date: 2024-09-01T05:19:38.128Z
updated: 2024-09-02T05:19:38.128Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keeping Insider Beta Features Hidden
excerpt: This Article Describes Keeping Insider Beta Features Hidden
keywords: Hidden Features Strategy,Insider Access Secrecy,Exclusive Beta Content,Private Product Testing,Internal Beta Limitations,Non-Public Development,Limited Feature Reveals
thumbnail: https://thmb.techidaily.com/fc56be1104b47b174a9a13d9255575e8e01dfcc34ec60d7f7f9e3cbb3a84553c.jpg
---

## Keeping Insider Beta Features Hidden

 Microsoft rolls out Insider builds to Windows Insiders before releasing them to the public. The preview is only intended for testing and feedback, and it provides access to the latest features & changes that will be included in the next release.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

## How to Stop Users From Getting Insider Preview Builds in Windows 11

 If you share your computer with others and don't want them to get the newer build, you need to prevent them from getting Insider Preview Builds in Windows 11\. There are basically three ways to achieve this, using System Settings, Group Policy Editor, or Registry Editor. For a detailed explanation of each, please see the following.

### 1\. Use the System Settings

 If you don't want someone to access the Insider builds, you can disable it from the Windows System settings. This option is hidden in the Windows Update settings, so you will need to navigate through the menus to find it. Here's how to do it:

1. Press **Win + I** to open System settings. You can also open it from the Start menu.
2. Once you're in System Settings, go to **Windows Update**.
3. Then navigate to **Windows Insider Programme** \> **Stop getting preview builds**.  
![Stop Getting Preview Builds in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/stop-getting-preview-builds-in-windows.jpg)
4. Now toggle the **Unenroll this device when the next version of Windows releases** switch to disable it.

 This will prevent the device from downloading further Insider builds even if someone initiates it manually.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Use the Local Group Policy Editor

 Windows 11's Local Group Policy Editor provides you with a wide range of options for configuring system settings. In fact, you can use this tool to disable access to preview builds. However, you will not have access to the Local Group Policy editor if you use Windows Home Edition.

 For this to work, you must first [activate the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems too complicated, you may skip it and move on to the next solution.

 Here are the steps you need to take to prevent other users from getting Insider Preview Builds

1. Press the **Win + R** keys to open the Run dialog box.
2. Type "gpedit.msc" into the text field, and then click the **OK** button to launch the Local Group Policy Editor.
3. In the Local Group Policy Editor, go to the following locations:  
`Computer Configuration > Administrative Templates > Windows Components > Data Collection and Preview Builds`
4. From the left menu, select the **Data Collection and Preview Builds** folder.
5. Then double-click on the **Toggle user control over Insider builds** on the right.  
![Block Insider Preview Builds Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Group-Policy.jpg)
6. Select the **Disabled** radio button in the dialog box that appears.  
![Toggle user control over Insider builds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Toggle-user-control-over-Insider-builds.jpg)
7. After you've made your changes, click **Apply** and **OK** to save them
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you have completed the steps above, you will need to restart your computer to ensure the changes are applied. After doing that, you'll no longer be able to install or receive Insider builds. If you ever need to give users access to Insider builds on your computer, open the Local Group Policy Editor again.

 Then, set "Toggle user control over Insider builds" either to the **Not Configured** or **Enabled** option. When you have finished making the changes, click Apply > OK.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### 3\. Tweak the Registry Editor

 Tweaking the Registry Editor is another method you can use to prevent users from getting Insider Preview Builds in Windows 11\. The process is easy and only requires a few steps. It is important, however, not to [accidentally mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) while doing so.

 If you edit the wrong keys, you may seriously damage your device. For this reason, you should always [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes to it.

 To prevent other users from getting Insider Preview Builds, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. In the search field, type "regedit" and click **OK**.
3. You will see a UAC window on your screen. Click **Yes** to confirm your action.
4. When you're in the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\PreviewBuilds`
5. If you don't find the PreviewBuilds key there, you will have to create it. In order to do this, right-click on the **Windows** key and select **New** \> **Key**.
6. Specify **PreviewBuilds** as the file name and hit Enter to save it.
7. In the right pane, right-click on an empty area and select **New > DWORD (32-bit) Value**.
8. This DWORD key should have the name **AllowBuildPreview**.
9. Click twice on the newly created DWORD key to open a pop-up menu.  
![Block Insider Preview Builds Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Block-Insider-Preview-Builds-Using-Registry-Editor.jpg)
10. Set the value data to **0** and choose the Hexadecimal base.
11. Click **OK** to save the changes.

 When you're done making these changes, restart your computer. If you ever need to roll back the changes, you can do so whenever you like.

 To do this, right-click the AllowBuildPreview key in the Registry Editor and choose **Modify**. You then need to set the Value data to **1** and hit **OK** to apply the changes.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Do I Need to Enroll in the Windows Insider Program?

 Windows Insider Program is a feature that allows you to try out new builds and features of Windows OS before they become publicly available. It is a great way to get early access to new features and provide feedback to Microsoft. The program is free to join, and you can opt out at any time.

 If you are considering joining the Windows Insider Program, here are a few things to keep in mind:

1. First, you should be aware that by joining the program, you will be sharing information with Microsoft about your device and how you use it. This information will help Microsoft improve Windows 10 for all users.
2. The second thing you should know is how beta testing works. When you join the Windows Insider Program, you can test out the new features and give feedback to Microsoft. It is important to note that you will be using pre-release software that could be unstable. Some of these builds may have bugs or other issues that could cause problems for your computer.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Would You Want to Prevent Access to Insider Builds?

 There are a few reasons people may want to prevent access to insider builds:

1. Insider builds are usually released before the public version, which means there could be more bugs and glitches.
2. It often contains new features that aren't ready for everyone to use, and some prefer the stability of the older versions.
3. Last but not least, insider builds are often released more frequently. As a result, they are harder to maintain, and some people would prefer a slower update rate for public builds.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## The Windows Insider Preview Build, Now Disabled

 If you want to prevent others from downloading and installing Insider Preview Builds on your Windows 11, you can turn off the Insider Preview feature on your computer. There are two ways to do this, either through the Group Policy Editor or through the Registry Editor. You can learn more about this in the article.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-groundbreaking-strategies-30-innovative-facebook-moves/"><u>[New] 2024 Approved  Groundbreaking Strategies  30 Innovative Facebook Moves</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-analyzing-the-frequency-of-youtube-payments/"><u>[New] In 2024, Analyzing the Frequency of YouTube Payments</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-mastering-subtitle-craft-with-the-best-online-resources-today-for-2024/"><u>[New] Mastering Subtitle Craft with The Best Online Resources Today for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-swift-skim-windows-file-compilation-for-2024/"><u>[New] Swift Skim Windows File Compilation for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-tailored-insights-setting-up-your-personalbusiness-yt-channel-mobilely/"><u>[Updated] 2024 Approved  Tailored Insights  Setting Up Your Personal/Business YT Channel Mobilely</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-accelerating-instagram-videos-mobile-and-desktop-tips/"><u>[Updated] In 2024, Accelerating Instagram Videos  Mobile & Desktop Tips</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-top-8-recommendations-tripods-for-sharp-4k-images-for-2024/"><u>[Updated] Top 8 Recommendations  Tripods for Sharp 4K Images for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/best-approaches-to-capture-and-share-compelling-customer-experiences/"><u>Best Approaches to Capture and Share Compelling Customer Experiences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquer-the-0x0-error-essential-fixes-for-win11-users/"><u>Conquer the 0X0 Error: Essential Fixes for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-error-e1-for-surface-go-win10/"><u>Correcting Error E1 for Surface Go (Win10)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-memory-the-easy-way-to-identify-ram/"><u>Decoding Windows Memory: The Easy Way to Identify RAM</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ensuring-seamless-live-stream-quality-with-steam/"><u>Ensuring Seamless Live Stream Quality with Steam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-knowledge-on-vcplusplus-distribution/"><u>Essential Knowledge on VC++ Distribution</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-non-windows-apps-for-modern-computing/"><u>Essential Non-Windows Apps For Modern Computing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-opengl-issue-3-with-nvidia-on-windows-11-os/"><u>Fixing OpenGL Issue #3 with NVIDIA on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-through-the-maze-of-windows-10-crash-modes/"><u>Guide Through the Maze of Windows 10 Crash Modes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-critical-js-error-affecting-discord-on-modern-windows-devices/"><u>How to Resolve Critical JS Error Affecting Discord on Modern Windows Devices</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-securely-perform-a-factory-restore-on-your-dell-inspiron-notebook/"><u>How To Securely Perform a Factory Restore on Your Dell Inspiron Notebook</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-lava-blaze-pro-5g-easily-by-drfone-android/"><u>How To Unlock a Lava Blaze Pro 5G Easily?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-honor-90-lite-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Honor 90 Lite FRP Android 10/11/12/13</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-spark-10-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Tecno Spark 10 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/in-depth-analysis-executing-powerful-registry-changes-via-terminal/"><u>In-Depth Analysis: Executing Powerful Registry Changes via Terminal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/initiating-quick-assistance-on-windows-11/"><u>Initiating Quick Assistance on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/insight-into-vcplusplus-redistributable-needs/"><u>Insight Into VC++ Redistributable Needs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-fix-loaded-lol-screens/"><u>Mastering Windows: Fix Loaded LOL Screens</u></a></li>
<li><a href="https://win11-tips.techidaily.com/protecting-privacy-the-ultimate-windows-encryption-list-152-chars/"><u>Protecting Privacy: The Ultimate Window's Encryption List (152 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redefine-the-point-of-interest-with-new-cursor-style/"><u>Redefine the Point of Interest with New Cursor Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-online-status-for-wow-gamers/"><u>Restoring Online Status for WoW Gamers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sidestep-mobility-center-stay-in-full-screen/"><u>Sidestep Mobility Center, Stay In Full Screen</u></a></li>
<li><a href="https://win-answers.techidaily.com/simple-solutions-for-resolving-a-corrupted-steam-game-disc/"><u>Simple Solutions for Resolving a Corrupted Steam Game Disc</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ified-processes-instantly-clearing-youtube-comments-for-2024/"><u>Simplified Processes  Instantly Clearing Youtube Comments for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/snapping-into-action-activate-snipping-tool-in-windows-11/"><u>Snapping Into Action: Activate Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-dealing-with-immutable-energy-states-in-windows-11/"><u>Solutions for Dealing with Immutable Energy States in Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/step-by-step-process-for-integrating-music-in-facebook-videos-for-2024/"><u>Step-by-Step Process for Integrating Music in Facebook Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tailored-security-for-browsers-trustable-sites-in-windows-11/"><u>Tailored Security for Browsers: Trustable Sites in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tame-excessive-system-update-notifications-in-windows-11/"><u>Tame Excessive System Update Notifications in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-fix-errors-with-windows-alt-codes/"><u>Techniques to Fix Errors with Windows ALT Codes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-unblock-overloaded-gpt-windows-errors/"><u>Tips to Unblock Overloaded GPT Windows Errors</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/transform-your-instagram-experience-with-obs-livestreaming-techniques/"><u>Transform Your Instagram Experience with OBS Livestreaming Techniques</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-bar-icon-failures/"><u>Troubleshooting Windows Bar Icon Failures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-your-pcs-touchpad-response-speed/"><u>Tweaking Your PC's Touchpad Response Speed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-windows-code-0x80780119-restore-mishap/"><u>Unraveling Windows' Code 0X80780119 Restore Mishap</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-start-button-revived-an-instruction-guide/"><u>Windows Start Button Revived: An Instruction Guide</u></a></li>
<li><a href="https://win-howtos.techidaily.com/wwe-2k-fixing-the-gameplay-error-on-dx11-with-feature-level-100/"><u>WWE 2K: Fixing the Gameplay Error on DX11 with Feature Level 10.0</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>