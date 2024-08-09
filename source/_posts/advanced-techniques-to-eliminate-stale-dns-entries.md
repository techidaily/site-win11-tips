---
title: Advanced Techniques to Eliminate Stale DNS Entries
date: 2024-08-08T10:56:25.701Z
updated: 2024-08-09T10:56:25.701Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Techniques to Eliminate Stale DNS Entries
excerpt: This Article Describes Advanced Techniques to Eliminate Stale DNS Entries
keywords: DNS Removal Guide,DNS Deletion Tactics,Outdated DNS Cleanse,DNS Hygiene Techniques,Eliminate Stale DNS,DNS Entries Purge Methods,Advanced DNS Cleaning Strategies
thumbnail: https://thmb.techidaily.com/a080ef814e8219bc0372e6a68a593bc00b4cb1212abb381c555dc4e79829ce23.jpg
---

## Advanced Techniques to Eliminate Stale DNS Entries

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of [DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-efficientuseofyourwebcamforrecording/"><u>[New] 2024 Approved  EfficientUseOfYourWebcamForRecording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-fast-fixes-for-chaotic-youtube-list-ordering/"><u>[New] 2024 Approved  Fast Fixes for Chaotic YouTube List Ordering</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-the-ultimate-guide-sharing-your-private-youtube-snippets-via-email/"><u>[New] 2024 Approved  The Ultimate Guide  Sharing Your Private YouTube Snippets via Email</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-a-compre-written-by-dr-john-smith-phd-in-environmental-science-for-2024/"><u>[New] A Compre Written By  Dr. John Smith, PhD in Environmental Science for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-digital-notepad-delight-photography-enhancers/"><u>[New] Digital Notepad Delight  Photography Enhancers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-ultimate-reference-to-youtube-video-aspect-ratios/"><u>[New] The Ultimate Reference to YouTube Video Aspect Ratios</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-perfect-visual-experience-on-youtube-with-professional-techniques/"><u>2024 Approved  Perfect Visual Experience on YouTube with Professional Techniques</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-poco-f5-pro-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Poco F5 Pro 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-boundaries-broken-five-methods-to-mend-security-shortfalls-in-win/"><u>Boot Boundaries Broken: Five Methods to Mend Security Shortfalls in Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-hardware-ram-management-in-windows-os/"><u>Breaking Down Hardware RAM Management in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-down-windows-pin-change-procedures/"><u>Breaking Down Windows PIN Change Procedures</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-stick-reviving-your-mouses-menu-action/"><u>Breaking the Stick: Reviving Your Mouse's Menu Action</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-through-chromes-black-screen-barrier/"><u>Breaking Through Chrome's Black Screen Barrier</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-formats-mastering-the-art-of-windows-esd-to-iso-conversion/"><u>Bridging Formats: Mastering the Art of Windows' ESD to ISO Conversion</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brighten-up-re-initialize-graphics-drivers-windows-11/"><u>Brighten Up: Re-Initialize Graphics Drivers Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/brightening-up-the-boot-prompts-appearance/"><u>Brightening Up the BOOT Prompt's Appearance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-error-22-and-restore-device-functionality-in-windows-11/"><u>Bypass Error 22 and Restore Device Functionality in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypass-freezes-photoshop-and-windows-guide/"><u>Bypass Freezes: Photoshop & Windows Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-cannot-open-errors-for-writable-files-in-win-oses/"><u>Bypassing 'Cannot Open' Errors for Writable Files in Win OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-blue-screen-chaos-how-to-fix-0x8007045d-on-windows-11/"><u>Bypassing Blue Screen Chaos: How to Fix 0X8007045d on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-permission-errors-on-windows-systems/"><u>Bypassing Permission Errors on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-roadblocks-with-microsoft-teams-eradicating-error-code-80080300/"><u>Bypassing Roadblocks with Microsoft Teams: Eradicating Error Code 80080300</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-interface-limitations-top-solutions/"><u>Bypassing Windows Interface Limitations: Top Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bypassing-windows-task-sequence-error-0x8007000f/"><u>Bypassing Windows Task Sequence Error 0X8007000f</u></a></li>
<li><a href="https://win11-tips.techidaily.com/calibrate-display-colors-go-to-settings-)-system-)-display-and-use-the-built-in-calibration-tool-for-accurate-color-representation/"><u>Calibrate Display Colors: Go to 'Settings' > 'System' > 'Display' And Use the Built-In Calibration Tool for Accurate Color Representation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-itel-p55-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Itel P55?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/capturing-life-one-click-at-a-time-the-ultimate-guide-for-documenting-your-sims-journey-in-sims-4-for-2024/"><u>Capturing Life, One Click at a Time  The Ultimate Guide for Documenting Your Sim's Journey in Sims 4 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cease-sudden-shuts-in-windows-11-systems/"><u>Cease Sudden Shuts in Windows 11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/changing-file-types-with-ease-a-windows-manual/"><u>Changing File Types with Ease: A Windows Manual</u></a></li>
<li><a href="https://win11-tips.techidaily.com/checking-if-windows-11-is-fully-operational/"><u>Checking If Windows 11 Is Fully Operational</u></a></li>
<li><a href="https://win11-tips.techidaily.com/chrome-files-not-syncing-winning-windows-tactics-to-try-first/"><u>Chrome Files Not Syncing? Winning Windows Tactics to Try First</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dj-pros-recommend-our-easy-to-use-free-tempo-detection-tools/"><u>DJ Pros Recommend Our Easy-to-Use Free Tempo Detection Tools</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-nokia-xr21-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Nokia XR21 in Minutes | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-the-compreayers-resource-for-optimal-io-screen-use/"><u>In 2024, The Compreayer's Resource for Optimal IO Screen Use</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unveiling-clarity-overcoming-gopro-haze-challenges/"><u>In 2024, Unveiling Clarity  Overcoming GoPro Haze Challenges</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-5-essentials-a-guide-to-purchasing-your-ideal-gaming-system/"><u>Top 5 Essentials: A Guide to Purchasing Your Ideal Gaming System</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-6-essential-discount-warehouses-master-the-art-of-savings/"><u>Top 6 Essential Discount Warehouses: Master the Art of Savings</u></a></li>
<li><a href="https://activate-lock.techidaily.com/what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-iphone-12-mini-by-drfone-ios/"><u>What You Want To Know About Two-Factor Authentication for iCloud From your iPhone 12 mini</u></a></li>
</ul></div>
