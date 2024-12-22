---
title: Exclusive Insight on Locating Windows 11/10 Product Key
date: 2024-12-19T08:24:01.507Z
updated: 2024-12-21T18:55:56.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exclusive Insight on Locating Windows 11/10 Product Key
excerpt: This Article Describes Exclusive Insight on Locating Windows 11/10 Product Key
keywords: Win11KeyFind,WindowsProductCode,KeyLocatorTool,PCKeySearchWin,ProdKeyFinderWin,AccessWindowsKey,LicenseKeyProbeWin
thumbnail: https://thmb.techidaily.com/42e80c71c3e676d07f669fb711246bda708f83a958555a8cf5d9869ea65371d4.jpg
---

## Exclusive Insight on Locating Windows 11/10 Product Key

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell

![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/n-2024-unveiling-the-numbers-comprehensive-guide-to-count-views-clicks-and-cash-in-youtube/"><u>[New] In 2024, Unveiling the Numbers Comprehensive Guide to Count Views, Clicks, and Cash in YouTube</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-iphones-quintet-of-premier-podcast-tools/"><u>[Updated] In 2024, IPhone's Quintet of Premier Podcast Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-failed-ccleaner-scans-in-windows-11/"><u>Fixing Failed CCleaner Scans in Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/game-on-unlock-the-secrets-of-effective-lol-recording/"><u>Game-On! - Unlock the Secrets of Effective LOL Recording</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reestablishing-non-working-ccleaner-in-win1011-pcs/"><u>Guide to Reestablishing Non-Working CCleaner in Win10/11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manage-wi-fi-data-usage-metrics-on-windows-11/"><u>How to Manage Wi-Fi Data Usage Metrics on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-an-absent-printer-windows-solutions/"><u>Restoring an Absent Printer: Windows Solutions</u></a></li>
<li><a href="https://network-issues.techidaily.com/seamless-operation-fallout-4-on-computer/"><u>Seamless Operation: Fallout 4 on Computer</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlining-your-screen-with-updated-hdmi-driver/"><u>Streamlining Your Screen with Updated HDMI Driver</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/the-route-to-richer-tiktok-bios-a-guide-to-linktree-integration/"><u>The Route to Richer TikTok Bios A Guide to Linktree Integration</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-fixing-file-or-directory-corruption-in-win1011/"><u>The Ultimate Guide to Fixing 'File or Directory' Corruption in Win10/11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/troubleshooting-and-updating-webcam-drivers-on-windows-10-a-comprehensive-guide/"><u>Troubleshooting and Updating Webcam Drivers on Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-where.techidaily.com/1728478232736-windows-1011/"><u>Windows 10/11向けデータ消去と初期化の正確な比較：具体的方法とその違いを解明</u></a></li>
</ul></div>

