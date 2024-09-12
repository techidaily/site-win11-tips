---
title: "Win 11/10: Overcoming Install Failure Due to Privilege Lacking"
date: 2024-09-11T01:24:55.636Z
updated: 2024-09-12T01:24:55.636Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11/10: Overcoming Install Failure Due to Privilege Lacking"
excerpt: "This Article Describes Win 11/10: Overcoming Install Failure Due to Privilege Lacking"
keywords: Win Win11,Fix Install Fail,Privileges Deficit,Overcome Win Errors,Win10 Troubleshoot,Bypass Install Loss,Elevate User Permissions
thumbnail: https://thmb.techidaily.com/f00def1c04cb418f21da5c60f199b078da943127e970aa7acf9eb30479f71c91.jpg
---

## Win 11/10: Overcoming Install Failure Due to Privilege Lacking

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select **Properties**.

 If you can see an **Unblock** option on the **General** tab, deselect the checkbox and select **Apply**.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click **Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about [taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a **Take Ownership** option to the context menu with Winaero Tweaker.

![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135475/26400" target="_top" id="2135475">
  <img src="//a.impactradius-go.com/display-ad/26400-2135475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135475/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/), an app you can access by pressing the **Windows** logo + **R** hotkey and inputting a **service.msc** command.
2. Right-click Windows Installer and select **Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its **Restart** context menu option.

 Alternatively, you can double-click the **Windows Installer** service to view its properties window and restart it from there. Click **Start** if the service is already stopped, or, select **Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)





<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in its sidebar.
2. Then double-click **Windows Settings** \> **Security Settings** \> **Local Policies** \> **Security Options** to access UAC policy settings.
3. Double-click **User Account Control: Admin Approval Mode** to bring up that policy setting window.  
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select **Disabled** to turn off that policy setting.




<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




5. Click **Apply** \> **OK** to save the policy setting you’ve selected.  
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)





<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123479/16836" target="_top" id="2123479">
  <img src="//a.impactradius-go.com/display-ad/16836-2123479" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123479/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-best-mac-capture-software-excluding-traditional-bandicam/"><u>[New] 2024 Approved Best Mac Capture Software Excluding Traditional Bandicam</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-advanced-methods-for-recording-in-adobe-presenter-for-2024/"><u>[New] Advanced Methods for Recording in Adobe Presenter for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-learn-to-record-mac-display-like-a-pro-for-2024/"><u>[New] Learn to Record MAC Display Like a Pro for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-accelerate-engagement-through-vimeo-linking/"><u>2024 Approved Accelerate Engagement Through Vimeo Linking</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-the-full-scoop-on-camstudio-screen-recorders/"><u>2024 Approved The Full Scoop on CamStudio Screen Recorders</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-your-channel-strategies-for-skyrocketing-view-counts/"><u>Boosting Your Channel Strategies for Skyrocketing View Counts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-line-mastery-navigating-through-windows-error-messages-with-precision-and-skill/"><u>Command Line Mastery: Navigating Through Windows Error Messages with Precision and Skill</u></a></li>
<li><a href="https://win11-tips.techidaily.com/counteracting-frozen-display-windows-steam-guide/"><u>Counteracting Frozen Display: Windows Steam Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/craft-a-tailored-clutter-free-windows-11-environment/"><u>Craft a Tailored, Clutter-Free Windows 11 Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cut-to-the-chase-speed-up-workflow-with-grouped-directories-in-win11plus11/"><u>Cut to the Chase: Speed up Workflow with Grouped Directories in Win11+11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deal-makers-delight-windows-10-612-lifetime-bf-discount/"><u>Deal-Makers' Delight: Windows 10, $6.12 Lifetime BF Discount</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-oneplus-nord-3-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on OnePlus Nord 3 5G Devices | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-repairing-isdonedll-errors-in-windows-11-os/"><u>Guide to Repairing ISDone.dll Errors in Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-proficiently-utilize-the-windows-print-device-manager/"><u>How To Proficiently Utilize the Windows Print Device Manager</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-zte-blade-a73-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any ZTE Blade A73 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-vivo-y78plus-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Vivo Y78+ Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11-tips.techidaily.com/keep-taskmanager-front-and-center-in-windows/"><u>Keep TaskManager Front and Center in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/managing-file-capacity-with-win-1011-tips/"><u>Managing File Capacity with Win 10/11 Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-chatgpt-windows-setup-guide/"><u>Mastering ChatGPT: Windows Setup Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/minimizing-wasted-cpu-by-ntoskrnlexe-processes/"><u>Minimizing Wasted Cpu by Ntoskrnl.exe Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-windows-11-easy-wi-fi-deletion-guide/"><u>Optimize Windows 11: Easy Wi-Fi Deletion Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reducing-delays-increasing-frame-rate-win-edition-guide/"><u>Reducing Delays, Increasing Frame Rate: Win Edition Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/regaining-access-to-off-screen-panes-win11-guide/"><u>Regaining Access to Off-Screen Panes: Win11 Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/removing-barriers-steam-and-windows-11-file-privilege-issue/"><u>Removing Barriers: Steam & Windows 11 File Privilege Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/seamless-sites-shutdown-top-strategies-for-windows-browsing-woes/"><u>Seamless Sites Shutdown: Top Strategies for Windows Browsing Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/shorten-system-awakening-edit-boot-sequence-timing-windows-11/"><u>Shorten System Awakening: Edit Boot Sequence Timing Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/sneaking-preview-into-unreleased-windows-capabilities-with-vivetool/"><u>Sneaking Preview Into Unreleased Windows Capabilities with ViVeTool</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-diagnostics-error-on-pc/"><u>Solutions for Fixing 'Diagnostics Error' On PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-the-disappearance-issue-rockalldlldll-errors/"><u>Solving the Disappearance Issue: Rockalldll.dll Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-shared-printer-setup-on-desktops/"><u>Streamlining Shared Printer Setup on Desktops</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-overcome-windows-intruder-bsod-crisis/"><u>Techniques to Overcome Windows' Intruder BSOD Crisis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-isdonedll-failures-on-windows-1011/"><u>Troubleshooting ISDone.dll Failures on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-the-dynamics-of-windows-updates/"><u>Understanding the Dynamics of Windows Updates</u></a></li>
<li><a href="https://fox-http.techidaily.com/unleash-potential-the-best-10-motivational-movies/"><u>Unleash Potential The Best 10 Motivational Movies</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-secret-behind-x80070091-error-in-windows-environments/"><u>Unveiling the Secret Behind X80070091 Error in Windows Environments</u></a></li>
<li><a href="https://buynow-info.techidaily.com/webex-pros-vs-cons-is-it-the-right-tool-for-your-virtual-team/"><u>WebEx Pros Vs. Cons - Is It the Right Tool for Your Virtual Team?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win1011-reactivating-unresponsive-adobe-photoshop/"><u>Win10/11: Reactivating Unresponsive Adobe Photoshop</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11-woes-re-opening-chrome-made-simple/"><u>Windows 11 Woes: Re-Opening Chrome Made Simple</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    