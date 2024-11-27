---
title: Strategies to Tackle Non-Starting Battle.net on Win 10/11 PCs
date: 2024-11-23T16:23:46.339Z
updated: 2024-11-27T17:48:34.348Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Tackle Non-Starting Battle.net on Win 10/11 PCs
excerpt: This Article Describes Strategies to Tackle Non-Starting Battle.net on Win 10/11 PCs
keywords: Battle.net Freeze Fix,Win 10 Start Issues,Solve Non-Boot Battle.net,Windows XP/Vista Game Launch,PC Boot Strategy Guide,Fixing Battle.net Startup,Overcoming Win Start Problems
thumbnail: https://thmb.techidaily.com/3afd30f31da7656743dda52f15a6af22d0fe17904a91a11b2b12cd01fcb4a3ee.jpg
---

## Strategies to Tackle Non-Starting Battle.net on Win 10/11 PCs

 Battle.net is game launcher software with which users install and play Call of Duty: Warzone, Hearthstone, World of Warcraft, and Overwatch. However, users can’t launch Blizzard games when the Battle.net software doesn’t open on Windows. Battle.net may or may not display an error message when it doesn’t open, but that software doesn’t start either way.

 You can probably resolve whatever Battle.net startup issue you’re trying to fix in Windows, so long as your PC meets the software’s minimum system requirements. These general fixes can resolve a wide variety of Battle.net startup errors or crashes in a Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Set Battle.net to Run With Admin Rights

 This is a simple potential fix for Battle.net not opening that some users have confirmed works. Setting Battle.net to run as administrator will give that software elevated system access, which can resolve permission issues. You can configure Battle.net to always run with administrative rights like this:

1. Open Battle.net’s installation directory (folder) within File Explorer.
2. Next, click the**Battle.net Launcher.exe** file with your right mouse button and select**Properties** .
3. Click**Compatibility** on the Battle.net Launcher.exe Properties window.
4. Select**Run this program as administrator** if that checkbox isn’t selected.  
![The Run this program as an administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/run-this-program-as-administrator-option.jpg)
5. Press the Properties window’s**Apply** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In addition, running the software in compatibility mode might help some users fix Battle.net not opening. You can do that by selecting the**Run this program in compatibility mode** option on the same**Compatibility** tab. Choose Windows 8 on the drop-down menu.

## 2\. Delete the Battle.net and Blizzard Entertainment Data Folders

 Battle.net and Blizzard Entertainment are two cache folders for Blizzard’s game launcher software. The Battle.net software often doesn’t start right when those folders contain corrupted data. Deleting those directories will clear Battle.net’s cache.

This is how you can erase those folders in Windows 11/10:

1. First, make sure there aren’t any Battle.net background processes running by[opening Task Manager’s Process tab](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) . Disable any Battle.net processes you see there by selecting them and clicking**End task** .
2. Hold the**Windows** keyboard key and press**E** to view the Explorer file and folder manager.
3. Clear Explorer’s folder path bar, and input this directory location there: C:\\ProgramData  
![The Blizzard Entertainment folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/blizzard-entertainment-folder.jpg)
4. Right-click the Battle.net directory and select the**Delete** context menu option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-delete-button.jpg)
5. Next, erase the Blizzard Entertainment folder.
6. Try opening Battle.net again.

 This should hopefully clear any cache issues and Battle.net should open correctly.

## 3\. Check the Secondary Logon Service Is Enabled

 The Secondary Logon service enables the starting of processes with alternative types of user credentials. That’s a required prerequisite service for Battle.net’s Blizzard agent. So, check Secondary Login is enabled and running like this:

1. To open Services, click the search box or magnifying glass on your Windows 11/10 taskbar. Type**services.msc** in the search box, and select the Services app.
2. Double-click**Secondary Logon** to view the properties window for that service.  
![The Secondary Logon service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/secondary-logon-service.jpg)
3. Set the**Startup type** option to**Automatic** .
4. Click the**Start** service button for Secondary Logon.  
![The Secondary Logon Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-logon-properties-window.jpg)
5. Remember to select**Apply** to save the setting.
6. Select**OK** to exit the Secondary Logon Properties window.
7. Click**Restart** on the Start menu in Windows 11/10.

 If you find Secondary Logon is already enabled, restart the service instead. Right-click Secondary Logon on the Services window to select**Restart** . Or you can click**Stop** and**Start** in the service’s properties window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall will block Battle.net from connecting with Blizzard services if that software isn’t permitted through it. To test if that firewall is blocking the Battle.net client, temporarily disable it in the following steps:

