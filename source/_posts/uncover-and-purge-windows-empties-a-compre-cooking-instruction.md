---
title: "Uncover & Purge Window's Empties: A Compre Cooking Instruction"
date: 2024-09-11T01:25:08.524Z
updated: 2024-09-12T01:25:08.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Uncover & Purge Window's Empties: A Compre Cooking Instruction"
excerpt: "This Article Describes Uncover & Purge Window's Empties: A Compre Cooking Instruction"
keywords: Cooking Guide,Purging Kitchen Trash,Unwanted Food Removal,Cleanup Window Emptiness,Organize Kitchen Waste,Efficient Cooking Space,Eliminate Kitchen Clutter
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## Uncover & Purge Window's Empties: A Compre Cooking Instruction

 Despite not consuming any disk space, empty folders can still impede our file management efforts. For this reason, clearing out unnecessary clutter is essential to keep your drives and folders organized. The problem is, having hundreds of folders on various drives makes manually finding and deleting empty ones nearly impossible. This raises the question: is there an efficient way to delete empty folders from your computer?

 In this article, we'll show you how to remove empty folders from your computer with PowerShell, a Windows built-in utility, and third-party software.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## Setting the Foundation to Delete Empty Folders in Windows

 By default, not all users can delete every empty folder on a device; some can only be accessed, edited, and deleted by administrators.

 Since we'll be deleting all empty folders hiding on your device, logging in with an administrator account is best to avoid encountering errors later. Need help? Check out our[g](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/#how-to-enable-or-disable-the-windows-administrator-account) uide that explains[the Windows administrator account](http://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) in detail, including how to enable (or disable) it.

 Secondly, the methods we'll cover can help delete empty folders quickly, but only those are visible to us, not hidden. Therefore, if you want to delete all empty folders without leaving any hidden ones behind, you should first unhide all hidden folders. Follow these steps to do so:

1. Open Windows File Explorer.
2. In Windows 11, click on**three horizontal dots** at the right end of the File Explorer menu and then click**Options** .  
![Going to the Options Menu by Clicking on the Three Horizontal Dots in the Right End of the File Explorer Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/1-going-to-the-options-menu-by-clicking-on-the-three-horizontal-dots-in-the-right-end-of-the-file-explorer-menu.jpg)  
 When using Windows 10, select the**File** menu and click**Options** .
3. Go to the**View** tab in the**Folder** **Options** window and check the box for**Show hidden files, folders, and drives** .  
![Checking the Circle for Show Hidden Files Folders and Drives in Folder Options Window of File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/2-checking-the-circle-for-show-hidden-files-folders-and-drives-in-folder-options-window-of-file-explorer.jpg)

 Once you've signed in as an administrator and revealed the hidden folders, it's time to delete the empty folders.





<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Find and Delete Empty Folders Using Windows PowerShell

 If you only want to declutter a few folders, such as the ones containing your college data, there is no need to use third-party software. Interestingly, the Windows PowerShell utility can help you wipe out empty folders with just one command. Here's how:

