---
title: "Easy Method: Turn Off PIN During Windows 11 Display Cast"
date: 2024-11-29T18:07:42.309Z
updated: 2024-12-06T20:11:18.851Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Easy Method: Turn Off PIN During Windows 11 Display Cast"
excerpt: "This Article Describes Easy Method: Turn Off PIN During Windows 11 Display Cast"
keywords: Disable WIDDisplayPIN,Turnoff PinWindows11Cast,Eliminate DisplayPINLock,Remove PinOnWindows11Screen,Dismiss PINForWindows11Cast,Erase Windows11DisplayPIN,Omit PINInWindows11Cast
thumbnail: https://thmb.techidaily.com/b513a033c1a351aae3735f8454f39fad640e3916330df7f776c432bd4bea35f1.jpg
---

## Easy Method: Turn Off PIN During Windows 11 Display Cast

 Windows requires a PIN when projecting your computer onto another screen, such as a projector or a second monitor. Doing so prevents others from accessing your private information or projecting their content onto your computer.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Using Windows Settings

 Windows has a built-in app that allows you to change various settings. You can use this app to turn off the “require PIN for pairing” setting when projecting to your PC. Here’s how to do it:

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left sidebar, select the **System** tab.
3. Scroll down to the **Projecting to this PC** section and click on it.

 On the next page, look for the **Require a PIN for pairing** setting. Click on its drop-down menu, and you’ll see three options:

* **Never:** Never ask for a PIN for pairing when projecting to this PC.
* **First Time:** Require a PIN the first time you’re projecting to this PC.
* **Always:** Always requiring a PIN for pairing when projecting to this PC.

 Choose the **Never** option and exit the Settings window. The settings will be saved automatically, and you won’t need to enter a PIN when projecting your computer onto another display.

 If you don’t see **Require a PIN for pairing** in the **Projecting to this PC** section, the feature is disabled on your computer.

 To enable this feature, click on the **Optional features** link. You can also navigate to **Settings** \> **Apps** \> **Optional features** to access the same page. Doing so will open the optional features window.

![Add the Wireless Display optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-the-wireless-display-optional-feature.jpg)

 Click the **Add an optional feature** button and search for **Wireless Display**. You should see the Wireless Display feature listed in the search results. Check the box next to it and click **Next** \> **Install**.

![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-an-optional-feature.jpg)

 Once the feature is installed, return to the Projecting to this PC section in Settings. You should now see the “require a PIN for pairing” setting. Choose the **Never** option and close the window.