1. First, open WDF in the Control Panel with a method in our guide for opening the Windows Defender Firewall applet.
2. Select the**Turn Windows Defender Firewall on or off** navigation option on the left of the applet.  
![The Windows Defender Firewall applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-defender-control-panel-applet.jpg)
3. Click the**Turn off Windows Defender Firewall** options for both the public and private network settings.  
![The Turn off Windows Defender Firewall radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/turn-off-windows-defender-firewall-settings.jpg)
4. Select**OK** to save the new WDF options.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Try opening Battle.net again with the firewall disabled.

 If Battle.net now starts, check Windows Defender Firewall’s app permission settings. Make sure the Battle.net software is allowed through that firewall. Check out our article about[allowing apps through the Windows Firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for full instructions. Then you can turn WDF back on.

## 5\. Disable Third-Party Antivirus and Firewall Software

 Some third-party antivirus and firewall software can also block Battle.net from running. Antivirus utilities sometimes wrongly identify legitimate programs to be malware. So, temporarily disable third-party antivirus tools or firewalls before selecting to launch Battle.net if you don’t want to uninstall anything.

 You can usually find options for disabling third-party antivirus software on their context menus. So, right-click an antivirus icon in the system tray and look for an option to disable or turn off its shield on the menu that opens. If that works, you’ll know what’s causing the issue. Whitelist Battle.net in your antivirus tool’s exclusion settings.

## 6\. Disable the Proxy Server

 Proxy servers conflict with Battle.net’s login module, which can prevent the software from launching. Even if you can’t recall enabling a proxy server yourself, double-check the proxy server setting isn’t selected in Windows. You can disable the proxy server as follows:

1. Bring up the file and app search box in Windows.
2. Enter**inetcpl.cpl** in the Type here to search text box.
3. Select**inetcpl.cpl** to view Internet Properties.
4. Click**Connections** to access network options.
5. Next, click**LAN settings** to view a Local Area Network (LAN) window.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/LAN-settings-button.jpg)
6. Uncheck (deselect) the**Use a proxy server** option if its checkbox is selected.  
![The Use a proxy server checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-use-a-proxy-server-checkbox.jpg)
7. Press the**OK > Apply** buttons.

 Malware can activate a proxy server setting on Windows. If you discover a proxy server enabled, but didn’t select it yourself, consider manually running an antivirus scan. Our[Windows Security (Defender) guide](https://www.makeuseof.com/windows-11-quick-security-guide/) tells you how to run a scan with the built-in antivirus utility on Windows.

## 7\. Set Windows 11/10 to Clean Boot

 Clean-booting Windows is when you boot a PC without any third-party startup programs or services automatically starting. Configuring a clean boot disables all such startup apps and services. Our[guide for performing a clean boot on Windows 11](https://www.makeuseof.com/clean-boot-windows-11/) provides details about how to remove all third-party software and services from the startup.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After setting a clean boot, restart your PC and try launching Battle.net. Did that potential resolution work? If it did, clean booting likely eliminated a program or service conflicting with Battle.net. Then you can keep the boot configuration as it is or attempt to figure out what software or service caused the issue.

## 8\. Reinstall the Battle.net Software

 Finally, reinstall Battle.net Launcher if all else fails. Reinstalling that software will replace its files and ensure you’re utilizing the latest version. That won’t uninstall games installed with Battle.net.

![The Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-programs-and-features-applet.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can remove Battle.net in Control Panel’s Programs and Features applet, as outlined in our[guide for uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . After uninstalling the game launcher, open the[Battle.net desktop app](https://www.blizzard.com/en-us/apps/battle.net/desktop) download page; click**Download for Windows** on that page. Then double-click the**Battle.net-Setup.exe** file in whatever folder it downloaded to, and go through the setup wizard to install.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Enjoy Blizzard Battle.net Games Again

 When you’ve got Battle.net up and running again, you’ll be able to download, launch, and play Blizzard games. As there are many potential causes for Battle.net not starting, we can’t guarantee the solutions in this guide will resolve all startup issues for that software.

 However, those potential resolutions will address the most common causes for Battle.net not opening in Windows 11 and 10\. So, there’s a very good chance at least one will kick-start Blizzard’s gaming client on your PC.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-instagram-profit-the-ultimate-strategy-blueprint/"><u>[New] In 2024, Mastering Instagram Profit The Ultimate Strategy Blueprint</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-elite-trailer-showcase-collection/"><u>[Updated] 2024 Approved Elite Trailer Showcase Collection</u></a></li>
<li><a href="https://extra-information.techidaily.com/assessing-acid-pro-top-alternative-software-for-2024/"><u>Assessing ACID Pro Top Alternative Software for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-resolving-updater-error-0x80246007-on-w10w11/"><u>Deciphering and Resolving Updater Error 0X80246007 on W10/W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/hiding-your-drive-in-the-windows-1110-shadows/"><u>Hiding Your Drive in the Windows 11/10 Shadows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-vivo-g2-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Vivo G2 Lock Screen Password?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/methods-to-correctly-interpret-task-managers-cpu-numbers/"><u>Methods to Correctly Interpret Task Manager's CPU Numbers</u></a></li>
<li><a href="https://howto.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-vivo-x90s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveil-the-ultimate-8-online-places-to-find-free-3d-text-files-for-2024/"><u>Unveil the Ultimate 8 Online Places to Find FREE 3D Text Files for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secrets-of-win11s-paint-cocreator-for-generating-imaginative-ai-visuals/"><u>Unveiling the Secrets of Win11's Paint Cocreator for Generating Imaginative AI Visuals</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Samsung Galaxy A23 5G | Dr.fone</u></a></li>
</ul></div>

