---
title: "Expanding Security Horizons: Longer Pins in Win10/11"
date: 2024-09-11T01:28:10.621Z
updated: 2024-09-12T01:28:10.621Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expanding Security Horizons: Longer Pins in Win10/11"
excerpt: "This Article Describes Expanding Security Horizons: Longer Pins in Win10/11"
keywords: Windows Pin Security,Advanced Win10 Protection,Enhanced OS Safety,Extended PC Security,Secure Win10 Longer Pins,Safe System Updates,Heightened Windows Security
thumbnail: https://thmb.techidaily.com/de4f0312e209bc69406fe77be7db4ffab9fd4723c69e6ec9a49854fd1e940559.jpg
---

## Expanding Security Horizons: Longer Pins in Win10/11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




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




<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.




<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123736/7443" target="_top" id="2123736">
  <img src="//a.impactradius-go.com/display-ad/7443-2123736" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123736/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)





<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-screenflow-unleashed-the-ultimate-macos-experience/"><u>[New] 2024 Approved ScreenFlow Unleashed The Ultimate MacOS Experience</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-all-about-lightroom-a-comprehensive-android-study/"><u>[Updated] In 2024, All About Lightroom A Comprehensive Android Study</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-investors-handbook-for-monetized-youtubers/"><u>[Updated] The Investor's Handbook for Monetized Youtubers</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-windows-aural-amplification-feature/"><u>Diminish Windows Aural Amplification Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-reducing-disk-storage-usage-on-windows/"><u>Essential Tips for Reducing Disk Storage Usage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-why-keeping-windows-11s-alerts-is-important/"><u>Explore Why Keeping Windows 11'S Alerts Is Important</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-malwarebytes-service-connection-failures-on-windows-11-os/"><u>Fixing Malwarebytes' Service Connection Failures on Windows 11 OS</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-note-30-5g-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reviving-non-compatible-controllers-in-windows/"><u>Guide to Reviving Non-Compatible Controllers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-windows-11-emulation-on-vmware-17/"><u>Guiding You Through Windows 11 Emulation on VMWare 17</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/high-res-4k8k10k-bildverbesserung-and-reparatur-mithilfe-von-winxvideos-ai-technologie/"><u>High-Res 4K/8K/10K Bildverbesserung & Reparatur Mithilfe Von WinxVideo's AI-Technologie</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-xiaomi-redmi-k70-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Xiaomi Redmi K70 Quickly? | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-the-astro-a50-microphone-troubleshooting-and-solutions/"><u>How to Fix the Astro A50 Microphone: Troubleshooting and Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-operation-failed-0x0000011b-error-on-windows-10-and-11/"><u>How to Fix the Operation Failed 0X0000011B Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-problem-with-this-windows-installer-package-error-on-windows-10-and-11/"><u>How to Fix the Problem With This Windows Installer Package Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prioritize-calculator-visibility-in-windows/"><u>How to Prioritize Calculator Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-windows-manages-reserved-memory-resources/"><u>How Windows Manages Reserved Memory Resources</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/insider-look-at-youtube-revenue-policies/"><u>Insider Look at YouTube Revenue Policies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-tackling-windows-steam-playback-problems/"><u>Quick Guide: Tackling Windows Steam Playback Problems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-hidden-depths-the-guide-to-activating-windows-private-self-view/"><u>Revealing Hidden Depths: The Guide to Activating Windows' Private Self-View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-shopping-redefined-by-microsofts-ai-hub/"><u>Seamless Shopping Redefined by Microsoft’s AI Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-access-to-non-local-files/"><u>Streamlining Access to Non-Local Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-win11-package-management-using-wingetui/"><u>Streamlining Win11 Package Management Using WingetUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-graphics-errors-a-comprehensive-d3d11-fix-in-windows-1110/"><u>Tackling Graphics Errors: A Comprehensive D3D11 Fix in Windows 11/10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-honor-play-8t-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Honor Play 8T Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-oculus-q2-into-windows-compatible-vr/"><u>Transforming Oculus Q2 Into Windows-Compatible VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-microsofts-intelligent-assistance/"><u>Turn Off Microsoft's Intelligent Assistance</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-steps-for-perfect-setup-of-your-steelseries-arctis/"><u>Ultimate Steps for Perfect Setup of Your SteelSeries Arctis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-roblox-403/"><u>Understanding & Correcting Windows Roblox 403</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-in-built-color-tuning-for-win11-applications/"><u>Utilizing In-Built Color Tuning for Win11 Applications</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualizing-resources-efficiently-taskbar-display-reimagined/"><u>Visualizing Resources Efficiently: Taskbar Display Reimagined</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    