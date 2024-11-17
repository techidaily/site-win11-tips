---
title: Keeping Insider Beta Features Hidden
date: 2024-11-13T16:42:45.690Z
updated: 2024-11-17T19:04:15.091Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Use the System Settings

 If you don't want someone to access the Insider builds, you can disable it from the Windows System settings. This option is hidden in the Windows Update settings, so you will need to navigate through the menus to find it. Here's how to do it:

1. Press **Win + I** to open System settings. You can also open it from the Start menu.
2. Once you're in System Settings, go to **Windows Update**.
3. Then navigate to **Windows Insider Programme** \> **Stop getting preview builds**.  
![Stop Getting Preview Builds in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/stop-getting-preview-builds-in-windows.jpg)
4. Now toggle the **Unenroll this device when the next version of Windows releases** switch to disable it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will prevent the device from downloading further Insider builds even if someone initiates it manually.

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

 Once you have completed the steps above, you will need to restart your computer to ensure the changes are applied. After doing that, you'll no longer be able to install or receive Insider builds. If you ever need to give users access to Insider builds on your computer, open the Local Group Policy Editor again.

 Then, set "Toggle user control over Insider builds" either to the **Not Configured** or **Enabled** option. When you have finished making the changes, click Apply > OK.

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Do I Need to Enroll in the Windows Insider Program?

 Windows Insider Program is a feature that allows you to try out new builds and features of Windows OS before they become publicly available. It is a great way to get early access to new features and provide feedback to Microsoft. The program is free to join, and you can opt out at any time.

 If you are considering joining the Windows Insider Program, here are a few things to keep in mind:

1. First, you should be aware that by joining the program, you will be sharing information with Microsoft about your device and how you use it. This information will help Microsoft improve Windows 10 for all users.
2. The second thing you should know is how beta testing works. When you join the Windows Insider Program, you can test out the new features and give feedback to Microsoft. It is important to note that you will be using pre-release software that could be unstable. Some of these builds may have bugs or other issues that could cause problems for your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Would You Want to Prevent Access to Insider Builds?

 There are a few reasons people may want to prevent access to insider builds:

1. Insider builds are usually released before the public version, which means there could be more bugs and glitches.
2. It often contains new features that aren't ready for everyone to use, and some prefer the stability of the older versions.
3. Last but not least, insider builds are often released more frequently. As a result, they are harder to maintain, and some people would prefer a slower update rate for public builds.

## The Windows Insider Preview Build, Now Disabled

 If you want to prevent others from downloading and installing Insider Preview Builds on your Windows 11, you can turn off the Insider Preview feature on your computer. There are two ways to do this, either through the Group Policy Editor or through the Registry Editor. You can learn more about this in the article.

 However, it's good to remember that Insider builds can contain bugs or other issues that can lead to instability or data loss. If you are running an insider build and don't want anyone else to download the newer version, you can disable their access. Here's how it works.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-finding-value-in-sport-photography-cameras-for-the-price-conscious/"><u>[New] Finding Value in Sport Photography – Cameras for the Price-Conscious</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-ultimate-kinemaster-guide-to-green-screening/"><u>[New] The Ultimate KineMaster Guide to Green Screening</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-covertly-crafted-covers-for-iphones-and-androids/"><u>[Updated] 2024 Approved Covertly Crafted Covers for iPhones & Androids</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-browse-backwards-a-guide-to-facebook-archives-for-2024/"><u>[Updated] Browse Backwards A Guide to Facebook Archives for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-audience-attraction-in-a-minute-comparing-youtubes-shorts-and-tiktoks/"><u>2024 Approved Audience Attraction in a Minute Comparing YouTubes Shorts and TikToks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-video-repair-tool-to-fix-and-repair-corrupt-mp4movavi-video-files-of-c22-by-stellar-video-repair-mobile-video-repair/"><u>Best Video Repair tool to Fix and Repair Corrupt MP4,MOV,AVI video files of C22</u></a></li>
<li><a href="https://win11-tips.techidaily.com/crafting-your-win-os-window-snapping-paradigm/"><u>Crafting Your Win OS Window Snapping Paradigm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dealing-with-hidden-windows-bar-when-edges-are-expanded/"><u>Dealing With Hidden Windows Bar when Edges Are Expanded</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-techkey-bluetooth-dongle-driver-compatible-with-windows-11-7-and-8/"><u>Download Techkey Bluetooth Dongle Driver: Compatible with Windows 11, 7 & 8</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-pc-performance-reducing-extraneous-tasks/"><u>Enhancing PC Performance: Reducing Extraneous Tasks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mysterious-menu-moves-win11s-vanishing-power-option/"><u>Mysterious Menu Moves: Win11's Vanishing Power Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-system-switches-win11s-undetectable-power-feature/"><u>Silent System Switches: Win11's Undetectable Power Feature</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/speedy-realignment-youtube-videos-for-mac-views-for-2024/"><u>Speedy Realignment YouTube Videos for MAC Views for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-correct-windows-1011-photo-package-errors/"><u>Steps to Correct Windows 10/11 Photo Package Errors</u></a></li>
<li><a href="https://win-dash.techidaily.com/toughness-is-the-energy-absorption-capacity-of-a-material-up-to-fracture-combining-strength-and-ductility/"><u>Toughness Is the Energy Absorption Capacity of a Material up to Fracture, Combining Strength and Ductility.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-x80246007-in-windows-updates/"><u>Troubleshooting X80246007 in Windows Updates</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-diagnostic-skills-using-command-prompt-for-pinpointing-and-correcting-windows-errors/"><u>Unlocking Diagnostic Skills: Using Command Prompt for Pinpointing & Correcting Windows Errors</u></a></li>
</ul></div>

