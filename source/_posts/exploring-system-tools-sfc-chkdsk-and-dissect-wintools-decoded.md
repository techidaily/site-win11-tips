---
title: "Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded"
date: 2024-08-28T01:20:29.779Z
updated: 2024-08-29T01:20:29.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded"
excerpt: "This Article Describes Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded"
keywords: SysToolSFC,ChkDSKWinTool,DissectWinHelp,SystemScanCheck,FileSystemAnalyzer,FaultTracingTool,WinToolsDiagnostics
thumbnail: https://thmb.techidaily.com/7e22f518017db6277dcd7e1190b41157a7934026017c8917e3ff6d2a5ba30944.jpg
---

## Exploring System Tools: SFC, CHKDSK, and Dissect - WinTools Decoded

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-pixels-melodic-matches-and-personalization/"><u>[New] 2024 Approved  Pixel's Melodic Matches and Personalization</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-stop-in-app-video-buffering-issues/"><u>[Updated] 2024 Approved  Stop In-App Video Buffering Issues</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-peoples-take-on-vllo/"><u>2024 Approved  The People's Take on VLLO</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-quick-glitch-fix-for-podcast-broadcasts/"><u>2024 Approved  The Quick Glitch Fix for Podcast Broadcasts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-honor-x7b-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Honor X7b | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-ways-to-unlock-iphone-x-screen-lock-by-drfone-ios-unlock-ios-unlock/"><u>Best ways to unlock iPhone X screen lock</u></a></li>
<li><a href="https://extra-tips.techidaily.com/building-bonds-youtube-and-brands-in-unity/"><u>Building Bonds  YouTube and Brands in Unity</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-12-pro-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from 12 Pro 5G</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-windows-n-releases-tech-enthusiasts-guide/"><u>Comparing Windows N Releases: Tech Enthusiast's Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-approach-to-unhandled-exception-in-windows-apps/"><u>Comprehensive Approach to Unhandled Exception in Windows Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-folder-size-evaluation-using-powershell-commands/"><u>Demystifying Folder Size Evaluation Using PowerShell Commands</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-media-player-server-issue/"><u>Eliminating Media Player Server Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-readwrite-errors-in-windows-systems/"><u>Eliminating Read/Write Errors in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-steps-for-google-maps-setup-on-pc/"><u>Essential Steps for Google Maps Setup on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/exploring-alternatives-to-cortana-in-windows-10/"><u>Exploring Alternatives to Cortana in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/final-version-dragon-ball-z-kakarot-with-all-prior-glitches-corrected/"><u>Final Version Dragon Ball Z: Kakarot with All Prior Glitches Corrected</u></a></li>
<li><a href="https://win11-tips.techidaily.com/five-portable-windows-devices/"><u>Five Portable Windows Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-microsoft-store-error-code-0x80073cf3-on-win11/"><u>Fixing Microsoft Store Error Code 0X80073CF3 on Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-gamepad-that-wont-respond/"><u>Fixing Windows Gamepad that Won't Respond</u></a></li>
<li><a href="https://win11-tips.techidaily.com/focusing-on-fixing-the-failed-to-initiate-lunar-client-issue/"><u>Focusing on Fixing the Failed to Initiate Lunar Client Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-troubleshooting-display-with-windows-drivers/"><u>Guide to Troubleshooting Display with Windows Drivers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-effective-is-chatgpt-in-controlling-and-automating-home-environments/"><u>How Effective Is ChatGPT in Controlling and Automating Home Environments?</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-itel-a70-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Itel A70 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-poco-m6-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Poco M6 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-inspire-chuckles-designing-memes-on-kapwing/"><u>In 2024, Inspire Chuckles – Designing Memes on Kapwing</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-visual-effects-on-a-budget-essential-tutorials-and-techniques-from-4-vfx-experts-videos/"><u>In 2024, Mastering Visual Effects on a Budget  Essential Tutorials and Techniques From 4 VFX Experts' Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ingenious-tactics-to-outwit-windows-sign-in-prompts/"><u>Ingenious Tactics to Outwit Windows Sign-In Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-windows-tech-for-premium-macos-experience/"><u>Integrating Windows Tech for Premium macOS Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-edge-written-for-optimal-system-performance/"><u>Managing Edge' Written for Optimal System Performance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-pc-troubles-try-our-top-10-tools/"><u>Navigating PC Troubles? Try Our Top 10 Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/podcast-perfection-on-pc-win-five-no-cost-filters/"><u>Podcast Perfection on PC: Win Five No-Cost Filters</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quieten-the-high-contrast-in-windows-ui/"><u>Quieten the High Contrast in Windows UI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reverting-windows-errors-curb-dwarf-fortress-haltings/"><u>Reverting Windows Errors: Curb Dwarf Fortress Haltings</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/saving-the-fun-downloading-tweets-gif-content-easily-for-2024/"><u>Saving the Fun  Downloading Tweets' GIF Content Easily for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/smartcapture-hd-v2/"><u>SmartCapture HD V2</u></a></li>
<li><a href="https://buynow-info.techidaily.com/stay-chilled-while-you-game-a-comprehensive-review-of-the-havit-five-fan-gaming-laptop-cooler/"><u>Stay Chilled While You Game: A Comprehensive Review of the HAVIT Five-Fan Gaming Laptop Cooler</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-your-system-5-must-have-pc-tools/"><u>Streamline Your System: 5 Must-Have PC Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swiftly-realign-windows-desktop-elements/"><u>Swiftly Realign Windows Desktop Elements</u></a></li>
<li><a href="https://win11-tips.techidaily.com/switching-offon-windows-11s-online-scan-feature/"><u>Switching Off/On Windows 11'S Online Scan Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-inaccessible-game-sessions-due-to-steams-vac/"><u>Tackling Inaccessible Game Sessions Due to Steam’s VAC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-concealreveal-windows-security-zones/"><u>Tactics to Conceal/Reveal Windows Security Zones</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723001242462-they-serve-as-the-base-of-the-food-chain-and-can-sustain-growth-without-external-organic-inputs-due-to-photosynthesis/"><u>They Serve as the Base of the Food Chain and Can Sustain Growth without External Organic Inputs Due to Photosynthesis.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-path-related-issues-in-windows-os/"><u>Troubleshooting Path-Related Issues in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tweaking-security-settings-for-general-pc-users-in-windows/"><u>Tweaking Security Settings for General PC Users in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/undo-customization-reverting-win11-user-permissions/"><u>Undo Customization: Reverting Win11 User Permissions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-apps-to-supercharge-your-windows/"><u>Winning Apps to Supercharge Your Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/your-account-has-been-disabled-in-the-app-store-and-itunes-from-iphone-6-plus-by-drfone-ios/"><u>Your Account Has Been Disabled in the App Store and iTunes From iPhone 6 Plus?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>