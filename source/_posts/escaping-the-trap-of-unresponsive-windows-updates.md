---
title: Escaping the Trap of Unresponsive Windows Updates
date: 2024-10-08T03:31:19.850Z
updated: 2024-10-09T01:57:10.669Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Escaping the Trap of Unresponsive Windows Updates
excerpt: This Article Describes Escaping the Trap of Unresponsive Windows Updates
keywords: Update Responsiveness,WU Non-Responsive,Windows Patch Issues,Updater Failure,Stable Windows Update,Quick Windows Fixes,Unblocking Updates
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## Escaping the Trap of Unresponsive Windows Updates

 Update errors are nothing new for Windows users. In some cases, the updates simply do not start, while in others, they start fine, but become stuck at some point.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Wait for the Process to Complete

 It may take longer for some Windows updates to install, so before you begin troubleshooting, ensure that the update is stuck and not in between operations.

 The best way to do this is by waiting for the process to complete on its own. You should give the update process at least 3-4 hours before proceeding with the troubleshooting methods if you can. Some users left their computers overnight for the updates to be installed.

 We understand that waiting this long might not be possible for everyone and if it does not suit you as well, go ahead with the methods below. It is also important to note that before proceeding with the methods in this guide that require you to access your system, you will need to break the update loop that is causing the issue. To do this, reboot your PC to perform the steps listed.

## 2\. Remove Any USB Peripherals and Restart Your PC

 Start by removing any USB peripherals that may be connected to your PC. When you have extra external devices connected, your PC thinks of it as a change in the default hardware settings, leading to issues like the one at hand.

 Once you have removed all peripherals, wait for a few minutes and see if it makes any difference. If not, you can try force restarting the PC. However, this method involves removing the battery from your laptop, so we recommend you only proceed if you have some experience doing so.

 Here is how you can force restart your PC:

1. Press and hold the power button of your PC to shut it down.
2. Once it shuts down, remove the power supply and battery.
3. Then, wait for a few minutes before inserting it back.
4. Now, boot your PC and see if the issue is resolved.

## 3\. Restart the Windows Update Service

 The Windows Update service handles the download, installation, and removal of updates on your system. If this service is disabled or not working as it is supposed to, you are likely to encounter issues while updating your operating system and its applications.

 If removing the external peripherals did not help, then you can try restarting the Windows Update service.

 Here is how you can make sure that the update service is running properly:

1. Press **Win** \+ **R** to open Run.
2. Type "services.msc" in Run and press **Enter**.
3. In the following window, look for the Windows Update service and right-click on it.
4. Choose **Properties** from the context menu.  
![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, click on the **Stop** button.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Stop button in Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/win10-windows-update-properties-stop.jpg)
6. Wait for a few seconds before hitting the **Start** button again.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Expand the dropdown for Startup type and choose **Automatic** from the list.  
![Startup type of service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-automatic-startup-type.jpg)
8. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Scan for Viruses

 Your operating system might also be infected with a virus or corruption error that is preventing you from installing the latest updates.

 To check if this is the case, try running a system scan using the security program you have installed on your PC. If you do not have a third-party security program, you can [run built-in troubleshooting utilities like SFC, DISM, and CHKDSK](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) via Command Prompt.

 However, if you are unable to use the basic Windows features and applications installed, then you must first [boot into Repair Mode](https://www.makeuseof.com/fix-windows-11-stuck-preparing-windows/). Once you are in the Repair Mode, head over to **Troubleshoot** \> **Advanced options**. Then, choose **Command Prompt** from the list of options and run the scans.

![Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-command-prompt.jpg)

 If these utilities find any issues, they will attempt to resolve them without requiring your input. After the scans, check if the issue is resolved.

## 5\. Run the Windows Update Troubleshooter

 Another troubleshooting method that has helped users fix the issue is running the Windows Update troubleshooter. This is a built-in utility that is specifically designed by Microsoft to fix issues regarding Windows updates.

 Here is how you can run it:

1. Press **Win** \+ **I** to open Windows Settings.
2. Choose **Troubleshoot** from the left pane and click on **Other troubleshooters** on the right side of the window.  
![other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/other-troubleshooters-1.jpg)
3. In the following window, look for Windows Update troubleshooter and click on the **Run** button associated with it.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Run button for Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-troubleshooter.jpg)
4. The troubleshooter will now begin scanning the system for potential errors. If it finds issues, it will recommend fixes. In that case, click on **Apply this fix**.

