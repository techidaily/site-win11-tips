---
title: Correcting Absence in Task Manager's Startups
date: 2024-09-11T01:23:58.639Z
updated: 2024-09-12T01:23:58.639Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Absence in Task Manager's Startups
excerpt: This Article Describes Correcting Absence in Task Manager's Startups
keywords: TaskManagerBootError,StartupTaskAbsent,FixTaskStartupFail,RestartTaskManager,ResolveTaskMissing,CorrectTaskFailure,BootTaskManagement
thumbnail: https://thmb.techidaily.com/4813724d53b5cad6b133b133522844cf1838d9743eb384dd583504939bc1aed2.jpg
---

## Correcting Absence in Task Manager's Startups

 While using the Windows Task Manager, you may suddenly come across an error message that reads, “There are no startup items to display in Task Manager.” It's a confusing error message, but don't fret; it's very easy to fix.

 Let’s check out the best ways to fix Task Manager's "no startup items" error.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



## 1\. Restart File Explorer

 Restarting File Explorer is one of the easiest ways to resolve this issue. The best way to do this is to restart your Windows PC completely.

 If that doesn’t resolve the problem, or you'd rather not restart your PC, you can restart File Explorer through these steps:

1. Press**Win + X** to open the Quick Access menu.
2. Select**Task Manager** from the options.
3. Right-click on the**Windows Explorer** option and then select**Restart** .