## 2\. Using the Group Policy Editor

 Another option is to use the Group Policy Editor. This method requires you to have a Pro or Enterprise Windows version. However, you can [activate the Group Policy Editor in Windows Home Edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Once you’ve done that, follow these steps to turn off the feature:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Group Policy Editor window.
3. From the left sidebar, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Connect​`
4. On the right side of the window, look for **Require pin for pairing** and double-click on it. Doing so will open the policy settings page.  
![Disable the Require pin for pairing policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-require-pin-for-pairing-policy.jpg)
5. Select the **Enabled** radio button and select **Never** from the drop-down menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Never Require Pin For Pairing in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-require-pin-for-pairing-in-gpe.jpg)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Using the Registry Editor

 If you can’t access the Group Policy Editor, you can use the Registry Editor to disable the “Require PIN for Pairing” setting. This method involves editing the Windows registry, so [creating a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding is essential. That way, you can easily restore your computer if anything goes wrong.

 Once you’ve done that, follow these steps to turn off the feature:

1. Press the **Windows** key to open the Start menu.
2. Type **regedit** in the search bar and hit **Enter** to open the Registry Editor.
3. If the User Account Control window prompts, click **Yes** to give the program permission.
4. In the left sidebar, navigate to this path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect`
5. If you don’t see the Connect key at this location, right-click on Windows and select **New > Key**. Name it **Connect** and press **Enter**.
6. Now, right-click on Connect and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **RequirePinForPairing** and press **Enter**. Doing so will create a new DWORD in the registry.
8. Double-click on this newly created value to open its Properties window.  
![Tweak Registry to Disable Require PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/tweak-registry-to-disable-require-pin-for-pairing.jpg)
9. Set the **Value data** to **0** and click **OK** to save the changes.

 Once you've done that, exit the Registry Editor window and restart your computer. After restart, you won't need a PIN when projecting your computer onto another screen.

 To turn the feature back on, follow the same steps but set the **Value data** to **1**. This will enable the required PIN for pairing settings when projecting to a Windows 11 PC​​​​​.

## 4\. Using a REG File

 The fourth and final option is to use a REG file. This method is for those who have little or no experience with the Registry Editor. The REG file contains instructions that edit the Windows registry on your behalf. If you'd rather use this method, here’s what you need to do:

1. Right-click on Start and select **Run** from the menu.
2. Type **Notepad** in the text field and press **Enter**.
3. In the Notepad window, type or copy-paste the following code lines:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000001`
4. Click **File** and select **Save as** from the menu.
5. In the Save As window, click the **Save as type** drop-down menu and select **All files**.
6. Name the file **DisableRequirePin.reg** and select **Desktop** from the left sidebar.  
![Disable the Required PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-required-pin-for-pairing.jpg)
7. Now click **Save** and exit Notepad. You'll find the REG file on your desktop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8. Double-click on it and select **Yes** when prompted. This will edit the registry on your behalf.

 Once done, restart your computer and the settings will be saved automatically. You won't need to enter a PIN when projecting your PC onto another screen.

 If you ever want to re-enable this feature, repeat the same steps as above and use this code in Notepad:

`<code>Windows Registry Editor Version 5.00  
  
[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000003`

 Save the file with the **EnableRequirePin.reg** filename and double-click on it to edit the registry.

 After that, restart your computer and the setting will be enabled. You'll now need to enter a PIN each time you project the PC onto another screen.

## Project to a Windows 11 PC Without Requiring a PIN

 Projecting your PC onto another display is a useful feature that allows you to mirror or extend your computer screen. Now you know how to do so without needing to enter your PIN every time.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-a-compreehers-path-to-aspect-ratio-mastery-in-facebook-videos/"><u>[Updated] In 2024, A Compreeher's Path to Aspect Ratio Mastery in Facebook Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-professional-insights-crafting-and-sharing-360-videos-on-fb/"><u>[Updated] In 2024, Professional Insights Crafting & Sharing 360 Videos on FB</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-seeking-the-perfect-samsung-gear-360-replacement-our-list-of-2023s-best-cameras/"><u>[Updated] In 2024, Seeking the Perfect Samsung Gear 360 Replacement Our List of 2023'S Best Cameras</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-toolwiz-photos-app-complete-review/"><u>[Updated] Toolwiz Photos App – Complete Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-mystery-of-group-policies-on-windows/"><u>Decoding the Mystery of Group Policies on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-windows-rule-book-through-3-views/"><u>Decoding the Window's Rule Book Through 3 Views</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-game-crashes-expert-tips-for-running-guilty-gear-strive-smoothly-on-a-computer/"><u>Fixing Game Crashes: Expert Tips for Running Guilty Gear Strive Smoothly on a Computer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-missing-file-how-to-handle-mcuicntexe-failure/"><u>Fixing Missing File: How to Handle McUICnt.exe Failure</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/gpt-blueprint-custom-chatgpt-crafting-guide/"><u>GPT Blueprint: Custom ChatGPT Crafting Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Infinix Hot 30i? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masteringdarkschemeonnotepadwinos/"><u>MasteringDarkSchemeOnNotepadWinOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-windows-issues-made-simple/"><u>Navigating Through Windows Issues Made Simple!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-16-top-rated-free-avi-rotators-for-windows-mac-android-and-iphone-for-2024/"><u>New 16 Top-Rated Free AVI Rotators for Windows, MAC, Android, and iPhone for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-login-failure-duration-in-win-1011/"><u>Personalizing Login Failure Duration in Win 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-cleanup-windows-self-deleting-system-guide/"><u>Streamline Cleanup: Windows' Self-Deleting System Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-your-windows-with-expert-wsl-2-docker-techniques/"><u>Transforming Your Windows with Expert WSL 2 Docker Techniques</u></a></li>
</ul></div>

