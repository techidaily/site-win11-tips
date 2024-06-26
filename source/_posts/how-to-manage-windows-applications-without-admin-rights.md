---
title: How to Manage Windows Applications Without Admin Rights
date: 2024-06-25T16:53:39.512Z
updated: 2024-06-26T16:53:39.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Manage Windows Applications Without Admin Rights
excerpt: This Article Describes How to Manage Windows Applications Without Admin Rights
keywords: Admin-Free Windows Use,Windows No-Admin Tools,Guest Access in Windows,Navigating Windows Gently,Non-Admin Windows Control,Bypassing Windows Admin,User-Only Windows Management
thumbnail: https://thmb.techidaily.com/9abfa493c09f599241cf74fbf150ee16ae0981c6610495144fe17eca852c8fbd.jpg
---

## How to Manage Windows Applications Without Admin Rights

 Some users have reported an uninstall issue on Microsoft’s forum with an error message that says, “You do not have sufficient access to uninstall.” That error message pops up when users try to uninstall certain software in Windows 11/10\. As a result, users can’t uninstall whatever software packages that error occurs for.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

## 1\. Enable the Windows Admin Account

 First, make sure you’re utilizing an admin account. You can [activate a built-in Windows admin account](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/) via the Command Prompt. Then log in to that built-in admin account and try uninstalling the software from there.

 Alternatively, you can switch a current standard user account to an admin one. Check out this guide to [changing Windows account types](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) for full instructions about how to do so.

## 2\. Run the Affected Software’s Uninstaller File as an Administrator

 Also, run the software’s uninstaller file as an administrator. The software’s installation directory will include its uninstaller file. Right-click that file to select a **Run as administrator** context menu option.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option5.jpg)

## 3\. Troubleshoot With the Program Install and Uninstall Troubleshooter

 Windows doesn’t include any troubleshooter for fixing uninstallation issues. However, there is a Microsoft Program Install and Uninstall troubleshooter that might be useful for fixing the “You do not have sufficient access to uninstall” error. This is how you can run the Program Install and Uninstall troubleshooter:

1. Bring up the troubleshooter's [Microsoft download page](https://support.microsoft.com/en-us/topic/fix-problems-that-block-programs-from-being-installed-or-removed-cca7d1b6-65a9-3d98-426b-e9f927e1eb4d).
2. Then click on the **Download** troubleshooter button.
3. Double-click on the **MicrosoftProgram\_Install\_and\_Uninstall.meta.diagcab** troubleshooter file.  
![The Program Install and Uninstall troubleshooter window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-install-and-uninstall-troubleshooter.jpg)
4. Click on **Next** \> **Uninstalling** to bring up a program list.  
![The Uninstalling option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstalling-option.jpg)
5. Then select the program you can’t uninstall and select **Next**.  
![The Program Install and Uninstall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/program-list.jpg)

## 4\. Turn Off User Account Control

 The “You do not have sufficient access to uninstall” error can sometimes arise because User Account Control is set to high. So, try temporarily turning UAC off before uninstalling the affected software. Our guide on [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off UAC.

![The User Account Control settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control.jpg)

## 5\. Set Full Control Permissions for the Software’s Installation Folder

 You might need to fix this error because the full user control permission setting isn’t set for the software installation’s folder. So, check the control permission settings for the software installation folder. This is how you can set full control permission for a folder:

1. Open the folder that contains the installation directory of the affected software.
2. Right-click on the installation folder and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option3.jpg)
3. Click **Edit** on the **Security** tab.
4. Select your user account name.
5. Click the **Full control** checkbox to select that setting if it’s not already.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-control-window.jpg)
6. Then select **Apply** \> **OK** on the folder’s permissions window.
7. Select **OK** to exit the properties window.
8. Repeat the above instructions for the program’s EXE (application) file.

## 6\. Uninstall the Software With an UninstallString Value

 Some users have resolved this error by uninstalling the affected software packages with their UninstallString values. You can do that by copying and pasting the UninstallString value for a program from the registry into the Command Prompt. These are the steps for uninstalling software with an UninstallString value:

1. Open Windows Search with **Win + S**.
2. Type in **regedit** to find the Registry Editor.
3. Select Registry Editor to launch that app.
4. Next, input this location into Registry Editor’s address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\Windows\CurrentVersion\Uninstall`
5. Click on the subkeys in the **Uninstall** key to view the **DisplayName** strings for them.

1. Select the key for the software you can’t install by identifying it with the **DisplayName** string.  
![DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/display-name.jpg)
2. Double-click on the key's **UninstallString** string.
3. Copy the text in the **Value data** box by selecting it and pressing **Ctrl** \+ **C**.  
![The Edit String window for the UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window3.jpg)
4. Open Command Prompt as an admin (See [how to open Command Prompt with admin permissions](https://www.makeuseof.com/windows-run-command-prompt-admin/)).
5. Click inside the Command Prompt and press **Ctrl** \+ **V** to paste in the string.  
![An uninstall command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/undostring-command.jpg)
6. Press **Enter** to run the command and remove the software.

 Note that the above registry string is for 64-bit software. To find the strings for 32-bit software, you’ll need to go to this registry path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`

