---
title: Correcting File Access Failures in Microsoft Office Outlook
date: 2024-06-25T16:30:58.374Z
updated: 2024-06-26T16:30:58.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting File Access Failures in Microsoft Office Outlook
excerpt: This Article Describes Correcting File Access Failures in Microsoft Office Outlook
keywords: Fix Outlook Files,Overcome Access Errors,Resolve Outlook I/O Issues,Tackle OLK File Problems,Cure Office Outlook Failures,Eradicate Email Access Mistakes,Correct Outlook Data Entry
thumbnail: https://thmb.techidaily.com/fb656afcca36e04556318b24814fb553c32e021b58e5e7b1eb34d691269dedb8.jpg
---

## Correcting File Access Failures in Microsoft Office Outlook

 Do you keep getting the "this file cannot be previewed" error when previewing attachments in Outlook? The good news is that you don't need to download attachments every time you want to view them, as it is possible to fix this annoying issue.

 Below, we share eight quick and easy fixes for resolving the “this file cannot be previewed” error in Outlook for Windows.

## 1\. Install Relevant Apps to Preview Files

 Outlook may fail to preview attachments if the appropriate app for the file format is not installed on your PC. For instance, if you don’t have a [PDF reader app on your PC](https://www.makeuseof.com/tag/6-pdf-readers-windows/) , Outlook may display the “this file cannot be previewed because there is no previewer installed for it” error.

 To avoid this, ensure that the appropriate app or software for the file format is available on your computer. After that, Outlook should be able to preview your files without any problems.

## 2\. Disable Preview Handler in PowerToys

 Using Microsoft PowerToys is an excellent way to [boost your productivity on Windows computers](https://www.makeuseof.com/set-up-windows-pc-maximum-productivity/) . However, these PowerToys utilities can sometimes interfere with app processes and prevent apps from working properly.

 Several users on the forums reported fixing Outlook’s “this file cannot be previewed” error by disabling the Preview Handler feature. You can also give this method a shot.

1. Open the**PowerToys** app using the search menu.
2. Switch to the**File Explorer add-ons** tab using the left sidebar.
3. Under the**Preview Pane** section, disable the toggle next to**Portable Document Format** .  
![Disable Preview Handlers in PowerToys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-preview-handlers-in-powertoys.jpg)

## 3\. Enable Attachment Preview in Outlook

 It's possible that Outlook is failing to preview attachments because the file previewer feature is disabled in the app. To overrule this possibility, you need to check the attachment handling settings in Outlook.

1. Open the**Outlook** app on your PC.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left sidebar.
4. Navigate to the**Trust Center** tab and click the**Trust Center Settings** button.
5. In the**Attachment Handling** tab, clear the**Turn off Attachment Preview** checkbox.
6. Click on**Attachment and Document Previewers** and make sure all the previewers are active. Then, click**OK** .
7. Restart the Outlook app after this and see if you can preview attachments.  
![Attachment Handling in Outlook](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/attachment-handling-in-outlook.jpg)

## 4\. Change Outlook User Interface Settings

 Another thing you can do is tweak the User Interface Settings in Outlook and see if that gets the app to load attachment previews on Windows. Here are the steps for the same:

1. Open the Outlook app and click the**File** menu at the top.
2. Select**Options** from the left column.
3. In the Outlook Options window, navigate to the**General** tab.
4. Under the**User Interface Settings** section, select**Optimize for compatibility** option.  
![Optimize Outlook for Compatibility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/optimize-outlook-for-compatibility.jpg)

 Restart the Outlook app after this and check if the issue is still there.

## 5\. Clear Outlook Cache

 Outlook, like most apps, stores cache files on your computer to reduce loading times. Although this data is supposed to improve app performance, it’s not uncommon for it to become corrupted over time. When this happens, Outlook may malfunction or throw strange errors. You can try deleting the Outlook cache and see if that helps.

To delete Outlook cache data on Windows, use these steps:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Run** from the list.
3. Type**%localappdata%\\Microsoft\\Outlook** in the text box and press**Enter** .
4. In the**RoamCache** folder that appears, select all the files and click the**trash icon** at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

## 6\. Enable Windows Firewall

 Have you disabled Windows Defender Firewall on your computer? That could prevent Outlook from previewing attachments.

 Here's how to check if the Windows Defender Firewall is enabled on your PC.

1. Press**Win + S** to open the search menu.
2. Type**Windows Security** in the search box and press**Enter** .
3. Select**Firewall & network protection** tab from the left pane.
4. Choose a network profile.
5. Enable the toggle for**Windows Defender Firewall** .  
![Enable Microsoft Defender Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-microsoft-defender-firewall.jpg)

## 7\. Modify Registry Files

 Incorrect [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) settings could also cause such anomalies. If that's the case, you'll need to correct the Registry settings manually on your PC.

 Since Registry files contain important settings for Windows and its apps, you should only use this method if you’re familiar with editing Registry files. Also, it’s a good idea to back up all the Registry files before you proceed. If you need help with that, check our guide on [how to back up Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > ​SOFTWARE > ​Microsoft > ​Windows > ​CurrentVersion > ​PreviewHandlers** .
5. Look for the following string values and check the associated**Data** on the right side.  
`{00020827-0000-0000-C000-000000000046} = Microsoft Excel previewer  
{21E17C2F-AD3A-4b89-841F-09CFE02D16B7} = Microsoft Visio previewer  
{65235197-874B-4A07-BDC5-E65EA825B718} = Microsoft PowerPoint previewer  
{84F66100-FF7C-4fb4-B0C0-02CD7FB668FE} = Microsoft Word previewer  
{DC6EFB56-9CFA-464D-8880-44885D7DC193} = Adobe PDF Preview Handler for Vista`  
![Preview Handlers in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/preview-handlers-in-registry.jpg)
6. If any of the above-mentioned values are missing, right-click on an empty spot and select**New > String Value** .
7. Double-click on the newly created string value.
8. Enter the name of the application handler in the**Value data** field and click**OK** .
9. Right-click on the string value, select**Rename** and type the value associated with the application handler.
10. Exit the Registry Editor window and restart your PC.  
![Edit String in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-string-in-registry.jpg)

## 8\. Run the Microsoft Office Repair Tool

 Microsoft Office includes a repair tool for fixing Office apps on Windows. So, if nothing works, you can run this tool to repair the Outlook app. Here's how:

1. [Use one of the many ways to open the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) .
2. Go to**Programs and Features** .
3. Locate and select**Microsoft Office** on the list. Then, click the**Change** button at the top.
4. Select**Quick Repair** and then click**Repair** .  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 Wait for the process to finish and check if you can preview files. If you can't, repeat the above steps to perform an**Online Repair** . As suggestive of its name, this process does necessitate an active internet connection on your computer.

## Preview Your Outlook Attachments Again on Windows

 One of these eight fixes should take care of the “this file cannot be previewed” error in Outlook. If not, you can consider reinstalling the Outlook app as a last resort.

 If you're tired of dealing with the Outlook app's recurring problems, there are plenty of excellent email clients for Windows.


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
<li><a href="https://win11-tips.techidaily.com/tech-free-gaming-setup-dualshock-for-windows-users/"><u>Tech-Free Gaming Setup: DualShock for Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harnessing-the-power-of-google-maps-in-your-windows-system/"><u>Harnessing the Power of Google Maps in Your Windows System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-mastery-a-path-through-preferences/"><u>System Mastery: A Path Through Preferences</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-guide-to-a-neat-system-restart-in-windows-11/"><u>The Essential Guide to a Neat System Restart in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/secrets-of-superior-gaming-with-amd-radeon-tweaks/"><u>Secrets of Superior Gaming with AMD Radeon Tweaks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-steps-to-address-retrieve-settings-error-on-winx/"><u>Quick Steps to Address Retrieve Settings Error on WinX</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-usb-drive-problems-for-efficient-data-handling/"><u>Solving USB Drive Problems for Efficient Data Handling</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-you-dont-have-permission-to-view-this-file-error-on-windows/"><u>How to Fix the “You Don’t Have Permission to View This File” Error on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/securing-your-quest-preventing-crashes-on-your-pcs-platform/"><u>Securing Your Quest: Preventing Crashes on Your PC's Platform</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bring-forth-invisible-5ghz-connections-with-these-fixes/"><u>Bring Forth Invisible 5GHz Connections with These Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-comprehensive-walkthrough-of-youtube-timestamping-techniques/"><u>2024 Approved  A Comprehensive Walkthrough of YouTube Timestamping Techniques</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-here-are-some-of-the-best-free-and-paid-split-screen-video-editors-and-makers-that-you-can-use-online-and-offline/"><u>Updated In 2024, Here Are some of the Best Free and Paid Split-Screen Video Editors and Makers that You Can Use Online and Offline</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-tailoring-timeline-memories-the-look-back-video-expertise/"><u>[Updated] In 2024, Tailoring Timeline Memories  The Look Back Video Expertise</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ideal-extras-for-enhancing-dji-phantom-4-for-2024/"><u>Ideal Extras for Enhancing DJI Phantom 4 for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-leading-offline-pc-screen-recording-software/"><u>In 2024, Leading Offline PC Screen Recording Software</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-discover-two-hands-on-approaches-to-personalize-snapchat-audio/"><u>[Updated] In 2024, Discover Two Hands-On Approaches to Personalize Snapchat Audio</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-easygoing-sounds-scores-of-country-music-to-dance-and-relax-on-tiktok/"><u>[New] Easygoing Sounds  Scores of Country Music to Dance and Relax On (TikTok)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-crafting-a-distinctive-tiktok-stream-hashcode/"><u>[Updated] Crafting a Distinctive TikTok Stream Hashcode</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-a-comprehensive-guide-for-converting-pinterest-video-content-to-mp3-format/"><u>In 2024, A Comprehensive Guide for Converting Pinterest Video Content to MP3 Format</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-pro-max-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 Pro Max Passcode without Computer?</u></a></li>
</ul></div>
