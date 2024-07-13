---
title: Proven Strategies for Unlocking Store Apps Directory
date: 2024-07-12T17:30:07.097Z
updated: 2024-07-13T17:30:07.097Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proven Strategies for Unlocking Store Apps Directory
excerpt: This Article Describes Proven Strategies for Unlocking Store Apps Directory
keywords: Store Apps Direct List,Accessing Store Directory,Unlocking App Marketplace,App Directory Solutions,Strategy to Open Directories,Enhancing App Accessibility,Mastery of App Directories
thumbnail: https://thmb.techidaily.com/099f29eab2c71ad55d4343f08e03217de8a45609b98e37e8d331924ca8f4791a.jpg
---

## Proven Strategies for Unlocking Store Apps Directory

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.

## What Is the WindowsApps Folder?

 You can find the WindowsApps folder under the **C:\\Program Files** directory in Windows 10 and 11\. This folder has all the files related to UWP packages or Windows apps that you get from the Microsoft Store or that come preinstalled on Windows OS.

 The problem is that a basic Windows user or even a system administrator user account can't access or change the files in the folder. This is because it is owned by a Microsoft account named "TrustedInstaller." We've already covered [everything about TrustedInstaller](https://www.makeuseof.com/tag/what-is-trustedinstaller-and-why-does-it-keep-me-from-renaming-files/) and how to disable it in detail.

![WindowsApps Hidden Folder In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Hidden-Folder.jpg)

 Even if you uninstall or debloat some of the apps on Windows, the core application files are not removed from the WindowsApps folder. So, there are chances that such apps will reappear after a new Windows update.

 This is why we recommend using one of the [popular software uninstallers for Windows](http://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/). Because these tools not only uninstall an app completely but also clean up any leftovers and traces from all the secured folders.

 If you don't know what you're doing—modifying or deleting the files in the WindowsApps folder could cause system errors or even cause the Windows operating system to crash.

 There are many ways to access the WindowsApps folder and bypass the protection to gain access to the necessary files.

## Method 1\. How to Access WindowsApps via File Explorer

 You can easily find the WindowsApps folder in the Windows File Explorer by unhiding the respective folder first. However, to access the folder and make changes to the files—you need to gain some extra rights by changing the ownership.

 Follow these steps to view the WindowsApps folder first:

1. Open the Windows File Explorer (**Win + E**) and go to the **C:\\Program Files** directory.  
![Program Files Directory In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Program-Files-Directory-In-Explorer.jpg)
2. Now, click the **View** options button at the top of the File Explorer.
3. Click or hover over the **Show** button and select the **Hidden items** option to enable it.  
![File Explorer View Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/file-explorer-view-options.jpg)

 That's it. Now, you can see theWindowsApps folder in the same directory.

 If you try to open it, you'll see an information popup saying, "You have been denied permission." So, to actually access that folder and gain exclusive read and write rights—you've got to do a bit more.

### Change Ownership Properties to Get Access

 For the next steps, you need a user account with administrative rights. If you're a beginner, you must know [everything about the Administrator account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) to understand the steps better.

 Follow the steps mentioned below to change the ownership rights and access the required folder:

1. Select the **WindowsApps** folder and right-click on it.
2. Once the context menu appears, select **Properties** from the list. You can also use a quick shortcut to open the folder properties, i.e., **Alt + Enter**.  
![WindowsApps Properties Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Properties-Option.jpg)
3. Now, under the **Properties** window. Click the **Security** tab and then the **Advanced** option locatedright at the bottom.  
![WindowsApps Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Security-Properties.jpg)
4. Once you've opened the Advanced Security Settings window, click the **Change** text next to Owner.
5. Now, click **Advanced > Find Now > Administrator on the following screen**.  
![Advanced Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-properties.jpg)
6. Finally, click **OK** to select the Administrator as the owner and again **OK** to save the changes.  
![User Group Selection Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/User-Group-Selection-Window.jpg)
7. Then, tick the checkbox before the **Replace owner on sub containers and objects** text.
8. Now, click the **Apply** button, followed by the **OK** button, to initiate the process of transferring ownership.  
![WindowsApps Advanced Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Advanced-Security-Settings.jpg)
9. Once done, click the **OK** button on the next pop-up.

 If you followed the steps above to take ownership of the WindowsApps folder, you can now move or delete files from that folder.

 When you don't pause automatic software installations from the Microsoft store, the WindowsApps folder occupies a considerable bit of disc space. So, it becomes essential for you to access this folder once and check for the files that you no longer need.

 Moreover, you can also check out some [free tools for taking control of files and folders](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) on Windows. Such tools allow you to take full ownership of all your files and folders with a single click.

## Method 2\. How to Access WindowsApps via a PowerShell Command

 The File Explorer-based method is pretty complicated for a newbie. Use PowerShell to complete your job if you're looking for an easy-to-go method. Using Windows PowerShell is a pretty straightforward and automated way of doing the same thing.

 Follow these steps to access the WindowsApps folder using PowerShell:

 1\. Launch the Windows start menu or Windows search by pressing **Win + Q**.

 2\. Type in **PowerShell** and click the **Run as Administrator** option to run PowerShell with administrator rights. Besides, you must also know some other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) for future usage.

![PowerShell In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-In-Windows-Search.jpg)

 4\. In Powershell, run the following command and press the Enter key:

`takeown /f &ldquo;C:\Program Files\WindowsApps&rdquo; /r`

![Change Ownership Command In Shell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Change-Ownership-Command-In-Shell.jpg)

 The above command will restore all the files or folder ownership to the system administrator. It will take some time for your administrator user account to become the owner of the WindowsApps folder and everything in it.

 The access you gain by executing the above process is similar to that of the Windows File Explorer-based method. You have just automated the process and eliminated the unhiding of system files. Now, you can back up, clear some space, or make changes to the Windows apps' back-end files.

 If you're facing crashes while executing the file, make sure to check out some [effective ways to fix PowerShell crash errors](http://www.makeuseof.com/windows-powershell-has-stopped-working-error-fix/).

## 3\. How to Access WindowsApps via a Registry Hack

 There's another quick way to do the same thing with just a few steps. If you cannot use the PowerShell method stated above, you can use a simple registry hack to access the files in one go.

 Here's how you can take full ownership of the context menu for your files and folders and get to the WindowsApps folder:

1. Download the [Take Ownership registry](https://www.majorgeeks.com/files/details/take%5Ffull%5Fownership%5Fof%5Ffiles%5Ffolders%5Fregistry%5Fhack.html) file.
2. Extract the zip and open the **Add Take Ownership to Context menu** registry file.  
![Take Ownership Registry File In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Registry-File.jpg)
3. On the next screen, click **Yes** to add it to the registry.
4. Next, exit the popup by clicking **OK** and navigate to the **C:\\Program Files** directory.
5. Select the **WindowsApps** folder and right-click on it.
6. From the context menu, click the **Take Ownership** option.  
![Take Ownership Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Context-Menu.jpg)
7. In the Command Prompt, you must [give User Account Control Administrator rights](https://www.makeuseof.com/tag/user-account-control-windows-10/) for the registry hack to work. After that, please wait a few minutes for the window to close. Soon, it will display success messages constantly in the Command Prompt.

 Once finished, you'll no longer face the "You've been denied permission" error on clicking the WindowsApps folder.

## Enjoy Unrestricted Access to the WindowsApps Folder

 Using one of the provided methods, you should now be able to view the hidden files and folders inside the WindowsApps folder. Now that you know everything about it, you can easily make changes to the UWP packages that are safe.

 Moreover, in the WindowsApps folder—you can remove Windows app remnants, open any software directly from the .EXE file, and inspect all removed packages, among other things.

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11-tips.techidaily.com/unlock-maximum-speed-for-your-digital-purchases-at-microsoft/"><u>Unlock Maximum Speed for Your Digital Purchases at Microsoft</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-laptop-or-desktop-windows-era/"><u>Unveiling Laptop or Desktop Windows Era</u></a></li>
<li><a href="https://win11-tips.techidaily.com/swift-swordsmans-secrets-tackle-windows-lag-in-star-wars-battlefront-2/"><u>Swift Swordsman's Secrets: Tackle Windows Lag in Star Wars Battlefront 2</u></a></li>
<li><a href="https://howto.techidaily.com/fix-vivo-y27-4g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Vivo Y27 4G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-for-generating-flawless-ai-images-on-windows-11-through-paint-tool-sai/"><u>The Ultimate Guide for Generating Flawless AI Images on Windows 11 Through Paint Tool SAI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tactics-to-implement-without-obstacles-win11-version-22h2-update/"><u>Tactics to Implement Without Obstacles: Win11 Version 22H2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/winning-against-zero-x-eight-oh-three-one-f-failures-in-mail-apps/"><u>Winning Against Zero X Eight Oh Three One F Failures in Mail Apps</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transformative-troubleshooting-tips-to-ease-team-communication-errors-on-w11/"><u>Transformative Troubleshooting Tips to Ease Team Communication Errors on W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/correcting-taskbar-icons-that-dont-pop-up/"><u>Correcting Taskbar Icons that Don't Pop Up</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-winning-software-for-the-ultimate-pc/"><u>Discover Winning Software for the Ultimate PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-the-secrets-pro-level-iphone-landscape-tips/"><u>Unlocking the Secrets  Pro-Level iPhone Landscape Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-easy-steps-to-starting-an-instagram-live/"><u>[Updated] Easy Steps to Starting an Instagram Live</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-samsung-galaxy-m14-4g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Samsung Galaxy M14 4G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/strategy-to-eradicate-error-0x80300024-on-pcs/"><u>Strategy to Eradicate Error 0X80300024 on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-windows-navigation-tips-on-using-narrator-commands/"><u>Streamlining Windows Navigation: Tips on Using Narrator Commands</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-8-valuable-image-ratio-changer-online/"><u>New In 2024, 8 Valuable Image Ratio Changer Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-ui-evolution-focusing-on-the-taskbar/"><u>Windows UI Evolution - Focusing on the Taskbar</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-a-digital-identity-simple-steps-to-create-businesspersonal-youtube-channels-on-smartphones/"><u>In 2024, Crafting a Digital Identity  Simple Steps to Create Business/Personal YouTube Channels on Smartphones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-master-your-edits-with-top-15-affordable-web-based-editors-2023/"><u>[New] Master Your Edits with Top 15 Affordable Web-Based Editors, 2023</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-roblox-availability-tackling-windows-settings-issue/"><u>Unblocking Roblox Availability: Tackling Windows Settings Issue</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-phantom-3-encounter-veil-4s-entry/"><u>[New] Phantom 3 Encounter  Veil 4'S Entry</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-say-goodbye-to-watermarks-top-online-tiktok-logo-removers-for-2024/"><u>New Say Goodbye to Watermarks Top Online TikTok Logo Removers for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/7-ways-to-fix-the-windows-services-tool-when-it-wont-open-or-respond/"><u>7 Ways to Fix the Windows Services Tool When It Won't Open or Respond</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-audiovisual-precision-how-to-refine-sound-quality-by-eliminating-ambient-noises-in-premiere-pro-for-2024/"><u>New Audiovisual Precision How to Refine Sound Quality by Eliminating Ambient Noises in Premiere Pro for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/beneath-the-spotlight-top-youtube-events-after-vidcon-for-2024/"><u>Beneath the Spotlight  Top YouTube Events After VidCon for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-making-sense-of-blue-screen-in-w11/"><u>Comprehensive Tutorial: Making Sense of Blue Screen in W11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-apple-iphone-14-pro-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your Apple iPhone 14 Pro and iPad?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-overcoming-windows-onedrives-cant-add-now-error/"><u>Step-by-Step Guide: Overcoming Windows OneDrive's 'Can’t Add Now' Error</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-zte-nubia-flip-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to ZTE Nubia Flip 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-picture-perfect-pieces-diy-collage-masterclass/"><u>[New] Picture Perfect Pieces  DIY Collage Masterclass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boundary-setting-for-insider-release-access/"><u>Boundary Setting for Insider Release Access</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-understanding-whatsapps-sound-conversations/"><u>[New] 2024 Approved  Understanding WhatsApp's Sound Conversations</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-maximizing-value-from-youtube-comment-threads/"><u>In 2024, Maximizing Value From YouTube Comment Threads</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-achieve-peak-collaboration-advanced-screen-sharing-techniques-in-discord/"><u>[New] 2024 Approved  Achieve Peak Collaboration  Advanced Screen Sharing Techniques in Discord</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-windows-11s-code-0x0000004e-hurdle/"><u>Addressing Windows 11'S Code 0X0000004E Hurdle</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-facebook-update-essential-strategies-for-social-media-savvy/"><u>2024 Approved  Facebook Update  Essential Strategies for Social Media Savvy</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-mov-files-saving-methods-for-windows-10-users/"><u>[Updated] In 2024, .mov Files  Saving Methods for Windows 10 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-guide-for-outdated-pcs-on-their-way-to-windows-11/"><u>The Guide for Outdated PCs on Their Way to Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevating-system-speed-strategies-for-virtual-memory-upgradation-in-windows-11/"><u>Elevating System Speed: Strategies for Virtual Memory Upgradation in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-samsung-galaxy-xcover-6-pro-tactical-edition-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Samsung Galaxy XCover 6 Pro Tactical Edition Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-pro-tips-for-pioneering-board-use-in-webinars-android-iphone-and-windows-users/"><u>In 2024, Pro Tips for Pioneering Board Use in Webinars  Android, iPhone & Windows Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-operational-amd-radeon-ssp-on-windows/"><u>Troubleshooting Non-Operational AMD Radeon SSP on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-security-clean-up-clearing-the-old-protection-data/"><u>Windows Security Clean-Up: Clearing the Old Protection Data</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-deleted-iphone-7-whatsapp-attachments-on-mac-and-windows-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Recover Deleted iPhone 7 WhatsApp Attachments on Mac and Windows | Stellar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-right-pace-for-your-cursor-how-to-turn-off-acceleration-win-11/"><u>The Right Pace for Your Cursor: How to Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-guide-to-windows-11-safe-mode-access/"><u>Step-by-Step Guide to Windows 11 Safe Mode Access</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-unleash-your-tiktok-potential-50plus-powerful-quotes-reviewed-for-2024/"><u>[Updated] Unleash Your TikTok Potential  50+ Powerful Quotes Reviewed for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/activating-advanced-taskbar-features-in-windows-11/"><u>Activating Advanced Taskbar Features in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridging-network-gaps-win-10-and-11-written-for-telnet-users/"><u>Bridging Network Gaps: Win 10 & 11' Written for Telnet Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-pin-removal-functionality-in-windows-11-os/"><u>Restoring PIN Removal Functionality in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-adobes-secrets-ms-store-version-acquisition/"><u>Unlocking Adobe's Secrets: MS Store Version Acquisition</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-6s-plus-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone 6s Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-extensive-analysis-djis-latest-uav-inspire-1/"><u>2024 Approved  Extensive Analysis  DJI's Latest UAV, Inspire 1</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-upload-ps4-screenshots-to-social-media-a-step-by-step-guide/"><u>New 2024 Approved Upload PS4 Screenshots to Social Media A Step-by-Step Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-mouthwateringmatters-leading-food-vloggers/"><u>[New] 2024 Approved  MouthwateringMatters  Leading Food Vloggers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-error-0xc00d36b4-from-win11-devices/"><u>Eliminating Error 0XC00D36B4 From Win11 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-downloading-and-installing-windows-11-arm-from-iso/"><u>Step by Step: Downloading and Installing Windows 11 ARM From ISO</u></a></li>
</ul></div>