## 7\. Try Uninstalling the Software With a Third-Party Uninstaller Tool

 Third-party uninstaller tools have helped some users fix the “do not have sufficient access to uninstall” error. The [best third-party uninstaller tools](https://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/) are superior to Windows’ Programs and Features applet for removing software. So, try uninstalling the software with a freely available utility like Revo Uninstaller, IObit Uninstaller, or Advanced Uninstaller Pro. This is how you can do that with IObit Uninstaller:

1. Open this [IObit Uninstaller](https://www.iobit.com/en/advanceduninstaller.php) download page.
2. Select **Free Download** to save IObit Uninstaller’s setup wizard within a folder.
3. Bring up the directory containing the **iobituninstaller.exe** file.
4. Double-click the **iobituninstaller.exe** file and click **Install** in the setup wizard.
5. Open IObit Uninstaller and select the **All programs** tab.  
![The IObit Uninstaller software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-iobit-uninstaller-software.jpg)
6. Select the program and click **Uninstall**.
7. Click on the checkbox labeled **Automatically remove residual files**.
8. Select **Uninstall** to remove the software.  
![The Uninstall button in IObit Uninstaller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-uninstall-button.jpg)

## 8\. Uninstall the Software Within Safe Mode

 Safe mode is Windows troubleshooting mode in which only essential drivers and services run. Uninstalling affected software in that mode might work since it will disable things like UAC that can interfere with the uninstallation process. This guide about [entering Windows safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) covers the different ways you can enter that mode.

 However, the safe mode also disables Windows Installer (MSI). So, you’ll need to tweak the registry to prevent the disabling of Windows Installer before entering safe mode. Edit the registry as follows:

1. Start the Registry Editor as covered in steps one to three of the sixth potential solution.
2. Then input the following registry key address:  
`HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\SafeBoot\Minimal`
3. Click the **Minimal** key with your right mouse button and select **New**.
4. Select **Key** and input **MSIServer** within the text box. If that key already exists, then you need not set up a new key.  
![The New > Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-key-option.jpg)
5. Next, select the **MSIServer** key and double-click its **(Default)** string.
6. Enter **Service** in the **Value data** box and select **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window4.jpg)
7. Then enter safe mode and try uninstalling the affected software.

## Uninstall the Software You Need to Remove on Windows

 Although not guaranteed, there’s a pretty good chance one of the resolutions in this guide will resolve the “do not have sufficient access to uninstall” error on your PC. If not, consider troubleshooting the issue with a third-party PC repair tool.

 A more drastic troubleshooting method, like resetting Windows 11/10 or performing an in-place upgrade, might be required to fix system file and registry issues.

 That error message highlights the issue is caused by insufficient access. However, the error can arise for users even when they have administrator privileges. This is how you can fix the “do not have sufficient access to uninstall” error in Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/running-state-of-the-art-ai-windows-edition/"><u>Running State-of-the-Art AI: Windows Edition</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-student-essentials-asus-vivobook-s-15-reviewed/"><u>The Ultimate Student Essentials - ASUS Vivobook S 15 Reviewed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-sizing-down-software-on-windows-11/"><u>Mastering the Art of Sizing Down Software on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/previewing-windows-wonders-with-vivetool-capabilities/"><u>Previewing Windows Wonders with ViVeTool Capabilities</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customize-mouse-indicator-for-a-unique-style/"><u>Customize Mouse Indicator for a Unique Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-mending-exception-error-on-win-os/"><u>Understanding and Mending Exception Error on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-windows-error-loadlib-err-87/"><u>Mitigating Windows Error LoadLib Err 87</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-cleanup-automating-deletion-of-files-in-windows/"><u>Quick Cleanup: Automating Deletion of Files in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-6-strategies-for-enhancing-vm-efficiency-in-windows/"><u>Top 6 Strategies for Enhancing VM Efficiency in Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-se-2020-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone SE (2020) without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-cross-platform-comedy-best-meme-contenders/"><u>[Updated] In 2024, Cross-Platform Comedy  Best Meme Contenders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-creating-impactful-learning-experiences-through-video/"><u>2024 Approved  Creating Impactful Learning Experiences Through Video</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-advanced-control-enhancing-your-live-broadcast-experience-for-2024/"><u>[Updated] Advanced Control  Enhancing Your Live Broadcast Experience for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/achieving-professionalism-with-zoom-configurations/"><u>Achieving Professionalism with Zoom Configurations</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-transform-yt-video-quality-utilizing-the-power-of-wm-maker/"><u>[Updated] 2024 Approved  Transform YT Video Quality  Utilizing the Power of WM Maker</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-flash-fixing-fame-is-it-youtubes-shorts-or-tiktok-for-quick-content-conquest/"><u>2024 Approved  Flash-Fixing Fame  Is It YouTubes Shorts or TikTok for Quick Content Conquest?</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-discovering-your-ideal-audio-format-a-step-by-step-strategy/"><u>In 2024, Discovering Your Ideal Audio Format A Step-by-Step Strategy</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-chime-chronicles-mastering-the-art-of-tamil-ringtones-for-2024/"><u>[Updated] Chime Chronicles  Mastering the Art of Tamil Ringtones for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-audio-visual-transcript-maker/"><u>In 2024, Audio Visual Transcript Maker</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>