![Restarting the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Restarting-the-Windows-File-Explorer.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<span id="1983584">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983584.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983584">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983584.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983584%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983584/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Create a New Startup Folder

 In some cases, you’d run into the issue at hand if the startup folder is corrupted. So, the best way to resolve the problem is to create a new startup folder.

Now, here are the steps for creating a new startup folder on Windows:

1. Press**Win + E** to open File Explorer.
2. Copy-paste the command into the File Explorer address bar and press**Enter** :

`C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\`

From there, follow these steps:

1. Locate and delete the**Startup folder** .
2. Create a new startup folder by right-clicking on a blank space and selecting**New > Folder** .
3. Name the folder as**Startup** and press**Enter** .

![Selecting the Startup folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/selecting-the-startup-folder.jpg)

Finally, restart your device to save these changes.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Perform a Check Disk Scan

![An illustration of a lens scanning digital devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-a-lens-scanning-digital-devices.jpg)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 There’s a possibility that the issue at hand might be caused by system issues. In such instances, scanning and repairing your device’s hard drive could help.

 Here’s how you can resolve the problem using a Check Disk (CHKDSK) scan:

1. Type**Command Prompt** in the Start menu search bar.
2. Right-click on the**Best match** result and select**Run as administrator** .
3. Type the following command and then press**Enter** to scan and repair your hard drive:

`chkdsk C: /f`

 If your Windows operating system (OS) is installed on a different drive, then replace**C:** in the command with the letter of the relevant drive.

Finally, restart your device when the scan is complete.

## 4\. Scan and Repair Windows Using the DISM and SFC Tools

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 If a normal disk scan doesn’t help, then you’d need to scan and repair your hard drive using advanced tools such as DISM and SFC. As we covered in our guide on[how to repair corrupted files with built-in Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/) , DISM and SFC are handy services that can help repair Windows errors.

Let’s start by checking out how you can run the DISM tool:

1. Press**Ctrl + Shift + Esc** to open the Task Manager.
2. Click**File** in the top-left corner and select**Run new task** .
3. Type**CMD** and then check the**Create this task with administrative privileges** box.
4. Press**OK** to run the Command Prompt.
5. Type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /ScanHealth`

 Wait for the process to complete. From there, type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /RestoreHealth`

Finally, restart your device once the DISM scan is complete.

Now, you can run the SFC tool through these steps:

1. Open the**Command Prompt** by following the previous steps.
2. Type the following command and press**Enter** to run the scan:

`sfc /scannow`

Wait for the scan to complete and then restart your device.

## 5\. Run the System Maintenance Troubleshooter

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Still struggling to resolve the issue? If so, you might be experiencing a system maintenance problem. In this case, you could tackle the error by running the System Maintenance troubleshooter.

Here are the steps you need to follow:

1. Type**Perform recommended maintenance tasks automatically** in the Start menu search bar and press**Enter** .
2. Click the**Next** button and then follow the on-screen instructions.

![Running the System Maintenance Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Running-the-System-Maintenance-Troubleshooter-on-Windows.jpg)

Wait for the process to complete and then restart your PC.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 6\. Temporarily Disable the Windows Defender Firewall

 In some instances, temporarily disabling the Windows Defender Firewall could tackle the problem. However, don’t forget to re-enable the tool later.

Now, here are the steps for disabling the Windows Defender Firewall:

1. Type**Control Panel** in the Start menu search bar and select the**Best match** .
2. Click the**View by** drop-down menu and then select**Large icons** .
3. Select**Windows Defender Firewall** from the options.
4. Click the**Turn Windows Defender Firewall on and off** option.

![Selecting the Turn Defender Firewall on or off option on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Selecting-the-Turn-Defender-Firewall-on-or-off-option-on-Windows.jpg)





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 Locate the**Domain** ,**Private** , and**Public network settings** and then check the**Turn off Windows Defender Firewall** boxes next to them. Finally, press**OK** and then restart your computer.

![Turning off the Defender Firewall on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Turning-off-the-Defender-Firewall-on-Windows.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 7\. Use a System Restore Point

 Using a system restore point can help you tackle the issue at hand. However, this approach will only help if you’ve already learned[how to create a system restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and made one.

 During the restoration process, the system restore tool will revert your PC to a previous state. As such, this tool will help only if the Task Manager error only started appearing recently.

 Here’s how you can tackle the issue at hand using a restore point:

1. Type "Create a restore point" in the Start menu search bar and select the**Best match** .
2. Click the**System Protection** tab and then select**System Restore** from the options.
3. Press**Next** to continue.
4. Select**Show more restore points** and then pick a restore point.
5. Click**Next** and then click**Finish** to finalize the process.

![Using a Restore Point on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Using-a-Restore-Point-on-Windows.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 8\. Update Your Device

 In some instances, updating your Windows device might be the best solution. Ideally,[you should always update Windows to the latest version](https://www.makeuseof.com/windows-update-new-version-releases-reasons/) , but if you've put it off for a while, try updating your PC.

Here are the steps for updating Windows:

1. Type**Settings** in the Start menu search bar and select the**Best match** .
2. Select**Update & Security** from the options.
3. Select the**Windows Update** option on the left.
4. Click the**Check for updates** button on the right and then follow the on-screen steps.

![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

## You’ve Successfully Resolved Your Task Manager Issues

 The Task Manager is a reliable tool that helps you close slow programs and improve your PC’s performance. However, this tool also often runs into various problems. If it's experiencing issues with startup programs, you can easily resolve the error using any of the solutions in this article.

 If the issue persists, then maybe it’s time to start exploring some Task Manager alternatives.


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
<li><a href="https://extra-resources.techidaily.com/new-a-deep-examination-of-androids-photo-editing-tool-lightroom/"><u>[New] A Deep Examination of Android's Photo Editing Tool, Lightroom</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-embracing-precision-with-iphone-xs-optical-mastery-for-2024/"><u>[New] Embracing Precision with iPhone X's Optical Mastery for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-making-life-easier-watching-fb-videos-on-your-tv/"><u>[Updated] 2024 Approved Making Life Easier Watching FB Videos on Your TV</u></a></li>
<li><a href="https://extra-information.techidaily.com/analyzing-the-updated-sony-s6500-blu-ray-player/"><u>Analyzing the Updated Sony S6500 Blu-Ray Player</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/conquer-ai-responses-top-tips-for-writing-effective-chatbot-prompts/"><u>Conquer AI Responses: Top Tips For Writing Effective Chatbot Prompts</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-the-pathway-to-windowsstore-folder/"><u>Decoding the Pathway to WindowsStore Folder</u></a></li>
<li><a href="https://win11-tips.techidaily.com/diminish-windows-aural-amplification-feature/"><u>Diminish Windows Aural Amplification Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eradicating-the-sinister-windows-c0000022-flaw/"><u>Eradicating the Sinister Windows C0000022 Flaw</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-techniques-for-updating-windows-security-pin/"><u>Essential Techniques for Updating Windows Security PIN</u></a></li>
<li><a href="https://win11-tips.techidaily.com/essential-tips-for-reducing-disk-storage-usage-on-windows/"><u>Essential Tips for Reducing Disk Storage Usage on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-strategies-for-managing-file-names-in-win-os-max-156/"><u>Expert Strategies for Managing File Names in Win OS (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-malwarebytes-service-connection-failures-on-windows-11-os/"><u>Fixing Malwarebytes' Service Connection Failures on Windows 11 OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-updates-dealing-with-errors-0xc1900101-and-0x30017/"><u>Fixing Updates: Dealing with Errors 0xC1900101 and 0X30017</u></a></li>
<li><a href="https://win11-tips.techidaily.com/gauging-the-impact-do-windows-11-widgets-boost-productivity/"><u>Gauging the Impact: Do Windows 11 Widgets Boost Productivity?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/get-your-team-talking-in-rainbow-six-siege-again-voice-chat-solutions-updated/"><u>Get Your Team Talking in Rainbow Six Siege Again! Voice Chat Solutions Updated</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-rectify-microsoft-store-error-0x80073cf3-in-windows-11/"><u>Guide to Rectify Microsoft Store Error 0X80073cf3 in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guiding-you-through-windows-11-emulation-on-vmware-17/"><u>Guiding You Through Windows 11 Emulation on VMWare 17</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-the-operation-failed-0x0000011b-error-on-windows-10-and-11/"><u>How to Fix the Operation Failed 0X0000011B Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-prioritize-calculator-visibility-in-windows/"><u>How to Prioritize Calculator Visibility in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-x-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone X To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-windows-manages-reserved-memory-resources/"><u>How Windows Manages Reserved Memory Resources</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Realme GT Neo 5? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/inside-look-windows-command-center/"><u>Inside Look: Windows' Command Center</u></a></li>
<li><a href="https://win11-tips.techidaily.com/integrating-network-speed-into-system-ui/"><u>Integrating Network Speed Into System UI</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/mac-users-alert-how-to-securely-add-your-domain-to-googles-safe-list-using-mail-on-macos/"><u>Mac Users Alert! How to Securely Add Your Domain to Google’s Safe List Using Mail on macOS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/masterful-concealment-of-wireless-networks-windows-style/"><u>Masterful Concealment of Wireless Networks, Windows Style</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-fixing-java-install-glitches/"><u>Mastering the Art of Fixing Java Install Glitches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mending-windows-11s-frozen-search-within-the-user-interface/"><u>Mending Windows 11'S Frozen Search Within the User Interface</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-the-in-place-upgrades-with-ease-in-windows-11/"><u>Navigate the In-Place Upgrades with Ease in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-through-windows-active-sessions/"><u>Navigate Through Windows’ Active Sessions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/redefining-portability-and-efficiency-the-impact-of-m1-chip-on-apples-latest-13-macbook-pro-2ebyte-2020-comprehensive-review/"><u>Redefining Portability and Efficiency: The Impact of M1 Chip on Apple's Latest 13 MacBook Pro (2Ebyte, 2020) - Comprehensive Review</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reigniting-screen-brilliance-overcoming-windows-11-limits/"><u>Reigniting Screen Brilliance: Overcoming Windows 11 Limits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resurrect-your-device-reviving-dead-usb-connections-win/"><u>Resurrect Your Device: Reviving Dead USB Connections Win</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revealing-hidden-depths-the-guide-to-activating-windows-private-self-view/"><u>Revealing Hidden Depths: The Guide to Activating Windows' Private Self-View</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-error-resolution-in-windows-11s-setup-process/"><u>Simplifying Error Resolution in Windows 11'S Setup Process</u></a></li>
<li><a href="https://win11-tips.techidaily.com/slowing-down-lifes-exuberance-in-your-windows-environment/"><u>Slowing Down Life's Exuberance in Your Windows Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-install-microsofts-pc-manager/"><u>Steps to Install Microsoft's PC Manager</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-storage-merging-files-on-windows-11/"><u>Streamlining Storage: Merging Files on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-indispensable-value-of-bsod-in-diagnostic-processes/"><u>The Indispensable Value of BSoD in Diagnostic Processes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/transforming-oculus-q2-into-windows-compatible-vr/"><u>Transforming Oculus Q2 Into Windows-Compatible VR</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-how-to-fix-a-non-functional-mic-on-skype-for-windows-10/"><u>Troubleshooting Guide: How to Fix a Non-Functional Mic on Skype for Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turn-off-microsofts-intelligent-assistance/"><u>Turn Off Microsoft's Intelligent Assistance</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-correcting-windows-roblox-403/"><u>Understanding & Correcting Windows Roblox 403</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlocking-creativity-top-20-vlogger-themes/"><u>Unlocking Creativity Top 20 Vlogger Themes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unraveling-the-mystery-fixing-win11-camera-issue-with-error-a00f4289/"><u>Unraveling the Mystery: Fixing Win11 Camera Issue with Error A00F4289</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visualizing-resources-efficiently-taskbar-display-reimagined/"><u>Visualizing Resources Efficiently: Taskbar Display Reimagined</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10-repairing-directionally-inconsistent-headphone-output/"><u>Win10: Repairing Directionally Inconsistent Headphone Output</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win1011s-network-woe-how-to-resolve-error-code-0x800704b3/"><u>Win10/11's Network Woe: How to Resolve Error Code: 0X800704B3</u></a></li>
</ul></div>




