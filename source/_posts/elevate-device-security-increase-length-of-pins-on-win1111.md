---
title: "Elevate Device Security: Increase Length of PINs on Win11/11"
date: 2024-10-04T20:20:10.698Z
updated: 2024-10-09T05:15:11.430Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevate Device Security: Increase Length of PINs on Win11/11"
excerpt: "This Article Describes Elevate Device Security: Increase Length of PINs on Win11/11"
keywords: Secure Windows PIN,Elevate Win11 Security,Longer Win11 PIN Strength,Enhance Win11 Device Protection,Advanced Win11 Safety Measures,Upgrade Win11 Pin Length,Improve Windows 11 Access Control
thumbnail: https://thmb.techidaily.com/dee28e41650480f8be267c870e6c35efe9b36fe181500be81f958d9b44354162.jpg
---

## Elevate Device Security: Increase Length of PINs on Win11/11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/0-fastest-growing-youtube-channels-to-light-up-your-mind/"><u>[New] 10 Fastest Growing YouTube Channels to Light Up Your Mind</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-no-caps-lock-required-android-and-ios-downloader-hacks/"><u>[New] No Caps Lock Required Android and iOS Downloader Hacks</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transforming-audiencier-names-with-top-ai-tools/"><u>[New] Transforming Audiencier Names with Top AI Tools</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-brain-mechanisms-guiding-high-stakes-business-conclusions/"><u>[Updated] In 2024, Brain Mechanisms Guiding High-Stakes Business Conclusions</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-seamless-audio-junction-expert-logic-pro-x-tips/"><u>2024 Approved Seamless Audio Junction Expert Logic Pro X Tips</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-best-5-programs-for-snagging-facebook-feeds/"><u>2024 Approved The Best 5 Programs for Snagging Facebook Feeds</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-top-10-no-cost-software-for-professional-capture-at-home/"><u>2024 Approved Top 10 No-Cost Software for Professional Capture at Home</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/advanced-black-dashboard-for-professionals-reactive-crm-platform-using-reactstrap-and-bootstrap-v4-created-by-creative-tim/"><u>Advanced Black Dashboard for Professionals: Reactive CRM Platform Using Reactstrap and Bootstrap v4 - Created by Creative Tim</u></a></li>
<li><a href="https://win11-tips.techidaily.com/classic-refresh-a-modern-take-on-windows-98-vibe/"><u>Classic Refresh: A Modern Take on Windows 98 Vibe</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fix-and-fortify-dotnet-windows-style-max-156/"><u>Fix & Fortify DotNet, Windows Style (Max 156)</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-oppo-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Oppo Phones with/without a PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-disabled-firewall-in-windows-os/"><u>How to Reactivate Disabled Firewall in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-recover-pasting-functionality-in-top-browsers/"><u>How to Recover Pasting Functionality in Top Browsers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/jest-jamboree-utilizing-comic-tools-for-free-for-2024/"><u>Jest Jamboree Utilizing Comic Tools for Free for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skytop-techniques-for-elevated-fps-in-roblox/"><u>Skytop Techniques for Elevated FPS in Roblox</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-to-enhanced-win1011-system-graphics-memory/"><u>Step-by-Step to Enhanced Win10/11 System Graphics Memory</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshoot-and-restore-bluetooth-devices-on-win/"><u>Troubleshoot and Restore Bluetooth Devices on WIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-secrets-how-to-fix-the-no-server-error-in-pc-apex-legends-(156-chars/"><u>Unveiling Secrets: How to Fix the No-Server Error in PC Apex Legends (<156 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-gamers-should-prioritize-dxvk-in-their-win-based-setup/"><u>Why Gamers Should Prioritize DXVK in Their Win-Based Setup?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    