1. Copy the path to the folder or drive you intend to scan for empty subfolders.
2. Type**"Windows PowerShell"** into Windows Search, right-click on the**Windows PowerShell** app, then click**Run as administrator** .  
![Running the Windows PowerShell App as Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/3-running-the-windows-powershell-app-as-administrator.jpg)  
 Find out[how to open the Command Prompt and PowerShell utility in other ways](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .




<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




3. Enter the following command in the PowerShell application after adding the path to the target folder and hit**Enter** :  
`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | select FullName | Out-GridView`  
![Locating Empty Folders by Running a Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/4-locating-empty-folders-by-running-a-command-in-windows-powershell-app.jpg)
4. PowerShell will display all empty subfolders within that folder in a few seconds. Be patient if it takes a while.  
![Successfully Locating All Empty Folders and Subfolders Using Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/5-successfully-locating-all-empty-folders-and-subfolders-using-windows-powershell-app.jpg)
5. Look over the list of empty folders PowerShell displays and determine whether they are safe to delete. When you are sure you want to delete these empty folders, enter the following command after adding the target folder path at its respective location:  




<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




`(gci "folderpath" -r | ? {$_.PSIsContainer -eq $True}) | ?{$_.GetFileSystemInfos().Count -eq 0} | remove-item`  
![Deleting the Empty Folders by Running the Command in Windows PowerShell App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/6-deleting-the-empty-folders-by-running-the-command-in-windows-powershell-app.jpg)
6. Hit**Enter** and the empty subfolders will be automatically deleted.




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





 There's a catch, though. If you delete the empty subfolder in a folder that previously contained only that empty subfolder, the main folder also becomes empty. If you delete that empty folder by executing the command a second time, perhaps another parent folder in the tree may also become empty.

 To prevent this issue, run the above command three to four times until the command that finds the empty folders does not reveal any remaining empty subfolders in PowerShell.

 Similarly, you can use the above method to find empty folders on crowded drives and delete them. However, this method is limited because it doesn't allow you to delete some empty folders, leaving others intact selectively.

 Therefore, if you want more control over finding and deleting empty folders on your Windows device, you will have to use third-party tools. In the next section, we will demonstrate how you can do it.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Find and Delete Empty Folders Using Third-Party Software

 While the method discussed above will work in most cases, it requires more manual input and gives less control over deleting specific empty folders. To keep things more straightforward and less time-consuming, you can use third-party software to clean your device.

 You can use any software that lets you find and delete empty folders, but we recommend 4dots' Empty Folder Cleaner for its ease of use. Let's take a look at how it aids in finding and deleting empty folders on Windows:

1. Visit[4dots' official website](https://www.4dots-software.com/emptyfoldercleaner/#google%5Fvignette) to download Empty Folder Cleaner.
2. Install the software on your device.
3. Let Windows install any .NET Framework it prompts you to install.
4. Once the application has been installed, run it.
5. Check the boxes for all drives or folders you want to scan (except the one where your operating system is installed).  
![Checking the Boxes for Drives or Folders to Scan in the Empty Folder Cleaner Software on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/8-checking-the-boxes-for-drives-or-folders-to-scan-in-the-empty-folder-cleaner-software-on-windows.jpg)

1. When you have selected the drives and folders you want to scan for empty folders, click on the**Scan** button in the top-left corner.  
![Viewing the Empty Files and Folders Found After Scanning the Selected Folders in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/9-viewing-the-empty-files-and-folders-found-after-scanning-the-selected-folders-in-empty-folder-cleaner-software.jpg)
2. Depending on how much data you're scanning, the app may take a while. Wait until the scan is complete.
3. Upon completion of the scan, you will see a list of empty folders that have been found on your device. You can view them either as a list or as a tree.
4. Check the boxes for empty folders you wish to delete or select all empty folders by clicking**Select All** .  
![Checking the Boxes for All Empty Files and Folders by Clicking on Select All Button in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/10-checking-the-boxes-for-all-empty-files-and-folders-by-clicking-on-select-all-button-in-empty-folder-cleaner-software.jpg)
5. In the top-left corner, right next to**Scan** , click**Delete Empty Folders** .




<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




6. Once the warning pop-up appears, select**Yes** to delete all empty folders successfully.  
![Deleting All Empty Files and Folders by Clicking on the Yes Button in the Warning Pop-up in Empty Folder Cleaner Software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/11-deleting-all-empty-files-and-folders-by-clicking-on-the-yes-button-in-the-warning-pop-up-in-empty-folder-cleaner-software.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 There is no doubt that Empty Folder Cleaner makes deleting empty folders on Windows devices incredibly simple. Despite its ease of use, it remains a third-party software. Even though it has a good reputation, you should still be aware of security risks when using it, especially when allowing it to scan confidential documents.

## Don't Let Empty Folders Clog Up Your Device's Organization

 Even though empty folders don't strain our devices, removing them is a great way to keep your device organized. Hopefully, the instructions in this article will help clear your device of empty folders and unnecessary clutter.

 Besides empty folders you deleted, many other files and folders unnecessarily burden your device, including files in Windows Temp, Recycle Bin, and LiveKernelReports. So, watch out for this extra burden and lower it regularly to keep your machine running smoothly.


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
<li><a href="https://extra-lessons.techidaily.com/new-9plus-ways-to-experience-cricket-live-streaming-at-its-best/"><u>[New] 9+ Ways to Experience Cricket Live Streaming at Its Best</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-leading-stock-pictures-tales-and-internet-fame-for-2024/"><u>[New] Leading Stock Pictures' Tales and Internet Fame for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-average-revenue-what-every-view-contributes-to-creators/"><u>[Updated] 2024 Approved Average Revenue What Every View Contributes to Creators</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-closing-your-vlog-right-top-6-free-youtube-outro-tools/"><u>[Updated] Closing Your Vlog Right Top 6 Free YouTube Outro Tools!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/assessing-the-battery-life-and-durability-of-jabras-earbuds/"><u>Assessing the Battery Life and Durability of Jabra's Earbuds</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/camera-control-tips-for-unshakable-images-for-2024/"><u>Camera Control Tips for Unshakable Images for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/conquered-creativity-unleashing-photo-potential-on-snapchat/"><u>Conquered Creativity Unleashing Photo Potential on Snapchat</u></a></li>
<li><a href="https://techtrends.techidaily.com/delving-into-the-core-contrasts-of-apples-mac-and-microsofts-pc-find-out-how-they-differ/"><u>Delving Into the Core Contrasts of Apple's Mac and Microsoft's PC – Find Out How They Differ!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enriched-desktop-features-real-time-performance-indicators/"><u>Enriched Desktop Features: Real-Time Performance Indicators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-actions-to-resolve-windowed-games-issue/"><u>Essential Actions to Resolve Windowed Games Issue</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-components-and-specifications-choosing-the-right-gaming-pc/"><u>Essential Components and Specifications: Choosing the Right Gaming PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-reducing-disk-storage-usage-on-windows/"><u>Essential Tips for Reducing Disk Storage Usage on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-enhanced-control-with-the-sabrent-traveling-mouse-precision-meets-convenient-cables/"><u>Experience Enhanced Control with the Sabrent Traveling Mouse - Precision Meets Convenient Cables</u></a></li>
<li><a href="https://win11-tips.techidaily.com/explore-why-keeping-windows-11s-alerts-is-important/"><u>Explore Why Keeping Windows 11'S Alerts Is Important</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-malwarebytes-service-connection-failures-on-windows-11-os/"><u>Fixing Malwarebytes' Service Connection Failures on Windows 11 OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-zte-nubia-flip-5g-frp-by-drfone-android/"><u>Full Guide to Bypass ZTE Nubia Flip 5G FRP</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/es-in-a-gigabyte-10-hilarious-video-concepts-to-share-online/"><u>Giggles in a Gigabyte 10 Hilarious Video Concepts to Share Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-reviving-non-compatible-controllers-in-windows/"><u>Guide to Reviving Non-Compatible Controllers in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-windows-11-emulation-on-vmware-17/"><u>Guiding You Through Windows 11 Emulation on VMWare 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-operation-failed-0x0000011b-error-on-windows-10-and-11/"><u>How to Fix the Operation Failed 0X0000011B Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-problem-with-this-windows-installer-package-error-on-windows-10-and-11/"><u>How to Fix the Problem With This Windows Installer Package Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prioritize-calculator-visibility-in-windows/"><u>How to Prioritize Calculator Visibility in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-windows-manages-reserved-memory-resources/"><u>How Windows Manages Reserved Memory Resources</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-increase-photo-resolution-unaltered-image/"><u>In 2024, Increase Photo Resolution - Unaltered Image</u></a></li>
<li><a href="https://extra-hints.techidaily.com/introducing-the-ultimate-data-on-the-go-solution-the-368tb-nvme-ssd-wd-ultrastar-transporter-with-impressive-features/"><u>Introducing the Ultimate Data On-the-Go Solution: The 368TB NVMe SSD WD Ultrastar Transporter with Impressive Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-guide-tackling-windows-steam-playback-problems/"><u>Quick Guide: Tackling Windows Steam Playback Problems</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-hidden-depths-the-guide-to-activating-windows-private-self-view/"><u>Revealing Hidden Depths: The Guide to Activating Windows' Private Self-View</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionize-your-marketing-strategy-with-cookiebot-solutions/"><u>Revolutionize Your Marketing Strategy with Cookiebot Solutions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-shopping-redefined-by-microsofts-ai-hub/"><u>Seamless Shopping Redefined by Microsoft’s AI Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/skyrocket-your-file-transfer-speed-on-microsoft-platforms/"><u>Skyrocket Your File Transfer Speed on Microsoft Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-access-to-non-local-files/"><u>Streamlining Access to Non-Local Files</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-win11-package-management-using-wingetui/"><u>Streamlining Win11 Package Management Using WingetUI</u></a></li>
<li><a href="https://win11-tips.techidaily.com/system-survival-kit-top-13-ways-to-resurrect-windows/"><u>System Survival Kit: Top 13 Ways to Resurrect Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-graphics-errors-a-comprehensive-d3d11-fix-in-windows-1110/"><u>Tackling Graphics Errors: A Comprehensive D3D11 Fix in Windows 11/10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-oculus-q2-into-windows-compatible-vr/"><u>Transforming Oculus Q2 Into Windows-Compatible VR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-microsofts-intelligent-assistance/"><u>Turn Off Microsoft's Intelligent Assistance</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-what-it-means-as-openais-top-executive-calls-for-better-control-over-artificial-intelligence/"><u>Understanding What It Means as OpenAI's Top Executive Calls for Better Control over Artificial Intelligence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-potential-in-windows-via-alomware-features/"><u>Unlock Potential in Windows via AlomWare Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualizing-resources-efficiently-taskbar-display-reimagined/"><u>Visualizing Resources Efficiently: Taskbar Display Reimagined</u></a></li>
<li><a href="https://facebook.techidaily.com/warning-signs-and-actions-minor-facebook-usage/"><u>Warning Signs and Actions: Minor Facebook Usage</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-screen-makeover-tailored-wallpapers-per-monitor/"><u>Windows 11 Screen Makeover: Tailored Wallpapers Per Monitor</u></a></li>
</ul></div>




