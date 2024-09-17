---
title: "Expanding Security Horizons: Longer Pins in Win10/11"
date: 2024-09-12T02:51:41.005Z
updated: 2024-09-16T20:21:07.088Z
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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/2024-approved-unveiling-ideal-frames-per-second-for-excellent-slow-mo-videos/"><u>2024 Approved Unveiling Ideal Frames Per Second For Excellent Slow-Mo Videos</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-xs-max-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone XS Max to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-g22-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Nokia G22 Phone with Broken Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-lift-run-dance-select-the-most-motivating-exercise-tracks/"><u>In 2024, Lift, Run, Dance - Select the Most Motivating Exercise Tracks</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-personalized-guide-to-the-best-android-podcast-apps-top-6-selections/"><u>In 2024, Personalized Guide to the Best Android Podcast Apps – Top 6 Selections</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mitigating-low-virtual-memory-situations-in-vmware/"><u>Mitigating Low Virtual Memory Situations in VmWare</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-cant-add-your-folder-now-a-quick-guide-to-onedrive/"><u>Navigating Through 'Can't Add Your Folder Now': A Quick Guide to OneDrive</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-0x8007045d-error-in-win1011/"><u>Steps to Resolve 0X8007045D Error in Win10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essential-blueprint-constructing-personalized-keys-in-w11/"><u>The Essential Blueprint: Constructing Personalized Keys in W11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/the-top-7-stardew-valley-improvement-packs/"><u>The Top 7 Stardew Valley Improvement Packs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-selection-of-free-streaming-options-reviewed/"><u>Ultimate Selection of Free Streaming Options Reviewed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

