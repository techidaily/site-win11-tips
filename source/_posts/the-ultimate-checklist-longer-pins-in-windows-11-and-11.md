---
title: "The Ultimate Checklist: Longer PINs in Windows 11 and 11"
date: 2024-06-25T16:09:09.411Z
updated: 2024-06-26T16:09:09.411Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Checklist: Longer PINs in Windows 11 and 11"
excerpt: "This Article Describes The Ultimate Checklist: Longer PINs in Windows 11 and 11"
keywords: Windows 11 PIN Length,Longer Security Pin,Enhanced PC Pincode,Update Windows Pin Policy,11-Version Pin Strategy,Secure Win11 Login,Extended PIN Support (Win11)
thumbnail: https://thmb.techidaily.com/dbe86f0410f8e9bad5bf3228390b329f698cfe445d25a553d85696ff0b2a85a2.jpg
---

## The Ultimate Checklist: Longer PINs in Windows 11 and 11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/streamlining-your-shopping-experience-fixing-error-0x80072f30/"><u>Streamlining Your Shopping Experience: Fixing Error 0X80072F30</u></a></li>
<li><a href="https://win11-tips.techidaily.com/an-insight-into-hardware-allocated-memory-in-windows/"><u>An Insight Into Hardware-Allocated Memory in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decorate-with-style-customizing-themes-for-an-improved-win11-experience/"><u>Decorate with Style: Customizing Themes for an Improved Win11 Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-mouse-icon-with-ease-on-win-os/"><u>Transforming Your Mouse Icon with Ease on Win OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-installer-lacks-permissions-in-windows-1110/"><u>Troubleshooting Installer Lacks Permissions in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-printer-error-0x8000ffff-in-windows/"><u>How to Fix the Printer Error 0X8000ffff in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovery-of-missing-widgets-and-icons-on-windows-11/"><u>Recovery of Missing Widgets and Icons on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/what-youre-overlooking-with-low-priced-activation-keys/"><u>What You're Overlooking with Low-Priced Activation Keys</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-samsung-galaxy-s23-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-hidden-screenshotters-concealed-photography-on-the-snapchat-app/"><u>[Updated] 2024 Approved  Hidden ScreenShotters  Concealed Photography on the Snapchat App</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-motorola-defy-2-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Motorola Defy 2 with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-step-by-step-harvesting-hundreds-of-tiktok-videos/"><u>[New] In 2024, Step-by-Step  Harvesting Hundreds of TikTok Videos</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/preserving-your-google-voice-discussions-a-dual-platform-approach-for-2024/"><u>Preserving Your Google Voice Discussions A Dual-Platform Approach for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-itel-p40plus-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Itel P40+ FRP Bypass Instantly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-oneplus-ace-3-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on OnePlus Ace 3 Phones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-srt-file-playback-windows-and-mac-integration/"><u>2024 Approved  SRT File Playback  Windows & Mac Integration</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-best-free-4k-video-editors-for-beginners-and-pros-alike/"><u>In 2024, The Best Free 4K Video Editors for Beginners and Pros Alike</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>