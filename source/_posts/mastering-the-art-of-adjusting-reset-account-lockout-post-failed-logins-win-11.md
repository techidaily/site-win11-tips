---
title: Mastering the Art of Adjusting Reset Account Lockout Post Failed Logins, Win 11
date: 2024-10-15T00:30:37.070Z
updated: 2024-10-20T16:49:25.091Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Adjusting Reset Account Lockout Post Failed Logins, Win 11
excerpt: This Article Describes Mastering the Art of Adjusting Reset Account Lockout Post Failed Logins, Win 11
keywords: Master Reset Lockout,Manage Account Lockouts,Fix Login Failures,Optimize Win 11 Security,Lockout Recovery Guide,Adjusting Reset Settings,Post-Failure Access Fix
thumbnail: https://thmb.techidaily.com/a13a6e974ab2cc36089a6059bc5652aa7fea0848996089325ea48fd7dd51fd22.jpg
---

## Mastering the Art of Adjusting Reset Account Lockout Post Failed Logins, Win 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/updated-building-interactive-elements-a-guide-to-html-input-fields-for-2024/"><u>[Updated] Building Interactive Elements A Guide to HTML Input Fields for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-diving-deep-into-the-income-of-ajey-carryminati-for-2024/"><u>[Updated] Diving Deep Into the Income of Ajey (CarryMinati) for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-refine-video-creation-process-via-windows-10-photos-and-story-remix/"><u>[Updated] Refine Video Creation Process via Windows 10 Photos & Story Remix</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ridiculousrender-hub/"><u>2024 Approved RidiculousRender Hub</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-minmax-cpu-values-through-windows-menus/"><u>Deciphering Min/Max CPU Values Through Windows Menus</u></a></li>
<li><a href="https://media-tips.techidaily.com/digital-streams-surge-forward-yet-cinephiles-cherish-tangible-tributes/"><u>Digital Streams Surge Forward: Yet Cinephiles Cherish Tangible Tributes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-online-spots-for-digitized-artwork/"><u>Essential Online Spots for Digitized Artwork</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-rectify-windows-11-active-directory-printer-fails/"><u>How to Rectify Windows 11 Active Directory Printer Fails</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-oppo-a1-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Oppo A1 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-google-pixel-fold-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovating-interaction-connect-winpc-and-galaxy-phones-flow/"><u>Innovating Interaction - Connect WinPC and Galaxy Phones Flow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-methods-reopen-closed-nvidia-control-panel-windows-11/"><u>Quick Methods: Reopen Closed Nvidia Control Panel, Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamline-windows-view-overcoming-overscan-issues/"><u>Streamline Windows View: Overcoming Overscan Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/successful-execution-of-amd-195-on-your-os/"><u>Successful Execution of AMD 195 on Your OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-art-of-changing-your-home-screen-picture-on-pc/"><u>The Art of Changing Your Home Screen Picture on PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/three-easy-steps-to-remove-store-app-from-win11/"><u>Three Easy Steps to Remove Store App From Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-shadowy-taskbar-snoop-in-windows-11/"><u>Unveiling the Shadowy Taskbar Snoop in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/update-on-guilty-gear-strive-release-addressing-fan-concerns-and-expectations/"><u>Update on Guilty Gear Strive Release - Addressing Fan Concerns & Expectations</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    