5. If not, click **Close the troubleshooter** and move to the next method below.

## 6\. Boot Into Safe Mode

 Safe Mode is a Windows mode that launches Windows with only the basic drivers and programs. This troubleshooting mode helps users determine if a background process is causing issues within the system.

 In this method, we will first boot into Safe Mode using the Repair Mode and then restart the PC normally. Hopefully, this will fix the problem at hand.

 Here is what you need to do:

1. Boot Windows and during the process, press the F11 key repeatedly till Windows displays the Advanced Startup screen.
2. Head over to navigate to **Troubleshoot** \> **Advanced options** \> **Startup settings**.  
![Startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings.jpg)
3. Click on the **Restart** button in the following window.  

![Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings-restart.jpg)
4. Hit the F5 key on the keyboard to proceed. This will launch the Safe Mode successfully.

5. In Safe Mode, restart your PC the normal way (**Start menu** \> **Sign out** \> **Restart**).  
![Restart Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-safe-mode-restart.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Upon reboot, the issue should no longer appear. You can now check if the updates are successfully installed. If not, you can try any one of [the different methods to update Windows manually](https://www.makeuseof.com/update-windows-manually/).

## Resume the Update Process on Windows 11

 We hope that at least one of the methods listed above was able to help you. Nevertheless, if you have come this far without finding a solution, you should consider performing a complete system reset since the issue is likely caused by a component that conventional troubleshooting methods cannot fix.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-revolutionize-video-files-with-instant-fb-to-mp4-and-hd-upgrade/"><u>[New] In 2024, Revolutionize Video Files with Instant FB to MP4 & HD Upgrade</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-the-essentials-of-youtube-gaming-livestreaming/"><u>[New] In 2024, The Essentials of YouTube Gaming Livestreaming</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-utilizing-snap-camera-for-interactive-online-gatherings/"><u>[New] Utilizing Snap Camera for Interactive Online Gatherings</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-how-to-perfectly-blend-audiotracks-in-slideshows/"><u>[Updated] 2024 Approved How to Perfectly Blend Audiotracks in Slideshows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-legality-check-taking-screencasts-of-youtube-videos-for-2024/"><u>[Updated] Legality Check Taking Screencasts of YouTube Videos for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-beginners-choice-syma-x5c-racing-copter-evaluation/"><u>Affordable Beginner's Choice: SYMA X5C Racing Copter Evaluation</u></a></li>
<li><a href="https://techtrends.techidaily.com/anticipated-apple-household-assistant-bot-projected-cost-and-launch-timeline-unveiled/"><u>Anticipated Apple Household Assistant Bot - Projected Cost & Launch Timeline Unveiled</u></a></li>
<li><a href="https://win11-tips.techidaily.com/conquering-the-challenge-the-ultimate-fix-for-xbox-game-passs-error-code-0x800700e9/"><u>Conquering the Challenge: The Ultimate Fix for Xbox Game Pass’s Error Code 0X800700E9</u></a></li>
<li><a href="https://win11-tips.techidaily.com/customizing-win1011-context-menu-integrate-disk-space-viewer/"><u>Customizing Win10/11 Context Menu: Integrate Disk Space Viewer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-photo-editing-experience-with-photoshop/"><u>Enhancing Photo Editing Experience with Photoshop</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-how-to-see-every-participant-in-google-meet/"><u>In 2024, How to See Every Participant in Google Meet?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-split-display-frustrations-in-windows/"><u>Overcoming Split Display Frustrations in WIndows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/prime-protection-top-rated-windows-encryption-programs-153-chars/"><u>Prime Protection: Top-Rated Windows Encryption Programs (153 Chars)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reactivating-stuck-grammarly-service-on-pcs/"><u>Reactivating Stuck Grammarly Service on PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-role-of-non-verbal-communication-in-interviewing/"><u>The Role of Non-Verbal Communication in Interviewing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-skyrims-x-script-on-pc/"><u>Troubleshooting Skyrim's X-Script on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-photo-gallery-functions-on-windows-pc/"><u>Unlocking Photo Gallery Functions on Windows PC</u></a></li>
</ul></div>

