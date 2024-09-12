---
title: "Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
date: 2024-09-11T01:25:03.169Z
updated: 2024-09-12T01:25:03.169Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
excerpt: "This Article Describes Windows 11 Guide: Changing the Number of Failed Logins Before Resetting"
keywords: Windows 11 Login Failure,Change Login Attempts,Reset User Password,11 PC Security Guide,Failed Login Fix,Lockout Prevention Tricks,Update Passwords Steps
thumbnail: https://thmb.techidaily.com/c7779ebd6615899057fd1d41459b53b981bc532c7ceba807afb11ae201e1d4e5.jpg
---

## Windows 11 Guide: Changing the Number of Failed Logins Before Resetting

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>







<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  




<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.




<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.




<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->





 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.





<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-streamlining-monetization-strategies-on-youtube/"><u>[New] 2024 Approved Streamlining Monetization Strategies on YouTube</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-iphones-quickest-way-to-record-time-lapse-photos/"><u>[Updated] IPhone's Quickest Way to Record Time-Lapse Photos</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-vivo-y17s-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Vivo Y17s to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-practices-for-identifying-premier-free-srt-translation-services/"><u>Best Practices for Identifying Premier Free SRT Translation Services</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-speed-keyboard-mastery-through-powertoys/"><u>Elevate Speed: Keyboard Mastery Through PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminate-intrusive-windows-tracking-systems/"><u>Eliminate Intrusive Windows Tracking Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/explore-the-enhanced-functionality-of-mozilla-thunderbird-update-52/"><u>Explore the Enhanced Functionality of Mozilla Thunderbird Update 52</u></a></li>
<li><a href="https://win11-tips.techidaily.com/fixing-windows-reboot-loop-into-bios-setup/"><u>Fixing Windows Reboot Loop Into BIOS Setup</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-lava-blaze-curve-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-reactivate-a-non-operational-win11-code/"><u>How to Reactivate a Non-Operational Win11 Code</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ipad-pro-vs-macbook-pro-showdown-discover-what-sets-them-apart/"><u>IPad Pro vs MacBook Pro Showdown: Discover What Sets Them Apart</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-vocal-to-text-conversion-with-windows-whisper/"><u>Master the Art of Vocal to Text Conversion with Windows Whisper</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-steam-file-sync-in-windows-environment/"><u>Mastering Steam File Sync in Windows Environment</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/maxsuns-latest-creation-a-unique-reverse-slot-design-for-mini-itx-motherboards/"><u>Maxsun's Latest Creation: A Unique Reverse Slot Design for Mini-ITX Motherboards</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigate-the-world-of-computers-with-toms-hardware-mastery/"><u>Navigate the World of Computers with Tom's Hardware Mastery</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-top-5-best-mp4-video-editors-totally-free-for-2024/"><u>New Top 5 Best MP4 Video Editors Totally Free for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-issues-with-windows-character-map-functionality/"><u>Overcoming Issues with Windows Character Map Functionality</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-terminal-background-image/"><u>Personalizing Terminal Background Image</u></a></li>
<li><a href="https://win11-tips.techidaily.com/propel-productivity-top-7-ways-to-use-windows-11-smartly/"><u>Propel Productivity: Top 7 Ways to Use Windows 11 Smartly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/rectifying-unable-to-open-sharing-problems-with-geforce/"><u>Rectifying Unable to Open Sharing Problems with GeForce</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-the-windows-net-framework-obstacle-error/"><u>Remedying the Windows .NET Framework Obstacle Error</u></a></li>
<li><a href="https://win11-tips.techidaily.com/resolving-lack-of-hypervisor-in-windows-sandbox-environment/"><u>Resolving Lack of Hypervisor in Windows Sandbox Environment</u></a></li>
<li><a href="https://win11-tips.techidaily.com/simplifying-file-selection-harnessing-checkboxes-in-windows-11/"><u>Simplifying File Selection: Harnessing Checkboxes in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-the-unexpected-token-call-on-win10-devices/"><u>Solutions for the “Unexpected Token Call” On Win10 Devices</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solve-your-microsoft-store-sign-in-problems-today/"><u>Solve Your Microsoft Store Sign-In Problems Today</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-10-hang-issues-a-comprehensive-guide-to-get-it-running-smoothly-again/"><u>Solving Windows 10 Hang Issues: A Comprehensive Guide to Get It Running Smoothly Again</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-remove-hyber-v-from-windows-11-pro/"><u>Steps to Remove Hyber-V From Windows 11 Pro</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-end-of-cortana-dawn-of-four-alternatives-in-windows/"><u>The End of Cortana, Dawn of Four Alternatives in Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-shutting-down-a-stale-linkedin-account/"><u>The Ultimate Guide to Shutting Down a Stale LinkedIn Account</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-c0000022-crash-in-windows-os/"><u>Troubleshooting C0000022 Crash in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-windows-office-glitch-resetting-errors/"><u>Troubleshooting Windows Office Glitch: Resetting Errors</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlocking-fbm-potential-top-fixes-for-pc-users/"><u>Unlocking FBM Potential: Top Fixes for PC Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-motion-tracking-software-for-text-top-picks-for-2024/"><u>Updated Motion Tracking Software for Text Top Picks for 2024</u></a></li>
</ul></div>







<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    