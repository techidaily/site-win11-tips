---
title: Evaluating the Need for Maintaining Pagefile.sys Filespace
date: 2024-08-16T01:54:49.374Z
updated: 2024-08-17T01:54:49.374Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Evaluating the Need for Maintaining Pagefile.sys Filespace
excerpt: This Article Describes Evaluating the Need for Maintaining Pagefile.sys Filespace
keywords: Pagefile Evaluation Needs,File Maintenance Importance,Disk Space Usage Critique,.sys Files Impact Analysis,System Performance Optimization,Memory Management Insight,Pagefile.sys Preservation Benefits
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Evaluating the Need for Maintaining Pagefile.sys Filespace

 When your Windows computer is running out of storage space, you may find yourself looking for ways to free up some of it, even if they're a bit unconventional. One of these unconventional methods you may come across is deleting the Pagefile.sys file. But before you consider deleting it, you should know what Pagefile.sys is and if you should delete it in the first place.

Here's what you need to know.

## What Is Pagefile.sys?

 Pagefile.sys is a system file in Windows set aside for your computer’s [Random Access Memory (RAM)](https://www.makeuseof.com/tag/quick-dirty-guide-ram-need-know/) , also known as physical memory. When your computer's RAM begins to run out of memory, it uses the pagefile to offload data it doesn't need, such as files and apps.

 So how does your computer’s RAM decide when to offload data? Let’s use an app as an example of how this works.

 Usually, when you minimize an app, Windows will leave it running in the background. However, it will keep its data in the RAM so it can quickly access them when needed.

 Then, when you boot up a RAM-intensive app, Windows needs to make room for it within the RAM. As such, Windows will instruct your PC’s RAM to dump the minimized app’s program files into Pagefile.sys, so it can free up memory without losing data.

 By default, Windows will store Pagefile.sys in the root folder of your local drive (C:).

 When you need to use the minimized app again, Windows will read its data from the Pagefile.sys file. And you'll be none the wiser that it's compensating for its physical memory shortcomings with the help of your local drive.

 Reading an app’s program files from Pagefile.sys is slower than reading them from RAM. The process is even slower when you're using a hard disk drive (HDD)[instead of a solid-state drive (SDD)](https://www.makeuseof.com/choose-ssd-or-hdd-storage/) . However, It’s faster than closing the app and then relaunching it.

## How to Check the Size of Pagefile.sys

 To prevent tampering with Pagefile.sys, Windows will hide it by default. If you want to see it, here’s what you should do.

1. Press**Win + E** to open File Explorer.
2. Click on**This PC** in the navigation pane on the left and double-click your**local drive (C:)** on the right to open it.
3. Now you need to open Folder Options. On Windows 11, click the**three vertical dots** in the top menu and select**Options** . On Windows 10, click**View** in the top menu and then on**Options** .  
![selecting options in the top menu of file explorer in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/file-explorer-options.jpg)
4. Select the**View** tab in Folder Options and uncheck**Hide protected operating system files (Recommended)** .  
![The unhide protected os files option in folder options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/folder-options-unhide-protected-os-files.jpg)
5. In the warning that pops up, click**Yes** .
6. A bit further up, you see**Hidden files and folders** . Inside it, check the**Show hidden files, folders, and drives** radio button.
7. Click**OK** to close Folder Options and apply the changes.
8. Scroll down in your local drive, and you’ll be able to see Pagefile.sys.  
![the pagefile.sys file in the root folder of the local drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/pagefile-sys-file.jpg)

 As you can see, the Pagefile.sys file is quite large, which makes many people think deleting it is a good idea when they're running out of storage space.

## Should You Delete Pagefile.sys?

 One scenario where it would be reasonable to delete Pagefile.sys to save disk space is if you have a lot of RAM. That way, it can store all the data it needs to keep apps running without needing to offload them. For the average Windows user, the minimum RAM size for this would be 16GB.

 If you delete Pagefile.sys and your computer runs out of physical memory, your system will start to become sluggish. If the sluggishness gets too bad, Windows itself might even crash.

 Also, you might notice some apps becoming slower or crashing as well. That’s because they have nowhere to put the data they need to operate properly since your computer’s RAM is full and there is no Pagefile.sys to pick up the slack.

 So unless your physical memory needs aren’t greater than your installed RAM’s capacity, we recommend leaving Pagefile.sys alone.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Delete Pagefile.sys

 Since Windows is constantly using Pagefile.sys, it will not allow you to delete it in File Explorer directly. In fact, if you selected the file and hit the**Delete** key, you will see the following message: "The action can't be completed because the file is open in another program."

![deleting-pagefile-error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deleting-pagefile-error.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 However, there’s another method you can use to delete the file and save some disk space. To do that, follow the steps below.

1. Press**Win + S** to open Windows Search.
2. Type**sysdm.cpl** in the search box and hit the**Enter** key to open the System Properties window.  
![searching for sysdm.cpl in windows search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-search-sysdm-cpl.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.  
![the system properties dialog box in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/system-properties-advanced.jpg)
4. In the Performance Options window, select the**Advanced** tab and click**Change** .  
![the Perfomance Options window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/performance-options-advanced.jpg)
5. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
6. Click on the radio button for**No paging file** , and click the**Set** button on the right.  
![the Virtual Memory window on Windows with the No paging radio button ticked](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-no-paging-windows.jpg)
7. You’ll get a warning from Windows. Click**Yes** to bypass it.
8. Click on**OK** to close the Virtual Memory window and apply the changes.
9. Restart your Windows computer for the changes to take effect.

 When Windows boots back up, the OS will have no use for Pagefile.sys, and it will delete it from your local drive. It will also delete the Swapfile.sys along with it. If you don't know what that file is and its importance, please read our guide on [what Swapfile.sys is and if you can delete it](https://www.makeuseof.com/windows-swapfile-sys-guide/) .

## How to Restore Pagefile.sys

 If you deleted Pagefile.sys and discovered that you're experiencing problems because of it, you can easily restore it. However, if the problems are so severe that Windows is constantly freezing or can't even boot up properly, you should try entering Safe Mode first. To do that, please check out guides on [ways to boot into Safe Mode on Windows 11](https://www.makeuseof.com/windows-11-boot-safe-mode/) and [what is Safe Mode on Windows 10](https://www.makeuseof.com/windows-11-boot-safe-mode/) .

Now, to bring back Pagefile.sys, follow the steps below:

1. Press**Win + R** to open Windows Run.
2. In the text box, enter**sysdm.cpl** and then hit the**Enter** key to launch the System Properties window.  
![opening the System Properties window using Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/open-system-properties-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
3. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
4. In the Performance Options window, select the**Advanced** tab and click**Change** .
5. In the Virtual Memory window, make sure the**Automatically manage paging file size for all drives** checkbox at the top is checked.
6. Click on**OK** to close the Virtual Memory window and apply the changes.
7. Restart your Windows computer for the changes to take effect.

 Once your computer boots up, and you go to the folder where Pagefile.sys is located, you will see that the file has returned, along with Swapfile.sys.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Resize Pagefile.sys

 If deleting Pagefile.sys isn’t an option for you, consider resizing it instead. Here’s how to do that:

1. Press**Win + E** to open File Explorer.
2. In the Navigation Pane, right-click**This PC** and select**Properties** . On Windows 11, you will have to select**Show more options** first before you can see the**Properties** option.
3. Click on the**Advanced system settings** link to open the System Properties window. On Windows 11, you will find the link on the right panel, while, on Windows 10, it will be on the left side menu.  
![the About page of the System window in the Settings app on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-about-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
4. Select the**Advanced** tab, and in the**Performance** section, click the**Settings** button.
5. In the Performance Options window, select the**Advanced** tab and click**Change** .
6. In the Virtual Memory window, uncheck the**Automatically manage paging file size for all drives** checkbox at the top.
7. Click on the radio button for**Custom size** . Immediately, you’ll see that the two text boxes below it (**Initial size** and**Maximum size**) are no longer grayed out.
8. Enter the appropriate page file sizes in megabytes (MB) in both text boxes and then click**Set** .  
![the virtual memory dialog box on windows with the custom page file size set to 4096](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/virtual-memory-custom-size.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. Click**OK** to close the Virtual Memory window and apply the changes.
10. Restart your Windows computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Pagefile.sys, Demystified

 Pagefile.sys is an extremely important file when it comes to keeping your Windows computer running smoothly. It helps give your PC's RAM more breathing room when physical memory can no longer hold more data. You can delete it, but only do so when you know your computer's RAM has enough capacity to stand on its own. If not, you’re better off just resizing Pagefile.sys so it doesn’t take up too much space.

 If you’re unsure of what to do with Pagefile.sys, just leave it to Windows to handle the file and look for other ways to free up space on your storage drive.

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-profile-pictures-download-for-free/"><u>[New] 2024 Approved  Profile Pictures - Download for FREE</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capture-perfection-iphone-camera-skills-guide/"><u>[Updated] Capture Perfection  IPhone Camera Skills Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-meizu-21-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-realme-12-5g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Realme 12 5G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-guide-to-fix-windows-11-media-issues/"><u>Comprehensive Guide to Fix Windows 11 Media Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/contrast-in-connectivity-tackling-pcs-lag-on-laptops/"><u>Contrast in Connectivity: Tackling PC's Lag on Laptops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracts-for-sudden-windows-notepad-shutdowns/"><u>Counteracts for Sudden Windows Notepad Shutdowns</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-strategies-for-icon-placement-repair/"><u>Effective Strategies for Icon Placement Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-file-management-for-win11-users/"><u>Efficient File Management for Win11 Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-using-github-desktop-in-windows-step-by-step-guide/"><u>Efficiently Using GitHub Desktop in Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-to-mend-windows-store-error-0x0-failure/"><u>Expert Tips to Mend Windows Store Error 0X0 Failure</u></a></li>
<li><a href="https://win11-tips.techidaily.com/getting-plain-in-windows-11-shapes/"><u>Getting Plain in Windows 11 Shapes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-customize-windows-11s-default-screensavers/"><u>How to Customize Windows 11'S Default Screensavers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-there-are-no-more-files-error-on-windows-11-and-11/"><u>How to Fix the “There Are No More Files” Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-manually-check-your-windows-pc-for-signs-of-spyware-or-hacking/"><u>How to Manually Check Your Windows PC for Signs of Spyware or Hacking</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-preserving-audio-broadcasts-a-simple-internet-radio-technique/"><u>In 2024, Preserving Audio Broadcasts  A Simple Internet Radio Technique</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-nuc-driver-updates-simplified-expert-techniques-for-speed-and-ease/"><u>Intel NUC Driver Updates Simplified - Expert Techniques for Speed and Ease</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-your-moves-fixed-tips-to-overcome-windows-lags-in-sw-battlefront-2/"><u>Master Your Moves: Fixed Tips to Overcome Windows Lags in SW Battlefront 2</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-wsl-upgrades-in-new-windows-environments/"><u>Navigating WSL Upgrades in New Windows Environments</u></a></li>
<li><a href="https://tech-revival.techidaily.com/optimize-your-well-being-journey-the-ultimate-guide-to-setting-goals-using-chatgpt/"><u>Optimize Your Well-Being Journey: The Ultimate Guide to Setting Goals Using ChatGPT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-obstacles-in-onedrive-folder-integration-on-windows/"><u>Overcoming Obstacles in OneDrive Folder Integration on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-secure-boot-limits-with-rufus-on-win11/"><u>Overcoming Secure Boot Limits with Rufus on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h-265-on-xiaomi-civi-3-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Xiaomi Civi 3, is it possible?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prepared-participation-test-your-pcs-microphone-webcam/"><u>Prepared Participation: Test Your PC’s Microphone, Webcam</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preparing-vbox-on-win-prioritize-deps-for-smooth-setup/"><u>Preparing VBox on Win: Prioritize Deps for Smooth Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/proactive-approaches-to-linux-in-windows-mastering-wsl-2-techniques/"><u>Proactive Approaches to Linux in Windows: Mastering WSL 2 Techniques</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reinstated-default-printer-on-winerror-0x00000709/"><u>Reinstated Default Printer on WinError (0X00000709)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-and-personalize-window-11s-search-interface/"><u>Revamp and Personalize Window 11'S Search Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-navigation-through-windows-11s-component-tools/"><u>Seamless Navigation Through Windows 11'S Component Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-leftright-earheadphone-audio-issues-in-windows/"><u>Solving Left/Right Earheadphone Audio Issues in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-curtail-tiworkerexe-power-draw/"><u>Techniques to Curtail TiWorker.exe Power Draw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-essentials-of-boot-into-windows-repair/"><u>The Essentials of Boot Into Windows Repair</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-untapped-potential-within-windows-11s-offerings/"><u>The Untapped Potential Within Windows 11'S Offerings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transform-your-desktop-with-customizable-animated-clock-themed-screensaver-creation-tools/"><u>Transform Your Desktop with Customizable, Animated Clock-Themed Screensaver Creation Tools</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-discord-overlays-in-windows-os/"><u>Troubleshooting Non-Functional Discord Overlays in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-error-x7e1-in-windows-10/"><u>Unblocking Error X7E1 in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unblocking-store-error-x800704cf-on-windows-11/"><u>Unblocking Store Error X800704CF on WIndows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/unlock-career-potential-the-power-of-facebook-engagement/"><u>Unlock Career Potential: The Power of Facebook Engagement</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-user-identities-navigating-sid-retrieval-in-windows-11/"><u>Unveiling User Identities: Navigating SID Retrieval in Windows 11</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-alchemy-on-a-pc-transforming-footage-into-youtube-gold-for-2024/"><u>Video Alchemy on a PC  Transforming Footage Into YouTube Gold for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
</ul></div>
