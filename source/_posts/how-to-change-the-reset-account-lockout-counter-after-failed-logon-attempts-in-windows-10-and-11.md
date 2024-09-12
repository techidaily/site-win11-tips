---
title: How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11
date: 2024-09-11T01:20:43.805Z
updated: 2024-09-12T01:20:43.805Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11
excerpt: This Article Describes How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11
keywords: Windows Account Lockout Fix,Changing Reset Count,Reset Counter Reset Guide,Lockout Attempts Control,Failed Logon Counter Adjust,W10/W11 Account Changes,Increase Login Failures Limit
thumbnail: https://thmb.techidaily.com/102ab1b6aae4e1817df5a3836c10cfedb2eea5b3cb906b121a8d1c61752ad28b.jpg
---

## How to Change the Reset Account Lockout Counter After Failed Logon Attempts in Windows 10 and 11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  




<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->








<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.




<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-directing-tiktok-video-viewers-to-facebook-pages-for-2024/"><u>[New] Directing TikTok Video Viewers to Facebook Pages for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-unleashing-creativity-crafting-compelling-fb-video-campaigns/"><u>[New] Unleashing Creativity Crafting Compelling FB Video Campaigns</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-maximize-earnings-navigating-youtubes-partner-program-updates/"><u>[Updated] 2024 Approved Maximize Earnings Navigating YouTube's Partner Program Updates</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-guffaw-generator-pictorial-editor/"><u>2024 Approved Guffaw Generator Pictorial Editor</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-professional-picture-taking-within-microsoft-teams/"><u>2024 Approved Professional Picture Taking Within Microsoft Teams</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/aesthetic-and-bright-exploring-the-innovative-design-of-taotronics-tt-dl16-desk-lamp/"><u>Aesthetic and Bright: Exploring the Innovative Design of TaoTronics TT-DL16 Desk Lamp</u></a></li>
<li><a href="https://win11-tips.techidaily.com/building-an-easy-monthly-budget-using-microsoft-excel-tips-and-tricks-for-beginners/"><u>Building an Easy Monthly Budget Using Microsoft Excel – Tips and Tricks for Beginners</u></a></li>
<li><a href="https://tech-haven.techidaily.com/bypassing-the-cellular-barrier-how-to-join-chatgpt-whatsapp-and-telegram-without-your-phone-number/"><u>Bypassing the Cellular Barrier: How to Join ChatGPT, WhatsApp & Telegram without Your Phone Number</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comparing-microsoft-office-key-differences-on-windows-vs-macos-platforms/"><u>Comparing Microsoft Office: Key Differences on Windows vs macOS Platforms</u></a></li>
<li><a href="https://win11-tips.techidaily.com/comprehensive-tutorial-renaming-and-disposing-of-kindle-gadgets-via-amazons-online-portal/"><u>Comprehensive Tutorial: Renaming & Disposing of Kindle Gadgets via Amazon's Online Portal</u></a></li>
<li><a href="https://win11-tips.techidaily.com/configuring-microsoft-office-spell-checker-to-overlook-web-addresses-effortlessly/"><u>Configuring Microsoft Office Spell Checker to Overlook Web Addresses Effortlessly</u></a></li>
<li><a href="https://win11-tips.techidaily.com/discover-the-modernized-interface-of-microsoft-excels-revamped-formula-bar/"><u>Discover the Modernized Interface of Microsoft Excel's Revamped Formula Bar</u></a></li>
<li><a href="https://win11-tips.techidaily.com/easy-guide-unlocking-cell-type-ahead-with-slidebar-in-microsoft-excel/"><u>Easy Guide: Unlocking Cell Type-Ahead with Slidebar in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-guide-turning-off-microsoft-offices-security-warnings/"><u>Effective Guide: Turning Off Microsoft Office's Security Warnings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-methods-for-managing-visibility-of-sheet-tab-buttons-in-microsoft-excel/"><u>Effective Methods for Managing Visibility of Sheet Tab Buttons in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-applying-the-year-functionality-in-ms-excel-tutorials/"><u>Effective Techniques for Applying the Year Functionality in MS Excel Tutorials</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effective-techniques-for-identifying-variances-between-two-excel-datasets/"><u>Effective Techniques for Identifying Variances Between Two Excel Datasets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-lock-and-unlock-specific-rows-in-microsoft-excel-with-these-simple-tips/"><u>Efficiently Lock and Unlock Specific Rows in Microsoft Excel with These Simple Tips</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-modify-the-drop-down-selection-options-in-microsoft-excel/"><u>Efficiently Modify the Drop-Down Selection Options in Microsoft Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-total-up-multiple-excel-cells-a-comprehensive-tutorial/"><u>Efficiently Total Up Multiple Excel Cells - A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-guide-turning-excels-rows-into-columns-with-tips-and-tricks/"><u>Effortless Guide: Turning Excel's Rows Into Columns with Tips and Tricks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-comprehensive-guide-to-your-free-behringer-usb-audio-software/"><u>Effortless Installation: Comprehensive Guide to Your Free Behringer USB Audio Software</u></a></li>
<li><a href="https://win11-tips.techidaily.com/effortless-methods-how-to-populate-excel-rows-using-sequence-and-autofill-feature/"><u>Effortless Methods: How to Populate Excel Rows Using Sequence and AutoFill Feature</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-online-vs-desktop-understanding-my-preference-and-its-benefits/"><u>Excel Online Vs. Desktop: Understanding My Preference and Its Benefits</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-tricks-revealed-how-to-isolate-and-arrange-singular-entries-efficiently/"><u>Excel Tricks Revealed: How to Isolate & Arrange Singular Entries Efficiently</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-guide-tutorial-and-specific-functions-index-and-match/"><u>Excel, Guide, Tutorial, and Specific Functions INDEX and MATCH.</u></a></li>
<li><a href="https://win11-tips.techidaily.com/excel-word-and-powerpoint-go-virtual-with-latest-support-for-quest-vr-devices/"><u>Excel, Word & PowerPoint Go Virtual with Latest Support for Quest VR Devices!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-strategies-for-implementing-round-functionality-in-your-excel-spreadsheets/"><u>Expert Strategies for Implementing ROUND Functionality in Your Excel Spreadsheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/expert-tips-how-to-apply-the-rank-function-effectively-in-microsoft-excel-sheets/"><u>Expert Tips: How to Apply the RANK Function Effectively in Microsoft Excel Sheets</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-to-designing-excel-progress-trackers-using-advanced-conditional-format-rules/"><u>Guide to Designing Excel Progress Trackers Using Advanced Conditional Format Rules</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guide-locating-and-displaying-every-named-range-within-your-excel-spreadsheet/"><u>Guide: Locating and Displaying Every Named Range Within Your Excel Spreadsheet</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-does-compatibility-mode-work-within-the-microsoft-office-suite-exploring-its-functions-and-uses/"><u>How Does Compatibility Mode Work Within the Microsoft Office Suite? Exploring Its Functions and Uses</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-microsoft-office-2011-transforms-mac-workflows-with-a-fresh-take-on-the-infamous-tps-report-task/"><u>How Microsoft Office 2011 Transforms Mac Workflows with a Fresh Take on the Infamous TPS Report Task</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-or-deactivate-the-insert-sparkline-toolbar-icon-in-excel-tutorial/"><u>How to Hide or Deactivate the Insert Sparkline Toolbar Icon in Excel Tutorial</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-lava-blaze-curve-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-nokia-105-classic-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Nokia 105 Classic to PC? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/master-the-art-of-data-conversion-tips-for-turning-json-files-into-microsoft-excel-documents/"><u>Master the Art of Data Conversion: Tips for Turning JSON Files Into Microsoft Excel Documents</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cell-management-a-step-by-step-guide-to-combining-and-separating-cells-in-excel/"><u>Mastering Cell Management: A Step-by-Step Guide to Combining and Separating Cells in Excel</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-cell-replication-a-comprehensive-tutorial-on-cloning-formulas-in-excel/"><u>Mastering Cell Replication: A Comprehensive Tutorial on Cloning Formulas in Excel</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-chatgpt-in-google-spreadsheets-and-documents/"><u>Mastering ChatGPT in Google Spreadsheets & Documents</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/optimizing-audio-clarity-in-home-vo-recording-setups-for-2024/"><u>Optimizing Audio Clarity in Home VO Recording Setups for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/review-of-the-petsafe-automatic-pet-feeder-a-key-tool-for-managing-your-pets-diet/"><u>Review of the PetSafe Automatic Pet Feeder: A Key Tool for Managing Your Pet's Diet</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-best-portable-player-in-sound-a35/"><u>The Best Portable Player in Sound, A35</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-apps-and-online-tools-to-track-xiaomi-redmi-12-5g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Xiaomi Redmi 12 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://buynow-info.techidaily.com/trustworthy-reviews-on-the-ergohead-cushioned-desk-mat-enhancing-comfort-while-working/"><u>Trustworthy Reviews on the Ergohead Cushioned Desk Mat - Enhancing Comfort While Working</u></a></li>
<li><a href="https://extra-information.techidaily.com/whimsical-words-in-motion-animated-captions-for-ig-stories/"><u>Whimsical Words in Motion Animated Captions for IG Stories</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>